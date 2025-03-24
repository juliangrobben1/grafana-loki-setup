# Loki + Promtail + Grafana Logging Stack

A simple, production-friendly logging stack using Docker Compose.

## 📦 Services

- **Loki**: Stores and indexes logs
- **Promtail**: Collects Docker logs and ships them to Loki
- **Grafana**: Visualizes logs with powerful queries

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-org/loki-logging-stack.git
cd loki-logging-stack

docker-compose up -d
