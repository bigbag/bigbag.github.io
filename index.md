# Pavel Liashkov

Senior Backend Engineer | Python Expert | AI/ML Engineer

- [LinkedIn](https://www.linkedin.com/in/liashkov/)
- [GitHub](https://github.com/bigbag)
- [Kaggle](https://www.kaggle.com/bigbag1983) (Competitions Expert, top 3%)
- [Credly](https://www.credly.com/users/pavel-liashkov/badges#credly)
- [LeetCode](https://leetcode.com/u/bigbag/)

---

## Summary

Senior Backend Engineer with 12+ years building production Python systems on AWS and Kubernetes. I ship multi-agent LLM pipelines, RAG systems, and microservices that process 200M+ records/day. Day-to-day stack: FastAPI, PostgreSQL, Redis, Docker, CI/CD. Open-source contributor with 2.4M+ total PyPI downloads (220K+ monthly). Currently focused on agentic AI workflows, prompt engineering, and MLOps.

---

## Technical Skills

### Languages & Expertise
- **Python** (12+ years): FastAPI, Starlette, Django, Flask, asyncio, async/await patterns
- **Golang** (6+ years): Microservices, concurrent systems
- **Protocols**: gRPC, REST, GraphQL, Protocol Buffers, MCP (Model Context Protocol), AG-UI

### AI/ML & Data Science
- **LLM Integration**: PydanticAI, OpenAI GPT, Anthropic Claude, prompt engineering, function calling
- **Agentic Systems**: Multi-agent pipelines, MCP tool servers, agentic workflows, LLM evaluation
- **ML Frameworks**: PyTorch, Sentence-Transformers, BERT, KeyBERT
- **Optimization**: ONNX Runtime (INT8/AVX512 quantization), CPU-optimized inference
- **RAG Systems**: Vector embeddings, semantic search, pgvector, DuckDB VSS, hybrid search (HNSW + BM25)
- **NLP**: NLTK, language detection, multilingual models

### Databases & Storage
- **SQL**: PostgreSQL (including pgvector), MySQL, ClickHouse
- **NoSQL/Cache**: Redis
- **Data Warehouses**: Snowflake, StarRocks (OLAP), BigQuery
- **Vector Databases**: pgvector, DuckDB with VSS extension

### Cloud & Infrastructure
- **AWS**: ECS, EC2, RDS, S3, CloudWatch, IAM, Bedrock
- **Orchestration**: Kubernetes (CKA certified), Docker, Helm, Werf
- **Workflow**: Apache Airflow (certified), Celery, RabbitMQ, streaq
- **CI/CD**: Jenkins, GitHub Actions, GitLab CI/CD, ArgoCD

### Observability & Monitoring
- **Metrics**: Prometheus, Grafana, custom exporters
- **Tracing**: LangSmith, Pydantic Logfire, distributed tracing
- **Logging**: Structured logging, request ID tracking
- **Error Tracking**: Sentry

### Security & Authentication
- **Secrets Management**: HashiCorp Vault, Kubernetes service accounts
- **Cryptography**: RSA/AES hybrid encryption, JWT tokens, JWS/JWE
- **Compliance**: PCI DSS, authentication/authorization systems

### Additional Technologies
- **Message Queues**: Kafka, RabbitMQ, Redis Streams
- **Browser Automation**: Playwright
- **API Integration**: Apple Search Ads, Google Cloud Platform, OpenAI, Anthropic
- **Data Processing**: Pandas, Polars, PyArrow

---

## Professional Experience

### Backend Engineer, SplitMetrics
*July 2022 – Present*

- Wrote the multi-agent LLM research system end-to-end: PydanticAI-based Planner → 20 Skill Agents → Finalizer, with parallel execution and AG-UI SSE streaming. Powers competitive intelligence across App Store data
- Deep Search pipeline: 4 autonomous agents, streaq Redis-backed task queue, fact-based convergence detection, user-in-the-loop plan approval. Reports degrade gracefully on partial failures
- 33-tool FastMCP server + RAG layer: PostgreSQL pgvector for semantic search, DuckDB VSS with ONNX-optimized embeddings. Query latency under 100ms (CPU-optimized INT8 quantization, hybrid HNSW + BM25)
- Ran Snowflake/StarRocks/Airflow data pipelines at 200M+ records/day, 99.9% uptime
- BERT + ONNX keyword analysis service: sub-second responses at 5K+ req/s
- Added offline LLM evaluation (deterministic checks, subjective judge, hybrid groundedness scoring) and a memory extraction service that catches hallucinated app KPIs before they persist
- AWS infrastructure (ECS, RDS, S3, Bedrock), Kubernetes, Jenkins CI/CD. Wired multi-provider LLM routing across OpenRouter, DeepSeek, Ollama, and OpenAI-compatible endpoints

### Senior Software Engineer, Exness
*August 2016 – April 2022*

- Architected payment processing platform (22+ microservices) with JWS multi-signature validation, state machine invoice lifecycle, and Kafka event-driven reconciliation across 50+ payment providers
- Integrated Bitcoin Core RPC and USDT-OMNI for crypto deposits/withdrawals with wallet management and blockchain confirmation tracking
- 400+ technical interviews conducted; hired 20+ engineers across backend and platform teams
- Implemented PCI DSS compliant authentication with HashiCorp Vault credential management and JWS cryptographic signing
- Built KYC verification rules engine integrating 12+ MetaTrader servers with SumSub and multi-database connectivity

### Software Engineer, Game Stream Joint LLC
*August 2014 – August 2016*

- Built microservice-based coupon system and led premium shop redesign, increasing user engagement and sales
- Developed APIs for external platform integration using Python, Django, PostgreSQL, and Redis

### Software Developer, Mobispot Social Systems
*October 2012 – August 2014*

- Led development of billing systems for payment terminals and vending machines using Python, Flask, and MySQL
- Created online shop for NFC tags and integrated social network features

---

## Open Source Contributions

### E-Paper Reader Projects
- [papyrix-reader](https://github.com/bigbag/papyrix-reader): Open-source firmware for Xteink X4/X3 e-paper readers on ESP32-C3 (~380KB RAM). Single binary auto-detects device via I²C scan. Reads EPUB 2/3, FB2, HTML, Markdown, TXT, and XTC/XTCH. Knuth-Plass line breaking (TeX-quality justified text), Liang-pattern hyphenation in 7 languages, Arabic shaping with RTL layout, Thai mark positioning, CJK text. Streaming font system with LRU cache (25KB vs 70KB full load), dual-boot memory optimization, Calibre wireless sync, WiFi file transfer. C++20 on PlatformIO/FreeRTOS. 380 stars
- [epub-to-xtc-converter](https://github.com/bigbag/epub-to-xtc-converter): Browser-based EPUB to XTC/XTCH converter with CREngine WASM rendering, batch processing, 42 languages, and Floyd-Steinberg dithering via Web Workers for e-ink display. 90 stars
- [papyrix-flasher](https://github.com/bigbag/papyrix-flasher): Cross-platform Go utility for flashing ESP32-C3 firmware with SLIP framing, zlib compression, and automatic device detection. 20 stars

### Popular Python Libraries (2.4M+ total downloads, 220K+ monthly)
- [starlette-request-id](https://github.com/bigbag/starlette-request-id): ASGI middleware for request tracing with automatic ID generation and context propagation across async operations. [120K downloads/month](https://clickpy.clickhouse.com/dashboard/starlette-request-id), 1.4M total
- [request-id-helper](https://github.com/bigbag/request-id-helper): Thread-safe request ID tracking with decorator-based integration and automatic injection for cross-service tracing. [100K downloads/month](https://clickpy.clickhouse.com/dashboard/request-id-helper), 970K total
- [starlette-i18n](https://github.com/bigbag/starlette-i18n): Internationalization middleware for Starlette with gettext/Babel integration and automatic locale detection

---

## Education

- **Master of Science in Information Technology (MSIT)**, University of the People (3.97 GPA) (2025)
- **Master's Degree in Theoretical Physics**, Kemerovo State University (2005)

---

## Certifications

- [**CKA: Certified Kubernetes Administrator**](https://www.credly.com/badges/24122208-e39b-4052-80fd-19f49ed1176b/public_url)
- [**Astronomer Certification for Apache Airflow 2 Fundamentals**](https://www.credly.com/badges/9148e9ff-f4a8-4028-a3d3-a34c0acdb77a)
- [**Professional Scrum Developer™ I (PSD I)**](https://www.credly.com/badges/f3c7117f-ac89-4160-919f-995082f365f5)
- [**Kaggle Competitions Expert**](https://www.kaggle.com/bigbag1983) — top 3% (rank 1,712 highest), 3 bronze medals in fraud detection, credit risk, and housing market prediction
- [**Machine Learning Engineer Nanodegree**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/udacity_ml.pdf) (Udacity)
- [**Go Developer Professional Training Course**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/yandex_golang.pdf) (Yandex)
- [**AI Agents Course Certificate**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/hf_agents_course_2025.pdf) (Hugging Face, 2025)
- [**OxML 2024**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/oxml_2024.pdf): Oxford Machine Learning Summer School — ML theory, Health & Bio, Representation Learning & Generative AI
- Coursera Specializations: [Generative AI for Software Development](https://www.coursera.org/account/accomplishments/professional-cert/BSV952W3S4QC), [Agentic AI and AI Agents for Leaders](https://www.coursera.org/account/accomplishments/specialization/G84HKWXVXANF), [Data Structures and Algorithms](https://coursera.org/verify/specialization/8NKLJFF5QKZW), [Self-Driving Cars](https://coursera.org/verify/specialization/EDTCKBT5H78J), [Project Management](https://www.coursera.org/account/accomplishments/specialization/OTHQOGV48PRK), [Python 3 Programming](https://coursera.org/verify/specialization/59EV37F9US56), [Algebra](https://coursera.org/verify/specialization/QDWV3BG7QAWM), [Rocket Science 101](https://www.coursera.org/account/accomplishments/specialization/E7D87UJMA0CC)

---

## Languages

- **English**: Professional working proficiency
- **Russian**: Native

---
