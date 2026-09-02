<div align="center">

# ZhongYu Li

### I build trustworthy AI infrastructure, developer tools, and quantitative systems.

`AI Infrastructure` · `Developer Experience` · `Data Systems` · `Quantitative Engineering`

</div>

I work at the boundary between AI infrastructure, backend and data systems, developer experience, and quantitative engineering. I care about the parts that make software trustworthy in practice: deterministic behavior, explicit contracts, inspectable evidence, useful failure messages, and honest performance boundaries.

My open-source work focuses on the infrastructure around AI agents—not another chat wrapper. I prefer narrow changes with a reproducible failure, focused regression coverage, and a result that another engineer can independently verify.

## Merged upstream contributions

Verifiable fixes accepted by maintainers of public upstream projects. Each entry links directly to the merge record.

| Upstream project | Contribution | Result |
| --- | --- | --- |
| **[THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)** | [#1296](https://github.com/THU-MAIC/OpenMAIC/pull/1296) enforced LF checkouts for text files on Windows without renormalizing existing source blobs. | Merged after fresh-checkout, formatting, lint, type-check, and CI validation |
| **[The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent)** | [#2922](https://github.com/The-PR-Agent/pr-agent/pull/2922) made GitLab webhook handling robust to explicit `null` labels and preserved later ignore-rule evaluation. | Merged after focused regression coverage and CI |
| **[The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent)** | [#2939](https://github.com/The-PR-Agent/pr-agent/pull/2939) normalized inverted line ranges consistently across GitHub, GitLab, and Gitea link builders. | Merged with provider regression coverage |

[View all authored pull requests](https://github.com/search?q=is%3Apr+author%3ARRXXZZYY&type=pullrequests)

## Engineering focus

- **AI infrastructure and agents:** traceability, provider normalization, reliable tool boundaries, and reproducible agent workflows.
- **Backend and data systems:** explicit contracts, compatibility, failure isolation, and tests that preserve production behavior.
- **Quantitative engineering:** evidence-first research, declared assumptions, realistic execution semantics, and clear simulation boundaries.
- **Delivery discipline:** focused pull requests, cross-platform CI, security scanning, and verification claims that match the evidence.

## Independent work

### QuantSieve

[![QuantSieve — pretty charts are not proof](https://raw.githubusercontent.com/RRXXZZYY/QuantSieve/main/docs/assets/social-preview.png)](https://github.com/RRXXZZYY/QuantSieve)

**Pretty charts are not proof.** [QuantSieve](https://github.com/RRXXZZYY/QuantSieve) is a self-hosted quantitative research workspace that keeps results traceable to data, timing, assumptions, costs, and execution semantics—and fails closed when evidence is insufficient.

[Explore the repository](https://github.com/RRXXZZYY/QuantSieve) · [Watch the 55-second product tour](https://github.com/RRXXZZYY/QuantSieve/releases/tag/v0.1.1)

### Focused developer tools

| Project | What it does | Engineering focus |
| --- | --- | --- |
| **[SpanLint](https://github.com/RRXXZZYY/spanlint)** | Lints OpenTelemetry GenAI and MCP traces with 21 deterministic rules and visual diagnostics. | Observability, policy engines, SARIF/JUnit, CI |
| **[AgentWhy](https://github.com/RRXXZZYY/agentwhy)** | Explains which coding-agent instructions apply, why they win, and where they conflict. | Developer tooling, provenance, static analysis |
| **[TraceVCR](https://github.com/RRXXZZYY/tracevcr)** | Records, redacts, replays, and visually diffs agent tool calls without model or API access. | Agent testing, reproducibility, typed diagnostics |
| **[BatchLab](https://github.com/RRXXZZYY/batchlab)** | Simulates static batching, continuous admission, KV budgets, TTFT, and tail latency. | Inference systems, discrete-event simulation |
| **[SchemaBlast](https://github.com/RRXXZZYY/schemablast)** | Finds data-contract breaks and traces their field-aware lineage blast radius to owners. | Data infrastructure, graph traversal, contract CI |
| **[QuantSieve](https://github.com/RRXXZZYY/QuantSieve)** | Runs evidence-first quantitative research with reproducible backtests, factor diagnostics, and paper simulation. | Python/FastAPI, Next.js, research engineering |

Each focused developer tool includes runnable examples, deterministic tests, cross-platform CI, CodeQL scanning, machine-readable output, a GitHub Action, and a tagged release. Simulation results are labeled as simulations; project pages do not claim fabricated users, stars, or hardware benchmarks.

## What these projects demonstrate

- **Reliable AI systems:** trace contracts, replayable tool calls, agent-instruction provenance, and failure-first diagnostics.
- **Systems thinking:** scheduling, resource budgets, tail latency, graph reachability, compatibility rules, and stable identifiers.
- **Production-minded delivery:** focused CLIs, visual reports, CI integrations, security scanning, documentation, and reproducible releases.
- **Evidence over hype:** explicit assumptions, fail-closed boundaries, and claims that can be reproduced from the repository.

## Toolbox

`TypeScript` · `Node.js` · `Python` · `FastAPI` · `Next.js` · `PostgreSQL` · `Docker` · `OpenTelemetry` · `GitHub Actions`

I am open to roles in AI infrastructure, developer experience, backend/data systems, inference engineering, and quantitative research engineering.
