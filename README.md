<p align="center">
  <img src="./header.svg" alt="Ray (MyungJin Ko) — Software Engineer" width="100%">
</p>

# Hi 👋, I'm Ray (MyungJin Ko)

### Software engineer who builds and operates what I ship

I co-founded a startup and spent 5 years as its founding engineer — taking a B2B multi-tenant SaaS from **zero to 10+ business customers**, absorbing event-day peaks of **~25K concurrent users with zero downtime**, and operating everything I shipped, from the UI down to the infrastructure and the on-call that follows.

- 🌱 Going deeper on **system design & architecture that stays simple and reliable as it scales**
- 🚀 Looking to help build **ambitious global products where the engineering bar is high** — developer tools, AI, or deep tech — and own problems from zero to one
- 🛠 Polyglot by choice: shipped production systems in **TypeScript, Rust, Java, and C#** — the problem picks the tool
- 📫 Reach me at **rayleighko2@gmail.com** · [linkedin.com/in/rayleighko](https://linkedin.com/in/rayleighko)
- 📄 Résumé — **[English (PDF)](https://github.com/rayleighko/rayleighko/raw/main/resume.pdf)** · **[국문 (PDF)](https://github.com/rayleighko/rayleighko/raw/main/resume_ko.pdf)**
- ⚡ Fun fact — I built and ran a company for 7 years before returning to full-time engineering, and I'm a devoted cat person 🐈

## 🚧 Now building

**[The Bearings](https://www.thebearings.app)** — which economic regime is your portfolio betting on? A regime read for what you already hold. Solo-built and operated: Next.js 16 · React 19 · Supabase (Postgres RLS) · Claude-powered briefings behind a 3-layer safety filter · PWA on Vercel. Docs-first engineering with architecture decision records.

## 📝 Writing — production systems I built and operated

- **[Self-Service Domains: Letting Customers Provision DNS Without Talking to Us](발행 URL)** — slug uniqueness in Postgres, a four-step Vercel domain pipeline, and the day-2 gaps that stayed manual
- **[The 403 That Redesigned Our Auth: Three Login Systems, One Rust Middleware](https://ray-k.medium.com/the-403-that-redesigned-our-auth-three-login-systems-one-rust-middleware-2ba39ae935ee)** — how three identity classes accumulated, why a valid token still failed, and unifying enforcement without merging identity
- **[1,000 on a Normal Day, 25,000 on Event Day: Capacity Planning When Your Spikes Are Scheduled](https://ray-k.medium.com/1-000-on-a-normal-day-25-000-on-event-day-capacity-planning-when-your-spikes-are-scheduled-0693a3681ab3)** — absorbing a 25× event-day spike with no autoscaler: caches, serverless bursts, and a capped worker, layer by layer
- **[When Serverless Stops Making Sense: Moving Bulk PDF Generation to a Rust Worker](https://ray-k.medium.com/when-serverless-stops-making-sense-moving-bulk-pdf-generation-to-a-rust-worker-1de5074ce036)** — why per-invocation Chromium broke down, the axum worker that replaced it, and a [reproduction benchmark](https://github.com/rayleighko/pdf-worker-benchmark) (3.2× on bulk exports)
- **[The Event Is the Tenant: Multi-Tenancy for a Business Where Customers Are Projects, Not People](https://ray-k.medium.com/the-event-is-the-tenant-multi-tenancy-for-a-business-where-customers-are-projects-not-people-90a5763bf79f)** — identity, isolation, and billing scoped to events; ~$100/mo infra serving ₩5–10M-per-event contracts, and what I'd redesign

More at [ray-k.medium.com](https://ray-k.medium.com)

```typescript
const ray = {
  name: "MyungJin Ko (Ray)",
  role: "Software Engineer",
  edge: "builds and operates what I ship — adapts to any stack",
  exFounder: true,            // 7 years, took products 0 → 1
  nowBuilding: "cohort.co.kr",
  nowChasing: "system design × scale",
  catPerson: true,            // 🐈
  motto: "If things are not failing, you are not innovating enough.",
};
```

## 🛠 Tech stack

<p align="center">
  <img src="./tech_card.svg" alt="Tech Stack — Frontend, Backend, Data, Infra" width="100%">
</p>

## Connect

[![GitHub](https://img.shields.io/badge/GitHub-rayleighko-181717?logo=github&logoColor=white)](https://github.com/rayleighko)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rayleighko-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/rayleighko)
[![Medium](https://img.shields.io/badge/Medium-@ray--k-000000?logo=medium&logoColor=white)](https://medium.com/@ray-k)
[![LeetCode](https://img.shields.io/badge/LeetCode-rayleighko-FFA116?logo=leetcode&logoColor=white)](https://leetcode.com/rayleighko)
