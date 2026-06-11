# Chad Bartley

Cleveland, OH (remote) · bartlec04@gmail.com
[LinkedIn](https://www.linkedin.com/in/chad-k-bartley/) · [getward.ai](https://getward.ai/)

---

Senior engineer, ~10 years across fintech, healthtech, commerce, and adtech. I build production AI
systems — agent runtimes, LLM tooling, RAG — and the backends behind them in Rust, Python, and
TypeScript. Ex-Meta; two-time founder (one YC W24).

## Experience

**Ward (getward.ai) — Co-Founder & CPO** · 2025–Present
Enterprise data platform: ask questions of company data, with an audit trail on every AI answer.

- Built the agent runtime, analytics layer, and AI-powered BI tooling in Rust + React; deploys
  cloud or on-prem.
- Built the multi-tenant security model: Cedar policy enforcement, extensible OAuth, and
  SOC 2-compliant audit logging (contributor to the `doxa` crate).
- Live in a paid 12-week POC with a $400M, 850-store grocery chain, running against their
  production SAP S/4HANA data; 14 paying SMB customers on the same platform.

**HyperMarket — Senior Software Engineer (contract)** · 2025
Digital-commerce platform for creators; two-person engineering team.

- Re-platformed the core API from a Django monolith to Rust (Axum/Tokio); moved auth to AWS Cognito.
- Collapsed dev/sandbox/prod environment sprawl to test + production and consolidated serving onto
  a single EC2; monthly AWS bill dropped ~70%.
- Built AI tooling (Langchain/Langgraph, embeddings, vector search) that auto-imports brand designs
  from existing sites, cutting brand onboarding from hours to minutes.

**Fern (YC W24) — Co-Founder & Principal Engineer** · 2023–2024
Chargeback automation for banks. Y Combinator W24.

- Built the dispute pipeline in Rust: automated email intake, evidence collection from Stripe,
  Adyen, and Shopify, AI-assisted evidence-packet assembly, Slack-native review.
- Architected the async platform ingesting and normalizing transactions across the three processors.
- Replaced a manual process our partner bank had mostly given up on; won live disputes before the
  company wound down.

**Meta — Senior Business Engineer** · 2021–2023
Marketplace org.

- Led full-stack development and launch of Local Delivery on Marketplace, scaling from MVP to ~10K
  monthly transactions — including the DoorDash partnership
  ([TechCrunch](https://techcrunch.com/2022/08/15/doordash-partners-with-meta-to-test-delivery-of-facebook-marketplace-items/)).
- Built the Ratings & Reviews backend: daily ingestion of tens of millions of product reviews from
  five external platforms for thousands of shops (Python).
- Better Engineering Champion: drove engineering-efficiency practices (tooling, on-call,
  documentation) with senior leadership across a 30+ person org.

**Splash Financial — Senior Engineer** · 2020–2021
Fintech — student-loan refinancing.

- Rebuilt the document Upload Center end to end on AWS microservices (Lambda, SNS, SQS), partnering
  with Product; conversion rose ~30% and held, adding ~$50K in monthly recurring revenue.
- Wrote the team's onboarding guides and process documentation.

**Extreme Reach — Software Engineer → Senior Engineer** · 2016–2020
Adtech. Promoted junior to senior in two years.

- Led the Angular frontend rebuild of AdBridge for Sellers and owned technical planning across
  multiple teams; the product hit a $2M annual run rate in its first month.
- Introduced an ORM architecture across the C#/.NET backend, improving API consistency and
  readability.

## Selected Projects

- **Cleargate** — LLM gateway for production AI systems: declarative rules engine for cost control,
  PII redaction, and multi-provider routing (OpenAI, Anthropic, Bedrock), with real-time budget
  enforcement and a row-level-TTL cache for rolling-window analytics. Rust, React, TypeScript.
- **Federal Insights RAG** — searchable index of the federal congressional record (~20GB of bills,
  hearing transcripts, committee documents): scrape → transform → embed → query pipeline that runs
  on minimal hardware. Rust, React, Python.
- **AI-Release-Bot** (open source) — GitHub Action, listed on the GitHub Marketplace, that turns a
  software release into a ready-to-publish blog post.

## Skills

Rust · Python · TypeScript / React / Node · AI & agentic systems (agent runtimes, RAG, embeddings,
vector search, Langchain/Langgraph, multi-provider routing) · Postgres, Redis, ElasticSearch ·
AWS, Docker, Kubernetes, Terraform · GitHub Actions / CI/CD · Cedar authorization, SOC 2 logging ·
builds with coding agents daily

## Education

**Cleveland State University** — B.S. Computer Science · B.A. Economics
