# Infrastructure Overview

```text
                    Internet
                        │
                Cloudflare Tunnel
                        │
        ┌────────────────────────────────┐
        │        Raspberry Pi 5          │
        │────────────────────────────────│
        │ Docker Engine                  │
        │                                │
        │ • Pi-hole                      │
        │ • Grafana                      │
        │ • Prometheus                   │
        │ • WireGuard / Tailscale        │
        │ • Nextcloud                    │
        │ • Portainer                    │
        │ • Loki                         │
        │ • Omada Controller             │
        └────────────────────────────────┘
                        │
                Internal VLAN Network
                        │
        ┌───────────────┬───────────────┐
        │               │               │
     Servers         CCTV           Clients
```
