<h1 align="center">Hi, I'm Alex 👋</h1>

<p align="center">
  <b>Senior Rust backend developer · AI · co-founder of <a href="https://okoflow.com">OkoFlow</a></b><br>
  Seoul, South Korea · <b>open to work</b>
</p>

<p align="center">
  <a href="mailto:alexmun568@gmail.com"><img src="https://img.shields.io/badge/Email-alexmun568%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/ragen1337"><img src="https://img.shields.io/badge/Telegram-@ragen1337-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://wa.me/821022838565"><img src="https://img.shields.io/badge/WhatsApp-message-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
</p>

---

I've been building software commercially for 6+ years, the last 4 in Rust. Most of that is high-load backend: telemetry ingestion at up to 200K messages/s, Kafka pipelines where losing or duplicating an event is a bug, and media processing on AWS. Lately I also build AI features, such as RAG chatbots and semantic search, and I work agent-first with Claude Code, Codex and MCP.

I'm looking for a **senior Rust / backend** role, ideally one with an AI side. English C1, Russian native.

## Projects

### [LookSee](https://github.com/okoflow/looksee) · co-founder

Self-hosted video analytics with a visual workflow editor. LookSee watches camera streams and video files, runs ONNX object detection on them, and turns what it sees into alerts, snapshots and messages. Users wire cameras, models, zones and actions together as a graph, and everything runs on their own hardware.

`Python` `TypeScript` `ONNX Runtime` `WebRTC` `PostgreSQL` `Docker` · [website](https://looksee.okoflow.com) · [docs](https://github.com/okoflow/looksee-docs)

### [rust-realtime-analytics](https://github.com/ragen1337/rust-realtime-analytics)

An event analytics pipeline: HTTP ingestion → Kafka → batched writes → ClickHouse → cached analytics API. It handles 5,000 events/s at a p99 under 10 ms on a laptop, delivers at-least-once with deduplication in ClickHouse, and ships with Prometheus/Grafana and end-to-end tests in CI.

`Rust` `tokio` `actix-web` `Kafka` `ClickHouse` `Prometheus` `Docker`

## Stack

**Languages** · Rust, TypeScript, Python<br>
**Backend** · Tokio, Axum, actix-web, Tonic (gRPC), Kafka, PostgreSQL, ClickHouse, Redis<br>
**Cloud & infra** · AWS (EC2, Lambda, S3, SQS, SNS), Kubernetes, Docker, Prometheus, Grafana<br>
**AI** · RAG, embeddings, semantic search, ONNX Runtime, Claude Code, Codex, MCP
