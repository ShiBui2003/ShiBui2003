<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,100:7aa2f7&height=180&section=header&text=Rahul%20Jha&fontSize=40&fontColor=f8f8f2&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%7C%20Backend%20%26%20Systems&descAlignY=58&descSize=16"/>
</div>

<p align="center">
  <a href="https://rahuljha07.netlify.app"><img src="https://img.shields.io/badge/Portfolio-1a1b26?style=for-the-badge&logo=vercel&logoColor=7aa2f7" /></a>
  <a href="https://www.linkedin.com/in/rahul-jha-a256a6212/"><img src="https://img.shields.io/badge/LinkedIn-1a1b26?style=for-the-badge&logo=linkedin&logoColor=0077B5" /></a>
  <a href="https://leetcode.com/u/ShiBui/"><img src="https://img.shields.io/badge/LeetCode-1a1b26?style=for-the-badge&logo=leetcode&logoColor=FFA116" /></a>
  <a href="mailto:irahul.jha.007@gmail.com"><img src="https://img.shields.io/badge/Email-1a1b26?style=for-the-badge&logo=gmail&logoColor=EA4335" /></a>
</p>

<p align="center">
BTech CS @ Bennett University · CGPA 8.1 · Class of 2027<br>
I work below the UI layer — spatial SQL, search ranking, concurrency bugs, distributed rate limiting.
</p>

<br>

## Projects that actually run in production

<table>
<tr>
<td width="50%" valign="top">

### [RediSearch](https://github.com/ShiBui2003/RediSearch)
Hybrid search engine (BM25 + TF-IDF + FAISS) over Reddit data

- **348 tests** passing, GitHub Actions → k3s on Azure, gated rollout
- Docker image **5.77GB → 357MB** (94% cut) — pinned torch to CPU-only
- Fixed a multi-replica rate-limiter split-brain with an **atomic Redis Lua token bucket**
- Rebuilt the crawler on a background job queue after Reddit killed public JSON API access

`Python` `FastAPI` `PostgreSQL` `Redis` `FAISS` `Docker` `k3s`

</td>
<td width="50%" valign="top">

### [STRIDE](https://stride-6rm.pages.dev)
Real-time geospatial territory-capture PWA

- **PostGIS** engine — `ST_Intersects` / `ST_Difference` in one transactional RPC, zero race conditions
- **Supabase Realtime** broadcasts territory changes, no polling
- **VAPID web push** pipeline for live theft/streak alerts
- Cron Edge Function decays undefended ground 10% every 48h

`Next.js 14` `TypeScript` `Supabase` `PostGIS` `Cloudflare`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Civik](https://kaizen-prod.vercel.app)
AI civic issue reporting — **live and in use on campus**

- Gemini 2.0 Flash extracts title/category/urgency in **under 2s**
- Two-stage AI gate: Gemini filter → BART-large-MNLI urgency re-rank
- **7-role RBAC** across 26 Supabase migrations
- Voice reporting in **10+ Indian languages** via Vapi

`Next.js 14` `Gemini 2.0` `BART-large-MNLI` `Supabase`

</td>
<td width="50%" valign="top">

### [VASUNDHARA](https://github.com/ShiBui2003/Vasundhara)
Smart waste management ecosystem

- CNN waste classifier at **97.98% accuracy**
- Threshold-triggered dispatch replacing fixed collection routes
- Two-sided system: Flutter citizen app + municipal IoT dashboard
- 🥇 **1st, Tech Arena 2025** (60+ teams) · AIU Anveshan National Selectee · OpenAI x NxtWave Finalist

`Python` `Django` `CNN` `Flutter` `MongoDB`

</td>
</tr>
</table>

<br>

## Stack

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

<br>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ShiBui2003&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ShiBui2003&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <sub>Open to SDE / backend internship & entry-level roles — <a href="https://www.linkedin.com/in/rahul-jha-a256a6212/">reach out on LinkedIn</a></sub>
</p>
