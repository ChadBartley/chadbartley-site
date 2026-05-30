# Chad Bartley

Cleveland, OH (remote) · chad@askotter.ai
[LinkedIn](https://www.linkedin.com/in/chad-k-bartley/) · [getward.ai](https://getward.ai/)

---

I build production AI systems — agent runtimes, LLM tooling, RAG — and the backends behind them:
Rust where reliability matters, Python and TypeScript to move fast with a team. At Ward I wrote the
core myself; it runs inside a $400M, 850-store retailer's environment against their live SAP data. I've
co-founded a YC startup, took a Meta Marketplace product from zero to ~10k monthly transactions, and
rebuilt a failing platform in Rust that cut its infrastructure bill ~70%. Give me a hard problem and
I'll decide what to build and ship it.

## Experience

**Ward (getward.ai) — Co-Founder & CPO** · 2025–Present
Ward lets a company question its own data and trust the answers. I built the core in Rust myself:
the **agent runtime**, the analytics layer, and the multi-tenant security and audit model — Cedar
policy enforcement and SOC 2 logging — that makes it safe inside a regulated enterprise's own
environment. It's live in a paid POC against a **$400M, 850-store grocery chain's live SAP data**,
with 14 more companies running on the same platform.

**HyperMarket — Brought in to fix a failing platform** · 2025
A digital-commerce platform bleeding money on over-built infrastructure — separate dev, sandbox, and
prod environments across multiple servers, constant breakage, barely a hundred users. In three
months I stripped it down: deleted every environment but test and prod, collapsed production onto a
single server, and re-platformed the core API from a bloated Django monolith to Rust. The AWS bill
dropped ~70%, and I shipped AI tooling that cut brand onboarding from hours to minutes. The team
launched a new AI-powered version on top of it.

**Fern (YC W24) — Co-Founder & Principal Engineer** · 2023–2024
Banks were losing chargeback disputes because fighting them by hand was too slow to bother. We built
the system that did it for them — a Slack-native pipeline that caught each dispute by email, pulled
evidence from across Stripe, Adyen, and Shopify, assembled the case with AI, and handed it back
ready to file. I built the async platform underneath it that ingested and normalized transactions
across Stripe, Adyen, and Shopify. We made YC's W24 batch and won real disputes for the bank we
partnered with.

**Meta — Senior Business Engineer** · 2021–2023
A role built for dropping into whatever needed building. I took Local Delivery on Marketplace from
zero to roughly 10,000 monthly transactions, including the DoorDash partnership
([TechCrunch](https://techcrunch.com/2022/08/15/doordash-partners-with-meta-to-test-delivery-of-facebook-marketplace-items/)).
I built the backend that ingested tens of millions of product reviews from five outside platforms
for thousands of shops. I was also tapped as a Better Engineering Champion, setting engineering
practices alongside senior leadership across a 30-plus-person org.

**Splash Financial — Senior Engineer** · 2020–2021
A document-upload step was quietly killing conversion. I sized the gap with Product and rebuilt the
Upload Center end to end on AWS microservices. Conversion rose ~30% and held, adding roughly $50K in
monthly recurring revenue.

**Extreme Reach — Engineer** · 2016–2020
Where I grew up as an engineer. I led the Angular frontend rebuild of AdBridge for Sellers; it hit a
$2M annual run rate within the first month. I went from junior to senior in two years.

## Selected Projects

- **Cleargate** — an LLM gateway for production AI systems: declarative rules engine
  for cost control, PII redaction, and **multi-provider routing across OpenAI, Anthropic, and
  Bedrock**, with real-time budget enforcement and a row-level-TTL cache for rolling-window
  analytics. Rust, React, TypeScript.
- **AI-Release-Bot** (open source) — a GitHub Action, published on the GitHub Marketplace, that
  turns any software release into a ready-to-publish blog post.
- **Federal Insights RAG (iongov)** — made the federal congressional record searchable: bills,
  hearing transcripts, and committee documents, run through a full scrape → transform → embed → query
  pipeline that fits on a single small machine. Rust, React, Python.

## Skills

AI / agentic systems (agent runtimes, multi-model routing, RAG, embeddings, Langchain/Langgraph) ·
Rust · TypeScript / React · Python · Docker, Kubernetes, Terraform · GitHub Actions / CI/CD ·
AWS · Postgres, Redis, ElasticSearch · SOC 2 & Cedar-based authorization · AI-native workflow
(builds with coding agents daily)

## Education

**Cleveland State University** — B.S. Computer Science · B.A. Economics
