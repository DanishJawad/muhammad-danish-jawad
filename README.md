# Hi, I'm Danish

Software Engineering student at COMSATS University Lahore (7th semester). I build Python backends and LLM applications: FastAPI services, RAG pipelines and LangChain agents.

Open to AI engineering and backend internships, and freelance work.

## Projects

**[Aerofare](https://github.com/DanishJawad/aerofare)**: full-stack flight booking app, built during my internship at NETSOL Technologies and extended after it.

Row-level locking prevents overbooking (tested by racing two users for the last seat), JWT logout revocation through Redis, and 246 tests running in CI against real MySQL and Redis. A composite index cut rows examined per route search from about 6,700 to under 70 on 200,000 seeded flights, measured with a committed benchmark.

`FastAPI` `SQLAlchemy` `MySQL` `Redis` `Celery` `Docker` `React` `TypeScript`

**[RAG System](https://github.com/DanishJawad/rag-system)**: question answering over a corpus of 7 research papers.

A LangGraph router decides per query whether to retrieve or answer directly, conversation memory handles follow-ups, and a three-layer hallucination guard suppresses citations when the model refuses.

`LangGraph` `LangChain` `Ollama` `Chroma` `Streamlit`

**[Deal Hunter](https://github.com/DanishJawad/deal-hunter)**: live PC game prices and similar-game discovery.

Pulls prices from the CheapShark API and searches a 422-game catalog with local embeddings. The LLM's explanations only discuss games that were actually retrieved. Runs fully local, with no cloud API costs.

`LangChain` `Ollama` `Chroma` `Streamlit`

**[Fraud Detection](https://github.com/DanishJawad/fraud-detection)**: classification on 284,807 credit card transactions with a 578:1 class imbalance.

RandomForest with SMOTE and a chronological split: 73.3% recall, 93.2% precision, ROC-AUC 0.967. I audited the pipeline for data leakage and moved threshold selection to a separate validation split, so the reported numbers come from a test set scored once.

`scikit-learn` `SMOTE` `FastAPI` `Docker`

## Stack

- **LLM:** LangChain, LangGraph, Ollama, Chroma, RAG, agents and tool calling
- **Backend:** Python, FastAPI, SQLAlchemy, Alembic, Celery, REST APIs
- **Data:** MySQL, Redis, SQL Server
- **Tools:** Git, GitHub Actions, Docker, pytest
- **Also:** React, TypeScript, Java, C

## Contact

m.danishjawad@gmail.com · [LinkedIn](https://linkedin.com/in/muhammad-danish-jawad)
