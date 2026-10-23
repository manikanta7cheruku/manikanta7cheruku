# Manikanta Cheruku

I build things that actually work. Currently deep into 
**SEVEN**, the layer between you and your computer. You say 
what you want, and it happens on your PC. No cloud. No 
subscriptions. No data leaving your device.

Before that, I built a live data dashboard, a founder 
collaboration platform, and an ML app that predicts hackathon 
team performance. I like projects that have a real reason to exist.

Final year CS student from Hyderabad. Looking for roles where 
I can build things that matter.

---

## What I'm Working On

**SEVEN**: the layer between you and your Windows PC

The idea was simple: why do I have to click through the same 
apps, windows and settings every day, and why does an assistant 
need the internet to help? SEVEN sits between you and Windows. 
Say or type "set brightness to 100", "put Chrome and File Explorer 
side by side" or "save this workspace as Work", and it happens in 
milliseconds. Speech recognition, the language model and the 
memory all run locally, and it keeps working offline.

```
voice / text → ears (VAD, Whisper) → brain (29-layer pipeline) → hands (Windows actions) + mouth (Piper)
                                          ↘ local LLM via Ollama only when no instant layer can answer
```

- **Acts, then proves it.** Every action returns a receipt; if it failed, SEVEN says so.
- **Remembers with evidence.** Facts live in SQLite with history and provenance, plus a ChromaDB semantic index, so it can tell you what you said, when, and what changed.
- **Knows itself and your machine.** Abilities come from a live capability registry and an app map generated from the UI code; hardware answers come from live readings, never the model.

Built with Electron + React + Tailwind on the frontend and a 
FastAPI backend with 180+ local endpoints. Has a licensing 
system with plans and trials, in-app updates, a feedback 
pipeline, and syncs select data to a Render-hosted PostgreSQL 
server. CI runs 170+ tests, linting and builds on every pull request.

→ [Desktop App](https://github.com/manikanta7cheruku/NEURAL-SHELL) · 
[Docs](https://github.com/manikanta7cheruku/NEURAL-SHELL/tree/main/docs) · 
[Server](https://github.com/manikanta7cheruku/vii-server) · 
[Releases](https://github.com/manikanta7cheruku/seven-releases)

---

## Other Projects

**[AgentFetch](https://github.com/manikanta7cheruku/agent-fetch)**  
Pulls live weather and crypto data through real APIs. FastAPI 
backend, React dashboard, developer CLI. Built as a foundation 
for agentic automation with LLM integration down the line.

**[CoBuild](https://github.com/manikanta7cheruku/cobuild)**  
A platform for founders to find people to build with. 
The problem I kept running into myself.

**[Hackathon Predictor](https://github.com/manikanta7cheruku/Hackathon-Prediction)**  
End-to-end ML app that predicts how a hackathon team will 
perform based on commit velocity, sleep patterns, and 
communication data. Uses XGBoost with SHAP for explainability 
so you can see *why* it made a prediction.

---

## Stack

**Day to day**  
Python · JavaScript · TypeScript · SQL

**Building with**  
React · Electron · Vite · Tailwind · FastAPI · Node.js

**AI side**  
Ollama · Whisper · ChromaDB · SentenceTransformers · 
LangChain · XGBoost · SHAP

**Data**  
PostgreSQL · SQLite · ChromaDB (vector)

**Tools**  
Git · GitHub Actions · Docker · Linux · REST APIs

---

## Numbers (From SEVEN)

- 180+ local API endpoints
- 29-layer brain pipeline: commands answered in milliseconds, the LLM only when needed
- 7 local AI models working together (speech-to-text, voice activity, speaker ID, embeddings, LLM, text-to-speech, sound triggers)
- 170+ automated tests in CI
- 100% local inference, zero cloud dependency
- Runs on consumer hardware

---

## GitHub Activity

<img 
  src="https://streak-stats.demolab.com?user=manikanta7cheruku&theme=github-dark-dimmed&hide_border=true&date_format=j%20M%5B%20Y%5D" 
  width="100%"
  alt="GitHub Streak"
/>

<br/>

<p align="left">
  <img 
    src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=manikanta7cheruku&theme=github_dark&hide_border=true" 
    height="180" 
    alt="Languages"
  />
  <img 
    src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=manikanta7cheruku&theme=github_dark&hide_border=true" 
    height="180" 
    alt="Stats"
  />
</p>

<img 
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=manikanta7cheruku&theme=github_dark&hide_border=true" 
  width="100%"
  alt="Contribution Graph"
/>

---

**Python** · Hyderabad · Open to SDE and AI Engineer roles

[LinkedIn](https://linkedin.com/in/manikanta-cheruku) · 
[Portfolio](https://manikanta7cheruku.github.io/portfolio/) · 
cherukumanikanta77@gmail.com
