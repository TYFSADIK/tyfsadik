<!-- markdownlint-disable-file MD033 -->
<div align="center">
<img width="1942" height="809" alt="Home_Lab" src="https://github.com/user-attachments/assets/79faa19f-81db-4697-9a06-a03246f5c348" />
<a href="https://tyfsadik.org">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=800&height=45&lines=SOC+%26+Incident+Response+%7C+Threat+Detection;Cloud+Security+(Azure,+AWS)+%26+Infrastructure+Defense;Defence+Tech+%26+Robotics+(SDR,+ROS+2,+LoRa);7-Node+Bare-Metal+K8s+%26+Zero-Trust+Homelab;Full-Stack+Web+Developer+%7C+Open+Source+Contributor" alt="specializations" />
</a>
<p>
<img src="https://komarev.com/ghpvc/?username=TYFSADIK&label=Profile%20views&color=7aa2f7&style=flat" alt="profile views" />
<img src="https://img.shields.io/badge/Open_to-SOC_%2F_Cloud_%2F_Defence_Roles-9ece6a?style=flat&labelColor=1a1b26" alt="open to work" />
<img src="https://img.shields.io/badge/Based_in-North_York,_Toronto-7aa2f7?style=flat&labelColor=1a1b26" alt="location" />
<img src="https://img.shields.io/badge/Certifications-25+-e0af68?style=flat&labelColor=1a1b26" alt="25 plus certifications" />
</p>
<h3><a href="https://tyfsadik.org" target="_blank" rel="noopener">www.tyfsadik.org</a></h3>
<a href="mailto:taki@tyfsadik.org"><img src="https://skillicons.dev/icons?i=gmail" alt="Gmail" /></a>
<a href="https://www.linkedin.com/in/md-taki-yasir-faraji-sadik-63a026278/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" /></a>
<a href="https://github.com/TYFSADIK"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" /></a>

<h2>About Me</h2>
</div>
I'm Taki Sadik, a cybersecurity and IT professional based in North York, Toronto who likes to own his stack end to end. By day I triage security alerts and analyze threats at a SOC, and apply cyber threat intelligence to physical data center infrastructure at Microsoft. Outside of work I run a production-grade homelab on Proxmox, self-host everything from a private AI model to a public Wikipedia mirror, and document it all as hands-on labs.
I don't fully trust a system until I've tried to break it myself. The homelab below is where that happens before it happens on the job.
I got into IT through surveillance operations and discovered I cared more about the network underneath the cameras than the footage they captured. That curiosity led to networking, then Linux administration, then cloud, then security. I hold CompTIA A+ and CCNA Fundamentals and I'm currently pursuing CompTIA Security+.
Increasingly, that same instinct extends to hardware. My Canadian Defence Hardware Program is eleven sensor and robotics builds across sky, water, and ground (passive radar, hydrophone vessel monitors, seismic LoRa meshes, GPS-denied rovers, and a thermal SAR drone), each mapped to a real requirement from Canada's Defence Drone Initiative and the Army's MINERVA challenges.
I also design and deploy responsive, accessibility-first business websites for local Toronto clients, from initial brief through deployment on GitHub Pages, whether that's a glass contractor in the GTA or a pharmacy that needs WCAG-compliant accessibility.
<div align="center">
<p>
<img src="https://img.shields.io/badge/Lab_Writeups-116-9ece6a?style=for-the-badge&labelColor=1a1b26" alt="116 labs" />
<img src="https://img.shields.io/badge/K8s_Cluster-7_Nodes-7aa2f7?style=for-the-badge&labelColor=1a1b26" alt="7 node k8s" />
<img src="https://img.shields.io/badge/Defence_Builds-11-bb9af7?style=for-the-badge&labelColor=1a1b26" alt="11 defence builds" />
<img src="https://img.shields.io/badge/Self_Hosted_Services-9-e0af68?style=for-the-badge&labelColor=1a1b26" alt="9 self hosted services" />
</p>

