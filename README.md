## Roshan Singh

Go systems engineer in Delhi NCR. Selected as an LFX Mentorship Term 3 mentee for CNCF Jaeger (September to November 2026), benchmarking the MCP tools and skills Jaeger serves to AI agents. Building [HydraDNS](https://github.com/hydradns/hydradns). Notes at [roshansingh.systems](https://roshansingh.systems).

### Jaeger

**[jaeger-mcp-evals](https://github.com/lopster568/jaeger-mcp-evals)**
The mentorship harness for [jaeger#9135](https://github.com/jaegertracing/jaeger/issues/9135). Each trial breaks one OpenTelemetry Demo service with a feature flag, lets an agent investigate through Jaeger's MCP tools only, and scores its verdict against the known cause.

**[Merged in Jaeger](https://github.com/jaegertracing/jaeger/pulls?q=author%3Alopster568+is%3Amerged)**
Most of it in `jaegermcp`, the MCP server that exposes Jaeger to LLM clients: tools, integration tests, ADR sync, system-prompt instructions. Also a fix to dependency links in the memory store.

**[jaeger-mcp-bench](https://github.com/lopster568/jaeger-mcp-bench)**
A/B benchmark of MCP tool output formats for Jaeger SPM metrics: two 72-trial arms across Claude and Gemini, raw dumps and run manifests committed. A tiered output format took Claude from 6 of 18 to 16 of 18 tasks (p=0.0006). Built after the maintainer asked for benchmarks over opinion on [jaeger#8409](https://github.com/jaegertracing/jaeger/issues/8409).

### Building

**[hydradns/hydradns](https://github.com/hydradns/hydradns)**
Network-wide DNS filtering in Go: gRPC control plane, web dashboard, DoH-bypass blocking, and a built-in MCP server so an agent can manage the firewall. Self-hosted, GPL-3.0, [v0.1.1](https://github.com/hydradns/hydradns/releases) out.

### Other upstream merges

[grpc-go](https://github.com/grpc/grpc-go/pulls?q=author%3Alopster568+is%3Amerged) · [containerlab](https://github.com/srl-labs/containerlab/pulls?q=author%3Alopster568+is%3Amerged) · [cel-go](https://github.com/cel-expr/cel-go/pulls?q=author%3Alopster568+is%3Amerged) · [OPA](https://github.com/open-policy-agent/opa/pulls?q=author%3Alopster568+is%3Amerged) · [ToolHive](https://github.com/stacklok/toolhive/pulls?q=author%3Alopster568+is%3Amerged) · [CrowdSec](https://github.com/crowdsecurity/crowdsec/pulls?q=author%3Alopster568+is%3Amerged) · [DNSControl](https://github.com/DNSControl/dnscontrol/pulls?q=author%3Alopster568+is%3Amerged) · [Unikraft kraftkit](https://github.com/unikraft/kraftkit/pulls?q=author%3Alopster568+is%3Amerged)

As of October 2026, credited by name in 9 stable releases across 7 projects: Jaeger v2.17.0, v2.18.0 and v2.22.0, containerlab v0.79.0, cel-go v0.31.0, ToolHive v0.42.1, DNSControl v4.45.0, CrowdSec v1.8.0, OPA v1.20.0.

---

[roshansingh.systems](https://roshansingh.systems) · [LinkedIn](https://linkedin.com/in/roshan-singh568) · [Email](mailto:rosh.s568@gmail.com) · [Resume](https://drive.usercontent.google.com/download?id=1DxoaOIs-vZXXYZtyCL0hKjhftYYpVNUu&export=download)
