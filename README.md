<div align="center">

<img src="./banner.svg" alt="Yaseer Sabir banner" width="100%" />

</div>

<p align="center">
  <a href="https://www.linkedin.com/in/yaseer-sabir-0a24b4200/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:yaseersabir005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### About Me

- 🎓 B.S. Computer Science, Honors Scholars Program @ University of Colorado Denver
- 🤖 AI Fellow @ **Colorado Thrives** — building agentic AI pipelines for a 120,000+-stakeholder workforce network
- 🧠 Former ML Research Intern @ **CU Anschutz Medical Campus** — high-throughput pipelines for spatial transcriptomics research
- 🛠️ I like building distributed systems, backend infrastructure, and AI agent architectures
- 📫 Reach me at yaseersabir005@gmail.com

---

### Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/SLURM-024270?style=flat-square" />
</p>

---

### Featured Projects

**SpatiaScale — Cloud-Native Distributed Query Engine**
Fault-tolerant spatial query engine on AWS EKS indexing 148M+ multi-dimensional points (500M+ raw rows) in S3 with sub-10ms p99 latency (7.77ms measured on live EKS traffic). Quadtree partitioning + ElastiCache cut memory usage 76%; gRPC/Apache Arrow layer delivered an 11.3x deserialization speedup.

**AI Drug Discovery Swarm**
Distributed multi-agent system on Ray that autonomously evolves drug candidate molecules via evolutionary AI — explorer, chemist, safety, and selector agents coordinate over Redis Streams, scoring binding affinity (RDKit/AutoDock Vina) and synthetic accessibility in real time. Ships a FHIR R4-compliant Agent-to-Agent endpoint that resolves drug targets from gene variants and returns ranked candidates as a FHIR MedicationRequest bundle, validated by 92 integration tests. Placed 3rd/39 teams at Lynx Hack 2026.

**Distributed ML Inference Pipeline**
Fault-tolerant distributed inference system handling 10,000+ simulated concurrent requests/sec with FastAPI, Kafka, Redis, Docker, and PyTorch ResNet-50. Kafka-partitioned queues cut response latency by 85%.

**Trivia Wizards — Real-Time Multi-Interface Trivia Platform**
Full-stack real-time trivia app with three synchronized interfaces (host, kiosk, TV display) built on Next.js, Prisma, Supabase Postgres, and Socket.io. Forces WebSocket-only transport to eliminate polling lag for instant gameplay.

**ETL Pipeline — dbt + Snowflake + Airflow**
End-to-end ELT pipeline transforming raw TPC-H data through a layered staging → intermediate → mart architecture in dbt, orchestrated as native Airflow tasks via Astronomer Cosmos on a daily schedule, with source and mart-level data quality tests throughout.

**LEGv8 Pipeline CPU Simulator**
Cycle-accurate simulation of a 5-stage pipelined LEGv8 CPU in Python, with full hazard handling — data forwarding, load-use stalls, and branch flushes — plus a toggleable forwarding unit to directly compare pipeline speedup (up to ~2.09x) across hazard scenarios.

---
