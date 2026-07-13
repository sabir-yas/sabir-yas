<div align="center">

<img src="./banner.svg" alt="Yaseer Sabir — software engineering, distributed systems, and artificial intelligence" width="100%" />

</div>

<p align="center">
  <a href="https://www.linkedin.com/in/yaseer-sabir-0a24b4200/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect with Yaseer Sabir on LinkedIn" />
  </a>
  <a href="mailto:yaseersabir005@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Yaseer Sabir" />
  </a>
</p>

---

## About Me

* 🎓 B.S. in Computer Science, Honors Scholars Program — University of Colorado Denver
* 🤖 AI Fellow at **Colorado Thrives**, building agentic AI pipelines for a workforce network serving more than 120,000 stakeholders
* 🧠 Former Machine Learning Research Intern at **CU Anschutz Medical Campus**, where I developed high-throughput pipelines for spatial transcriptomics research
* 🛠️ Interested in distributed systems, backend infrastructure, data engineering, and AI agent architectures
* 📫 Reach me through [email](mailto:yaseersabir005@gmail.com) or [LinkedIn](https://www.linkedin.com/in/yaseer-sabir-0a24b4200/)

---

## Tech Stack

### Languages

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

### Backend, Web, and Machine Learning

<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
</p>

### Cloud, Infrastructure, and Distributed Systems

<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Amazon Web Services" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white" alt="Ray" />
  <img src="https://img.shields.io/badge/SLURM-024270?style=flat-square" alt="SLURM" />
</p>

### Data Engineering and Observability

<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Apache Airflow" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
</p>

---

## Featured Projects

### SpatiaScale — Cloud-Native Distributed Query Engine

`AWS EKS` · `Amazon S3` · `ElastiCache` · `gRPC` · `Apache Arrow`

* Built a fault-tolerant spatial query engine on AWS EKS for indexing more than **148 million multidimensional points** derived from over **500 million raw rows** in Amazon S3.
* Achieved **7.77 ms p99 query latency** during testing on live EKS traffic.
* Reduced memory usage by **76%** through quadtree-based spatial partitioning and ElastiCache-backed caching.
* Improved deserialization performance by **11.3×** using a gRPC and Apache Arrow data-transfer layer.

### AI Drug Discovery Swarm

`Ray` · `Redis Streams` · `RDKit` · `AutoDock Vina` · `FHIR R4`

* Built a distributed multi-agent system that generates and ranks candidate molecular structures through evolutionary search and computational scoring.
* Designed explorer, chemist, property-screening, and selector agents that coordinate through Redis Streams.
* Evaluated candidates using predicted binding affinity, molecular properties, and synthetic accessibility metrics.
* Developed a FHIR R4-compatible Agent-to-Agent endpoint that maps gene variants to potential drug targets and returns ranked candidates in a structured FHIR bundle.
* Validated the system with **92 integration tests**.
* Placed **3rd out of 39 teams** at Lynx Hack 2026.

### Distributed Machine Learning Inference Pipeline

`FastAPI` · `Apache Kafka` · `Redis` · `Docker` · `PyTorch`

* Built a fault-tolerant distributed inference system using PyTorch ResNet-50.
* Load-tested the system at more than **10,000 simulated requests per second** across concurrent clients.
* Used Kafka-partitioned work queues to distribute inference workloads across workers.
* Reduced response latency by **85%** compared with the initial pipeline design.
* Added Redis-backed result caching and Docker-based service isolation.

### Trivia Wizards — Real-Time Multi-Interface Trivia Platform

`Next.js` · `Prisma` · `Supabase` · `PostgreSQL` · `Socket.IO`

* Built a full-stack trivia platform with three synchronized interfaces: host controls, player kiosks, and a shared display.
* Implemented real-time game-state synchronization using Socket.IO with WebSocket-only transport.
* Eliminated polling overhead to provide low-latency updates across every connected interface.
* Used Prisma and Supabase PostgreSQL for persistent game, question, and session data.

### ETL Pipeline — dbt, Snowflake, and Airflow

`dbt` · `Snowflake` · `Apache Airflow` · `Astronomer Cosmos`

* Built an end-to-end ELT pipeline for transforming raw TPC-H data in Snowflake.
* Organized transformations using a layered **staging → intermediate → mart** architecture in dbt.
* Orchestrated dbt models as native Airflow tasks through Astronomer Cosmos.
* Scheduled daily pipeline runs with dependency-aware task execution.
* Added source-level and mart-level data quality tests throughout the transformation workflow.

### LEGv8 Pipelined CPU Simulator

`Python` · `Computer Architecture` · `Pipeline Simulation`

* Built a cycle-accurate simulator for a five-stage pipelined LEGv8 processor.
* Implemented data forwarding, load-use stalls, control-hazard detection, and branch flushing.
* Added a toggleable forwarding unit for direct performance comparisons across hazard scenarios.
* Measured pipeline speedups of up to approximately **2.09×**, depending on instruction dependencies and hazard frequency.

---
