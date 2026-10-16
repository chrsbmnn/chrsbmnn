# Hi, I'm Christian 👋

**I drive innovation from inside the operation.** I find where a business loses time — supplier invoices, bank movements, reconciliations, absences, billing differences — and turn it into software that people use every day.

Las Palmas de Gran Canaria · [bybumann.com](https://bybumann.com) · [LinkedIn](https://www.linkedin.com/in/christian-bumann/)

---

## What I'm building now

### A corporate intranet for a travel group — from scratch, in production

A multi-app platform (suppliers, customers, HR, brand assets) that replaces spreadsheets, inbox folders and copy-paste between systems.

- **From supplier email to validated invoice** — mail is read from Microsoft 365, PDFs are extracted (rules + AI), matched line by line against the ERP, and every difference is tracked until someone closes it.
- **Reconciliation that works like a person does** — when lines don't match one to one, it searches combinations whose totals add up and proposes them for review instead of guessing.
- **Bank, cards, BSP/IATA, commissions and accounting** under one roof, plus customer collections and HR absences synced from Factorial via webhooks.
- **Built to be trusted** — multi-tenant PostgreSQL with Row-Level Security, full audit trail, role-based permissions, live updates over SSE.
- **Built to last** — branch protection, mandatory CI (lint, types, tests, secret scanning), infrastructure as code on Azure, and in-app user manuals plus a changelog written for end users, updated in the same PR as the code.

<sub>~3,000 commits · ~900 pull requests · 270 database migrations · since June 2026</sub>

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `React` `TypeScript` `Vite` `TanStack Query` `Tailwind` `Azure` `Bicep` `GitHub Actions` `Microsoft Graph`

### AI-assisted engineering, with guardrails

Most of that code is written together with AI coding agents (Claude Code). The model is the easy part. What makes it work is the **system around it**: written architecture and style guides the agents must follow, small stacked PRs, a CI that can't be bypassed, and human review before anything reaches `master`. I design the process, define the product, and review every change.

---

## Before that, and still alongside

- **Custom banking connector** for Power Platform — authentication, API calls and transaction loading into Dataverse.
- **Supplier document automation** — high-volume download, decompression, SharePoint classification and invoice data extraction.
- **FACe invoice monitoring** — tracking invoices sent to public administrations and alerting the right office on rejection.
- **Financial Power BI models** on Business Central data, mapped to the Spanish General Accounting Plan (P&L, balance sheet, KPIs).
- **Data plumbing** — ODBC-to-Postgres sync, ERP ↔ HR integrations, SQL / Python / Power Query pipelines.
- **Web products** — multi-tenant SaaS for studio management and websites built with Next.js, Astro and Supabase.

`Power Apps` `Power Automate` `Dataverse` `Power BI` `Business Central` `SharePoint` `Next.js` `Astro` `Supabase` `SQL`

---

## How I work

- **Understand the process before writing code.** The system follows how the work is really done, not the other way around. And if a piece is missing, I ask — I don't invent the rule.
- **The structure is never the shortcut.** Scope can be cut in features, never in data model, security or auditing.
- **Write it down.** Commit messages explain the *why*, PRs say what was *not* done and *not* tested, and users get a manual.

---

## Currently

Driving **digital innovation** at a travel group — new internal products, automation, integrations and data · Studying **Computer Engineering**.

Most of my work lives in private repositories. Happy to walk through it — [get in touch](https://www.linkedin.com/in/christian-bumann/).

---

> I do not build systems from theory. I build them from real operational problems.
