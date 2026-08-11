## Hi, I'm Jinny

I build applied AI systems that work in real-world environments.

My focus is not just on models, but on how AI integrates into actual business processes —
from data pipelines and system design to deployment and iteration.

I often start with messy, ambiguous problems
and turn them into structured AI solutions that can be reliably used in production.

Before building anything, I prioritize understanding how people work —
because the success of an AI system depends more on adoption than accuracy.

I’ve worked across Malaysia, Singapore, Thailand, Brazil, and the US,
designing systems in environments where data is inconsistent and processes vary widely.
These experiences shaped how I approach scalable and resilient AI.

Currently focused on behavioral data pipelines,
LLM/RAG-based systems, and building AI that holds up beyond the prototype stage.

---

### Projects

**[soybeanoil-predict](https://github.com/jjinyy/soybeanoil-predict)**
Commodity purchase decision model — RL (DQN) + XGBoost/TFT, reframed as a sequential decision problem, not price forecasting.
SAP CAP/Node.js service layer (HANA CDS, OData) serving the model through SAP AI Core — training → inference validated end to end.

**[material-category-mapping-ai](https://github.com/jjinyy/material-category-mapping-ai)**
Auto-classification pipeline for 100K+ multilingual material records.
95%+ accuracy within a standardized category schema.
Human-in-the-loop design — accuracy compounds as users give feedback.
Triplet Loss + Hard Negative Mining based training architecture.

**[vendor-deduplication-ai](https://github.com/jjinyy/vendor-deduplication-ai)**
Dedup pipeline across ~50K global supplier records.
No universal ID across countries — tax ID used only as a secondary signal.
3-stage hybrid: Blocking → ANN → embedding similarity scoring.
~30% duplicate rate found and cleaned.

**[procurement-rag-system](https://github.com/jjinyy/procurement-rag-system)**
Internal compliance/policy Q&A system. Hybrid retrieval + enforced source citation for hallucination control.
Fully on-premise — LangChain + Ollama/DeepSeek, zero external API calls.

**[phishing-detection](https://github.com/jjinyy/phishing-detection)**
Real-time scam-call detection proxy — Whisper STT + keyword scoring + LLM response strategy.
Flask backend · self-built GitHub Actions CI/CD · deployed on Render, alone.

**[kleague-analytics](https://github.com/jjinyy/kleague-analytics)**
Pass-destination prediction from K League event sequences. LSTM vs. Transformer comparison.
Same problem shape as tracing a fault signature through commit history or test-execution logs.

---

### Stack

**Analytics / ML** `Python` `SQL` `pandas` `scikit-learn` `PyTorch` `NLP / Embeddings` `Triplet Loss` `Reinforcement Learning` `LangChain` `RAG` `Ollama`

**Systems / Backend** `FastAPI` `Flask` `Spring` `Vue.js` `Oracle DB` `Jenkins` `GitHub Actions` `Render`

**SAP / Enterprise** `SAP ERP` `SAP Ariba` `SAP BW / SAC` `SAP AI Core` `SAP CAP / HANA CDS`

