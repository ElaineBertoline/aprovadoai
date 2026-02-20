🚀 Aprovado AI - Portal de Estudos Inteligente
O Aprovado AI é uma plataforma SaaS (Software as a Service) desenvolvida para otimizar a preparação de candidatos para concursos públicos. Utilizando Inteligência Artificial de última geração, o sistema analisa editais e gera mini-simulados personalizados com gabaritos comentados.

🛠️ Tecnologias Utilizadas
O projeto utiliza uma arquitetura moderna e "serverless", garantindo velocidade e baixo custo de manutenção:

Frontend: HTML5, CSS3 (Modern Dark Mode) e JavaScript (ES6+).

Inteligência Artificial: Google Gemini API (Modelos Gemini 1.5 Flash / Gemini 3.0).

Backend & Banco de Dados: Google Apps Script integrado ao Google Sheets.

Hospedagem: GitHub Pages.

Integração de Dados: API REST via JSON para comunicação entre Frontend e Planilha.

🌟 Funcionalidades Principais
Análise de Edital por IA: O sistema identifica as disciplinas relevantes a partir do cargo e banca informados.

Geração de Questões Comentadas: Criação de 02 questões inéditas de múltipla escolha por ciclo, com explicações didáticas para cada alternativa.

Controle de Acesso (Login): Validação em tempo real de e-mails autorizados via base de dados no Google Sheets.

Registro de Desempenho: Armazenamento automático do histórico de questões por candidato e concurso na nuvem.

Interface Responsiva: Design otimizado para estudos via desktop, tablet ou smartphone.

📋 Como o Sistema Funciona
Autenticação: O aluno insere o e-mail cadastrado.

Entrada de Dados: O aluno informa o Cargo, Concurso e Organizadora (ex: Analista de Sistemas - FAPESP / 2026 - Vunesp).

Processamento: A IA Gemini processa o pedido e gera as questões com comentários.

Armazenamento: Ao clicar em "Salvar", os dados são enviados via POST para o Google Apps Script, que organiza as informações em colunas (Data, Candidato, Concurso e Conteúdo).

📂 Estrutura da Base de Dados (Google Sheets)
A aplicação gerencia duas bases principais:

utilizadores: Controle de licenças e acesso.

questoes: Registro detalhado de toda a atividade de estudo, permitindo auditoria e acompanhamento de progresso.

👤 Desenvolvedora
Elaine Bertoline

Gestora de Tráfego Pago 📊

Desenvolvedora de Sites Profissionais 💻

Estrategista em Automações com IA da AlvesDibo
