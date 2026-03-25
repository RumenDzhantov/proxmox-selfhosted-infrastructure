# Service Access

This document provides a high-level overview of how services are accessed in the Proxmox homelab.

## Access Model

Services in the lab are accessed in different ways depending on their role:

- internal access for lab-only services
- controlled external publishing for selected web services
- management access for administration and maintenance
- monitoring access for observability tools

## Principles

The access model is designed to support:
- separation between internal and externally published services
- simpler administration
- safer service exposure
- better documentation of operational workflows

## Examples

Typical access patterns include:
- internal-only service access
- selected external access through Cloudflare Tunnel
- management access for Proxmox and Linux systems
- monitoring access for dashboards and metrics

## Notes

This repository documents the architecture at a high level. Sensitive connection details, credentials, domain data and internal access specifics are not included.
