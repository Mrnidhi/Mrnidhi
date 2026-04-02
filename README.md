<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vCenter=true&width=750&lines=Hey+there!+Welcome+to+my+profile+%F0%9F%91%8B;SWE+%7C+ML+Engineer+%7C+Data+Engineer+%7C+AI+Engineer;Distributed+Systems+%7C+Microservices+%7C+Production+ML;Building+intelligent+systems+that+scale" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Srinidhi%20Gowda&fontSize=60&fontAlignY=35&desc=Building%20distributed%20systems%2C%20production%20ML%2C%20and%20intelligent%20data%20pipelines&descAlignY=60&descAlign=center" alt="Header" />
</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Mrnidhi&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Mrnidhi?label=Followers&style=social" alt="GitHub Followers" />
</p>

## 👋 Who Am I?

Hey! I'm **Srinidhi**, a Master's student in Applied Data Intelligence at San José State University, currently studying distributed systems, ML engineering, and big data technology. I build things end-to-end — microservices, streaming pipelines, recommendation engines, and multi-agent AI systems.

What really gets me excited is the intersection of distributed systems and AI. How do you build systems where multiple services, models, and agents actually work together reliably at scale? That's the question I keep coming back to in almost everything I build.

**Looking for:** Summer 2026 internships at FAANG and top-tier tech companies:
- **Software Engineering** — distributed systems, backend services, APIs built to scale
- **Data Engineering** — streaming pipelines, lakehouse architecture, real-time analytics
- **ML Engineering** — production ML, MLOps, recommendation systems, inference optimization
- **AI Engineering** — agentic systems, LLM evaluation, multi-agent orchestration

**📍** San Jose / SF Bay Area, CA &nbsp;|&nbsp; **📧** srinidhi.connects@gmail.com &nbsp;|&nbsp; **📱** +1 (669) 243-7083

---

## 🚀 What I've Built

<table>
<tr>
<td width="50%">

### 🔄 [AI-RAG-Kafka-Streaming](https://github.com/Mrnidhi/AI-Rag-Kafka-Streaming)

Built a production RAG system as 4 polyglot microservices — Go (Fiber), Java 21 (Spring Boot 3), Python (FastAPI + LangChain), PostgreSQL/pgvector — all connected through Kafka for async document ingestion. Full observability with OpenTelemetry, Prometheus, Grafana, and Jaeger. Accuracy evaluated with RAGAS.

**What it shows:** Polyglot microservices architecture · Async event-driven design · Production observability

**Stack:** Go, Java 21, Python, FastAPI, Kafka, pgvector, Redis, OpenTelemetry, Docker

</td>
<td width="50%">

### 🎯 [Two-Tower Recommendation System](https://github.com/Mrnidhi/Two-Tower_Recommendation)

Two separate embedding towers — one for users, one for items — handle fast candidate retrieval via ANN search, and a gradient boosting model re-ranks the results. Real-time feature updates flow through Kafka between stages. The same retrieval-then-ranking pattern used behind large-scale recommendation feeds.

**What it shows:** Retrieval → Ranking pipeline · Real-time feature streaming · Vector search at scale

**Stack:** PyTorch, FastAPI, Kafka, Redis, PostgreSQL, Nginx, Prometheus, Docker

</td>
</tr>
<tr>
<td width="50%">

### 🏨 [AtlasReserve](https://github.com/Mrnidhi/AtlasReserve)

Full-stack restaurant reservation platform built with Java 17 + Spring Boot 3 on the backend and Next.js 15 + React 19 on the front. Real-time conflict detection on bookings, location-based search via Google Maps, OTP auth, and deployed across 5 AWS services (Cognito, S3, SES, Elastic Beanstalk, Lambda) with GitHub Actions CI/CD.

**What it shows:** Full-stack SWE depth · AWS deployment · Real-time data consistency

**Stack:** Java 17, Spring Boot 3, Next.js 15, React 19, MySQL, AWS, Docker, GitHub Actions

</td>
<td width="50%">

### 🤖 [Multi-Agent AI Platform](https://github.com/Mrnidhi/multi-agent-ai)

Built a platform where 4 specialized AI agents collaborate autonomously — they designed, built, and deployed a trading simulation together without me stepping in. Agents communicate through structured handoffs, with role-based task delegation built from scratch. 95% test coverage across 25+ edge cases.

