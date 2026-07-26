# Olá, eu sou o Aureo 👋

🇧🇷 Português · [🇺🇸 English](README.en.md)

**Engenheiro full-stack e de IA · Fundador de SaaS · Programando desde 1997**

Eu pego um repositório em branco e coloco um **produto completo em produção** —
modelagem de dados, backend, frontend, autenticação, pagamentos, camada de IA,
deploy — e depois eu opero. Não cuido de um pedaço do stack. Cuido da coisa
funcionando, com dinheiro de verdade passando por ela.

Autodidata desde a era da internet discada. Toco minha própria empresa de
software de uma pessoa só desde 2015. Sem diploma, sem bootcamp — a prova está
logo abaixo, e ela abre com um clique.

---

### 🚀 Produtos no ar

| | | |
|---|---|---|
| 🩺 | **[clinexa.com.br](https://clinexa.com.br)** | Recepcionista de IA no WhatsApp para clínicas — agenda, confirma e reduz faltas. Multi-tenant, guardrails, Stripe + Pix |
| 🔮 | **[numenia.xyz](https://numenia.xyz)** | Produto de consumo, funil internacional sem cadastro, 3 idiomas, preço por paridade de poder de compra |
| 🚗 | **[themotorcrunch.com](https://themotorcrunch.com)** | 29+ calculadoras de custo automotivo, 4 países, SEO programático, 735 testes |
| 🔍 | **[raiox.digital](https://raiox.digital)** | Diagnóstico técnico gratuito de qualquer site em 60 segundos, atrás de um fetcher endurecido contra SSRF |
| 🤖 | **[ominixbot.xyz](https://ominixbot.xyz)** | Bot de administração de grupo no Telegram, vendido por assinatura |

---

### 🐛 O bug que eu tenho mais orgulho de ter achado

Um cliente pagante chamado `Søren` recebeu o resultado errado no Numenia.

A normalização de string tratava letras europeias fora do Latin básico — `Ø Æ Þ
Ł Ð Đ Œ` — como **zero**. Sem exceção, sem alerta, sem 500. O sistema cobrou,
entregou, e o número estava errado. Silencioso, e retroativo desde o primeiro
dia.

Achei desconfiando de uma divergência entre o valor exibido e o valor
persistido, e rodando a suíte contra um conjunto de nomes fora do ASCII.

Eu construo em fluxo IA-first, com agentes no loop todo dia. Aquele bug passou
pela revisão automatizada sem levantar absolutamente nada — do ponto de vista do
código, não havia erro. **O agente dá alavancagem; alguém ainda precisa
desconfiar do número.** Essa é a parte do trabalho que não se delega, e é ela
que eu estou oferecendo.

---

### 🧰 Open source — as partes difíceis, extraídas de produção

- **[multi-tenant-saas-starter](https://github.com/aureo-manzano/multi-tenant-saas-starter)** — isolamento de tenant · webhooks idempotentes, incluindo entrega duplicada · fila com dead-letter queue
- **[llm-safety-guardrails](https://github.com/aureo-manzano/llm-safety-guardrails)** — guardrails determinísticos para assistentes de IA em domínio de saúde, com harness de avaliação. TypeScript, zero dependências
- **[programmatic-seo-generator](https://github.com/aureo-manzano/programmatic-seo-generator)** — motor de pSEO com limiar de indexação auditável (anti scaled-content-abuse)
- **[portfolio](https://github.com/aureo-manzano/portfolio)** — case studies de arquitetura de tudo que está acima

---

### 🛠️ Tecnologias

`TypeScript` · `JavaScript` · `Python` · `Node.js` · `React` · `Next.js` ·
`TanStack` · `Prisma` · `Drizzle` · `PostgreSQL` · `Neon` · `Supabase` ·
`MongoDB` · `Redis/BullMQ` · `LLMs (OpenAI · Anthropic · OpenRouter)` · `RAG` ·
`Stripe` · `Pix` · `Docker` · `Linux (nginx, systemd)` · `Vercel` · `Railway` ·
`Playwright` · `Vitest` · `SEO técnico`

---

### 💼 Aberto a

**Senior Full-Stack · Product Engineer · Founding Engineer · AI Engineer** —
remoto.

Escrevo software há 25 anos e nunca tive um cargo. Procuro minha primeira
posição dentro de um time.

📧 aureomanzano@icloud.com · 💼 [LinkedIn](https://www.linkedin.com/in/aureo-manzano-120583421/)
