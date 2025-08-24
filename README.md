# SevServices — Next.js Storefront

A ready-to-deploy storefront for GTA services & R6 recoil scripts.

## Quick Start (Local)
```bash
npm install
npm run dev
# open http://localhost:3000
```

## Environment variables (optional)
- `NEXT_PUBLIC_SHOP_URL` (default: https://sevservices.mysellauth.com/)
- `NEXT_PUBLIC_DISCORD_INVITE` (default: https://discord.gg/8d3me5n852)

## Deploy on Railway
- Build command: `npm ci && npm run build`
- Start command: `npm start`
- Railway sets `PORT`; app listens on it.
