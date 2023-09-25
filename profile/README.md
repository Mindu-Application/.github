<a align="center">
  <h1 align="center">Míndu</h1>
</a>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#tech-stack--features"><strong>Tech Stack + Features</strong></a> ·
  <a href="#etapas-do-desenvolvimento"><strong>Etapas do Desenvolvimento</strong></a> ·
  <a href="#running-locally"><strong>Running Locally</strong></a>
</p>
<br/>

## Introduction

Este repositório contém o desenvolvimento de um Produto Mínimo Viável (MVP) para um aplicativo corporativo abrangente destinado a atender a um mercado de alta capilaridade. O aplicativo tem como objetivo atender a múltiplos usuários dentro de corporações, potencialmente para diversos clientes. Como parte do processo de desenvolvimento, diversos aspectos, desde o design arquitetônico até a construção do backend, estão sendo cuidadosamente considerados.


## Tech Stack + Features

### Frameworks

- [Next.js](https://nextjs.org/) – React framework for building performant apps with the best developer experience
- [Auth.js](https://authjs.dev/) – Handle user authentication with ease with providers like Google, Twitter, GitHub, etc.
- [Prisma](https://www.prisma.io/) – Typescript-first ORM for Node.js
- [NextAuth.js](https://minduapp.tech) – Facilite a autenticação de usuário em seus aplicativos Next.js com suporte a várias estratégias de autenticação.
- [PlanetScale](https://minduapp.tech) – Escale seu banco de dados com facilidade usando a poderosa plataforma de banco de dados distribuídos do PlanetScale.
- [Zod](https://minduapp.tech) – Biblioteca TypeScript para validação de esquemas de dados de forma segura e concisa.
- [Prisma](https://minduapp.tech) – ORM


### Platforms

- [Vercel](https://vercel.com/) – Easily preview & deploy changes with git

### UI

- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework for rapid UI development
- [Lucide](https://lucide.dev/) – Beautifully simple, pixel-perfect icons
- [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) – Optimize custom fonts and remove external network requests for improved performance

### Code Quality

- [TypeScript](https://www.typescriptlang.org/) – Static type checker for end-to-end typesafety
- [Zod](https://minduapp.tech) – Biblioteca TypeScript para validação de esquemas de dados de forma segura e concisa.
- [Prettier](https://prettier.io/) – Opinionated code formatter for consistent code style
- [ESLint](https://eslint.org/) – Pluggable linter for Next.js and TypeScript

## Etapas do Desenvolvimento
- **Gestão de Usuários e Organizações:** Permissão para os masters cadastrarem usuários em suas organizações, incluindo um painel de controle para avaliação de documentos enviados pelos usuários.
- **Edição de Perfis e Anexos:** Permitir que os usuários editem seus perfis, incluindo foto e documentos anexados.
- **Postagem de Histórias:** Implementação da funcionalidade de postagem de histórias por parte dos usuários.
- **Troca de Mensagens:** Desenvolvimento da capacidade de enviar e receber mensagens entre usuários.
- **Visualização de Postagens:** Configuração da visualização de postagens feitas pelos usuários.
- **Autenticação em Níveis de Acesso:** Configuração de autenticação para diferentes níveis de acesso, incluindo admin, master e usuário.
- **Banco de Dados:** Instanciação do banco de dados no PlanetScale para armazenamento de todos os tipos de dados necessários.
- **Cadastro de Organizações e Usuários:** Implementação do cadastro de organizações por um administrador por meio de um painel de controle, com um gerenciamento adicional de usuários pelos masters.
- **Funcionalidade de Check-in via QR Code:** Implementação da funcionalidade de check-in por meio da leitura de QR Code para rastreamento de localização.
- **Gestão de Checklist**: Os indivíduos podem gerenciar e preencher checklists de forma eficiente dentro do aplicativo.
- **Gamificação de Engajamento**: Uma estrutura simples de gamificação recompensa o engajamento do usuário, medindo seu nível de participação e reconhecendo sua posição no ambiente corporativo.
- **Armazenamento e Consulta de Dados**: Dados coletados de check-ins, checklists e outras ações são armazenados em um banco de dados seguro, permitindo análises e relatórios posteriores.
- **Configuração do Cloudinary:** É necessário configurar o bucket no Cloudinary para habilitar o upload de imagens e vídeos, especialmente para a funcionalidade de postagem de histórias e posts.
- **PlanetScale** - Configuração

## Running Locally

1. Install dependencies using pnpm:

```sh
npm install
```

2. Copy `.env.example` to `.env.local` and update the variables.

```sh
cp .env.example .env.local
```

3. Start the development server:

```sh
npm run dev
```

## Feedback e Contato
Seu feedback é inestimável para moldar o sucesso deste MVP. Para perguntas, sugestões ou dúvidas, não hesite em [entrar em contato](https://github.com/Mindu-Application/mindu/discussions) por meio do GitHub ou de outros canais de comunicação.

*Observação: Este projeto está em andamento, e atualizações serão feitas periodicamente para refletir os desenvolvimentos em curso.*
