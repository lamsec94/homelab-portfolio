# Production IT Infrastructure Homelab

[![Uptime](https://img.shields.io/badge/Uptime-99%25%2B-brightgreen)](http://uptime.lab)
[![Services](https://img.shields.io/badge/Services-15%2B-blue)]()
[![Security](https://img.shields.io/badge/SIEM-Wazuh-red)]()

> **Enterprise-grade security monitoring, network management, and systems administration**

## 🎯 Live Infrastructure Dashboard

**Heimdall Dashboard:** [Access via VPN] | **Uptime Status:** [http://uptime.lab](http://uptime.lab)

![Homelab Architecture](https://i.imgur.com/your-network-diagram.png)
*Multi-VLAN architecture with 15+ monitored services achieving 99%+ uptime*

---

## 🔒 Security Operations Stack

**Enterprise SIEM & Threat Detection:**
- **Wazuh SIEM** - Real-time security monitoring across 10+ Linux endpoints
- **Suricata IDS/IPS** - Network intrusion detection with 30k+ threat signatures
- **AdGuard Home** - DNS-based security filtering (300k+ malicious domains blocked)
- **Integrated Alerting** - Centralized threat correlation and incident response

**Key Security Achievements:**
- ✅ Deployed production SIEM monitoring 10+ endpoints with log aggregation
- ✅ Configured IDS/IPS integrated with Wazuh for automated alert correlation
- ✅ Implemented DNS-based threat blocking filtering 300k+ malicious domains
- ✅ Achieved 99%+ infrastructure uptime with 24/7 monitoring

---

## 🌐 Network & Infrastructure

**Virtualization Platform:**
- **Proxmox VE** - Type-1 hypervisor managing 10+ LXC containers
- **LXC Containerization** - Isolated service deployment (Debian/Ubuntu-based)
- **Resource Management** - 48GB RAM / 2TB SSD optimized allocation

**Network Architecture:**
- **Multi-VLAN Design** - Network segmentation (VLAN 11: Lab, VLAN 30: Services)
- **Custom DNS Namespace** - 17 internal service routes (*.lab domains)
- **Nginx Reverse Proxy** - Centralized SSL termination and service routing
- **Tailscale VPN** - Secure remote access with subnet routing

**Hardware:**
- Lenovo ThinkCentre M910 Tower (Intel i7-6700, 48GB RAM, 2TB SSD)
- Raspberry Pi 5 (DNS server, VPN gateway)
- TP-Link ER7206 Business Router + Netgear Managed Switch

---

## 📊 Monitoring & Management

**24/7 Infrastructure Monitoring:**
- **Uptime Kuma** - Service health monitoring (6 active monitors, 99%+ availability)
- **Wazuh Dashboards** - Security event visualization and threat analysis
- **Portainer** - Docker container management and resource monitoring
- **Heimdall** - Centralized service dashboard for infrastructure access

**IT Service Management:**
- **GLPI** - IT ticketing system, asset tracking, inventory management
- **NextCloud** - Self-hosted cloud storage and file collaboration
- **Vaultwarden** - Password manager for infrastructure credentials
- **Nginx Proxy Manager** - Web-based reverse proxy configuration

---

## 📈 Key Achievements

| Metric | Result |
|--------|--------|
| **Service Uptime** | 99%+ across 6 monitored services |
| **Monitored Endpoints** | 10+ Linux systems (Debian, Ubuntu, containers) |
| **Security Coverage** | SIEM + IDS/IPS with 30k+ threat signatures |
| **DNS Filtering** | 300k+ malicious domains blocked |
| **Network Segmentation** | 2 VLANs with custom routing |
| **Services Managed** | 15+ production applications |

---

## 🛠️ Technical Skills

**Virtualization & Containers:**
- Proxmox VE (LXC, KVM/QEMU, snapshots, backups)
- Docker (CasaOS, Portainer, container orchestration)
- Resource optimization and capacity planning

**Security Operations:**
- SIEM deployment and log analysis (Wazuh)
- IDS/IPS configuration and tuning (Suricata)
- DNS-based security filtering (AdGuard Home)
- Security hardening and vulnerability management

**Linux System Administration:**
- Multi-distro proficiency (Debian, Ubuntu, Arch-based)
- Service management (systemd, cron, process monitoring)
- Package management (apt, pacman)
- Shell scripting (bash) for automation

**Networking:**
- VLAN configuration and network segmentation
- DNS/DHCP service management
- Reverse proxy configuration (Nginx)
- VPN deployment (Tailscale, subnet routing)
- TCP/IP, subnetting, routing fundamentals

**Monitoring & Troubleshooting:**
- Service availability monitoring (Uptime Kuma)
- Log aggregation and analysis
- Performance metrics collection
- Incident response and root cause analysis

---

## 🎓 Certifications & Training

**In Progress:**
- CompTIA Network+ (N10-009) - Target: December 2025

**Homelab Learning Focus:**
- Network fundamentals and troubleshooting
- Security monitoring and incident response
- Linux server administration
- Infrastructure documentation

---

## 📁 Infrastructure Services

### Security Stack
- **Wazuh SIEM** (Container 105) - Security monitoring, log aggregation
- **Suricata IDS/IPS** (Container 104) - Network intrusion detection
- **AdGuard Home** (Raspberry Pi 5) - DNS filtering, custom namespace

### Core Infrastructure
- **Proxmox VE** (192.168.11.10) - Hypervisor host
- **CasaOS** (Container 113) - Docker container platform
- **Nginx Proxy Manager** (Container 112) - Reverse proxy, SSL
- **Uptime Kuma** - 24/7 service monitoring

### Applications & Services
- **NextCloud** (Container 106) - Cloud storage
- **GLPI** (Container 110) - IT ticketing and asset management
- **Vaultwarden** - Password management
- **Heimdall** - Service dashboard
- **Portainer** - Container management
- **Docmost** - Technical documentation wiki

### Network Services
- **TP-Link ER7206** (192.168.11.1) - Business gateway router
- **Netgear Switch** - Managed VLAN configuration
- **Tailscale VPN** - Secure remote access

---

## 🎯 Project Goals

This homelab demonstrates practical IT skills for:
- **Help Desk Technician** - Troubleshooting, ticketing systems, user support
- **Junior Systems Administrator** - Linux/Windows server management, monitoring
- **SOC Analyst** - SIEM operations, threat detection, log analysis
- **Network Technician** - VLAN configuration, DNS/DHCP, routing

**Career Focus:** Hands-on experience with enterprise tools and methodologies applicable to entry-level IT operations and security roles.

---

## 📸 Screenshots

*Coming soon: Network diagram, Wazuh dashboard, Uptime Kuma monitoring, Heimdall interface*

---

**👨‍💻 Built by:** Lamar Scott  
**📧 Contact:** [scottlamar05@gmail.com](mailto:scottlamar05@gmail.com)  
**💼 LinkedIn:** [https://linkedin.com/in/lamar-s-b02100260/](https://linkedin.com/in/lamar-s-b02100260/)  
**📁 GitHub:** [lamsec94](https://github.com/lamsec94)  

---

*This homelab-portfolio is maintained by [lamsec94](https://github.com/lamsec94)*
