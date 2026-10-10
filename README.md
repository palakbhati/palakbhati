# Hi, I'm Palak Bhati

**AI/ML Engineer (GenAI, RAG, Agents)** | Open-source contributor to Kubeflow and Sugar Labs | India

I build LLM applications that are meant to run in production, not just in a notebook: retrieval with access control, guardrails, evaluation in CI, cost tracking, and containerized deploys on Google Cloud Run.

[Portfolio](https://palakbuilds-portfolio.netlify.app) | [LinkedIn](https://linkedin.com/in/palakbhati) | [Email](mailto:palakbhati7488@gmail.com) | [Resume](Palak_resume.pdf)

**Open to:** AI/ML Engineer, GenAI Engineer and LLM Engineer roles (full-time or internship) starting October 2026.

---

## Featured projects

| Project | What it shows | Live |
| --- | --- | --- |
| [secure-rag-rbac-chatbot](https://github.com/palakbhati/secure-rag-rbac-chatbot) | Role-based access enforced inside the vector store (Qdrant payload filters), two-layer prompt-injection guardrails, PII redaction, Ragas evaluation that blocks PRs in CI, per-request cost tracking, Docker | [Demo](https://secure-rag-rbac-chatbot-534831126239.asia-south1.run.app/) |
| [nlp-log-classification](https://github.com/palakbhati/nlp-log-classification) | Hybrid classifier that routes each log to regex, embeddings + Logistic Regression, or an LLM fallback, served as a FastAPI service | [API docs](https://log-classifier-534831126239.asia-south1.run.app/docs) |
| [Blog-Writing-Agent](https://github.com/palakbhati/Blog-Writing-Agent) | LangGraph multi-agent pipeline: router, Tavily research, Pydantic-planned sections, parallel fan-out writers, cited Markdown output | |
| [ai-meeting-assistant](https://github.com/palakbhati/ai-meeting-assistant) | Local Whisper transcription, LCEL extraction of action items and decisions, chat-with-your-meeting RAG, English and Hinglish | |

## Open source

- **Sugar Labs / Music Blocks:** [#7876](https://github.com/sugarlabs/musicblocks/pull/7876) (merged) centralized the camera interval and listener lifecycle, fixed a capture bug found during manual testing, added 12 unit tests
- **Sugar Labs / Music Blocks:** [#7899](https://github.com/sugarlabs/musicblocks/pull/7899) fixed a file picker blocked by Chrome's user-activation rules (in review)
- **Kubeflow Pipelines:** work on the Python SDK and backend, including dependency security fixes and pagination token compatibility

## Tech I use

- **LLM and agents:** LangChain, LangGraph, LangSmith, Groq, Gemini, Mistral, Ollama, Whisper
- **Retrieval and eval:** Qdrant, ChromaDB, FAISS, Sentence-Transformers, Docling, Ragas
- **ML:** scikit-learn, pandas, NumPy
- **Backend and deploy:** Python, FastAPI, Streamlit, Pydantic, Docker, GitHub Actions, Google Cloud Run, pytest
