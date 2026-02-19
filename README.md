# 👋 Hi, I'm Jacob Rushinski

**Full-Stack & Backend Software Engineer | Secure, Production-Grade Systems**

![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Actively%20Seeking-success)

---

## 🚀 About Me

Contract Full-Stack Software Engineer focused on building secure, production-grade systems with layered architectures, strict data boundaries, and real operational discipline.

I design and ship platforms that prioritize:

- Transactional integrity  
- Idempotent event processing  
- Security-first request pipelines  
- Clean service/repository layering  
- Deployment reliability and observability  

---

## 💼 Featured Work — RealDealKickz (Contract)

**Contract Full-Stack Software Engineer**  
*Nov 2025 – Present*

Replaced Shopify with a custom Next.js + Supabase commerce platform designed for reliability, security, and cost control.

**Key Outcomes**

- Reduced infrastructure costs by **58%** by migrating to a custom Next.js architecture using Supabase, Upstash Redis, AWS SES, and Vercel.
- Designed and implemented a layered e-commerce backend spanning **60+ API routes** with transactional order processing and strict repository boundaries.
- Achieved a **100% order success rate** with zero duplicate charges or inconsistent order states through Stripe + Shippo webhook signature verification and idempotent event persistence.
- Maintained **100% deployment uptime** with GitHub Actions CI/CD including migration validation, build verification, and post-deploy health checks.

**Security & Architecture Highlights**

- Built a centralized request proxy pipeline enforcing:
  - CSRF protection  
  - Upstash rate limiting  
  - MFA-based admin guardrails  
  - Security headers and request IDs  

- Secured **100% of authenticated and admin endpoints** with zero unauthorized access incidents.
- Implemented Stripe event idempotency via persistent `stripe_events` tracking.
- Enforced layered architecture: route → service → repository → DB.

Core platform design and operational model are documented across:

- System design and entity model :contentReference[oaicite:0]{index=0}  
- Security posture and proxy enforcement :contentReference[oaicite:1]{index=1}  
- Operational runbook and incident handling :contentReference[oaicite:2]{index=2}  
- Full system overview and stack boundaries :contentReference[oaicite:3]{index=3}  

---

## 🧠 Selected Engineering Projects

### Discord Title Automation Bot
**JavaScript · MongoDB · ADBKit · Tesseract.js**

- Orchestrated a Discord-to-device automation pipeline mapping user IDs to MongoDB records and executing queued ADB title assignments.
- Reduced manual title assignment time from ~1 minute to ~5 seconds through scoped device automation.
- Implemented image-based UI state detection with a 95% success rate across multiple layout variants.

---

### Discord Automation & Moderation Bot
**JavaScript · Discord.js · MongoDB**

- Built and deployed a modular, event-driven bot across 8 servers serving 900+ members.
- Reduced moderator workload by 60% via automated ticketing workflows and archiving 1000+ transcripts.
- Designed a verification pipeline that screened 500+ members in 2 months, eliminating raid/bot entries.

---

## 🛠 Technical Skills

**Languages:**  
TypeScript, JavaScript, Python, SQL, Go, Java, PHP, C++

**Frameworks & Runtime:**  
Node.js, Next.js, React, Flask, Discord.js

**Databases:**  
PostgreSQL, Supabase, MongoDB, MySQL

**Cloud & Infrastructure:**  
Vercel, AWS (SES), Stripe, Shippo, Upstash Redis, Docker, GitHub Actions (CI/CD)

**Security & Systems:**  
REST API Design, Authentication & Authorization, RBAC, Row-Level Security (RLS), CSRF Protection, Rate Limiting, Webhook Signature Verification, Idempotent Processing, Transactional Integrity, Queue-Based Concurrency Control

---

## 📫 Contact & Resume

- 📧 jacobrushinski@gmail.com  
- 💼 https://www.linkedin.com/in/jacob-rushinski/  
- 📄 [View My Resume](https://drive.google.com/file/d/1q8mDutfdI8c-crfWNWs2l8L5F-ZlLD3t/view?usp=sharing)

---

⭐ Currently seeking Backend / Full-Stack Software Engineering roles  