<h2>Now</h2>
</div>
Focus
Status
Canadian Defence Hardware Program
Shipping 11 sensor and robotics builds, each with BOMs, prices, and build guides
CompTIA Security+
In progress (A+ and CCNA Fundamentals held)
Homelab
7-node K8s + 3-node Proxmox HA, 9 self-hosted services, zero public ingress
Lab write-ups
116 hands-on labs published, each with real commands and measurable outcomes
<div align="center">

<h2>Career Highlights</h2>
</div>
Cut SOC alert MTTR by 25%: mapped the end-to-end triage workflow across Splunk and AlienVault, found 3 bottlenecks, and shipped automated enrichment pipelines.
Automated 30+ daily security alerts with Python scripts and Splunk SPL correlation that eliminate false positives with minimal human intervention.
Apply cyber threat intelligence to physical infrastructure at Microsoft: auditing server racks, cabling, and Layer 1 for rogue devices, and executing firmware remediations driven by active IoCs.
Building an 11-project defence hardware program: receive-only passive radar scored against ADS-B truth, a ROS 2 GPS-denied rover with EKF drift measurements, a thermal SAR drone, and a cold-soak battery rig producing a public dataset.
Built a 7-node bare-metal Kubernetes cluster with VLAN segmentation, Calico CNI, MetalLB, Longhorn storage, and Prometheus + Grafana observability, all on consumer hardware.
Kept healthcare systems at 99%+ uptime by architecting a VLAN-segmented network and documenting data flows for compliance at CardiOCare.
Eliminated 100% of public IP exposure with a 3-node Proxmox HA cluster behind Cloudflare Tunnel, Tailscale fallback, and automated 30-day ZFS snapshot retention.
<div align="center">

<h2>Flagship Infrastructure &amp; Security Projects</h2>
</div>
<table>
<tr>
<td valign="top" width="50%">
7-Node Bare-Metal Kubernetes Cluster
Production-grade K8s across 3 desktop PCs and 4 laptops on a Proxmox/kubeadm base, with VLAN-segmented networking (Mgmt/Cluster/Storage), Calico CNI and NetworkPolicy, MetalLB for bare-metal LoadBalancers, Longhorn for 3x-replicated storage, and a Prometheus + Grafana + Loki observability stack. Hosts every other self-hosted service in production.
<br>Kubernetes Calico MetalLB Longhorn Prometheus Grafana Proxmox
</td>
<td valign="top" width="50%">
TYF-AI: Self-Hosted Local AI Security Platform
Hardened local inference stack that treats the model runtime as an untrusted workload: llama.cpp with CUDA behind an authenticated Caddy reverse proxy, per-model Firejail sandboxing (--net=none), SHA-256-pinned GGUF weights, and GPU passthrough on Proxmox. STRIDE-modeled end to end. Serves 50+ concurrent queries at sub-2s latency with zero external AI API calls.
<br>llama.cpp CUDA Caddy Firejail Proxmox GPU Passthrough
</td>
</tr>
<tr>
<td valign="top" width="50%">
Proxmox VE Zero-Trust Private Cloud
3-node Proxmox VE HA cluster on Ceph with four trust-tiered VLANs and zero public ingress. The only path in is a policy-gated Cloudflare Tunnel, with a Tailscale mesh as authenticated fallback. Automated hourly/daily/30-day ZFS snapshots via sanoid/syncoid. Eliminated 100% of public IP exposure at sub-50ms global tunnel latency.
<br>Proxmox VE Ceph Cloudflare Tunnel Tailscale ZFS
</td>
<td valign="top" width="50%">
Data Sovereignty & Secure Media Stack
Nextcloud AIO and Immich replacing Google Drive/Photos entirely, running on a zstd-compressed BTRFS pool across external SSDs with per-user ACL isolation. A 3-2-1 backup pipeline (local BTRFS snapshot → BorgBase → rsync.net) has run with zero data-loss events, at ~2.5 Gbps sustained read/write.
<br>Nextcloud Immich BTRFS BorgBase rsync.net
</td>
</tr>
<tr>
<td valign="top" width="50%">
Chakor: Self-Hosted AI Workspace · MIT, open source
A Next.js 15 / TypeScript AI workspace you run on your own hardware: local engines (llama.cpp, Ollama, LM Studio) or your own cloud keys, one-tap model switching, hardware-aware FITS/TIGHT/TOO BIG fit tagging to prevent OOM loads, in-app GGUF downloads from Hugging Face, web search, document chat, blind model A/B compare, and cross-conversation memory, all in a local SQLite store with no telemetry.
<br>Next.js 15 TypeScript SQLite llama.cpp Ollama
</td>
<td valign="top" width="50%">
Chakor: Custom 7B LLM from Scratch
A ~7B-parameter decoder-only transformer (32 layers, 32 heads, 4096 hidden dim) written and trained from random initialization in PyTorch, with attention, RoPE, RMSNorm, and the training loop all hand-built. Pretrained on a 100B+ token curated corpus via distributed multi-GPU DDP, instruction-tuned, then converted to GGUF and served 24/7 through a custom SSE-streaming llama.cpp front end.
<br>PyTorch Distributed Training GGUF llama.cpp Next.js
</td>
</tr>
<tr>
<td valign="top" width="50%">
Automated SOC Pipeline
Wazuh detections wired into TheHive case management with MISP threat-intel enrichment; custom detection rules tagged to MITRE ATT&CK technique IDs, with automated active response blocking brute-force sources.
<br>Wazuh TheHive Cortex MISP MITRE ATT&CK
</td>
<td valign="top" width="50%">
Active Directory Threat Hunting Lab
Instrumented an AD forest with Sysmon and Splunk; hunted Kerberoasting, Pass-the-Hash, and Golden Ticket attacks, with a honeypot SPN account deployed for high-fidelity early warning. Detected PtH within 2 minutes and mapped 15+ lateral-movement paths to Domain Admin.
<br>BloodHound Sysmon Splunk Kerberos Threat Hunting
</td>
</tr>
</table>
<div align="center">

