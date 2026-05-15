<!-- ===================== -->
<!--  GitHub Profile README -->
<!-- ===================== -->

<h1 align="center">Hyeonsang Kim</h1>

<p align="center">
  Full-stack Engineer @ <b>Soundmind</b> · Founding Member @ <b>WIGTN Crew</b><br/>
  Building harnesses for AI workflows · Designing systems that run without humans in the loop
</p>

<p align="center">
  <a href="https://kims-portfolio-six.vercel.app/" target="_blank"><b>Portfolio</b></a>
  ·
  <a href="https://github.com/wigtn" target="_blank"><b>WIGTN</b></a>
  ·
  <a href="https://github.com/wigtn/wigtn-plugins-with-claude-code" target="_blank"><b>WIGTN-Coding Plugin</b></a>
</p>

---

## About

I work at the intersection of **B2B operational systems** and **AI-native engineering**.

- Designed a multi-tenant **auth & permission platform** from scratch, serving multiple B2B partners on a single infrastructure
- Solved high-throughput operational issues — reduced DB write load by **95%** under 3,000~5,000 events/min
- Building open-source **harnesses** that let AI agents produce consistent, verifiable output without human intervention
- Won **ByteDance Build with TRAE Hackathon (Grand Prize)** and **Snowflake AI & Data Hackathon Korea (Runner-up)** with multi-agent verification workflows

> "Systems run reliably not because someone patches them every time, but because they're built to not break without a human in the loop."

---

### Tech Stack

**Frontend & Mobile**
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
</p>

**Backend & Data**
<p>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
</p>

**AI & DevOps**
<p>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
</p>

---

## Current Work @ Soundmind

Working on a B2B platform that ships pre-installed child-safety services to OEM devices (e.g., Galaxy Kids phones) via partners like Norang Market.

### 🔐 Unified Auth & Permission Server
- Designed solo — a single auth infrastructure serving multiple white-label partner services
- **Token Rotation + Token Family Tracking** to detect refresh-token reuse attacks
- **RBAC**, **PII lifecycle automation**, **Audit Log** for full operational traceability
- **Retry + DLQ** with a recovery console for partial-failure recovery without ops handholding

### 📍 ODIYA — Real-time Child Location Service
- Redis buffering + batch processing redesign → **95% reduction in DB write load** at 3,000~5,000 events/min
- Haversine-based safe-zone entry/exit detection
- OTA pipeline with HotUpdater + Supabase
- Contributed to **~230% B2B revenue growth** through platform stabilization

### 📱 Mohani — Remote Device Control
- Real-time app monitoring & blocking via Android AccessibilityService
- Samsung Knox Firewall integration for domain-level access control
- Diagnosed and eliminated recurring ANR caused by RN Bridge Queue + Knox IPC + Broadcast timeout

### 🏛️ KOCCA — Korean Language Assessment (National R&D)
- Full-stack Next.js + Prisma + PostgreSQL platform for foreign-student Korean proficiency evaluation
- 16kHz WAV recording → AWS S3 → external STT pipeline

---

## WIGTN Crew

Founding member of **WIGTN**, a 5-person AI engineering crew building harnesses and tools for AI-native development.

### 🔌 WIGTN-Coding — Multi-Agent Development Harness for Claude Code
A plugin that lets multiple AI agents collaborate on real codebases without losing context or quality.

- Role-based SKILL.md definitions for PRD writing, architecture design, parallel development, and code review
- **Validation gates** between stages — only output that passes quality checks advances
- Designed for teams: the same workflow that works for one developer scales to many
- → **Repo:** https://github.com/wigtn/wigtn-plugins-with-claude-code

---

## Achievements

- 🏆 **Grand Prize** — ByteDance Build with TRAE Hackathon (multi-agent debate platform with built-in verification)
- 🥈 **Runner-up** — Snowflake AI & Data Hackathon Korea

---

## Portfolio

🌐 https://kims-portfolio-six.vercel.app/

---

## Languages

- 🇰🇷 Korean (Native)
- 🇺🇸 English (Professional)
- 🇩🇪 German (Basic)
- 🇯🇵 Japanese (Learning)

---

## Contact

Open to conversations about **AI harnesses**, **multi-agent workflows**, and **enterprise-grade AI systems**. Reach out anytime.
