# Product Content Specification: Full-Stack Developer Portfolio

Content source of truth for populating the layout defined in `DESIGN.md`, based on Tran Thu Thuy's resume. Positioning: **Full-stack Developer** — backend-heavy (PHP/Node.js) with recurring frontend delivery (ReactJS, Angular, Next.js) across shipped projects.

## 1. Identity

| Field | Value |
|---|---|
| Name | Tran Thu Thuy |
| Title / Role | Full-stack Developer (Backend-leaning) |
| Years of experience | 5 years (Jan 2021 – present) |
| Education | Hanoi University of Science, VNU — B.Sc. Computer and Information Science, 2017–2021 |
| Location basis | — (not provided; leave field blank/omit) |

## 2. Header (Section 5.1)

*   **Logo / left:** "Tran Thu Thuy"
*   **Nav links:** About, Projects, Experience, Contacts
*   **Language switcher:** En / Vi (resume is bilingual-context; default to En, offer Vi)

## 3. Hero Section (Section 5.2)

*   **Staggered heading:** "Full-stack" / "Developer"
*   **Mission statement (short):**
    > "Backend-focused full-stack developer with 5 years of experience building scalable APIs, event-driven systems, and the React/Angular/Next.js interfaces around them."
*   **CTA button:** "Projects →"
*   **Social links row:** Email, Phone — only include icons for accounts the user actually provides; do not fabricate profile URLs (GitHub/LinkedIn not yet supplied).

## 4. Featured Projects Carousel (Section 5.3)

Pick the most visually/technically distinct projects for cards. Suggested order (most recent & most complete stack first):

1. **Talent Solution** (06/2025 – 02/2026)
   *   Description: Scalable multi-tenant ATS with industry-specific data segmentation and candidate recruitment workflows.
   *   Stack: NestJS, Next.js, Apache Kafka, PostgreSQL, Redis, Elasticsearch, S3/MinIO
   *   Highlight: Kafka/Debezium pipelines syncing data from CareerViet; multi-tenant data isolation by owner.

2. **CareerViet** (06/2025 – 02/2026)
   *   Description: Global recruitment & talent management ecosystem (B2C + B2B).
   *   Stack: NestJS, Next.js, Apache Kafka, PostgreSQL, Redis, Elasticsearch
   *   Highlight: Kafka + Debezium CDC streaming Postgres → Elasticsearch for instant search; BullMQ-driven async PDF/email workflows via AWS SES.

3. **Social Community Service** (07/2024 – 06/2025)
   *   Description: Social network increasing interaction between users, service providers, and operations staff.
   *   Stack: PHP Yii2, Angular, MySQL, Redis
   *   Highlight: Redis caching layer to remove DB bottlenecks under heavy concurrency.

4. **Tomonokai** (04/2024 – 07/2024)
   *   Description: High-volume payment processing & automated ledger platform for enterprise subscriptions.
   *   Stack: PHP Laravel, MySQL, Docker, Amazon S3
   *   Highlight: PCI-DSS compliant Stripe/PayPal gateway integration.

Each card: title, 1–2 line description, stack tags, "Read more →" pill button.

## 5. About & Skills Section (Section 5.4)

**Intro copy:**
> "Hello! I'm Thuy — a backend-focused full-stack developer with 5 years of experience designing microservices and event-driven systems, with hands-on database administration and a growing frontend toolkit (React, Angular, Next.js)."

**Skills breakdown (map to DESIGN.md's pill/category blocks):**

*   **Front-end:** ReactJS, Angular, Next.js, HTML5/CSS3, Bootstrap, SCSS
*   **Back-end:** PHP (Laravel, Yii2, CakePHP), Node.js (NestJS), RESTful API, Microservices
*   **Databases & Caching:** MySQL, PostgreSQL, MongoDB, Redis, Elasticsearch, Apache Kafka
*   **DevOps & Cloud:** Docker, Linux (Ubuntu/CentOS), AWS (S3, SES), MinIO
*   **Practices & Tools:** Git, Agile/Scrum, Database Administration (query optimization, index tuning, replication), AI-assisted development (Cursor IDE, Claude AI for prototyping/tests/refactoring)

Note: front-end weight is real but secondary — Skills section should visually rank Back-end and Databases above Front-end to stay honest about seniority level per role (title says "PHP Developer" / "Back-end Developer" in the source resume).

## 6. Work Experience Section (Section 5.5)

| Date range | Company | Role | Stack |
|---|---|---|---|
| May 2022 – present | MOR SOFTWARE JSC | Software Engineer / Back-end Developer | NestJS, PHP |
| Jan 2021 – Apr 2021 | JVB VIETNAM | Software Engineer | PHP, MySQL, PostgreSQL, JavaScript |

*   **Active row (current job):** MOR SOFTWARE JSC — reversed color treatment per design.
*   **Footer summary:** "Work experience: 5 years" (Jan 2021 – present).

## 7. Contact Section

| Channel | Value |
|---|---|
| Email | tranthuthuy.job@gmail.com |
| Phone | 0868694534 |
| GitHub / LinkedIn | not provided — leave off nav/social row until supplied |

## 8. Portrait / Photo

Placeholder only — swap before launch: `/assets/portrait-placeholder.jpg` (generic grayscale silhouette or plain avatar). Do not source a real photo without the user's own file.

## 9. Open Items / Needs Confirmation

*   Portrait photo is a placeholder (see §8) — user will supply the real one later.
*   GitHub/LinkedIn URLs still missing — add to Hero social row and Contact section once available.
*   Confirm whether to frame the title as "Full-stack Developer" (as requested) or keep the resume's literal "Back-end Developer" title with "full-stack capable" framing in the subtext.
*   Confirm which 4 projects to feature in the carousel (6 more exist: GPROCESS, OKR, COUPON, SAGBRAIN) if a different emphasis is wanted.