<h2>From the Workbench</h2>
</div>
Deep build guides from tyfsadik.org, each with real parts lists, prices, commands, and measured results:
Build
What you get
Sky: Passive Aerial Early-Warning Node
Receive-only passive radar on KrakenSDR, scored against ADS-B ground truth
TYF-AI: Self-Hosted Local AI Security Platform
Hardened llama.cpp inference with Firejail sandboxing and GPU passthrough
7-Node Bare-Metal Kubernetes Cluster
Calico, MetalLB, Longhorn, and full observability on consumer hardware
Automated SOC Pipeline lab
Wazuh + TheHive + MISP with MITRE ATT&CK-mapped detections, step by step
Cloud Security Posture Management lab
CIS-benchmark audits of AWS and Azure with Prowler and ScoutSuite
<div align="center">

<h2>Canadian Defence Hardware Program</h2>
</div>
Eleven active sensor and robotics builds across sky, water, and ground, each mapped to a stated requirement from Canada's Defence Drone Initiative or the Army's MINERVA challenges, with full parts lists, prices, and step-by-step build guides. Program hub →
<table>
<tr>
<td valign="top" width="50%">
Sky: Passive Aerial Early-Warning Node
Receive-only passive radar on a KrakenSDR with pyAPRiL processing, scored against an ADS-B ground-truth receiver.
<br>KrakenSDR pyAPRiL RTL-SDR ADS-B MQTT
Water: Passive Acoustic Vessel Monitor
Solar hydrophone node classifying vessels by acoustic signature, validated against AIS ground truth.
<br>Hydrophone Beamforming GCC-PHAT AIS Solar
Ground: Seismic & Acoustic Perimeter Mesh
Solar ESP32 LoRa nodes (915 MHz) telling vehicles from footsteps with on-edge classification.
<br>ESP32 LoRa Mesh Edge ML Seismic
</td>
<td valign="top" width="50%">
GPS-Denied Navigation Rover + Convoy Mesh
ROS 2 EKF navigation (robot_localization, LiDAR, BNO085 IMU) with the GNSS cut, plus convoy robots that survive degraded links.
<br>ROS 2 EKF LiDAR ArduPilot Zenoh
Thermal Search-and-Rescue Drone + Drone Detector
ArduPilot/Pixhawk build with FLIR Lepton thermal and Hailo HAT+ edge AI for the MINERVA Arctic ISR gap, plus a passive acoustic counter-drone detector.
<br>ArduPilot FLIR Lepton Hailo MAVLink
Cold-Soak Battery Rig + Secure Fleet Updates
Cold-weather battery dataset (runtime, voltage sag, failure mode vs temperature) and TPM 2.0 signed OTA updates for supply-chain integrity.
<br>TPM 2.0 Secure Boot Signed OTA Ed25519
</td>
</tr>
</table>
Everything feeds a Multi-Domain Common Operating Picture: MQTT/Zenoh transport, Kalman-filter sensor fusion, and Ed25519-signed tracks on the Kubernetes cluster.
<details>
<summary><strong>Six completed software defence builds (click to expand)</strong></summary>
<br>
Build
What it does
Arctic Domain Awareness Digital Twin
Fuses ADS-B, AIS, and Sentinel-1 radar over the North; dark-vessel and route-deviation alerts
DDIL-Proof DevOps
CI/CD and telemetry that survive denied, degraded, intermittent links; store-and-forward to k3s edge nodes
Counter-Drone Sensor Fusion Simulator
Synthetic radar/RF/acoustic/camera tracks with Kalman fusion and human-in-the-loop triage (defensive simulation only)
Decision Black Box
Tamper-evident, hash-chained audit log with replay and OPA policy checks
Zero-Trust Air-Gapped Supply Chain
SBOM, sigstore signing, and reproducible builds across a simulated one-way transfer
Operation LENTUS-Style Drone Mapping
Simulated disaster-response flights with edge computer vision and a live situational-awareness map
</details>
<div align="center">
<details>
<summary><strong>Additional self-hosted services (click to expand)</strong></summary>
<br>
Service
Stack
Endpoint
Private Search
SearXNG meta-search, no tracking
search.tyfsadik.org
Cloud Storage
Nextcloud, MariaDB, Docker
cloud.tyfsadik.org
Photo Management
Immich, PostgreSQL, ML face recognition
photo.tyfsadik.org
Wiki Mirror
Kiwix, full Wikipedia mirror
wiki.tyfsadik.org
DNS
Pi-hole + Unbound, recursive resolution
Internal
Email
Postfix + Dovecot + DKIM
@tyfsadik.org
OSINT Dashboard
FastAPI + 22 security tools, SQLite storage
osint.tyfsadik.org
Remote Desktop
Arch Linux + XFCE via WSL2, no port forwarding
★ 5 GitHub stars
</details>

