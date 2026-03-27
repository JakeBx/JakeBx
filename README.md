## Jake L — AI/ML Engineer

AI/ML practitioner with 10+ years building and deploying Generative AI and machine learning systems from prototype to production. I specialise in the full lifecycle of AI/ML: architecture, deployment, security hardening, and extracting measurable business value at scale. Extensive work with critical and regulated industries.

Currently working as a Staff-level AI Engineer in the Australian federal government, leading enterprise AI/ML strategy and production deployment. I oversee LLM infrastructure, workflow automation, and AI capability programmes.

Previously led high-impact production ML delivery across government and large enterprise (large-scale fraud detection capability recovering more than $2B+ annually) and served as Principal Consultant at a specialist consulting firm, managing enterprise AI engagements for clients including large banks, international government bodies, critical infrastructure, national security, and service delivery.

---

### What I build

- **Enterprise GenAI applications** — OpenAI API integrations, production prompt engineering, evaluation harnesses, customer-facing AI products
- **Agentic AI systems** — multi-agent orchestration, tool use, code agents, automated reasoning pipelines
- **RAG pipelines** — embedding generation, vector search, semantic retrieval at scale
- **Deployment infrastructure** — secure inference, mTLS, ABAC, enterprise guardrails, streaming
- **Workflow automation** — n8n, Python, comparative low-code/pro-code architectures
- **ML at production scale** — NLP, computer vision, fraud detection, identity resolution

---

### Open source

**n8n-io/n8n** — open PR #27309: adds mTLS client certificate support to the OpenAI node family (+675 lines, 27 new test cases). Covers OpenAI Enterprise mTLS beta, self-hosted inference endpoints behind certificate-authenticated proxies, and custom CA bundles. Addresses a recurring community pain point for enterprise deployments.

**anthropics/anthropic-sdk-python** — open PR #1280: adds a worked example (`examples/mtls.py`) demonstrating mTLS client certificate authentication and custom CA bundle configuration with the Anthropic SDK. No SDK code changes required — documents existing `http_client` capability that was previously undiscovered by enterprise users hitting proxy and certificate errors.

**[huggingface/smolagents](https://github.com/huggingface/smolagents)** (22k+ stars) — contributor. [PR #1420](https://github.com/huggingface/smolagents/pull/1420): added `reset_agent_memory` support in GradioUI, merged by the HuggingFace core team.

**[n8n-nodes-mtls-openai](https://www.npmjs.com/package/n8n-nodes-mtls-openai)** — published npm package providing n8n community nodes for mTLS-authenticated connections to OpenAI-compatible inference endpoints. Solves a real enterprise gap: connecting workflow automation to LLMs behind certificate-authenticated proxies.

---

### Featured projects

| Project | What it does |
|---------|-------------|
| [agentic-cti](https://github.com/JakeBx/agentic-cti) | Multi-agent threat intelligence system orchestrating specialised sub-agents (OpenCTI, OSINT, Wikipedia) — Hydra config management, automated evaluation harness, Docker deployment |
| [alcohol-and-other-drugs-understanding](https://github.com/JakeBx/alcohol-and-other-drugs-understanding) | End-to-end RAG pipeline over medical literature — automated scraping, PGVector storage, LLM-powered chatbot via OpenAI-compatible API, UMAP + topic modelling, interactive data map |
| [n8n-nodes-mtls-openai](https://github.com/JakeBx/n8n-nodes-mtls-openai) | Published npm package: custom n8n nodes (TypeScript) providing mTLS-authenticated connections to OpenAI-compatible inference endpoints — chat model and embeddings sub-nodes for enterprise RAG pipelines |
| [hardened-llm-deployment](https://github.com/JakeBx/hardened-llm-deployment) | Production deployment blueprint: ABAC + mTLS secured LLM inference on Kubernetes/KServe/Istio — streaming responses with pre-computed classification, async audit logging |
| [bellingcat-py](https://github.com/JakeBx/bellingcat-py) | OSINT corpus analysis pipeline — entity relationship extraction, vector embeddings, agentic semantic search — paired with an n8n equivalent for direct pro-code vs low-code architectural comparison |

---

### Stack

**GenAI / LLMs:** OpenAI API · HuggingFace · smolagents · RAG architectures · prompt engineering · ONNX · PyTorch
**Languages:** Python (advanced) · TypeScript · SQL · Bash
**Infrastructure:** AWS · GCP · Azure · Docker · Kubernetes · PostgreSQL · PGVector · Ray 
**AI security:** MITRE ATLAS · adversarial ML · differential privacy · ML red teaming

---

### Education

**M.S. Analytics (Computational)** — Georgia Institute of Technology, 2020 (GPA 4.0)
**B.Finance / B.Economics** — Australian National University, 2012

**Certifications:** SANS Offensive AI (2025) · Stanford Professional Certificate in AI (2023) · GIAC Penetration Tester (GPEN) · GIAC Detection Analyst (GCDA) · Cloud Native Architecture (Udacity)
