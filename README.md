# Cem Yıldız

Undergraduate studying Mathematics & Computer Science at Eskişehir Osmangazi University.  
Working at the intersection of applied probability, machine learning systems, and systems-level tooling.

I focus on writing deterministic, leak-free statistical models and resilient production backends.

[Website](https://cemyildiz.net) · [LinkedIn](https://linkedin.com/in/cemyildizcy) · [Email](mailto:cemyildizcy@hotmail.com)

---

### Selected Engineering & Research

- **[wc2026-ai-simulator](https://github.com/cemyildizcy/wc2026-ai-simulator)**  
  Monte Carlo tournament forecaster using bivariate Poisson distributions and multi-source feature ensembles. Built with Streamlit for interactive scenario exploration.

- **[CemByeDPI](https://github.com/cemyildizcy/CemByeDPI)**  
  Low-level TCP/TLS handshake fragmentation utility on Windows via WinDivert. Intercepts and reshapes packets at the network layer to bypass deep packet inspection.

- **[uyku-sagligi-tahmincisi](https://github.com/cemyildizcy/uyku-sagligi-tahmincisi)**  
  Sleep disorder risk classification service using leakage-free XGBoost with FastAPI, coupled with structured LLM recommendations.

- **[turkey-earthquake-risk-analysis](https://github.com/cemyildizcy/turkey-earthquake-risk-analysis)**  
  Geospatial clustering and recurrence analysis on historical seismic event logs retrieved from USGS APIs.

---

### Focus & Tooling

```text
Foundations   :: Applied Probability, Linear Algebra, Discrete Math
Modeling      :: XGBoost, Scikit-learn, SciPy, Pandas, NumPy
Systems & Web :: Python (FastAPI), TypeScript, Next.js, Cloudflare Workers
Data & Ops    :: PostgreSQL, Supabase, SQLite, Git, Linux
```

---

### Principles

- **No data leakage:** Preprocessing and transformations strictly fit on training splits.
- **Deterministic by default:** Seeded RNGs, benchmarked baselines, explicit assumptions.
- **Verify before shipping:** Comprehensive unit tests over raw intuition.
