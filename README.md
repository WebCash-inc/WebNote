<div align="center">

  <img src="img/webnote.png" width="400"/>
  
  ![WebNotes Banner](https://img.shields.io/badge/WebNotes-Organize%20suas%20ideias-blue?style=for-the-badge)
  
  [![Deploy Status](https://img.shields.io/badge/deploy-success-brightgreen?style=flat-square)](https://webnotesp.vercel.app)
  [![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

  **Uma aplicação moderna e intuitiva para gerenciar suas anotações online**

  [Demo ao Vivo](https://webnotesp.vercel.app) · [Reportar Bug](https://github.com/WebCash-inc/WebNote/issues)

</div>

---

## ✨ Sobre o Projeto

WebNotes é uma aplicação web completa para gerenciamento de anotações, desenvolvida com foco em produtividade e experiência do usuário. Com uma interface limpa e moderna, você pode organizar suas ideias, tarefas e pensamentos de forma eficiente e segura.

### 🎯 Principais Funcionalidades

- ✅ **Autenticação Segura** - Sistema completo de login e registro
- 📌 **Criação de Notas** - Interface intuitiva para criar e editar anotações
- 🏷️ **Organização** - Categorize e organize suas notas facilmente
- 🔍 **Busca Rápida** - Encontre suas anotações instantaneamente
- 📱 **Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 🌙 **Modo Escuro** - Interface adaptável para conforto visual
- ☁️ **Cloud Sync** - Suas notas sincronizadas em tempo real
- 🔒 **Privacidade** - Seus dados protegidos e criptografados

---

## 🚀 Demonstração

<div align="center">
  
  ![Demo Screenshot](https://youtu.be/XQDl3hjicGA)
  
  *Acesse a aplicação em: [webnotesp.vercel.app](https://webnotesp.vercel.app)*

</div>

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **React.js** - Biblioteca JavaScript para interfaces
- **TypeScript** - Superset tipado de JavaScript
- **Tailwind CSS** - Framework CSS utilitário
- **React Router** - Navegação entre páginas
- **Axios** - Cliente HTTP para requisições

### Backend
- **Node.js** - Ambiente de execução JavaScript
- **Express.js** - Framework web para Node.js
- **MongoDB** - Banco de dados NoSQL
- **JWT** - Autenticação por tokens
- **Bcrypt** - Criptografia de senhas

### DevOps & Deploy
- **Vercel** - Hospedagem e deploy contínuo
- **Git** - Controle de versão
- **ESLint** - Linter para código limpo
- **Prettier** - Formatação de código

---

## 📦 Instalação

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn
- MongoDB (local ou cloud)

### Passo a Passo

1. **Clone o repositório**
```bash
git clone https://github.com/yourusername/webnotes.git
cd webnotes
```

2. **Instale as dependências**
```bash
npm install
# ou
yarn install
```

3. **Configure as variáveis de ambiente**

Crie um arquivo `.env` na raiz do projeto:

```env
# Database
MONGODB_URI=sua_connection_string_mongodb
DATABASE_NAME=webnotes

# Authentication
JWT_SECRET=seu_jwt_secret_super_seguro
JWT_EXPIRE=7d

# API
API_URL=http://localhost:3000
PORT=3000

# Client
REACT_APP_API_URL=http://localhost:3000
```

4. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
# ou
yarn dev
```

5. **Acesse a aplicação**

Abra seu navegador em `http://localhost:3000`

---

## 📁 Estrutura do Projeto

```
webnotes/
├── src/
│   ├── components/       # Componentes reutilizáveis
│   │   ├── Auth/        # Componentes de autenticação
│   │   ├── Notes/       # Componentes de notas
│   │   └── UI/          # Componentes de interface
│   ├── pages/           # Páginas da aplicação
│   │   ├── Login/
│   │   ├── Register/
│   │   ├── Dashboard/
│   │   └── Notes/
│   ├── services/        # Serviços e API calls
│   ├── context/         # Context API
│   ├── hooks/           # Custom hooks
│   ├── utils/           # Funções utilitárias
│   ├── styles/          # Estilos globais
│   └── types/           # TypeScript types
├── public/              # Arquivos públicos
├── server/              # Backend
│   ├── controllers/     # Controladores
│   ├── models/          # Modelos do banco
│   ├── routes/          # Rotas da API
│   ├── middleware/      # Middlewares
│   └── config/          # Configurações
├── .env.example         # Exemplo de variáveis
├── package.json
└── README.md
```

---

## 🎮 Como Usar

### Criando sua Conta

1. Acesse a página de [login](https://webnotesp.vercel.app)
2. Clique em "Criar conta" ou "Registrar-se"
3. Preencha seus dados e confirme seu email
4. Faça login com suas credenciais

### Gerenciando Notas

1. **Criar nota**: Clique no botão "+" ou "Nova Nota"
2. **Editar nota**: Clique sobre qualquer nota para editá-la
3. **Deletar nota**: Use o ícone de lixeira para remover
4. **Buscar**: Use a barra de pesquisa no topo
5. **Organizar**: Arraste e solte ou use categorias

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Diretrizes de Contribuição

- Siga os padrões de código do projeto
- Escreva commits descritivos
- Adicione testes quando aplicável
- Atualize a documentação conforme necessário

---

## 🐛 Reportar Problemas

Encontrou um bug? Por favor, abra uma [issue](https://github.com/WebCash-inc/WebNote/issues) descrevendo:

- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs atual
- Screenshots (se aplicável)
- Ambiente (navegador, OS, etc)

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/WebCash-inc/WebNote/blob/main/LICENSE) para mais detalhes.

---

## 🙏 Agradecimentos

- Inspiração de design de várias aplicações de notas
- Comunidade open source

---

## 📊 Status do Projeto

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/webnotes?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/yourusername/webnotes?style=flat-square)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/webnotes?style=flat-square)

---

<div align="center">

**Desenvolvido por WebCash.

</div>
