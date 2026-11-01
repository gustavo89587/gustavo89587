# Gustavo Okamoto

**AI Security Engineer · Detection Engineering · Runtime Authorization**

I build security controls for the point where an AI agent's proposal becomes a real action.

[Vortex DFS](https://github.com/okamoto-security-labs/Vortex-DFS) · [Okamoto Security Labs](https://github.com/okamoto-security-labs) · [LinkedIn](https://www.linkedin.com/in/gustavo-okamoto-de-carvalho-ti/) · [Email](mailto:gugaokamoto1@gmail.com)

## About

My background spans nine years in IT support and operations. Today, my work focuses on AI security, detection fidelity, policy enforcement, and the execution boundaries of autonomous systems.

I lead the engineering of **Vortex DFS**, an experimental Rust runtime that evaluates identity, evidence, authority, policy, and consequences before protected execution. I care about security behavior that can be inspected in code, explained through stable reason codes, and reproduced through executable failure scenarios.

Based in Brazil and open to remote opportunities in AI security, detection engineering, and security operations.

## Flagship project: Vortex DFS

> Evidence is not authority. A proposed action is not permission to execute.

[Vortex DFS](https://github.com/okamoto-security-labs/Vortex-DFS) places an explicit decision boundary between an agent or workflow and its executor.

```text
request → identity + evidence + policy + consequence
        → ALLOW / REJECT / REDACT / AUDIT
        → guarded execution
```

The current repository includes:

- a deterministic Rust decision engine and hard execution gate;
- bearer identity, tenant context, and scope enforcement;
- PostgreSQL-backed, tenant-isolated audit events;
- versioned policy bundles, registry, and publisher-trust foundations;
- a runtime-failure conformance harness built from generalized security invariants;
- AISVS C9 action-class conformance tests for reversibility, consequence, and oversight;
- protected HTTP paths for agent tool evaluation and anonymization;
- experimental eBPF/XDP and post-quantum research, clearly separated from production claims.

**Maturity:** experimental pre-alpha. The project has executable security properties and working enforcement paths, but it is not presented as production-certified or independently audited.

## Selected engineering work

| Area | What I am building |
|---|---|
| Runtime authorization | Typed decisions, stable reason codes, fail-closed evaluation, and guarded execution |
| Authority preservation | Constraints for missing identity, denied intent, retries, scopes, and incomplete approval context |
| Consequence-aware control | Worst-case action-chain evaluation, reversibility, oversight, and irreversible-action hard gates |
| Auditability | Audit-before-execution semantics, bounded evidence records, and tenant-isolated retrieval |
| Policy distribution | Deterministic bundles, integrity validation, local installation, registry resolution, and publisher trust |
| Conformance engineering | Executable runtime-failure scenarios and external semantic mapping instead of security-by-claim |

## Other projects

- [Detection Fidelity Score](https://github.com/gustavo89587/detection-fidelity-score) — engineering work around measurable detection quality and operational confidence.
- [Security Observability Governance](https://github.com/gustavo89587/security-observability-governance) — governance patterns for security telemetry and observability.
- [DFS SDK Open](https://github.com/okamoto-security-labs/DFS-SDK-OPEN) — open integration work around Vortex runtime decisions.
- [SOC Incident Response Playbooks](https://github.com/gustavo89587/soc-incident-response-playbooks) — practical response automation and operational guidance.
- [SOC Threat Intel Automation](https://github.com/gustavo89587/soc-threat-intel-automation) — threat-intelligence automation experiments.

## Open-source contributions

My public work also includes contributions or technical participation across:

- [Elastic Detection Rules](https://github.com/elastic/detection-rules) — detection documentation and investigation guidance;
- [OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) — security-related documentation and implementation work;
- [OpenTelemetry Semantic Conventions](https://github.com/open-telemetry/semantic-conventions) — semantic and telemetry contributions;
- [CoSAI](https://github.com/cosai-oasis) — secure design and defender-focused work for agentic systems;
- [Wazuh Ruleset](https://github.com/wazuh/wazuh-ruleset) — detection and ruleset contributions.

I distinguish implementation, documentation, experiments, and production guarantees. A merged change is evidence of scoped engineering work—not a claim of universal system safety.

## What I work with

`Rust` · `Python` · `Detection Engineering` · `Policy Enforcement` · `Security Telemetry` · `AI Agent Security` · `OpenTelemetry` · `Elastic`

I am especially interested in:

- explicit execution authorization for AI agents;
- runtime failure modes and reproducible conformance tests;
- detection quality and explainable security decisions;
- telemetry semantics that preserve security meaning;
- the boundary between evidence, authority, action, and consequence.

## Work with me

- **Engineering opportunities:** AI security, detection engineering, runtime authorization, and security operations.
- **Technical pilots:** agent execution controls and runtime-failure assessments through Okamoto Security Labs.
- **Research conversations:** conformance, policy enforcement, and secure agent architecture.

Contact: [gugaokamoto1@gmail.com](mailto:gugaokamoto1@gmail.com)
