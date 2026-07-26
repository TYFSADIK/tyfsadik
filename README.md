<!-- markdownlint-disable-file MD033 -->
<div align="center">

<h1>MD. Taki Yasir Faraji Sadik</h1>
<h3>Cybersecurity Analyst & SOC Specialist</h3>

<a href="https://tyfsadik.org">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=780&height=45&lines=Security+Operations+Center+(SOC)+%26+Incident+Response;Cloud+Security+(Azure,+AWS)+%26+Infrastructure+Defense;Architect+of+a+25-Project+Homelab+%26+7-Node+K8s+Cluster;Training+and+Serving+AI+Models+on+Hardware+I+Own" alt="specializations" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=TYFSADIK&label=Profile%20views&color=7aa2f7&style=flat" alt="profile views" />
  <img src="https://img.shields.io/badge/Open_to-SOC_%2F_Cloud_Security_Roles-9ece6a?style=flat&labelColor=1a1b26" alt="open to work" />
  <img src="https://img.shields.io/badge/Based_in-Toronto,_CA-7aa2f7?style=flat&labelColor=1a1b26" alt="location" />
  <img src="https://img.shields.io/badge/Certifications-15%2B-bb9af7?style=flat&labelColor=1a1b26" alt="certifications" />
</p>

<img src="https://github-profile-trophy-fork-two.vercel.app/?username=TYFSADIK&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7&title=Commits,Repositories,Stars,Followers,PullRequest,MultiLanguage,Experience" alt="trophies" />

<h3><a href="https://tyfsadik.org" target="_blank">www.tyfsadik.org</a></h3>

