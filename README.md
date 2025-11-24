# sk-collective-digital
All-in-one ERP + Accounting for SMEs. “One platform. Total control.”

## Quick Start (Next.js)

Prereqs: Node.js LTS, Git, GitHub, Vercel account.

```bash
npx create-next-app@latest sk-collective-digital
cd sk-collective-digital
npm run dev
```

Open http://localhost:3000.

## Deploy

1. Push code to GitHub (main branch).
2. Import the repo in Vercel → Deploy.
3. Live URL appears on successful build.

## Project Structure (default Next.js)
- app/ or pages/ — routes
- public/ — static assets
- package.json — scripts and deps

## Scripts
- dev: start dev server
- build: production build
- start: run production server

## Environment Variables (later)
Create a .env.local for secrets (not needed today). Examples (to be added later):
- DATABASE_URL=
- NEXT_PUBLIC_APP_NAME=SK Collective Digital

## Roadmap — MVP Scope
- Auth, organizations, users/roles
- Contacts, Items, Tax Rates (ZA VAT 15%)
- Invoices (PDF + email), manual payments
- Bank CSV import + reconciliation
- VAT summary + invoice list

## Contributing (Day 1)
- Use GitHub Project board: Backlog → In Progress → Done.
- One small change per pull request.

## License
TBD
