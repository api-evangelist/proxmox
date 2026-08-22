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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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
