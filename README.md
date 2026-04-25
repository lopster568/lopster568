## Roshan Singh

Go systems engineer in Delhi NCR. I build infrastructure software — DNS security, distributed-tracing tooling, local-first AI agents — and contribute upstream to the CNCF projects I depend on.

Currently shipping [HydraDNS](https://github.com/hydradns/hydradns), an open-source DNS security gateway. Notes and writing at [roshansingh.systems](https://roshansingh.systems).

---

### Building

**[hydradns/hydradns](https://github.com/hydradns/hydradns)** — DNS-layer security gateway. Go control plane (Gin REST + gRPC), Next.js dashboard, containerised data plane. Self-hosted, GPL-3.0. Phase 1 (solid core) in progress.

**[odin-distil](https://github.com/lopster568/odin-distil)** — Local-first code-intelligence agent. Indexes ~30K AST-aware chunks across CNCF source trees (Kubernetes, Jaeger v2, LangChainGo) and runs a planner/grounder dual-model loop (Gemini + local Qwen2.5-72B over ROCm) on top. Built it to map unfamiliar codebases before contributing — it works, see Jaeger below.

### Upstream

**[CNCF Jaeger](https://github.com/jaegertracing/jaeger/pulls?q=author%3Alopster568+is%3Amerged)** — 7 merged PRs on `jaegermcp`, the MCP server that exposes Jaeger to LLM clients. Shipped: `get_service_dependencies` tool, end-to-end tracing integration tests, ADR-002 sync, MCP SDK client integration tests, LLM system-prompt instructions, search-trace summary improvements.

**[Unikraft / kraftkit](https://github.com/unikraft/kraftkit/pulls?q=author%3Alopster568+is%3Amerged)** — Error-handling refactor across the build package; Makefile lint target fix.

### Maintaining

**[hostplane](https://github.com/lopster568/hostplane)** — Go control plane behind a small managed-WordPress hosting service on a Proxmox homelab. Three paying customers in production. Maintenance mode while HydraDNS gets the focus.

---

[roshansingh.systems](https://roshansingh.systems) · [LinkedIn](https://linkedin.com/in/roshan-singh568)
