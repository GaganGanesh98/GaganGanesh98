# Hi, I'm Gagan

Applied AI Engineer building LLM agents, retrieval systems, and the evaluation harnesses that say whether they actually work.

- Built an **AI agent governance platform** — [Grace](https://github.com/GaganGanesh98/Grace) — shipping an **MCP tool-calling server**, WebSocket transport, signed execution receipts and a Merkle audit chain on FastAPI + Next.js + Postgres + Redis. 939 test functions across 165 files, with CodeQL, Trivy, gitleaks and TruffleHog wired into CI.
- Deep on **RAG and retrieval** — self-corrective **LangGraph** agents with article-level citations ([german-compliance-agent](https://github.com/GaganGanesh98/german-compliance-agent)), and hybrid BM25+vector, **GraphRAG/Neo4j** and Atlas vector search compared on one corpus ([Trinity](https://github.com/GaganGanesh98/Trinity)).
- **Evaluation-first**: I build the eval before the claim, pre-register hypotheses, and publish negative results. Three of my repos report numbers that did *not* go my way.
- Backend-first: **Python, FastAPI, SQLAlchemy** — plus Docker, Terraform, GitHub Actions, GCP Cloud Run.
- **M.Sc. Artificial Intelligence & Machine Learning**, SRH Berlin — thesis on effort gaps in compressed LLMs (pre-registered, [ActFloor](https://github.com/GaganGanesh98/ActFloor)).
- Previously **Technical Analyst at Oracle India** (2+ years).
- Based in Berlin.

## A few projects

- [**SlopCheck**](https://github.com/GaganGanesh98/SlopCheck) — grounds AI-written vulnerability reports against the source tree they describe. Measured on 557 labelled curl reports: it contradicts **29.4% of confirmed** vulnerabilities, so it fails as a triage gate. Published as a negative result with a DOI and the corpus.
- [**Grace**](https://github.com/GaganGanesh98/Grace) — cryptographic governance receipts for AI agents: 6-stage governed execution, Ed25519 + ML-DSA-65 signing, RFC-6962 Merkle chain, MCP server.
- [**german-compliance-agent**](https://github.com/GaganGanesh98/german-compliance-agent) — LangGraph agent answering GDPR questions with citations, and auditing contracts against them. *(TODO: add citation-accuracy numbers over a labelled set.)*
- [**ActFloor**](https://github.com/GaganGanesh98/ActFloor) — pre-registered MSc thesis experiments on compression and effort gaps in LLMs, with the findings that failed to replicate written up alongside the ones that held.
- [**solar-forecast-de**](https://github.com/GaganGanesh98/solar-forecast-de) — day-ahead solar forecasting for the German grid. 2.57% nMAE on a 25-day walk-forward backtest, and **−11.5% skill** against the TSO baseline on synthetic data, where that baseline is unrealistically strong.
- [**Trinity**](https://github.com/GaganGanesh98/Trinity) — one ENISA corpus, three retrieval backends, one harness. *(TODO: replace the saturated eval set before quoting a number.)*

Reach me: [LinkedIn](https://www.linkedin.com/in/gaganganesh-a132bb213)

<!-- Languages: English (fluent) · German (TODO — add your CEFR level, e.g. B1) -->
