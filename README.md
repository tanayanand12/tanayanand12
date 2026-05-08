## Tanay Anand

**Applied AI Researcher · Agentic Systems · RL Workflows**
Data Scientist, AI/ML Engineering @ R Systems International
B.Tech, AI & Data Science · IIT Jodhpur (2024)

📧 tanay.anand12@gmail.com · [LinkedIn](https://linkedin.com/in/tanay-anand-702555229) · 🌐 tanayanand12.github.io *(in progress)*

---

### About

I work on production agentic systems and applied ML research at the
intersection of LLM tooling, reinforcement learning, and biomedical AI.
At R Systems, I build multiagent RAG and RL-driven workflow systems
deployed against enterprise document corpora. My research sits at the
IIT Jodhpur Ayurtech Centre of Excellence, with a current submission
under review at *PNAS* on cross-talking ontologies between modern and
Ayurvedic phenotypes (COMAP / AyurPhenoClusters).

In December 2025 I joined Prof. Abhilash Jindal's group (CSE, IIT Delhi)
as an invited collaborator on POPPER — a dataflow system for in-flight
error handling in ML workflows, also deployed in production at R Systems.

**Currently:** extending the Medical Research Agent toward an EMNLP /
AMIA submission, and fine-tuning BioMistral on the COMAP dataset.

---

### Production Work — R Systems International

Client-facing systems shipped to production. Source is proprietary;
architectures and outcomes summarised below.

- **SalesWhiz** — Multiagent RAG over enterprise document corpora (PDFs, PPTs, DOCX, Excel) with token-aware context windowing, four-strategy query expansion, and seven-category intent classification. 150+ test cases; 3 critical security vulnerabilities surfaced pre-deployment.
- **POPPER** — Assertion-validated multi-model entity extraction with multi-armed bandit routing for cost-vs-accuracy escalation. 95.48% extraction accuracy across 12+ entity types; ~66% API cost reduction vs. frontier baseline.
- **ATLAS** — Three-agent AutoGen pipeline (planning / execution / validation) for LLM-guided adaptive scraping over JS-rendered and structurally dynamic targets, with human-in-the-loop escalation for low-confidence extractions.
- **Seapeak** — Multimodal RAG fusing vision encoders (charts, tables, diagrams) with text embeddings, agent-routed by modality, with mandatory document-provenance attribution per response.
- **TUCCI** *(TUUCI Inc.)* — Hybrid Graph RAG combining vector retrieval with ontology-aligned knowledge graph traversal across product families, materials, and accessory compatibility.
- **Sales Workflow Automation** — FastAPI presales pipeline: inbound email parsing, structured requirement extraction, semantic offering-matching, and personalised response synthesis with LLM-driven topic modelling.

---

### Selected Open-Source Work

- **[Medical-Research-Agent](https://github.com/tanayanand12/Medical-Research-Agent)** — Six-agent LangChain pipeline for biomedical literature synthesis over PubMed + ClinicalTrials.gov, with three-tier knowledge layering across UMLS, SNOMED-CT, Gene Ontology, and KEGG. Scaled to 100K+ papers; basis for planned EMNLP / AMIA submission.
- **[Clinical-Trials-AI-Suite](https://github.com/tanayanand12/Clinical-Trials-AI-Suite)** — Production-grade tooling for clinical trial intelligence: eligibility analysis, endpoint prediction, protocol design generation, and benchmark comparison against ClinicalTrials.gov.
- **[Agentic-Document-Generation-Toolkit](https://github.com/tanayanand12/Agentic-Document-Generation-Toolkit)** — Multi-agent document generation with template-agnostic PDF synthesis and traceable evidence chains. Supports 20+ distinct document types from a single layout-inference agent.
- **[AI-Powered-Video-Generation-Pipeline](https://github.com/tanayanand12/AI-Powered-Video-Generation-Pipeline)** — Four-agent multimodal video pipeline: storyboard generation → Veo3 scene-level synthesis → temporal coherence validation → ffmpeg-based clip stitching with audio alignment.
- **[Due Diligence Report Generation Agent]( )** — Multi-agent RAG (ingestion, entity extraction, risk flagging, synthesis) over heterogeneous sources with full evidence traceability per output.
- **[Serverless Vector DB — FAISS on GCP]( )** — FAISS index lifecycle system with serialised shard storage on GCP Cloud Storage; versioning, incremental updates, cache-warming. Sub-200ms retrieval with no always-on vector DB infra.

---

### Research

- **Cross-Talking Ontology for Modern and Ayurveda Phenotypes (COMAP / AyurPhenoClusters)** — Submitted to *PNAS*; rebuttal under review.
   *Mentors:* Dr. Mitali Mukerji, Dr. Lipika Dey · IIT Jodhpur Ayurtech Centre of Excellence.
   Unified 10,610 HPO terms and 12,678 rare diseases across modern and Ayurvedic ontologies; EM clustering yielded six AyurPhenoClusters with significant ciliary gene enrichment (43%) in the Kapha-predominant cluster.
- **POPPER — Winter Research Residency, IIT Delhi (December 2025)**
   Invited collaborator with Prof. Abhilash Jindal (CSE, IIT Delhi) on POPPER's multi-armed bandit query optimizer; research discussions on extending the optimizer for unexpected data drift and LLM-based data pipelines.
- **Medical Research Agent (in progress)** — Targeting EMNLP / AAAI / AMIA. Currently scoping novelty against BioRAG and MedRAG; planned evaluation against BioASQ / MedQA with ablations.

---

### Stack

**Agentic & LLM:** LangChain · LangGraph · AutoGen · OpenAI APIs · Hugging Face Transformers · WebSockets · FastAPI
**ML / DL:** PyTorch · Scikit-Learn · XGBoost · NumPy · Pandas · SHAP · LORA Fine-Tuning · OpenCV
**RL:** Multi-Armed Bandits · Thompson Sampling · UCB · Cost-Aware Routing
**Biomedical NLP:** scispaCy · NLTK · spaCy · UMLS · SNOMED-CT · PubMed API · ClinicalTrials.gov API
**Retrieval & Graphs:** FAISS · Neo4j · Firestore Vector Search · Graph RAG · Multimodal Retrieval · Semantic Reranking
**Infra:** GCP (Associate Cloud Engineer) · Azure · Docker · Kubernetes · CI/CD · MLflow · AWS SageMaker

---

### Education

**B.Tech, Artificial Intelligence & Data Science** — Indian Institute of Technology, Jodhpur (2024)
*Coursework:* Pattern Recognition & Machine Learning · Optimization for ML · Deep Learning · Advanced AI · Dependable AI · Statistical Inference · Data Engineering · DSA

---

### Certifications

GCP Associate Cloud Engineer · Google Advanced Data Analytics Professional Certificate