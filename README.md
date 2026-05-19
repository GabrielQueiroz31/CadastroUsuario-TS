# Cadastro de Usuários com TypeScript

Projeto simples desenvolvido em TypeScript para praticar o uso de interface, objetos, funções e estrutura condicional.

## Descrição

Este projeto consiste em um sistema simples de cadastro de usuários.

O programa cria uma interface chamada `Usuario`, contendo as propriedades `id`, `nome`, `email` e `isAdmin`.

Também foi criada uma função chamada `renderizarPerfil`, que recebe um usuário e exibe no console se ele é um usuário administrador ou um usuário comum.

## Tecnologias Utilizadas

- TypeScript
- Node.js

## Estrutura do Projeto

CadastroUsuario-TS/
├── dist/
│   └── index.js
├── src/
│   └── index.ts
├── package.json
├── package-lock.json
├── tsconfig.json
└── .gitignore

## Funcionalidades

- Criação de uma interface `Usuario`
- Cadastro de usuários com nome, e-mail, id e tipo de acesso
- Verificação se o usuário é administrador ou comum
- Exibição das informações no console

## Como Executar

Instale as dependências do projeto:

npm install

Execute o projeto:

npm run dev

## Saída Esperada

Usuário Administrador: Gomes (gomes@email.com)
Usuário Comum: Enzo (Enzo@email.com)

## Como Funciona

A interface `Usuario` define quais informações um usuário precisa ter.

O campo `isAdmin` recebe um valor booleano:

- `true` significa que o usuário é administrador
- `false` significa que o usuário é comum

A função `renderizarPerfil` verifica esse valor e mostra uma mensagem diferente no console.

## Conceitos Praticados

- Interface em TypeScript
- Tipagem de dados
- Objetos
- Funções
- Condicional if/else
- Execução de código TypeScript com Node.js

## Autor

Gabriel Gomes de Queiroz