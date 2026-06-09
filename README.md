# Gustech

Gustech e um projeto de e-commerce/storefront para produtos gamer e tecnologia, com vitrine, carrinho, favoritos, pedidos, area de conta e painel administrativo.

## Funcionalidades

- Catalogo de produtos com paginas de detalhe.
- Carrinho, checkout e acompanhamento de pedidos.
- Favoritos e area de usuario.
- Painel administrativo.
- Backend com rotas para produtos, carrinho, pedidos, usuarios, avaliacoes e wishlist.
- Banco local em SQLite no desenvolvimento e suporte opcional a MySQL.

## Stack

- JavaScript
- HTML/CSS
- Node.js
- Express
- SQLite ou MySQL
- Firebase
- Docker opcional

## Estrutura

- `GusTech/`: storefront web.
- `backend/`: API Node.js/Express.

## Backend local

```bash
cd backend
npm install
npm run dev
```

Na primeira execucao, o backend cria o banco local e popula o catalogo inicial quando necessario.

## Configuracao

Use `backend/.env.example` como base. Arquivos `.env` reais nao devem ser enviados ao GitHub.

