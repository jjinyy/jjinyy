## Hi, I'm Hyejin (Jinny)

**Enterprise Data & AI Architect | Hands-on AI Engineer**

I design and build data and AI solutions that connect complex enterprise systems with real business needs.

Over the past 8 years, I've worked across **enterprise data architecture, applied machine learning, AI systems, and customer-facing technical consulting** — from understanding business requirements and evaluating technical options to building solutions and validating their impact.

At **CJ CheilJedang**, I've worked on enterprise data platform modernization, including hands-on validation of **SAP Business Data Cloud–Databricks integration** and Delta Sharing. My work involves evaluating architecture trade-offs across performance, cost, governance, and AI readiness. I've also developed AI solutions for procurement decision support, material classification, entity resolution, RAG, and knowledge graph-based profitability analysis.

Previously at **Hansol PNS**, I worked with clients across manufacturing, logistics, pharmaceuticals, and distribution, collaborating with sales teams on technical PoCs, solution architecture, and end-to-end project delivery.

I enjoy solving problems where the right technical approach isn't obvious at first — understanding the business context, designing practical solutions, building them hands-on, and testing whether they actually work.

Currently exploring **AI agents, retrieval and evidence-grounded reasoning, evaluation, and reliable AI systems**.

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
