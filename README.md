### Likhith Busam — AI Engineer

I build multi-agent and RAG systems end to end: experiment harness, typed production backend, operator dashboard. Three projects below show how I work.

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

**[StudyGenie Hub](https://github.com/santhoshkumaritla/Study-Genie)** — AI-Powered Study Platform (Peekuthon Hackathon)
A collaborative study platform with AI-generated flashcards, quizzes, and document summarization, an AI tutoring chatbot, and real-time collaborative study rooms with shared notes and live chat.
`React` `TypeScript` `Node.js` `MongoDB`

#### Tech Stack

`Python` `TypeScript` `LangChain` `LangGraph` `FastAPI` `React` `PyTorch` `XGBoost` `FAISS`

#### Currently

- Building production-track infrastructure for multi-agent systems: memory, tracing, tool-failure handling
- B.Tech, Rajiv Gandhi University of Knowledge Technologies, Andhra Pradesh
- Open to AI Engineer internship roles
