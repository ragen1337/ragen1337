<h1 align="center">Hi, I'm Alex 👋</h1>

<p align="center">
  <b>Rust & AI developer · co-founder of <a href="https://okoflow.com">OkoFlow</a></b><br>
  Seoul, South Korea · <b>open to work</b>
</p>

<p align="center">
  <a href="mailto:alexmun568@gmail.com"><img src="https://img.shields.io/badge/Email-alexmun568%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/ragen1337"><img src="https://img.shields.io/badge/Telegram-@ragen1337-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://wa.me/821022838565"><img src="https://img.shields.io/badge/WhatsApp-message-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
</p>

---

I build backend systems that move a lot of data and stay correct while doing it: event pipelines, stream processing, and the infrastructure around AI models. I like Rust for the hot path, measurements over guesses, and designs whose failure modes are written down.

I'm looking for a **Rust, backend or AI engineering** role.

## Projects

### [LookSee](https://github.com/okoflow/looksee) · co-founder

Self-hosted video analytics with a visual workflow editor. LookSee watches camera streams and video files, runs ONNX object detection on them, and turns what it sees into alerts, snapshots and messages. Users wire cameras, models, zones and actions together as a graph, and everything runs on their own hardware.

`Python` `TypeScript` `ONNX Runtime` `WebRTC` `PostgreSQL` `Docker` · [website](https://looksee.okoflow.com) · [docs](https://github.com/okoflow/looksee-docs)

### [rust-realtime-analytics](https://github.com/ragen1337/rust-realtime-analytics)

An event analytics pipeline: HTTP ingestion → Kafka → batched writes → ClickHouse → cached analytics API. It handles 5,000 events/s at a p99 under 10 ms on a laptop, delivers at-least-once with deduplication in ClickHouse, and ships with Prometheus/Grafana and end-to-end tests in CI.

`Rust` `tokio` `actix-web` `Kafka` `ClickHouse` `Prometheus` `Docker`

## Stack

**Languages** · Rust, Python, TypeScript<br>
**Backend** · tokio, actix-web, Kafka, ClickHouse, PostgreSQL, REST<br>
**AI / CV** · ONNX Runtime, object detection, video pipelines<br>
**Infra** · Docker Compose, GitHub Actions, Prometheus, Grafana
