# Gauntlet Shop

A small Next.js (App Router) + TypeScript + Tailwind e-commerce storefront used as a target application for
end-to-end testing. Everything is local: mock catalogue, cart, checkout (fake card), accounts, settings,
newsletter. No environment variables or external services.

## Run

```bash
npm ci
npm run build
npm start          # http://localhost:3000
```

`npm run dev` also works. Each pull request in this repository is an ordinary small product change against `main`.
