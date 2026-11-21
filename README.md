<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=170&section=header&text=Gargi%20Gore&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Engineer%20%7C%20Always%20building%2C%20always%20learning&descSize=16&descAlignY=58" width="100%"/> <p align="center"> <a href="https://www.linkedin.com/in/gargi-gore"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> <a href="mailto:goregargi25@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a> </p>
About Me

Software Engineer with 4+ years at Dell Technologies, where I built Python automation and CI/CD workflows for enterprise distributed storage platforms (PowerStore, PowerFlex) using Jenkins, Docker and Kubernetes.

I am now focused on data engineering: designing batch and streaming pipelines with PySpark, orchestrating workflows, and deploying data infrastructure that is scalable, reliable and easy to maintain. I hold an M.Tech in Big Data Analytics and am pursuing an MS in Data Science & Engineering at CCNY.

🎓 MS in Data Science & Engineering at The City College of New York
🧠 M.Tech in CSE with a Big Data Analytics specialization (Hadoop, Hive, Spark)
🏆 Hackathon awards in AI in 2023, 2025 and 2026
🌱 Currently building with Airflow, dbt, Kafka and Terraform
How I Build Pipelines
SourcesAPIs · files · streams
IngestPython · Kafka
Raw layerobject storage
TransformPySpark · dbt
Analytics layerwarehouse
Dashboardsand consumers
OrchestrationAirflow
CI/CDGitHub Actions · Docker

My rules for a pipeline:

Scalable. Partitioned storage and distributed processing that grow with the data.
Reproducible. One docker compose up brings everything up locally.
Idempotent. Re-running a job never duplicates or corrupts data.
Observable. When something fails, the logs and lineage show where and why.
My Work
📈 Real-Time Market Data Pipeline

Streaming · Live   CI

A streaming pipeline that ingests live crypto trades from the Coinbase WebSocket feed, processes them with Spark Structured Streaming, and serves real-time market metrics and pipeline health on a Grafana dashboard.

<a href="https://github.com/goregargi/realtime-market-data-pipeline"><img src="https://raw.githubusercontent.com/goregargi/realtime-market-data-pipeline/main/docs/dashboard.png" width="100%" alt="Real-time market data dashboard"/></a>

Ingestion: Python producer streams BTC, ETH and SOL trades into Kafka, with dead-letter routing for bad messages
Processing: 1-minute OHLCV candles and VWAP using event-time windows and watermarks for late data
Reliability: idempotent upserts and checkpointing, so the pipeline is safe to restart and replay
Observability: data freshness, throughput and late-record counts on the same dashboard

Kafka Spark Structured Streaming TimescaleDB Grafana Docker GitHub Actions

👉 View the project

🏦 SEC Financials Lakehouse

Batch · In progress

A batch lakehouse built on SEC EDGAR filings for thousands of US public companies. Raw XBRL financial data moves through bronze, silver and gold Delta Lake layers, dbt models company fundamentals (revenue, margins, growth), and Airflow runs it incrementally every day.

Airflow PySpark Delta Lake dbt AWS S3

🚧 Coming soon

Tech Stack

Languages & Data

<p> <img src="https://skillicons.dev/icons?i=python,postgres,mongodb,mysql&theme=dark" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black" /> <img src="https://img.shields.io/badge/Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black" /> <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" /> </p>

Cloud, Infra & CI/CD

<p> <img src="https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,jenkins,githubactions,gitlab,linux&theme=dark" /> </p>

APIs & Web

<p> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" /> <img src="https://img.shields.io/badge/REST%20APIs-009688?style=flat-square" /> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" /> </p>

AI/ML

<p> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/LLaMA-0467DF?style=flat-square&logo=meta&logoColor=white" /> <img src="https://img.shields.io/badge/RAG-8A2BE2?style=flat-square" /> </p>
Experience Highlights

Dell Technologies, Software Engineer 2 · 2021 to 2026

Built and maintained 50+ Python automation scripts for distributed storage platforms, cutting execution time by 60% through scheduled nightly and per-release runs
Designed automated workflows across REST APIs, Kubernetes and containerized infrastructure, integrated into Jenkins CI/CD
Developed AI-driven automation agents (LLaMA, LangChain, RAG) that increased throughput and reduced manual effort

Hackathon Awards (AI category)

Year	Project
2026	Multi-agent AI orchestration framework for end-to-end automation
2025	RAG-based AI automation framework
2023	AI automated summarization model (Best Innovative Idea)
GitHub Activity
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=goregargi&show_icons=true&hide_border=true&theme=github_dark&count_private=true" height="160"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=goregargi&layout=compact&hide_border=true&theme=github_dark" height="160"/> </p>
Education
MS, Data Science and Engineering, The City College of New York · 2026 to 2027
M.Tech, CSE & Big Data Analytics, Vellore Institute of Technology · 2022 · GPA 8.63/10
<p align="center"><i>Always happy to talk about data pipelines, distributed systems, or where the two meet.</i></p> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=90&section=footer" width="100%"/>
