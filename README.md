# Olá, eu sou o Aureo 👋

🇧🇷 Português · [🇺🇸 English](README.en.md)

**AI Engineer · Coloco sistemas de LLM em produção — agentes, RAG, guardrails · Full-stack · Desde 1997**

Eu construo **IA-first**: orquestro agentes (Claude Code) para colocar sistemas de
LLM em produção — recepcionista de IA que atende paciente, guardrails de segurança,
RAG, integração com OpenAI e Anthropic. Mas o que eu entrego não é velocidade de
digitação. É **julgamento**: sobre integridade de dado, edge case e segurança —
justamente o que o agente não tem. O agente escreve; eu decido se está certo.

Pego um repositório em branco e coloco o produto **inteiro** no ar — dado, backend,
frontend, pagamentos, camada de IA, deploy — e depois opero. Autodidata desde a era
da internet discada, tocando minha própria empresa de software desde 2015. Sem
diploma, sem bootcamp — a prova está logo abaixo, e ela abre com um clique.

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

### 🤖 IA em produção (não em slide)

- **Recepcionista de IA que atende paciente** (Clinexa) — agente conversacional em WhatsApp com **guardrails determinísticos**: bloqueia diagnóstico e prescrição, detecta emergência e escala. LLM na frente de gente real, com trava de segurança testável.
- **[llm-safety-guardrails](https://github.com/aureo-manzano/llm-safety-guardrails)** — biblioteca open source de guardrails para assistentes de IA em saúde, com harness de avaliação (evals). TypeScript, zero dependências.
- **Orquestração de agentes no dia a dia** — Claude Code no loop, integração com OpenAI e Anthropic, RAG, engenharia de prompt. Construo o sistema; o agente escreve; eu julgo.

Meus 4 anos de medicina não são detalhe aqui: são a razão de eu saber **o que uma IA não pode dizer a um paciente** — e de os guardrails serem os certos.

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

- **[llm-safety-guardrails](https://github.com/aureo-manzano/llm-safety-guardrails)** — guardrails determinísticos para assistentes de IA em domínio de saúde (detecção de emergência, bloqueio de diagnóstico/prescrição) + harness de avaliação. TypeScript, zero dependências
- **[multi-tenant-saas-starter](https://github.com/aureo-manzano/multi-tenant-saas-starter)** — isolamento de tenant · webhooks idempotentes, incluindo entrega duplicada · fila com dead-letter queue
- **[programmatic-seo-generator](https://github.com/aureo-manzano/programmatic-seo-generator)** — motor de pSEO com limiar de indexação auditável (anti scaled-content-abuse)
- **[portfolio](https://github.com/aureo-manzano/portfolio)** — case studies de arquitetura de tudo que está acima

---

### 🛠️ Tecnologias

**IA** · `LLMs (OpenAI · Anthropic · OpenRouter)` · `RAG` · `AI Agents` ·
`Guardrails / AI Safety` · `Prompt Engineering` · `MCP` · `Claude Code` ·
`Vector DBs`
**Stack** · `TypeScript` · `JavaScript` · `Python` · `Node.js` · `React` ·
`Next.js` · `Prisma` · `PostgreSQL` · `Supabase` · `MongoDB` · `Redis/BullMQ` ·
`Stripe` · `Pix` · `Docker` · `Linux (nginx, systemd)` · `Vercel` · `Railway`

---

### 💼 Aberto a

**AI Engineer · AI Product Engineer · Applied AI / LLM Engineer · Senior Full-Stack** — remoto.

Escrevo software há 25 anos e nunca tive um cargo. Procuro minha primeira
posição dentro de um time.

📧 aureomanzano@icloud.com · 💼 [LinkedIn](https://www.linkedin.com/in/aureo-manzano-120583421/)
