# Hi, I'm Parthiv S. 👋

**AI Systems Architect | Real-Time Voice AI & Spatial Computing**

I don't build academic prototypes or rely on standard wrapper libraries. I solo-architect distributed, stateful, and fault-tolerant AI systems from zero-to-one. I specialize in extreme-low-latency Voice AI, pure LangGraph state orchestration, and Mixed Reality (MR) pipelines, solving complex concurrency and hardware bottlenecks for enterprise production environments.

### 🛠️ The Technical Arsenal

| Domain | Stack |
| :--- | :--- |
| **Orchestration & State** | Pure LangGraph, Python Dict State Management, State Machines, Concurrency Guards |
| **Real-Time Voice AI** | Deepgram Nova 3 (Streaming ASR), Groq Whisper, ElevenLabs, Silero VAD, Twilio (WebSockets) |
| **Spatial & MR** | Unity 6, Meta Quest 3 Passthrough APIs, MediaPipe, Serverless GPU Compute |
| **Backend & DevOps** | FastAPI, Uvicorn, Docker, asyncio, PostgreSQL, Vector DBs, GitHub Actions CI/CD |
| **Frontend** | React, Vite, TypeScript, Tailwind CSS, Glassmorphism UI |

---

### 🚀 Featured Architectural Feats

#### 1. Enterprise Real-Time Voice AI Platform (Production)
*An end-to-end autonomous reservation voice bot handling 370+ live concurrent calls for UK enterprise clients.*
* **The Architecture:** Designed a 13-step pure LangGraph state machine with zombie-turn protection to prevent stale DB writes during overlapping asynchronous invocations.
* **Extreme Low Latency:** Engineered a speculative LLM execution engine that fires during the VAD grace period, achieving a 67% cache hit rate and a **535ms median perceived latency**.
* **Resilience:** Built a dual ASR ensembling pipeline (Deepgram streaming + Groq Whisper large-v3-turbo batch fallback) with soft table-locking to prevent double-bookings.

#### 2. Project HoloBorn (Mixed Reality / Spatial Computing)
*A dynamic MR pipeline bridging local headset hardware with cloud-GPU serverless compute.*
* **The Engine:** Engineered a bypass for the Meta Quest 3's 4MP camera limitation by building an AI Portraitizer layer to generate high-fidelity textures without sacrificing user identity.
* **The Pipeline:** Architected a cold-start serverless CI/CD backend that generates fully rigged, animatable 3D avatars from 2D physical passthrough captures in under 6 minutes.

#### 3. Agentic Content & Orchestration Engine
*A highly distributed Hub-and-Spoke multi-agent system.*
* **Pure State Control:** Completely bypassed standard LangChain wrappers in favor of highly optimized, pure Python dictionaries for absolute deterministic state management. 
* **The Fallback:** Engineered a 5-model image generation fallback cascade (Imagen-4 → Phoenix → Flux → SDXL) guaranteeing a 95% execution success rate.

#### 4. LeadIntentAI (Open Source ML)
* **The Science:** Fine-tuned a BERT model to classify live sales conversations into 8 distinct intent categories, achieving a 95% F1-score to prove mathematical depth beyond just calling APIs. 
* **Hosted:** Available directly on Hugging Face: `Sanji8421/fine_tuned_BERT`.

---

### 🧩 My Engineering Philosophy

* **Architects Over Wrappers:** I build custom logic and strict state control. If a library abstracts away too much control, I strip it out and write it myself. 
* **Debug by Obsession:** Latency is the enemy. I don't sleep until the state machine flows deterministically and the async DB writes execute flawlessly.
* **Ship or Die:** Code that sits on a local machine is useless. I deploy containerized, production-grade systems. 

📬 **Connect:** [LinkedIn](https://linkedin.com/in/parthiv-s-831b58248) | **Email:** parthivkovilakathu@gmail.com
