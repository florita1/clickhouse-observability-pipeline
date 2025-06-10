# 🚀 Observability Stack: Tempo • Prometheus • Grafana

Production-style local observability stack using Docker Compose. Supports OTEL trace ingestion, Prometheus metrics, and Grafana dashboards.

## 🔧 Stack Components

- **Tempo** – Distributed tracing (OTLP receiver)
- **Prometheus** – Metrics collection (scrapes /metrics)
- **Grafana** – Visualization for metrics and traces

## ▶️ Quick Start

```bash
docker-compose up -d

