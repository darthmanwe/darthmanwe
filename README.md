<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,100:113A8F&height=230&section=header&text=Kutlu%20Mizrak&fontSize=48&fontColor=EAF2FF&animation=fadeIn&fontAlignY=38&desc=Senior%20Applied%20ML%20Engineer%20%7C%20GenAI%20%7C%20MLOps&descAlignY=60&descAlign=50" alt="header" />
</p>

<p align="center">
  <img src="https://avatars.githubusercontent.com/darthmanwe?v=4" width="140" alt="Kutlu Mizrak headshot" style="border-radius: 50%;" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kutlu-mizrak/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:kutlumizrak@gmail.com"><img src="https://img.shields.io/badge/Email-1A73E8?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://darthmanwe.github.io/"><img src="https://img.shields.io/badge/Portfolio-0D47A1?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
</p>

## Executive Snapshot

Senior Applied ML and GenAI engineer focused on measurable business outcomes. I build production AI systems that improve reliability, reduce operational risk, and accelerate delivery from prototype to stable release.

### Impact Highlights

- **99.9% uptime** supporting **100k+ daily API requests** in production.
- **230% pipeline acceleration** via workflow hardening and worker automation.
- **35% entity extraction F1 improvement** in custom NER and JSON extraction systems.
- **98.7% OCR accuracy** across **5M+ lines** of low-quality legacy artifacts.
- **99.8% CI/CD reliability** across 20+ AI automation releases.

## Featured Projects

### 1) lorekeeper
LKGE (Lorekeeper Graph Engine): agentic story generation with Neo4j knowledge graphs, dual RAG retrieval, and contradiction guardrails.

- **61% fewer contradictions** in paired evaluation versus rolling-context baseline
- Graph memory and pre-generation guardrails to preserve narrative consistency at scale
- Production-ready stack design with FastAPI, Streamlit, LangGraph, ChromaDB, and OpenTelemetry

**Repo:** <https://github.com/darthmanwe/lorekeeper>

### 2) Medical_Doc_Knowledge_Graph_System
Neo4j + FastAPI graph-backed retrieval and grounded RAG for medical documents.

- 5-stage Cypher retrieval pipeline with semantic reranking
- Sub-200 ms retrieval target
- Focus on provenance, explainability, and contradiction reduction

**Repo:** <https://github.com/darthmanwe/Medical_Doc_Knowledge_Graph_System>

### 3) Training_Distributed_Systems
Fault-tolerant distributed RL platform using Ray + PyTorch PPO.

- Asynchronous rollout collection across heterogeneous workers
- Heartbeat-based health monitoring
- Automatic worker replacement for resilience

**Repo:** <https://github.com/darthmanwe/Training_Distributed_Systems>

### 4) PDF_to_Presentation
Document automation pipeline for converting instructional PDFs into structured, reusable presentation output.

**Repo:** <https://github.com/darthmanwe/PDF_to_Presentation>

### 5) Work_Sample
Representative applied data science and ML implementation samples.

**Repo:** <https://github.com/darthmanwe/Work_Sample>

### 6) Beats_MCP
Prototype MCP-focused project with LEPOR evaluation concepts for AI workflow experimentation.

**Repo:** <https://github.com/darthmanwe/Beats_MCP>

## Core Technical Stack

- **Core Languages:** Python, SQL, JavaScript, TypeScript, Java, C#/.NET, C++, Go, COBOL, Bash, PowerShell, Jupyter, YAML, JSON

- **Backend / API Engineering:** FastAPI, Flask, REST APIs, GraphQL, OpenAPI/Swagger, Pydantic, SQLAlchemy, Alembic, Uvicorn, Gunicorn, Celery, Redis/RQ, async Python, microservices, webhooks, API validation, schema validation, retries, rate limiting, idempotent job design

- **LLM / Agentic AI:** OpenAI API, Anthropic Claude API, Gemini API, Hugging Face Transformers, LangChain, LangGraph, LlamaIndex, AutoGen, CrewAI concepts, tool calling, function calling, structured JSON outputs, schema-constrained generation, Pydantic parsers, prompt templates, prompt versioning, JSON repair, model fallback logic, agent state machines

- **RAG / GraphRAG / Knowledge Graphs:** Neo4j, Neo4j Python Driver, Cypher, APOC, Neo4j Graph Data Science concepts, GraphRAG, property graphs, ontology/schema design, entity resolution, entity linking, relationship extraction, graph traversal, k-hop expansion, shortest-path reasoning, vector-seeded graph retrieval, semantic reranking, provenance linking, source citation workflows, Cypher optimization, graph indexes

- **Vector / Search Systems:** Supabase Vector, pgvector, ChromaDB, FAISS, Pinecone concepts, Weaviate concepts, Elasticsearch, OpenSearch, BM25, dense embeddings, sparse retrieval, hybrid search, metadata filtering, document chunking, recursive splitters, semantic chunking, cross-encoder rerankers, sentence-transformers, OpenAI embeddings, retrieval evaluation, top-k/MMR tuning

