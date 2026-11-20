<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=170&section=header&text=Gargi%20Gore&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Data%20Engineer%20%7C%20Scalable%20pipelines%20on%20distributed%20systems&descSize=16&descAlignY=58" width="100%"/> <p align="center"> <a href="https://www.linkedin.com/in/gargi-gore"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> <a href="mailto:goregargi25@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a> <img src="https://img.shields.io/badge/New%20York%2C%20NY-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white"/> <img src="https://img.shields.io/badge/Open%20to-Data%20Engineering%20roles-2ea44f?style=for-the-badge"/> </p>
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
Featured Projects
<table> <tr> <td width="50%" valign="top">
📈 realtime-market-data-pipeline

Streaming pipeline that ingests live crypto trade data from exchange WebSockets, processes it with Spark Structured Streaming, and computes real-time metrics such as VWAP, volatility and volume spikes. Handles late and malformed events with watermarking and a dead-letter queue, and serves results to a live Grafana dashboard.

Kafka Spark Structured Streaming TimescaleDB Grafana Docker

</td> <td width="50%" valign="top">
🏦 sec-financials-lakehouse

Batch lakehouse built on SEC EDGAR filings for thousands of US public companies. Ingests raw XBRL financial data into bronze, silver and gold Delta Lake layers, models company fundamentals (revenue, margins, growth) with dbt, and runs incrementally on a daily Airflow schedule.

Airflow PySpark Delta Lake dbt AWS S3

</td> </tr> </table>

<sub>🚧 Actively building. Each repo includes an architecture diagram, one-command setup and performance results.</sub>

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
