# ⚖️ CLAUSE | AI Legal Safety Gauge
**Foundry Project 1/6 by [Babylon Technologies](https://nehemiah.is-a.dev)**

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Groq Llama-3](https://img.shields.io/badge/AI-Llama--3%20(Groq)-orange)](https://groq.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🏛️ The Problem
Terms of Service (ToS) are intentionally designed to be unreadable. Most consumers unknowingly sign away class-action rights, data ownership, and privacy. **CLAUSE** uses agentic AI and mathematical benchmarking to scan these "legal traps" in under 2 seconds.

## 🛠️ The Tech Stack
- **Engine:** Python 3.10
- **Intelligence:** Groq Llama-3-70B (Low-latency inference)
- **Data Science:** `scikit-learn` (Cosine Similarity benchmarking)
- **Database:** Supabase (Postgres) for scan history & relational mapping
- **Frontend:** Streamlit + PWA wrapper

## 📊 The "Scam Score" Logic
Unlike generic AI, CLAUSE uses a dual-layer validation system:
1. **Semantic Search:** Vectorizing the uploaded contract against a "Fair-Standard" dataset using **Cosine Similarity**.
2. **Heuristic Analysis:** TF-IDF keyword density check for aggressive arbitration and data-licensing language.

## 🚀 Quick Start
```bash
git clone [https://github.com/yourusername/clause.git](https://github.com/yourusername/clause.git)
pip install -r requirements.txt
streamlit run app.py