<h2>Professional Experience</h2>
</div>
<table>
<tr>
<td valign="top" width="50%">
Data Center Engineer · Microsoft
Sep 2025 – Present · Contract · Markham, ON
Apply cyber threat intelligence (CTI) to physical infrastructure: audit server racks, cabling, and network gear for anomalies, rogue devices, and unauthorized Layer 1 connections.
Execute urgent firmware updates and hardware remediations on bare-metal servers driven by active IoCs and threat feeds.
Incident Analyst · Felixous Technology Inc.
Nov 2025 – Present · North York, ON
Monitor security systems and databases; triage alerts and escalate events per defined SOPs.
Mapped the SOC triage workflow across Splunk and AlienVault; shipped automated enrichment pipelines that cut MTTR by 25%.
Built Python and Splunk SPL automation processing 30+ daily alerts with minimal human intervention.
Cloud Support Engineer (Intern) · Microsoft
May 2025 – Sep 2025 · Toronto, ON
Provided cloud support engineering for Azure-based enterprise customers from Dominion Centre, 222 Bay St.
Diagnosed infrastructure, networking, and identity issues across Microsoft cloud environments.
Network Analyst Intern · CardiOCare
Jan 2025 – Sep 2025 · Hybrid
Architected a VLAN-segmented network maintaining 99%+ uptime for healthcare systems; documented data flows for compliance.
Performed Wireshark packet analysis and IDS traffic monitoring to detect anomalies and support incident investigations.
</td>
<td valign="top" width="50%">
IT Help Desk Analyst · TD
Oct 2024 – Jan 2025 · Contract, Part-time
Managed the end-to-end lifecycle of IT support tickets in ServiceNow under strict enterprise SLAs.
Troubleshot Tier 1/Tier 2 software, hardware, and connectivity issues in a highly secure, regulated banking environment.
Server Operator (Junior) · Fiera Foods
Jun 2024 – Jul 2025 · Contract, Part-time
Managed server alerts on Linux and Windows Server with priority-based response; verified backups, applied patches, and built runbooks.
Built Terraform modules with GitHub Actions for self-service Azure provisioning; administered Entra ID IAM, RBAC, and Conditional Access.
Surveillance Operator / Help Desk · Elite Force / Rogers Centre
Sep 2022 – Nov 2023 · Contract, Part-time
Monitored multi-camera CCTV and IP surveillance systems, ensuring 24/7 security coverage and rapid escalation of verified threats.
Surveillance Operator · Elite Security
Jan 2022 – Apr 2023 · Contract, Part-time
Monitored CCTV systems and performed regular property inspections across commercial facilities.
Executive Editor · IKU Digital
Feb 2021 – Dec 2023 · Full-time
Directed digital publication operations: databases, administration, and digital content management.
</td>
</tr>
</table>
<div align="center">

