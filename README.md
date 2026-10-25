![Header](./headerimage.jpeg)

<h1 align="center">Mayur Gadakh</h1>
<p align="center"><strong>Full-Stack & AI Engineer · SaaS & Fintech · India 🇮🇳</strong></p>

<p align="center">
  <a href="https://mayurgadakh.dev">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/mayurgadakh/">LinkedIn</a> ·
  <a href="mailto:mayurgadakh12@gmail.com">Email</a> ·
  <a href="https://twitter.com/Mayur_S_G">X / Twitter</a>
</p>

I build **AI SaaS products and fintech systems** with TypeScript, React, Node.js, and PostgreSQL. I enjoy owning the full stack-from database design and background jobs to the interface and deployment.

Currently a **Full Stack Developer at Dapton Technologies**, engineering a multi-tenant payments platform with payment routing, tokenization, subscription billing, and fraud/risk controls.

Outside work, I build **[Docup](https://docup.dev)**, **[Makewise](https://makewise.dev)**, and **[Resumly](https://resumly.dev)**-products that help people document code, build apps, and tailor resumes with AI.

## What I'm building

### [Docup](https://docup.dev) - Documentation that keeps up with your code

Connect a GitHub repository, generate a documentation draft, edit it, and publish a hosted docs site. When the code changes, Docup updates affected pages and proposes changes to pages you've edited.

- **Code-to-docs pipeline:** AI explores repositories through read-only file tools, plans the documentation, and writes pages with bounded concurrency, retries, and model fallback.
- **Updates from GitHub pushes:** Signed webhooks trigger background jobs that identify affected pages. Manual edits are preserved through suggestions you can review and apply.
- **Ask AI:** Published docs are chunked and embedded in Qdrant. Readers get streamed answers based on retrieved documentation, with links to the source pages.
- **Hosted docs:** Markdown-backed rich-text editing, private drafts, custom domains, branding, page search, SEO controls, and reader analytics.
- **Backend reliability:** Redis caching and rate limits, webhook deduplication, and deployment-aware response caching on Cloudflare Workers.

**Built with:** TypeScript · React · vinext · Tailwind CSS · Cloudflare Workers & R2 · PostgreSQL · Drizzle ORM · Redis · Trigger.dev · Vercel AI SDK · Google Vertex AI · Qdrant · Better Auth · Tiptap

### [Makewise](https://makewise.dev) - Build and edit web apps through chat

A platform for non-technical users to connect a GitHub repository and modify a web app through a chat interface, with a live preview.

- Automatically configures the development environment and keeps code out of the main editing flow.
- Provides controls to create pull requests or push changes to the main branch.

**Built with:** Next.js · TypeScript · AI Agents · Docker · WebContainers · Tailwind CSS

### [Resumly](https://resumly.dev) - AI resume builder

A SaaS application for parsing resumes into structured data, tailoring them to job descriptions, and exporting PDFs, with a focus on ATS keyword alignment.

- Built resume parsing and tailoring workflows using structured JSON and chained prompts.
- Used Inngest for background AI processing and Azure Blob Storage for files.

**Built with:** React · Next.js · Node.js · PostgreSQL / Supabase · OpenAI API · Inngest · Auth.js · Azure Blob Storage

## Experience

### Dapton Technologies - Full Stack Developer

**Mar 2026 – Present · Pune, Maharashtra**

- Engineer backend and frontend systems for a multi-tenant payments platform, including payment routing, tokenized card-data handling, subscription billing, and fraud/risk rule engines.
- Own architecture decisions, code reviews, and CI/CD workflows under security and compliance requirements.
- Build internal tooling, including AI-assisted data generation for staging and demo environments.

### [Bhumeet Digital Pvt. Ltd.](https://bhumeet.in) - Junior Software Engineer

**Mar 2025 – Jan 2026 · Nashik, Maharashtra**

- Built React interfaces and Node.js services for a drone flight planning platform handling **500+ monthly surveys**, including an AI anomaly detection interface.
- Optimized PostgreSQL spatial queries, reducing map tile rendering latency from **8 seconds to 2 seconds**.
- Designed REST API contracts connecting the drone hardware SDK to the web dashboard for real-time telemetry.

### [Manasvi Tech Solutions Pvt. Ltd.](https://manasvi.tech) - Junior Fullstack Developer

**Jun 2024 – Feb 2025 · Nashik, Maharashtra**

- Delivered **15+ features**, including OAuth flows, role-based dashboards, and REST APIs handling **10,000+ daily requests**.
- Reduced JavaScript bundle size by **40%** and initial page load time by **3 seconds**, improving Lighthouse scores from approximately **55 to 85+**.
- Designed and maintained PostgreSQL schemas, keeping API response times below **200 ms** at peak load.

## Technologies I work with

| Area | Technologies |
| --- | --- |
| Frontend | TypeScript, React, Next.js, vinext, Tailwind CSS |
| Backend | Node.js, NestJS, Express, REST APIs, Better Auth, Auth.js |
| Data & storage | PostgreSQL, Drizzle ORM, Prisma, Redis, Qdrant, Supabase, Cloudflare R2, Azure Blob Storage |
| AI | Vercel AI SDK, Google Vertex AI, OpenAI API, LangChain, RAG, embeddings, tool calling |
| Background jobs | Trigger.dev, Inngest, BullMQ |
| Infrastructure | Cloudflare Workers, Docker, CI/CD, Google Cloud, Azure |

**Engineering focus:** Multi-tenant architecture · Payments & fintech · Authentication & access control · Background workflows · Caching & performance

## What I'm exploring

- Improving retrieval quality and evaluating AI-generated answers.
- Designing background workflows that recover cleanly from failures.
- Making applications faster through caching, query optimization, and profiling.

I value consistency, readable code, and building useful products. **Code. Learn. Build. Ship. Repeat.**

---

**Open to full-stack and AI engineering opportunities · Remote / Hybrid**
