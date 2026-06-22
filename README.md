<h1 align="center">Olá, eu sou Vitor 👋</h1>

<p align="center">
  <strong>IT Support N1/N2 · Blue Team enthusiast · Homelab builder</strong><br>
  Florianópolis, SC — Brasil
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CompTIA-Security%2B-brightgreen?style=flat-square&logo=comptia" />
  <img src="https://img.shields.io/badge/Microsoft-SC--900%20%7C%20SC--200-blue?style=flat-square&logo=microsoft" />
  <img src="https://img.shields.io/badge/Kubernetes-K3s-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Proxmox-VE-E57000?style=flat-square&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Wazuh-SIEM%2FXDR-4B0082?style=flat-square" />
</p>

---

## 👋 Sobre mim

Técnico de suporte de TI em ambiente hospitalar (N1/N2) com ~2 anos de experiência, sendo 1 ano em infraestrutura crítica de saúde. Estou em transição ativa para **Blue Team / SOC**, com foco em monitoramento, detecção de ameaças e resposta a incidentes.

Fora do trabalho, mantenho um **homelab com cluster Kubernetes** onde pratico configuração de SIEM, observabilidade e segurança de redes.

- 🎯 Foco: Blue Team · SOC Analyst · Segurança defensiva
- 📚 Estudando: CompTIA Security+ · SC-900 → SC-200 (Microsoft Sentinel)
- 🌐 Disponível para oportunidades remotas
- 📍 Baseado em Florianópolis, SC — Brasil

---

## 🛡️ Homelab

### Cluster K3s no Proxmox
- 3 nós Proxmox rodando **K3s Kubernetes**
- Namespaces: `homelab`, `monitoring`, `security`
- MetalLB + Traefik configurados para load balancing e ingress

### Stack de Monitoramento
| Serviço | IP | Função |
|---|---|---|
| AdGuard | 192.168.69.151 | DNS filtering |
| Zabbix | 192.168.69.152 | Infrastructure monitoring |
| Grafana | 192.168.69.153 | Dashboards & alertas |
| Prometheus | Alpine LXC | Métricas complementares |

### Stack de Segurança
- **Wazuh** (SIEM/XDR) integrado ao homelab
- **AWS EC2** conectado via Tailscale com Zabbix Proxy (SQLite3)
- CA própria com OpenSSL + Nginx Proxy Manager para HTTPS local
- VLANs no MikroTik hEX: VLAN 67 (servidores) · VLAN 69 (produção)

---

## 🔧 Stack técnica

**Segurança & Monitoramento**
`Wazuh` `Zabbix` `Grafana` `Prometheus` `AdGuard`

**Infraestrutura & Redes**
`Proxmox` `Kubernetes / K3s` `Docker` `Linux` `MikroTik` `VLANs`

**Cloud & Conectividade**
`AWS EC2` `Tailscale` `Nginx Proxy Manager` `WireGuard`

---

## 🌐 Idiomas

| Idioma | Nível |
|---|---|
| 🇧🇷 Português | Nativo |
| 🇪🇸 Espanhol | Fluente |
| 🇺🇸 Inglês | Avançado (C1) |

---

## 📫 Contato

- 💼 [LinkedIn](https://linkedin.com/in/vitorg-goncalves/)
- 📧 vitorg.gcoelho@gmail.com
- 🔎 Aberto a oportunidades remotas em Blue Team / SOC
