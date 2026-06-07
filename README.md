<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1f3c,100:1a0a0a&height=140&section=header&text=Usman%20Ghani&fontSize=52&fontColor=ffffff&fontAlignY=55&desc=Mobile%20Engineer%20%C2%B7%20AI%20Integration%20%C2%B7%20Full-Stack%20Development&descSize=14&descAlignY=78&descColor=aaaaaa&animation=fadeIn" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1f3c,100:1a0a0a&height=140&section=header&text=Usman%20Ghani&fontSize=52&fontColor=ffffff&fontAlignY=55&desc=Mobile%20Engineer%20%C2%B7%20AI%20Integration%20%C2%B7%20Full-Stack%20Development&descSize=14&descAlignY=78&descColor=aaaaaa&animation=fadeIn" />
</picture>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&multiline=false&width=600&lines=BS+Computer+Science+%2727+%C2%B7+Lahore%2C+Pakistan;6%2B+Published+Apps+%C2%B7+Android+%26+iOS;Building+production-grade+AI-powered+systems)](https://git.io/typing-svg)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=code-with-usmang&label=Profile+Views&color=1a3a6b&style=flat-square)

<br/>

<p>
  <a href="https://www.linkedin.com/in/usmanghanics/">
    <img src="https://img.shields.io/badge/LinkedIn-0a1628?style=for-the-badge&logo=linkedin&logoColor=2F81F7" />
  </a>
  &nbsp;
  <a href="mailto:usmanghanii7729@gmail.com">
    <img src="https://img.shields.io/badge/Email-0a1628?style=for-the-badge&logo=gmail&logoColor=cc2222" />
  </a>
  &nbsp;
  <a href="https://x.com/USMAANGF">
    <img src="https://img.shields.io/badge/Twitter-0a1628?style=for-the-badge&logo=x&logoColor=ffffff" />
  </a>
  &nbsp;
  <a href="https://veloq.tech">
    <img src="https://img.shields.io/badge/Veloq.tech-0a1628?style=for-the-badge&logo=google-chrome&logoColor=2F81F7" />
  </a>
</p>

</div>

---

## About

Mobile engineer building production-grade, AI-integrated applications — not prototypes. I architect from day one with proper state management, cloud functions, scalable data models, and clean system design.

Currently contributing to **[Veloq](https://veloq.tech)** — an engineer-led AI software house delivering agentic systems, RAG pipelines, and full-stack AI products for clients across healthcare, logistics, and enterprise.

```text
Currently building  →  Leafiyo — AI-powered ebook SaaS for the francophone market
Interests           →  Agentic AI · LLM Integration · Mobile Systems · Workflow Automation
Open to             →  Collaborations · Freelance · Production-grade engineering roles
```

<br/>

---

## Published Apps

> 6+ apps live across the **Google Play Store** and **Apple App Store**, published under [Bluex Software Solutions](https://play.google.com/store/apps/developer?id=Bluex+Software+Solutions).

### Client & Business Apps — Android & iOS

| App | Description | Play Store | App Store |
|-----|-------------|:----------:|:---------:|
| **Makki AutoCare** | Smart automotive service booking platform with real-time scheduling, service history, and business analytics | [▶ Play](https://play.google.com/store/apps/details?id=com.bizcare.makki_autocare) | [⬛ App Store](https://apps.apple.com/us/app/makki-autocare/id6752372809) |
| **BizCare** | End-to-end business management solution with operations, client tracking, and financial oversight | [▶ Play](https://play.google.com/store/apps/details?id=com.bizcare.bizcare) | [⬛ App Store](https://apps.apple.com/us/app/bizcare/id6752336703) |
| **BizParta** | Business support platform with integrated support portal and compliance pages | [▶ Play](https://play.google.com/store/apps/details?id=com.bizcare.bizparta) | [⬛ App Store](https://apps.apple.com/us/app/biz-parta/id6752411960) |

### Personal Apps — Android Only (Google Play)

| App | Description | Stack | Play Store |
|-----|-------------|-------|:----------:|
| **SnapCut** | Professional audio & video editor — multi-track editing, FFmpeg rendering, media effects | Flutter · FFmpeg | [▶ Play](https://play.google.com/store/apps/details?id=com.bluex.soundy) |
| **Clippy** | Smart clipboard assistant — persistent clipboard history with quick-access management | Kotlin | [▶ Play](https://play.google.com/store/apps/details?id=com.bluex.clippy) |
| **Scannix** | Document scanner with OCR, edge detection, and PDF export | Kotlin | [▶ Play](https://play.google.com/store/apps/details?id=com.bluex.scanix) |

<br/>

---

## Featured Projects

### Leafiyo — AI-Powered Ebook Generator *(In Development)*

> SaaS platform for generating, downloading, and selling AI-authored digital products — targeting the global francophone market with support for French, English, Spanish, and German.
> **Repo:** [github.com/ayeshag7/Leafiyo](https://github.com/ayeshag7/Leafiyo)

**What it does:**
- Users input a topic or keyword → AI generates 5 title/description ideas via Claude Sonnet 4
- Select a tier (Basic / Mid / Premium), choose from 3 AI-generated covers, then generate the full ebook
- Illustrated Books and comic-style formats available via the "Leafiyo Stories" flow with character-consistent image generation
- Credit-based economy: Stripe (international) + CinetPay (francophone Africa), with atomic deduct/refund operations

**Architecture highlights:**
- Long-running jobs (60–120s) handled via async job queue — API returns `job_id` instantly, frontend polls status
- Character consistency enforced by injecting the character card verbatim into every sequential Gemini image prompt
- All PDF generation via PDFKit/Puppeteer; signed download URLs owner-restricted to 1-hour windows
- Admin panel: KPI dashboards, user management, promo codes, payment toggles, Meta Pixel/GA4/GTM config

**Stack:** `Next.js 14` · `Supabase (PostgreSQL)` · `Claude Sonnet 4` · `Gemini Image via fal.ai` · `Stripe` · `CinetPay` · `Vercel`

---

### DOS2-AI — AI-Powered Condo Management Platform *(Contributor)*

> Multi-tenant property management SaaS for Ontario condo corporations — AI email triage, RAG-powered Q&A, WhatsApp concierge, and automated Status Certificate generation.
> **Repo:** [github.com/usmansafdarktk/DOS2-AI](https://github.com/usmansafdarktk/DOS2-AI) · **Role:** Frontend development · Backend integration · API wiring

**Key capabilities:**
- **WhatsApp AI Concierge** — LangGraph state machine routes residents by role and intent: balance inquiries, amenity booking, complaints, visitor parking, and emergency escalation
- **AI Email Triage** — Polls shared Gmail inbox every 5 minutes, classifies by category and risk, generates action text and priority scores via Groq (llama-3.3-70b)
- **RAG Q&A** — Gemini embeddings (768-dim) over governance documents via pgvector; residents and managers query building rules in natural language
- **Status Certificate Engine** — Auto-populates Ontario SC forms from live DB, corp profile, and RAG search; generates XFA PDF via XML injection
- **Emergency Detection** — Classifies resident WhatsApp messages; triggers a 60-second cancellable manager alert

**Stack:** `React/Vite` · `FastAPI (Python)` · `PostgreSQL + pgvector` · `LangGraph` · `Groq` · `Gemini` · `WhatsApp Cloud API` · `GCP Cloud Run`

---

### BizCare ERP — Business Operations Platform

> Comprehensive ERP solution for SMBs — operations management, client tracking, invoicing, and analytics in a unified platform, live on both Android and iOS.

- Full CRUD operations across client, staff, and service management modules
- Real-time analytics dashboard with revenue tracking and performance metrics
- Cross-platform delivery (Flutter) with Firebase backend, push notifications, and offline support

**Stack:** `Flutter` · `Firebase` · `REST APIs` · `Android` · `iOS`

---

### Makki AutoCare — Smart Auto Service Platform

> End-to-end automotive service booking platform for Makki Oil Store, live on Android and iOS.

- Real-time appointment scheduling with service catalog management
- Customer profile tracking, service history, and personalized recommendations
- Business analytics dashboard with revenue and service performance metrics

**Stack:** `Flutter` · `Firebase` · `Android` · `iOS`

---

### SnapCut — Professional Audio & Video Editor

> Feature-rich multimedia editor for Android with multi-track audio editing and high-performance video processing. **[▶ Play Store](https://play.google.com/store/apps/details?id=com.bluex.soundy)**

- Multi-track audio layering, mixing, and real-time preview
- Video trim, cut, merge, and effects pipeline powered by FFmpeg
- Optimized encoding and export; direct integration with device media library

**Stack:** `Flutter` · `FFmpeg` · `Kotlin` · `Android`

---

### Additional Work

| Project | Description |
|---------|-------------|
| **Lost & Found Management System** | University project — students report lost/found items; AI-assisted matching surfaces relevant claims to the right users |
| **n8n Lead Generation Automation** | Outbound leads automation pipeline built for client delivery — email sequencing, personalization, and reply routing |
| **Car Insurance Automation (France)** | Optimized and extended an existing n8n workflow for a French automotive insurance company |

<br/>

---

## Academic Projects

| Course | Project | Description |
|--------|---------|-------------|
| DSA | **Treasure Hunting Game** | Graph-traversal console game with pathfinding algorithms |
| OOP | **Ant Farm Simulation** | Colony behavior simulation with battles and resource management |
| Programming Fundamentals | **Chess Engine** | Full CLI chess with legal move validation and game state management |

<br/>

---

## Tech Stack

### Languages
![Dart](https://img.shields.io/badge/Dart-0d1f3c?style=flat-square&logo=dart&logoColor=2F81F7)
![Kotlin](https://img.shields.io/badge/Kotlin-0d1f3c?style=flat-square&logo=kotlin&logoColor=2F81F7)
![Python](https://img.shields.io/badge/Python-0d1f3c?style=flat-square&logo=python&logoColor=2F81F7)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1f3c?style=flat-square&logo=javascript&logoColor=2F81F7)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1f3c?style=flat-square&logo=typescript&logoColor=2F81F7)
![C++](https://img.shields.io/badge/C++-0d1f3c?style=flat-square&logo=c%2B%2B&logoColor=2F81F7)

### Mobile
![Flutter](https://img.shields.io/badge/Flutter-0d1f3c?style=flat-square&logo=flutter&logoColor=2F81F7)
![Android](https://img.shields.io/badge/Android_(Kotlin)-0d1f3c?style=flat-square&logo=android&logoColor=2F81F7)
![iOS](https://img.shields.io/badge/iOS_(Xcode)-0d1f3c?style=flat-square&logo=apple&logoColor=ffffff)
![Riverpod](https://img.shields.io/badge/Riverpod-0d1f3c?style=flat-square&logoColor=2F81F7)
![Bloc](https://img.shields.io/badge/BLoC-0d1f3c?style=flat-square&logoColor=2F81F7)

### AI & LLM Systems
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-1a0a0a?style=flat-square&logoColor=cc2222)
![Gemini](https://img.shields.io/badge/Gemini-1a0a0a?style=flat-square&logo=google&logoColor=cc2222)
![OpenAI](https://img.shields.io/badge/OpenAI-1a0a0a?style=flat-square&logo=openai&logoColor=cc2222)
![LangGraph](https://img.shields.io/badge/LangGraph-1a0a0a?style=flat-square&logoColor=cc2222)
![RAG](https://img.shields.io/badge/RAG_Systems-1a0a0a?style=flat-square&logoColor=cc2222)
![n8n](https://img.shields.io/badge/n8n-1a0a0a?style=flat-square&logo=n8n&logoColor=cc2222)
![OpenRouter](https://img.shields.io/badge/OpenRouter-1a0a0a?style=flat-square&logoColor=cc2222)

### Backend & APIs
![Firebase](https://img.shields.io/badge/Firebase-0a1a0a?style=flat-square&logo=firebase&logoColor=16a34a)
![FastAPI](https://img.shields.io/badge/FastAPI-0a1a0a?style=flat-square&logo=fastapi&logoColor=16a34a)
![Node.js](https://img.shields.io/badge/Node.js-0a1a0a?style=flat-square&logo=node.js&logoColor=16a34a)
![REST](https://img.shields.io/badge/REST_APIs-0a1a0a?style=flat-square&logoColor=16a34a)
![WebSockets](https://img.shields.io/badge/WebSockets-0a1a0a?style=flat-square&logoColor=16a34a)
![JWT](https://img.shields.io/badge/JWT-0a1a0a?style=flat-square&logoColor=16a34a)
![OAuth2](https://img.shields.io/badge/OAuth_2.0-0a1a0a?style=flat-square&logoColor=16a34a)

### Databases
![Firestore](https://img.shields.io/badge/Firestore-0d1f3c?style=flat-square&logo=firebase&logoColor=2F81F7)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1f3c?style=flat-square&logo=postgresql&logoColor=2F81F7)
![Supabase](https://img.shields.io/badge/Supabase-0d1f3c?style=flat-square&logo=supabase&logoColor=2F81F7)
![MongoDB](https://img.shields.io/badge/MongoDB-0d1f3c?style=flat-square&logo=mongodb&logoColor=2F81F7)
![MySQL](https://img.shields.io/badge/MySQL-0d1f3c?style=flat-square&logo=mysql&logoColor=2F81F7)
![pgvector](https://img.shields.io/badge/pgvector-0d1f3c?style=flat-square&logoColor=2F81F7)

### Cloud & DevOps
![GCP](https://img.shields.io/badge/Google_Cloud-1a0a0a?style=flat-square&logo=googlecloud&logoColor=cc2222)
![Vercel](https://img.shields.io/badge/Vercel-1a0a0a?style=flat-square&logo=vercel&logoColor=ffffff)
![Docker](https://img.shields.io/badge/Docker-1a0a0a?style=flat-square&logo=docker&logoColor=cc2222)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1a0a0a?style=flat-square&logo=githubactions&logoColor=cc2222)
![CI/CD](https://img.shields.io/badge/CI%2FCD-1a0a0a?style=flat-square&logoColor=cc2222)

### Tools
![Git](https://img.shields.io/badge/Git-0a1a0a?style=flat-square&logo=git&logoColor=16a34a)
![Postman](https://img.shields.io/badge/Postman-0a1a0a?style=flat-square&logo=postman&logoColor=16a34a)
![Android Studio](https://img.shields.io/badge/Android_Studio-0a1a0a?style=flat-square&logo=androidstudio&logoColor=16a34a)
![VS Code](https://img.shields.io/badge/VS_Code-0a1a0a?style=flat-square&logo=visualstudiocode&logoColor=16a34a)
![Xcode](https://img.shields.io/badge/Xcode-0a1a0a?style=flat-square&logo=xcode&logoColor=16a34a)

<br/>

---

## Competitions

| Award | Event | Result |
|-------|-------|--------|
| 🥇 | CodeX 3.0 — National Programming Competition | **1st Place (National Champion)** |
| 🥈 | AureX — Inter-University Competition | **Runner-Up** |
| 🥉 | Visio Spark | **3rd Place** |

<br/>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Code-with-UsmanG&theme=github-dark-blue&background=0d1117&border=1a3a6b&stroke=1a3a6b&ring=1a3a6b&fire=cc2222&currStreakLabel=2F81F7&hide_border=false" />

</div>

<br/>

---

<div align="center">

<picture>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0a0a,100:0d1f3c&height=100&section=footer&animation=fadeIn" />
</picture>

<sub>Mobile engineer · AI systems builder · Open to collaboration</sub>

<br/><br/>

<a href="https://www.linkedin.com/in/usmanghanics/">
  <img src="https://img.shields.io/badge/LinkedIn-0a1628?style=for-the-badge&logo=linkedin&logoColor=2F81F7" />
</a>
&nbsp;
<a href="mailto:usmanghanii7729@gmail.com">
  <img src="https://img.shields.io/badge/Email-0a1628?style=for-the-badge&logo=gmail&logoColor=cc2222" />
</a>
&nbsp;
<a href="https://veloq.tech">
  <img src="https://img.shields.io/badge/Veloq.tech-0a1628?style=for-the-badge&logo=google-chrome&logoColor=16a34a" />
</a>

</div>
