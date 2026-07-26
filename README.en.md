# Hi, I'm Aureo 👋

**Full-stack & AI engineer · SaaS founder · Shipping software since 1997**

I take a blank repository and put a **complete product into production** — data
model, backend, frontend, auth, payments, the AI layer, deploy — and then I
operate it. I don't own a slice of the stack. I own the thing working, with real
money moving through it.

Self-taught since the dial-up era. Running my own one-person software company
since 2015. No degree, no bootcamp — the evidence is below, and it's clickable.

---

### 🚀 Live products

| | | |
|---|---|---|
| 🩺 | **[clinexa.com.br](https://clinexa.com.br)** | AI receptionist on WhatsApp for clinics — books, confirms, cuts no-shows. Multi-tenant, guardrails, Stripe + Pix |
| 🔮 | **[numenia.xyz](https://numenia.xyz)** | Consumer product, no-signup international funnel, 3 locales, purchasing-power-parity pricing |
| 🚗 | **[themotorcrunch.com](https://themotorcrunch.com)** | 29+ automotive cost calculators, 4 countries, programmatic SEO, 735 tests |
| 🔍 | **[raiox.digital](https://raiox.digital)** | Free 60-second technical audit of any site, behind an SSRF-hardened fetcher |
| 🤖 | **[ominixbot.xyz](https://ominixbot.xyz)** | Telegram group-admin bot sold as a subscription service |

---

### 🐛 The bug I'm proudest of finding

A paying customer named `Søren` got the wrong result out of Numenia.

String normalization treated European letters outside basic Latin — `Ø Æ Þ Ł Ð Đ
Œ` — as **zero**. No exception, no alert, no 500. The system charged, delivered,
and the number was wrong. Silent, and retroactive to day one.

I found it by distrusting a mismatch between the displayed value and the
persisted one, then running the suite against a set of non-ASCII names.

I build AI-first, with agents in the loop every day. That bug passed automated
review without raising anything — from the code's point of view, nothing was
wrong. **The agent gives leverage; someone still has to distrust the number.**
That's the part of the job that doesn't get delegated, and it's what I'm selling.

---

### 🧰 Open source — the hard parts, extracted from production

- **[multi-tenant-saas-starter](https://github.com/aureo-manzano/multi-tenant-saas-starter)** — tenant isolation · idempotent webhooks, including duplicate delivery · job queue with a dead-letter queue
- **[llm-safety-guardrails](https://github.com/aureo-manzano/llm-safety-guardrails)** — deterministic guardrails for LLM assistants in health-adjacent domains, plus an eval harness. TypeScript, zero deps
- **[programmatic-seo-generator](https://github.com/aureo-manzano/programmatic-seo-generator)** — pSEO engine with an auditable indexation threshold (anti scaled-content-abuse)
- **[portfolio](https://github.com/aureo-manzano/portfolio)** — architecture case studies for everything above

---

### 🛠️ Tech

`TypeScript` · `JavaScript` · `Python` · `Node.js` · `React` · `Next.js` ·
`TanStack` · `Prisma` · `Drizzle` · `PostgreSQL` · `Neon` · `Supabase` ·
`MongoDB` · `Redis/BullMQ` · `LLMs (OpenAI · Anthropic · OpenRouter)` · `RAG` ·
`Stripe` · `Pix` · `Docker` · `Linux (nginx, systemd)` · `Vercel` · `Railway` ·
`Playwright` · `Vitest` · `Technical SEO`

---

### 💼 Open to

Remote **Senior Full-Stack · Product Engineer · Founding Engineer · AI Engineer**.

I've been writing software for 25 years and never held a job title. Looking for
my first role inside a team.

📧 aureomanzano@icloud.com · 💼 [LinkedIn](https://www.linkedin.com/in/aureo-manzano-120583421/)
