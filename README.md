## Roshan Singh

Go systems engineer in Delhi NCR. Building [HydraDNS](https://github.com/hydradns/hydradns), an open-source DNS security gateway. Contributing upstream to CNCF Jaeger and Unikraft. Notes at [roshansingh.systems](https://roshansingh.systems).

### Building

**[hydradns/hydradns](https://github.com/hydradns/hydradns)**
DNS security gateway. Go control plane (Gin REST + gRPC), Next.js dashboard, Docker Compose deployment. GPL-3.0. Phase 1 in progress.

**[odin-distil](https://github.com/lopster568/odin-distil)**
Local-first code-intelligence agent. AST-aware vector index of ~30K chunks across Kubernetes, Jaeger v2, and LangChainGo. Planner (Gemini) drives, grounder (local Qwen2.5-72B on ROCm) answers from retrieved code. Built it to map unfamiliar codebases before sending PRs. The Jaeger work below came out of it.

### Upstream

**[CNCF Jaeger](https://github.com/jaegertracing/jaeger/pulls?q=author%3Alopster568+is%3Amerged)**
7 merged PRs on `jaegermcp`, the MCP server that exposes Jaeger to LLM clients. Shipped: `get_service_dependencies` tool, end-to-end tracing integration tests, ADR-002 sync, MCP SDK client integration tests, LLM system-prompt instructions, search-trace summary improvements.

**[Unikraft / kraftkit](https://github.com/unikraft/kraftkit/pulls?q=author%3Alopster568+is%3Amerged)**
2 merged PRs. Error-handling refactor across the build package. Makefile lint target fix.

---

[roshansingh.systems](https://roshansingh.systems) · [LinkedIn](https://linkedin.com/in/roshan-singh568)
