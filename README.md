<div align="center">

# Maxim - Full-Stack Developer

Remote · Ukraine

[![Email](https://img.shields.io/badge/Email-demolovfennec%40gmail.com-333?style=flat&logo=gmail&logoColor=white)](mailto:demolovfennec@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@volnowan-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/volnowan)
[![Portfolio](https://img.shields.io/badge/Portfolio-dml--central.dev-000?style=flat&logo=vercel&logoColor=white)](https://dml-central.vercel.app)

</div>

---

## About

18, full-stack developer working remotely out of Ukraine. About a year and a half hands-on with Node.js — enough to take a real-time. Already making projects what can easily go in production.

Know advanced fundamentals — architecture, design patterns and can code in different modern and popular frameworks for frontend, backend, docker, 3D and CI/CD.

Outside client-shaped work, I build creative sites with 3D graphics and animation.

## Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,nestjs,prisma,postgres,redis,docker,githubactions,threejs,svelte" />
</div>

**Frontend** — Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS v4, shadcn/ui, Zustand, React Hook Form, Zod, SvelteKit

**Backend** — NestJS 11, Prisma 7, PostgreSQL 16, Redis 7, BullMQ, Passport + JWT, Socket.IO, Stripe, Swagger/OpenAPI

**3D & Animation** — Three.js, React Three Fiber, drei, GSAP, ScrollTrigger/ScrollSmoother, custom GLSL shaders

**DevOps** — Docker Compose, GitHub Actions, Turborepo, pnpm workspaces, Vercel

**Testing** — Jest, ts-jest, Vitest, Playwright

## Projects

### [COS Code — AI SaaS Platform](https://github.com/DML142/saas-ai-fullstack-portfolio)
`Next.js` `NestJS` `Prisma` `PostgreSQL` `Redis` `BullMQ` `Socket.IO` `Stripe`

Production-shaped SaaS platform in a pnpm/Turborepo monorepo, built to demonstrate a complete, real backend — not a demo.

- JWT access + rotating refresh tokens, Redis-tracked token families with replay/reuse detection; Google OAuth with email-based account linking
- RBAC (USER/PREMIUM/ADMIN) kept separate from billing tier
- Stripe billing through a raw-body, signature-verified, idempotent webhook handler as the single source of truth for subscription state
- Redis-backed rate limiting that fails open rather than locking users out on a Redis outage
- WebSocket chat gateway with a tier-gated, Redis-counted monthly quota
- Full stack — Postgres, Redis, Mailpit, backend, frontend, Stripe CLI forwarding — comes up with one `docker compose up`

Still working on getting this project up in public.

### [dml-central (soon dml-central.dev)](https://dml-central.vercel.app) 
`Next.js` `Three.js` `R3F` `GSAP` `Playwright` `Zod` `React Hook Form` `Husky` `Telegram`

- WebGL particle-network hero: custom depth-driven point shader, pointer repulsion, static SVG fallback for no-WebGL/no-JS
- Full i18n (EN/UA/RU) with a typed dictionary, no i18n library
- 240+ unit tests, 400+ E2E tests across five browser/device profiles
- Bundle trimmed from ~500KB to ~300KB gzipped via code-splitting and lazy-loaded chunks
- Telegram integration for form sending without any backend - only Next.js API Routes

### [DML's Solutions](https://dml-142.vercel.app/) — *archived*
`Next.js` `Three.js` `R3F` `GSAP`

First creative site taken to a finished, deployed state — heavy 3D and custom shaders. Proof of interactive front-end work, no longer maintained.

## Languages

Ukrainian (native) · Russian (native) · English (working proficiency)

---
<div align="center">
  
## Personal plans on future

Use [this](dml-central.dev) domain

Deploy COS Code

</div>
---

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=DML142&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DML142&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</div>
