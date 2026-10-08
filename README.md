## Aman Singh

I build AI agents and the backend infrastructure they run on.

Most of my recent work is on **agent harnesses**: the layer around a model that gives it tools, memory, playbooks, budgets and a safety boundary, so it can work on real systems without supervision going wrong. Before that, and alongside it, I build distributed backends in Go and Python.

### Currently building

**[sre-agent](https://github.com/DevloperAmanSingh/sre-agent)** · An agent harness for incident investigation. It reads Kubernetes and other systems through pluggable connectors, follows markdown playbooks, and explains the root cause. Incident memory is in progress. A strict read-only lock means it never changes anything.

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [quantcell](https://github.com/DevloperAmanSingh/quantcell) | Multi-agent platform for financial research and trading. Agents run as independent A2A services, the planner pauses for human approval, and research is grounded in SEC filings | Python, LangGraph, A2A, LanceDB |
| [atlas](https://github.com/DevloperAmanSingh/atlas) | Self-learning text-to-SQL agent that grounds queries in schema, business rules and past fixes, and runs only read-only SQL | Python, FastAPI, pgvector |
| [open-research](https://github.com/DevloperAmanSingh/open-research) | RAG over research papers that answers with page-located citations and scores its own faithfulness. A knowledge-graph retrieval path is in progress | Python, Qdrant, Neo4j, LangGraph |
| [ReviewBot](https://github.com/DevloperAmanSingh/ReviewBot) | GitHub App that reviews pull requests with an LLM and comments issues by severity | Python, FastAPI |
| [watcher](https://github.com/DevloperAmanSingh/watcher) | Distributed HTTP uptime monitoring engine with worker pools and event-driven alerting | Go, TimescaleDB |
| [waspdb](https://github.com/DevloperAmanSingh/waspdb) | Vector database built from first principles, for learning how similarity search works | Python, FastAPI |

### What I care about

- **Agents that are safe by construction.** Permissions, read-only locks and hard budgets enforced in code, not in the prompt.
- **Grounded answers.** Every conclusion should point to the evidence it came from.
- **Small, boring infrastructure.** Fewer moving parts, clear failure modes, deadlines on everything.

### Open source

- **[OpenCut](https://github.com/OpenCut-app/OpenCut)** · Split and cut, multi-file upload and global mute for the web-based video editor

### Tools I use most

Python · Go · TypeScript · LangGraph · deepagents · LiteLLM · PostgreSQL · Redis · Kafka · Docker · Kubernetes · AWS

### Contact

[amansinghneh211205@gmail.com](mailto:amansinghneh211205@gmail.com)
