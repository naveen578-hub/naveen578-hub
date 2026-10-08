<div align="center">

<img src="https://img.shields.io/badge/N%C2%B7K%C2%B7R-callsign-e0943f?style=flat-square&labelColor=1b1d17" alt="NKR" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=E0943F&center=true&vCenter=true&width=600&lines=Senior+Backend+Engineer;Distributed+Systems+%7C+PostgreSQL;Building+with+RAG+%2B+LLMs+in+production">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=B5651D&center=true&vCenter=true&width=600&lines=Senior+Backend+Engineer;Distributed+Systems+%7C+PostgreSQL;Building+with+RAG+%2B+LLMs+in+production" alt="Typing SVG" />
</picture>

</div>

### Hi, I'm Naveen 👋

Senior Backend Engineer with 7+ years owning core systems end-to-end — distributed pipelines, multi-region disaster recovery, and production AI-powered features shipped to 500K+ users across 15 countries. Deep in PostgreSQL and AWS infrastructure; increasingly focused on building and operating Retrieval-Augmented Generation (RAG) systems.

```
while (true) {
  design();   // multi-region failover, exactly-once pipelines
  ship();     // 500K+ users, 99.9% uptime
  measure();  // RAGAS, Hit@k/MRR, flakiness scoring
}
```

- 🔭 Currently building **RAGGuard** — a production-grade RAG quality/evaluation/reliability platform — and an **AI Quality Engineering Copilot** that turns requirements into traceable, evaluated test cases.
- 🧠 Production experience with the **Anthropic Claude API** and **OpenAI API** — not demos, shipped features serving 500K+ end users.
- 🏗️ Spent 7 years ramping fast across healthcare, IoT, banking, and fintech — taking ownership of a core system from day one, every time.
- 📫 Reach me: [LinkedIn](https://www.linkedin.com/in/reddyn016/) · naveenkumargouni00@gmail.com · [Portfolio](https://claude.ai/artifact/TGqysLysJ43hJvsCzYfgt6)

<br>

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ RAGGuard <sub>![Status](https://img.shields.io/badge/repo-private%20%2F%20in--progress-8fa389?style=flat-square)</sub>
**Production-grade RAG quality, evaluation & reliability platform**

FastAPI + React/TypeScript + PostgreSQL/Redis/ChromaDB, built in phases with every major decision documented as an ADR. Covers ingestion, hybrid retrieval + reranking, grounded generation with citations, automated RAGAS + custom evaluation, regression testing against a baseline, adversarial/security testing, and full observability (OpenTelemetry/Prometheus/Grafana) — CI-gated end to end.

`FastAPI` `React/TS` `PostgreSQL` `ChromaDB` `RAGAS` `Docker`

</td>
<td width="50%" valign="top">

### 🧪 [AI Quality Engineering Copilot](https://github.com/naveen578-hub/ai-quality-engineering-copilot)
**RAG-based test generation & QA analytics platform**

Generates traceable, schema-validated test cases from uploaded requirements, with a citation-verification guardrail that overwrites any model-claimed source with the real retrieved chunk. Ships requirements traceability, duplicate/conflict detection, requirement-change impact analysis, and test-health/flakiness analytics behind JWT auth/RBAC and PII masking. 94 backend tests, a 21-check Playwright e2e suite, zero-violation accessibility audit across 14 views.

`FastAPI` `RAG` `JWT/RBAC` `Playwright` `Docker`

</td>
</tr>
</table>

**[Coding Chat Interface](https://github.com/naveen578-hub/CODING-CHAT-INTERFACE)** — Full-stack AI chat assistant for programming questions, streaming token-by-token from Claude with the API key kept server-side only.

<br>

## 🧰 Tech I work with most

![Java](https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

<br>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=naveen578-hub&show_icons=true&theme=gruvbox&hide_border=true&bg_color=1b1d17&title_color=e0943f&icon_color=e0943f&text_color=ece7d6">
  <img src="https://github-readme-stats.vercel.app/api?username=naveen578-hub&show_icons=true&theme=default&hide_border=true&title_color=1F3A5F&icon_color=B5651D&text_color=444444" alt="Naveen's GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=naveen578-hub&layout=compact&hide_border=true&bg_color=1b1d17&title_color=e0943f&text_color=ece7d6">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=naveen578-hub&layout=compact&hide_border=true&title_color=1F3A5F&text_color=444444" alt="Top Langs" />
</picture>

</div>
### Hi, I'm Naveen

I build small, complete AI systems rather than large half-finished ones. Everything
below is tested against real engines — real filesystem events, real audio round
trips, real Docker containers — not mocked out for a demo.

#### 🗣️ [jarvis-cli](https://github.com/naveen578-hub/jarvis-cli)
A local AI agent built in four scoped steps, each one working before the next started:
- **Tool-calling agent** on Anthropic's Messages API, with local RAG (no API key
  needed to index — embeddings run on-device via `sentence-transformers`)
- **Real-time indexing** — a `watchdog`-based file watcher keeps the RAG index in
  sync as files change, no manual rebuilds
- **Voice interface** — a WebSocket server with fully local speech-to-text
  (`faster-whisper`) and text-to-speech (`pyttsx3`), no extra API keys
- **Sandboxed code execution** — the agent can run code inside a disposable Docker
  container with no network access, no host filesystem access, and a read-only
  root filesystem, verified by real integration tests, not just configured

#### 💬 [CODING-CHAT-INTERFACE](https://github.com/naveen578-hub/CODING-CHAT-INTERFACE)
A full-stack AI chat app — React/Vite frontend, Express backend streaming real
responses from Claude over Server-Sent Events. The API key never reaches the
browser.

---

I'd rather ship something small that's actually correct than something large that
only looks correct. If you look at the commit history on either repo, that's the
throughline.
