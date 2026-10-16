<div align="center">

# Hi, I'm Sameer Nagar

### I build AI systems that show their work.

**Full-stack engineer · GenAI lead at [Saayam For All](https://github.com/saayam-for-all) · Agentic Dev Tools Hackathon winner (SF, 2026)**
*M.S. Computer Science · 5x Salesforce Certified · San Jose, CA*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-aavonsameer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aavonsameer)
[![Portfolio](https://img.shields.io/badge/Portfolio-live-111827?style=for-the-badge&logo=streamlit&logoColor=FF4B4B)](https://portfolioai-aoaxbktwyqkfm2ne6vxqes.streamlit.app/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--2302--9092-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-2302-9092)
[![REGEN live](https://img.shields.io/badge/REGEN-live%20demo-D4A72C?style=for-the-badge&logo=render&logoColor=white)](https://regen-engine.onrender.com)

</div>

---

### The short version

I like the hard middle of software: the part where an AI agent has to touch real systems, real money or real people and
**still be honest about what it did**. Most of what I've shipped in 2026 is some version of that idea: agents that keep
receipts, memory that can be revoked, verifiers that catch an agent lying, and backends that fail honestly instead of
returning a confident 502.

**Past year on GitHub:** 500+ contributions · 400+ commits · 43 pull requests · 10 hackathon and team builds · 12 PRs to a
501(c)(3)'s production AI service.

---

### Now building: [REGEN](https://github.com/sameernagar-hub/regen-engine), an autonomous job engine

An open-source engine that runs entirely in Docker: it discovers roles at the source, tailors a truthful one-page resume
per job from a Fact Bank of provable lines, applies through a fleet of container workers, and keeps a saved confirmation
page as proof for every submit. Zero model cost: you drive it from your own AI client over **MCP**.

- **5,000+ company boards** polled directly across Greenhouse, Ashby, Lever, Workable, Workday, SmartRecruiters and iCIMS
- **165 applications** submitted with proof, best day 49; every answer, fact and skip reason in an append-only ledger
- **Fit gate** that reads the full JD before spending effort, tuned against every real rejection it received
- Postgres ledger, FastAPI + Next.js control room, autoscaling supervisor with kill switch, privacy gate in CI
- 176 commits and 13 merged PRs (v0.4 → v0.15) since October 2026

`Python` `FastAPI` `Next.js` `TypeScript` `Playwright` `PostgreSQL` `Docker` `MCP`

---

### Open source: [Saayam For All](https://github.com/saayam-for-all) (501(c)(3), "Uber for help")

Full-stack and GenAI lead on the nonprofit platform that connects people who need food, shelter or healthcare with
volunteers and organizations. **12 pull requests to the production AI service** ([saayam-for-all/ai](https://github.com/saayam-for-all/ai)), including:

- **Emergency Contacts** resolve within the requested country, never return an empty number, and no longer 502 (#146)
- **More Information** answers without the database and fails honestly when it can't (#169)
- **Organizations tab** survives a provider outage, with the contract `orgAggregatorList` depends on pinned (#170)
- **Ask the model the question the person actually asked** (#183)
- Made the **test suite runnable, classified and documented**, and fixed two router defects it found (#171)
- **Onboarding guardrails and an architecture map** for new contributors (#163)

Also contributing to the [data](https://github.com/saayam-for-all/data) engineering team.

---

### Hackathons and team builds (2026)

| Project | What it does | Event |
| :--- | :--- | :--- |
| 🏆 **[Replace Your Human with AI Skill](https://github.com/kklike32/Replace-Your-Human-with-AI-Skill)** | Native macOS app that records real desktop work plus voice and turns it into a reusable, shareable AI skill | **1st place**, Agentic Dev Tools Hackathon, SF |
| **[Immune](https://github.com/sameernagar-hub/immune)** | An immune system for agent memory: finds a planted lie, quarantines it and reverses every decision made because of it (`$graphLookup` provenance cascade, trust-filtered Vector Search, Change Streams) | MongoDB .local Build Fest, Persistent Context Sprint |
| **[Pinocchio](https://github.com/akhiping/yc-greptile)** | Catches coding agents lying about their work: checks "tests pass" claims against the diff and receipts, and blocks the turn | YC × Greptile |
| **[CLARITY](https://github.com/sameernagar-hub/clarity)** · [live](https://fdaapproval-pzpr.onrender.com/?trial=NCT05951205) | FDA-grade review room: point it at an NCT ID, get a cited nine-domain dossier and an approval-risk call that shows the weakest argument first. 53 tests | Clinical AI build |
| **[Probception](https://github.com/sameernagar-hub/probception)** | AI scientist that states what it believes as probabilities and runs the experiment most likely to prove itself wrong (in vivo CRISPR derisking) | re:AGENT, Track A |
| **[Oto.ai](https://github.com/KrishnaJ-bit/Memory_Meets_Motion)** | Remembers why you did what you did and finishes the task while you're away (event stream → live knowledge graph → governed agent) | Memory Meets Motion, Frontier Tower SF |
| **[Amortize](https://github.com/vraj00222/Amort)** | Local proxy that makes agents cheaper with zero code changes: **−28% tokens** cold, **−97%** on replay with output parity, measured | Hackathon team build |
| **[Crew](https://github.com/vraj00222/crew)** | Voice-native swarm of five agents that clears your inbox and calendar, and phones you when only you can decide | Hackathon team build |
| **[Zephyr](https://github.com/Mr-Shine09/Zephyr)** | Ambient companion for Mistral Vibe CLI: watch and answer your coding agent from your phone | Mistral Vibe Hackathon, Track 02 |
| **[Runway.ai](https://github.com/sameernagar-hub/svai-runway-token-ai)** | Budget-aware multi-agent planner: turns a mission into a dependency graph and finishes before the tokens do | SVAI |

---

### More projects

- **[promptPilot](https://github.com/sameernagar-hub/promptPilot)**: prompt-intelligence engine that analyzes multi-turn conversation logs to decode how you prompt (Next.js, FastAPI, Neon, `pgvector`)
- **[Anomaly Detection Workbench](https://github.com/sameernagar-hub/anomaly-detection-workbench)**: system-log anomaly detection with a sequence baseline, an argument-aware model and drift-aware thresholds
- **[Titan Smart Scheduler](https://github.com/sameernagar-hub/titan-smart-scheduler)**: student-aware staff scheduling with fair workload, conflict prevention and risk-aware backup coverage
- **[Open-Source Tax Tooling](https://github.com/sameernagar-hub/Open-Source-Tax-Tooling)**: research on the open-source US tax and bookkeeping landscape and its integration surfaces
- **[portfolio.ai](https://github.com/sameernagar-hub/portfolio.ai)**: portfolio with a Gemini chat assistant, local fallback and serverless proxies
- **[PenPulse](https://github.com/sameernagar-hub/PenPulseAWS)** and **[AWS Intelligent Interaction Services](https://github.com/sameernagar-hub/AWS-Intelligent-Interaction-Services)**: three-tier AWS blogging platform and AWS AI services work

---

### Stack

| Domain | Tools |
| :--- | :--- |
| **Languages** | Python, TypeScript/JavaScript, Java 17, Go, C++, SQL |
| **AI and agents** | MCP servers, agent memory and provenance, grounded RAG, LLM evaluation, Claude, Gemini, Vertex AI, LangChain |
| **Backend and data** | FastAPI, Spring Boot 3, Node.js, PostgreSQL (`pgvector`), MongoDB Atlas (Vector Search, Change Streams), Kafka / AWS MSK |
| **Frontend** | Next.js, React, React Native, Canvas and motion UI |
| **Cloud and ops** | AWS (EKS, Lambda, API Gateway, Cognito, Aurora), Docker, Render, GitHub Actions, Playwright |
| **Certifications** | 5x Salesforce: Admin, Advanced Admin, Platform Developer I and II, Agentforce Specialist |

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sameernagar-hub&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sameernagar-hub&layout=compact&hide_border=true&theme=tokyonight" height="165" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sameernagar-hub&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Contribution graph" />

**Open to new-grad and early-career SWE, AI engineering and full-stack roles.** Let's talk.

</div>
