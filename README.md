# Hi, I'm Patrick 

**IT Systems & Network Administrator** specializing in enterprise Windows Server infrastructure, Hyper-V virtualization, Enterprise networking, and PowerShell automation. 

I design, deploy, and maintain high-availability systems—focusing on core network redundancy, automated virtual machine provisioning, disaster recovery, and infrastructure-as-code scripting.

---

## 🛠 Tech Stack & Core Competencies

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Virtualization & Compute** | Hyper-V (Failover Clustering, CSVs, SET), VMware ESXi, Windows Server (2016–2025), Linux (RHEL/Ubuntu) |
| **Networking & Routing** | Cisco IOS, L2/L3 Core Switching, HSRP, 802.1Q VLAN Trunking, LACP/EtherChannel, IP Helper Relays |
| **Directory & Core Services**| Active Directory (AD DS), DNS, DHCP, Group Policy (GPO), PKI / Certificate Services, Network Policy Server (NPS) |
| **Backup & Business Continuity** | Veeam Backup & Replication, MPIO Direct-Attach SAN / Block Storage, Automated backups |
| **Automation & Scripting** | PowerShell, Python, Bash, C, Assembly, Rust |

---

## 🏗 Featured Projects

### 📡 [Network-lab](https://github.com/PatMitchell-Tech/Network-lab)
A high-fidelity, scaled-down enterprise network simulation built in Cisco Packet Tracer:
* **High Availability Core:** Dual Cisco 3560 L3 switches with HSRP gateway failover, EtherChannel trunking, and sub-second failover paths.
* **Centralized Services:** Multi-VLAN DHCP relaying via `ip helper-address` back to Active Directory servers.
* **Storage Isolation:** Dedicated SAN switching fabric for block-level iSCSI storage, keeping disk I/O off client SVIs.
* **Scale Testing:** Engineered around simulator limitations (~250 active endpoints with background ARP/STP timers).

### 🛠 [Networktools](https://github.com/PatMitchell-Tech/Networktools)
A collection of custom production-ready scripts written for network engineering, switch staging, and bulk configuration management.

---

## 📊 Infrastructure Philosophy

> *"Build for high availability, automate the repetitive tasks, and isolate storage traffic."*

* **Redundancy First:** Every core service gets a failover pair—whether it's dual L3 core switches, HSRP gateways, or active/passive DHCP scopes.
* **Scripted Operations:** If a task takes more than two clicks or needs to be repeated, write a PowerShell module for it.
* **Air-Gapped & Resilient:** Backups follow strict 3-2-1-1-0 strategies using Veeam immutable repositories and offsite replication.

---

<details>

</details>

---

📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/patrick-mitchell-16a606214) | [Portfolio Site](https://patmitchell-tech.github.io/)
