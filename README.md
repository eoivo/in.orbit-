# Gerenciador de Metas - NLW Pocket: Javascript Full-stack Intermediário

Este projeto foi desenvolvido durante o evento **NLW Pocket** da **Rocketseat**, com foco no desenvolvimento **full-stack** intermediário. Trata-se de uma aplicação de **gerenciamento de metas**, onde os usuários podem cadastrar e gerenciar suas metas de forma eficiente e intuitiva.

## Funcionalidades

- **Cadastro de Metas**: Permite aos usuários cadastrar metas com descrições e prazos.
- **Gerenciamento de Metas**: Oferece uma interface para acompanhar o progresso das metas.

## Tecnologias Utilizadas

### Back-end:
- Node.js
- Fastify
- TypeScript
- DrizzleORM
- PostgreSQL
- Docker
- Zod

### Front-end:
- ReactJS
- TypeScript
- Vite
- TailwindCSS
- TanStack Query

## Estrutura do Projeto

### Back-end

```
backend/
├── migrations/
├── src/
│   ├── db/
│   ├── functions/
│   ├── http/
│   └── env.ts
├── .env
├── .biome.json
├── .docker-compose.yml
├── .drizzle.config.json
└── package.json
```

### Front-end

```
frontend/
├── src/
│   ├── assets/
│   ├── components/
│   ├── http/
│   ├── App.tsx
│   └── index.tsx
├── tailwind.config.js
├── vite.config.ts
└── package.json
```

## Como Executar o Projeto

### Pré-requisitos

- **Node.js**
- **Docker**
- **Git**

### Passo a Passo

1. Clone o repositório:

   ```bash
   git clone https://github.com/eoivo/in.orbit-
   ```

2. Acesse a pasta **backend** e instale as dependências:

   ```bash
   cd server
   npm install
   ```

3. Configure o ambiente com Docker:

   ```bash
   docker-compose up -d
   ```

4. Execute as migrações do banco de dados:

   ```bash
   npm run migrate
   ```

5. Inicie o servidor:

   ```bash
   npm run dev
   ```

6. Acesse a pasta **frontend** e instale as dependências:

   ```bash
   cd web
   npm install
   ```

7. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

8. Acesse a aplicação em `http://localhost:3333`.