<h2>Web Development Portfolio</h2>
</div>
Responsive, accessibility-first business websites built from client brief through deployment on GitHub Pages.
<table>
<tr>
<td valign="top" width="50%">
GTA High Glass
Multi-page site for a glass and glazing contractor in the GTA. Services showcase, filterable project gallery with CSS Grid auto-fill and aspect-ratio locking, and a quote request form. Mobile-first, WebP-optimized, with Safari-specific hero fixes.
<br>HTML5 CSS3 CSS Grid Flexbox Responsive
Hakimi Fruits
Online presence for a local fruit and produce business: seasonal highlights, product listings filterable by category (citrus, berries, tropical) via data-* attributes, and an order inquiry form. CSS Grid auto-fill for responsive product cards.
<br>HTML5 CSS3 JavaScript E-commerce
HomeBound Aisha · ★ 4 GitHub stars
Multi-page site for a home-based cleaning and domestic service provider: landing, services with pricing tiers, about/trust signals, and a validated enquiry form. BEM naming, ARIA labels, and focus management for accessible navigation.
<br>HTML5 CSS3 JavaScript Accessibility GitHub Pages
</td>
<td valign="top" width="50%">
Pharmacy Website
Accessibility-first medical/pharmacy site built to WCAG AA contrast standards (4.5:1 minimum). Live product search with aria-live announcements, schema.org structured data for SEO, full keyboard navigation, and a responsive Google Maps embed.
<br>HTML5 CSS3 JavaScript WCAG AA Healthcare
GateArch
Student portal and course-management system with full CRUD for courses, students, and enrollment tracking.
<br>PHP MySQL JavaScript
TaxGlobe
Multi-jurisdiction tax calculator handling federal and provincial brackets with real-time computation and dynamic output rendering.
<br>JavaScript HTML CSS
</td>
</tr>
</table>
<div align="center">

