<!-- ============================================================ -->
<!-- VARIANT 04 — HYBRID (Data-viz + Terminal headers)            -->
<!-- ============================================================ -->

<h1>Avik Mandal &nbsp;<sub><sub>// Data Engineer → Data + AI Engineer</sub></sub></h1>

<sub>Bangalore, India &nbsp;•&nbsp; Shipping data platforms since 2012 &nbsp;•&nbsp; Building with AI, building for AI</sub>

<p>
  <a href="https://www.linkedin.com/in/avikmandal/">
    <img src="https://img.shields.io/badge/-Connect%20on%20LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=avikbesu&style=flat&color=8957E5&label=profile+views"/>
</p>

---

### `~/flow` &nbsp;<sub>how the work flows</sub>

```mermaid
flowchart LR
    A[("SOURCES<br/>Kafka · APIs · S3")]
    B["INGEST<br/>Flink · Spark · Glue"]
    C["ORCHESTRATE<br/>Airflow 3.x · MWAA"]
    D[("LAKE<br/>Iceberg · S3 · MinIO")]
    E["QUERY<br/>Trino · Athena · DuckDB"]
    F(["AI LAYER<br/>LLM tooling · RAG · Bedrock"])
    G[["PRODUCTS<br/>dashboards · features · agents"]]

    A --> B --> C --> D --> E --> G
    D -.-> F -.-> G
    C -.-> F

    classDef ai fill:#2D1B4E,stroke:#8957E5,stroke-width:2px,color:#E6EDF3;
    classDef core fill:#161B22,stroke:#30363D,color:#E6EDF3;
    class F,G ai;
    class A,B,C,D,E core;
```

<sub><i>The solid path is where I've lived for a decade. The dotted path is where I'm building next.</i></sub>

---
### `~/focus` &nbsp;<sub>right now</sub>

<table>
<tr><td><b>Platform work</b></td><td>Airflow 3.x · Kubernetes · Iceberg + Trino lakehouse patterns</td></tr>
<tr><td><b>AWS</b></td><td>MWAA · EMR · Glue · Athena · S3 · Lambda · ECS</td></tr>
<tr><td><b>AI in the loop</b></td><td>Using AI across the dev cycle — design, code, review, docs</td></tr>
<tr><td><b>AI in the product</b></td><td>Shipping features where AI measurably improves UX</td></tr>
<tr><td><b>Learning</b></td><td>AWS Data Engineer cert · Go for backend services · model serving</td></tr>
</table>

---

### `~/projects` &nbsp;<sub>pinned</sub>

<table>
<tr>
<td width="50%" valign="top">
<strong><a href="https://github.com/avikbesu/local-infra-setup">local-infra-setup</a></strong><br/>
<sub>Local dev infra with all services wired together.</sub><br/>
<sub><code>Shell</code> · <code>Docker</code> · <code>Makefile</code></sub>
</td>
<td width="50%" valign="top">
<strong><a href="https://github.com/avikbesu/airflow3-dags">airflow3-dags</a></strong><br/>
<sub>Production-style DAG patterns exploring Airflow 3.x.</sub><br/>
<sub><code>Python</code> · <code>Airflow 3.x</code></sub>
</td>
</tr>
</table>

---

### `~/stack` &nbsp;<sub>by layer</sub>

<table>
<tr><td><sub><b>ORCHESTRATION</b></sub></td><td>
<img src="https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Flink-E6526F?style=flat&logo=apacheflink&logoColor=white"/>
</td></tr>
<tr><td><sub><b>AWS</b></sub></td><td>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/MWAA-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/EMR-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Glue-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Athena-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white"/>
<img src="https://img.shields.io/badge/Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white"/>
</td></tr>
<tr><td><sub><b>INFRA</b></sub></td><td>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white"/>
</td></tr>
<tr><td><sub><b>LANGUAGES</b></sub></td><td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/Scala-DC322F?style=flat&logo=scala&logoColor=white"/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white"/>
</td></tr>
<tr><td><sub><b>DATA</b></sub></td><td>
<img src="https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Cassandra-1287B1?style=flat&logo=apachecassandra&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Iceberg-1E6FEB?style=flat&logo=apacheiceberg&logoColor=white"/>
<img src="https://img.shields.io/badge/Trino-DD00A1?style=flat&logo=trino&logoColor=white"/>
</td></tr>
<tr><td><sub><b>AI / ML</b></sub></td><td>
<sub>upskilling →</sub>
<img src="https://img.shields.io/badge/LLM%20tooling-8957E5?style=flat"/>
<img src="https://img.shields.io/badge/RAG-8957E5?style=flat"/>
<img src="https://img.shields.io/badge/Model%20serving-8957E5?style=flat"/>
<img src="https://img.shields.io/badge/Bedrock-8957E5?style=flat"/>
</td></tr>
</table>

---

### `~/stats` &nbsp;<sub>github signal</sub>

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=avikbesu&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=8957E5&icon_color=8957E5" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=avikbesu&theme=github-dark-blue&hide_border=true&background=0D1117&ring=8957E5&fire=8957E5&currStreakLabel=8957E5" height="160"/>
</p>

---

### `~/talks` &nbsp;<sub>speaking & open source</sub>

<table>
<tr>
<td width="33%" valign="top">
<h4>🎤 Speaking</h4>
<sub><b>Airflow DAG patterns at scale</b></sub><br/>
<sub>Internal tech talks — production-grade orchestration, failure modes, observability.</sub>
<br/><br/>
<sub><b>Data platform case studies</b></sub><br/>
<sub>Lakehouse architecture, cost/perf trade-offs. Available on request.</sub>
<br/><br/>
<sub><a href="https://www.linkedin.com/in/avikmandal/">→ Invite me to speak</a></sub>
</td>
<td width="33%" valign="top">
<h4>🌱 Open Source</h4>
<sub><b>Airflow community</b></sub><br/>
<sub>Contributing around Airflow 3.x patterns, providers, and dev ergonomics.</sub>
<br/><br/>
<sub><b>Local-dev tooling</b></sub><br/>
<sub><a href="https://github.com/avikbesu/local-infra-setup">local-infra-setup</a> — batteries-included dev stack.</sub>
<br/><br/>
<sub><a href="https://github.com/avikbesu?tab=repositories">→ All repositories</a></sub>
</td>
<td width="33%" valign="top">
<h4>✍️ Writing</h4>
<sub><b>Production DAG patterns</b></sub><br/>
<sub>Notes on idempotency, backfills, and observability in Airflow.</sub>
<br/><br/>
<sub><b>AI-augmented engineering</b></sub><br/>
<sub>What actually moves the needle in the daily dev loop.</sub>
<br/><br/>
<sub><a href="https://www.linkedin.com/in/avikmandal/">→ Posts on LinkedIn</a></sub>
</td>
</tr>
</table>

---

### `~/ask-me-about`

`Apache Airflow` &nbsp;·&nbsp; `Data pipeline design` &nbsp;·&nbsp; `Kubernetes for data` &nbsp;·&nbsp; `Data lake architecture` &nbsp;·&nbsp; `AWS data stack` &nbsp;·&nbsp; `AI-augmented development` &nbsp;·&nbsp; `Shipping AI features in data products`
