# Proxmox VE (proxmox)

Proxmox Virtual Environment (Proxmox VE) is an open-source server virtualization platform that combines KVM hypervisor and LXC containers, software-defined storage and networking, and clustering and high- availability features in a single web-managed solution. The Proxmox VE API exposes all platform operations under /api2/json on port 8006, including node, cluster, storage, pool, and access management endpoints. Supported authentication methods include stateless API tokens (PVEAPIToken header) and ticket-based sessions issued via /access/ticket.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/proxmox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/proxmox/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Virtualization
- KVM
- Containers
- LXC
- Clustering
- Open Source

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Proxmox VE API

REST-style management API for Proxmox VE covering nodes, virtual machines, containers, storage, networking, clustering, pools, and access management. Authenticated via API tokens (PVEAPIToken header) or ticket-based sessions with CSRFPreventionToken for write operations.

- **Human URL:** [https://pve.proxmox.com/wiki/Proxmox_VE_API](https://pve.proxmox.com/wiki/Proxmox_VE_API)
- **Base URL:** `https://your.server:8006/api2/json`

#### Tags

- Virtualization
- Cluster Management
- Infrastructure

#### Properties

- [Documentation](https://pve.proxmox.com/wiki/Proxmox_VE_API)
- [A P I  Viewer](https://pve.proxmox.com/pve-docs/api-viewer/)
- [Authentication](https://pve.proxmox.com/wiki/Proxmox_VE_API#Authentication)
- [Postman Collection](collections/proxmox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/proxmox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/proxmox)
- [Website](https://www.proxmox.com)
- [Documentation](https://pve.proxmox.com/pve-docs/)
- [Pricing](https://www.proxmox.com/en/proxmox-virtual-environment/pricing)
- [Download](https://www.proxmox.com/en/downloads)
- [A P I  Viewer](https://pve.proxmox.com/pve-docs/api-viewer/)
- [Git Hub](https://github.com/proxmox)
- [Community  Forum](https://forum.proxmox.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
