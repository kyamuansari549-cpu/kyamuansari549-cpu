<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4c1d95,6d28d9,7c3aed,8b5cf6,a855f7&height=280&section=header&text=Kiyamuddin%20Ansari&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Kiyamuddin Ansari"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=A855F7&center=true&vCenter=true&width=640&lines=Final-Year+B.Tech+%7C+Full-Stack+Developer;Python+%E2%80%A2+React+%E2%80%A2+FastAPI+%E2%80%A2+AI%2FML;Building+Agentic+AI+%26+Real-World+Products;Open+to+Internships+%26+Collaborations" alt="typing animation"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Lucknow%2C_India-8b5cf6?style=flat-square" alt="location"/>
  <a href="https://github.com/kyamuansari549-cpu/my-portfolio"><img src="https://img.shields.io/badge/Portfolio-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="portfolio"/></a>
  <a href="https://www.linkedin.com/in/kiyamuddin-ansari-ba6a60381/"><img src="https://img.shields.io/badge/LinkedIn-8b5cf6?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="mailto:kyamuansari549@gmail.com"><img src="https://img.shields.io/badge/Gmail-8b5cf6?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail"/></a>
  <a href="https://github.com/kyamuansari549-cpu"><img src="https://img.shields.io/badge/GitHub-8b5cf6?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kyamuansari549-cpu&color=8b5cf6&style=flat-square" alt="profile views"/>
  <img src="https://img.shields.io/github/followers/kyamuansari549-cpu?label=Followers&style=flat-square&color=8b5cf6&logo=github" alt="followers"/>
</p>

---

## About Me

Final-year **B.Tech (AI & ML)** student and **full-stack developer** who builds real, working software — not demos. From multi-agent AI research systems to an on-device AR navigation aid for the visually impaired, my projects go from idea to production: deployed, tested, and field-verified.

I work across the stack — **Python, React, FastAPI** — with deep hands-on experience in **LLMs, RAG, and agentic AI**, including fine-tuning and shipping my own 7B vision-language model on consumer hardware.

**Open to:** Full-stack & AI internships · collaborations · open source

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,js,ts,kotlin,html,css&theme=dark" alt="languages"/><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite&theme=dark" alt="frontend"/><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,postgres,sqlite,redis&theme=dark" alt="backend"/><br/>
  <img src="https://skillicons.dev/icons?i=docker,vercel,supabase,git,githubactions,linux&theme=dark" alt="devops"/>
</p>

| Layer | Technologies |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, Kotlin, SQL, HTML/CSS |
| **Frontend** | React, Next.js 16, Tailwind CSS, Vite |
| **Backend** | FastAPI, Node.js, Drizzle ORM, SQLAlchemy |
| **Databases** | PostgreSQL (Neon), SQLite, Redis (Upstash) |
| **Cloud & DevOps** | Docker, Vercel, Render, Supabase, GitHub Actions, Linux (WSL2) |

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| LLM Fine-tuning (QLoRA) | Advanced | Fine-tuned Qwen2.5-7B & Qwen2.5-VL-7B on an RTX 3050 (6GB VRAM); 2,297-example custom dataset; full pipeline — training, merge, abliteration, GGUF export, Ollama deployment |
| RAG Systems | Advanced | DocQA — document Q&A with cited answers; embeddings + vector search + grounded generation |
| Multi-Agent Systems | Advanced | Agentic Research Assistant — planner → researcher → writer → critic pipeline with real paper search and SSE streaming |
| Vision-Language Models | Intermediate | Qwen2.5-VL fine-tune with mmproj export for local vision inference |
| On-device ML | Intermediate | MediaPipe EfficientDet-Lite0 + TTS pipelines running fully offline (DrishtiNav) |

---

## Featured Projects

<details>
<summary><b>Agentic Research Assistant — flagship project</b></summary>
<br/>

Multi-agent research pipeline that produces cited, plagiarism-checked research reports from a single query.

