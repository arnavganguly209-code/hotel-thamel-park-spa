# Hotel Thamel Park & Spa

Luxury hospitality website for Hotel Thamel Park & Spa, Kathmandu — built with React 19, TanStack Start, TanStack Router, Tailwind CSS v4, shadcn/ui, and Framer Motion.

## Scripts

```bash
bun install
bun run dev       # local dev on :8080
bun run build     # production build
bun run preview   # preview production build
bun run lint
```

## Deploy

The build target is `cloudflare-module` (Cloudflare Workers / Pages). It also deploys cleanly to Vercel via the TanStack Start adapter — switch the `target` in `vite.config.ts` if needed (`vercel`, `node-server`, `bun`, etc.).
