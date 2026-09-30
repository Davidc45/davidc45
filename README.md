<h1 align="center">David Calderon</h1>

<p align="center">
  <b>Full-Stack Software Engineer</b> · CS, Cal State Fullerton (2026) · Orange County, CA
</p>

<p align="center">
  <a href="https://alleyesonme.cc/"><img src="https://img.shields.io/badge/Portfolio-alleyesonme.cc-111?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/david-calderon-07554a243"><img src="https://img.shields.io/badge/LinkedIn-davidcalderon-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:davidcalderon4000@gmail.com"><img src="https://img.shields.io/badge/Email-davidcalderon4000%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I build full-stack products end to end: Postgres schemas and access rules, APIs, and the UI people actually use. I've led a four-person team from design to a live launch, shipped client sites with real traffic, and I like the unglamorous parts: failure handling, caching, auth, and keeping services alive.

**Open to:** entry-level full-stack / software engineer roles · remote, hybrid, or onsite · relocating anywhere in the U.S.

---

## Featured work

### [Cora](https://cora.fyi) — community safety reporting PWA
*PM + Lead Full-Stack · team of 4 · presented at CSUF ECS Expo 2026*

- Location-based incident reports on **PostGIS**, with **Row Level Security** enforcing a tiered trust model (guest → registered → phone-verified via **Twilio Verify**)
- Real-time report feeds via Supabase subscriptions; installable PWA with service workers; bot protection with Cloudflare Turnstile; transactional email via Resend

`Next.js` `React` `TypeScript` `Supabase` `PostgreSQL/PostGIS` `Google Maps API` `Tailwind` `Vercel`

### [Aliquot](https://github.com/Davidc45/aliquot) — lab chain-of-custody API · [live](https://aliquot.onrender.com)

- Flask + PostgreSQL middleware for kit orders and sample chain-of-custody, written in **raw SQL** (no ORM)
- Containerized with **Docker** and deployed on Render

`Python` `Flask` `PostgreSQL` `Docker`

### [RentSignal](https://rent-signal.vercel.app/) — rent affordability by city

- Merges **U.S. Census ACS** median rent with **Zillow ZORI** data in a Next.js route handler: Census failure fails the request, Zillow failure degrades gracefully, 10s abort timeout, one-day shared cache
- **Vitest** coverage on data normalization, affordability boundaries, CSV parsing, and source merging; team repo with protected `main` and PR review
- Migrated off the original AWS AppSync / Lambda / DynamoDB GraphQL backend to a simpler serverless route

`Next.js` `Redux Toolkit` `Vitest` `GraphQL` `AWS`

### [All Eyes On Me](https://alleyesonme.cc/) — self-hosted portfolio + 24/7 livestream

- RTSP camera → MediaMTX → **LL-HLS**, proxied through a Next.js route so the browser never touches the media server
- Runs on a home machine behind **Cloudflare Tunnel**: three Windows services, a scheduled watchdog on `/api/health`, and an Anthropic SDK chat agent with live status from Notion

`Next.js` `HLS` `Cloudflare Tunnel` `Anthropic SDK`

### [Calderon Bulldogs](https://calderonbulldogs.com/) — client site via Altitud

- Booking, galleries, CMS, PayPal payments, email notifications, and SEO; **2K+ visitors**
- Recruited, interviewed, and onboarded the build team as co-founder of [Altitud](https://altitud.io)

`Next.js` `TypeScript` `PostgreSQL` `Prisma` `PayPal API`

---

## 🔨 Currently building

**Encore** — a ticketing platform focused on the hard backend problems: Stripe payments and webhooks, live seat holds, inventory under concurrent purchase, background jobs, and RBAC.

---

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,react,nextjs,nodejs,flask,postgres,supabase,prisma,graphql,redux,tailwind,docker,aws,vercel,cloudflare,vitest,git&perline=10" alt="Tech stack">
</p>

**Languages:** TypeScript, JavaScript, Python, SQL, HTML/CSS
**Backend & data:** Node.js, Flask, PostgreSQL/PostGIS, Supabase (RLS, realtime), GraphQL, REST
**Frontend:** React, Next.js, Redux Toolkit, Tailwind CSS, PWAs
**Infra & tooling:** Docker, Vercel, Render, AWS (AppSync, Lambda, DynamoDB), Cloudflare, Vitest, Git
