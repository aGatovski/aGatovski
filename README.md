<div align="center">

# Hey, I'm Antonio 👋

### Backend & AI Engineer
**Currently:** Backend Developer Intern @ SAP Labs Bulgaria 🇧🇬

Building production systems by day, training models by night.

---

</div>

### 👨‍💻 About Me

Software Engineer with a focus on backend systems and applied AI. I work on enterprise-scale software at SAP while building AI-powered projects on the side — from LLM-integrated financial assistants to hackathon-winning language games. Currently deepening my knowledge in machine learning and agentic AI systems.

* 🔭 **Currently working on:** finance-agent — a full-stack agentic finance assistant with a LangGraph-powered chat backend, semantic RAG transaction retrieval, and an ML ingest pipeline
* 🌱 **Currently learning:** PyTorch, deep learning fundamentals, agentic AI patterns
* 🥅 **2026 Goal:** Ship production-ready AI systems and land a role at the intersection of backend engineering and applied ML
* ⚡ **Hobbies:** Skiing ⛷️, Fitness 🏋️‍♂️, Outdoor adventures 🌲

### 🌐 Connect with me:
<div align="center">

<a href="https://www.linkedin.com/in/antonio-gatovski-523957288" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</div>

### 🛠️ Languages and Tools:

<img align="left" alt="Python" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="padding-right:10px;" />
<img align="left" alt="PyTorch" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" style="padding-right:10px;" />
<img align="left" alt="Java" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" style="padding-right:10px;" />
<img align="left" alt="FastAPI" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" style="padding-right:10px;" />
<img align="left" alt="PostgreSQL" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" style="padding-right:10px;" />
<img align="left" alt="TypeScript" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" style="padding-right:10px;" />
<img align="left" alt="Next.js" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" style="padding-right:10px;" />
<img align="left" alt="Docker" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" style="padding-right:10px;" />
<img align="left" alt="SAP ABAP" width="26px" src="https://cdn.simpleicons.org/sap/008FD3" style="padding-right:10px;" />
<img align="left" alt="Git" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="padding-right:10px;" />

<br /><br /><br />

---

## 🏆 Hackathon Highlights

| Project | Event | Description & Stack | Achievement |
| :--- | :--- | :--- | :--- |
| **Alingo 👽** | *FMI{Codes}* | A sci-fi linguistic puzzle game where players translate alien languages to save a spaceship. <br> 🛠️ `Python` `AI/LLMs` `TypeScript` `Next.js` | 🥈 **2nd Place** |
| **CIX 🎮** | *Crossroads AI Hackathon (150+ participants)* | AI-powered word puzzle game where players solve interconnected word chains through linguistic relationships. Features GPT-4 dynamic puzzle generation, neural network-style BFS validation, real-time feedback, and CEFR multi-language support (A1–C1). <br> 🛠️ `Python` `FastAPI` `OpenAI` `TypeScript` `Next.js` | 🥇 **1st Place** |

---

## 🚀 Featured Projects

### 💸 [finance-agent](https://github.com/aGatovski/Python/tree/main/finance-agent)
A full-stack agentic personal finance assistant with a LangGraph-powered chat backend, semantic RAG retrieval, and an ML ingest pipeline.

* **LangGraph agent:** multi-step reasoning loop with tool-calling for budgets, goals, and spending queries — the agent plans, retrieves context, and executes actions from natural language
* **RAG transaction retrieval:** transactions are embedded with sentence-transformers and stored in pgvector; the agent retrieves semantically relevant history to ground every response in real data
* **ML ingest pipeline:** CSV normalization → merchant extraction → embedding-based category classifier with LLM fallback; classified outputs are written back to retrain the classifier over time
* **Full-stack:** React + TypeScript frontend with pages for dashboard, transactions, budgets, goals, merchants, and chat; Dockerized for local dev
* 🛠️ `Python` `FastAPI` `LangGraph` `PostgreSQL` `pgvector` `Sentence Transformers` `React` `TypeScript` `Docker`

### 🎙️ [Slavic Language Identification](https://github.com/aGatovski/slavic-lid)
A systematic deep learning study of automatic spoken language identification across 8 Slavic languages, evaluated at three tiers of model capacity.

* **Three-tier progression:** shallow CNN on log-Mel spectrograms → Transformer encoder with AAM-Softmax → fine-tuned XLS-R-300M, evaluated against parallel CE-baseline and MFCC-feature tracks
* **Best system (Whisper-small fine-tune):** macro-F1 = 0.795 in-domain (MCV, 107k samples) and 0.817 OOD (FLEURS, 6k samples)
* **Core research question:** does metric-learning loss (ArcFace/AAM-Softmax) consistently beat plain cross-entropy as model capacity scales?
* 🛠️ `Python` `PyTorch` `HuggingFace` `XLS-R` `Whisper` `Google Colab` `Kaggle` 
* 📄 *Academic paper — FMI Sofia University*
