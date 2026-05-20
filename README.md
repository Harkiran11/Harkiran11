<div align="center">

<h1>
  Harkiran Panesar
</h1>

<p>
  Software engineering student at <strong>McMaster University</strong> building backend systems and ML infrastructure.<br/>
  Production deployments at <strong>TD Bank</strong> (10M+ users) and <strong>City of Toronto</strong> (500+ server fleet).
</p>

<p>
  <a href="https://linkedin.com/in/Harkiran11"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  &nbsp;
  <a href="mailto:harkiran.kps@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  &nbsp;
  <a href="https://ml-experiment-tracker-1.onrender.com"><img src="https://img.shields.io/badge/Live%20Project-3FB950?style=flat-square&logo=render&logoColor=white" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Open%20to%20Work-internships%20%26%20new%20grad-3FB950?style=flat-square" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:21262d&height=80&section=header&text=&animation=fadeIn" width="100%" />

</div>

---

## Experience

| | Role | Company | Period |
|---|---|---|---|
| 🏦 | **Software Engineer Intern** — Identity & Security (CIAM) | TD Bank | Jan–Apr 2026 |
| 🏙️ | **IT Trainee** — Infrastructure & Platform Services | City of Toronto | Sep–Dec 2025 |

**TD:** Built Java CIAM authentication services on Transmit Security serving 10M+ users. Led zero-downtime production deployment across US and Canada during RHEL 7→8 upgrade. Configured Dynatrace + Splunk observability across 4 environments.

**City of Toronto:** Built Node.js REST APIs and real-time dashboards for a 500+ server fleet. Integrated Splunk for centralized log aggregation. Automated server administration with Ansible, eliminating 20% of manual overhead.

---

## Projects

### [ML Experiment Tracker](https://github.com/Harkiran11/ml-experiment-tracker) &nbsp;[![Live](https://img.shields.io/badge/live-3FB950?style=flat-square&logo=render&logoColor=white)](https://ml-experiment-tracker-1.onrender.com)

Full-stack dashboard for tracking ML training runs. The core problem is a read-heavy polling pattern — the dashboard hits the API every 5 seconds per active run. Solved with Redis in front of Postgres (30s TTL, invalidate on write). Sub-100ms reads under load. The UI shows REDIS HIT vs CACHE MISS on every request so you can verify the caching behavior in real time.

`Python` `Flask` `React` `PostgreSQL` `Redis` `Docker` `GitHub Actions`

---

### [OmniDoc](https://github.com/Harkiran11/omnidoc) — Multimodal Document Intelligence

Llama 3.2 Vision and Qwen-VL running simultaneously on AMD MI300X (192GB HBM3). Built the inference pipeline and batching logic. 340 pages/min — 18x faster than CPU baseline. Chart-level and figure-level Q&A with full page citation.

`Python` `ROCm` `AMD MI300X` `Llama Vision` `Qwen-VL`

---

### [PathFinderAI](https://github.com/Harkiran11/pathfinderai) — Agentic RAG System

Multi-agent workflows with persistent state across turns, live data API integration, and semantic vector search. Built on LangGraph for state-managed reasoning chains.

`Python` `LangChain` `LangGraph` `Azure` `Vector DBs`

---

### CUDA Matrix Multiplication Engine

GPU kernel using shared memory tiling and memory coalescing. Profiling with NVIDIA Nsight Compute to resolve compute-bound vs memory-bound bottlenecks on large matrix workloads.

`CUDA` `C++` `NVIDIA Nsight Compute`

---

## Stack

```
Languages   Python · Java · C/C++ · CUDA · TypeScript · SQL · Bash
Backend     Flask · Node.js · Spring Boot · REST APIs
Frontend    React · Vite · Recharts
Infra       Docker · Kubernetes · Terraform · Ansible
CI/CD       GitHub Actions · Jenkins
Databases   PostgreSQL · MongoDB · Redis
ML          PyTorch · TensorFlow · LangChain · LangGraph · RAG · Vector DBs
Cloud       AWS · Azure
Observ.     Splunk · Dynatrace
```

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Harkiran11&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=8b949e&count_private=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harkiran11&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=6" />

</div>

---

<div align="center">
  <sub>McMaster University · Bachelor of Software Engineering · Expected April 2027 · Toronto, ON</sub>
</div>