<h2>Complete Project Index</h2>
</div>
Every build documented on tyfsadik.org, with full write-ups, parts lists, and code.
<details>
<summary><strong>Defence projects (18) (click to expand)</strong></summary>
<br>
Project
Description
Canadian Defence Hardware Program
Program hub: all 11 hardware builds with BOMs, prices, and step-by-step guides
Sky: Passive Aerial Early-Warning Node
Receive-only KrakenSDR passive radar with pyAPRiL, scored against ADS-B ground truth
Water: Passive Acoustic Vessel Monitor
Solar hydrophone node classifying vessels by acoustic signature, validated against AIS
Ground: Seismic and Acoustic Perimeter Mesh
Solar ESP32 LoRa mesh telling vehicles from footsteps with on-edge classification
GPS-Denied Navigation Rover
ROS 2 EKF rover on wheel odometry, BNO085 IMU, and 2D LiDAR with the GNSS cut
Convoy-Following Robots on a Degraded Mesh
Rover convoy holding formation through induced LoRa and Wi-Fi link drops
Passive Acoustic Drone Detector
MEMS microphone array detecting rotor harmonics with beamforming direction finding
Thermal Search-and-Rescue Drone
ArduPilot quad with FLIR Lepton thermal and Hailo AI HAT+ for the MINERVA Arctic ISR gap
Cold-Soak Battery Characterization Rig
Drone battery runtime, voltage sag, and failure modes vs temperature as a public dataset
Secure Robot-Fleet Updates
TPM 2.0 measured boot, YubiKey-signed OTA updates, and automatic A/B rollback
Mini Airspace Deconfliction Manager
ESP32 tracker beacons plus ArduPilot SITL drones with 3D geofences and human override
Multi-Domain Common Operating Picture
Kalman-fused air, water, and ground tracks over MQTT/Zenoh with signed detections
Arctic Domain Awareness Digital Twin
ADS-B, AIS, and Sentinel-1 fusion flagging dark vessels over Canada's North
DDIL-Proof DevOps
Store-and-forward CI/CD and telemetry that survive denied and degraded links
Counter-Drone Sensor Fusion Simulator
Synthetic radar, RF, acoustic, and camera tracks with Kalman fusion and human triage
Decision Black Box
Hash-chained, Ed25519-signed audit log with replay and OPA policy checks
Zero-Trust Air-Gapped Supply Chain
SBOM, sigstore signing, and reproducible builds across a simulated one-way transfer
Operation LENTUS-Style Drone Mapping
Simulated disaster-response flights with edge computer vision and OR-Tools routing
</details>
<details>
<summary><strong>Infrastructure projects (14) (click to expand)</strong></summary>
<br>
Project
Description
Kubernetes Infrastructure
7-node bare-metal K8s with Calico, MetalLB, Longhorn, and Prometheus plus Grafana
TYF-AI: Self-Hosted Local AI Security Platform
Hardened llama.cpp inference with CUDA, authenticated Caddy proxy, and Firejail sandboxing
Proxmox VE Zero-Trust Private Cloud
3-node HA cluster on Ceph with zero public ingress via Cloudflare Tunnel
Data Sovereignty and Secure Media Stack
Nextcloud plus Immich on BTRFS with 3-2-1 backup to BorgBase and rsync.net
Chakor: Self-Hosted AI Workspace
MIT-licensed Next.js AI workspace for local models with no telemetry
Private AI Model
Self-hosted LLM with web search at ai.tyfsadik.org and no cloud subscriptions
Proxmox Homelab
Full KVM and LXC virtualization stack for servers, VMs, and network testing
Self-Hosted DNS
Pi-hole plus Unbound for network-wide ad blocking and recursive resolution
Private Email Server
Postfix plus Dovecot SMTP and IMAP on @tyfsadik.org with DKIM
Self-Hosted Cloud Storage
Private Nextcloud instance replacing Google Drive across all devices
Self-Hosted Photo Server
Immich photo management with ML face recognition and mobile auto-backup
Public Search Engine
SearXNG meta-search at search.tyfsadik.org with no tracking
Public Wiki Server
Full Kiwix Wikipedia mirror at wiki.tyfsadik.org
Arch Linux Remote Desktop via WSL2
Arch plus XFCE remote desktop over WSL2 with no router port forwarding
</details>
<details>
<summary><strong>Applications (3) (click to expand)</strong></summary>
<br>
Project
Description
GateArch
Student portal and course-management system with full CRUD and authentication
TaxGlobe
Multi-jurisdiction tax calculator with real-time federal and provincial breakdowns
Wonder Learning
E-learning platform with course listings and embedded video
</details>
<details>
<summary><strong>Games (1) (click to expand)</strong></summary>
<br>
Project
Description
Depot Gato
2D tower defense game in Godot with wave spawning, placement mechanics, and pixel art
</details>
<div align="center">

