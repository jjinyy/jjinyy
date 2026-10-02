## Hi, I'm Hyejin (Jinny)

I'm an AI/software engineer interested in building intelligent systems that work beyond the prototype.

My work spans **AI agents, LLM systems, retrieval, applied ML, reinforcement learning, and full-stack AI applications** — from experimenting with models and architectures to building APIs, evaluation pipelines, and production integrations.

I enjoy problems where the right solution isn't obvious at the start: understanding the problem structure, choosing the right technical approach, building the system end-to-end, and testing whether it actually works.

I've worked across 20+ projects in manufacturing, logistics, pharma, and distribution, and have built AI systems in both client-facing and enterprise environments across Korea, Malaysia, Singapore, Thailand, Brazil, and the US.

Currently exploring **AI agents, AI for software engineering, retrieval & evidence-grounded reasoning, evaluation, and reliable AI systems.**

---

## Selected Projects

### [incident-response-agent](https://github.com/jjinyy/incident-response-agent)

An AI agent that investigates production incidents across a synthetic microservice environment.

Uses native tool calling to inspect **logs, metrics, distributed traces, deployments, configuration changes, dependencies, and runbooks**.

Built fault-injection scenarios for deployment regressions, dependency failures, bad configurations, connection-pool exhaustion, and traffic spikes — with evidence validation, bounded investigation loops, human approval for high-risk remediation, and stateful recovery verification.

`Python` `FastAPI` `LLM Tool Calling` `Distributed Tracing` `Agent Evaluation`

---

### [bug-ranker](https://github.com/jjinyy/bug-ranker)

A research-inspired fault-localization system based on the AutoFL approach.

Given a stack trace, ranks the functions most likely to contain the bug using **AST-level code chunking, hybrid keyword + embedding retrieval, and optional Claude reranking**.

Achieved **100% Top-1 / Top-5 retrieval accuracy on a 5-case controlled benchmark**, with automated evaluation through GitHub Actions.

`Python` `AST` `Embeddings` `Hybrid Retrieval` `Claude API` `Evaluation`

---

### [material-category-mapping-ai](https://github.com/jjinyy/material-category-mapping-ai)

A multilingual classification system for **100K+ records**, combining learned embeddings with rule-based logic and human feedback.

Built with **Triplet Loss + Hard Negative Mining** and a human-in-the-loop retraining workflow, achieving **95%+ classification accuracy**.

`PyTorch` `Embeddings` `Triplet Loss` `Hard Negative Mining` `Human-in-the-loop`

---

### [phishing-detection](https://github.com/jjinyy/phishing-detection)

A real-time voice AI system for detecting and responding to suspicious calls.

Whisper handles speech-to-text, a lightweight rule-based layer provides low-latency and explainable risk detection, and GPT is used selectively for language generation.

Built end-to-end from backend and telephony integration to frontend and deployment.

`Whisper` `OpenAI API` `Flask` `Twilio` `React` `GitHub Actions` `Render`

---

### [vendor-deduplication-ai](https://github.com/jjinyy/vendor-deduplication-ai)

A multilingual entity-resolution system for **~50K global records** with inconsistent identifiers and noisy text.

Reduced a naïve **~151M pairwise comparison space to tens of thousands of candidates** through:

**Blocking → ANN Retrieval → Composite Similarity Scoring**

`Python` `ANN` `Embeddings` `Entity Resolution` `Multilingual NLP`

---

### [soybeanoil-predict](https://github.com/jjinyy/soybeanoil-predict)

An ML decision system that treats commodity purchasing as a **sequential decision problem rather than just a forecasting problem**.

Experiments with XGBoost, Temporal Fusion Transformer, and DQN to generate **Buy / Split / Wait** recommendations, exposed through a REST serving layer.

`XGBoost` `TFT` `DQN` `Reinforcement Learning` `Time Series` `REST API`

---

## What I Work With

**AI / ML**  
`LLM APIs` `Tool Calling` `RAG` `Embeddings` `PyTorch` `scikit-learn` `Reinforcement Learning` `Whisper` `LangChain`

**Backend / Systems**  
`Python` `FastAPI` `Flask` `Django` `Spring` `REST APIs` `SQL`

**Frontend**  
`React` `TypeScript` `Vue.js`

**Cloud / Infrastructure**  
`AWS Lambda` `API Gateway` `S3` `GitHub Actions` `Render`

**Enterprise Systems**  
`SAP` `Ariba` `BW/SAC` `CAP` `HANA`

---

## What I Care About

I'm interested in the space between **a model that works in a notebook and an AI system that actually works.**

That means thinking about more than model accuracy:

**retrieval · evaluation · latency · grounding · failure modes · human feedback · system integration · deployment**

I like experimenting with new AI techniques, but I'm even more interested in understanding **when they work, when they fail, and how to turn them into reliable systems.**
