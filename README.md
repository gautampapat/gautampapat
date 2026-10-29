# Gautam Papat

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gautam-papat)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gautampapat)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gautampapat@gmail.com)

**AI/ML Engineer & Full-Stack Developer**  
*B.Tech in Artificial Intelligence & Machine Learning — Walchand College of Engineering*

</div>

---

### About Me

I design and build production-ready AI systems, hybrid RAG pipelines, and scalable full-stack applications. My engineering philosophy focuses on deterministic AI workflows, low-latency retrieval, strict unit economics (< $0.005/run), and clean system design over brute-force generative prompts.

- **AI/ML Focus:** Deterministic RAG pipelines, dense/sparse hybrid search, candidate ranking engines, and time-series forecasting.
- **Full-Stack Focus:** React 19, TypeScript, FastAPI, Supabase (RLS), and mobile apps with Kotlin / Jetpack Compose.
- **Performance Obsessed:** Sub-second inference, vectorized matrix operations, and zero-cost serverless architectures.

---

### Main Projects

#### 1. [Zenis](https://github.com/gautampapat/Zenis) — Ultra-Low-Token AI Presentation Engine
> Deterministic, tool-heavy presentation generation with automated deep research.
* Offloads 90% of processing from frontier LLMs to deterministic open-source scrapers (`Trafilatura`, `Crawl4AI`, `PyMuPDF`) and single-forward-pass System-1 decision models.
* Implements an in-memory two-pass layout reducer and batched micro-synthesis (`BAML`/`Instructor`) achieving **<$0.005 cost per deck** and a **sub-8 second end-to-end SLA**.
* *Stack:* `Python`, `Trafilatura`, `PyMuPDF`, `Chonkie`, `BAML`, `python-pptx`, `React`

#### 2. [eduWin](https://github.com/gautampapat/eduWin) — Single-Tenant Coaching Institute OS
> Turn-key operations and financial management blueprint for Indian coaching institutes.
* Multi-role enterprise portal (Admin, Teacher, Student, Parent) with granular fee installment ledgers, automated payment receipts, attendance logging, and batch management.
* Architected for zero-cost serverless deployment on Supabase Free Tier (PostgreSQL + Row-Level Security) with Cloudflare Pages/Vercel.
* *Stack:* `TypeScript`, `React 19`, `Tailwind CSS 4`, `Supabase`, `TanStack Query 5`

#### 3. [Parakh / LabelDekho](https://github.com/gautampapat/parakh) — Personalized Product Intelligence Engine
> India-first packaged-goods transparency engine spanning food, beverages, and personal care.
* Barcode-driven SKU identification engine integrating Open Food Facts and Open Beauty Facts APIs with strict source provenance, freshness windows, and versioned package-label evidence.
* Generates personalized hazard breakdowns, additive flags, and nutritional insights based on user dietary preferences and allergies.
* *Stack:* `Python`, `TypeScript`, `Capacitor`, `PWA`, `REST APIs`

---

### Secondary Highlights

* **[DocLearn (FastAPI)](https://github.com/gautampapat/doclearn-fastapi)** — Full-stack interactive documentation learning platform. Synthesizes version-locked FastAPI docs into structured lessons with line-by-line AI code breakdowns using DeepSeek R1, ChromaDB vector search (`bge-small-en-v1.5`), and FastAPI SSE streaming.
* **[NestMate](https://github.com/gautampapat/nestmate_android)** — Android platform for shared campus living built with Kotlin and Jetpack Compose. Features a custom roommate compatibility scoring algorithm, peer-to-peer expense splitter, housing listings, and community safety hubs.

---

### Machine Learning & Data Science Showcase

| Project | Domain | Architecture & Key Result |
| :--- | :--- | :--- |
| **[Redrob Candidate Ranker](https://github.com/gautampapat/Redrob-Candidate-Ranker)** | Semantic Search & Anomaly Detection | **1.00s CPU execution across 100,000 candidates**. Offloads `all-MiniLM-L6-v2` embeddings to memory-mapped `.npy` stores offline; executes online vectorized dot-product scoring and continuous anomaly penalty modeling. |
| **[Smart PDF Contract Analyzer](https://github.com/gautampapat/Smart-PDF-Contract-Analyzer)** | Document AI & Legal NLP | **Production Hybrid RAG pipeline**. Combines BM25 sparse keyword search + ChromaDB dense vectors with local Cross-Encoder reranking and Gemini Flash to extract legal clauses and assign tiered risk scores. |
| **[EventLabs Churn Prediction](https://github.com/gautampapat/ChurnPrediction_Project)** | Predictive Analytics & Classification | **0.9806 ROC-AUC on 19,889 user sessions**. Calibrated logistic regression mapping 4 discrete retention tiers; identified that early session actions predict completion with 95% accuracy. |
| **[Retail Sales Forecasting](https://github.com/gautampapat/Sales-Forecasting)** | Time-Series & Clustering | **Multi-model demand forecasting system**. Combines SARIMA, Prophet, and XGBoost with Isolation Forest anomaly detection and K-Means SKU clustering behind an interactive Streamlit dashboard. |
| **[WalchandOnGo](https://github.com/gautampapat/WalchandOnGo)** | Graph Theory & Algorithms | **Campus pathfinding engine**. Parses raw OpenStreetMap data into navigable topological graphs; features a live comparison visualizer benchmark testing A*, Dijkstra, and BFS traversal paths. |

---

### Tech Stack & Tooling

- **Languages:** Python, TypeScript, JavaScript, SQL, Kotlin, C++
- **AI / RAG / ML:** LangChain, ChromaDB, Sentence-Transformers, PyMuPDF, Chonkie, BAML, Scikit-Learn, XGBoost, Prophet, Statsmodels, DeepSeek R1, Gemini API
- **Backend & Cloud:** FastAPI, Uvicorn, SSE Streaming, Node.js, Express, Supabase (PostgreSQL, RLS), Docker
- **Frontend & Mobile:** React 19, Vite, Tailwind CSS 4, Kotlin, Jetpack Compose, HTML5/CSS3
- **Data & Tools:** Pandas, NumPy, OpenStreetMap, Git/GitHub, Cloudflare Pages, Vercel
