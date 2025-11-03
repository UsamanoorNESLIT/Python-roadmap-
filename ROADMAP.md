# ROADMAP: Become a Well-Rounded Python Developer

_A practical 12-week learning roadmap + detailed study plan, with curated resources and hands-on checkpoints. Follow sequentially or adapt to your schedule._

---

## Overview

This roadmap covers:

- **Core Python** and software engineering fundamentals  
- **Web APIs** with **FastAPI**  
- **Databases & ORM** with **SQLAlchemy** / **Postgres**  
- **LLM engineering** using **LangChain**  
- **Machine Learning / Deep Learning** with **TensorFlow**  
- **Computer Vision** with **OpenCV**  
- **Engineering skills**: testing, CI/CD, Docker, Git, and deployment

Each section contains: purpose, curated resources (docs/repos/lectures), hands-on exercises, and project suggestions. The 12-week schedule below breaks this into weekly objectives and deliverables with checkpoints.

---

## Table of Contents

1. [Foundations — Core Python & Computer Science](#foundations)  
2. [Version Control & Best Practices](#version-control)  
3. [Web APIs — FastAPI](#fastapi)  
4. [Databases & ORM — SQLAlchemy / Postgres](#sqlalchemy)  
5. [Large Language Model Engineering — LangChain](#langchain)  
6. [Machine Learning & Deep Learning — TensorFlow](#tensorflow)  
7. [Computer Vision — OpenCV](#opencv)  
8. [Testing, Tooling & DevOps](#testing-devops)  
9. [Capstone Projects & Portfolio](#capstone)  
10. [12-Week Study Schedule & Weekly Checkpoints](#12-week-schedule)  
11. [How to Read Repos & Study Advice](#how-to-read)

---

## 1) Foundations — Core Python & Computer Science <a name="foundations"></a>

**Purpose:** Build fluency in Python syntax, idioms, data structures, algorithms, and problem solving — the foundation for backend, ML, and systems work.

**Primary resources**
- Python tutorial (official) — https://docs.python.org/3/tutorial/  
- Automate the Boring Stuff — https://automatetheboringstuff.com/  
- MIT 6.0001 — https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/  
- Real Python (articles & example repos) — https://github.com/realpython

**What to practice**
- Core language constructs, comprehension, context managers, iterators, generators.  
- Implement basic data structures from scratch (linked list, stack, queue, binary tree).  
- Solve algorithmic problems (sorting, search, recursion, dynamic programming) — 50 problems across difficulty.

**Mini projects**
- CLI tools: file organizer, CSV merger, log analyzer.  
- Build a small test harness using `pytest`.

---

## 2) Version Control & Best Practices <a name="version-control"></a>

**Purpose:** Master Git workflows, branching, pull requests, and the developer collaboration cycle.

**Resources**
- Real Python Git & GitHub guides — https://realpython.com/learn/git/  

**Practice**
- Create a clean repo for each project with README, CONTRIBUTING, LICENSE.  
- Use GitHub Actions: run tests and lint on PRs.

---

## 3) Web APIs — FastAPI <a name="fastapi"></a>

**Purpose:** Build performant, typed REST APIs and microservices; understand dependency injection, auth, and async endpoints.

**Primary resources**
- FastAPI tutorial — https://fastapi.tiangolo.com/tutorial/  
- full-stack-fastapi-template — https://github.com/tiangolo/full-stack-fastapi-template  
- FastAPI GitHub — https://github.com/fastapi/fastapi

**Practice**
- Build CRUD APIs with Pydantic models and OpenAPI docs.  
- Add JWT auth, role-based access, background tasks, and file uploads.  
- Containerize with Docker and docker-compose.

**Mini project**
- Task manager API with user auth, attachments, and pagination.

---

## 4) Databases & ORM — SQLAlchemy / Postgres <a name="sqlalchemy"></a>

**Purpose:** Model data relationally, run efficient queries, handle migrations, relationships, and transactions.

**Primary resources**
- SQLAlchemy tutorial — https://docs.sqlalchemy.org/tutorial/  
- SQLAlchemy GitHub — https://github.com/sqlalchemy/sqlalchemy

**Practice**
- Design relational schema (Contacts, Companies, Notes) with constraints and relations.  
- Use Alembic for migrations.  
- Add async DB support and optimize queries with indices.

---

## 5) Large Language Model Engineering — LangChain <a name="langchain"></a>

**Purpose:** Learn retrieval-augmented generation (RAG), chains, agents, memory, and integrating LLMs into apps.

**Primary resources**
- LangChain GitHub — https://github.com/langchain-ai/langchain  
- LangChain docs — https://docs.langchain.com/

**Practice**
- Prompt engineering fundamentals.  
- Build a simple RAG Q&A with document loaders + vector store (e.g., pgvector or FAISS).  
- Implement an agent that calls external tools / Python functions.

**Mini project**
- Knowledge base assistant that ingests docs and answers with citations.

---

## 6) Machine Learning & Deep Learning — TensorFlow <a name="tensorflow"></a>

**Purpose:** Learn model training, evaluation, and serving; build pipelines and integrate models with services.

**Primary resources**
- TensorFlow tutorials — https://www.tensorflow.org/tutorials  
- TensorFlow Models (Model Garden) — https://github.com/tensorflow/models

**Practice**
- Implement models with Keras (classification, transfer learning).  
- Export SavedModel and serve via a FastAPI prediction endpoint.

**Mini project**
- Image classifier on CIFAR-10, endpoint for predictions, and demonstration notebook.

---

## 7) Computer Vision — OpenCV <a name="opencv"></a>

**Purpose:** Image/video preprocessing, detection, tracking, and building vision pipelines for ML.

**Primary resources**
- OpenCV Python tutorials — https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html  
- CS231n (vision + CNNs) — http://cs231n.stanford.edu/

**Practice**
- Build webcam face detector & tracker + simple classifier.  
- OCR pipeline and preprocessing workflows.

---

## 8) Testing, Tooling & DevOps <a name="testing-devops"></a>

**Purpose:** Ensure software quality, reproducible environments, CI/CD, and deployable artifacts (Docker images).

**Primary resources**
- pytest docs — https://pytest.org/  
- GitHub Actions docs — https://docs.github.com/en/actions

**Checklist**
- Unit & integration tests, linting (ruff/flake8), CI jobs, Dockerfiles, docker-compose for local dev.

---

## 9) Capstone Projects & Portfolio <a name="capstone"></a>

**Suggested capstones**
1. **Full-stack Product**: FastAPI + SQLAlchemy + Postgres + React; deploy via Docker to a VM or cloud. (Start from the full-stack-fastapi-template.)  
2. **LLM Assistant**: LangChain + vector DB + FastAPI + minimal frontend.  
3. **Vision Product**: OpenCV + TensorFlow classifier, deployed as service with container.

**Portfolio tips**
- Provide README, architecture diagram, tests, CI, deployment steps, and a short demo/GIF.

---

## 10) 12-Week Study Schedule & Weekly Checkpoints <a name="12-week-schedule"></a>

**Notes on pacing:** Target ~10–15 hours per week (adjust to your availability). Each week has objectives, resources, a hands-on assignment, and a checkpoint deliverable.

### Week 1 — Python fundamentals & environment (10–15 hrs)
**Objectives**
- Python syntax, virtualenv, package management, and basic I/O.  
- Understand data types, control flow, functions, and modules.

**Resources**
- Python tutorial (official), Automate the Boring Stuff (first 6 chapters).

**Assignment**
- Solve 15 beginner Python exercises (e.g., from Exercism / HackerRank).  
- Build a CLI script: `csv-summary` that summarizes CSV files (rows, columns, nulls).

**Checkpoint (deliverable)**
- Repository `week-1-python-fundamentals`: README + `csv-summary` script + 10 tests.

---

### Week 2 — Data Structures, OOP & Testing (10–15 hrs)
**Objectives**
- Implement key data structures. Learn object-oriented design and `pytest`.

**Resources**
- MIT 6.0001 lectures (selected), pytest docs.

**Assignment**
- Implement stack, queue, binary tree; write unit tests covering edge cases.

**Checkpoint**
- Repo `week-2-ds-oop`: implementations + test suite; CI configured to run tests.

---

### Week 3 — Git, GitHub & Project Setup (8–12 hrs)
**Objectives**
- Git workflows, branching, PRs, GitHub Actions basics, project scaffolding.

**Resources**
- Real Python Git tutorials; GitHub Actions docs.

**Assignment**
- Create a template repo (README, LICENSE, CONTRIBUTING, basic CI for tests & lint).

**Checkpoint**
- `dev-template` repo with CI that runs `pytest` and lint.

---

### Week 4 — FastAPI Basics & First API (12–16 hrs)
**Objectives**
- FastAPI fundamentals: endpoints, Pydantic models, request/response validation, docs.

**Resources**
- FastAPI tutorial.

**Assignment**
- Build a CRUD API for a Notes app with in-memory storage; include OpenAPI docs.

**Checkpoint**
- `notes-api` repo with running instructions and basic tests.

---

### Week 5 — Databases & SQLAlchemy Integration (12–16 hrs)
**Objectives**
- Learn SQLAlchemy ORM, migrations (Alembic), and integrate Postgres via Docker.

**Resources**
- SQLAlchemy tutorial; full-stack-fastapi-template examples.

**Assignment**
- Convert Notes app to use Postgres + SQLAlchemy models + Alembic migrations.

**Checkpoint**
- `notes-api` updated: Docker compose for Postgres, migrations, sample data, and tests.

---

### Week 6 — Auth, File Uploads, and Deployment Basics (12–16 hrs)
**Objectives**
- Implement JWT authentication, file uploads, background tasks; containerize app.

**Resources**
- FastAPI docs (security, background tasks).

**Assignment**
- Add user auth to `notes-api`, protect endpoints by user, add file attachments storage, add Dockerfile.

**Checkpoint**
- `notes-api` deployed locally via Docker compose; documented runbook.

---

### Week 7 — LangChain & LLM Basics (12–16 hrs)
**Objectives**
- Learn prompt engineering, simple chains, and document loaders.

**Resources**
- LangChain docs and examples.

**Assignment**
- Build a small RAG prototype: ingest markdown docs, build vector store, simple query endpoint.

**Checkpoint**
- `rag-prototype` repo with ingestion scripts, vector DB (local), and API demo.

---

### Week 8 — LangChain Agents & Integrations (12–16 hrs)
**Objectives**
- Advanced LangChain: agents, tool integration, memory.

**Resources**
- LangChain advanced examples and agents docs.

**Assignment**
- Add an agent that can call simple external tools (HTTP or local Python function) to enrich answers.

**Checkpoint**
- `rag-prototype` updated with agent + tests and demo notebook.

---

### Week 9 — TensorFlow Fundamentals (12–16 hrs)
**Objectives**
- ML fundamentals, Keras API, training loops, and evaluation.

**Resources**
- TensorFlow tutorials (classification, transfer learning).

**Assignment**
- Train a simple image classifier (e.g., on CIFAR-10 or subset), evaluate metrics, and save the model.

**Checkpoint**
- `tf-cifar` repo with training notebook, model artifacts, and test inference script.

---

### Week 10 — Model Serving & Integration with FastAPI (12–16 hrs)
**Objectives**
- Serve models using FastAPI, write prediction endpoints, and package models for deployment.

**Resources**
- TensorFlow serving docs / FastAPI integration guides.

**Assignment**
- Create a `predict` endpoint that loads the trained model and returns predictions for images.

**Checkpoint**
- `tf-service` repo with Dockerfile and tests for prediction endpoint.

---

### Week 11 — OpenCV & Vision Pipelines (12–16 hrs)
**Objectives**
- Image preprocessing, detection, simple tracking with OpenCV; combine with TF model.

**Resources**
- OpenCV tutorials, CS231n resources.

**Assignment**
- Build a webcam demo: detect faces, preprocess frames, classify using your TF model, and log results.

**Checkpoint**
- `vision-demo` repo with demo script, README, and video/GIF showing results.

---

### Week 12 — Capstone Integration & Portfolio Polish (15+ hrs)
**Objectives**
- Integrate components into a capstone project (choose from suggested capstones), add CI, documentation, and deployment.

**Assignment**
- Finalize capstone: full README, architecture diagram, CI, tests, and demo assets (video/GIF).

**Checkpoint (deliverable)**
- `capstone` repo: public GitHub repo with complete docs, deployed demo (or clear deployment steps), and a 3–5 minute demo recording.

---

## 11) How to Read Repos & Study Advice <a name="how-to-read"></a>

- Start with `README.md` → `docs/` → `examples/`. Run the project locally and step through code while debugging.  
- Replace small parts (swap DB, add a feature) — experimentation accelerates learning.  
- Keep a learning journal: commit notes and short explanations to each repo's `NOTES.md`.

---

## Quick Reference Links (copy/paste friendly)

- Python tutorial — https://docs.python.org/3/tutorial/  
- Automate the Boring Stuff — https://automatetheboringstuff.com/  
- MIT OCW 6.0001 — https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/  
- full-stack-fastapi-template — https://github.com/tiangolo/full-stack-fastapi-template  
- FastAPI docs — https://fastapi.tiangolo.com/tutorial/  
- SQLAlchemy docs — https://docs.sqlalchemy.org/tutorial/  
- LangChain — https://github.com/langchain-ai/langchain  
- LangChain docs — https://docs.langchain.com/  
- TensorFlow tutorials — https://www.tensorflow.org/tutorials  
- OpenCV Python tutorials — https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html  
- pytest — https://pytest.org/

---

## Final notes

- Keep projects small and frequent. Prefer many small wins over infrequent huge leaps.  
- Use the schedule as a flexible guide — adapt weeks to your cadence.  
- If you'd like, I can:
  - Generate the GitHub repo templates for each week's checkpoint (boilerplate files, CI config).  
  - Create a calendar (Google Calendar / ICS) with the 12-week schedule.  
  - Create checkpoint PR templates and grading rubric for self-evaluation.

---

**End of ROADMAP.md**
