<div align="center">

<img src="https://raw.githubusercontent.com/ShiBui2003/ShiBui2003/main/assets/header.png" width="100%" alt="Rahul Jha"/>

# Rahul Jha
### Full-Stack | Backend & Systems

**BTech CS @ Bennett University** · CGPA 8.1 · Class of 2027

[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://rahuljha07.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-jha-a256a6212/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/ShiBui/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:irahul.jha.007@gmail.com)

</div>

---

### What I actually build

I work across the stack, but the interesting part of my work is usually below the UI: spatial SQL, search ranking, concurrency bugs, distributed rate limiting. Currently deep in placement prep and shipping systems-heavy side projects.

---

### 🔨 Projects

**[RediSearch](https://github.com/ShiBui2003/RediSearch)** — Hybrid search engine (BM25 + TF-IDF + FAISS) over Reddit data
- Deployed to a self-managed **k3s cluster on Azure**, GitHub Actions gated rollout, **348 passing tests**
- Cut Docker image **94%** (5.77GB → 357MB) by pinning torch to CPU-only
- Fixed a multi-replica rate-limiter split-brain with an atomic **Redis Lua token bucket**
- Rebuilt the crawler around a background job queue after Reddit killed public JSON API access

**[STRIDE](https://stride-6rm.pages.dev)** — Real-time geospatial territory-capture PWA
- **PostGIS** engine using `ST_Intersects` / `ST_Difference` in a single-transaction RPC to kill race conditions
- Supabase Realtime broadcasts territory changes with zero polling
- VAPID web push pipeline for live theft/streak alerts

**[Civik](https://kaizen-prod.vercel.app)** — AI civic issue reporting, live and in use on campus
- Gemini 2.0 Flash auto-extracts title/category/urgency from photo, text, or voice in **under 2s**
- Two-stage AI gate (Gemini filter → BART-large-MNLI urgency re-rank) surfaces critical issues first
- 7-role RBAC across 26 Supabase migrations, voice support in **10+ Indian languages**

**[VASUNDHARA](https://github.com/ShiBui2003/Vasundhara)** — Smart waste management ecosystem
- CNN waste classifier at **97.98% accuracy**
- 🏆 1st place, Tech Arena 2025 (60+ teams) · AIU Anveshan 2025 National Selectee · OpenAI x NxtWave National Finalist

---

### 🛠️ Stack

`C++` `TypeScript` `Python` `SQL` — `Next.js` `FastAPI` `React` — `PostgreSQL` `PostGIS` `Redis` `Supabase` — `Docker` `Kubernetes` `Git`

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ShiBui2003&show_icons=true&theme=dracula&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ShiBui2003&theme=dracula&hide_border=true" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShiBui2003&layout=compact&theme=dracula&hide_border=true" height="165"/>

</div>

---

<div align="center">
<sub>Open to SDE / backend internship and entry-level roles. Reach out on <a href="https://www.linkedin.com/in/rahul-jha-a256a6212/">LinkedIn</a>.</sub>
</div>
