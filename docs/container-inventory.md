# Container Inventory

This document lists the main LXC containers currently used in the Proxmox homelab.

| ID  | Name                          | Role                              | Notes |
|-----|-------------------------------|-----------------------------------|-------|
| 100 | wallos                        | dashboard / utility service       | self-hosted service |
| 101 | cloudflared                   | Cloudflare Tunnel                 | secure publishing of selected services |
| 102 | myip                          | network utility                   | used for IP-related checks |
| 103 | duplicati                     | backup service                    | backup-related workload |
| 104 | prometheus                    | monitoring                        | metrics collection |
| 105 | prometheus-pve-exporter       | Proxmox metrics exporter          | exports Proxmox metrics to Prometheus |
| 106 | grafana                       | visualization                     | dashboards and monitoring views |
| 107 | prometheus-alertmanager       | alerting                          | alert routing and notification logic |
| 108 | prometheus-blackbox-exporter  | endpoint probing                  | checks endpoint availability |
| 109 | metube                        | media utility                     | self-hosted media-related service |
| 110 | homepage                      | dashboard                         | service landing page / overview |
| 115 | paymenter                     | hosting / billing platform        | self-hosted service platform |
| 119 | ampache                       | media streaming                   | music/media service |
| 120 | vaultwarden                   | password manager                  | self-hosted credential management |
