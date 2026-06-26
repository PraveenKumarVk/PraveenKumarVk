# Praveen Kumar Varkala

**AI/ML Engineer** — Production RAG · LLM Evaluation · Regulated Industries

I build AI systems for environments where mistakes are expensive: legal, healthcare, and finance. My focus is on making RAG and LLMs reliable enough to ship into high-stakes workflows — not just demo well.

---

## Featured Projects

### [ArxivAI](https://github.com/PraveenKumarVk/arxiv-ai) — Production RAG API
Search arXiv CS.AI papers with hybrid BM25 + semantic retrieval, live-updated via Airflow.

- **Retrieval:** OpenSearch 2.19 · Jina Embeddings v3 (1024-dim) · RRF fusion
- **Speed:** Redis cache delivering 150x speedup on repeated queries (<5ms hit)
- **Observability:** Full Langfuse tracing across every RAG span
- **Infra:** FastAPI · Docker Compose (10 services) · PostgreSQL 16 · Deployed on Render

🔗 **Live:** [arxiv-ai.onrender.com/docs](https://arxiv-ai.onrender.com/docs)

---

### [SOAP-Generator](https://github.com/PraveenKumarVk/SOAP-Generator) — Ambient Clinical Scribe
End-to-end clinical documentation: speech in, structured SOAP note out, with a full eval suite.

- **Pipeline:** WhisperX large-v2 ASR → pyannote 3.1 diarization → Claude SOAP generation
- **Eval:** Hallucination detection · medical NER (scispaCy) · PDQI-9 proxy scoring
- **Result:** 73% transcription latency reduction (185s → 50s) · HIPAA-aware design

🔗 **Live:** [HuggingFace Spaces](https://huggingface.co/spaces/pvarkala18/ambient-scribe)

---

## Stack

**AI / LLM**

![RAG](https://img.shields.io/badge/RAG-Production-4B8BBE?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA_Fine--tuning-FF6B35?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP_Explainability-8E44AD?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square)

**Infra & Cloud**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-praveenvarkala-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/praveenvarkala)
[![Portfolio](https://img.shields.io/badge/Portfolio-praveenvarkala.netlify.app-00C7B7?style=flat-square)](https://praveenvarkala.netlify.app)
[![Email](https://img.shields.io/badge/Email-reachpraveenvk@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:reachpraveenvk@gmail.com)
