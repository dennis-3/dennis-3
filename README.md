# Dennis Mwangi

**Network Infrastructure & Automation Engineer | NetDevOps**  
[LinkedIn](https://linkedin.com/in/dennismwangi3/) • [Tech Blog](https://dennismwangi.com/)

Designing resilient network infrastructure from enterprise backbones to carrier fabrics. I specialize in closed-loop GitOps pipelines, Source of Truth architectures, and automated network state validation.

### Featured Project: [sros-automation-starter](https://github.com/dennis-3/sros-automation-starter) `v1.0.0`
- **22 Jinja2 Templates**: Native SR OS MD-CLI/YANG data hierarchies covering Underlay (IS-IS/OSPF/SR-MPLS), Overlay (MP-BGP), L2VPN (Epipe/VPLS), L3VPN (VPRN/IES), and QoS.
- **Concurrency-Safe Deployment**: Exclusive whole-pipeline NETCONF candidate locking (`sros_lock_candidate`) preventing shared candidate collisions.
- **Closed-Loop Verification**: 6-stage deployment orchestrator (`run_verified_deployment.py`) featuring pre/post-change pyATS state snapshots, convergence soak, and automatic confirmed-commit rollback on invariant regressions.
- **Streaming Telemetry**: Containerlab topology integrating gNMI telemetry collection via Telegraf, Prometheus, and a pre-provisioned Grafana dashboard.

### Recent Technical Writing

- **[OSPF Series](https://dennismwangi.com/ospf/)**: In-depth architecture breakdown covering single/multi-area topology design, cost metric tuning, and OSPFv3 IPv6.
- **[NetDevOps & Source of Truth with NetBox](https://dennismwangi.com/netdevops/)**: Automated dynamic inventories, Containerlab Infrastructure as Code testbeds, and pyATS state verification.
- **[Enterprise Routing & Switching](https://dennismwangi.com/ccna-labs/)**: Hands-on implementations of EtherChannel, STP, HSRP gateway failover, and Layer 2 defense-in-depth.

### Tech Stack & Tooling

#### Core Infrastructure & Routing
![Nokia SR OS](https://img.shields.io/badge/Nokia-SR%20OS-red?style=flat-square)
![Cisco](https://img.shields.io/badge/Cisco-IOS-blue?style=flat-square)
![MikroTik](https://img.shields.io/badge/MikroTik-RouterOS-1F527E?style=flat-square)
![Routing Protocols](https://img.shields.io/badge/Routing-BGP%20%7C%20OSPF%20%7C%20IS--IS-00599C?style=flat-square)
![Transport & MPLS](https://img.shields.io/badge/Transport-MPLS%20%7C%20RSVP--TE%20%7C%20SR--MPLS-orange?style=flat-square)
![VPN Services](https://img.shields.io/badge/VPN-VPWS%20%7C%20VPLS%20%7C%20VPRN-purple?style=flat-square)

#### NetDevOps, Automation & Source of Truth
![Ansible](https://img.shields.io/badge/Ansible-Automation-EE0000?style=flat-square&logo=ansible&logoColor=white)
![NetBox](https://img.shields.io/badge/Source%20of%20Truth-NetBox-007ACC?style=flat-square&logo=netbox&logoColor=white)
![pyATS](https://img.shields.io/badge/Testing-pyATS-049fd9?style=flat-square)
![Containerlab](https://img.shields.io/badge/Simulation-Containerlab-008080?style=flat-square)
![Docker](https://img.shields.io/badge/Containers-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![NETCONF & gNMI](https://img.shields.io/badge/Protocols-NETCONF%20%7C%20gNMI%20%7C%20YANG-blueviolet?style=flat-square)

#### Languages & Observability
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![Jinja2](https://img.shields.io/badge/Templating-Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white)
![Bash](https://img.shields.io/badge/Shell-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Prometheus](https://img.shields.io/badge/Metrics-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Visuals-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
