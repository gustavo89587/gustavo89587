

### Gustavo Okamoto

---

AI Security Engineer  Detection Engineering 路 Runtime Authorization


I build security controls for the point where an AI agent's proposal becomes a real action.


Flagship project 路 Engineering evidence 路 Open-source contributions 路 Contact





### About

---

My background spans nine years in IT support and operations. Today, my engineering work focuses on AI security, detection fidelity, and explicit authorization at execution boundaries.


I build Vortex DFS at Okamoto Security Labs: an experimental Rust runtime that evaluates policy and evidence before protected execution. My focus is making security behavior inspectable through code, reason codes, architecture decisions, and executable failure scenarios.


Brazil 路 Open to remote opportunities in AI security, detection engineering, and security operations.


### Flagship: Vortex DFS

---

The problem: a proposed action, a risk score, and permission to execute are different things. Integrations must preserve that distinction all the way to the executor.


The approach: evaluate evidence, authority, and consequences against explicit policy; return a structured decision; enforce that decision at the protected execution boundary.


Review area	Evidence
Runtime implementation	Rust runtime modules
Architectural reasoning	Separate evidence, authority, and consequence
Reproducible security scenarios	Runtime failure conformance harness
Build and test history	GitHub Actions

Maturity: experimental pre-alpha. Enforcement depends on the integration path and the evidence supplied to it. The repository distinguishes runtime functionality from experimental cryptography and eBPF work.


### Selected engineering work

---


Preserving authority constraints: denied-intent constraints and retry constraints make prior security state explicit in runtime evaluation.

Handling incomplete approval context: fail-closed evaluation prevents missing mandatory approval evidence from silently becoming permission.

Separating risk from authority: executable conformance cases test that a risk signal does not manufacture execution authority.

Distributing policy: versioned bundles and registry foundations separate bundle integrity from publisher authenticity.


These links describe specific changes and their scope; they are not claims of universal agent safety or production certification.


### Upstream contributions

---

Selected merged contributions. Documentation and implementation work are identified separately.


Project	Contribution	Type
OpenTelemetry Collector Contrib	Clarified redaction rule precedence and added an operator example	Documentation
Elastic Detection Rules	Improved encrypted-archive investigation guidance and false-positive scenarios	Detection documentation
Agent Vortex Envelope	Made missing DFS evidence produce an explicit fail-safe block	Implementation and tests
Agent Vortex Envelope	Separated DFS decisions from runtime context	Implementation

### Engineering interests

---

Rust  Python  Detection engineering  Policy enforcement Security telemetry Agent execution boundaries


I care about explicit failure states, reproducible tests, and explaining where a security guarantee ends.


### Work with me

Engineering opportunities: AI security, detection engineering, and security operations.


Technical pilots and research conversations: agent execution controls and runtime failure assessments through Okamoto Security Labs.


Email Technical writing



