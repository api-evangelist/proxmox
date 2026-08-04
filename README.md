# Proxmox VE (proxmox)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
