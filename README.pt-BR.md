## 👩‍💻 Aprendizados

[🇺🇸 Read this documentation in English](./README.md)

Durante o desenvolvimento do "Support Tickets", explorei e apliquei diversos conceitos fundamentais para projetos de backend, focando na construção de um servidor do zero (from scratch). Os principais aprendizados incluem:

Servidor HTTP de Baixo Nível:

--> Fundamentos do Protocolo: Entendimento prático de como o módulo nativo http lida com sockets e streams, incluindo o processamento manual de requisições (req) e respostas (res).

--> Roteamento Personalizado: Implementação de um roteador manual que processa métodos HTTP e URLs (req.url), mapeando-os diretamente para as funções controladoras (controllers).

Arquitetura de Middlewares:

--> Construção de Pipeline: Criação de uma cadeia de middlewares para processar a requisição antes que ela chegue ao controller. Isso inclui a implementação manual de um Body Parser para lidar com payloads JSON em requisições POST e PUT.

--> Separação de Preocupações: Uso de middlewares para isolar responsabilidades cruciais, como tratamento de erros e validação inicial de dados.

Modularização e Organização de Código:

--> Módulos ES6: Divisão do código em arquivos lógicos (controllers, services, etc.) utilizando a sintaxe import/export, garantindo que o projeto seja escalável e de fácil navegação.

--> Padrões RESTful: Reforço na compreensão do mapeamento de verbos HTTP (GET, POST, PUT, PATCH, DELETE) para operações de gerenciamento de recursos.

Módulos Nativos Essenciais:

--> File System (fs): Utilização do módulo fs para persistência de dados assíncrona e logs.

--> Crypto e IDs: Uso do módulo crypto para gerar identificadores únicos (UUIDs), seguindo as boas práticas de segurança para o gerenciamento de dados.

## 💻 Estrutura do Projeto
  SUPPORT-TICKETS-PROJECT
  
  ├── node_modules/         # Dependências (ignorado pelo Git)
  
  ├── src/                  # Código fonte do backend
  
  ├── .gitignore

  ├── Insomnia_Collection_Tickets.json.yaml

  ├── README.md

  ├── README.pt-BR.md
  
  └──  package-lock.json

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

## 🛠️ Testes da API com Insomnia
--> Localize o arquivo de coleção, "Insomnia_Collection_Tickets.json".

--> Importe no Insomnia

--> Selecione o arquivo "Insomnia_Collection_Tickets.json".

--> odas as requisições na coleção estão configuradas para a URL padrão: http://localhost:[Sua Porta].

## ⚙️ Tecnologias
Esse projeto foi desenvolvido usando as seguintes tecnologias:

- Node.js
  
- JavaScript (ES6+)
  
- GIT E Github
