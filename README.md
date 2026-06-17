# Teste-de-API
Um mini projeto criado em sala por uma equipe iniciante deum curso de TI, no qual o objetivo é a criação de uma API simples, porem com todos os ensinamentos dados em sala 

# 🎮 GameRegistry API - Sistema de Cadastro de Jogos

Este projeto consiste em uma aplicação web completa (Full Stack) para o gerenciamento e cadastro de jogos. A aplicação simula um ambiente real de produção, contando com uma API REST estruturada em Node.js/Express no ecossistema de backend, e uma interface dinâmica e responsiva no frontend utilizando HTML5, CSS3 e JavaScript Vanilla (Fetch API).

Atividade desenvolvida como parte da primeira entrega prática da disciplina, com foco em arquitetura profissional e comunicação assíncrona.

---

## 🚀 Tecnologias Utilizadas

### Backend
- **Node.js** (Ambiente de execução)
- **Express** (Framework web)
- **CORS** (Compartilhamento de recursos de origens diferentes)

### Frontend
- **HTML5** (Estrutura da aplicação)
- **CSS3** (Estilização moderna com temática Dark/Neon)
- **JavaScript (ES6+)** (Manipulação de DOM e consumo da API via Fetch)

---

## 📁 Estrutura do Projeto

O projeto foi estritamente modularizado seguindo boas práticas de mercado, garantindo a separação de responsabilidades (Rotas, Controllers e Servidor).

```text
meu-projeto/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   │   └── gameController.js   # Lógica de negócio (GET e POST)
│   │   ├── routes/
│   │   │   └── gameRoutes.js       # Definição dos endpoints
│   │   └── app.js                  # Configuração de middlewares e rotas
│   ├── package.json                # Gerenciador de dependências
│   └── server.js                   # Inicialização do servidor
│
└── frontend/
    ├── index.html                  # Interface do sistema
    ├── style.css                   # Identidade visual temática
    └── app.js                      # Consumo assíncrono da API
