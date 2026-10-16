# Hi, I'm Christian 👋

**I drive innovation from the inside.** I find where a business loses time — supplier invoices, bank transactions, reconciliations, absences, billing discrepancies — and turn it into tools people rely on every day.

Las Palmas de Gran Canaria · [bybumann.com](https://bybumann.com) · [LinkedIn](https://www.linkedin.com/in/christian-bumann/)

---

## What I'm building now

### A corporate intranet for a travel group — built from scratch, used every day

A platform of several applications (suppliers, customers, HR and brand assets) that replaces spreadsheets, inbox folders and copy-pasting between systems.

- **From supplier email to validated invoice** — it reads mail from Microsoft 365, extracts PDF data using rules and AI, matches each line against the ERP, and tracks every discrepancy until someone resolves it.
- **Reconciliation that thinks like a person** — when lines don't match one to one, it looks for combinations that add up and suggests them for review rather than guessing.
- **One tool, not ten** — bank, cards, IATA BSP, commissions and accounting, plus customer collections and absences that arrive from Factorial the moment they're logged.
- **Data you can trust** — multi-tenant PostgreSQL with row-level security, a full audit trail, role-based permissions and screens that update themselves.
- **Built to be maintained** — nothing ships without review and a passing CI run (linting, type checks, tests and secret scanning). The Azure infrastructure is defined as code, and every change comes with its own user manual update and release note.

<sub>3,000+ commits · 800+ pull requests · 270+ database migrations · since June 2026</sub>

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `React` `TypeScript` `Vite` `TanStack Query` `Tailwind` `Azure` `Bicep` `GitHub Actions` `Microsoft Graph`

### AI-assisted engineering, with guardrails

Most of that code is written with AI coding agents (Claude Code). The model is the easy part. What makes it work is everything around it: architecture and style guides the agents have to follow, small stacked pull requests, a CI pipeline nobody can bypass, and human review before anything reaches `master`. I design the process, own the product and review every change.

---

## Other work, past and ongoing

- **Custom banking connector** for Power Platform — authentication, API calls and loading transactions into Dataverse.
- **Supplier document automation** — high-volume downloading, unzipping, SharePoint filing and invoice data extraction.
- **FACe invoice monitoring** — tracking invoices sent to Spanish public bodies and alerting the right office when one is rejected.
- **Financial Power BI models** built on Business Central data and mapped to the Spanish chart of accounts (P&L, balance sheet, KPIs).
- **Data plumbing** — ODBC-to-PostgreSQL sync, ERP–HR integrations, and SQL, Python and Power Query pipelines.
- **Web products** — a multi-tenant SaaS for studio management, and websites built with Next.js, Astro and Supabase.

`Power Apps` `Power Automate` `Dataverse` `Power BI` `Business Central` `SharePoint` `Next.js` `Astro` `Supabase` `SQL`

---

## How I work

- **Understand the process before writing any code.** The tool fits the way the work actually gets done, not the other way around. And when something's missing, I ask rather than make up the rule.
- **Never cut corners on structure.** Features can be cut; the data model, security and audit trail can't.
- **Write it down.** Commit messages explain the *why*, pull requests say what was left out and what couldn't be tested, and users get a manual.

---

## Currently

Driving **digital innovation** at a travel group — new internal products, automation, integrations and data · Studying **Computer Engineering**.

Most of my work lives in private repositories. Happy to walk you through it — [get in touch](https://www.linkedin.com/in/christian-bumann/).

---

> I do not build systems from theory. I build them from real operational problems.
