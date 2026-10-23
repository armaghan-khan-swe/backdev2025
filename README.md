# Hi, I'm Armaghan 👋

### AI & Backend Engineer | Scalable Systems | AI Integration

I build **intelligent, reliable, and scalable backend systems** that solve real-world problems.

My work focuses on AI-powered applications, retrieval-augmented generation (RAG), API development, data processing, and workflow automation. I care about building systems that are not only functional, but also maintainable, secure, and production-ready.

- 🤖 Building AI-powered applications and RAG pipelines
- ⚙️ Developing backend services with Python, FastAPI, and Go
- 🔎 Working with LLM integrations, vector search, and real-time data synchronization
- 🗺️ Building data-driven platforms and automated workflows
- 🐳 Exploring scalable deployments, system architecture, and backend reliability

**Smart Models. Solid Systems.**

---

## 🧠 System Design & Architecture

I focus on designing systems with clear boundaries between APIs, business logic, AI services, background processing, and data storage.

### Example: RAG System Architecture

```mermaid

flowchart TB
    subgraph INGEST["01 · DATA INGESTION"]
        SRC["Documents / Live Data"]
        PARSE["Parse & Clean"]
        CHUNK["Chunking + Metadata"]
        EMBED["Embedding Model"]
        VDB[("Vector Database")]

        SRC --> PARSE --> CHUNK --> EMBED --> VDB
    end

    subgraph QUERY["02 · QUERY PIPELINE"]
        USER(["User Question"])
        API["FastAPI"]
        QEMBED["Query Embedding"]
        RETRIEVE["Similarity Search"]
        CONTEXT["Retrieved Chunks"]
        PROMPT["Context + Prompt"]
        LLM["LLM"]
        VALIDATE["Grounding / Output Validation"]
        ANSWER(["Answer + Citations"])

        USER --> API --> QEMBED --> RETRIEVE
        RETRIEVE --> CONTEXT --> PROMPT
        PROMPT --> LLM --> VALIDATE --> ANSWER
        VDB -.-> RETRIEVE
    end

    classDef entry fill:#172554,stroke:#60A5FA,color:#FFFFFF
    classDef service fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef storage fill:#3B2F63,stroke:#A78BFA,color:#FFFFFF

    class USER,ANSWER entry
    class PARSE,CHUNK,EMBED,API,QEMBED,RETRIEVE,CONTEXT,PROMPT,LLM,VALIDATE service
    class VDB storage

```

*Illustrative architecture demonstrating how ingestion and retrieval fit together in a RAG application.*

---

## 🛠️ Technical Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### Backend Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

### AI & LLM Engineering

![LLMs](https://img.shields.io/badge/LLM_Integration-6C47FF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_Pipelines-2563EB?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Langflow](https://img.shields.io/badge/Langflow-8A2BE2?style=flat-square)

### Databases & Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Infrastructure & Automation

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4AAA?style=flat-square&logo=n8n&logoColor=white)
![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=flat-square&logo=nextcloud&logoColor=white)

---

## 🚀 Areas of Work

| Area | Focus |
|---|---|
| AI Engineering | LLM integration, RAG, retrieval, context management |
| Backend Development | REST APIs, service architecture, validation, authentication |
| Data Systems | Database design, vector search, real-time synchronization |
| Workflow Automation | Event-driven workflows, integrations, background processing |
| Infrastructure | Docker, Linux, Nginx, deployment and server operations |

---

## 📌 What I Value

- **Clean architecture** — clear boundaries and maintainable code.
- **Reliability** — predictable behavior, validation, and meaningful error handling.
- **Security** — protecting data, credentials, and application boundaries.
- **Performance** — efficient database access, caching, and asynchronous processing.
- **Practical AI** — building AI features that solve real problems rather than adding AI without purpose.

---

## 🤝 Let's Connect

I'm interested in collaborating on AI-powered applications, backend platforms, RAG systems, and scalable software architecture.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/backdev2025)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=backdev2025&label=Profile%20Views&color=2563eb&style=flat" alt="Profile views" />
</p>
