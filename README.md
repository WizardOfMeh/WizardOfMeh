# Dmitrii Kizenkov

Backend engineer. Go, PostgreSQL, Kubernetes.
Seven years in production infrastructure: Linux, networking, virtualization.

I run a two-site homelab on Proxmox and k3s. Both projects below came out
of needing them there, and both run there now.

### Projects

**[inventory-api](https://github.com/WizardOfMeh/inventory-api)** — REST API over PostgreSQL.
Keyset pagination instead of OFFSET: 104 ms → 0.045 ms on 500k rows.
Runs on k3s. Go, Docker, Kubernetes.

**[healthchecker](https://github.com/WizardOfMeh/healthchecker)** — monitoring daemon in Go.
Concurrent TCP and HTTP checks across 9 nodes, Telegram alerts on state
change. Running unattended since <месяц>.

### Now

- Integration tests with testcontainers for inventory-api
- Prometheus metrics and Grafana dashboards

### Contact

Belgrade, Serbia — open to remote and contract work
d.kizenkov@outlook.com
