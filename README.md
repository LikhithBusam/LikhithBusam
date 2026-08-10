### Hi, I'm Likhith — AI/ML Engineer building agentic AI systems

I design and ship multi-agent, RAG, and LLM-orchestration systems end to end: research/experiment harness, typed production backend, and the dashboard to operate it. Below are the three projects that best represent how I work.

#### Featured Work

**[enterprise-ai-customer-support](https://github.com/LikhithBusam/enterprise-ai-customer-support)** — Adaptive Multi-Agent Customer Support System
A LangGraph-orchestrated, memory-augmented multi-agent pipeline (7 typed agents: Intake, Planner, Executor, Critic/Replanner, Memory Manager, Response, Escalation) with a research track (paper-citable ablation results comparing memoryless vs. static-ReAct vs. memory-augmented vs. policy-memory baselines) and a production track (FastAPI backend, per-client auth, OpenTelemetry tracing, Stripe/Zendesk tool integrations, PII redaction) plus a 15-page React operations dashboard with a live LangGraph execution-trace visualizer.
`LangGraph` `FastAPI` `React` `ChromaDB` `OpenTelemetry`

**[predictive_Intelligence](https://github.com/LikhithBusam/predictive_Intelligence)** — Predictive Intelligence 360
An agentic RAG-powered predictive maintenance platform for industrial equipment (CNC, bearings, pumps, turbofan engines). A 3-stage pipeline — XGBoost fault classification/RUL regression, FAISS semantic search over 1,527 knowledge chunks, and LLM-based diagnostic reasoning — served through a FastAPI backend and real-time dashboard. Backed by a 112-test suite (111 passing) covering ML validation, RAG retrieval, and API correctness.
`XGBoost` `FAISS` `FastAPI` `sentence-transformers` `scikit-learn`

**[GroundedRx](https://github.com/LikhithBusam/GroundedRx)** — Bilingual Medical RAG with a Groundedness Gate
A fully self-hosted (no external LLM API) medical RAG system that answers medication questions in Arabic or English from a corpus of patient information leaflets, using hybrid dense+BM25 retrieval and a locally-hosted Qwen2.5-7B model. Every answer is checked against its retrieved source before being shown — the groundedness gate fails closed and has caught a real fabricated answer during evaluation. Cross-lingual retrieval (Arabic query → English source) is measured, not assumed.
`RAG` `LLM` `Qwen2.5` `Hybrid Retrieval` `Arabic NLP`

#### Collaborations

**[JEPA-Med-OOD](https://github.com/Nikhil-Rao20/JEPA-Med-OOD)** — Self-Supervised Learning for Out-of-Distribution Detection in Medical Imaging
Team project comparing JEPA, MAE, and supervised learning for chest X-ray OOD detection — evaluating not just classification accuracy but each method's ability to flag data it wasn't trained on, a key safety requirement for clinical AI deployment.
`PyTorch` `Self-Supervised Learning` `Medical Imaging` `OOD Detection`

#### Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337ab7?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=flat)

#### Currently

- Building production-track infrastructure for multi-agent systems: memory, tracing, tool-failure handling
- B.Tech, Rajiv Gandhi University of Knowledge Technologies, Andhra Pradesh
- Open to AI Engineer internship roles

#### GitHub Stats

![Likhith's GitHub stats](https://github-readme-stats.vercel.app/api?username=LikhithBusam&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LikhithBusam&layout=compact&hide_border=true)
