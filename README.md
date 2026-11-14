<h1 align="center">Carl Gergi</h1>

<p align="center">
  Computer Science & Economics @ University of Toronto<br/>
  AI agents · Finance and technology · Software engineering
</p>

<p align="center">
  <a href="https://carlgergi.vercel.app/"><img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/carlgergi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:carlgergi@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
</p>

---

## 👋 About Me

I study Computer Science and Economics at the University of Toronto, and I'm most interested in the problems where finance and technology meet. Lately, most of what I build is about AI agents: keeping them from repeating actions, serving them faster on a GPU, and putting them to work on real tasks.

- **Education:** 3rd year, CS & Economics (AI focus) · 3.8 CGPA · Dean's List every semester
- **Experience:** Software Engineering Intern at Deloitte, Dubai (2026) and Turnkey Systems, Beirut (2025)
- **Awards:** Winner of the Kanz AI Hackathon (4,500+ submissions) and the TechTO Hackathon
- **Languages:** English, French, Arabic

---

## 🚀 Projects

### [Ledger](https://github.com/CarlGergi/Ledger) <sub>crash-safe gateway for AI agents</sub>

<img src="https://img.shields.io/badge/Rust-B7410E?style=flat-square&logo=rust&logoColor=white" /> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />

- Sits between an agent and its tools and records every call before it runs, so a retry can never send the same email twice.
- Cut duplicate actions from **423** per 1,000 calls to **0**, verified across **1,000,000** simulated crash scenarios.

### [Layover](https://github.com/CarlGergi/Layover) <sub>LLM inference engine for agents</sub>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" /> <img src="https://img.shields.io/badge/Triton-5A5A5A?style=flat-square" />

- While an agent waits on a tool, its KV cache sits idle on the GPU. Layover decides each time whether to keep it, move it to CPU memory, or drop it.
- Completes agent jobs about **a third** faster than always dropping the cache, using custom CUDA and Triton kernels.

### [Touchstone](https://github.com/CarlGergi/Touchstone) <sub>queue-aware market-making backtester</sub>

<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />

- Records Coinbase's full order book 24/7 on AWS and simulates fills from where an order would actually sit in the queue.
- Shows that a naive backtest overstates filled volume by **3.9×**; the C++ engine replays **88M** events per second.

### [Argus AI](https://github.com/CarlGergi/ArgusAI) <sub>competitive intelligence agents</sub>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" />

- A team of agents reviews competitors' websites, pricing, job posts and filings overnight and delivers a one-page brief by morning.
- Covers **9** source types, with a critic agent that removes any claim the evidence does not support.

---

## 🏆 Hackathons

### [SIMTERN](https://github.com/CarlGergi/simtern) <sub>Winner, Kanz AI Hackathon</sub>

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" />

- An internship simulator where students work a full day alongside AI coworkers and receive a skill report backed by evidence from their session.
- Built solo; selected from **4,500+** submissions across 15+ countries. [Demo](https://www.youtube.com/watch?v=bC3WfVR_4LI)

### [Auri](https://loud-tweak-592173.framer.app) <sub>Winner, TechTO Hackathon</sub>

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />

- A voice concierge for hotels that handles bookings and room service through natural conversation.
- Responds in under **500 ms**; pitched live to YC-backed founders.

### [TD Threat Denied](https://www.youtube.com/watch?v=H3lH_ozz0hU) <sub>GenAI Genesis Hackathon</sub>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />

- A phishing verification tool for banks: forward a suspicious email and receive a fraud verdict.
- **6** agents analyze the sender, links and language in under **30 seconds**, escalating uncertain cases to an analyst.

### [Finora](https://github.com/CarlGergi/anthropichackaton) <sub>Anthropic Hackathon</sub>

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white" />

- A voice-first budgeting assistant for students.
- Scans receipts for an instant affordability check and weighs both sides of a purchase before you buy. [Demo](https://youtu.be/zAN5Ru6b67E)

---

## 💼 Experience

| Role | Company | When |
| :-- | :-- | :-- |
| **Software Engineering Intern** | **Deloitte** · Dubai | May – Aug 2026 |
| **Full-Stack Developer** | **[DurhamOne Canada](https://durham1.ca)** · Toronto | Sept 2025 – May 2026 |
| **Student Consultant** | **Viridian Management Consulting** · Toronto | Sept 2025 – May 2026 |
| **Software Engineering Intern** | **Turnkey Systems** · Beirut | May – July 2025 |
| **Co-Founder** | **The Young Readers Society** · Beirut | June 2023 – Aug 2024 |

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Rust-B7410E?style=for-the-badge&logo=rust&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>AI & Agents</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
      <img src="https://img.shields.io/badge/Multi--Agent_Systems-7C3AED?style=for-the-badge&logo=probot&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>ML & GPU</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
      <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
    </td>
  </tr>
  <tr>
    <td><b>Web & Mobile</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Backend & Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Cloud & DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
    </td>
  </tr>
</table>
