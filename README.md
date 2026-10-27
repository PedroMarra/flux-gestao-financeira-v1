# Flux — Gestão Financeira (v1)

> ⚠️ **Versão antiga, arquivada.** A versão atual, com login, MySQL e Prisma, está em
> [PedroMarra/flux-gestao-financeira](https://github.com/PedroMarra/flux-gestao-financeira).

Primeira versão do app de controle financeiro feito na disciplina **Programação para Dispositivos Móveis** (IESB, 2026).

## Tecnologias
- **App:** React Native com Expo
- **API:** Node.js + Express
- **Banco:** SQLite (criado automaticamente em `backend/database.sqlite` ao iniciar)

## Como rodar
```bash
# API
cd backend && npm install && npm run dev

# App (outro terminal)
cd frontend && npm install && npx expo start
```

A pasta `postman/` tem a coleção para testar as rotas da API.
