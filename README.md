# Pedro Victor Guimarães

**Desenvolvedor Back-end | Java · Spring Boot · Ruby on Rails**

Sou desenvolvedor em Belo Horizonte, com experiência em aplicações web com **Ruby on Rails** e projetos em **Java/Spring Boot**, **React** e **inteligência artificial aplicada**. Construo marketplaces, APIs REST e automações, com atenção às regras de negócio, à modelagem de dados e aos testes.

Graduando em **Análise e Desenvolvimento de Sistemas na UniCesumar** e formado no **bootcamp Full Stack do Le Wagon**. Minha trajetória anterior em gestão e vendas contribui para conectar decisões técnicas às necessidades do negócio.

### 🔗 Contatos
* **Portfólio:** [peuvictor.github.io](https://peuvictor.github.io/)
* **LinkedIn:** [in/pedro-guimaraes-dev](https://www.linkedin.com/in/pedro-guimaraes-dev/)
* **Email:** [peuvictor22@gmail.com](mailto:peuvictor22@gmail.com)

### 💻 Tecnologias e áreas de atuação

| Área | Tecnologias |
| --- | --- |
| Back-end | Java, Spring Boot, Ruby, Ruby on Rails, APIs REST |
| Front-end | JavaScript, React, HTML, CSS, Tailwind CSS, Bootstrap, Turbo e Stimulus |
| Dados | PostgreSQL, MySQL, SQL, Active Record e Spring Data JPA |
| Qualidade | TDD, JUnit 5, Mockito, Testcontainers e Minitest |
| Infraestrutura | Docker, GitHub Actions, Sidekiq, Redis, Render e estudos em Azure/Serverless |
| IA e integrações | Spring AI, Google Gemini, OpenAI API, engenharia de prompts e web scraping com Nokogiri |

### 🚀 Projetos em Ruby on Rails

#### 💈 [BH Agendamentos](https://github.com/Peuvictor/bh_agendamentos)

Marketplace de serviços e agendamentos para profissionais independentes e negócios locais de Belo Horizonte. Reúne clientes, prestadores e administradores em uma aplicação com regras de agenda e integração de pagamentos.

- **Agenda:** disponibilidade por duração do serviço, múltiplos turnos, bloqueios de horários, calendário e reagendamento com histórico.
- **Pagamentos:** integração com Mercado Pago para cartão e PIX, webhooks assinados e processamento idempotente.
- **Gestão:** catálogo de serviços com fotos, avaliações, dashboard financeiro e moderação administrativa.
- **Qualidade:** testes com Minitest e Selenium, análise com RuboCop e integração contínua no GitHub Actions.
- **Tecnologias:** Ruby, Rails 7.1, PostgreSQL, Devise, Turbo, Stimulus, Tailwind CSS, Sidekiq, Redis, Active Storage e Docker.

[Ver código](https://github.com/Peuvictor/bh_agendamentos) · [Demonstração — pagamentos em sandbox](https://bh-agendamentos.onrender.com/)

#### 🥗 [Alter Snack](https://github.com/MatEstevam/altersnack)

Participei do desenvolvimento Full Stack de uma plataforma de venda de alimentos e produtos para pessoas com restrições alimentares, com proposta semelhante à de um marketplace de delivery.

**Atuação:** desenvolvedor web remoto, de abril a agosto de 2024.

- **Catálogo:** restaurantes e produtos organizados em uma aplicação web.
- **Compras:** carrinho com alteração de quantidades e remoção de produtos, criação e consulta de pedidos.
- **Receitas com IA:** integração com a API da OpenAI para gerar sugestões a partir de ingredientes, visualizar o resultado e salvar receitas na conta do usuário.
- **Pagamentos:** integração com Stripe e estrutura de recebimento de eventos por webhooks.
- **Acesso:** autenticação com Devise e autorização com Pundit.
- **Tecnologias:** Ruby, Rails 7.1, PostgreSQL, JavaScript, Bootstrap, Turbo, Stimulus, Devise, Pundit, Cloudinary, Stripe e ruby-openai.

[Ver código](https://github.com/MatEstevam/altersnack)

#### 👕 [FutWear](https://github.com/Peuvictor/rails-marketplace)

Marketplace de camisas de futebol, desenvolvida com Ruby on Rails e PostgreSQL para praticar a construção de uma experiência de compra e venda.

- **Catálogo e anúncios:** estrutura para listar, consultar, cadastrar, editar e excluir camisetas.
- **Compras:** rotas para compra de produtos, gerenciamento de pedidos e checkout.
- **Usuários:** autenticação com Devise e páginas de perfil.
- **Conceitos trabalhados:** arquitetura MVC, rotas REST e persistência com Active Record.
- **Tecnologias:** Ruby, Rails 7.1, PostgreSQL, JavaScript, Bootstrap, Turbo, Stimulus, Devise, pg_search e Cloudinary.

[Ver código](https://github.com/Peuvictor/rails-marketplace)

#### 📚 Estudos e prática com Rails

| Projeto | Foco |
| --- | --- |
| [Watch List](https://github.com/Peuvictor/rails-watch-list) | Listas de filmes e bookmarks, com rotas aninhadas para organizar os recursos. |
| [Wikinimous](https://github.com/Peuvictor/rails-wikinimous) | Recurso de artigos com rotas REST para praticar a estrutura de uma aplicação Rails. |

### ☕ Projetos em Java e Spring Boot

#### 🎙️ [DIO Budgeting Gemini](https://github.com/Peuvictor/dio-budgeting-gemini)

Assistente financeiro que recebe comandos por áudio, interpreta a intenção do usuário, registra ou consulta transações e responde em voz.

- **IA aplicada:** transcrição com Gemini, orquestração com Spring AI e tool calling para executar os casos de uso.
- **Dados e API:** persistência em PostgreSQL, valores monetários em centavos e validação de transações e uploads de áudio.
- **Arquitetura:** separação entre domínio, aplicação e infraestrutura, com testes locais e integrações com o provedor de IA.
- **Tecnologias:** Java, Spring Boot, Spring AI, Google Gemini, Spring Data JPA, PostgreSQL, Docker Compose, Gradle e JUnit 5.

#### 📦 [OrderFlow](https://github.com/Peuvictor/orderflow) — em desenvolvimento

API REST de produtos, com evolução planejada para pedidos, reservas temporárias e controle de estoque.

- **Foco atual:** domínio de produtos, validação e normalização de SKU, persistência relacional e tratamento de erros.
- **Prática de engenharia:** desenvolvimento orientado por testes, arquitetura em camadas e versionamento do banco com Flyway.
- **Próximas etapas:** pedidos com múltiplos itens, reserva de estoque, expiração, idempotência e eventos com RabbitMQ.
- **Tecnologias:** Java 25, Spring Boot, Gradle, PostgreSQL, Flyway, JUnit 5, Mockito, Testcontainers e Docker.

> O README do projeto distingue as etapas desenvolvidas localmente das funcionalidades disponíveis na versão remota.

#### 🎬 [Filme Catalog API](https://github.com/Peuvictor/filmecatalog)

API de catálogo de filmes integrada à OMDb para consultar informações externas e persistir os dados.

- **Integração:** consumo da OMDb com OpenFeign.
- **Design:** aplicação dos padrões Facade e Strategy, com estratégias para cálculo de notas.
- **Tecnologias:** Java 21, Spring Boot 3, PostgreSQL, OpenFeign e Swagger/Springdoc.

#### 🧩 [Sudoku Java](https://github.com/Peuvictor/sudoku-java-dio)

Jogo de Sudoku com versões de terminal e interface gráfica em Swing.

- Tabuleiro 9 × 9, proteção das casas fixas, verificação de respostas e reinício da partida.
- Navegação por teclado, cronômetro e contador de progresso.
- Prática de orientação a objetos, matrizes, eventos e testes da lógica em Java puro.
- **Tecnologias:** Java, Swing e AWT.

### ⚛️ Projetos em React

#### 🧮 [Calculadora React](https://github.com/Peuvictor/calculadora-react)

Calculadora com estado centralizado em `useReducer`, lógica separada da interface e suporte a teclado.

- Operações encadeadas, tratamento de divisão por zero e controle da entrada de números decimais.
- Formatação com `Intl.NumberFormat` e layout com CSS Grid.
- **Tecnologias:** React, JavaScript e CSS.

#### 🗂️ [GitHub Wiki](https://github.com/Peuvictor/github-wiki)

Catálogo pessoal que busca repositórios pela API REST do GitHub e mantém uma lista salva no navegador.

- Persistência com `localStorage`, prevenção de duplicidades e tratamento visual de erros.
- Comunicação HTTP isolada em uma camada de serviço e formulários com React Form Actions.
- **Tecnologias:** React 19, Vite, Tailwind CSS e Fetch API.

### 🤖 Automações e inteligência artificial

#### 🎞️ [Curador de Cinema AI](https://github.com/Peuvictor/curador-cinema-ai)

Curadoria cinematográfica que combina histórico do Filmow, dados do TMDB e recomendações do Gemini.

- Extração do histórico com Nokogiri e armazenamento em CSV.
- Filtragem de filmes já assistidos e seleção de recomendações por gênero em uma interface de terminal.
- **Tecnologias:** Ruby, Nokogiri, TMDB API e Google Gemini.

#### 💼 [Vagas Hunter AI](https://github.com/Peuvictor/vagas-hunter-ai)

Automação para buscar e avaliar oportunidades de estágio e nível júnior em Ruby on Rails e Java/Spring Boot.

- Extração de vagas, filtragem por senioridade e análise de compatibilidade técnica com Gemini.
- Notificações pelo Telegram e registro local de vagas processadas para evitar reprocessamento.
- **Tecnologias:** Ruby, Nokogiri, Google Gemini, Telegram API e JSON.

#### 🧠 [Copilots Library](https://github.com/Peuvictor/copilots-library)

Biblioteca de instruções de sistema para apoiar o desenvolvimento em Ruby on Rails.

- Perfis **Don**, **Atlas**, **Mira** e **Dora**, voltados a planejamento, implementação, diagnóstico e aprendizado.
- Organização de prompts reutilizáveis para orientar o uso de assistentes de IA no ciclo de desenvolvimento.

#### 💸 [VibeFinance](https://github.com/Peuvictor/dio-lab-vibe-coding-app-financas) — protótipo

Estudo de prototipação de um aplicativo financeiro com IA, orientado por um documento de requisitos (PRD).

- Proposta de registro de despesas por linguagem natural, categorização, relatórios e acompanhamento de metas.
- Documentação do processo de criação, demonstrações visuais e análise das limitações do desenvolvimento guiado por IA.

### 🎓 Formação e aprendizado contínuo

- **Análise e Desenvolvimento de Sistemas — UniCesumar:** em andamento, desde 2026.
- **Web Development Full Stack — Le Wagon:** formação em 2024.
- **Engenharia de Mobilidade — UNIFEI:** oito períodos cursados entre 2015 e 2020.

**Bootcamps e programas de formação — DIO:**

- Globant — Java & Spring Boot AI Developer.
- Itaú — Java com Inteligência Artificial.
- Santander 2026 — AI Java Back-end.
- Microsoft — GitHub Copilot e Azure Serverless na Prática.
- Aceleração Microsoft — Azure AI Agents.
- Riachuelo — Criando produtos com IA.

**Outras certificações:** Java (Basic), pela HackerRank, e Google Cloud Computing Foundations, pelo Google.

### ⚡ Um pouco mais
Quando não estou codando, estou acompanhando o **Cruzeiro** no futebol, a NBA (Lakers) ou a NFL (Patriots). Mantenho a cabeça no lugar com **musculação diária**, **corridas de 5km** aos sábados, podcasts de **True Crime** e um bom **churrasco**.
