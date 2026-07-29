# Dushyant Singh Pawar

**Full-stack software engineer** building systems that survive real usage.

I design software where correctness matters. Multi-tenant architectures, proper auth boundaries, schema evolution, event-driven pipelines, and ML integrated into products instead of notebooks.

The gap between it works in dev and it works at scale is where I focus.

---

## Philosophy

I don't believe in:

- Prototypes without a migration strategy
- ML notebooks shipped as "production"
- APIs without contracts or access boundaries
- Data systems without ownership semantics

I build for:

- Reliability and observability
- Schema evolution and long-lived systems
- Multi-tenant isolation and RBAC
- Deployable, testable services
- Predictable APIs that don't surprise you at 2 AM

---

## Featured Work

### [MedKids OrderUp](https://github.com/dushyantsinghpawar/medkids-orderup-backend)

MVP replica of the MedKids OrderUp production backend, built to demo the system to clients and stakeholders. Manages children's profiles, dietary preferences, and allergies. Full production context is in the repo README.

Why it matters: Multi-tenant data systems are hard. This shows how to isolate user data, enforce access boundaries, and keep schemas safe across migrations.

Tech: `FastAPI`, `PostgreSQL`, `SQLAlchemy`, `Alembic`, `JWT`, `RBAC`, `Docker`, `Railway`

---

### [QuickAPI](https://github.com/dushyantsinghpawar/quickapi)

Reusable backend service template. How I start every API project.

Why it matters: I don't write one-off scripts. This is my template for service structure: clean separation, proper logging, testable layers, deployment-ready from day one.

Tech: `FastAPI`, `SQLAlchemy`, `PostgreSQL`, `Pydantic`, `Docker`, `pytest`

---

### [SupportAI](https://github.com/dushyantsinghpawar/supportai)

Hybrid RAG retrieval system over 1,000+ academic papers. FAISS vector search plus BM25 keyword matching, re-ranked with a cross-encoder. Every answer cites its source.

Why it matters: Retrieval quality is what separates useful RAG from confident nonsense. Combining dense and sparse retrieval with reranking gets answers right, and citation-backed responses keep them verifiable. Built during my MS research assistantship at UNC Charlotte.

Tech: `FAISS`, `BM25`, `SentenceTransformers`, `Cross-encoder Reranking`, `FastAPI`, `Python`

---

### [LSTM Forecasting Service](https://github.com/dushyantsinghpawar/lstm-stock-predictor)

End-to-end time-series prediction pipeline. Deterministic training and inference.

Why it matters: ML only matters when it's reproducible, versioned, and deployable. This is a service with proper model versioning, input validation, and inference guarantees. Not a Jupyter notebook.

Tech: `TensorFlow`, `PyTorch`, `scikit-learn`, `FastAPI`, `MLflow`, `PostgreSQL`, `Docker`

---

## What Interests Me

Systems architecture and distributed service design. Event-driven processing. Data pipelines and ETL.

Schema design and database evolution. Multi-tenancy patterns. Query optimization.

ML that actually works in production. Model versioning. Feature engineering pipelines.

API design and contracts. Authentication and authorization. Database safety. Service orchestration.

---

## Background

Software Engineer at a stealth startup, building a real-time computer-vision fitness product.

Previously: Software Engineer at Rebecca Everlene Trust Company. MS Computer Science, UNC Charlotte. Earlier roles as Software Developer and Systems Engineer.

---

## Contact

- Email: dushyantsinghpawar@gmail.com
- LinkedIn: https://www.linkedin.com/in/dushyantsinghpawar/
- Portfolio: https://dushyantsinghpawar.github.io/Portfolio/

---

I'm interested in full-stack and backend engineering roles, AI-powered products, and talking about how to move software from prototype to something reliable.
