# Dmitrii Kizenkov

Backend engineer working in Go and Postgres, with a background in
production infrastructure — Linux, networking, virtualization, Kubernetes.

### Projects

**[inventory-api](https://github.com/WizardOfMeh/inventory-api)** — REST API in Go.
Keyset pagination brought deep-page reads from 104 ms down to 0.045 ms on
500k rows. Runs on k3s in a 20 MB distroless image.

**[healthchecker](https://github.com/WizardOfMeh/healthchecker)** — monitoring daemon in Go.
Concurrent TCP and HTTP checks across 9 nodes, alerts only on state change,
running unattended for months.

Both run on a two-site Proxmox and k3s setup I built and maintain.

### Now

- Integration tests with testcontainers for inventory-api
- Prometheus metrics and Grafana dashboards

### Contact

Belgrade, Serbia — open to remote and contract work
d.kizenkov@outlook.com
