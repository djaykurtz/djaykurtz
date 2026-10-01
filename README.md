# David Kurtz

**Systems thinking. Practical automation.**

I work on making complex systems easier to coordinate, maintain, and understand, with projects spanning agent workflows, Windows application patching, and infrastructure design.

[Explore my portfolio](https://djaykurtz.github.io/) &nbsp; / &nbsp; [Connect on GitHub](https://github.com/djaykurtz)

## Selected work

### [COHORT](https://djaykurtz.github.io/#cohort)

I built COHORT's agent-coordination functions to organize my own projects and tasks. The goal is a personal engineering team: distinct role perspectives, explicit ownership, review of exact artifacts, durable context, and visible unknowns/failures. Reliability, not bureaucracy. ZeroBrain / superdashv2 makes the work inspectable.

[Repository](https://github.com/djaykurtz/COHORT) &nbsp; / &nbsp; [Project story](https://djaykurtz.github.io/COHORT/) &nbsp; / &nbsp; [Functional synthetic demo](https://djaykurtz.github.io/COHORT/demo/)

[Explore system atlas](https://djaykurtz.github.io/COHORT/systems/) &nbsp; / &nbsp; [Try research and decisions](https://djaykurtz.github.io/COHORT/demo/?view=governance)

The atlas maps documented/exported systems, authority, handoffs, and runtime availability, not a complete bundled runtime. Deliberation waves are not delivery; votes are audit evidence, not a numeric ratification gate.

<a href="https://djaykurtz.github.io/assets/cohort-governance.png" title="View full-resolution COHORT image"><img src="https://djaykurtz.github.io/assets/cohort-governance.png" alt="OFFLINE / SYNTHETIC research and decisions inspector with illustrative votes and deliberation evidence; no backend or real agent decisions." width="720"></a>

*OFFLINE / SYNTHETIC: selected dashboard/frontend and architecture/contracts, not the whole runtime; coordinator/backend/database omitted. Fixture-driven layers, drilldowns, and in-memory simulation/reset; no API calls, credentials, or persistent changes.*

### [ANS-CHOCO](https://djaykurtz.github.io/#ans-choco)

Policy-driven Windows software alignment with Ansible and Chocolatey, from reviewed package intent to per-host deployment evidence. Explore the source-grounded architecture, build/deploy workflows, and reporting.

Catalogs and policy, inventories, package sources, and authentication are configurable rather than tied to one lab. Execution currently uses Ansible and WinRM. Planned, not implemented: Azure Arc delivery through official modules and client-based authentication to reduce reliance on WinRM.

[Repository](https://github.com/djaykurtz/ANS-CHOCO) &nbsp; / &nbsp; [Explore architecture](https://djaykurtz.github.io/ANS-CHOCO/)

<a href="https://djaykurtz.github.io/assets/ans-choco-architecture.png" title="View full-resolution ANS-CHOCO image"><img src="https://djaykurtz.github.io/assets/ans-choco-architecture.png" alt="ANS-CHOCO architecture connecting catalog and inventory to Ansible build/deploy, Windows reconciliation, and deployment evidence." width="720"></a>

*Static showcase, not live fleet operations. Some package operations remain stubs; sysPatch and cloud credential integration are incomplete. Operational configuration is environment-specific; viewing the showcase requires no targets or credentials.*

### [Azure Local POC](https://djaykurtz.github.io/#azure-local)

A recorded four-node Azure Local lab proof of concept spanning physical fabric, pooled storage, Arc management, Kubernetes, and workload delivery. Progressive movements and evidence cutaways explain the engineering.

[Repository](https://github.com/djaykurtz/AZLOCAL-POC) &nbsp; / &nbsp; [Guided capstone](https://djaykurtz.github.io/AZLOCAL-POC/viewer/) &nbsp; / &nbsp; [Standalone presenter](https://djaykurtz.github.io/AZLOCAL-POC/)

<a href="https://djaykurtz.github.io/assets/azure-local-architecture.png" title="View full-resolution Azure Local image"><img src="https://djaykurtz.github.io/assets/azure-local-architecture.png" alt="Static Azure Local capstone view of generic fabric, platform, Arc bridge, pooled storage, and memory scope; not a connected Azure dashboard." width="720"></a>

*Static presentation of recorded lab work, not a connected Azure dashboard or production certification. Actual provisioning requires your own cloud environment, hardware, permissions, and credentials; viewing the capstone does not.*
