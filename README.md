# IT Cloud & Security Portfolio

Hands-on labs, projects, and documentation in **Cloud Infrastructure** and **Cybersecurity**, focused on Microsoft Azure. Every entry is a real environment I built, broke on purpose, and verified — not a copied tutorial.

**Mosab Hassan** · Cloud & Security · [LinkedIn](https://www.linkedin.com/in/mosab-hassan) · [Email](mailto:YOUR-EMAIL)

> 🎯 **Track:** Azure networking & security, building toward **AZ-500 (Azure Security Engineer)** and a full secure-architecture capstone.

---

## 🧪 Labs

Each lab follows the same discipline: a clear objective, an architecture diagram, real command output, and **verification by rollback** (change one variable, re-test, prove causation).

| # | Lab | Domain | Key skills | Status |
|---|-----|--------|-----------|--------|
| 01 | [Blocking traffic with a UDR (blackhole)](labs/azure-net-01-udr-routing) | Networking | UDR · Route tables · Longest Prefix Match · Effective routes | ✅ Complete |
| 02 | Azure Firewall vs NSG | Networking | Azure Firewall · Network/App rules · DNAT | 🔜 Next |
| 03 | Private VM access with Azure Bastion | Networking / Security | Bastion · No public IP · Jump access | 🔜 Planned |
| 04 | Load Balancer & health probes | Networking | L4 LB · Backend pool · Probes | 🔜 Planned |
| 05 | Application Gateway + WAF | App delivery | L7 · TLS termination · WAF | 🔜 Planned |
| 06 | Private Endpoint & Private Link | Security | Private access to PaaS · DNS | 🔜 Planned |

---

## 🗂️ Repository Structure

```
it-cloud-security-portfolio/
├── labs/         hands-on, single-topic environments (numbered)
├── projects/     larger multi-service builds (capstone architecture)
├── docs/         concepts, cheat sheets, troubleshooting notes
└── README.md     this index
```

**Lab naming:** `<domain>-<area>-<NN>-<short-name>` — e.g. `azure-net-01-udr-routing`. The prefix groups topics; the number preserves order.

---

## 🎯 Areas of Focus

| Domain | Topics |
|--------|--------|
| **Azure Networking** | VNet · Subnets · NSG · UDR · Firewall · Load Balancer · App Gateway · Private Link · VPN |
| **Identity & Access** | Microsoft Entra ID · RBAC · Managed Identity · Key Vault · Least Privilege |
| **Security Architecture** | Defense in depth · Segmentation · Zero Trust · Private-by-default |
| **Monitoring** | Azure Monitor · Log Analytics · Network Watcher · NSG Flow Logs |

---

## 🏗️ Capstone (in progress)

A production-style **Secure Azure Architecture**: internet → Application Gateway + WAF → web tier → Azure Firewall → private app tier → private database, with Bastion for management, Private Endpoints for PaaS, and full monitoring. Built lab by lab, then assembled in `projects/`.

---

*This portfolio is actively maintained. Each commit reflects real hands-on work.*
