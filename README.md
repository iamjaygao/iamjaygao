# Jian (Jay) Gao

MS in Computer Science at Northeastern University. Research Assistant in the
Human-AI Nexus Group, working on LLM decision reliability. Before CS, I spent
seven years in automotive marketing analytics.

**Currently:** looking for Summer 2027 internships in software engineering, machine learning, and AI engineering.

**Interests:** LLM agents and evaluation, search and ranking, recommender systems.

### Research
- **When Hiring Becomes Agent-Mediated: Evaluating Access and Recurrence in Two-Agent Résumé Screening**  
  Jian Gao, Hang Jiang. REALM Workshop @ EMNLP 2026.  
  [Paper](https://aclanthology.org/2026.realm-1.44/) · [Project page](https://iamjaygao.github.io/agent-mediated-hiring/)  
  Two screening procedures can advance similar numbers of applications, but not the same applications.
- Reviewer, REALM Workshop @ EMNLP 2026

### Projects
- **[multilingual-product-ranking](https://github.com/iamjaygao/multilingual-product-ranking)**: audited Amazon's ESCI ranking benchmark (found swapped relevance gains in the official evaluation script) and trained a multilingual cross-encoder reranker. NDCG@20 0.856 vs. 0.835 for my reproduction of the official baseline on the US like-for-like slice.
- **[docs-cite-mcp](https://github.com/iamjaygao/docs-cite-mcp)**: MCP server that searches markdown docs and returns file path and line span with every result. Document Recall@5 0.76 on the repo's public 28-query benchmark.
- **[Multi-Stage-Recommendation-Ranking-Pipeline](https://github.com/iamjaygao/Multi-Stage-Recommendation-Ranking-Pipeline)**: ItemCF + Two-Tower retrieval, DeepFM/DIN ranking, MMR reranking on 15.47M interactions. DIN lifts NDCG@10 from 0.3981 to 0.4421 over DeepFM on the same features (sampled-negative evaluation).
- **CareerBridge** (private; code available on request): full-stack career platform (Django REST, PostgreSQL, Redis, Celery, Docker, React) with booking-slot locking enforced by PostgreSQL constraints.

### Open source
- [amazon-science/esci-data #26](https://github.com/amazon-science/esci-data/pull/26): fix for swapped Substitute/Complement relevance gains in the evaluation script ([minimal reproduction](https://github.com/iamjaygao/esci-gain-mapping-repro))

### Tools
**ML:** Python · PyTorch · Hugging Face Transformers · sentence-transformers · scikit-learn · LightGBM · FAISS · NumPy · pandas  
**Backend:** Django · PostgreSQL · Redis · Celery · Docker · React

### Contact
[LinkedIn](https://linkedin.com/in/iamjaygao)