**Results:** 60% faster dev cycle · 100% invalid transaction prevention · 95% test coverage

**Stack:** CrewAI, Python, Gradio, OpenAI GPT-4

</td>
</tr>
<tr>
<td width="50%">

### 🛠️ [DataEngineering Copilot](https://github.com/Mrnidhi/DataEngineering_Copilot)

A self-healing plugin for Apache Airflow that hooks into the Listener API to detect task failures as they happen, runs LangChain + LLM root-cause analysis on the logs and DAG code, generates a patch, and routes it through Slack or GitHub for approval before applying it. Supports Ollama locally and cloud LLM backends.

**What it shows:** AIOps · LLM-powered debugging · Human-in-the-loop automation

**Stack:** Python, Apache Airflow, LangChain, Ollama, Streamlit, Docker

</td>
<td width="50%">

### 🎬 [Real-Time YouTube Analytics](https://github.com/Mrnidhi/yt-analysis)

Serverless pipeline on AWS: Lambda pulls YouTube metrics, Glue converts JSON to Parquet (5x query speedup), Athena queries the data lake, and Airflow orchestrates the whole thing. Tableau and QuickSight dashboards sit on top for daily product team use.

**Results:** 90% less manual data prep · 5x faster queries · Sub-second insights for 10k+ records

**Stack:** AWS Lambda, Glue, Athena, S3, Apache Airflow, Spark, Tableau, QuickSight

</td>
</tr>
<tr>
<td width="50%">

### 🏗️ [Azure Medallion Data Pipeline](https://github.com/Mrnidhi/ETL-azure.git)

Bronze-Silver-Gold lakehouse on Azure Databricks pulling from 8 sources with 100k+ records per run. Kafka handles real-time ingestion, dbt transforms data at each layer, and Power BI + Synapse serve the analytics. Built this because flat ETL scripts fall apart at this volume.

**Performance:** 60% faster processing · Powers $2M+ in revenue analytics · 8 data source integrations

**Stack:** Azure Databricks, Data Factory, Kafka, dbt, Power BI, Synapse, Docker

</td>
<td width="50%">

### 🤖 [AI Customer Support Assistant](https://github.com/Mrnidhi/Customer-Support-assistant)

RAG-powered assistant that searches 10k+ historical support tickets to answer new questions instantly — sub-second responses with source citations. FastAPI handles embedding generation and ChromaDB vector search; Next.js is the chat frontend.

**Impact:** 70% faster resolution times · 95% answer accuracy · Sub-second RAG with source citations

**Stack:** FastAPI, Next.js, Sentence Transformers, ChromaDB, Google Gemini API

</td>
</tr>
<tr>
<td width="50%">

### 💰 [Intelligent Financial Research Platform](https://github.com/Mrnidhi/financial-research-ai)

Replaced hours of manual research with a CrewAI agent pipeline that scrapes live web data, processes unstructured filings, and produces structured investment reports end-to-end. 90% report accuracy, fully automated.

**Speed:** 95% reduction in research time · 90% report accuracy · 100% automated

**Stack:** CrewAI, OpenAI GPT-4, Python, SerperDev API

</td>
<td width="50%">

### ✈️ [PlanPilot](https://github.com/Mrnidhi/PlanPilot)

Travel planner you interact with through a Telegram bot — describe your trip in plain language and the system returns a full itinerary. Java Spring Boot handles orchestration, Python CrewAI + Google Vertex AI runs the planning agents, and RabbitMQ decouples the services asynchronously. Two languages, async messaging, and real-world data grounding via Maps + Serper APIs.

**What it shows:** Multi-language microservices · Async messaging · Conversational AI interface

**Stack:** Java Spring Boot, Python, CrewAI, Google Vertex AI, RabbitMQ, PostgreSQL, Docker

</td>
</tr>
</table>

<div align="center">
  <a href="https://github.com/Mrnidhi?tab=repositories">
    <img src="https://img.shields.io/badge/View%20All%20Repos-100000?style=for-the-badge&logo=github&logoColor=white" alt="All Repositories" />
  </a>
</div>

---

## 💼 Work Experience

### Data Scientist @ WebNet Solutions &nbsp;|&nbsp; *May 2024 – Nov 2024*

