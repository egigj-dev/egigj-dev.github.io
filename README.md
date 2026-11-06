<div align="center">

# Egi — systems, models & field notes

**Software engineering × applied machine learning × language systems**

*Tirana, Albania · Building things, testing assumptions, writing down what I learn.*

[Explore my field notebook](https://egigj-dev.github.io) · [ML blog](https://egigj-dev.github.io/my-blog/) · [Repositories](https://github.com/egigj-dev?tab=repositories)

</div>

---

### Hello, I'm Egi.

I'm interested in the part of AI engineering that happens *after* a promising notebook: making models understandable, connecting them to real software, and knowing when a simpler system is the better choice.

My interests move between **NLP and retrieval**, **recommendation and predictive modeling**, and the software and infrastructure that support them.

### A few things I've worked on

| Project | What it's about |
| :-- | :-- |
| [albanian-banking-assistant](https://github.com/egigj-dev/albanian-banking-assistant) | An Albanian-language assistant for banking regulations and bank rates. Rates come from structured tables, and every generated sentence is checked against its sources. |
| [TiranaTips](https://github.com/egigj-dev/TiranaTips) | A multilingual guide to Tirana: hybrid search over Qdrant, cross-encoder reranking, and streamed answers from a FastAPI app. Built with collaborators. |
| [real-estate](https://github.com/egigj-dev/real-estate) | A property-listing app for Tirana, using XGBoost price estimates and comparable listings to help put asking prices in context. Built with collaborators; my commits focus on the FastAPI backend. |
| [ML blog](https://egigj-dev.github.io/my-blog/) ([source](https://github.com/egigj-dev/my-blog)) | Interactive articles on deep learning fundamentals. |
| [credit-risk-platform](https://github.com/egigj-dev/credit-risk-platform) | Default-probability and early-warning scoring, next-best offers, an API, and a dashboard. A deterministic demo runs on generated clients with no database. |

### How I approach the work

`Question → Data → Baseline → Model → Evaluation → Integration → Iterate`

I care about good problem definitions, sensible metrics, understanding failure modes, and treating deployment and security as part of the engineering problem rather than an afterthought.

**Working vocabulary:** Python · Machine Learning · NLP · RAG · Vector Search · FastAPI · Docker · Cloud · Security

---

<div align="center">

**[Visit the more personal side →](https://egigj-dev.github.io)**

<sub>Less of a scoreboard, more of a working notebook.</sub>

</div>


### Portfolio content maintenance

The site links to public repositories and to the published blog at <https://egigj-dev.github.io/my-blog/>. Check that a repository is public before linking it; `notebooks` is private, so it isn't featured.

Before adding more detailed claims, verify:

- **TiranaTips:** supported languages and evaluation evidence. The default branch lags `mvp-hardening`.
- **real-estate:** evaluation dataset, split, baseline, and measured prediction errors.
- **credit-risk-platform:** model metrics. The demo uses generated clients, so it says nothing about model quality.
- **All projects:** personal contribution and project status, before adding role or maturity labels.
