# Cloudflare Tunnel

This document describes the role of Cloudflare Tunnel in the Proxmox homelab.

## Purpose

Cloudflare Tunnel is used to publish selected internal services in a more controlled way without exposing them directly through traditional port forwarding.

## Main Use

The tunnel service helps provide:
- secure publishing of selected services
- controlled remote access
- simpler public exposure for web-based applications
- reduced need for direct inbound access

## Practical Value

Using Cloudflare Tunnel in the lab helps demonstrate:
- service publishing concepts
- remote access design
- practical security awareness
- integration of self-hosted services with external access methods

## Notes

Sensitive data such as tokens, credentials, domain secrets and internal configuration details are not included in this repository.
