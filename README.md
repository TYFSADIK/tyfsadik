<div align="center">
<img src="./hero-banner.svg" alt="Taki Sadik - Cybersecurity Analyst & Homelab Architect" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=800&height=45&lines=Security+Operations+Center+(SOC)+%26+Incident+Response;Cloud+Security+(Azure,+AWS)+%26+Infrastructure+Defense;25-Project+Homelab+%26+7-Node+Bare-Metal+K8s+Cluster;Full-Stack+Web+Developer+%7C+Open+Source+Contributor" alt="typing" />


<a href="https://tyfsadik.org">
<a href="mailto:taki@tyfsadik.org">
<a href="https://www.linkedin.com/in/md-taki-yasir-faraji-sadik-63a026278/">

<img src="https://img.shields.io/badge/Open_to-SOC_%2F_Cloud_Security_Roles-9ece6a?style=flat&labelColor=1a1b26" />
<img src="https://img.shields.io/badge/Based_in-Toronto,_CA-7aa2f7?style=flat&labelColor=1a1b26" />


</div>
I detect, triage, and respond to security incidents. I also build infrastructure that defends itself.
SOC analyst by day. Homelab architect by night. I harden Azure and AWS cloud environments professionally, then come home to a production-grade lab where I break and rebuild everything from bare-metal Kubernetes to self-hosted LLMs. The hands-on loop is where I actually learned to defend infrastructure.
<div align="center">
Table
Labs	K8s Nodes	DNS Records	Projects	Certs
116	7	31	25	20+
</div>
Featured Work
7-Node Bare-Metal Kubernetes Cluster
Production K8s on Proxmox. VLAN-segmented networking, Calico CNI with NetworkPolicy, MetalLB, Longhorn 3x replication, Prometheus + Grafana + Loki observability. Every self-hosted service runs here.
Kubernetes Calico MetalLB Longhorn Prometheus Grafana Proxmox
TYF-AI - Self-Hosted Local AI Security Platform
Hardened inference stack: llama.cpp with CUDA behind authenticated Caddy proxy, per-model Firejail sandboxing (--net=none), SHA-256-pinned GGUF weights, GPU passthrough. STRIDE-modeled. 50+ concurrent queries, sub-2s latency, zero external API calls.
llama.cpp CUDA Caddy Firejail Proxmox GPU Passthrough
Proxmox VE Zero-Trust Private Cloud
3-node HA cluster on Ceph. Four trust-tiered VLANs. Zero public ingress; Cloudflare Tunnel only, Tailscale fallback. Automated ZFS snapshots. 100% public IP elimination, sub-50ms global latency.
Proxmox VE Ceph Cloudflare Tunnel Tailscale ZFS
Automated SOC Pipeline
Wazuh detections wired into TheHive case management with MISP threat-intel enrichment. Custom MITRE ATT&CK-tagged detection rules. Automated active response blocking brute-force sources.
Wazuh TheHive MISP MITRE ATT&CK
AD Threat Hunting Lab
Instrumented AD forest with Sysmon + Splunk. Hunted Kerberoasting, Pass-the-Hash, Golden Ticket. Honeypot SPN for early warning. PtH detected in 2 minutes; 15+ lateral paths to Domain Admin mapped.
BloodHound Sysmon Splunk Kerberos
<details>
<summary><strong>More services running on tyfsadik.org</strong></summary>
Table
Service	Stack	Endpoint
Private Search	SearXNG	search.tyfsadik.org
Cloud Storage	Nextcloud AIO	cloud.tyfsadik.org
Photos	Immich + PostgreSQL	photo.tyfsadik.org
Wiki	Kiwix full mirror	wiki.tyfsadik.org
DNS	Pi-hole + Unbound	Internal
Email	Postfix + Dovecot + DKIM	@tyfsadik.org
OSINT Dashboard	FastAPI + 22 tools	osint.tyfsadik.org
Remote Desktop	Arch + XFCE via WSL2	5 stars
</details>
Experience
Table
Role	Company	When
Incident Manager	CN Tower / Tour CN	Aug 2025 - Present
Incident Analyst	Shield Security Systems	Nov 2025 - Present
Cloud Support Engineer (Intern)	Microsoft	May 2025 - Sep 2025
Network Analyst Intern	CardiOCare	Jan 2025 - Sep 2025
Server Operator (Junior)	Fiera Foods	Jun 2024 - Jul 2025
Surveillance Operator / Help Desk	Elite Force / Rogers Centre	Sep 2022 - Nov 2023
Certifications
Table
Certification	Issuer	Status
Azure Fundamentals (AZ-900)	Microsoft	Active
AWS Cloud Practitioner	AWS	Active
AWS Academy - Cloud Security	AWS	Active
CompTIA A+	CompTIA	Active
CCNA Fundamentals	Cisco	Active
OPSWAT CIP	OPSWAT	Mar 2026 - Feb 2027
OPSWAT ICIP	OPSWAT	Mar 2026 - Mar 2027
ISC2 Candidate (CC)	ISC2	Aug 2025 - Aug 2026
Ontario Security Guard Licence	Ontario Gov	Active
Cybersecurity Defense Analyst	Cisco	Target: May 2026
CompTIA Security+	CompTIA	In Progress
Google Cybersecurity	Google	Target: Feb 2026
IBM Cybersecurity Tools	IBM	Target: Feb 2026
MSSQL Certification	Microsoft	Active
First Aid & CPR	-	Active
Tech Stack
<div align="center">
Cloud & DevOps


<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare,docker,kubernetes,nginx,ansible,terraform,prometheus,grafana,git&perline=6" />
Systems & Security


<img src="https://skillicons.dev/icons?i=linux,ubuntu,kali,debian,bash,powershell,vim,regex&perline=6" />
Languages & Data


<img src="https://skillicons.dev/icons?i=python,ts,js,php,rust,mysql,postgres,mongodb&perline=6" />

Splunk Wireshark Nmap Metasploit Burp Suite Wazuh TheHive Cortex MISP BloodHound Sysmon YARA nftables
</div>
Education

    Seneca Polytechnic - Advanced Diploma, Computer Networking & Cybersecurity Jan 2023 - Apr 2026
    University of Toronto - BSc, Computer Networking & Cybersecurity (Information Analysis) 2022 - 2026
    Alison Academy - Diploma, Ethical Hacking 2024
    Scarborough Training Centre - A+ Certified Professional Course 2024

Infrastructure at a Glance
<div align="center">
31 DNS records. Zero public ports. All traffic through Cloudflare Tunnels.
<img src="https://img.shields.io/badge/Requests-296K-7aa2f7?style=flat-square&labelColor=1a1b26" />
<img src="https://img.shields.io/badge/Visits-101K-9ece6a?style=flat-square&labelColor=1a1b26" />
<img src="https://img.shields.io/badge/Countries-113-e0af68?style=flat-square&labelColor=1a1b26" />
<img src="https://img.shields.io/badge/TLS_1.3-65.8%25-bb9af7?style=flat-square&labelColor=1a1b26" />
</div>
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=TYFSADIK&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&hide_title=true&card_width=500" />

<img src="https://streak-stats.demolab.com?user=TYFSADIK&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TYFSADIK&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph&height=280" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
</picture>


<a href="https://tyfsadik.org">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=120&section=footer&text=Securing%20infrastructure%20from%20the%20ground%20up&fontSize=15&fontColor=c0caf5&fontAlignY=75" />
</a>
</div>
