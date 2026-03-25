# Proxmox Self-Hosted Infrastructure

This repository documents my Proxmox-based homelab environment, focused on self-hosted services, Linux administration, monitoring, storage organization and practical infrastructure management.

## Project Goals

- document a real Proxmox homelab environment
- organize services, storage and workloads clearly
- demonstrate practical infrastructure skills
- show monitoring and operational awareness
- build a portfolio project for internships and IT operations roles

## Core Technologies

- Proxmox VE
- Linux containers (LXC)
- Virtual machines
- Prometheus
- Grafana
- Alertmanager
- Blackbox Exporter
- Cloudflare Tunnel
- self-hosted applications
- SDN zones and storage organization

## Environment Overview

The homelab is built on Proxmox VE and uses a mix of LXC containers and virtual machines for hosting services, testing Linux systems and monitoring infrastructure.

Main focus areas:
- service hosting with LXC
- infrastructure monitoring
- storage separation
- controlled service publishing
- practical Linux and virtualization administration

## Current Services

### LXC Containers
- wallos
- cloudflared
- myip
- duplicati
- prometheus
- prometheus-pve-exporter
- grafana
- prometheus-alertmanager
- prometheus-blackbox-exporter
- metube
- homepage
- paymenter
- ampache
- vaultwarden

### Virtual Machines
- RedHat10.1
- RedHat10.1s
- ls3
- ls4

## Documentation Structure

This repository will include documentation for:

- Proxmox host overview
- container inventory
- virtual machine inventory
- monitoring stack
- Cloudflare Tunnel usage
- storage layout
- SDN zones
- service access and architecture notes

## Monitoring Stack

The lab includes a dedicated monitoring stack based on:
- Prometheus for metrics collection
- Prometheus PVE Exporter for Proxmox metrics
- Grafana for dashboards and visualization
- Alertmanager for alert routing
- Blackbox Exporter for endpoint probing

## Repository Contents

- [Proxmox Overview](docs/proxmox-overview.md)
- [Container Inventory](docs/container-inventory.md)
- [Virtual Machines](docs/virtual-machines.md)
- [Monitoring Stack](docs/monitoring-stack.md)
- [Storage Layout](docs/storage-layout.md)
- [Cloudflare Tunnel](docs/cloudflare-tunnel.md)
- [SDN Zones](docs/sdn-zones.md)
- [Service Access](docs/service-access.md)

## Notes

Sensitive information such as credentials, tokens, private IP details, private keys and internal secrets is excluded or redacted from this repository.

## Status

This is an active documentation project and will be expanded with architecture notes, service descriptions, diagrams and operational procedures.
