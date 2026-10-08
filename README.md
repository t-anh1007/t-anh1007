<div align="center">

<img src="assets/banner.svg" alt="Nguyễn Tuấn Anh — Fullstack Engineer" width="100%" />

<a href="https://nguyentuananh.me"><img src="https://img.shields.io/badge/Portfolio-nguyentuananh.me-111827?style=for-the-badge&logo=googlechrome&logoColor=white" /></a> <a href="https://www.linkedin.com/in/nguyntuananh"><img src="https://img.shields.io/badge/LinkedIn-nguyntuananh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="mailto:nguyntuananh.it@gmail.com"><img src="https://img.shields.io/badge/Email-nguyntuananh.it-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

### 👋 Hi, I'm Tuấn Anh

Information Systems student at **IUH** (HCMC). I build fullstack products on **event-driven microservices** — React · TypeScript · Node.js · PostgreSQL — and I work **spec-first, AI-native**: requirements and acceptance criteria first, then Claude Code / Codex drafts, then tests and cross-agent review before anything ships. On the BA side I turn workflows into use cases, business rules and testable acceptance criteria.

> **If you only have two minutes, look at these two systems 👇**

---

## ⭐ Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/t-anh1007/Badminton-Platform">
  <img src="assets/courtin-shot.jpg" alt="Courtin homepage" width="100%" />
</a>

### <img src="assets/courtin-logo.png" alt="" height="30" align="top" /> [Courtin — Badminton Platform](https://github.com/t-anh1007/Badminton-Platform)

Book courts in real time, find matches by skill level, and play **stake-backed competitive matches** — paid via VietQR, settled exactly once.

**🛠 Fullstack**
- **5 Node.js microservices** + API gateway, schema-per-service PostgreSQL, RabbitMQ events via a **transactional outbox**
- Match escrow across **3 services**: VietQR stake → score claim → **12-hour** dispute window → payout, settled exactly once
- React 19 web app with realtime booking & matchmaking — **500** concurrent sockets, `450 → 1` DB query

**📋 Business Analysis**
- Defined **62 core use cases** for players, court owners and admins, phased across 3 releases
- Wrote **198 Given/When/Then acceptance criteria**, validated by automated tests and **8 Playwright E2E journeys**

<p>
<a href="https://courtin-web.vercel.app"><img src="https://img.shields.io/badge/▶_Live_demo-courtin--web.vercel.app-F7E463?style=for-the-badge&labelColor=17456B" /></a>
</p>
<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.IO-010101?logo=socketdotio&logoColor=white" />
</p>

<sub>Full-Stack Developer & BA · team of 2 · Aug 2026 → now</sub>

</td>
<td width="50%" valign="top">

<a href="https://github.com/t-anh1007/CAB-Ride-Booking-System">
  <img src="assets/cab-shot.jpg" alt="CAB customer, driver and admin UI" width="100%" />
</a>

### 🚕 [CAB — Ride Booking System](https://github.com/t-anh1007/CAB-Ride-Booking-System)

A ride-hailing platform for customers, drivers and admins: quotes, driver matching, live tracking, ETA and surge pricing — with **Zero Trust** security.

**🛠 Fullstack**
- **11 microservices** + Python AI services behind one gateway
- Kafka dispatcher + outbox on the booking path: throughput **+74%**, p95 latency **−41%** under k6 load
- Auth service with RS256 JWT, OTP login and admin MFA — blocked **11/11** privilege escalations across 15 scenarios

**📋 Business Analysis**
- Mapped end-to-end **Customer, Driver and Admin** workflows: booking, matching, realtime tracking, payment, rating
- Specified role-based access requirements and an auth data model spanning **12 PostgreSQL tables**

<p>
<a href="https://github.com/t-anh1007/CAB-Ride-Booking-System#0-performance-benchmarks"><img src="https://img.shields.io/badge/📊_Benchmarks-k6_load_tests-2CE6A6?style=for-the-badge&labelColor=10231D" /></a>
</p>
<p>
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/k6-7D64FF?logo=k6&logoColor=white" />
</p>

<sub>Phase 1: Security Engineer · team of 9 · Phase 2: solo maintainer</sub>

</td>
</tr>
</table>

---

## 🧰 Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,python,react,vite,tailwind,nodejs,express,prisma,postgres,mongodb,redis,rabbitmq,kafka,docker,githubactions,vercel,railway&perline=9" />
</p>

## 🧠 How I work

- **Spec → tests → code.** Courtin started from 10 domain specs and 198 acceptance criteria.
- **Measure, don't guess.** Every performance claim links to a script you can rerun.
- **Design for failure.** Outbox, idempotency keys, exactly-once settlement, circuit breakers.

<div align="center">
<sub>Open to <b>Fullstack / Business Analyst internships</b> in Ho Chi Minh City — let's talk.</sub>
</div>
