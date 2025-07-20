#📂 Estrutura Completa do Projeto React + TypeScript

## 🏗️ Visão Geral da Arquitetura
<pre>
project/<br>
├── node_modules/ # Todas as dependências do projeto (3.627 diretórios)<br>
├── public/ # Arquivos públicos servidos diretamente<br>
│   └── vite.svg # Logo padrão do Vite<br>
├── src/ # Código-fonte principal<br>
│   ├── assets/ # Recursos estáticos<br>
│   │   ├── fundo-image.png # Imagem de fundo<br>
│   │   ├── fundo-login.jpg # Background da página de login<br>
│   │   ├── LOGO_COMPLETA_BRANCA.png # Logo versão branca<br>
│   │   └── LOGO_COMPLETA_COLORIDA.png # Logo versão colorida<br>
│   ├── components/ # Componentes reutilizáveis<br>
│   ├── Home/ # Página principal<br>
│   │   ├── Home.tsx # Componente Home<br>
│   │   ├── HomeStyle.css # Estilos da Home<br>
│   │   └── Tabs/ # Sistema de abas<br>
│   │       ├── Products/ # Aba de produtos<br>
│   │       └── Users/ # Aba de usuários<br>
│   ├── Login/ # Autenticação<br>
│   │   ├── Login.tsx # Página de login<br>
│   │   ├── LoginStyle.css # Estilos do login<br>
│   │   └── ForgotPassword/ # Recuperação de senha<br>
│   ├── Profile/ # Perfil do usuário<br>
│   │   ├── Profile.tsx # Componente de perfil<br>
│   │   └── ProfileStyle.css # Estilos do perfil<br>
│   ├── App.tsx # Componente raiz<br>
│   ├── main.tsx # Ponto de entrada<br>
│   └── vite-env.d.ts # Tipos do Vite<br>
├── .gitignore # Arquivos ignorados pelo Git<br>
├── package.json # Configuração do projeto e scripts<br>
├── package-lock.json # Versões exatas das dependências<br>
├── tsconfig.json # Configuração do TypeScript<br>
├── tsconfig.node.json # Config TS para ambiente Node<br>
├── vite.config.ts # Configuração do Vite<br>
└── README.md # Documentação do projeto<br>
</pre>

## 📦 Principais Dependências

### Core
- `react@18.2.0` - Biblioteca principal
- `typescript@4.9.5` - Superset JavaScript tipado
- `vite@4.3.9` - Build tool e dev server

### Roteamento
- `react-router-dom@6.11.2` - Navegação entre páginas

### UI/Estilos
- `bootstrap@5.2.3` - Framework CSS
- Múltiplos componentes individuais (Button, Modal, Table, etc.)

### Desenvolvimento
- `@vitejs/plugin-react@4.0.3` - Suporte a React
- `@typescript-eslint/*` - Linting para TS
- `eslint@8.38.0` - Análise de código

## 🛠️ Como Executar

1. Instale as dependências:
```bash
npm install
Inicie o servidor de desenvolvimento:

bash
npm run dev
Acesse no navegador:

text
http://localhost:5173
🔗 Links Úteis
Documentação React

TypeScript Handbook

Guia Vite