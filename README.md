<div align="center">

# Hi, I'm chipfighter 👋

**Making AI agents remember more, drift less, and dig deeper.**

I build plugins, skills and harnesses for coding agents like **Claude Code** and **Codex**,<br>and AIGC workflows that turn image and video generation into something you can direct.

<sub>专注 AI Agent 工具链：让 Agent 记得更多、跑偏更少、挖得更深。</sub>

</div>

---

### ⭐ Featured

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/chipfighter/context-attachment-manager"><img src="https://raw.githubusercontent.com/chipfighter/context-attachment-manager/HEAD/plugin/assets/logo.png" width="40" height="40" alt=""></a><br>
      <a href="https://github.com/chipfighter/context-attachment-manager"><b>Context Attachment Manager</b></a><br>
      <sub>Codex · Claude Code plugin</sub>
      <br><br>
      Keeps long, image-heavy Codex and Claude Code chats fast. Earlier images fold into ID placeholders the model fetches back on demand, even after compaction.
      <br><br>
      <sub><b>42.4 MB → 0.12 MB</b> in one Codex request · <b>20/20</b> image questions right after compaction</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/chipfighter/lodestar"><img src="https://raw.githubusercontent.com/chipfighter/lodestar/HEAD/docs/logo.svg" width="40" height="40" alt=""></a><br>
      <a href="https://github.com/chipfighter/lodestar"><b>Lodestar</b></a><br>
      <sub>Claude Code plugin · Windows client</sub>
      <br><br>
      Choose which skills each Claude Code session loads, and only those. Pick a skill set at the first message; subagents get their own.
      <br><br>
      <sub>Also works with Codex · 中文 / English</sub>
    </td>
  </tr>
</table>

### 🚧 Building now

**[liveops](https://github.com/chipfighter/liveops)** — a local-first, open-source assistant for live-commerce and short-video operations, built around an agent. It records live streams, transcribes them, splits them into per-product segments, reads on-screen prices and offers, and answers operations questions with tools. No account, no backend: your own model and key, on 127.0.0.1.
<br><sub>Early stage · Douyin live pipeline works end to end · TypeScript server and agent · Python workers (Whisper, RapidOCR) · pnpm + uv monorepo</sub>

### 🧰 Agent tooling

- **[coding-discipline](https://github.com/chipfighter/coding-discipline)** — guardrails for AI coding agents: traces bugs with unclear causes and keeps confirmed project decisions across sessions
- **[Radar-Research](https://github.com/chipfighter/Radar-Research)** — a local research agent that reads *every* source in a list you curate (RSS, arXiv, GitHub, HN, Reddit) and cites each line
- **[rag_diff](https://github.com/chipfighter/rag_diff)** — regression testing and debugging CLI for RAG pipelines: context diffing, cached LLM judges, root-cause triage

### 🎬 AIGC skills

**[aigc-skills](https://github.com/chipfighter/aigc-skills)** — the skill library I use every day to direct AI image and video work in Claude Code and Codex. Nine skills take an idea from *what the audience should feel* to shots, prompts and sound. <sub>(docs in Chinese)</sub>

- **Plan** — [long-video-workflow](https://github.com/chipfighter/aigc-skills/tree/main/skills/long-video-workflow) sets the direction for a 1–2 minute film, splits it into scenes, and builds it segment by segment
- **Design** — [storyboard-preview](https://github.com/chipfighter/aigc-skills/tree/main/skills/storyboard-preview) (shot tables, SVG composition sketches, preview frames) · [white-model-animation](https://github.com/chipfighter/aigc-skills/tree/main/skills/white-model-animation) (3D blocking for camera paths and staging) · [aigc-learning-skill](https://github.com/chipfighter/aigc-skills/tree/main/skills/aigc-learning-skill)
- **Generate** — [image-prompt](https://github.com/chipfighter/aigc-skills/tree/main/skills/image-prompt) (ideas into photographic language) · [video-prompt](https://github.com/chipfighter/aigc-skills/tree/main/skills/video-prompt) (acting and camera, for Seedance, Kling and more) · [natural-emotional-performance](https://github.com/chipfighter/aigc-skills/tree/main/skills/natural-emotional-performance)
- **Check & finish** — [image-spec-check](https://github.com/chipfighter/aigc-skills/tree/main/skills/image-spec-check) (a requirements checklist, crop-checked on every image) · [post-production-sound](https://github.com/chipfighter/aigc-skills/tree/main/skills/post-production-sound) (layered SFX and mixing)

### 🧩 Full-stack agent apps

- **[Agentic Tutor](https://github.com/chipfighter/gaokao_tutor)** — a multi-agent exam-prep assistant. A small router model hands each question to a tutoring, planning or emotional-support agent; study plans go through a drafter-vs-reviewers loop, then pause for the student to approve or edit.
  <br><sub>Next.js · Tailwind · React Flow ⇄ SSE ⇄ FastAPI · LangGraph · Docker Compose</sub>
- **[Spy Among Us](https://github.com/chipfighter/SpyAmongUs)** — a real-time multiplayer party game with LLM players that speak, vote and bluff. Rooms, timed rounds, voting, a private spy channel and an admin panel. My graduation project.
  <br><sub>Vue 3 · Pinia · Vite ⇄ WebSocket ⇄ FastAPI · Redis · MongoDB · JWT</sub>

### 🤝 Open source

- **[kagent-dev/kagent](https://github.com/kagent-dev/kagent)** (cloud-native agentic AI) — UI form-validation tests ([#3017](https://github.com/kagent-dev/kagent/pull/3017)) and mock-mode docs ([#2998](https://github.com/kagent-dev/kagent/pull/2998))
- Listed in [awesome-ai-plugins](https://github.com/hashgraph-online/awesome-ai-plugins), [awesome-codex-plugins](https://github.com/hashgraph-online/awesome-codex-plugins) and [up-for-grabs.net](https://github.com/up-for-grabs/up-for-grabs.net)

### 🛠 Tools I work with

<sub><b>Languages</b></sub><br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

<sub><b>Front end & desktop</b></sub><br>
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)

<sub><b>Back end & data</b></sub><br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<sub><b>Agents</b></sub><br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-4A4A4A?style=flat-square&logo=modelcontextprotocol&logoColor=white)
