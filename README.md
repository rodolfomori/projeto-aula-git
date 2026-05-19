# DevClub

> DevClub é o melhor lugar para aprender e crescer como desenvolvedor!

Aplicação web criada como projeto de aula, apresentando uma landing page institucional do **DevClub**. O projeto serve como base de estudos para os fundamentos de uma SPA moderna construída com **React + Vite**, incluindo componentização, gerenciamento de estado com hooks, estilização com CSS moderno e build otimizado.

## ✨ Funcionalidades

- Landing page responsiva com hero section e identidade visual do DevClub.
- Contador interativo construído com `useState`, demonstrando reatividade do React.
- Seção de documentação e redes sociais com ícones SVG.
- Layout adaptável a diferentes tamanhos de tela via media queries.
- Hot Module Replacement (HMR) para feedback instantâneo durante o desenvolvimento.

## 🚀 Tecnologias

| Categoria | Ferramenta |
| --- | --- |
| Biblioteca de UI | [React 19](https://react.dev/) |
| Build tool / Dev server | [Vite 8](https://vite.dev/) |
| Linguagem | JavaScript (ES Modules) + JSX |
| Estilização | CSS3 (variáveis, nesting e media queries) |
| Qualidade de código | [ESLint](https://eslint.org/) + `eslint-plugin-react-hooks` + `eslint-plugin-react-refresh` |
| Plugin oficial | [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react) |

## 📂 Estrutura do projeto

```
devclub/
├── public/              # Arquivos estáticos (favicon, ícones)
├── src/
│   ├── assets/          # Imagens e logos
│   ├── App.jsx          # Componente raiz da aplicação
│   ├── App.css          # Estilos do componente App
│   ├── index.css        # Estilos globais e variáveis CSS
│   └── main.jsx         # Ponto de entrada do React
├── index.html           # HTML base servido pelo Vite
├── vite.config.js       # Configuração do Vite
├── eslint.config.js     # Configuração do ESLint
└── package.json
```

## 🔧 Pré-requisitos

- [Node.js](https://nodejs.org/) 18 ou superior
- npm (já vem com o Node) ou outro gerenciador de pacotes de sua preferência

## 📦 Instalação

Clone o repositório e instale as dependências:

```bash
git clone <url-do-repositorio>
cd devclub
npm install
```

## ▶️ Scripts disponíveis

| Comando | Descrição |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento com HMR em `http://localhost:5173` |
| `npm run build` | Gera a versão de produção otimizada na pasta `dist/` |
| `npm run preview` | Sobe um servidor local para visualizar o build de produção |
| `npm run lint` | Executa o ESLint em todo o projeto |

## 🎓 Sobre

Projeto desenvolvido como material de aula para alunos do **DevClub**, com o objetivo de demonstrar, na prática, como dar os primeiros passos com React utilizando o ecossistema moderno do Vite.
