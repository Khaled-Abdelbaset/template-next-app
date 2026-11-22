# Template — Next.js app

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?logo=github)](https://github.com/Khaled-Abdelbaset/template-next-app/generate)

Minimal **[Next.js](https://nextjs.org/)** 15 (App Router) app with org **CI** and **Discord** workflows. Part of [engineering-standards](https://github.com/Khaled-Abdelbaset/engineering-standards).

---

## What you get

- App Router shell (`src/app/layout.tsx`, `page.tsx`)
- TypeScript strict config
- `.github/workflows/ci.yml` → reusable Next CI (`flavor: next`, `@v1.0.0`)
- `.github/workflows/discord-notify.yml`
- [CONTRIBUTING.md](CONTRIBUTING.md), PR template, Cursor git rule

---

## Create a project from this template

1. GitHub → **Use this template** → create `your-app`.
2. Clone and install:

   ```bash
   git clone git@github.com:Khaled-Abdelbaset/your-app.git
   cd your-app
   npm ci
   npm run dev
   ```

3. Open http://localhost:3000 (default Next dev port — change in `package.json` if needed).

4. Set [GIT_IDENTITY](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_IDENTITY.md), branch protection, and optional `DISCORD_WEBHOOK_URL` — [NEW_PROJECT.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/NEW_PROJECT.md).

---

## Prerequisites

- Node.js 22+

---

## Scripts

| Command | Purpose |
|---------|---------|
| `npm run dev` | Development server |
| `npm run build` | Production build (`tsc` + Next build in CI) |
| `npm run start` | Serve production build |

---

## Customize

1. Update `package.json` name and add UI stack (Tailwind, etc.).
2. Add `next.config.ts` rewrites if you pair with a separate API repo.
3. Follow [focus-planner-frontend](https://github.com/Khaled-Abdelbaset/focus-planner-frontend) for a full product layout.

---

## Related

| Resource | Link |
|----------|------|
| Full UI example | [focus-planner-frontend](https://github.com/Khaled-Abdelbaset/focus-planner-frontend) |
| API template | [template-nest-api](https://github.com/Khaled-Abdelbaset/template-nest-api) |
| Handbook | [engineering-standards](https://github.com/Khaled-Abdelbaset/engineering-standards) |

---

## License

Private / customize per new repo.