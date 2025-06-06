# 🍝 Casa di Sapori

Um site institucional para o restaurante italiano **Casa di Sapori**, com uma interface acolhedora e elegante, e um assistente virtual (IA) para responder dúvidas dos visitantes.

🔗 Acesse o site: [casa-di-sapori.onrender.com](https://casa-di-sapori.onrender.com/index.html)

---

## 📌 Funcionalidades

- Página inicial com informações sobre o restaurante
- Layout responsivo
- Chatbot com inteligência artificial (Google Gemini) para responder perguntas
- Backend em Node.js com Express
- Integração com a API generativa da Google (`@google/genai`)
- Hospedagem no Render

---

## 🛠️ Tecnologias utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express
- Google Gemini (via `@google/genai`)
- dotenv

---

## 🚀 Como rodar o projeto localmente

### 1. Clone o repositório

git clone https://github.com/susanpaschoal/casa-di-sapori.git
cd casa-di-sapori

### 2. Instale as dependências

npm install

### 3. Crie um arquivo .env com o seguinte conteúdo:

PORTA=3000
MINHA_CHAVE=sua_chave_da_api_google_aqui

### 4.Inicie o servidor

npm start

### Acesse no navegador:

http://localhost:3000

## Assistente IA
O projeto utiliza o modelo Gemini 2.0 Flash, com respostas curtas e diretas às perguntas dos usuários sobre o restaurante, menu, horário de funcionamento, etc.

## Estrutura do projeto
casa-di-sapori/
├── public/
│   └── index.html
├── index.js
├── .env
├── package.json
└── README.md

## ✨ Créditos
Desenvolvido por Susan Paschoal
IA: Google Gemini API
Hospedagem: Render
