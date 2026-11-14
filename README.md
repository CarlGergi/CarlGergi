<h1 align="center">Carl Gergi</h1>

<p align="center">
  <a href="https://carlgergi.vercel.app/"><img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/carlgergi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:carlgergi@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
</p>

## 👋 About Me

I'm a Computer Science and Economics student at the University of Toronto, and I love **solving real-world problems**: taking an idea and turning it into something people actually use, something that makes their day a little easier. Whether it's a weekend hackathon or an agent I'm building on my own, that's the part I enjoy most.

These days I'm building mostly around **AI agents** and the space where **finance meets technology**.

- **Education:** Third year · AI focus · 3.8 CGPA · Dean's List every semester
- **2× Hackathon Winner:** Kanz AI Hackathon (out of 4,500+ submissions) and TechTO Hackathon

## 🚀 Projects

### [Ledger](https://github.com/CarlGergi/Ledger) <sub>Crash-safe gateway for AI agents</sub>

<img src="https://img.shields.io/badge/Rust-B7410E?style=flat-square&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />

- Sits between an agent and its tools and records every call before it runs, so a retry never sends the same email twice.
- Cuts duplicate actions from **423** per 1,000 calls to **0**, verified across **1,000,000** simulated crash scenarios.

### [Layover](https://github.com/CarlGergi/Layover) <sub>LLM inference engine built for agents</sub>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" /> <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" /> <img src="https://img.shields.io/badge/Triton-5A5A5A?style=flat-square" alt="Triton" />

- Decides at every tool call whether to keep an agent's KV cache on the GPU, move it to CPU memory, or drop it.
- Finishes agent jobs about **a third** faster than always dropping the cache, with custom CUDA and Triton kernels.

### [Taxon](https://github.com/CarlGergi/Taxon) <sub>Catalog intelligence for AI shopping agents</sub>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" /> <img src="https://img.shields.io/badge/Rust-B7410E?style=flat-square&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" /> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />

- Fine-tunes a small vision-language model that runs on a laptop to file products into Shopify's taxonomy, then tests whether shopping agents do better on its catalog.
- Agents solved **93.8%** of shopping tasks on its catalog, which cost **$0** in API calls to build, against **$13.27** with a frontier model.

### [Touchstone](https://github.com/CarlGergi/Touchstone) <sub>Queue-aware market-making backtester</sub>

<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />

- Records Coinbase's full order book 24/7 on AWS and simulates fills from where an order would actually sit in the queue.
- Shows that a naive backtest overstates filled volume by **3.9×**; the C++ engine replays **88M** events per second.

### [Argus AI](https://github.com/CarlGergi/ArgusAI) <sub>Competitive intelligence run by AI agents</sub>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API" />

- A team of agents reviews competitors' websites, pricing, job posts and filings overnight and delivers a one-page brief by morning.
- Covers **9** source types, with a critic agent that removes any claim the evidence does not support.

## 🏆 Hackathons

### [SIMTERN](https://github.com/CarlGergi/simtern) <sub>Winner, Kanz AI Hackathon</sub>

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API" />

- An internship simulator where students work a full day alongside AI coworkers and receive a skill report backed by evidence from their session.
- Built solo; won out of **4,500+** submissions across 15+ countries.

<a href="https://www.youtube.com/watch?v=bC3WfVR_4LI"><img src="https://img.shields.io/badge/Watch_the_demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch the demo" /></a>

### [Auri](https://loud-tweak-592173.framer.app) <sub>Winner, TechTO Hackathon</sub>

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white" alt="ElevenLabs" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" />

- A voice concierge for hotels that handles bookings and room service through natural conversation.
- Responds in under **500 ms**; pitched live to YC-backed founders.

<a href="https://loud-tweak-592173.framer.app"><img src="https://img.shields.io/badge/Visit_the_site-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Visit the site" /></a>

### [TD Threat Denied](https://github.com/tabetant/threatdenied) <sub>GenAI Genesis Hackathon</sub>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />

- A phishing verification tool for banks: forward a suspicious email and receive a fraud verdict.
- **6** agents analyze the sender, links and language in under **30 seconds**, escalating uncertain cases to an analyst.

<a href="https://www.youtube.com/watch?v=H3lH_ozz0hU"><img src="https://img.shields.io/badge/Watch_the_demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch the demo" /></a>

### [Finora](https://github.com/CarlGergi/anthropichackaton) <sub>Anthropic Hackathon</sub>

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" /> <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API" /> <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white" alt="ElevenLabs" />

- A voice-first budgeting assistant that scans receipts for an instant affordability check and weighs both sides of a purchase.
- Runs on Supabase Edge Functions, orchestrating Claude for reasoning and ElevenLabs for voice.

<a href="https://youtu.be/zAN5Ru6b67E"><img src="https://img.shields.io/badge/Watch_the_demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch the demo" /></a>

## 🛠️ Tech Stack

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Rust-B7410E?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
    </td>
  </tr>
  <tr>
    <td><b>AI & Agents</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
      <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
      <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="MCP" />
      <img src="https://img.shields.io/badge/Multi--Agent_Systems-7C3AED?style=for-the-badge&logo=probot&logoColor=white" alt="Multi-Agent Systems" />
    </td>
  </tr>
  <tr>
    <td><b>ML & GPU</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
      <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
    </td>
  </tr>
  <tr>
    <td><b>Web & Mobile</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
    </td>
  </tr>
  <tr>
    <td><b>Backend & Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
    </td>
  </tr>
  <tr>
    <td><b>Cloud & DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
    </td>
  </tr>
</table>

<br/>

<p align="center"><b><i>Always building. Always learning.</i></b></p>
