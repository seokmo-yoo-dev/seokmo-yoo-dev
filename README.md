## Seokmo Yoo

AI Engineer at NAVER, building real-time recommendation systems for live streaming.
Previously a backend engineer at NAVER Financial.

### Experience

**AI Engineer** · NAVER · Jul 2024 – Present

Live streaming recommendation system

- Personalized live streaming recommendation to grow MAU and watch time
- Real-time transcripts of live video with ASR, then LLM summaries and embeddings
- Personalized interest keywords extracted with LLMs
- Real-time log streaming at 300k+ TPS with Flink, Kafka and Iceberg
- LLM serving and optimization with KServe, vLLM and SGLang

**Backend Engineer** · NAVER Financial · Dec 2020 – Jul 2024

Financial backend services

- Credit and mortgage loan comparison service on a Kubernetes-based MSA
- Insurance claim service on an asynchronous architecture
- Personalized ads from aggregated payment events with Kafka and Hive

### Open Source

**Apache Kafka**

- Merged: [#24007](https://github.com/apache/kafka/pull/24007) Replace try/fail/catch with assertThrows in SASL client tests
- In review: [#23393](https://github.com/apache/kafka/pull/23393) KAFKA-21043, do not share `LoginManager` across class loaders
- In review: [#23394](https://github.com/apache/kafka/pull/23394) KAFKA-14102, create the OAUTHBEARER `SaslClient` from the local factory

The two fixes in review come from running Kafka clients with SASL/OAUTHBEARER in Flink session clusters, where each job has its own class loader.

### Skills

| Area | |
|---|---|
| AI / ML | LLM serving (vLLM, SGLang, KServe), ASR, embeddings, recommender systems |
| Streaming / Data | Kafka, Flink, Iceberg, Hive |
| Backend | Kotlin, Java, TypeScript, Spring, Node.js |
| Infra | Kubernetes, Docker, Prometheus, Grafana, Kerberos |
| Storage | MySQL, MongoDB, Aerospike, Elasticsearch |

### Links

- Blog: https://trouvaillle.github.io/
