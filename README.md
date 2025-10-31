<!DOCTYPE html>
<html lang="pt-BR">
<head>  
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz ENEM - Geometria Espacial</title>

    <style>
        body {
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 50%, #1d4ed8 100%);
            min-height: 100%;
            color: #1f2937;
            line-height: 1.5;
            font-size: 14px;
        }
        html { height: 100%; }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(59, 130, 246, 0.2);
            padding: 20px 0;
            margin-bottom: 40px;
        }
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .logo { display: flex; align-items: center; gap: 12px; }
        .logo-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, #3b82f6, #1d4ed8);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 20px;
        }
        h1 {
            font-size: 1.5rem;
            font-weight: 700;
            color: #1e40af;
            margin: 0;
        }
        .subtitle {
            font-size: 0.9rem;
            color: #6b7280;
            margin: 0;
        }
        .nav-tabs {
            display: flex;
            gap: 8px;
            background: rgba(255, 255, 255, 0.95);
            padding: 8px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(59, 130, 246, 0.2);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        .tab-button {
            background: transparent;
            color: #4b5563;
            border: 1px solid transparent;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.9rem;
            font-weight: 500;
            transition: all 0.2s ease;
            white-space: nowrap;
        }
        .tab-button:hover {
            background: rgba(59, 130, 246, 0.1);
            color: #1e40af;
            border-color: rgba(59, 130, 246, 0.3);
        }
        .tab-button.active {
            background: #3b82f6;
            color: white;
            font-weight: 600;
            box-shadow: 0 2px 8px rgba(59, 130, 246, 0.3);
            border-color: #2563eb;
        }
        .content-section {
            display: none;
            background: white;
            border-radius: 16px;
            padding: 40px;
            box-shadow: 0 4px 24px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
        }
        .content-section.active { display: block; }

        /* ... (mantive todo o CSS igual) ... */
        
        @keyframes rotate {
            0% { transform: rotateX(-15deg) rotateY(25deg); }
            25% { transform: rotateX(-15deg) rotateY(115deg); }
            50% { transform: rotateX(-15deg) rotateY(205deg); }
            75% { transform: rotateX(-15deg) rotateY(295deg); }
            100% { transform: rotateX(-15deg) rotateY(385deg); }
        }

        @media (max-width: 768px) {
            .container { padding: 0 15px; }
            .header-content { flex-direction: column; text-align: center; }
            .nav-tabs { flex-wrap: wrap; justify-content: center; }
            .content-section { padding: 24px; }
            .score-panel { flex-direction: column; text-align: center; }
            .question-meta { flex-direction: column; align-items: flex-start; }
        }
    </style>
</head>
<body>
    <!-- o corpo do HTML está correto -->
    <!-- ... (mantém igual ao que você mandou) ... -->
    
    <script>
        let userAnswers = {};              
        let answeredQuestions = new Set(); 
        let correctCount = 0;
        const totalQuestions = 5;

        function showTab(tabName, element) {
            document.querySelectorAll('.tab-button').forEach(btn => btn.classList.remove('active'));
            document.querySelectorAll('.content-section').forEach(sec => sec.classList.remove('active'));
            if (element) element.classList.add('active');
            const targetSection = document.getElementById(tabName);
            if (targetSection) targetSection.classList.add('active');
        }

        function selectOption(element, questionNum, isCorrect) {
            if (!element) return;
            const optionsGrid = element.closest('.options-grid');
            const questionContainer = element.closest('.question-container');
            if (!optionsGrid || !questionContainer) return;
            optionsGrid.querySelectorAll('.option-button').forEach(opt => opt.classList.remove('selected'));
            element.classList.add('selected');
            userAnswers[questionNum] = !!isCorrect;
            const checkBtn = questionContainer.querySelector('.check-button');
            if (checkBtn) checkBtn.disabled = false;
        }

        function checkAnswer(questionNum) {
            if (answeredQuestions.has(questionNum)) return;
            const optionsGrid = document.querySelector(`.options-grid[data-question="${questionNum}"]`);
            if (!optionsGrid) return;
            const questionContainer = optionsGrid.closest('.question-container');
            const explanationBox = questionContainer.querySelector('.explanation-box');
            const correct = userAnswers[questionNum];
            
            optionsGrid.querySelectorAll('.option-button').forEach(btn => {
                btn.classList.remove('correct', 'incorrect');
            });

            const selected = optionsGrid.querySelector('.selected');
            if (selected) {
                if (correct) {
                    selected.classList.add('correct');
                    correctCount++;
                } else {
                    selected.classList.add('incorrect');
                }
            }

            if (explanationBox) explanationBox.classList.add('show');
            answeredQuestions.add(questionNum);

            const scoreDisplay = document.getElementById('score-display');
            if (scoreDisplay) {
                scoreDisplay.textContent = `Progresso: ${answeredQuestions.size}/${totalQuestions} questões respondidas`;
            }
        }

        function resetQuiz() {
            userAnswers = {};
            answeredQuestions.clear();
            correctCount = 0;
            document.querySelectorAll('.option-button').forEach(btn => {
                btn.classList.remove('selected', 'correct', 'incorrect');
            });
            document.querySelectorAll('.check-button').forEach(btn => btn.disabled = true);
            document.querySelectorAll('.explanation-box').forEach(box => box.classList.remove('show'));
            const scoreDisplay = document.getElementById('score-display');
            if (scoreDisplay) scoreDisplay.textContent = `Progresso: 0/${totalQuestions} questões respondidas`;
        }
    </script>
</body>
</html>