<p align="center">
  <img src="https://img.shields.io/badge/XGBoost%20Churn%20Model-84%25%20Precision-success?style=flat-square&logo=amazonaws" alt="XGBoost" />
  <img src="https://img.shields.io/badge/ETL%20Pipelines-25k%2B%20Records%2Fday-blue?style=flat-square&logo=apacheairflow" alt="ETL" />
  <img src="https://img.shields.io/badge/Redshift%20Optimization-50%25%20Faster-orange?style=flat-square&logo=amazonredshift" alt="Redshift" />
</p>

- Deployed an XGBoost churn model on AWS SageMaker — 84% precision, reduced customer attrition by 12%, improved renewals by 15%
- Built serverless ETL pipelines with Lambda + Glue + Airflow processing 25k+ records/day, improving data quality by 30%
- Optimized Redshift schema and partitioning — 50% faster queries, 30% storage cost reduction

### Data Science Intern @ WebNet Solutions &nbsp;|&nbsp; *Dec 2023 – May 2024*

- Built supervised and unsupervised ML models that beat baseline by 18%
- Engineered preprocessing pipelines for multi-million-row datasets — 35% faster processing
- EDA and feature engineering work that improved model inputs by 20%

---

## 🛠️ Tech Stack

<div align="center">

### Languages
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
</p>

### Backend & Distributed Systems
<p>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

### Cloud & Data Engineering
<p>
<img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" alt="Spark" />
<img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white" alt="Airflow" />
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake" />
<img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />
<img src="https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=for-the-badge&logo=amazon-redshift&logoColor=white" alt="Redshift" />
</p>

### ML & AI
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
<img src="https://img.shields.io/badge/XGBoost-3776AB?style=for-the-badge&logo=xgboost&logoColor=white" alt="XGBoost" />
</p>

### Observability & Databases
<p>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
</p>

### Frontend
<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" alt="Power BI" />
</p>

</div>

---

## 💡 What Drives Me

I like building things that actually work in production — not just in notebooks or demos. The 80/20 I keep running into: most ML failures aren't model problems, they're data and infrastructure problems. That's what pushed me toward distributed systems and data engineering alongside the ML side.

Right now I'm deep into:

- **Agentic AI** — building systems where agents collaborate and execute autonomously rather than just answering prompts. Still figuring out the hard parts: failure recovery, inter-agent trust, and knowing when to hand back to a human
- **Advanced RAG** — hybrid search, cross-encoder re-ranking, multi-hop reasoning. Basic retrieval is a solved problem; making it actually reliable isn't
- **Distributed systems design** — studying consistency models, consensus, and how large systems stay up when things go wrong
- **Privacy-preserving ML** — differential privacy, federated learning. Important work that doesn't get enough attention
- **LLM fine-tuning** — making foundation models actually useful for specific domains without breaking their general capability

---

## 🎓 Education

**M.S. in Applied Data Intelligence** &nbsp;|&nbsp; San José State University &nbsp;|&nbsp; *Jan 2025 – May 2027*

Coursework: **Distributed Systems**, Data Warehousing & Pipelines, Big Data Technology, Machine Learning, Deep Learning, Statistical Analysis, Generative AI Applications, Data Mining, Data Visualization

**B.E. in Electrical & Electronics Engineering** &nbsp;|&nbsp; PES College of Engineering, India

---

## 📈 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mrnidhi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mrnidhi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mrnidhi&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mrnidhi&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
</div>

---

## 🏆 GitHub Achievements

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Mrnidhi&theme=tokyonight&column=7&margin-w=15&margin-h=15&no-frame=true" alt="GitHub Trophies" />
</div>

---

## 📫 Let's Talk

Whether you're hiring, building something interesting, or just want to geek out about distributed systems or AI — hit me up.

<p align="center">
  <a href="https://www.linkedin.com/in/srinidhi-gowda/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:srinidhi.connects@gmail.com">
    <img src="https://img.shields.io/badge/Email-srinidhi.connects%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Mrnidhi">
    <img src="https://img.shields.io/badge/GitHub-Mrnidhi-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="Footer" />
</div>

<p align="center">
  <i>"The best way to predict the future is to build it."</i>
</p>

<p align="center">
  If you find a project useful, a ⭐ is always appreciated — helps others discover the work too.
</p>
