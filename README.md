# David Kurtz

**Systems thinking. Practical automation.**

I work on making complex systems easier to coordinate, maintain, and understand, with projects spanning agent workflows, Windows application patching, and infrastructure design.

[Explore my portfolio](https://djaykurtz.github.io/) &nbsp; / &nbsp; [Connect on GitHub](https://github.com/djaykurtz)

## Selected work

### [COHORT](https://djaykurtz.github.io/#cohort)

I built COHORT's agent-coordination functions to organize my own projects and tasks. The goal is a personal engineering team: distinct role perspectives, explicit ownership, review of exact artifacts, durable context, and visible unknowns/failures. Reliability, not bureaucracy. ZeroBrain / superdashv2 makes the work inspectable.

[Repository](https://github.com/djaykurtz/COHORT) &nbsp; / &nbsp; [Project story](https://djaykurtz.github.io/COHORT/) &nbsp; / &nbsp; [Interactive demo](https://djaykurtz.github.io/COHORT/demo/)

[Explore system atlas](https://djaykurtz.github.io/COHORT/systems/) &nbsp; / &nbsp; [Try research and decisions](https://djaykurtz.github.io/COHORT/demo/?view=governance)

The atlas maps documented systems, authority, handoffs, runtime availability, and source evidence. Deliberation waves are not delivery; votes are audit evidence, not a numeric ratification gate.

<a href="https://djaykurtz.github.io/assets/cohort-governance.png" title="View full-resolution COHORT image"><img src="https://djaykurtz.github.io/assets/cohort-governance.png" alt="Research and decisions inspector showing sample votes and deliberation evidence." width="720"></a>

*Interactive demo with sample data. Explore task, review, design, knowledge, and research/decision workflows through filters, drilldowns, and local simulation.*

### [ANS-CHOCO](https://djaykurtz.github.io/#ans-choco)

Policy-driven Windows software alignment with Ansible and Chocolatey, from reviewed package intent to per-host deployment evidence. Modular build/deploy roles, catalog and inventory policy, explicit reboot controls, and retry evidence make the operational workflow inspectable.

Catalogs and policy, inventories, package sources, and authentication are configurable rather than tied to one lab. Execution currently uses Ansible and WinRM. As deployment scale, business scope, and security requirements evolve, future enhancement options include Azure Arc execution through official modules and client-based authentication, with the aim of reducing reliance on WinRM.

[Repository](https://github.com/djaykurtz/ANS-CHOCO) &nbsp; / &nbsp; [Explore architecture](https://djaykurtz.github.io/ANS-CHOCO/)

<a href="https://djaykurtz.github.io/assets/ans-choco-architecture.png" title="View full-resolution ANS-CHOCO image"><img src="https://djaykurtz.github.io/assets/ans-choco-architecture.png" alt="ANS-CHOCO architecture connecting catalog and inventory to Ansible build/deploy, Windows reconciliation, and deployment evidence." width="720"></a>

*Explore the architecture of the delivered application-alignment workflow. Configure targets, package sources, and authentication to apply its policy-and-evidence model in your environment.*

### [Azure Local POC](https://djaykurtz.github.io/#azure-local)

An initial six-node Azure Local cluster goal became a resource-aware design exercise using available lab hardware. The delivered four-node POC connects physical fabric, pooled storage, Arc management, Kubernetes, and workloads, with the capstone showing the engineering choices behind the working platform.

[Repository](https://github.com/djaykurtz/AZLOCAL-POC) &nbsp; / &nbsp; [Guided capstone](https://djaykurtz.github.io/AZLOCAL-POC/viewer/) &nbsp; / &nbsp; [Standalone presenter](https://djaykurtz.github.io/AZLOCAL-POC/)

<a href="https://djaykurtz.github.io/assets/azure-local-architecture.png" title="View full-resolution Azure Local image"><img src="https://djaykurtz.github.io/assets/azure-local-architecture.png" alt="Azure Local capstone view of fabric, platform, Arc bridge, pooled storage, and memory scope." width="720"></a>

*Explore recorded lab engineering in the guided capstone. Adapt the provisioning examples to your cloud environment, hardware, permissions, and credentials.*
