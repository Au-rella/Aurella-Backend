# Aurella — Backend

Express API starter for the Fashion Hub storefront. This repo is **just the scaffold** —
no routes or models are built yet beyond a health check. See [open issues](../../issues)
for what to build.

Pairs with:
- [Aurella-frontend](../Aurella-frontend) — Next.js storefront
- [Aurella-contracts](../Aurella-contracts) — Stellar smart contract

## Stack

- Node.js + Express
- ES modules

## Getting started

```bash
cp .env.example .env
npm install
npm run dev
```

API runs at http://localhost:4000 — try `GET /health`.

## Project structure

```
src/
  routes/        # Express routers (empty — add as you build)
  controllers/    # Request handlers (empty — add as you build)
  models/         # Data models / DB schemas (empty — add as you build)
  middleware/     # Custom middleware (empty — add as you build)
  app.js          # Express app setup
  server.js       # Entrypoint
```

No database is wired up yet — that's an open issue (see `good first issue` label).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and pick an issue.
