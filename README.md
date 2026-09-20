<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=23&duration=3200&pause=900&color=FF4F38&center=true&vCenter=true&width=780&height=45&lines=Distributed+Data+Platform+%40+HPE;Spark+%E2%80%A2+Kafka+%E2%80%A2+Debezium+%E2%80%A2+Trino+%E2%80%A2+1%2B+TB%2Fday;Apache+Spark+%26+PyDeequ+contributor;Building+a+database+from+scratch%2C+to+find+out+how" alt="Anmol Mishra" />

### Anmol Mishra

**Software Engineer — Distributed Data Platform**  ·  Bangalore, India

[![Portfolio](https://img.shields.io/badge/Portfolio-amc--hawk.github.io-FF4F38?style=flat-square&logo=githubpages&logoColor=white)](https://amc-hawk.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anmol--mishra-0A66C2?style=flat-square)](https://www.linkedin.com/in/anmol-mishra-92ab67188/)
[![Email](https://img.shields.io/badge/Email-anmol99993%40gmail.com-1a1a1a?style=flat-square&logo=gmail&logoColor=white)](mailto:anmol99993@gmail.com)

</div>

---

## What I actually do

I care about what happens to data **before** anyone models it.

Most of the interesting failures in a data platform don't happen in the model — they happen
three systems upstream, in a schema nobody owned, in a CDC stream that silently dropped a
column, in a join that was fine until the partition skewed. That's the layer I work at.

At **Hewlett Packard Enterprise** I design and operate the batch and streaming pipelines
behind the Distributed Data Platform:

<img src="pipeline.svg" alt="Postgres to Debezium CDC to Kafka to Spark to Iceberg to Trino to 15+ BI models" width="100%">

| | |
|---|---|
| **1+ TB / day** | processed across batch and streaming pipelines |
| **15+ BI data models** | delivered for Customer Success, FinOps and Engineering |
| **95%+** | production incident SLA compliance |

---

## Open source

| Project | Contribution | Status |
|---|---|---|
| **[Apache Spark](https://github.com/apache/spark/pull/58760)** | `SPARK-59146` — retain qualified access to source columns affected by pipe `SET`, with planner changes and SQL test coverage | open |
| **[AWS PyDeequ](https://github.com/awslabs/python-deequ/pull/289)** | DQDL support via `EvaluateDataQuality`, with tests and documentation | **merged** |

---

## Building

**RaftDB** — a mini distributed database, written from scratch because I didn't want
consensus, recovery and query optimization to stay black boxes.
Raft consensus, leader election, log replication, WAL, snapshots, SSTables, Bloom filters
and background compaction — with a cost-based SQL layer on Apache Calcite over the top.
`Java` · `Raft` · `LSM Tree` · `RocksDB` · `Apache Calcite`

**Data quality research** — working toward a cloud-native data quality framework for
open-source datasets: validation systems, error detection, label noise and LLM-driven
cleaning.

Public experiments →
[AIOps Platform](https://github.com/AMC-hawk/AIOps-Platform-POC) ·
[JanusGraph](https://github.com/AMC-hawk/JanusGraph-POC) ·
[Airflow + Spark](https://github.com/AMC-hawk/Airflow-Spark-Setup) ·
[MCP Server](https://github.com/AMC-hawk/MCP_Server_LocalSetup) ·
[MLflow](https://github.com/AMC-hawk/ML_Flow_Setup) ·
[Scala REST API](https://github.com/AMC-hawk/scala-rest-api)

---

## Stack

**Data**
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache%20Iceberg-1B1B1B?style=flat-square)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Platform**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

---

<div align="center">

**B.Tech Computer Science & Engineering**, Vellore Institute of Technology · 8.81 / 10

Interested in distributed systems, database internals, performance engineering
and AI-powered data platforms.

**[amc-hawk.github.io](https://amc-hawk.github.io)**

</div>
