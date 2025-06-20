# DataSage

[Click here to see the prototype](https://arthurgab03.github.io/project-datasage/)

---

## 🚀 Objective
**DataSage** turns raw, unstructured documents into reliable answers by applying semantic‑aware chunking and Retrieval‑Augmented Generation (RAG). It closes the gap between messy data and production‑ready AI features.

## 🌟 Vision
*Empower every team to unlock insight from any document—fast, accurately, and without ML PhDs.*

## 🔑 Key Features
| Category | Description |
| --- | --- |
| **Adaptive Chunking** | Dynamically splits content by semantic cohesion, not fixed pages or token counts. |
| **Metadata‑Rich Index** | Stores headings, hierarchy, and positions to maintain full context during retrieval. |
| **Vector Search** | Uses OpenAI embeddings + Azure AI Search for sub‑second, high‑relevance look‑ups. |
| **Self‑Optimizing Agent** | Evaluates answer quality and auto‑tunes chunk size & overlap—no manual labeling required. |
| **Plug‑and‑Play API** | Simple REST endpoints for ingesting docs and asking questions. |
| **Dashboard** | Streamlit UI to visualize chunks, embeddings, and evaluation metrics. |

## 🛠️ Core Technologies
- **Azure Blob Storage & Data Factory** – scalable ingestion pipeline  
- **Azure Document Intelligence** – layout & OCR parsing  
- **OpenAI Embeddings & GPT‑4o** – semantic search + generation  
- **LangChain / FastAPI** – orchestration & API  
- **Streamlit** – live monitoring dashboard

## 📐 Architecture (High‑Level)
