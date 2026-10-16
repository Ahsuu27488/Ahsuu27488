# Hi, I'm Muhammad Ahsan 👋

I build **AI agents, RAG chatbots and full-stack apps**, and take them all the way to production: code, deployment, docs and releases. I'm a developer from Nawabshah, Pakistan, and a student in the GIAIC / [Panaversity](https://github.com/panaversity) program.

## 🛠️ Latest: Taskvane, a better Task Manager for Windows 11 · [code](https://github.com/Ahsuu27488/taskvane) · [site](https://taskvane.ahsandev.site)

<a href="https://taskvane.ahsandev.site"><img src="https://raw.githubusercontent.com/Ahsuu27488/taskvane/main/website/public/img/og.png" alt="Taskvane: a better Task Manager for Windows 11" width="560"></a>

A free, open-source Windows app with CPU and GPU temperatures, power draw in watts and battery health, using about 0.4% CPU.

- Python desktop app with a WebView2 UI, hardware sensors in a crash-isolated helper process, and process stats from a single `NtQuerySystemInformation` call
- Handles elevation, a signed kernel driver and scheduled tasks; ships as an installer and a portable zip through GitHub Actions
- [Website](https://taskvane.ahsandev.site) built with Astro, with structured data for search engines and AI assistants

## 🤖 What I do with AI

- **AI agents:** multi-agent systems on the **OpenAI Agents SDK** with handoffs between specialist agents, streaming responses and tools that change real data
- **MCP:** I write my own **Model Context Protocol** servers and tools, so an agent can create, update, complete, delete and search records safely, scoped to each user
- **RAG:** ingestion pipelines that chunk content, embed it into **Qdrant** and answer questions grounded in the source, with semantic search that falls back to keywords
- **Voice:** speech-to-text with **Whisper**, so users can manage their data by talking, in English, Urdu and Roman Urdu
- **Agentic development:** I build with **Claude Code** using spec-driven development, custom subagents, skills and plugins, and I publish my own plugins

## ⭐ Featured work

### Chronos: an AI assistant that runs your to-do list · [code](https://github.com/Ahsuu27488/evolution-of-todo) · [live](https://evolution-of-todo-tau.vercel.app)

A task manager built in five phases, from a Python console app to an AI agent system deployed on Kubernetes.

- **Chat or talk to it:** "remind me to pay rent on Friday", "what's due this week?", "mark the grocery one done". A main **Chronos agent** hands off to a **Planning agent** (weekly plans, priorities) and a **Query agent** (complex searches), built with the OpenAI Agents SDK and gpt-4o-mini
- **7 MCP tools I built myself:** `add_task`, `update_task`, `complete_task`, `delete_task`, `list_tasks`, `get_task` and `semantic_search`, each acting only on the signed-in user's tasks
- **Voice control:** record a command, Whisper transcribes it (tuned for Urdu speakers), and the agent carries it out; it asks to confirm when the transcription is unclear
- **Semantic search:** "grocery items" finds "buy milk" and "eggs", using OpenAI embeddings in Qdrant
- **Notifications:** due-date reminders and completion alerts arrive in real time in the app (SSE), as browser push notifications and by email (Resend), on the channels each user chooses, plus daily and weekly digests from a background scheduler
- **Real-time UI:** changes the agent makes show up instantly on the task board, without a refresh
- **Cloud-native:** Docker, Helm, Kubernetes (Minikube, Oracle OKE), Dapr and Kafka-compatible event streaming (Redpanda)
- **Stack:** Next.js 15, FastAPI, SQLModel, Neon PostgreSQL, Better Auth, Zustand, TanStack Query

### Physical AI & Humanoid Robotics: an AI-native textbook · [code](https://github.com/Ahsuu27488/physical-ai-textbook) · [live](https://ahsuu27488.github.io/physical-ai-textbook/)

An interactive textbook (ROS 2, Gazebo, NVIDIA Isaac, vision-language-action models) with AI built in.

- **RAG chatbot:** an ETL pipeline chunks every lesson, embeds it into Qdrant, and the chatbot answers questions from the book's own content with gpt-4o-mini
- **Personalization:** lessons adapt to the reader's software and hardware background
- **One-click Urdu translation** by an LLM, cached so each page is only translated once
- **Stack:** Docusaurus, FastAPI, Qdrant, OpenAI, Better Auth, deployed on GitHub Pages and Railway

## 🚀 More projects

| Project | What it is | Built with |
|---|---|---|
| **[Edit Recreator](https://github.com/Ahsuu27488/edit-recreator)** | Claude Code plugin that recreates any short-form video edit (TikTok, Reels, CapCut, After Effects) frame by frame in Remotion | Claude Code skills, Remotion, Python |
| **[PCAO-F study pack](https://github.com/Ahsuu27488/pcao-f-study-pack)** · [live](https://tinyurl.com/pcao-f) | Exam prep for my cohort: 10 crash courses, flashcards, 180 questions and a timed mock test in English, Roman Urdu and Urdu | HTML, CSS, JavaScript |
| **[GameLoop WASD fix](https://github.com/Ahsuu27488/gameloop-pubgm-wasd-speed-fix)** and **[keymap copier](https://github.com/Ahsuu27488/pubgm-flash-keymapping-gameloop)** | Tools for PUBG Mobile players on GameLoop: instant WASD direction changes, and copying a keymapping between game builds | PowerShell |
| **[Furniro](https://github.com/Ahsuu27488/ui-ux-hackathon)** · [live](http://furniro-hackathon.netlify.app/) | Furniture e-commerce store from the Governor IT Initiative UI/UX hackathon | Next.js, TypeScript, Tailwind CSS |
| **[Lead lifecycle](https://github.com/Ahsuu27488/lead-lifecycle-overview)** · [live](https://lead-lifecycle-overview000.netlify.app/) | Lead management system with role-based workflows | TypeScript |
| **[BlogsTerra](https://github.com/Ahsuu27488/BlogsTerra)** · [live](http://blogsterra.netlify.app/) | Responsive blog with a headless CMS | Next.js, Tailwind CSS, Sanity |

## 🧰 What I work with

- **AI and agents:** OpenAI Agents SDK, Model Context Protocol (MCP), RAG, Qdrant, OpenAI embeddings, gpt-4o-mini, Whisper, Claude Code (skills, subagents, plugins), spec-driven development
- **Languages:** Python, TypeScript, JavaScript, SQL, PowerShell
- **Backend and data:** FastAPI, SQLModel, Alembic, PostgreSQL (Neon), SSE streaming, web push, background schedulers
- **Frontend:** Next.js, React, Tailwind CSS, shadcn/ui, Zustand, TanStack Query, Docusaurus, Astro
- **Cloud and DevOps:** Docker, Kubernetes, Helm, Dapr, Kafka (Redpanda), Oracle Cloud, GitHub Actions, Vercel, Railway, Cloudflare
- **Windows:** pywebview / WebView2, Win32 APIs, .NET interop, PyInstaller, Inno Setup

## 📫 Find me

- 💼 [LinkedIn](https://www.linkedin.com/in/muhammad-ahsan-653298289/)
- 🌐 [taskvane.ahsandev.site/about](https://taskvane.ahsandev.site/about/)

If something I built helped you, a ⭐ on the repo is the best thanks.
