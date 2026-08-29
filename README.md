## Danny Urrea

Senior Full Stack Engineer — **TypeScript · Node.js · Go · React/Next.js ·
PostgreSQL**. 12+ years building product for large engineering orgs, most
recently at **EPAM** and **Globant**, on teams delivering for Johnson & Johnson,
Exact Sciences, and Live Nation. Based in Bogotá, Colombia; working remote.

Most of that work sits behind client NDAs, so what's public here is my own
product work.

### Statos — [statos.pro](https://statos.pro)

A football analytics SaaS I designed, built, and run solo — every layer of it.

- **Backend:** Go REST API, PostgreSQL, scheduled Go ingestion workers pulling
  fixtures, odds and match statistics from third-party sports data providers
  into an append-only store of several million rows
- **Frontend:** Next.js + TypeScript, Tailwind, a component library shared
  across app and marketing surfaces, fetch-on-expand detail views over a live
  odds feed
- **Product:** Stripe subscriptions and customer portal, OTP login and MFA, API
  keys with scoped permissions, transactional email with DKIM/DMARC alignment
- **Infra:** Dockerized, GitHub Actions CI/CD, Cloudflare → Caddy → containers
  on a hardened VPS, with migrations, backups and incident triage on me

### [statos-mcp](https://github.com/dumkoder/statos-mcp) — [`@statospro/mcp`](https://www.npmjs.com/package/@statospro/mcp) on npm

A [Model Context Protocol](https://modelcontextprotocol.io) server that exposes
the Statos API to AI assistants as a typed tool surface — zod-validated schemas,
scoped API-key auth, 32 unit tests, CI across Node 20/22/24. Source is public;
this is the readable slice of the Statos codebase.

### [oh-my-zsh-claude-code-statusline](https://github.com/dumkoder/oh-my-zsh-claude-code-statusline)

A small shell tool that renders a Claude Code statusline matching your existing
oh-my-zsh theme.

---

**Also work in:** GraphQL (Apollo, AppSync), AWS (Lambda, Cognito, S3),
OAuth 2.0 & MFA, Redux, Jest/Vitest, Docker, LLM/AI API integration.

📫 [danny.urrea@icloud.com](mailto:danny.urrea@icloud.com) ·
[LinkedIn](https://www.linkedin.com/in/mudvi)
