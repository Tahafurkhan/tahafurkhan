<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00c6ff&height=220&section=header&text=Taha%20Furkan&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Agentic%20AI%20Data%20Engineer&descAlignY=58&descSize=20" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=900&color=00C6FF&center=true&vCenter=true&width=800&lines=Agentic+AI+Data+Engineer;Azure+Data+Engineer;Databricks+Engineer;Spark+%2B+PySpark+Developer;Streaming+Data+Architect;AI+Workflow+Engineer;LangGraph+Developer;RAG+System+Builder;MCP+Integration+Engineer;Intelligent+Data+Platform+Engineer)](https://git.io/typing-svg)

<p>
  <a href="https://www.linkedin.com/in/developertaha"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:tahafurkhan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open_to-Senior%20%2F%20Staff%20Data%20%26%20AI%20Platform%20Roles-1a1a2e?style=for-the-badge&logo=databricks&logoColor=FF3621"/>
</p>

<table>
<tr>
<td align="center"><img src="https://img.shields.io/badge/🏗️_DATA_ENGINEER-0F2027?style=for-the-badge&labelColor=0F2027&color=00C6FF"/></td>
<td align="center">✕</td>
<td align="center"><img src="https://img.shields.io/badge/🤖_AGENTIC_AI_ENGINEER-1a0f2e?style=for-the-badge&labelColor=1a0f2e&color=B084FF"/></td>
<td align="center">=</td>
<td align="center"><img src="https://img.shields.io/badge/✨_AGENTIC_AI_DATA_ENGINEER-101820?style=for-the-badge&labelColor=101820&color=FFD700"/></td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=4&width=1000" width="70%"/>

</div>

<br/>

## 🧭 Value Proposition

> I design **enterprise-scale data platforms** and fuse them with **Agentic AI** to build autonomous, intelligent, production-ready systems — where pipelines don't just move data, they reason over it.

My work sits on three pillars:

| 🏗️ Data Engineering | ☁️ Cloud Data Platform | 🤖 Agentic AI Engineering |
|---|---|---|
| Spark, PySpark, Databricks, Delta Lake, Unity Catalog, Auto Loader, DLT, dbt, Airflow, Kafka, Structured Streaming | Medallion Architecture, real-time streaming, batch ETL, data governance & quality, CI/CD, Docker, GitHub Actions, IaC | LangGraph, LangChain, LangSmith, MCP servers, tool/function calling, multi-agent systems, RAG, MLflow, Databricks AI Apps |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

<div align="center">

## ⚡ The Convergence — Where Two Disciplines Become One

</div>

```mermaid
flowchart LR
    subgraph DE["🏗️ DATA ENGINEER"]
        direction TB
        D1(("Azure &<br/>Databricks"))
        D2(("Spark &<br/>Delta Lake"))
        D3(("Streaming &<br/>Governance"))
        D1 --- D2 --- D3
    end

    subgraph CORE["✨ AGENTIC AI DATA ENGINEER"]
        direction TB
        X((("🧬<br/>Autonomous<br/>Intelligent<br/>Platforms")))
    end

    subgraph AI["🤖 AGENTIC AI ENGINEER"]
        direction TB
        A1(("LangGraph &<br/>MCP"))
        A2(("RAG &<br/>Vector Search"))
        A3(("MLflow &<br/>Observability"))
        A1 --- A2 --- A3
    end

    DE ==>|"reliable, governed data"| CORE
    AI ==>|"reasoning & autonomy"| CORE
    CORE ==>|"ships production systems"| OUT(["🚀 Enterprise Impact"])

    classDef de fill:#0F2027,color:#00C6FF,stroke:#00C6FF,stroke-width:2px;
    classDef ai fill:#1a0f2e,color:#B084FF,stroke:#B084FF,stroke-width:2px;
    classDef core fill:#101820,color:#FFD700,stroke:#FFD700,stroke-width:3px;
    classDef out fill:#111,color:#fff,stroke:#00C6FF,stroke-width:2px;

    class D1,D2,D3 de
    class A1,A2,A3 ai
    class X core
    class OUT out
```

<div align="center">
<sub>Two disciplines. One engineer. Data pipelines that don't just move data — they <b>reason</b> over it, <b>act</b> on it, and <b>govern</b> it.</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

<div align="center">

## 🏛️ Reference Architecture — Lakehouse ⇄ Agent Layer

</div>

