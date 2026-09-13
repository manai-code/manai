# MANAI workspace

## Folder layout

- `apps/web` — Next.js, React, and Tailwind website
- `supabase` — database migrations, seed data, and Supabase configuration
- `tooling/scripts` — project automation scripts
- `docs` — project decisions and setup notes

## Commands

Run these from the `MANAI` folder:

```bash
npm install
npm run dev
npx supabase status
```

`npm run dev` starts the website. Supabase’s local services also require Docker Desktop to be installed and running.
