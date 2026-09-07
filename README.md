# Noah Ingwers

I build security and evaluation infrastructure for agentic systems — software that makes authority explicit, evidence reproducible, and failure modes legible.

U.S. person · no sponsorship required · TPM / TEE / MCP policy · Python + TypeScript

## Selected work

- **[Attested Capability Broker](https://github.com/noah-ing/attested-capability-broker)** — Independent reference experiment
  using released AgenTrust components to bind TPM-appraised platform state and
  authenticated agent identity to a short-lived, minimal-scope MCP capability with
  at-most-once redemption.
- **[GoldKey Guard](https://github.com/noah-ing/goldkey)** — Policy-bound
  authorization receipts and a local, fail-closed enforcement path for privileged
  agent actions.
- **[SENTINEL](https://github.com/noah-ing/SENTINEL)** — Reproducible
  prompt-injection evaluation and explicit policy gating for tool-using agents.
- **[raptor-trace](https://github.com/noah-ing/raptor-trace)** — TRACE replay-transfer
  evidence, validators, and working note for the AI Agent Security competition.
- **[EMAP](https://github.com/noah-ing/EMAP)** — Artifact-grounded experiments on
  multi-agent architectures under hard token budgets.

## Upstream

- **[cMCP](https://github.com/agentrust-io/cmcp/pull/601)** — Consolidated TPM NV
  parsing on a shared API and added portable reference fixtures.
- **[Agent Manifest](https://github.com/agentrust-io/agent-manifest/pull/304)** — Added
  shared, typed parsing for TPM NV attestations.
- **[cA2A](https://github.com/agentrust-io/ca2a/pull/151)** — Added an official Python
  A2A SDK loopback example, integration documentation, and transport regression tests.
- **[Framework integrations](https://github.com/agentrust-io/integrations/pull/124)** —
  Improved LangGraph callback interoperability and added released-framework coverage.
- **[Reef](https://github.com/Human-Agent-Society/reef/pull/285)** — Improved
  release-read responsiveness during long-running evolution.

## Engineering principles

`Least privilege` · `Explicit authorization` · `Reproducible evaluation` ·
`Auditable interfaces`

Python · TypeScript/JavaScript · systems security
