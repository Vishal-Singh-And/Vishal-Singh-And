<h1 align="center">Hi, I'm Vishal Singh 👋</h1>
<p align="center"><b>I build AI tools for teachers and students — K–12, India, in many Indian languages.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js_16-000000?logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
</p>

---

### 🧑‍🏫 What I work on

I work at **Apps and Devices**. I make education products where generative AI does the heavy lifting
and a teacher stays in charge. My users are school teachers, many in government schools. So the
tools must work in their language, print well on paper, and keep working offline.

### 🚀 Featured projects

**🍎 AI Teacher Assistant** · *Next.js 16 · React 19 · Prisma + PostgreSQL · pg-boss · GCS · Gemini / OpenRouter / Ollama*
A teacher picks a board, class, subject, chapter and sub-topic. The app then makes ready-to-teach material:
- **17 content types**: lesson plans, slide decks, worksheets, mind maps, flashcards, comics, summaries, podcasts and more
- **Question papers** with marking schemes and maths rendered in LaTeX/KaTeX
- **Present mode** for the classroom, print-ready layouts, and offline HTML/ZIP exports
- **Indian languages** (Hindi, Tamil, Assamese and more), including neural text-to-speech voices
- **Ask AI**: a chat assistant on a local Ollama model, with Gemini as fallback
- **Production pieces**: schools and roles, invites, usage limits per user, a background job queue, a shared library on Cloud Storage, backups and daily reports

**🧠 Stucle Q-Agent** · *FastAPI · Next.js · Google ADK · Gemini + Ollama · Docker*
A multi-agent system that writes assessment questions for CBSE/NCERT, JEE and NEET. One agent drafts each
question. A pedagogy-and-critic agent then checks it for correctness, maths/LaTeX and difficulty for the board.
Only questions that pass this check are saved.

**📚 NCERT Knowledge Base** · *OCR · hybrid retrieval · Qdrant + BM25 · cross-encoder rerank*
A RAG pipeline for the Class 11–12 NCERT science and maths textbooks: OCR → chapter tree → chunks
by content type → embeddings → hybrid search with re-ranking. Tutoring agents query it.

**🎬 ARL Creator Studio** · *Next.js · Gemini*
A subject expert gives a course outline. The studio turns each topic into 14 kinds of learning material,
including rendered video. Every piece downloads as a file that works offline.

**🗺️ AI Curriculum Designer** · *Next.js*
Generates themed courses and mind maps from a short brief.

### 🛠️ How I build

- **AI-paired engineering.** I build with Claude Code. Every feature is a numbered phase (P0 → P120+)
  with a written plan, a design review and a commit of its own.
- **Design first.** I draw the screens in **Penpot** before writing code, and the app's own artwork is exported from there.
- **Gates, not hope.** Every phase adds `verify:*` scripts. They include headless-Chrome checks of the real UI at
  phone and desktop widths, layout and overflow checks, and mutation tests to prove the gate can fail.
- **Cost-aware AI.** A ledger records every model call. Paid image and voice generation never runs inside tests.
  Fallback chains route each call to a cloud or local model.
- **Built for the classroom.** Indic scripts, print layouts, low bandwidth, offline exports.

### 📫 Reach me

- ✉️ vishal_singh@appsndevices.in

<!-- Most of my work lives in private repositories. Ask me for a walkthrough. -->
