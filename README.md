# Organizze Financeiro - Scaffold

Scaffold inicial do projeto Organizze Financeiro.

Stack:
- Next.js + TypeScript
- Tailwind CSS
- Prisma (Postgres)

Para rodar localmente:

1. Copie `.env.example` para `.env` e preencha as variáveis.
2. Instale dependências: `npm install`
3. Rode o banco (docker-compose) ou configure um Postgres local.
4. Rode as migrations/seed:
   - `npx prisma migrate dev --name init`
   - `node prisma/seed.js` (ou `ts-node prisma/seed.ts` se tiver ts-node)
5. Rode em desenvolvimento: `npm run dev`

Licença: MIT