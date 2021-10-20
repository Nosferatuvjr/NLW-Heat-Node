<h1 align="center">NLW Heat - Node.js</h1>

## ✨ Tecnologias

A aplicação foi desenvolvida em:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🚀 Como utilizar o projeto

> Usamos no projeto autenticação via OAuth com o GitHub

- Clone o repositório e acesse a pasta;
- Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

## 📄 O que aprendi na prática e as features que adicionei no projeto

- Aprendi a integrar Node com Banco de Dados SQlite utilizando o Prisma, ferramenta genial;
- Criei tabelas e migrations também utilizando o Prisma;
- Aprendi como funciona o relacionamento entre as tabelas;
- Utilizei WebSocket para comunição Realtime;
- Aprendi a usar melhor o Insomnia aaaaaaaaaaaaaaaa 😁;
### Features
- Além das informações de Nome, Avatar, e User(Login) do usuário, adicionei o link de perfil para que ao cadastrar uma mensagem o Perfil do usuário ficasse disponível no frontend da aplicação, para que dessa forma outras pessoas pudessem ser direcionadas ao perfil do autor de cada mensagem.
- Para isso adicionei uma nova tabela no Banco de Dados para armazenar o link do perfil;


### Obrigado [Rocketseat](https://www.rocketseat.com.br/) e vamos 🛸 #RumoAoPróximoNível

