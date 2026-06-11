# Aditya Rola

Backend and distributed systems engineer — financial execution infrastructure. Nine years building correctness-critical systems, from secure enterprise data platforms and payments tooling (JPMorgan, Visa) to on-chain arbitrage execution and settlement (Capx, Thema). I work across Rust, Go, TypeScript, and Solidity and own backend architecture end to end.

Currently Founding Engineer at **Thema Labs**. Previously Tech Lead at **Capx AI**, with earlier engineering roles at **Visa** and **JPMorgan Chase**. Based in Bengaluru, India.

[GitHub](https://github.com/adirola) · [X](https://x.com/adityarola)

---

### Current project

- **[Aisle](https://github.com/adirola/aisle)** — wedding and venue vendor portals built for AI agents, encapsulating agentic commerce and traversal over an ERC-based protocol.

### What I work on

- **Latency-sensitive execution** — built an on-chain arbitrage hot path in Rust decoding ~150 sources per block; a three-tier submission cascade (private relay → exclusive validator mempool → public gas auction) sustained **~85–90% inclusion** across a 9,000-execution live beta.
- **High-scale platforms** — served portfolio valuation, charts, and leaderboards at **sub-second P90** via a read-through Redis cache, and held **99.9% uptime** through 200K+ participant launch campaigns using Kafka queues and request-level load shedding.
- **Correctness-critical pipelines** — ordered, idempotent, at-least-once processing with dedup so retries never double-count, backed by hot-standby failover and automated crash recovery on TimescaleDB.
- **On-chain primitives** — ERC-4626 / 7540 tokenized vaults and a custom Safe module in Solidity, with invariants validated through Foundry property-based fuzzing before any capital was deployed.
- **Agentic engineering** — a staged research → design → implement harness that cut token cost per shipped change **~60%** and agent-caused change failures **~80%** by moving review upstream.

### Writing

- [How to set up your own self-sovereign app-chain ZK-rollup using Polygon zkEVM](https://medium.com/coinmonks) — Coinmonks
- Early open-source contributor to Polygon zkEVM, ai16z Eliza, and Luganodes.

### Tech

`Rust` · `Go` · `TypeScript` · `Solidity` · `Java`
`Node.js` · `Next.js` · `Spring Boot` · `React`
`PostgreSQL` · `TimescaleDB` · `Redis` · `Kafka` · `RabbitMQ`
`Foundry` · `Grafana` · `Terraform`
`GCP` · `AWS` · `Azure` · `Docker` · `Kubernetes`