[![Gmail](https://skillicons.dev/icons?i=gmail)](mailto:taki@tyfsadik.org)
[![LinkedIn](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/md-taki-yasir-faraji-sadik-63a026278/)
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/TYFSADIK)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

</div>

## 👨‍💻 About Me

As a Cybersecurity Analyst and SOC Specialist, my focus is the detection, triage, and response side of security operations — reading alerts, tracing root cause, and closing the loop before a small anomaly becomes an incident. 

I split my time between hardening Azure and AWS cloud infrastructure and running a production-grade, **25-project homelab ecosystem**. This ecosystem is anchored by a **7-node bare-metal Kubernetes cluster** that hosts everything from a self-trained 7B LLM to a zero-public-ingress private cloud. Everything in it is built, broken, and rebuilt by hand. This hands-on loop, backed by **116+ documented lab writeups** and industry certifications, is where my deepest infrastructure defense knowledge comes from.

<div align="center">

<p>
  <img src="https://img.shields.io/badge/Homelab_Projects-25%2B-e0af68?style=for-the-badge&labelColor=1a1b26" alt="25+ projects" />
  <img src="https://img.shields.io/badge/Lab_Writeups-116%2B-9ece6a?style=for-the-badge&labelColor=1a1b26" alt="116+ labs" />
  <img src="https://img.shields.io/badge/K8s_Cluster-7_Nodes-7aa2f7?style=for-the-badge&labelColor=1a1b26" alt="7 node k8s" />
  <img src="https://img.shields.io/badge/DNS_Records-31-bb9af7?style=for-the-badge&labelColor=1a1b26" alt="31 dns records" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

</div>

## 🚀 Flagship Projects

<table>
<tr>
<td valign="top" width="50%">

**[7-Node Bare-Metal Kubernetes Cluster](https://tyfsadik.org/work/infrastructure/kubernetes-infrastructure.html)**  
Production-grade K8s cluster across 3 desktop PCs and 4 laptops on a Proxmox/kubeadm base, with VLAN-segmented networking (Mgmt/Cluster/Storage), Calico for CNI/NetworkPolicy, MetalLB for bare-metal LoadBalancers, Longhorn for 3x-replicated storage, and a Prometheus + Grafana + Loki observability stack.  
<br>`Kubernetes` `Calico` `MetalLB` `Longhorn` `Prometheus` `Grafana`

</td>
<td valign="top" width="50%">

**[TYF-AI — Self-Hosted Local AI Security Platform](https://tyfsadik.org/work/infrastructure/tyf-ai-platform.html)**  
Hardened local inference stack treating the model runtime as an untrusted workload: `llama.cpp` with CUDA behind an authenticated Caddy reverse proxy, per-model Firejail sandboxing (`--net=none`), SHA-256-pinned GGUF weights, and GPU passthrough on Proxmox. STRIDE-modeled end-to-end.  
<br>`llama.cpp` `CUDA` `Caddy` `Firejail` `Proxmox` `GPU Passthrough`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**[Proxmox VE Zero-Trust Private Cloud](https://tyfsadik.org/work/infrastructure/proxmox-zero-trust.html)**  
3-node Proxmox VE HA cluster on Ceph with four trust-tiered VLANs and zero public ingress. The only path in is a policy-gated Cloudflare Tunnel, with a Tailscale mesh as authenticated fallback. Automated hourly/daily/30-day ZFS snapshots via sanoid/syncoid.  
<br>`Proxmox VE` `Ceph` `Cloudflare Tunnel` `Tailscale` `ZFS`

</td>
<td valign="top" width="50%">

**[Data Sovereignty & Secure Media Stack](https://tyfsadik.org/work/infrastructure/data-sovereignty-stack.html)**  
Nextcloud AIO and Immich replacing Google Drive/Photos entirely, running on a zstd-compressed BTRFS pool across external SSDs with per-user ACL isolation. A 3-2-1 backup pipeline (local BTRFS snapshot → BorgBase → rsync.net) runs with zero data-loss events.  
<br>`Nextcloud` `Immich` `BTRFS` `BorgBase` `rsync.net`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**[Chakor — Self-Hosted AI Workspace](https://ai.tyfsadik.org)** *(MIT, Open Source)*  
A Next.js 15 / TypeScript AI workspace you run on your own hardware. Features local engines (llama.cpp, Ollama), hardware-aware `FITS`/`TIGHT`/`TOO BIG` fit tagging to prevent OOM loads, in-app GGUF downloads, web search, document chat, and cross-conversation memory in a local SQLite store.  
<br>`Next.js 15` `TypeScript` `SQLite` `llama.cpp` `Ollama`

</td>
<td valign="top" width="50%">

**[Chakor — Custom 7B LLM from Scratch](https://ai.tyfsadik.org)**  
A ~7B-parameter decoder-only transformer (32 layers, 32 heads, 4096 hidden dim) written and trained from random initialization in PyTorch. Pretrained on a 100B+ token curated corpus via distributed multi-GPU DDP, instruction-tuned, then converted to GGUF and served 24/7.  
<br>`PyTorch` `Distributed Training` `GGUF` `llama.cpp` `Next.js`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**[Automated SOC Pipeline](https://tyfsadik.org/work.html)**  
Wazuh detections wired into TheHive case management with MISP threat-intel enrichment. Custom detection rules tagged to MITRE ATT&CK technique IDs, with automated active response blocking brute-force sources.  
<br>`Wazuh` `TheHive` `Cortex` `MISP` `MITRE ATT&CK`

</td>
<td valign="top" width="50%">

**[Active Directory Threat Hunting Lab](https://tyfsadik.org/blog/labs/security/ad-threat-hunting.html)**  
Instrumented AD forest with Sysmon and Splunk; hunted Kerberoasting, Pass-the-Hash, and Golden Ticket attacks. Deployed honeypot SPN account for high-fidelity early warning, detecting PtH within 2 minutes and mapping 15+ lateral-movement paths.  
<br>`BloodHound` `SharpHound` `Sysmon` `Splunk` `Kerberos`

</td>
</tr>
</table>

<details>
<summary><strong>📂 Additional Self-Hosted Services (Click to Expand)</strong></summary>
<br>

| Service | Stack | Endpoint / Status |
|---|---|---|
| **Cloud Storage** | Nextcloud, MariaDB, Docker | `cloud.tyfsadik.org` |
| **Photo Management** | Immich, PostgreSQL, ML face recognition | `photo.tyfsadik.org` |
| **Private Search Engine** | SearXNG, Docker, Nginx | `search.tyfsadik.org` |
| **Public Wiki Mirror** | Kiwix, full Wikipedia mirror | `wiki.tyfsadik.org` |
| **Network DNS** | Pi-hole + Unbound, recursive resolution | Internal Network |
| **Private Email Server** | Postfix + Dovecot + DKIM | `@tyfsadik.org` |
| **Remote Desktop** | Arch Linux + XFCE via WSL2 (No port forwarding) | ⭐ 5 GitHub Stars |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 💼 Professional Experience

- **Incident Analyst** @ **Shield Security Systems** *(Nov 2025 – Present)*  
  Monitor security systems, triage alerts, and escalate events per SOPs. Perform ongoing threat assessments and vulnerability analysis.
- **Incident Manager** @ **CN Tower / Tour CN** *(Aug 2025 – Present)*  
  Lead end-to-end incident lifecycle: detection, triage, prioritization, escalation, resolution, and post-incident review for critical infrastructure.
- **Cloud Support Engineer (Intern)** @ **Microsoft** *(May 2025 – Sep 2025)*  
  Provided cloud support engineering for Azure-based enterprise customers, diagnosing and resolving infrastructure, networking, and identity issues.
- **Network Analyst Intern** @ **CardiOCare** *(Jan 2025 – Sep 2025)*  
  Monitored network infrastructure, performed packet analysis/traffic monitoring using IDS, and supported deployment of cloud-connected devices.
- **Server Operator (Junior)** @ **Fiera Foods** *(Jun 2024 – Jul 2025)*  
  Managed server alerts on Linux/Windows Server, performed daily maintenance (backups, patching), and leveraged SQL for data workflows.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 🛠️ Technical Skills

<table>
<tr>
<td valign="top" align="center" width="33%">

### ☁️ Cloud & DevOps
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare,docker,kubernetes,nginx,ansible,terraform,prometheus,grafana,git&perline=4" alt="cloud and devops skills" />

</td>
<td valign="top" align="center" width="33%">

### 🖥️ Systems & Security
<img src="https://skillicons.dev/icons?i=linux,ubuntu,kali,debian,bash,powershell,vim,regex&perline=4" alt="systems and security skills" />

</td>
<td valign="top" align="center" width="33%">

### 💻 Languages & Data
<img src="https://skillicons.dev/icons?i=python,ts,js,php,rust,mysql,postgres,mongodb&perline=4" alt="languages and data skills" />

</td>
</tr>
</table>

<div align="center">

**🛡️ SOC / Security Tooling**  
`Splunk` `Wireshark` `Nmap` `Metasploit` `Burp Suite` `Wazuh` `TheHive` `Cortex` `MISP` `BloodHound` `Sysmon` `YARA` `nftables`

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 🎓 Education & Certifications

**Education**
- **Advanced Diploma, Computer Networking & Cybersecurity** | Seneca Polytechnic *(2023 – 2026)*
- **BSc, Computer Networking & Cybersecurity** | University of Toronto *(2022 – 2026)*

**Key Certifications**
- ✅ **Microsoft**: Azure Fundamentals (AZ-900), MSSQL Certification
- ✅ **Amazon Web Services**: Cloud Practitioner, AWS Academy Cloud Security
- ✅ **CompTIA**: A+ Certified Professional *(Security+ In Progress)*
- ✅ **Cisco**: CCNA Fundamentals, Cybersecurity Defense Analyst *(Expected May 2026)*
- ✅ **OPSWAT**: Critical Infrastructure Protection (CIP), ICIP
- ✅ **ISC2**: Certified in Cybersecurity (CC) Candidate
- ✅ **Other**: Ontario Security Guard Licence, Smart Serve Ontario, First Aid & CPR

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 🌐 Live Infrastructure

<p>31 DNS records managed across <code>tyfsadik.org</code>, all fronted by Cloudflare Tunnels — <strong>no service on the homelab exposes a public port directly</strong>.</p>

<p>
  <img src="https://img.shields.io/badge/Requests-296K-7aa2f7?style=flat-square&labelColor=1a1b26" alt="296k requests" />
  <img src="https://img.shields.io/badge/Visits-101K-9ece6a?style=flat-square&labelColor=1a1b26" alt="101k visits" />
  <img src="https://img.shields.io/badge/Countries-113-e0af68?style=flat-square&labelColor=1a1b26" alt="113 countries" />
  <img src="https://img.shields.io/badge/TLS_1.3-65.8%25-bb9af7?style=flat-square&labelColor=1a1b26" alt="65.8% TLS 1.3" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 📊 GitHub Statistics

<table>
<tr>
<td valign="top" width="50%">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=TYFSADIK&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true" alt="github stats" />

</td>
<td valign="top" width="50%">

<img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=TYFSADIK&theme=tokyonight" alt="languages" />

</td>
</tr>
<tr>
<td valign="top" width="50%">

<img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TYFSADIK&theme=tokyonight" alt="profile details" />

</td>
<td valign="top" width="50%">

<img src="https://streak-stats.demolab.com?user=TYFSADIK&theme=tokyonight&hide_border=true" alt="streak" />

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

## 📈 Activity Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TYFSADIK&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" alt="contribution activity graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=120&section=footer&text=Securing%20infrastructure%20from%20the%20ground%20up&fontSize=15&fontColor=c0caf5&fontAlignY=75" alt="footer wave" />