<h2>Technical Skills</h2>
</div>
<table>
<tr>
<td valign="top" align="center" width="33%">
Cloud & DevOps
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare,docker,kubernetes,nginx,ansible,terraform,prometheus,grafana,git&perline=4" alt="cloud and devops skills" />
</td>
<td valign="top" align="center" width="33%">
Systems & Security
<img src="https://skillicons.dev/icons?i=linux,ubuntu,kali,debian,bash,powershell,vim,regex&perline=4" alt="systems and security skills" />
</td>
<td valign="top" align="center" width="33%">
Languages & Data
<img src="https://skillicons.dev/icons?i=python,ts,js,php,rust,mysql,postgres,mongodb&perline=4" alt="languages and data skills" />
</td>
</tr>
</table>
<div align="center">
SOC / Security Tooling
Splunk AlienVault Wireshark Nmap Metasploit Burp Suite Wazuh TheHive Cortex MISP BloodHound Sysmon YARA nftables
Defence Hardware & Robotics
KrakenSDR RTL-SDR pyAPRiL ROS 2 ArduPilot/Pixhawk ESP32 + LoRa Hailo HAT+ FLIR Lepton MAVLink MQTT/Zenoh Kalman Fusion TPM 2.0

<h2>Certifications</h2>
<p>25+ active certifications across security, cloud, and networking. Full list at <a href="https://tyfsadik.org/resume.html">tyfsadik.org/resume.html</a>.</p>
</div>
<details>
<summary><strong>Selected certifications (click to expand)</strong></summary>
<br>
Certification
Issuer
Status
CompTIA A+
CompTIA
Active
Cybersecurity Defense Analyst
Cisco
May 2026
Azure Cloud Architecture (AZ-900)
Microsoft
Active
AWS Cloud Practitioner + Cloud Security
Amazon Web Services
Active
Foundations of Cybersecurity
Google
Feb 2026
Certified Information Professional (CIP)
OPSWAT Academy
exp. Feb 2027
Critical Infrastructure Protection (ICIP)
OPSWAT
exp. Mar 2027
Cybersecurity Virtual Experience
MasterCard (Forage)
Mar 2026
EASY Framework for Threat Intelligence
AttackIQ
Mar 2026
Introduction to Model Context Protocol
Anthropic
Mar 2026
Cisco Routing Course
APNIC Academy
exp. Mar 2029
ISC2 Candidate (CC)
ISC2
exp. Aug 2026
Diploma in Ethical Hacking
Alison
Mar 2026
Computer Networks and Network Security
IBM iX
Apr 2026
MSSQL Certification
Microsoft
Active
CCNA Fundamentals
Cisco Networking Academy
Active
CompTIA Security+
CompTIA
In Progress
</details>
<div align="center">

<h2>Education</h2>
</div>
Program
School
Dates
B.Eng, Information Technology (GPA 3.56)
University of Toronto
Jan 2023 – Dec 2026 (expected)
Postgraduate, Cyber/Electronic Operations and Warfare (GPA 3.92)
Seneca Polytechnic
Jan 2024 – Apr 2026
B.Eng, Computer Science (GPA 3.89, transferred)
BRAC University, Dhaka
Jan 2022 – Jan 2023
<div align="center">

<h2>Live Infrastructure</h2>
<p>31 DNS records managed across <code>tyfsadik.org</code>, all fronted by Cloudflare Tunnels. No service on the homelab exposes a public port directly.</p>
<p>
<img src="https://img.shields.io/badge/Requests-296K-7aa2f7?style=flat-square&labelColor=1a1b26" alt="296k requests" />
<img src="https://img.shields.io/badge/Visits-101K-9ece6a?style=flat-square&labelColor=1a1b26" alt="101k visits" />
<img src="https://img.shields.io/badge/Countries-113-e0af68?style=flat-square&labelColor=1a1b26" alt="113 countries" />
<img src="https://img.shields.io/badge/TLS_1.3-65.8%25-bb9af7?style=flat-square&labelColor=1a1b26" alt="65.8% TLS 1.3" />
</p>

<h2>GitHub Statistics</h2>
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
<!-- Contribution snake: generated by the Platane/snk GitHub Action on the
TYFSADIK/TYFSADIK repo, published to the "output" branch. -->
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TYFSADIK/TYFSADIK/output/github-contribution-grid-snake-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TYFSADIK/TYFSADIK/output/github-contribution-grid-snake.svg" />
<img alt="github contribution snake animation" src="https://raw.githubusercontent.com/TYFSADIK/TYFSADIK/output/github-contribution-grid-snake-dark.svg" />
</picture>

<h2>Daily Fuel</h2>
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="daily dev quote" />
</div>
