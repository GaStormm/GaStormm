<h1 align="center">Hi, I'm Vitor Gonçalves 👋</h1>

<p align="center">
  <b>IT Support (N1/N2) · Blue Team enthusiast · Homelab builder</b><br>
  Florianópolis, Brazil · Open to remote opportunities
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-00AC4F?style=flat-square&logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft-SC--900%20%7C%20SC--200-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-K3s-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Proxmox-VE-E57000?style=flat-square&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Wazuh-SIEM%2FXDR-4B0082?style=flat-square" />
</p>

---

## About me

IT Support technician (N1/N2) in a hospital environment, actively transitioning into **Blue Team / SOC**.  
With ~2 years of IT experience (1 year in critical healthcare infrastructure), I combine my day-to-day support work with hands-on security practice in a self-built homelab: a 3-node Proxmox cluster running K3s Kubernetes with a full monitoring and security stack.

- 🎯 Target role: **SOC Analyst L1/L2** — threat detection, log analysis, incident response
- 📚 Certifications in progress: **CompTIA Security+** · **SC-900 → SC-200** (Microsoft Sentinel path)
- 🌐 Available for **remote opportunities** in Blue Team / Security Operations
- 🗣️ Portuguese (native) · Spanish (fluent) · English (C1)

---

## 🖥️ Homelab

### 3-Node Proxmox Cluster + K3s Kubernetes

Migrated from a standalone Proxmox node to a production-grade 3-node cluster running **K3s Kubernetes**.  
Namespaces: `homelab` · `monitoring` · `security`  
MetalLB handles load balancing; Traefik manages ingress routing.

`Proxmox VE` `K3s / Kubernetes` `MetalLB` `Traefik`

---

### 📊 Monitoring Stack

| Service | IP | Role |
|---|---|
| AdGuard | DNS filtering & ad blocking |
| Zabbix | Infrastructure monitoring |
| Grafana | Dashboards & alerting |
| Prometheus | Alpine LXC | Metrics collection |

Custom Zabbix **UserParameters** for GPU monitoring on a GTX 1050 Ti (via Ollama AI server `ga-ia`).

---

### 🛡️ Security Stack — Wazuh SIEM/XDR + AWS

- **Wazuh** deployed in the `security` namespace, ingesting events from the entire homelab
- **AWS EC2** instance connected via Tailscale, running a **Zabbix Proxy (SQLite3)** for metric buffering
- Private **CA with OpenSSL** + Nginx Proxy Manager for internal HTTPS — zero public exposure
- MikroTik hEX handles DNS for the custom local domain

`Wazuh SIEM/XDR` `AWS EC2` `Tailscale` `OpenSSL CA` `Nginx Proxy Manager`

---

### 🌐 Network — MikroTik hEX + FortiSwitch 108F

- MikroTik hEX (RB750Gr3) as core router with **bridge-native VLAN filtering**
- **VLAN 67** (192.168.67.0/24) — servers
- **VLAN 69** (192.168.69.0/24) — production services
- FortiSwitch 108F on server ports

`MikroTik` `FortiSwitch` `VLANs` `WireGuard`

---

## 🔧 Tech Stack

**Security & Monitoring**  
`Wazuh` `Zabbix` `Grafana` `Prometheus` `AdGuard`

**Infrastructure**  
`Proxmox VE` `K3s / Kubernetes` `Docker` `Linux` `Bash`

**Networking & Cloud**  
`MikroTik` `VLANs` `AWS EC2` `Tailscale` `WireGuard`

---

## 📫 Contact

- 💼 [linkedin.com/in/vitorg-goncalves](https://linkedin.com/in/vitorg-goncalves)
- 🐙 [github.com/GaStormm](https://github.com/GaStormm)
- 📍 Florianópolis, SC — Brazil
- 🔎 Open to remote **SOC Analyst / Blue Team** roles