```mermaid
flowchart TD
    subgraph L1[" "]
        direction LR
        EH[Azure Event Hub / Kafka] --> SS[Spark Structured Streaming]
        SS --> AL[Databricks Auto Loader]
    end

    subgraph LAKE["🏗️ DATA ENGINEERING — Governed Lakehouse"]
        direction LR
        BR[🟫 Bronze<br/>Raw] --> SI[⬜ Silver<br/>Cleansed] --> GO[🟨 Gold<br/>Curated]
        GO --> UC[🔐 Unity Catalog<br/>Governance & Quality]
    end

    subgraph AGENTS["🤖 AGENTIC AI — Reasoning Layer"]
        direction LR
        MF[📊 MLflow<br/>Model & Prompt Registry] --> LG[🧠 LangGraph<br/>Multi-Agent Orchestration]
        LG --> MCP[🔌 MCP Servers<br/>Tool / Function Calling]
        MCP --> RAG[📚 RAG<br/>Vector + Hybrid Search]
    end

    L1 --> LAKE
    UC ==>|"trusted, governed data"| MF
    RAG ==>|"grounded answers"| USR

    USR(["👤 Enterprise Users &<br/>Autonomous Decisions"])

    style EH fill:#0F2027,color:#fff,stroke:#00C6FF
    style SS fill:#203A43,color:#fff,stroke:#00C6FF
    style AL fill:#2C5364,color:#fff,stroke:#00C6FF
    style BR fill:#8B5E34,color:#fff,stroke:#00C6FF
    style SI fill:#C0C0C0,color:#000,stroke:#00C6FF
    style GO fill:#FFD700,color:#000,stroke:#00C6FF
    style UC fill:#1a1a2e,color:#00C6FF,stroke:#00C6FF
    style MF fill:#0194E2,color:#fff,stroke:#B084FF
    style LG fill:#1C3C3C,color:#fff,stroke:#B084FF
    style MCP fill:#000000,color:#fff,stroke:#B084FF
    style RAG fill:#4B2E83,color:#fff,stroke:#B084FF
    style USR fill:#111,color:#fff,stroke:#FFD700,stroke-width:2px
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

## 🤖 Agentic AI Showcase

<table>
<tr>
<td width="50%" valign="top">

### 🧠 Autonomous Data Agents
- Intelligent workflow orchestration
- Multi-agent collaboration
- Dynamic planning & task decomposition
- Memory-enabled reasoning
- Human-in-the-loop checkpoints

</td>
<td width="50%" valign="top">

### 📚 Enterprise RAG Systems
- Hybrid search (keyword + semantic)
- Vector search & embeddings
- Context engineering
- Grounded, citation-backed responses
- Automated AI evaluation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔧 AI Tool Integration
- MCP servers
- SQL & Databricks API tool calling
- REST APIs & Azure services
- Python-native tool ecosystems
- External knowledge sources

</td>
<td width="50%" valign="top">

### 📊 LLMOps
- MLflow experiment & model tracking
- LangSmith tracing
- Prompt versioning
- Evaluation pipelines
- AI observability & monitoring

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

## 🛠️ Skills Dashboard

**☁️ Cloud**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![ADF](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![EventHub](https://img.shields.io/badge/Event%20Hub-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![ADLS](https://img.shields.io/badge/Data%20Lake%20Gen2-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![KeyVault](https://img.shields.io/badge/Key%20Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**🏗️ Data Engineering**
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![DeltaLake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logo=delta&logoColor=white)
![UnityCatalog](https://img.shields.io/badge/Unity%20Catalog-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**🌊 Streaming**
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![StructuredStreaming](https://img.shields.io/badge/Structured%20Streaming-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![EventHubStream](https://img.shields.io/badge/Azure%20Event%20Hub-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**🤖 AI Engineering**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP%20Servers-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge)
![VectorSearch](https://img.shields.io/badge/Vector%20Search-8A2BE2?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**⚙️ DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHubActions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

## 📌 Featured Projects

<table>
<tr>
<td width="50%">

### 🏞️ Intelligent Lakehouse Platform
**Azure · Spark · Databricks · Delta · Unity Catalog**
Medallion-architecture Lakehouse with governed Bronze/Silver/Gold layers and CI/CD via Azure DevOps.
📎 [`Azure-Data-Pipeline-Medallion-DevOps`](https://github.com/Tahafurkhan/Azure-Data-Pipeline-Medallion-DevOps)

</td>
<td width="50%">

### 🌊 Enterprise Streaming Pipeline
**Kafka · Event Hub · Structured Streaming · Delta Lake**
Real-time vehicle tracking & monitoring pipeline on Azure with low-latency stream processing.
📎 [`traccia-azure-streaming-pipeline`](https://github.com/Tahafurkhan/traccia-azure-streaming-pipeline)

</td>
</tr>
<tr>
<td width="50%">

### 🕵️ FinGuard — Real-Time Fraud Detection
**Databricks · Spark Structured Streaming · Kafka · Delta Lake**
Watermarked stream-stream joins detecting fraud in real time across a Bronze→Silver→Gold Lakehouse.
📎 [`fingurad_fraudetection_streaming_project`](https://github.com/Tahafurkhan/fingurad_fraudetection_streaming_project)

</td>
<td width="50%">

### 🤖 Agentic AI Data Assistant
**LangGraph · MCP · MLflow · Tool Calling · RAG**
Autonomous agent layer that reasons over Lakehouse data, calls tools, and grounds answers via RAG.
📎 *In progress — check pinned repos*

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

## 📊 GitHub Dashboard

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tahafurkhan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0D1117" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tahafurkhan&theme=tokyonight&hide_border=true&background=0D1117" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tahafurkhan&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" width="50%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Tahafurkhan&theme=tokyo-night&hide_border=true&bg_color=0D1117" width="90%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Tahafurkhan&theme=darkhub&no-frame=true&row=1&column=7" width="90%" />
</p>

<!--
Optional: contribution snake animation.
Requires a one-time GitHub Actions workflow in this repo
(platane/snk) that runs on a schedule and commits the generated
SVG below — cannot be generated from a README edit alone.
<p align="center">
  <img src="https://raw.githubusercontent.com/Tahafurkhan/Tahafurkhan/output/github-contribution-grid-snake-dark.svg" width="90%" />
</p>
-->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:7C3AED,100:00c6ff&height=3&width=1000" width="100%"/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:2C5364,100:0F2027&height=120&section=footer" width="100%"/>

*Building the future of enterprise data platforms — where Data Engineering meets Agentic AI.*

</div>
