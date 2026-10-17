# Vaijayanti Deshmukh
### AI/ML Engineer | RAG & Production AI Systems

Building AI for decisions that need evidence — investment memos, consumer text, and real-estate intelligence.

CS graduate and former software developer (2 years) with strong fundamentals in DSA and system design — now shipping production AI systems, not prompt demos.

**Currently:** seeking AI/ML engineer / FDE roles · building auditable RAG and agent systems for high-stakes decisions

[LinkedIn](https://www.linkedin.com/in/vaijayanti-deshmukh) · [Email](mailto:deshmukhvaijayanti5@gmail.com)

---

## How I build (not vibes)
- Treat LLM output as untrusted: ground claims, verify, then human-gate.
- Prefer measurable pipelines (fixtures, metrics, support rates) over demo prompts.
- Ship with APIs, queues, and Docker — not notebooks alone.
- Bring a CS + SWE foundation: data structures, system design, and production debugging habits.

---

## What I believe about production AI
- Retrieval quality matters more than model size in many RAG systems.
- Human review is often a feature, not a limitation.
- Explainability becomes essential in high-stakes domains.
- The hardest part of AI products is often the workflow around the model.

---

## Featured Projects

### [DMAG — Deal Memo Auto Generator](https://github.com/VJGit1/Deal-Memo-Auto-Generator) · Finance
> Agentic RAG pipeline that turns due diligence docs (10-Ks, CIMs, pitch decks) into structured, citation-backed investment memos.

**Proof:** 8-step pipeline · DOCX + citation appendix · HITL confidence gates  
**Impact:** Hours → minutes for memo drafting, with closed-book evidence gating  
**Stack:** Python · FastAPI · React · Redis/RQ · Docker · Chroma · BM25 · Pydantic · Gemini

### [Miami Condo GPT](https://github.com/VJGit1/Miami-Condo-GPT) · Real Estate
> LangGraph agent for Miami condo intelligence — natural language SQL, maps, charts, and PDF reports.

**Proof:** NL → SQL + RAG · AST SQL security gateway · tool guardrails  
**Impact:** Ambiguous questions → safe, executable data operations  
**Stack:** LangGraph · Flask · PostgreSQL · FAISS · OpenAI

### [Financial Complaint Classification (NLP)](https://github.com/VJGit1/NLP_Project) · NLP
> Compares Naive Bayes (TF-IDF) vs fine-tuned DistilBERT for multi-class CFPB complaint categorization.

**Proof:** Domain transformer fine-tune · imbalance-aware training · baseline vs transformer trade-offs  
**Impact:** Production-minded NLP with clear evaluation, not just model training  
**Stack:** PyTorch · DistilBERT · HuggingFace · FastAPI · React

---

## More work
- [Startup Scout](https://github.com/VJGit1/startup_scout) — AI agent that scouts and surfaces startup / opportunity signals from public sources
- [FIFA 2026 Tournament Simulator](https://github.com/VJGit1/FIFA-2026-World-Cup-Tournament-Simulator) — FastAPI + Next.js + scikit-learn pipeline
- [Bonsai Biome](https://bonsai-biome.vercel.app) (Private repo · live demo) — ML / AI project

---

## Tech Stack

**AI / Agents:** Python, LangGraph, LangChain, OpenAI, Gemini, RAG (hybrid retrieval), HuggingFace, PyTorch, Pydantic  
**Backend / APIs:** FastAPI, Flask, uvicorn, Redis, RQ (background jobs)  
**Data:** PostgreSQL, SQL, FAISS, Chroma, MongoDB, Neo4j  
**Frontend:** React, TypeScript, Vite, Next.js  
**Deploy / Ops:** Docker, Docker Compose, AWS (S3, EC2, Lambda), Azure, Vercel, Git  
**Eval / Quality:** pytest · offline LLM evals (gold fixtures) · claim grounding / LLM-as-judge · precision–recall on reconcile flags · HITL confidence gates · SQL/AST safety checks · schema validation (Pydantic)

---

## Education
MS in Data Science — George Washington University  
Bachelor's in Computer Science · Software Developer (2 years)
