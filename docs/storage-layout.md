# Storage Layout

This document provides a high-level overview of the storage structure used in the Proxmox homelab.

## Storage Areas

### local
Used for local Proxmox storage and system-related data.

### data
Used for service data and persistent application storage where needed.

### backups
Used for backup-related storage and backup workflows.

## Goals

The storage layout is organized to:
- separate system and service data
- keep backups isolated from active workloads
- make the environment easier to manage
- support clearer documentation and maintenance

## Notes

The exact storage configuration may evolve over time as the lab grows and changes.
