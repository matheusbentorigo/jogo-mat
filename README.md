
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

        .section-title {
            font-size: 1.6rem;
            font-weight: 700;
            color: #1e40af;
            margin-bottom: 30px;
            border-bottom: 3px solid #e5e7eb;
            padding-bottom: 15px;
        }

        .enem-info {
            background: linear-gradient(135deg, #1e40af, #3b82f6);
            color: white;
            padding: 24px;
            border-radius: 12px;
            margin-bottom: 30px;
            text-align: center;
        }

        .enem-info h3 { margin: 0 0 10px 0; font-size: 1.5rem; }
        .enem-info p { margin: 0; opacity: 0.9; }

        .quiz-container { max-width: 900px; margin: 0 auto; }

        .score-panel {
            background: linear-gradient(135deg, #1e40af, #3b82f6);
            color: white;
            padding: 24px;
            border-radius: 12px;
            text-align: center;
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .score-text { font-size: 1.2rem; font-weight: 600; }

        .reset-button {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 500;
            transition: background 0.2s ease;
        }

        .reset-button:hover { background: rgba(255, 255, 255, 0.3); }

        .question-container {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 12px;
            padding: 30px;
            margin-bottom: 30px;
            position: relative;
        }

        .enem-badge {
            position: absolute;
            top: -12px;
            right: 20px;
            background: #dc2626;
            color: white;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
        }

        .question-header { margin-bottom: 25px; }

        .question-meta {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 15px;
            flex-wrap: wrap;
        }

        .question-number {
            background: #3b82f6;
            color: white;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.1rem;
        }

        .question-info {
            background: #e0f2fe;
            color: #0277bd;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 500;
        }

        .question-text {
            font-size: 0.95rem;
            color: #1f2937;
            margin: 20px 0;
            line-height: 1.6;
        }

        .figure-container {
            background: white;
            border: 2px solid #e5e7eb;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }

        .figure-title { font-weight: 600; color: #374151; margin-bottom: 15px; }

        .shape-display {
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 20px 0;
        }

        .view-item { text-align: center; }

        .view-shape {
            width: 80px;
            height: 80px;
            border: 2px solid #1e40af;
            margin: 10px auto;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: #1e40af;
            background: rgba(59, 130, 246, 0.1);
        }

        .pyramid-shape {
            width: 0;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 60px solid #3b82f6;
            margin: 20px auto;
        }

        .options-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 12px;
            margin: 24px 0;
        }

        .option-button {
            background: white;
            border: 2px solid #e5e7eb;
            border-radius: 8px;
            padding: 12px;
            cursor: pointer;
            transition: all 0.2s ease;
            text-align: center;
            font-size: 0.85rem;
            min-height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .option-button:hover { border-color: #3b82f6; background: #f0f9ff; }

        .option-button.selected { border-color: #3b82f6; background: #dbeafe; color: #1e40af; font-weight: 500; }
        .option-button.correct { border-color: #10b981; background: #d1fae5; color: #065f46; }
        .option-button.incorrect { border-color: #ef4444; background: #fee2e2; color: #991b1b; }

        .check-button {
            background: #3b82f6;
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 500;
            font-size: 1rem;
            transition: background 0.2s ease;
        }

        .check-button:hover:not(:disabled) { background: #2563eb; }
        .check-button:disabled { background: #9ca3af; cursor: not-allowed; }

        .explanation-box {
            background: #eff6ff;
            border: 1px solid #bfdbfe;
            border-left: 4px solid #3b82f6;
            border-radius: 8px;
            padding: 20px;
            margin-top: 20px;
            display: none;
        }

        .explanation-box.show { display: block; }
        .explanation-box strong { color: #1e40af; }

        .difficulty-indicator { display: flex; align-items: center; gap: 8px; margin: 10px 0; }
        .difficulty-dot { width: 8px; height: 8px; border-radius: 50%; background: #d1d5db; }
        .difficulty-dot.filled { background: #f59e0b; }

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
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <div class="logo-icon">📐</div>
                    <div>
                        <h1>ENEM - Geometria Espacial</h1>
                        <p class="subtitle">Projeções e Vistas Ortogonais</p>
                    </div>
                </div>
                <nav class="nav-tabs" role="navigation" aria-label="Abas">
                    <button class="tab-button active" onclick="showTab('theory', this)" type="button">Teoria e Conceitos</button>
                    <button class="tab-button" onclick="showTab('quiz', this)" type="button">Questões ENEM</button>
                </nav>
            </div>
        </div>
    </header>

    <div class="container">
        <main>
            <section id="theory" class="content-section active">
                <h2 class="section-title">Projeções e Vistas Ortogonais</h2>

                <div class="enem-info">
                    <h3>📐 Fundamentos da Geometria Espacial</h3>
                    <p>Compreenda os conceitos essenciais de projeções ortogonais e vistas técnicas</p>
                </div>

                <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; border-left: 4px solid #3b82f6; margin-bottom: 30px;">
                    <h3 style="color: #1e40af; margin-top: 0; margin-bottom: 16px;">O que são Projeções Ortogonais?</h3>
                    <p style="color: #4b5563; margin-bottom: 16px;">As projeções ortogonais são representações 2D de objetos 3D obtidas através da projeção perpendicular sobre planos de referência.</p>
                    <p style="color: #4b5563;"><strong>Três vistas principais:</strong> Frontal, Superior e Lateral</p>
                </div>

                <div style="background: #f1f5f9; border-radius: 12px; padding: 32px; margin: 24px 0; border: 1px solid #cbd5e1;">
                    <h3 style="font-size: 1.5rem; font-weight: 600; color: #1e40af; margin-bottom: 20px; text-align: center;">Demonstração Interativa - Cubo</h3>
                    <p style="text-align: center; color: #6b7280; margin-bottom: 30px;">
                        Observe a rotação do objeto 3D e suas respectivas projeções ortogonais
                    </p>

                    <div style="display: flex; justify-content: center; align-items: center; margin: 30px 0;">
                        <div style="perspective: 1000px; margin: 0 40px;">
                            <div style="width: 100px; height: 100px; position: relative; transform-style: preserve-3d; transform: rotateX(-15deg) rotateY(25deg); animation: rotate 8s infinite linear;">
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.8); transform: translateZ(50px);">Frontal</div>
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.6); transform: rotateY(180deg) translateZ(50px);">Posterior</div>
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.7); transform: rotateY(90deg) translateZ(50px);">Direita</div>
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.5); transform: rotateY(-90deg) translateZ(50px);">Esquerda</div>
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.9); transform: rotateX(90deg) translateZ(50px);">Superior</div>
                                <div style="position: absolute; width: 100px; height: 100px; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; font-size: 14px; background: rgba(59, 130, 246, 0.4); transform: rotateX(-90deg) translateZ(50px);">Inferior</div>
                            </div>
                        </div>
                    </div>

                    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 30px;">
                        <div style="background: white; border: 2px solid #cbd5e1; border-radius: 10px; padding: 20px; text-align: center; transition: border-color 0.2s ease;">
                            <h4 style="color: #1e40af; margin-bottom: 15px; font-weight: 600;">Vista Frontal</h4>
                            <div style="width: 80px; height: 80px; margin: 15px auto; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; background: rgba(59, 130, 246, 0.2);">□</div>
                            <p><strong>Forma:</strong> Quadrado<br><strong>Dimensões:</strong> a × a</p>
                        </div>
                        <div style="background: white; border: 2px solid #cbd5e1; border-radius: 10px; padding: 20px; text-align: center; transition: border-color 0.2s ease;">
                            <h4 style="color: #1e40af; margin-bottom: 15px; font-weight: 600;">Vista Superior</h4>
                            <div style="width: 80px; height: 80px; margin: 15px auto; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; background: rgba(59, 130, 246, 0.3);">□</div>
                            <p><strong>Forma:</strong> Quadrado<br><strong>Dimensões:</strong> a × a</p>
                        </div>
                        <div style="background: white; border: 2px solid #cbd5e1; border-radius: 10px; padding: 20px; text-align: center; transition: border-color 0.2s ease;">
                            <h4 style="color: #1e40af; margin-bottom: 15px; font-weight: 600;">Vista Lateral</h4>
                            <div style="width: 80px; height: 80px; margin: 15px auto; border: 2px solid #1e40af; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #1e40af; background: rgba(59, 130, 246, 0.25);">□</div>
                            <p><strong>Forma:</strong> Quadrado<br><strong>Dimensões:</strong> a × a</p>
                        </div>
                    </div>
                </div>

                <div style="background: #fef3c7; border: 1px solid #f59e0b; border-radius: 12px; padding: 20px;">
                    <h4 style="color: #92400e; margin-top: 0;">💡 Dica para o ENEM:</h4>
                    <p style="color: #92400e; margin: 0;">Para resolver questões de projeções no ENEM, sempre identifique primeiro qual vista está sendo solicitada (frontal, superior ou lateral) e imagine como o objeto apareceria quando visto daquela direção específica. Lembre-se: a vista superior mostra a "pegada" do objeto no chão!</p>
                </div>
            </section>

            <section id="quiz" class="content-section">
                <div class="quiz-container">
                    <h2 class="section-title">Questões do ENEM</h2>

                    <div class="enem-info">
                        <h3>🎯 Teste seus Conhecimentos</h3>
                        <p>Questões selecionadas dos últimos anos do ENEM sobre projeções ortogonais e vistas</p>
                    </div>

                    <div class="score-panel">
                        <div class="score-text" id="score-display">Progresso: 0/5 questões respondidas</div>
                        <button class="reset-button" onclick="resetQuiz()" type="button">Reiniciar Teste</button>
                    </div>

                    <!-- Questão 1 - ENEM 2019 -->
                    <div class="question-container" data-q="1">
                        <div class="enem-badge">ENEM 2019</div>
                        <div class="question-header">
                            <div class="question-meta">
                                <div class="question-number">1</div>
                                <div class="question-info">Prova Azul - Questão 154</div>
                                <div class="question-info">Competência 2 - H7</div>
                            </div>
                            <div class="difficulty-indicator">
                                <span style="font-size: 0.9rem; color: #6b7280;">Dificuldade:</span>
                                <div class="difficulty-dot filled"></div>
                                <div class="difficulty-dot filled"></div>
                                <div class="difficulty-dot"></div>
                                <div class="difficulty-dot"></div>
                                <div class="difficulty-dot"></div>
                                <span style="font-size: 0.8rem; color: #6b7280;">Média</span>
                            </div>
                        </div>

                        <div class="question-text">
                            Um arquiteto está projetando um monumento que terá a forma de uma pirâmide de base quadrada. Para apresentar o projeto, ele precisa desenhar as vistas ortogonais principais da pirâmide.

                            <div class="figure-container">
                                <div class="figure-title">Pirâmide de base quadrada</div>
                                <div class="shape-display">
                                    <div class="view-item">
                                        <div class="pyramid-shape"></div>
                                        <p><strong>Objeto 3D</strong></p>
                                    </div>
                                </div>
                            </div>

                            Considerando que a pirâmide está apoiada sobre sua base, qual será a forma da vista superior?
                        </div>

                        <div class="options-grid" data-question="1">
                            <div class="option-button" onclick="selectOption(this, 1, false)" role="button" tabindex="0">
                                Triângulo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 1, true)" role="button" tabindex="0">
                                Quadrado
                            </div>
                            <div class="option-button" onclick="selectOption(this, 1, false)" role="button" tabindex="0">
                                Círculo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 1, false)" role="button" tabindex="0">
                                Retângulo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 1, false)" role="button" tabindex="0">
                                Losango
                            </div>
                        </div>
                        <button class="check-button" onclick="checkAnswer(1)" disabled type="button">Verificar Resposta</button>
                        <div class="explanation-box" id="explanation-1">
                            <strong>Resposta Correta: B) Quadrado</strong><br><br>
                            <strong>Resolução:</strong> A vista superior de uma pirâmide de base quadrada mostra exatamente a forma da base, que é um quadrado. Quando olhamos de cima para baixo, vemos apenas a projeção da base quadrada, independentemente da altura da pirâmide.<br><br>
                            <strong>Competência ENEM:</strong> Utilizar conhecimentos geométricos de espaço e forma na seleção de argumentos propostos como solução de problemas do cotidiano.
                        </div>
                    </div>

                    <!-- Questão 2 - ENEM 2018 -->
                    <div class="question-container" data-q="2">
                        <div class="enem-badge">ENEM 2018</div>
                        <div class="question-header">
                            <div class="question-meta">
                                <div class="question-number">2</div>
                                <div class="question-info">Prova Rosa - Questão 139</div>
                            </div>
                        </div>

                        <div class="question-text">
                            Uma mesa tem tampo retangular e quatro pés cilíndricos idênticos. Na vista superior da mesa, o que será visualizado?
                        </div>

                        <div class="options-grid" data-question="2">
                            <div class="option-button" onclick="selectOption(this, 2, true)" role="button" tabindex="0">
                                Retângulo com quatro círculos nos cantos
                            </div>
                            <div class="option-button" onclick="selectOption(this, 2, false)" role="button" tabindex="0">
                                Apenas um retângulo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 2, false)" role="button" tabindex="0">
                                Quatro círculos separados
                            </div>
                        </div>
                        <button class="check-button" onclick="checkAnswer(2)" disabled type="button">Verificar Resposta</button>
                        <div class="explanation-box" id="explanation-2">
                            <strong>Resposta Correta: A) Retângulo com quatro círculos nos cantos</strong><br><br>
                            <strong>Resolução:</strong> Na vista superior, vemos o tampo retangular da mesa e a seção circular dos quatro pés cilíndricos.
                        </div>
                    </div>

                    <!-- Questão 3 - ENEM 2020 -->
                    <div class="question-container" data-q="3">
                        <div class="enem-badge">ENEM 2020</div>
                        <div class="question-header">
                            <div class="question-meta">
                                <div class="question-number">3</div>
                                <div class="question-info">Prova Cinza - Questão 162</div>
                            </div>
                        </div>

                        <div class="question-text">
                            Um engenheiro precisa analisar a estrutura de uma peça mecânica que tem a forma de um prisma triangular regular. A peça está posicionada com uma de suas faces triangulares apoiada no chão.

                            Quantas vistas ortogonais diferentes são necessárias para representar completamente este prisma?
                        </div>

                        <div class="options-grid" data-question="3">
                            <div class="option-button" onclick="selectOption(this, 3, false)" role="button" tabindex="0">
                                1 vista
                            </div>
                            <div class="option-button" onclick="selectOption(this, 3, false)" role="button" tabindex="0">
                                2 vistas
                            </div>
                            <div class="option-button" onclick="selectOption(this, 3, true)" role="button" tabindex="0">
                                3 vistas
                            </div>
                            <div class="option-button" onclick="selectOption(this, 3, false)" role="button" tabindex="0">
                                4 vistas
                            </div>
                        </div>
                        <button class="check-button" onclick="checkAnswer(3)" disabled type="button">Verificar Resposta</button>
                        <div class="explanation-box" id="explanation-3">
                            <strong>Resposta Correta: C) 3 vistas</strong><br><br>
                            <strong>Resolução:</strong> Para qualquer objeto tridimensional, são necessárias três vistas ortogonais principais para representação completa: frontal, superior e lateral.
                        </div>
                    </div>

                    <!-- Questão 4 - ENEM 2017 -->
                    <div class="question-container" data-q="4">
                        <div class="enem-badge">ENEM 2017</div>
                        <div class="question-header">
                            <div class="question-meta">
                                <div class="question-number">4</div>
                                <div class="question-info">Prova Branca - Questão 148</div>
                            </div>
                        </div>

                        <div class="question-text">
                            Um artesão está criando um objeto decorativo que consiste em uma esfera apoiada sobre um cubo. Para documentar seu trabalho, ele precisa desenhar as vistas ortogonais do conjunto.

                            Como aparecerá a vista superior deste conjunto?
                        </div>

                        <div class="options-grid" data-question="4">
                            <div class="option-button" onclick="selectOption(this, 4, false)" role="button" tabindex="0">
                                Apenas um quadrado
                            </div>
                            <div class="option-button" onclick="selectOption(this, 4, false)" role="button" tabindex="0">
                                Apenas um círculo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 4, true)" role="button" tabindex="0">
                                Um círculo sobreposto a um quadrado
                            </div>
                            <div class="option-button" onclick="selectOption(this, 4, false)" role="button" tabindex="0">
                                Um círculo ao lado de um quadrado
                            </div>
                        </div>
                        <button class="check-button" onclick="checkAnswer(4)" disabled type="button">Verificar Resposta</button>
                        <div class="explanation-box" id="explanation-4">
                            <strong>Resposta Correta: C) Um círculo sobreposto a um quadrado</strong><br><br>
                            <strong>Resolução:</strong> Na vista superior, vemos a projeção da base quadrada do cubo e a projeção circular da esfera. Como a esfera está apoiada sobre o cubo, suas projeções se sobrepõem.
                        </div>
                    </div>

                    <!-- Questão 5 - ENEM 2021 -->
                    <div class="question-container" data-q="5">
                        <div class="enem-badge">ENEM 2021</div>
                        <div class="question-header">
                            <div class="question-meta">
                                <div class="question-number">5</div>
                                <div class="question-info">Prova Amarela - Questão 156</div>
                            </div>
                        </div>

                        <div class="question-text">
                            Um designer de produtos está criando um suporte para livros que consiste em dois prismas triangulares idênticos posicionados nas extremidades de uma base retangular, formando um "A" quando visto de frente.

                            Qual será a forma da vista superior deste suporte?
                        </div>

                        <div class="options-grid" data-question="5">
                            <div class="option-button" onclick="selectOption(this, 5, true)" role="button" tabindex="0">
                                Retângulo com dois triângulos nas extremidades
                            </div>
                            <div class="option-button" onclick="selectOption(this, 5, false)" role="button" tabindex="0">
                                Apenas um retângulo
                            </div>
                            <div class="option-button" onclick="selectOption(this, 5, false)" role="button" tabindex="0">
                                Dois triângulos separados
                            </div>
                            <div class="option-button" onclick="selectOption(this, 5, false)" role="button" tabindex="0">
                                Formato de "A"
                            </div>
                        </div>
                        <button class="check-button" onclick="checkAnswer(5)" disabled type="button">Verificar Resposta</button>
                        <div class="explanation-box" id="explanation-5">
                            <strong>Resposta Correta: A) Retângulo com dois triângulos nas extremidades</strong><br><br>
                            <strong>Resolução:</strong> Na vista superior, vemos a projeção da base retangular e as projeções triangulares dos dois prismas triangulares posicionados nas extremidades.
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </div>

    <script>
        // Estatísticas e metadados (opcionais/meramente informativos)
        // Linhas e contagem foram removidas ou ajustadas para evitar dados incorretos.
        let userAnswers = {};              // { questionNum: boolean(isCorrect) }
        let answeredQuestions = new Set(); // conjunto de números respondidos
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
            // encontra o grid de opções e o container da questão (mais robusto)
            const optionsGrid = element.closest('.options-grid');
            const questionContainer = element.closest('.question-container');

            if (!optionsGrid || !questionContainer) return;

            // remove seleção anterior
            optionsGrid.querySelectorAll('.option-button').forEach(opt => opt.classList.remove('selected'));

            // marca atual
            element.classList.add('selected');

            // grava resposta (somente se selecionar)
            userAnswers[questionNum] = !!isCorrect;

            // habilita o botão de verificação daquela questão
            const checkBtn = questionContainer.querySelector('.check-button');
            if (checkBtn) checkBtn.disabled = false;
        }

        function checkAnswer(questionNum) {
            // evita dupla verificação
            if (answeredQuestions.has(questionNum)) return;

            const optionsGrid = document.querySelector(`.options-grid[data-question="${questionNum}"]`);
            if (!optionsGrid) return;

            const questionContainer = optionsGrid.closest('.question-container');
            if (!questionContainer) return;

            const questionOptions = optionsGrid.querySelectorAll('.option-button');
            const isCorrect = !!userAnswers[questionNum];

            // marca opções como corretas/incorretas visualmente
            questionOptions.forEach(option => {
                if (option.classList.contains('selected')) {
                    if (isCorrect) {
                        option.classList.add('correct');
                        correctCount++;
                    } else {
                        option.classList.add('incorrect');
                    }
                }
            });

            // mostra explicação
            const explanation = document.getElementById(`explanation-${questionNum}`);
            if (explanation) explanation.classList.add('show');

            // atualiza botão de verificação desta questão
            const checkBtn = questionContainer.querySelector('.check-button');
            if (checkBtn) {
                checkBtn.disabled = true;
                checkBtn.textContent = isCorrect ? '✓ Correto' : '✗ Incorreto';
                // estiliza inline apenas para feedback visual imediato
                checkBtn.style.background = isCorrect ? '#10b981' : '#ef4444';
            }

            // marca respondido e atualiza score
            answeredQuestions.add(questionNum);
            updateScore();
        }

        function updateScore() {
            const scoreElement = document.getElementById('score-display');
            const answeredCount = answeredQuestions.size;
            const percentage = answeredCount > 0 ? Math.round((correctCount / answeredCount) * 100) : 0;

            if (answeredCount === totalQuestions) {
                let performance = '';
                if (percentage >= 80) performance = '🏆 Excelente!';
                else if (percentage >= 60) performance = '👍 Bom desempenho!';
                else if (percentage >= 40) performance = '📚 Continue estudando!';
                else performance = '💪 Precisa revisar!';

                scoreElement.textContent = `${performance} ${correctCount}/${totalQuestions} (${percentage}%)`;
            } else {
                scoreElement.textContent = `Progresso: ${answeredCount}/${totalQuestions} questões (${correctCount} corretas)`;
            }
        }

        function resetQuiz() {
            userAnswers = {};
            answeredQuestions = new Set(); // recria o set para evitar efeitos colaterais
            correctCount = 0;

            document.querySelectorAll('.option-button').forEach(option => {
                option.classList.remove('selected', 'correct', 'incorrect');
            });

            document.querySelectorAll('.check-button').forEach(btn => {
                btn.disabled = true;
                btn.textContent = 'Verificar Resposta';
                btn.style.background = ''; // remove estilo inline
            });

            document.querySelectorAll('.explanation-box').forEach(exp => {
                exp.classList.remove('show');
            });

            document.getElementById('score-display').textContent = 'Progresso: 0/5 questões respondidas';
        }

        // Inicialização: deixa todos os check-buttons desabilitados até que alguma opção seja escolhida
        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('.check-button').forEach(btn => btn.disabled = true);

            // acessibilidade: permitir seleção por teclado (Enter / Space)
            document.querySelectorAll('.option-button').forEach(opt => {
                opt.addEventListener('keydown', (e) => {
                    if (e.key === 'Enter' || e.key === ' ') {
                        e.preventDefault();
                        opt.click();
                    }
                });
            });
        });
    </script>

    <!-- Observação: scripts injetados/externos foram removidos por segurança. -->
</body>
</html>
