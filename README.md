### Hi there 👋, I'm Hamza Ouadid

I write about how modern LLM systems actually work, and ship them in production.

**[Theia](https://theia-ltd.com)** — a free, 34-chapter, 137,000-word course that takes a reader with no code and no math background to training a GPT from scratch and shipping the production system around it. Every claim in it was executed and verified before publication, and each chapter states plainly what a technique does *not* do. Ships with ARIA, an embedded LLM study assistant, and an annotated index of ~160 papers, courses, and tools.

---

**Currently:** AI Engineer at an enterprise health-tech SaaS company (confidential search), owning a retrieval platform end to end — ingestion, hybrid search API, Kubernetes deployment, and the on-call hardening afterward. Architected a complete knowledge-base platform from first commit to production in 5 weeks; 175 merge requests across 20 production codebases in 21 months.

**Recent work** — measured, not asserted; each ships with an eval harness and a committed baseline:

- 🔎 **[finco](https://github.com/HamzaOuadid/finco)** — hybrid BM25 + dense retrieval over SEC filings, +75% recall@5 over dense-only, reranked by a cross-encoder
- 📈 **[shopico](https://github.com/HamzaOuadid/shopico)** — Shopify demand forecasting where the promoted model has *worse* MAE than the baseline and still nets +$11,593 over a 12-week backtest, because the promotion gate scores dollars, not accuracy
- 🩺 **[mcp-health-coach](https://github.com/HamzaOuadid/mcp-health-coach)** — an MCP server, 31 wellness tools, every factual claim grounded in a verified public source (USDA, openFDA, MedlinePlus, PubMed) instead of model recall

- 💬 Ask me about retrieval failure modes, RAG evaluation, or the newsvendor problem
- 📫 hamzaouadid@gmail.com · [LinkedIn](https://linkedin.com/in/hamza-ouadid)

**Stack:** Python · RAG / hybrid retrieval / rank fusion · MCP server development · PostgreSQL + pgvector · Kubernetes · Docker · Dagster · dbt · Kafka · Spark · LightGBM · MLflow · PyTorch · FastAPI
