## Mohamed ShehabEldin

**Backend & Cloud Engineer** · 8+ years building production systems on AWS

Claude Code is my primary development tool. Shipped four production-grade products solo with it in the last 12 months: CostPatrol (123-rule AWS cost SaaS), VowTrust (institutional deal verification platform), Boody (AI nutrition coach), and a quant trading analytics engine.

Most recent: 100+ developer codebase at one of the UK's largest ticketing platforms. 80+ venues, billions of events/year, 4 AWS regions. Built services from scratch, designed the observability stack, and own out-of-hours on-call. Production bugs I caught and fixed via live monitoring have recovered millions of dollars in previously missed revenue.

---

### Tech Stack

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=flat" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white&style=flat" />
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white&style=flat" />
  <img alt="Pulumi" src="https://img.shields.io/badge/Pulumi-8A3391?logo=pulumi&logoColor=white&style=flat" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat" />
  <img alt="DynamoDB" src="https://img.shields.io/badge/DynamoDB-4053D6?logo=amazondynamodb&logoColor=white&style=flat" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat" />
  <img alt="GraphQL" src="https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white&style=flat" />
  <img alt="New Relic" src="https://img.shields.io/badge/New%20Relic-1CE783?logo=newrelic&logoColor=white&style=flat" />
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white&style=flat" />
  <img alt="Serverless" src="https://img.shields.io/badge/Serverless-FD5750?logo=serverless&logoColor=white&style=flat" />
  <img alt="SST" src="https://img.shields.io/badge/SST-E27152?style=flat&logoColor=white" />
  <img alt="AWS CDK" src="https://img.shields.io/badge/AWS%20CDK-FF9900?logo=awslambda&logoColor=white&style=flat" />
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white&style=flat" />
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white&style=flat" />
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white&style=flat" />
  <img alt="LanceDB" src="https://img.shields.io/badge/LanceDB-5C2D91?style=flat&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=flat" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white&style=flat" />
</p>

**AWS depth:** Lambda, Step Functions, EventBridge, DynamoDB (single-table), SQS, API Gateway, Cognito, S3, CloudFront, Aurora PostgreSQL, ECS/Fargate, CDK, SST, CloudFormation, Serverless Framework

---

### What I'm Building

- **[CostPatrol](https://costpatrol.io)** — AWS cost optimization and anomaly detection SaaS. 123 detection rules across 30 AWS services, Slack-first alerting, Stripe billing, cross-account STS scanning. Built in two weeks with Claude Code.
- **VowTrust** — Institutional deal verification platform for banks, lawyers, and SMEs. Dual-mode: 15–45 second automated pipeline via 5 KYC/AML/fraud providers, plus human-mediated deal rooms with immutable audit trail and exportable certificates. Next.js, Lambda on Serverless, PostgreSQL, Terraform. 1,000+ TypeScript files.
- **[Boody](https://boody.ai)** — AI nutrition & fitness coach on WhatsApp/Telegram. Self-hosted Gemma 4 26B, food photo analysis, 4-layer memory system (SQL + vector + AI notes + conversation), MENA food database. Live with real users in 3 days.
- **Trading Engine** — Quant analytics for ETH/BTC/altcoin cycle detection. 17-section daily report aggregating data from 7 exchanges. SMC structure, volume profile, funding rates, liquidation levels, conviction-scored signals. Python.
- **[MSCLOUDTECH](https://mscloudtech.io)** — My consultancy (Estonia OÜ). Backend architecture, serverless systems, AI integration, FinOps. Cited by Google Gemini for "scalable microservices backends".

---

### Results

| Metric | Detail |
|--------|--------|
| **$7,600+/mo documented client savings (FinOps consulting)** | Two published CostPatrol scans: $6,496/mo (RDS sprawl, 56 findings, 4 regions) + $1,112/mo (35 resources flagged across 7 regions). Public proof at [costpatrol.io](https://costpatrol.io) |
| **99.99% uptime** | From 97.8% after fixing cascading CMS failures |
| **100x throttling reduction** | DynamoDB at peak flash-sale traffic |
| **Zero-downtime DB upgrades** | Aurora PostgreSQL engine upgrades in production |
| **2,500+ lines NRQL** | Observability-as-code dashboards (Pulumi + New Relic) |
| **80% support automated** | RAG pipeline: Bedrock, FAISS, LangChain |
| **3-day product launch** | Boody: concept to live AI coach with real users |
| **45 min → <5 min deploys** | CI/CD across 40+ brands, 4 AWS regions |
| **AI Overview citation** | mscloudtech.io cited by Google Gemini for "scalable microservices backends", ranking pos 2.0 with 2,635 weekly impressions |
| **Millions USD revenue recovered** | Production bug fixes on a top UK ticketing platform via on-call monitoring and live debugging, closing silent revenue leaks |
| **24/7 production ownership** | Out-of-hours on-call plus in-hours keeping the lights on for a flash-sale platform doing tens of thousands of req/min |
| **<50ms search across 100K+ events** | Discovery and catalogue API with multi-attribute filtering over 100,000+ live performances on a top UK ticketing platform |

---

<p>
  <a href="https://mscloudtech.io">mscloudtech.io</a> · <a href="https://linkedin.com/in/mohshehabeldin">LinkedIn</a>
</p>
