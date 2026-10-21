# Hi, I'm Palak Bhati

**AI Engineer & Python Developer** | GenAI, RAG, Agents · Django, FastAPI, PostgreSQL | Open-source contributor (Sugar Labs, Kubeflow) | Indore, India

I build two kinds of things in Python: **LLM applications** that are meant to run in production (access-controlled retrieval, guardrails, evaluation in CI, cost tracking), and **backend web apps** with role-based access, PostgreSQL, Pytest suites and Docker deploys on Google Cloud Run.

[Portfolio](https://palakbuilds-portfolio.netlify.app) | [LinkedIn](https://linkedin.com/in/palakbhati) | [Email](mailto:palakbhati7488@gmail.com)

**Open to:** AI Engineer, GenAI Engineer, Python Developer and Backend Developer internship roles. Available now.

---

## AI & LLM projects

| Project | What it shows | Live |
| --- | --- | --- |
| [secure-rag-rbac-chatbot](https://github.com/palakbhati/secure-rag-rbac-chatbot) | RAG with role-based access enforced inside the vector store (Qdrant payload filters), two-layer prompt-injection guardrails, PII redaction, Ragas evaluation that blocks PRs in CI, LangSmith tracing, per-request cost tracking | [Demo](https://secure-rag-rbac-chatbot-534831126239.asia-south1.run.app/) |
| [nlp-log-classification](https://github.com/palakbhati/nlp-log-classification) | Hybrid classifier that routes each log to regex, MiniLM embeddings + Logistic Regression (99% accuracy on held-out data), or an LLM fallback; DBSCAN clustering to find regex patterns; FastAPI on Cloud Run | [API docs](https://log-classifier-534831126239.asia-south1.run.app/docs) |

## Python backend projects

| Project | What it shows | Live |
| --- | --- | --- |
| [job-portal](https://github.com/palakbhati/job-portal) | Django job board with employer and job-seeker roles, paginated search, permission-checked resume downloads, 74 Pytest tests; Docker on Cloud Run with PostgreSQL, Cloud Storage and Secret Manager | [Demo](https://jobportal-534831126239.us-central1.run.app/) |
| [ecommerce-django-react](https://github.com/palakbhati/ecommerce-django-react) | Django REST Framework API + React store: JWT auth with automatic token refresh, per-user cart and order endpoints, checkout in one database transaction | [Demo](https://ecommerce-django-react-xi.vercel.app/) |

## Open source

- **Sugar Labs / Music Blocks:** [#7876](https://github.com/sugarlabs/musicblocks/pull/7876) (merged) centralized the camera interval and listener lifecycle, fixed a capture bug found during manual testing, added 12 unit tests
- **Sugar Labs / Music Blocks:** [#7899](https://github.com/sugarlabs/musicblocks/pull/7899) (in review) fixed a file picker blocked by Chrome's user-activation rules
- **DBpedia / Databus:** [#268](https://github.com/dbpedia/databus/pull/268) (in review) shows file sizes in binary units (GiB/MiB/KiB)
- **Kubeflow Pipelines:** PRs to the Python SDK and backend: urllib3 CVE fix ([#14723](https://github.com/kubeflow/pipelines/pull/14723)), idempotent context creation ([#13721](https://github.com/kubeflow/pipelines/pull/13721)), page-token rolling-upgrade compatibility ([#13925](https://github.com/kubeflow/pipelines/pull/13925))

## Tech I use

- **LLM and agents:** LangChain, LangGraph, LangSmith, Groq, Gemini, Mistral, Ollama, Whisper, MCP
- **Retrieval and eval:** Qdrant, ChromaDB, FAISS, Sentence-Transformers, Docling, Ragas
- **ML and NLP:** scikit-learn, Hugging Face Transformers, pandas, NumPy
- **Backend:** Python, Django, Django REST Framework, FastAPI, Flask, Pydantic, PostgreSQL, REST APIs, JWT auth
- **Testing and deploy:** Pytest, Docker, GitHub Actions, Google Cloud Run, Cloud Storage, Vercel, Render
- **Also:** SQL, JavaScript, React, Tailwind CSS, Git, Linux
