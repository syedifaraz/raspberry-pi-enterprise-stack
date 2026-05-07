# Raspberry Pi Enterprise Stack

Enterprise-grade Raspberry Pi infrastructure stack focused on self-hosting, monitoring, VPN access, DNS filtering, automation, and secure remote management.

---

## Features

- Docker-based deployment
- Pi-hole DNS filtering
- WireGuard / Tailscale VPN
- Cloudflare Tunnel integration
- Grafana + Prometheus monitoring
- Loki centralized logging
- Nextcloud self-hosting
- Omada Controller integration
- VLAN-ready infrastructure design
- Automated backups and monitoring

---

## Infrastructure Components

| Component | Purpose |
|---|---|
| Raspberry Pi 5 | Main infrastructure node |
| Docker | Container orchestration |
| Pi-hole | Network-wide DNS filtering |
| WireGuard | Secure VPN access |
| Cloudflare Tunnel | Secure external access |
| Grafana | Monitoring dashboards |
| Prometheus | Metrics collection |
| Loki | Log aggregation |
| Nextcloud | Private cloud platform |
| Omada Controller | Network management |

---

## Repository Structure

```text
docs/          → Documentation
screenshots/   → Dashboard and setup screenshots
diagrams/      → Infrastructure diagrams
configs/       → Example configuration files
monitoring/    → Monitoring stack files