| | |
|---|---|
| **Stack** | FastAPI, React, Groq, Gemini, Semantic Scholar + arXiv APIs, SSE |
| **Scale** | Multi-agent pipeline (planner, researcher, writer, critic) |
| **Performance** | Streaming responses, LLM failover with backoff |
| **Security** | 12-phase security audit passed — 8/8 security tests green |
| **Impact** | Real paper research with verified citations, not plausible fakes |
| **Repository** | [Agentic-Research-Assistant](https://github.com/kyamuansari549-cpu/Agentic-Research-Assistant) |

</details>

<details>
<summary><b>CyberForge v2 — my own 7B vision-language AI model</b></summary>
<br/>

A custom AI model built end-to-end on a laptop: cybersecurity expertise, general conversation, image understanding, and reduced refusals — all running locally and offline.

| | |
|---|---|
| **Stack** | Qwen2.5-VL-7B, QLoRA, Heretic abliteration, llama.cpp, Ollama |
| **Scale** | 7B parameters, 2,297-example training dataset |
| **Performance** | Q4_K_M quantized (~4.5GB), runs on RTX 3050 6GB |
| **Security** | Abliterated: refusals cut from 44/100 to 2/100 with quality preserved |
| **Impact** | Vision + chat + cyber expertise in one fully local model |
| **Repository** | Self-hosted via Ollama (`cyberforge-v2`) |

</details>

<details>
<summary><b>DrishtiNav — AR navigation aid for the visually impaired</b></summary>
<br/>

Android app combining ARCore depth sensing with on-device object detection to guide visually impaired users safely.

| | |
|---|---|
| **Stack** | Kotlin, ARCore, MediaPipe, TTS, OSRM |
| **Scale** | On-device EfficientDet-Lite0 (14MB), zero network dependency |
| **Performance** | Real-time obstacle alerts with priority interrupts |
| **Security** | Fully offline — no user data ever leaves the device |
| **Impact** | Field-verified on real hardware; public v0.6.1 release |
| **Repository** | [DrishtiNav](https://github.com/kyamuansari549-cpu/DrishtiNav) |

</details>

<details>
<summary><b>DocQA — RAG document Q&A</b></summary>
<br/>

Upload documents, ask questions, get answers with citations — every claim traceable to the source.

| | |
|---|---|
| **Stack** | FastAPI, React, Gemini embeddings, Groq, SQLite + NumPy vector search |
| **Scale** | Custom ~70-line vector store (no native deps) |
| **Performance** | L2-normalized 768-dim search, cited responses |
| **Security** | Same-language answers, clean markdown output |
| **Impact** | Live in production: [app](https://docqa-rag-two.vercel.app) · [api](https://docqa-rag-mcfg.onrender.com) |
| **Repository** | [docqa-rag](https://github.com/kyamuansari549-cpu/docqa-rag) |

</details>

<details>
<summary><b>SeatBook — full-stack event booking platform</b></summary>
<br/>

Production event booking with atomic seat holds, real payments, and organizer dashboards.

| | |
|---|---|
| **Stack** | Next.js 16, PostgreSQL (Neon), Auth.js, Razorpay, Upstash Redis |
| **Scale** | Atomic 10-min seat holds, waitlists, refunds, cron jobs |
| **Performance** | 80 tests green, clean production build |
| **Security** | Race-condition-safe booking via row-level locking |
| **Impact** | Live with full E2E verified: login → hold → payment → confirmed booking |
| **Repository** | [booking-platform](https://github.com/kyamuansari549-cpu/booking-platform) · [live](https://booking-platform-phi-three.vercel.app) |

</details>

<details>
<summary><b>AI Code Review Bot — GenAI code review & bug fixing</b></summary>
<br/>

Paste code or screenshots, get reviews, bug fixes, and follow-up answers from an AI reviewer.

| | |
|---|---|
| **Stack** | FastAPI, React, LLM APIs |
| **Scale** | Text + image input, full fixed-code output |
| **Performance** | End-to-end review flow working locally |
| **Security** | Input-grounded responses — no hallucinated reviews |
| **Impact** | Interview-portfolio project with real PR-review flow |
| **Repository** | [ai-code-review-bot](https://github.com/kyamuansari549-cpu/ai-code-review-bot) |

</details>

---

## Achievements

<p align="center">

| Recognition | Details |
|---|---|
| Custom AI Model | Fine-tuned and shipped a 7B vision-language model end-to-end on a consumer RTX 3050 — dataset, training, abliteration, GGUF export, Ollama deployment |
| Shipped Mobile App | DrishtiNav — on-device AR navigation aid, field-verified on real hardware, public v0.6.1 release |
| Production Payments | SeatBook live with full booking + Razorpay payment flow verified end-to-end |
| Security Audit | Agentic Research Assistant cleared a 12-phase security audit — 8/8 tests passing |
| Google Cloud Career Launchpad | Selected for the Google Cloud Career Launchpad program (2026) |

</p>

---

## Coding Profiles

<p align="center">
  <a href="https://leetcode.com/u/5GTnrYHW9f/"><img src="https://img.shields.io/badge/LeetCode-8b5cf6?style=for-the-badge&logo=leetcode&logoColor=white" alt="leetcode"/></a>
</p>

---

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kyamuansari549-cpu&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117" alt="github stats" height="165"/>
  <img src="https://streak-stats.demolab.com?user=kyamuansari549-cpu&theme=midnight-purple&hide_border=true&background=0d1117" alt="streak stats" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kyamuansari549-cpu&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117" alt="top languages"/>
</p>

---

## GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kyamuansari549-cpu&theme=dracula&no-frame=true&no-bg=true&margin-w=4" alt="trophies"/>
</p>

---

## Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kyamuansari549-cpu&bg_color=0d1117&color=a855f7&line=8b5cf6&point=c084fc&area=true&hide_border=true" alt="activity graph"/>
</p>

---

## Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kyamuansari549-cpu/kyamuansari549-cpu/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kyamuansari549-cpu/kyamuansari549-cpu/output/github-snake.svg"/>
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/kyamuansari549-cpu/kyamuansari549-cpu/output/github-snake.svg"/>
  </picture>
</p>

---

## Current Focus

```yaml
learning:
  - Advanced RAG architectures
  - System design for AI products
building:
  - CyberForge — personal local AI models
  - Internship-ready portfolio projects
exploring:
  - Vision-language models
  - On-device ML
open_to:
  - Full-stack internships
  - AI/ML collaborations
```

---

## Connect

<p align="center">
  <a href="mailto:kyamuansari549@gmail.com"><img src="https://img.shields.io/badge/Gmail-8b5cf6?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail"/></a>
  <a href="https://www.linkedin.com/in/kiyamuddin-ansari-ba6a60381/"><img src="https://img.shields.io/badge/LinkedIn-8b5cf6?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="https://github.com/kyamuansari549-cpu"><img src="https://img.shields.io/badge/GitHub-8b5cf6?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>
  <a href="https://github.com/kyamuansari549-cpu/my-portfolio"><img src="https://img.shields.io/badge/Portfolio-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="portfolio"/></a>
</p>

---

<p align="center">
  <i>Ship real software. No demos, no fakes.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4c1d95,6d28d9,7c3aed,8b5cf6,a855f7&height=120&section=footer" alt="footer"/>
</p>