- **Data Engineering:** PostgreSQL, Supabase, BigQuery, Databricks, Snowflake, Unity Catalog concepts, MongoDB, SQLite, Redis, S3, Azure Blob Storage, GCS concepts, Pandas, NumPy, PySpark concepts, Airflow concepts, dbt concepts, ETL/ELT, batch ingestion, document ingestion, JSON normalization, data validation, deduplication, canonical entity modeling, Great Expectations concepts

- **ML / NLP / Document AI:** PyTorch, JAX, scikit-learn, Hugging Face, Transformers, sentence-transformers, spaCy, NER, entity extraction, relation extraction, text classification, semantic similarity, clustering, OCR post-processing, OpenCV, Tesseract concepts, PDFPlumber, PyMuPDF, pypdf, layout-aware extraction, table extraction, human-in-the-loop QA

- **MLOps / LLMOps / Model Serving:** MLflow, Weights & Biases, DVC concepts, LangSmith concepts, RAGAS concepts, DeepEval concepts, BentoML, ONNX Runtime, TorchServe concepts, SageMaker endpoints, Vertex AI endpoints, FastAPI inference services, Dockerized model serving, Kubernetes-hosted inference, batch/real-time inference, artifact versioning, prompt tracking, model registry concepts, rollback patterns, drift checks, latency/cost/output-quality monitoring

- **Cloud / Infrastructure:** AWS, Azure, GCP, Azure ML Studio, Azure Databricks, Azure GovCloud, Amazon EKS, SageMaker, Vertex AI, AWS Lambda, Azure Functions concepts, Kubernetes, Docker, Docker Compose, Terraform, Azure DevOps, GitHub Actions, VMWare, Linux, IAM/RBAC, VPC/VNet concepts, load balancers, autoscaling, hybrid deployment, on-prem/air-gapped deployment awareness

- **Observability / Reliability / QA:** OpenTelemetry, Prometheus, Grafana, Loki concepts, ELK/Elastic Stack, Datadog concepts, Sentry concepts, CloudWatch, Azure Monitor, structured JSON logs, trace IDs, request IDs, API health checks, Kubernetes readiness/liveness probes, worker health checks, queue depth monitoring, RCA workflows, release safety, rollback planning, SLO/SLA concepts, pytest, unittest, mypy, ruff, black, pre-commit, regression suites, schema tests, data contract tests, golden-set evaluation

- **Security / Governance / LLM Safety:** OAuth2 concepts, JWT, OIDC concepts, Azure Key Vault, AWS Secrets Manager, KMS concepts, TLS/HTTPS, encryption-in-transit/at-rest, audit logging, data lineage, source provenance, reproducible pipelines, deterministic validation, explainability tooling, model cards, Fortify SCA, Snyk concepts, Trivy concepts, zero-trust concepts, GovCloud constraints, OWASP LLM Top 10, prompt injection mitigation, retrieval permission filters, PII-aware processing, model supply-chain risk awareness, data poisoning awareness, model DoS/cost controls, NeMo Guardrails concepts, Guardrails AI concepts

- **L3 Technical Support / ML Escalation:** L3 escalation ownership, complex production triage, customer issue reproduction, severity classification, SLA/SLO tracking, incident timelines, RCA docs, 8D reporting, support runbooks, KB ownership, ticket QA, junior support mentoring, customer-facing technical summaries, ML-team escalation handoffs, engineering defect packages, Jira, GitHub Issues, Azure DevOps Boards, Confluence, Notion, Slack, Microsoft Teams, Postman, Insomnia, Swagger/OpenAPI, cURL, SQL debugging, PostgreSQL inspection, Neo4j Browser, Cypher debugging, APOC checks, Elasticsearch/OpenSearch debugging, Supabase dashboard, BigQuery console, Databricks notebooks, Docker logs, Kubernetes logs, kubectl, RAG/GraphRAG validation, hallucination investigation, retrieval failure debugging, ingestion failure triage, schema/RBAC debugging

- **Analytics / Delivery:** PowerBI, SQL analytics, BigQuery analytics, dashboarding, KPI design, operational reporting, stakeholder-facing metrics, root cause reporting, OSINT pipeline automation, Git, GitHub, Trello, Jira, Notion, Confluence, Markdown docs, Mermaid diagrams, technical design docs, architecture notes, release notes

- **Certifications:** AWS Certified Machine Learning Specialty, Google Cloud Professional Machine Learning Engineer, Microsoft Azure AI Engineer Associate

## Certifications

- AWS Certified Machine Learning - Specialty
- Google Cloud Machine Learning Engineer
- Azure AI Engineer Associate

<!-- PROFILE_TOGGLE_SHOW_GITHUB_SNAPSHOT=false -->
<!-- To re-enable later: set toggle to true and uncomment block below. -->
<!--
## GitHub Snapshot

<p align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=darthmanwe&theme=github_dark" alt="GitHub stats" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=darthmanwe&theme=github_dark" alt="Top languages by repository" />
</p>
-->

---

## Contact

If you are hiring for senior AI/ML roles (GenAI, NLP/OCR, MLOps, production platforms), I am open to discussing high-impact opportunities.

- LinkedIn: <https://www.linkedin.com/in/kutlu-mizrak/>
- Email: <mailto:kutlumizrak@gmail.com>
