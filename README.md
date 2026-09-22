<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=Veer%20Bajpai&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20%26%20Systems%20%7C%20Full%20Stack&descAlignY=55&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Backend+%7C+Full-Stack+%7C+Forward+Deployed+Engineer;FastAPI+%7C+PostgreSQL+%7C+Redis+%7C+Docker;C%2B%2B+%7C+Python+%7C+High-Performance+Systems;Shipped+3+FastAPI+systems+%2B+199%2F199+tests+passing" alt="Typing SVG" />
</a>

<br/>

![B.E. Computer Science](https://img.shields.io/badge/B.E.-Computer%20Science-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white)
![Chandigarh University](https://img.shields.io/badge/Chandigarh%20University-2022--2026-4C1D95?style=for-the-badge&logo=graduation-cap&logoColor=white)
![Open to Work](https://img.shields.io/badge/Open%20to-Backend%20%7C%20Full--Stack%20%7C%20FDE%20roles-7C3AED?style=for-the-badge)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veer-bajpai/)
[![Email](https://img.shields.io/badge/Email-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bajpai.veer01@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/veer-bajpai)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=veer-bajpai&style=for-the-badge&color=8b5cf6&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/veer-bajpai?style=for-the-badge&color=7c3aed&labelColor=1e1b2e&logo=github)
![Stars](https://img.shields.io/github/stars/veer-bajpai?style=for-the-badge&color=a78bfa&labelColor=1e1b2e&logo=github)

</div>

<br/>

---

## 🟣 About Me

<img align="right" width="280" src="https://raw.githubusercontent.com/vaishakhk/vaishakhk/master/img/coding.gif"/>

I'm **Veer Bajpai**, a software engineer who builds **production-shaped backend systems end-to-end** — authentication, RBAC, payments, and Docker deployment — alongside **high-performance C++ systems work** at the network and memory level.

I've shipped 3 FastAPI systems, held seat-overselling at **zero across 600 concurrent bookings**, and verified **199/199 tests passing** on an AI code agent. On the systems side, I've built a multi-threaded Deep Packet Inspection engine classifying real-time network traffic with 90% accuracy and zero false negatives.

My engineering philosophy centers on **precision, scalability, and product impact** — optimizing not just for correctness, but for throughput, reliability, and real-world usability.

**Core Focus Areas:**

- 🧩 **Backend & API Engineering** — FastAPI, JWT auth & RBAC, multi-tenancy, payments, webhooks
- ⚙️ **Systems & Networking** — multi-threaded architectures, TCP/IP, socket programming, concurrent data structures
- 🌐 **Full-Stack Development** — RESTful API design, relational database architecture, scalable service integration
- 🧠 **Applied AI/ML** — AI agents & tool calling, Retrieval-Augmented Generation (RAG), vector search (HNSW/KD-Tree), local LLM inference with Ollama, BM25 search

<br clear="right"/>

### 🎯 Open To

```

🔹 Backend / Full-Stack Engineering Roles
🔹 Forward Deployed Engineer Opportunities
🔹 Systems / Software Engineering Roles
🔹 AI/ML Engineering Roles
🔹 Open Source Collaboration

```

---

## 🟣 Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,cpp,c,ts,mysql,postgresql" />

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js,react" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,python,cpp,postgresql,sqlite,redis,mongodb" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=git,github,docker,vscode,linux,cmake,postman" />

</div>

---

## 🟣 Applied AI/ML Specialty

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **AI Agents & Tool Calling** | ⭐⭐⭐⭐☆ | Built a sandboxed, human-in-the-loop AI code agent (search, read, edit, run tests, diff) gated by approval on every mutating action |
| **Retrieval-Augmented Generation (RAG)** | ⭐⭐⭐⭐☆ | Built custom RAG pipelines integrating local LLM inference via Ollama for context-aware retrieval and generation |
| **Vector & Lexical Search** | ⭐⭐⭐⭐☆ | Implemented HNSW indexing with sub-second query latency across 100,000+ documents, and BM25 lexical search for codebase retrieval |
| **LLM Integration** | ⭐⭐⭐⭐☆ | Engineered high-concurrency REST APIs serving semantic search and Gemini-assisted field mapping against LLM backends |
| **Embedding Systems** | ⭐⭐⭐⭐☆ | Architected scalable embedding storage, reducing memory overhead by 20% with high-precision retrieval |

</div>

---

## 🟣 Featured Projects

<details open>
<summary><b>🧩 EventForge — Multi-Tenant Event Management Platform</b></summary>
<br/>

A multi-tenant event hosting platform: organizations create events, sell tickets, take payments, and check guests in at the door, with full tenant isolation and role-based access.

| Attribute | Detail |
|---|---|
| **Stack** | FastAPI, PostgreSQL, Redis, SQLAlchemy 2, Docker |
| **RBAC** | 4 roles (`viewer < staff < admin < owner`) via a dependency-based gate; non-members get `404`, not `403` |
| **Auth** | Rotating refresh tokens with theft detection — reusing a rotated token revokes the whole token family |
| **Concurrency** | Seat reservation via conditional `UPDATE … WHERE sold + qty <= capacity` — **zero oversold seats across 600 concurrent bookings** |
| **Payments** | HMAC-signed webhooks with an idempotency ledger; replayed webhooks are harmless |
| **Testing** | 15 passing API tests covering tenancy, RBAC, refresh rotation, overselling, and webhooks |
| **Links** | [Live Demo](https://eventforge-o7yt.onrender.com/) · [Repository](https://github.com/veer-bajpai/Event.Forge-Multi-Tenant-Event-Management-Platform) |

</details>

<br/>

<details open>
<summary><b>🤖 RepoPilot — AI Code Agent</b></summary>
<br/>

An AI developer agent that reads a repository, plans a fix, edits files, and runs tests — with a human approval gate before every edit and every test run.

| Attribute | Detail |
|---|---|
| **Stack** | FastAPI, Python 3.10+, Google Gemini, BM25 Search, Docker |
| **Safety** | 5-tool sandboxed action set (search, read, edit, run tests, diff); the model never touches the filesystem, network, or shell directly |
| **Security layers** | Visitor isolation, abuse limits, path/secret hard-blocks, approval gates, scrubbed test execution |
| **Verified** | **199/199 tests passing**, and a rejected edit never touched the file in a real run |
| **Links** | [Live Demo](https://repo-pilot-ai-code-agent.onrender.com/) · [Repository](https://github.com/veer-bajpai/Repo.Pilot-AI-Code-Agent) |

</details>

<br/>

<details open>
<summary><b>🔌 IntegrateHub — AI-Powered Data Integration Platform</b></summary>
<br/>

A unified ingestion pipeline that turns client data arriving from disconnected sources into clean, mapped records.

| Attribute | Detail |
|---|---|
| **Stack** | FastAPI, SQLite, Google Gemini, Docker |
| **Ingestion** | CSV uploads, HMAC-verified webhooks, and REST pulls into one JWT-scoped, multi-tenant workspace |
| **AI mapping** | Gemini-assisted field mapping with a deterministic local fallback when no API key is set |
| **Security** | Constant-time HMAC signature verification, encrypted-at-rest connector secrets |
| **Verified** | **20 concurrent uploads at 269 req/s with 100% correct duplicate detection**, forged signatures rejected |
| **Links** | [Live Demo](https://integratehub.onrender.com/) · [Repository](https://github.com/veer-bajpai/Integrate.Hub-AI-Powered-Data-Integration-Platform) |

</details>

<br/>

<details open>
<summary><b>🔷 DPI Engine — Deep Packet Inspection System</b></summary>
<br/>

High-throughput, multi-threaded Deep Packet Inspection engine built in C++, designed for real-time network traffic classification at scale using a producer-consumer architecture.

| Attribute | Detail |
|---|---|
| **Stack** | C++, Multi-threading, TCP/IP, TLS/SNI Parsing, PCAP Analysis |
| **Scale** | Real-time traffic processing across diverse network protocols |
| **Performance** | Low-latency packet parsing with consistent-hashing-based flow management |
| **Security** | TLS/SNI extraction for precise, protocol-aware application identification |
| **Impact** | 90% traffic classification accuracy with zero false negatives across 75+ PCAP datasets |
| **Repository** | [View Project](https://github.com/veer-bajpai) |

Architected scalable flow management using thread-safe queues and consistent hashing to ensure high availability and reliable packet processing under sustained heavy load.

</details>

<br/>

<details open>
<summary><b>🧠 AI Personal Assistant — LLM-Powered Chatbot</b></summary>
<br/>

A high-concurrency, LLM-powered semantic search and retrieval system combining a custom RAG pipeline with local inference and optimized vector search.

| Attribute | Detail |
|---|---|
| **Stack** | C++, REST APIs, HNSW, Ollama |
| **Scale** | 100,000+ document knowledge base |
| **Performance** | Sub-second query latency via HNSW-optimized vector search |
| **Security** | Local LLM inference — no external data exposure |
| **Impact** | 20% reduction in memory overhead while preserving high-precision retrieval |
| **Repository** | [View Project](https://github.com/veer-bajpai) |

Engineered a high-concurrency RESTful API in C++ integrating directly with LLM-based backend services, enabling context-aware document retrieval and generation through a custom-built RAG pipeline powered by Ollama.

</details>

---

## 🟣 Experience

### Software Engineer Intern · **The Boring Education**
`Apr 2025 – Nov 2025` · Remote, India

Contributed as a backend-focused software engineering intern within an Agile team, delivering data pipelines, optimized database queries, and core backend improvements.

**Scope of Work:**
- Automated data ingestion pipelines using Python, processing 10,000+ records daily and reducing manual data entry time by 40%
- Optimized 20+ complex SQL queries for reporting dashboards, reducing execution time by 35%
- Refactored core C++ backend modules for multi-threading and memory management, achieving a 30% reduction in request latency under high concurrency
- Delivered 10+ backend features in an Agile environment, maintaining 95% on-time sprint delivery with rigorous peer code review

<br/>

<div align="center">

![Python](https://img.shields.io/badge/-Python-6D28D9?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-6D28D9?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-6D28D9?style=flat-square&logo=postgresql&logoColor=white)
![Agile](https://img.shields.io/badge/-Agile%2FScrum-6D28D9?style=flat-square&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/-Git-6D28D9?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🟣 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 **Best Final Year Project — 2026** | Chandigarh University · Multi-threaded C++ Deep Packet Inspection engine achieving 90% forwarding accuracy with zero false negatives across 75+ PCAP test cases |
| 🎖️ **Meta Back-End Developer Professional Certificate — 2025** | Coursera · Hands-on projects in Python, Django, APIs, databases, Git, and back-end web development principles |

</div>

---

## 🟣 Certifications

<div align="center">

![Oracle Cloud Infrastructure AI Foundations Associate](https://img.shields.io/badge/Oracle-AI%20Foundations%20Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![AI/Agent Applied Skills](https://img.shields.io/badge/Microsoft-AI%2FAgent%20Applied%20Skills-6D28D9?style=for-the-badge&logo=microsoft&logoColor=white)
![MongoDB Associate Developer](https://img.shields.io/badge/MongoDB-Associate%20Developer-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![GitHub Foundations](https://img.shields.io/badge/GitHub-Foundations-4C1D95?style=for-the-badge&logo=github&logoColor=white)
![Meta Back-End Developer](https://img.shields.io/badge/Meta-Back--End%20Developer%20Professional%20Certificate-0866FF?style=for-the-badge&logo=meta&logoColor=white)
![Coursera](https://img.shields.io/badge/Coursera-Verified%20Certificate-6D28D9?style=for-the-badge&logo=coursera&logoColor=white)

</div>

---

## 🟣 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-6D28D9?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/Veer_Bajpai/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-4C1D95?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/bajpaivhiwe)
[![HackerRank](https://img.shields.io/badge/HackerRank-5B21B6?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/bajpai_veer01)

500+ DSA problems solved across LeetCode, GeeksforGeeks & HackerRank.

</div>

---

## 🟣 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=veer-bajpai&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9c9c9&count_private=true" width="49%"/>
<img src="https://streak-stats.demolab.com?user=veer-bajpai&theme=radical&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=a78bfa" width="49%"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=veer-bajpai&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9c9c9" width="50%"/>

</div>

---

## 🟣 GitHub Trophies

<div align="center">

<img src="https://github-trophies.vercel.app/?username=veer-bajpai&theme=radical&no-frame=true&no-bg=true&margin-w=15&row=1" />

</div>

---

## 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=veer-bajpai&theme=react-dark&hide_border=true&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=ffffff" width="100%"/>

</div>

---

## 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/veer-bajpai/veer-bajpai/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

---

## 🟣 Current Focus

```yaml
Building:
  - Production-shaped backend systems (auth, RBAC, payments, multi-tenancy)
  - AI agents with sandboxed tool calling and human approval gates
  - High-performance network processing engines

Learning:
  - Advanced Distributed Systems Design
  - Large Language Model Fine-Tuning & Optimization
  - Cloud-Native Backend Architecture

Exploring:
  - Systems-Level AI Infrastructure
  - Scalable Microservice Architectures

Open To:
  - Backend / Full-Stack / Forward Deployed Engineer roles
  - Systems & AI/ML Engineering Opportunities
  - Open Source Collaboration
```

---

## 🟣 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-bajpai.veer01%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bajpai.veer01@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-veer--bajpai-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veer-bajpai/)
[![GitHub](https://img.shields.io/badge/GitHub-veer--bajpai-5B21B6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/veer-bajpai)

</div>

---

<div align="center">

### *"Engineering systems that scale, and intelligence that adapts."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer" width="100%"/>

</div>
