# Hi, I'm José Miguel Gómez

Senior Software Engineer and AI Engineer based in Lima, Peru. I build AI agents and LLM-powered automation on top of solid backend engineering, and I take them to production.

- 6+ years building backend systems, including a platform with 500K+ users and 30M+ daily transactions.
- Designed an LLM automation pipeline that cut incident triage time by 92%, from 20 minutes to under 90 seconds.
- Currently pursuing an MS in Applied AI at Golden Gate University.

## Autonomous Software Factory

My main project. An autonomous factory that designs, builds, tests, audits and documents production-grade software overnight, while a human approves what gets built and reviews every pull request.

The models write and correct the code; a deterministic pipeline decides what is accepted, under a hard budget, with every token and dollar recorded.

- **263 projects delivered** as pull requests across four assembly lines.
- **82% delivered with no human fix** (249 of 304 started items). Every hand fix is recorded as an intervention and excluded from that rate.
- **Model-agnostic:** the same pipeline and gates run on Anthropic, Google Gemini, Vertex AI and DeepSeek, measured side by side. API cost starts at USD 0.11 per project.
- **Production quality gates on every project:** lint, types, tests with at least 80% coverage, documentation standard, secret scan, dependency audit, an independent specification audit, and CI on Linux and Windows.
- **A team of roles, not one prompt:** analyst, architect, generator, fixer, auditor, docs writer, security engineer and visual QA, plus deterministic planning, gates and publishing.

**See how it works and the measured results:** [live page](https://trysac.github.io/autonomous-software-factory/) · [showcase repo](https://github.com/Trysac/autonomous-software-factory)

The factory itself (source code, prompts, rules and operating data) is private. What you see here is what it has built.

## Bigger systems built by the factory

Where one generation is not enough, the factory's architect splits the work into modules with frozen interfaces and builds them in dependency order.

| Project | What it is |
|---|---|
| [u401-lsm-kv-engine](https://github.com/Trysac/u401-lsm-kv-engine) | LSM-tree key-value storage engine |
| [u402-linearizability-checker](https://github.com/Trysac/u402-linearizability-checker) | Checker for linearizability of concurrent histories |
| [u403-wasm-interpreter](https://github.com/Trysac/u403-wasm-interpreter) | WebAssembly interpreter |
| [u404-cdcl-sat-solver](https://github.com/Trysac/u404-cdcl-sat-solver) | CDCL SAT solver |
| [u405-crdt-json](https://github.com/Trysac/u405-crdt-json) | CRDT for collaborative JSON documents |
| [u406-linear-regex](https://github.com/Trysac/u406-linear-regex) | Linear-time regular expression engine |
| [u407-formula-engine](https://github.com/Trysac/u407-formula-engine) | Spreadsheet formula engine |
| [u408-datalog-engine](https://github.com/Trysac/u408-datalog-engine) | Datalog engine |
| [u409-columnar-sql-engine](https://github.com/Trysac/u409-columnar-sql-engine) | Columnar SQL engine |
| [u410-git-objects](https://github.com/Trysac/u410-git-objects) | Git object store |

**Unreal Engine agent toolsets** for the Unreal Engine 5.8 MCP server, delivered with no human fix: [asset intake](https://github.com/Trysac/u801-ue-asset-intake-toolset), [captures](https://github.com/Trysac/u802-ue-capture-toolset), [render profiles](https://github.com/Trysac/u803-ue-render-profiles-toolset) and [performance probes](https://github.com/Trysac/u804-ue-perf-probe-toolset).

**All delivered projects:** [browse the catalog](https://github.com/Trysac?tab=repositories&q=topic%3Aautonomous-software-factory)

## Tech I work with

**Languages:** Java, Go, Python, TypeScript, Rust
**AI and agents:** Anthropic, Gemini and Vertex AI, DeepSeek, OpenAI, LangGraph, CrewAI, RAG, tool calling, structured outputs, evals, MCP
**Backend and architecture:** Spring Boot, FastAPI, Node.js, microservices, Hexagonal Architecture, DDD, CQRS
**Data and cloud:** PostgreSQL, pgvector, Redis, AWS, Google Cloud, Azure, Docker, Kubernetes, GitHub Actions
**AI-assisted development:** Claude Code, Cursor, GitHub Copilot

## Get in touch

[LinkedIn](https://www.linkedin.com/in/jose-miguel-gomez-architect/) · [itch.io](https://trysac.itch.io/)

Open to remote roles and B2B contracts.
