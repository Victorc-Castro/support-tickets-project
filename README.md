## 👩‍💻 Aprendizados
Durante o desenvolvimento do "Support Tickets", aprendi e apliquei vários conceitos fundamentais para projetos web backend. Alguns dos principais aprendizados incluem:
  --> 1. Servidor HTTP de Baixo Nível:
  Fundamentos do Protocolo: Entendimento prático de como o módulo nativo http lida com sockets, streams e como processar manualmente as requisições (req) e respostas (res).

  Roteamento Manual: Implementação de um roteador personalizado que lida com o método HTTP e a URL (req.url), permitindo o mapeamento exato para as funções de controller responsáveis pelo CRUD.

  --> 2. Arquitetura de Middlewares:
  Criação de Pipeline: Construção de uma cadeia de middlewares (funções que processam a requisição antes do controller). Isso inclui a implementação manual de um Body Parser para ler o payload JSON de requisições POST e PUT.

  Separação de Preocupações: Uso de middlewares para isolar responsabilidades cruciais, como tratamento de erros e validação inicial de dados.
  
  --> 3. Modularização e Organização do Código:
  Uso de Módulos ES6: Prática da divisão de código em arquivos lógicos separados (controllers, services, etc.) utilizando a sintaxe import e export, garantindo que o projeto fosse escalável e fácil de navegar.

  Padrão RESTful: Reforço na compreensão de como mapear verbos HTTP (GET, POST, PUT, PATCH, DELETE) para as operações de gerenciamento de recursos (Tickets).
  
  --> 4. Utilização de Módulos Nativos Essenciais:
  Manipulação de Arquivos (fs): Utilização do módulo fs para simular o armazenamento de dados (ou para fins de log), consolidando a leitura e escrita assíncrona.

  Criptografia e IDs (crypto): Uso do módulo crypto para gerar identificadores únicos (UUIDs) para cada ticket, um requisito essencial em qualquer sistema de gerenciamento de dados.

## 💻 Estrutura do Projeto
  SUPPORT-TICKETS-PROJECT
  hadirday_project
  ├── node_modules/         # Dependências (ignorado pelo Git)
  ├── src/                  # Código fonte do backend
  ├── .gitignore
  ├── package-lock.json
  └── README.md

## 💾 Pré Requisitos
  --> Node.js (versão [v22.17.0])
  --> npm ou yarn (Gerenciador de pacotes)
  --> **Insomnia** ou Postman (Para testar os endpoints da API)

## 🚀 Como Rodar
  Esta API utiliza Node.js puro e um arquivo JSON (db.json) para persistência de dados simulada.

  1. Instalação
    Clone o repositório e instale as dependências.

  2. Inicie o servidor Backend.
    --> npm run dev 

  3. Uso
    --> Use o Insomnia ou Postman para testar os endpoints da API (GET, POST, PUT, DELETE, PATCH).

## ⚙️ Tecnologias
Esse projeto foi desenvolvido usando as seguintes tecnologias:

- Node.js
- JavaScript (ES6+)
- GIT E Github

## 🏷️ Layout
Você pode visualizar o layout do projeto através [desse link](https://efficient-sloth-d85.notion.site/API-de-ticket-de-suporte-25654d26e5704936a5da1b3083f03c27).
É necessário ter uma conta no [Figma](https://www.figma.com).