# Awesome-Cloud-Network-Firewall

# Awesome-Cloud-Network-Firewall



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud Firewalls, Network Security & Virtual Appliances*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Network Firewalls**. These tools help organizations protect cloud workloads with stateful inspection, intrusion prevention, and centralized policy management across multi-cloud environments.



**Examples** include Azure Firewall, AWS Network Firewall, Google Cloud Armor, Palo Alto VM-Series, Fortinet FortiGate-VM, Check Point CloudGuard, Cisco Secure Firewall, SonicWall NSv, Sophos XG Firewall, and Barracuda CloudGen Firewall (the category leaders).



**Open-source emphasis**: Cloud network firewalls have a **mature open-source foundation**, with **OPNsense**, **pfSense**, and **VyOS** leading as full-featured NGFW alternatives . **OpenSnitch** provides application-level firewall control for Linux with **9,748 stars** , and **Portmaster** offers privacy-focused network monitoring with **8,544 stars** . However, **no open-source firewall matches the managed cloud integration** of AWS Network Firewall, Azure Firewall, or GCP Cloud Armor. This section documents these production-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global enterprise firewall market is estimated at **~$15.8B in 2026**, with hardware appliances capturing **47.65% of 2025 revenues** and cloud-native Firewall-as-a-Service growing at **13.68% CAGR** through 2031 . North America led with **35.02% of 2025 revenues**, while Asia-Pacific is set for the fastest growth at **12.38% CAGR** . The sector is **moderately concentrated** — Cisco, Palo Alto, Fortinet, and Check Point dominate on-premises, while cloud providers (AWS, Azure, GCP) bundle native firewalls as value-adds. No single vendor holds a winner-take-all position; enterprises typically run hybrid appliance + cloud-native stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[AWS Network Firewall](https://aws.amazon.com/network-firewall/)** | Managed, cloud-native firewall for VPC-level protection with stateful inspection, intrusion prevention, and centralized policy. | **$0.395/hour per firewall endpoint** + **$0.065/GB processed** . | **AWS Free Tier**: New accounts get **$100–$200 credits**. No perpetual free tier for Network Firewall. | **~$638B revenue (Amazon FY2025)** |

| **[Azure Firewall](https://azure.microsoft.com/en-us/products/azure-firewall/)** | Cloud-native firewall with built-in threat intelligence, FQDN filtering, and centralized policy across VNets . | **Standard**: **$0.016/hour** (~$11.52/month) + data processing . | **Azure free account**: **$200 credit for 30 days** + 12 months of free services. No perpetual free tier. | **~$281B revenue (Microsoft FY2025)** |

| **[Google Cloud Armor](https://cloud.google.com/armor)** | DDoS protection and WAF for Google Cloud workloads. Provides Layer 7 filtering and adaptive protection . | **Custom pricing** — typically **$0.75/rule/month** + **$0.05/GB processed**. | **Google Cloud Free Tier**: **$300 credit for 90 days**. No perpetual free tier for Cloud Armor. | **~$350B revenue (Alphabet FY2025)** |

| **[Palo Alto VM-Series](https://www.paloaltonetworks.com/)** | Virtualized next-gen firewall for public and private clouds. Same PAN-OS features as hardware appliances. | **Custom enterprise pricing** — quote required. Typical entry contracts **$15K–$50K/year**. | **None** — enterprise demo required. | **~$9.2B revenue (Palo Alto FY2025)** |

| **[Fortinet FortiGate-VM](https://www.fortinet.com/)** | Virtualized NGFW with FortiOS. Supports all major hypervisors and cloud platforms. | **Custom enterprise pricing** — quote required. Entry-level **FortiGate-VM01** starts at **~$1,500/year**. | **FortiGate-VM evaluation license**: Free 15-day trial. | **~$5.5B revenue (Fortinet FY2025)** |

| **[Check Point CloudGuard](https://www.checkpoint.com/)** | Cloud-native security with NGFW, threat prevention, and posture management. | **Custom enterprise pricing** — quote required. | **CloudGuard Network Security**: Free 30-day trial. | **~$2.5B revenue (Check Point FY2025)** |

| **[Cisco Secure Firewall](https://www.cisco.com/)** | Enterprise NGFW with Snort 3 IPS, URL filtering, and advanced malware protection. **Hardware**: **$1,136** (CSF220-TD-K9) . **Small Business Edition 3-year**: **$2,196.99** . | **None** — enterprise demo required. | **~$63B revenue (Cisco FY2025)** |

| **[SonicWall NSv](https://www.sonicwall.com/)** | Virtual firewall with advanced threat protection. **NSv 270 2-year**: **$4,036.65** . **3-year**: **$5,964.71** . | **None** — enterprise demo required. | **Private (~$500M+ revenue est.)** |

| **[Sophos XG Firewall](https://www.sophos.com/)** | Synchronized security firewall with Xstream architecture. | **XG 450 Full Guard 5-year**: **₹1,895,510** (~$22,700) . **XG 650 3-year**: **₹2,153,500** (~$25,800) . | **None** — enterprise demo required. | **Private (~$700M+ revenue est.)** |

| **[Barracuda CloudGen Firewall](https://www.barracuda.com/)** | Cloud-optimized firewall with SD-WAN. **F-Series F12**: **$1,034.40** . **GCP Level 2**: **$345.99** . **Remote Access (1 month, 4 cores)**: **$67.82** . | **None** — enterprise demo required. | **Private (~$500M+ revenue est.)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[OpenSnitch](https://github.com/evilsocket/opensnitch)** — **GNU/Linux interactive application firewall** inspired by Little Snitch. Outbound connection control, process-level filtering, GUI . | [![Stars](https://img.shields.io/github/stars/evilsocket/opensnitch?style=social&color=white)](https://github.com/evilsocket/opensnitch/stargazers) | ~9,748 |

| **[Portmaster](https://github.com/safing/portmaster)** — **Privacy-focused network monitor and firewall.** Block mass surveillance, control app connections, DNS filtering . | [![Stars](https://img.shields.io/github/stars/safing/portmaster?style=social&color=white)](https://github.com/safing/portmaster/stargazers) | ~8,544 |

| **[OPNsense](https://github.com/opnsense/core)** — **Full-featured open-source NGFW.** Firewall, QoS, VPN, IDS/IPS, and more. Actively maintained (2025 releases) . | [![Stars](https://img.shields.io/github/stars/opnsense/core?style=social&color=white)](https://github.com/opnsense/core/stargazers) | ~3,500 |

| **[pfSense](https://github.com/pfsense/pfsense)** — **The most widely deployed open-source firewall.** Based on FreeBSD, mature and stable with huge community . | [![Stars](https://img.shields.io/github/stars/pfsense/pfsense?style=social&color=white)](https://github.com/pfsense/pfsense/stargazers) | ~2,500 |

| **[VyOS](https://github.com/vyos/vyos-1x)** — **Open-source router and firewall platform.** More router than firewall, with server control tools . | [![Stars](https://img.shields.io/github/stars/vyos/vyos-1x?style=social&color=white)](https://github.com/vyos/vyos-1x/stargazers) | ~2,000 |

| **[BunkerWeb](https://github.com/bunkerity/bunkerweb)** — **Open-source WAF/WAAP.** OWASP Top 10 protection, antibot, DDoS mitigation, SSL offloading . | [![Stars](https://img.shields.io/github/stars/bunkerity/bunkerweb?style=social&color=white)](https://github.com/bunkerity/bunkerweb/stargazers) | ~7,500 |

| **[IPFire](https://github.com/ipfire/ipfire-2.x)** — **Specialized Linux distribution for creating a firewall.** Active releases in 2025 . | [![Stars](https://img.shields.io/github/stars/ipfire/ipfire-2.x?style=social&color=white)](https://github.com/ipfire/ipfire-2.x/stargazers) | ~1,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[CrowdSec](https://github.com/crowdsecurity/crowdsec)** — Collaborative IPS/IDS with WAF engine. Blocks SQLi, XSS, and OWASP Top 10 . | [![Stars](https://img.shields.io/github/stars/crowdsecurity/crowdsec?style=social&color=white)](https://github.com/crowdsecurity/crowdsec/stargazers) |

| **[ModSecurity](https://github.com/SpiderLabs/ModSecurity)** — The original open-source WAF engine. Works with Apache, Nginx, IIS . | [![Stars](https://img.shields.io/github/stars/SpiderLabs/ModSecurity?style=social&color=white)](https://github.com/SpiderLabs/ModSecurity/stargazers) |

| **[Suricata](https://github.com/OISF/suricata)** — Open-source IDS/IPS/NSM engine. High-performance threat detection . | [![Stars](https://img.shields.io/github/stars/OISF/suricata?style=social&color=white)](https://github.com/OISF/suricata/stargazers) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud firewalls handle sensitive network traffic and security policies; ensure proper configuration, logging, and compliance with organizational security requirements.

- **Open-source reality**: The open-source ecosystem for network firewalls is **mature and production-proven** at the **appliance layer** (**OPNsense**, **pfSense**, **VyOS**) and **application-level control** (**OpenSnitch**, **Portmaster**) . However, **no open-source alternative matches the managed cloud integration** of AWS Network Firewall, Azure Firewall, or GCP Cloud Armor — these provide native VPC/VNet integration, centralized policy, and cloud-native threat intelligence that require significant engineering to replicate. The open-source path is **genuinely viable** for **self-hosted network security**, **application-level filtering**, or **organizations with strong infrastructure engineering capacity**.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. Firewall pricing is notoriously complex — appliance costs, subscription licenses, support contracts, and throughput tiers all affect total cost. Always request a formal quote for accurate budgeting.



---



**Made for network security engineers, cloud architects, platform teams, and infrastructure specialists.**

Let's make cloud network security more open, transparent, and accessible.
