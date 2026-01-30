# Pavel Liashkov

Backend Engineer | Python Expert | ML Enthusiast

- [LinkedIn](https://www.linkedin.com/in/liashkov/)
- [GitHub](https://github.com/bigbag)
- [Credly](https://www.credly.com/users/pavel-liashkov/badges#credly)
- [LeetCode](https://leetcode.com/u/bigbag/)

---

## About

Backend Engineer with 12+ years building scalable, production-grade systems specializing in AI/ML integration, microservices architecture, and high-performance data pipelines. Expert in Python with deep experience in LLM agents, RAG systems, and real-time analytics processing 200M+ records/day. Active open-source contributor with 2.4M+ total downloads (220K+ monthly) across multiple PyPI packages. Passionate about AI agent architectures, distributed systems, and MLOps.

---

## Professional Experience

### Backend Engineer, SplitMetrics
*July 2022 – Present*

- Developed conversational AI market research LLM agent using PydanticAI with multi-agent orchestration (Planner → Domain Agents → Finalizer), 5 specialized domain agents and 11 scenario agents for automated competitive intelligence
- Architected FastMCP server with 33 tools for App Store intelligence, integrating PostgreSQL with pgvector for semantic search and StarRocks OLAP for historical analytics
- Designed RAG systems with DuckDB VSS and ONNX-optimized embeddings, achieving sub-100ms query latency with CPU-optimized INT8 quantization and hybrid search (HNSW + BM25)
- Managed and processed big data analytics pipelines (>200 million records/day) with 99.9% uptime using Snowflake, StarRocks, and Apache Airflow
- Engineered AI-powered keyword analysis service with BERT embeddings and ONNX optimization, delivering sub-second response times at 5k+ requests/second
- Built enterprise-grade microservices using gRPC, FastAPI, and Celery, integrating OpenAI GPT, Claude API, and Apple Search Ads API
- Built complete AWS infrastructure (ECS, RDS, S3, Bedrock) with Kubernetes orchestration and Jenkins CI/CD pipelines

**Technologies & Tools:**
- **Languages & Frameworks:** Python 3.12+, FastAPI, gRPC, Slack Bolt SDK, Protocol Buffers
- **ML/AI:** PyTorch, Sentence-Transformers, BERT, KeyBERT, ONNX Runtime, OpenAI GPT, Pydantic AI, FastEmbed, RAG systems
- **Multi-Agent Systems:** PydanticAI, MCP (Model Context Protocol), agent orchestration, workflow automation
- **Data Processing:** Snowflake, PostgreSQL (with pgvector), StarRocks (OLAP), BigQuery, Pandas, Polars, PyArrow, SQLAlchemy, Redis
- **Cloud & Infrastructure:** AWS (ECS, EC2, RDS, S3, CloudWatch, IAM, Bedrock Voyage AI), Kubernetes, Docker, Jenkins CI/CD, Poetry, Prometheus monitoring
- **Workflow Orchestration:** Apache Airflow, Celery, RabbitMQ
- **Browser Automation:** Playwright (ASA authentication flows)
- **Observability:** LangSmith, Logfire, Sentry, Prometheus, distributed tracing
- **External APIs:** Apple Search Ads, Google Cloud Platform, Google Sheets API, OpenAI API, Anthropic Claude API

### Senior Software Engineer, Exness
*August 2016 – April 2022*

- Created standardized driver interfaces enabling seamless integration of 50+ payment systems through unified API gateway
- Designed microservices-based billing system with support for traditional payment methods and crypto (BTC, USDT-OMNI), significantly increasing deposit volumes
- Participated in 400+ technical interviews, contributing to the successful hiring of 20+ top-tier developers
- Implemented PCI DSS compliant authentication mechanisms and regulatory compliance features for global financial operations
- Optimized database performance through SQL query tuning and architectural improvements using distributed database systems

**Technologies & Tools:**
- **Languages & Frameworks:** Python, Thrift
- **Infrastructure:** Docker, Kubernetes, Helm
- **Databases:** Distributed database systems, SQL optimization
- **Security:** PCI DSS compliance, authentication/authorization systems
- **Blockchain:** Bitcoin Core integration, cryptocurrency payment processing
- **Architecture:** Microservices, API Gateway, service mesh

### Software Engineer, Game Stream Joint LLC
*August 2014 – August 2016*

- Built a microservice-based coupon system and led the premium shop redesign, increasing user engagement and sales.
- Developed versatile APIs for seamless external platform integration.

**Technologies & Tools:**
- **Languages & Frameworks:** Python, Django
- **Databases:** PostgreSQL, Redis
- **Infrastructure:** Docker
- **Architecture:** Microservices

### Software Developer, Mobispot Social Systems
*October 2012 – August 2014*

- Led development of billing systems for payment terminals and vending machines.
- Created an online shop for NFC tags and integrated social network features.

**Technologies & Tools:**
- **Languages & Frameworks:** Python, Flask
- **Databases:** MySQL, Redis
- **Infrastructure:** Docker

---

## Open Source Contributions

### Popular Python Libraries (2.4M+ total downloads, 220K+ monthly)
- [starlette-request-id](https://github.com/bigbag/starlette-request-id): High-performance ASGI middleware for request tracing in Starlette applications, enabling distributed system observability with automatic request ID generation, context propagation across async operations, and seamless integration with Python's logging framework for enhanced debugging and monitoring. [120K downloads/month](https://clickpy.clickhouse.com/dashboard/starlette-request-id) (1.4M total downloads).
- [request-id-helper](https://github.com/bigbag/request-id-helper): Thread-safe request ID tracking library for Python applications, providing decorator-based integration, custom log formatters, and automatic request ID injection for cross-service tracing in microservices architectures with comprehensive testing and type checking support. [100K downloads/month](https://clickpy.clickhouse.com/dashboard/request-id-helper) (970K total downloads).
- [starlette-i18n](https://github.com/bigbag/starlette-i18n): Internationalization middleware for Starlette applications, integrating gettext and Babel translation systems with automatic locale detection from HTTP headers, lazy translation loading, and customizable language preferences for building multi-language web applications. ⭐ >10 stars

### E-Paper Reader Ecosystem
- [papyrix-reader](https://github.com/bigbag/papyrix-reader): Lightweight firmware fork for Xteink X4 e-paper reader built on ESP32-C3, featuring EPUB parsing with customizable fonts, WiFi book upload, exFAT support, and intelligent SD card caching to operate within ~380KB RAM constraints.⭐ >50 stars
- [papyrix-flasher](https://github.com/bigbag/papyrix-flasher): Cross-platform Go utility for flashing firmware onto ESP32-C3 based e-paper readers, implementing ESP32 ROM bootloader protocol with SLIP framing, zlib compression for faster transfers, and automatic device detection across Windows, Linux, and macOS.
- [epub-to-xtc-converter](https://github.com/bigbag/epub-to-xtc-converter): Browser-based EPUB to XTC/XTCH converter for Xteink e-readers, featuring CREngine WASM for accurate rendering, batch processing, live page preview, customizable fonts and layouts across 42 languages, CSS optimization, image grayscale conversion, and Floyd-Steinberg dithering via Web Workers for optimal e-ink display quality.

---

## Notable Projects

### Multi-Agent AI Research System
Built a production-grade multi-agent orchestration platform using PydanticAI for market research and competitive intelligence:
- **Architecture**: Planner → Domain Agents → Finalizer workflow with 5 specialized domain agents and > 10 scenario agents
- **Integration**: Slack Bolt SDK for conversational interface, FastMCP for external tool integration, SSE streaming for real-time responses
- **AI/ML**: Multi-model strategy with automatic fallback across major LLM providers
- **Observability**: LangSmith tracing, Sentry error tracking, Prometheus metrics, comprehensive usage tracking
- **Technologies**: Python, PydanticAI, FastAPI, PostgreSQL, MCP protocol, Slack API

### RAG Knowledge Base Systems
Developed multiple RAG implementations for semantic search and knowledge retrieval:
- **Market Research RAG**: DuckDB with VSS extension, ONNX-optimized embeddings, hybrid search (HNSW + BM25)
- **MCP RAG Framework**: Semantic tool retrieval system to mitigate prompt bloat in LLM tool selection using FastEmbed
- **Performance**: CPU-optimized INT8 quantization, sub-100ms query latency, no external API dependencies
- **Technologies**: Python, DuckDB, ONNX Runtime, sentence-transformers, FastEmbed, pgvector

### Apple Search Ads Intelligence Platform (MCP Server)
Architected FastMCP server with > 30 tools for App Store competitive intelligence:
- **Features**: Semantic app search with BM25 ranking, competitor discovery, keyword analysis, historical trends, SOV tracking
- **Databases**: PostgreSQL with pgvector for semantic search, StarRocks OLAP for time-series analytics (April 2024+)
- **Performance**: Parallel processing with asyncio.gather(), file-based caching with TTL, background health checks
- **Observability**: Prometheus metrics tracking, distributed tracing with Logfire, JWT authentication middleware
- **Technologies**: Python 3.12+, FastMCP, PostgreSQL, pgvector, StarRocks, AWS Bedrock, Pydantic

---

## Education

- **Master of Science in Information Technology (MSIT)**, University of the People (3.97 GPA)
- **Master's Degree in Theoretical Physics**, Kemerovo State University

---

## Certifications

### General
- [**Professional Scrum Developer™ I (PSD I)**](https://www.credly.com/badges/f3c7117f-ac89-4160-919f-995082f365f5)
- [**Astronomer Certification for Apache Airflow 2 Fundamentals**](https://www.credly.com/badges/9148e9ff-f4a8-4028-a3d3-a34c0acdb77a)
- [**CKA: Certified Kubernetes Administrator**](https://www.credly.com/badges/24122208-e39b-4052-80fd-19f49ed1176b/public_url)

### Coursera Specializations
- [**Project Management and Planning**](https://www.coursera.org/account/accomplishments/specialization/OTHQOGV48PRK)
- [**Generative AI for Software Development**](https://www.coursera.org/account/accomplishments/professional-cert/BSV952W3S4QC)
- [**Agentic AI and AI Agents for Leaders**](https://www.coursera.org/account/accomplishments/specialization/G84HKWXVXANF)
- [**Algebra: Elementary to Advanced**](https://coursera.org/verify/specialization/QDWV3BG7QAWM)
- [**Data Structures and Algorithms**](https://coursera.org/verify/specialization/8NKLJFF5QKZW)
- [**Introduction to Scripting in Python**](https://coursera.org/verify/specialization/SGW7JYL2UK8B)
- [**Python 3 Programming**](https://coursera.org/verify/specialization/59EV37F9US56)
- [**Self-Driving Cars**](https://coursera.org/verify/specialization/EDTCKBT5H78J)
- [**Rocket Science 101**](https://www.coursera.org/account/accomplishments/specialization/E7D87UJMA0CC)

### Udacity
- [**Machine Learning Engineer Nanodegree**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/udacity_ml.pdf)

### Yandex
- [**Go Developer Professional Training Course**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/yandex_golang.pdf)

### Hugging Face AI Agents Course (2025)
- [**AI Agents Course Certificate**](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/hf_agents_course_2025.pdf)

### Oxford Machine Learning Summer School
- [**OxML 2024**: Attended advanced lectures on ML theory and its applications in Health & Bio, and Representation Learning & Generative AI](https://github.com/bigbag/bigbag.github.io/blob/main/certifications/oxml_2024.pdf)

---

## Technical Skills

### Languages & Expertise
- **Python** (12+ years): FastAPI, Starlette, Django, Flask, async/await patterns
- **Golang** (6+ years): Microservices, concurrent systems
- **Protocols**: gRPC, REST, GraphQL, Protocol Buffers, MCP (Model Context Protocol)

### AI/ML & Data Science
- **LLM Integration**: PydanticAI, OpenAI GPT, Anthropic Claude, Slack Bolt SDK
- **ML Frameworks**: PyTorch, Sentence-Transformers, BERT, KeyBERT
- **Optimization**: ONNX Runtime (INT8/AVX512 quantization), CPU-optimized inference
- **RAG Systems**: Vector embeddings, semantic search, pgvector, DuckDB VSS
- **NLP**: NLTK, language detection, multilingual models

### Databases & Storage
- **SQL**: PostgreSQL (including pgvector), MySQL, Alembic migrations
- **NoSQL/Cache**: Redis, SQLAlchemy ORM
- **Data Warehouses**: Snowflake, StarRocks (OLAP)
- **Vector Databases**: pgvector, DuckDB with VSS extension

### Cloud & Infrastructure
- **AWS**: ECS, EC2, RDS, S3, CloudWatch, IAM, Bedrock
- **Orchestration**: Kubernetes (CKA certified), Docker, Helm, Werf
- **Workflow**: Apache Airflow (certified), Celery, RabbitMQ
- **CI/CD**: Jenkins, GitHub Actions

### Observability & Monitoring
- **Metrics**: Prometheus, Grafana, custom exporters
- **Tracing**: LangSmith, Logfire, distributed tracing
- **Logging**: Structured logging, request ID tracking
- **Error Tracking**: Sentry

### Security & Authentication
- **Secrets Management**: HashiCorp Vault, Kubernetes service accounts
- **Cryptography**: RSA/AES hybrid encryption, JWT tokens
- **Compliance**: PCI DSS, authentication/authorization systems

### Additional Technologies
- **Message Queues**: RabbitMQ, Redis Streams
- **Browser Automation**: Playwright
- **API Integration**: Apple Search Ads, Google Cloud Platform, OpenAI
- **Data Processing**: Pandas, Polars, PyArrow, BigQuery

---

## Languages

- **English**: Professional working proficiency
- **Russian**: Native

---