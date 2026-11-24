# Vishvendra Reddy Bhoomidi

I build AI products and the systems behind them, from the first customer conversation to the workflow an operator can run. As founder and lead engineer at Kaarya AI, I work across React product interfaces, Python services, integrations, and customer onboarding.

[Engineering portfolio](https://vishvendrabhoomidi.com/work/open-source-engineering) · [Kaarya AI case study](https://vishvendrabhoomidi.com/work/kaarya-ai) · [LinkedIn](https://www.linkedin.com/in/vishvendra-reddy-bhoomidi/)

## Selected engineering work

- **Full-stack** · [Workflow Desk](https://github.com/Vishvendra07/workflow-desk) preserves an operator's draft when two browser sessions edit the same case. [See the conflict and recovery UI](https://github.com/Vishvendra07/workflow-desk/blob/main/evidence/conflict-desktop.png)
- **Backend** · [Event Relay](https://github.com/Vishvendra07/event-relay) commits an order and its outbox together. The worker retries a failed acknowledgment and the receiver keeps one receipt. [See the three delivery scenarios](https://github.com/Vishvendra07/event-relay/blob/main/evidence/demo.json)
- **Applied AI** · [Intake Evals](https://github.com/Vishvendra07/intake-evals) compares two deterministic extractors on 60 authored cases for corrections, abstention, and evidence. [Inspect the errors and per-field results](https://github.com/Vishvendra07/intake-evals/blob/main/evidence/comparative-report.json)
- **Forward deployed** · [Implementation Kit](https://github.com/Vishvendra07/implementation-kit) runs two simulated CRM rollouts. A rerun writes zero extra records, and rollback preserves a later operator edit. [Read the operator handoff](https://github.com/Vishvendra07/implementation-kit/blob/main/HANDOFF.md)

## More systems to explore

- [Postgres CDC Projection](https://github.com/Vishvendra07/postgres-cdc-projection) · Replays an unacknowledged batch after a consumer restart and reconciles the read model against the source.
- [MCP Approval Demo](https://github.com/Vishvendra07/mcp-approval-demo) · An MCP client proposes an edit, and a separate operator step approves the exact payload before the catalog changes.
- [Tenant Search Benchmark](https://github.com/Vishvendra07/tenant-search-benchmark) · Compares keyword and vector retrieval under tenant filters and checks exact ranking parity with pgvector.
