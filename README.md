# Homelab

This repo contains all of the configurations and documentation of my homelab.

I began working on this 2025-12-15

## Tooling

### Kubernetes Cluster
* [Arch Linux](https://archlinux.org/) - Host OS on old laptop
* [K3s](https://k3s.io/) - Lightweight Kubernetes distribution
* [Flux](https://fluxcd.io) - GitOps continuous delivery
* [N8N](https://n8n.io) - Workflow automation platform

### Network Infrastructure
* [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - DNS filtering and ad blocking (Raspberry Pi)


## Goals

* Run Prometheus and Grafana Stack
* Everything should be deployed using GitOps
* 

## Log

### 1. Configure AdGuard DNS 
- Add DNS entries in AdGuard Home

### 2. Install cert-manager 
- Add cert-manager via Flux for certificate management
- Set up self-signed CA 

### 3. Configure HTTPS 
- Update Traefik for websecure entrypoint
- Update IngressRoutes to use HTTPS
- Fix n8n secure cookie setting (`N8N_SECURE_COOKIE: "true"`)

