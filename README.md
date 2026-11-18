<h1 align="center">Hi, I'm Syed Ali Ahmed</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=620&lines=AI+Engineer+building+agents+that+do+real+work;LangGraph+%C2%B7+RAG+%C2%B7+Evals+%C2%B7+FastAPI;Turning+messy+problems+into+working+systems" alt="AI Engineer building agents that do real work" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/syed-ali-343aa5268"><img src="https://img.shields.io/badge/LinkedIn-Let%27s%20connect-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:aliiahmed8527@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## About me

I'm an AI engineer from Islamabad, Pakistan, with a BS in Software Engineering from IIUI. In a little over three years I've gone from data science trainee to building agent systems that real teams use every day, across FinTech, public safety, cloud SaaS, and PropTech.

What I love most is the engineering around the model: choosing the right tools, managing memory and context, handling the messy edge cases, and proving with evals that it all works. An agent that stops and asks a good clarifying question makes me happier than one that confidently guesses.

- Currently an **AI Engineer at Zoneomics**, building agents that automate zoning research
- I don't ship an agent I haven't measured, so evals and tracing are part of every project
- I enjoy making LLM apps faster and cheaper with caching, model routing, and fewer LLM calls
- Ask me about LangGraph, multi-agent design, RAG vs GraphRAG, or agent evals

---

## Featured projects

### [DeepAgent BI Platform](https://github.com/Syedaliahmed852728/BI-platform-agent)

A multi-tenant BI agent that answers business questions in plain English over each client's SQL database, and gets better the more it's used.

- Remembers successful queries in Redis Vector Search, so a repeat question can skip SQL generation and come back faster and cheaper
- A background worker turns good runs into clean, reusable examples, with no model retraining
- Validates SQL before running it, resolves fuzzy entity names, and keeps every client's data and memory isolated

**Stack:** DeepAgents · LangGraph · LangChain · OpenAI · Redis Vector Search · SQL Server · FastAPI

### [Zoning Map Finder](https://github.com/Syedaliahmed852728/Zoneomics-assessment)

Ask for *"zoning map of Princeton, TX"* and it hunts down every version on the web, downloads the PDFs, reads the date printed on each, and tells you which one is newest.

- A LangGraph pipeline that makes only **2 LLM calls per run**, so it works even on a small local model
- Switch between Anthropic, OpenAI, and Ollama with a quick config change
- Interactive ArcGIS maps that can't be downloaded are still reported instead of quietly dropped
- It started as my Zoneomics assessment, and today I work on problems like it there full-time

**Stack:** LangGraph · FastAPI · pdfplumber · DuckDuckGo + Tavily search · Docker

### [LuxeStay AI: Voice Hotel Booking Agent](https://github.com/Syedaliahmed852728/booking-agent)

A voice-first booking agent: you talk, it listens, finds you a room, and answers out loud.

- faster-whisper for speech-to-text and Kokoro for text-to-speech, both running locally
- A LangGraph workflow with an auth check, tools to search hotels, find available rooms, and create reservations, and a step that picks up booking details as the conversation goes
- Runs on open-source models through Groq, with a fallback model and a small fast model for quick classification

**Stack:** LangGraph · Groq (gpt-oss, Qwen, Llama) · faster-whisper · Kokoro TTS · FastAPI · PostgreSQL

### [EchoSafe: Disaster Risk Platform](https://github.com/Syedaliahmed852728/echosafe-disaster-platform)

My final year project: an end-to-end platform that forecasts earthquake, heatwave, and hailstorm risk across Pakistan.

- Incremental bronze → silver → gold pipelines over 10 years of data from USGS, NASA POWER, Open-Meteo, and IEM
- scikit-learn models with time-based train/test splits and SMOTE for rare events, plus a rule-based flood risk scorer
- A Streamlit dashboard with login, a regional risk map, and alerts, with Airflow DAGs for daily runs

**Stack:** Python · scikit-learn · PostgreSQL · Airflow · Streamlit

---

## What I've built at work

- **Multi-agent trading assistant** (FinTech contract): trend, momentum, and volatility agents with human approval on every trade signal, cutting the manual workflow by about 90%
- **Cloud audit agents** (Kubar.io): moved retrieval from flat RAG to Neo4j GraphRAG for about 30% better accuracy, measured with DeepEval and LangSmith every sprint
- **Accident data pipeline** (Navisafe.io): made a messy government-data pipeline incremental and 30% faster, then moved it from Azure Functions to Kubernetes
- **Database chatbot** (freelance): answers questions over millions of rows by writing its own SQL, and asks a clarifying question instead of guessing when it gets stuck

---

## Tech I work with

**Languages and backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**AI and agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![DeepAgents](https://img.shields.io/badge/DeepAgents-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-333333?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-7C3AED?style=flat-square)

**Data and ML**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Cloud and DevOps**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## What I'm exploring now

- Agents that stay reliable on messy, real-world input
- Agent memory, context management, and multi-tenant design
- Smarter retrieval with vector, hybrid, and graph search
- Evaluation and observability for LLM systems

---

<p align="center">
  If you're building with agents, or just want to swap notes on LangGraph, I'd love to hear from you.<br/>
  <strong>Let's build something useful together. 🚀</strong>
</p>
