## Rayan Saoud

Networks & Telecommunications student (Bachelor of Technology, cloud track) in Colmar, France.
Looking for an **infrastructure / cloud internship from March 2027**: Basel, Geneva or Alsace.

**I build infrastructure that survives failure, and I prove it.**

→ [Pull the plug on my internship cluster](https://ryn-s.github.io/#demo): an interactive simulation of the
high-availability Proxmox VE cluster I built at NXO Telecom (quorum, fencing, failover, failback).
The site is in [French](https://ryn-s.github.io/?lang=fr), [English](https://ryn-s.github.io/?lang=en)
and [German](https://ryn-s.github.io/?lang=de).

### Internship at NXO Telecom, summer 2026

- Designed and deployed a 2-node Proxmox VE HA cluster with a QDevice on the NAS as third quorum vote, 20 VMs
- Deliberately took a node down to validate failover: restart on the survivor in 1 to 2 minutes, then failback
- 4 VLANs, inter-VLAN filtering, vzdump and Veeam backups with tested restores
- 46-test acceptance plan, all passed, plus 9 caveats and 13 recommendations for production
- Wrote **[pvetool](https://github.com/Ryn-s/pvetool)** on the Proxmox REST API. Its operations report found
  12 VMs with no backup at all.

### Projects

| Repository | What it does |
|---|---|
| [pvetool](https://github.com/Ryn-s/pvetool) | Python CLI for Proxmox VE: inventory, cloud-init deployment, lifecycle, backups, reports. Dry-run mode, idempotent, 33 tests. |
| [ansible-linux-baseline](https://github.com/Ryn-s/ansible-linux-baseline) | Ansible roles for a hardened, observable Debian/Ubuntu server: SSH, nftables, security updates, node_exporter. Molecule on 3 distributions, GitHub Actions and GitLab CI. |
| [azure-landing-zone-ch](https://github.com/Ryn-s/azure-landing-zone-ch) | Terraform landing zone where data stays in Switzerland: Azure Policy, segmented hub-and-spoke network, Key Vault, logs, budget. `terraform test`, TFLint, trivy. |
| [proxmox-terraform](https://github.com/Ryn-s/proxmox-terraform) | My internship cluster as code: cloud-init VMs, Proxmox VE 9 HA rules with failback, per-VM firewall, nightly backups, generated Ansible inventory. |
| [Onion_Router](https://github.com/Ryn-s/Onion_Router) | Onion routing across virtual routers, RSA implemented from scratch (for learning), PyQt5 monitoring, MariaDB. Pair project. |
| [ryn-s.github.io](https://github.com/Ryn-s/Ryn-s.github.io) | My site: static HTML/CSS/JS in three languages, cluster simulator covered by Playwright tests in CI. |

### Toolbox

**Proven at work:** Proxmox VE (HA, QDevice), ZFS, NFS, vzdump, Veeam B&R, VLAN 802.1Q, Python, cloud-init, PowerShell/GPO
**Projects:** Terraform, Ansible, Molecule, Microsoft Azure, GitHub Actions, GitLab CI, Linux, Docker, KVM, Cisco IOS, OSPF, BGP/MPLS-VPN, DNS/DNSSEC, Active Directory, nftables, OpenVPN, Zabbix

French (native) · English (B1) · German (A2)

[Site](https://ryn-s.github.io) · [LinkedIn](https://www.linkedin.com/in/rayan-saoud-94a11933b/) · saoud.rayan.pro@gmail.com

---

<sub>🇫🇷 Étudiant en BUT R&T (parcours Cloud) à Colmar, je cherche un stage en infrastructure / cloud à partir de mars 2027. Portfolio en français : [ryn-s.github.io](https://ryn-s.github.io/?lang=fr).</sub>
