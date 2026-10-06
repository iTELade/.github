<div align="center">

<img src="https://avatars.githubusercontent.com/u/170614338?v=4" width="120" alt="iTELade logo">

# iTELade

### Infrastructure · Service Management · Security Operations

Self-hosted tools and infrastructure built for practical day-to-day IT operations.

[Website](https://itelade.pl) · [Service status](https://status.itelade.pl) · [Contact](mailto:kontakt@itelade.pl)

<br>

![Linux](https://img.shields.io/badge/Linux-infrastructure-222?logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-containers-222?logo=docker&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-identity-222?logo=keycloak&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-networking-222?logo=wireguard&logoColor=white)

</div>

---

## What we build

<table>
<tr>
<td width="50%" valign="top">

### Service Desk

Self-hosted IT service management platform built around real operational workflows.

**Core areas**

- incidents and service requests
- customer and agent portals
- LDAP / SSO authentication
- SLA policies and automation
- assets and configuration items
- workflows, queues and ticket linking
- knowledge base integration

**Repository:** [iTELade/service-desk](https://github.com/iTELade/service-desk)

</td>
<td width="50%" valign="top">

### Knowledge Base

Documentation and knowledge management developed alongside Service Desk.

**Core areas**

- structured internal documentation
- service and troubleshooting articles
- reusable operational knowledge
- Service Desk integration
- searchable technical content

**Repository:** [iTELade/service-desk-knowledge-base](https://github.com/iTELade/service-desk-knowledge-base)

</td>
</tr>
</table>

## Infrastructure

iTELade runs a self-hosted environment focused on keeping infrastructure understandable, maintainable and under direct control.

| Area | Stack |
|---|---|
| Systems | Linux · Windows Server · Active Directory |
| Containers | Docker · Docker Compose |
| Identity | Keycloak · LDAP · SSO |
| Networking | WireGuard · MikroTik · Nginx |
| DNS | PowerDNS |
| Mail | Mailcow |
| Development | GitHub · GitHub Actions |
| Operations | monitoring · incident tracking · service status |

## Operations

Public-facing service availability is published at **[status.itelade.pl](https://status.itelade.pl)**.

Administrative services are kept separate from public-facing applications, with access controls built around private networking and centralized identity.

## Open source

Public repositories are used for projects that can be developed openly. Internal infrastructure configuration, credentials and private operational data remain outside public repositories.

---

<div align="center">

**iTELade**  
[itelade.pl](https://itelade.pl) · [kontakt@itelade.pl](mailto:kontakt@itelade.pl)

</div>
