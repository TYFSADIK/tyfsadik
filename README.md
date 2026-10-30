<!-- markdownlint-disable-file MD033 -->
<div align="center">

<img width="1942" height="809" alt="Home_Lab" src="https://github.com/user-attachments/assets/79faa19f-81db-4697-9a06-a03246f5c348" />

<a href="https://tyfsadik.org">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=800&height=45&lines=Security+Engineering+%26+Threat+Detection;Cloud+Security+(Azure,+AWS)+%26+Infrastructure+Defense;Defence+Tech+%26+Robotics+(SDR,+ROS+2,+LoRa);7-Node+Bare-Metal+K8s+%26+Zero-Trust+Homelab;Open+Source:+Ad+Blocking+for+Mobile+Chrome" alt="specializations" />
</a>

<p>
<img src="https://komarev.com/ghpvc/?username=TYFSADIK&label=Profile%20views&color=7aa2f7&style=flat" alt="profile views" />
<img src="https://img.shields.io/badge/Based_in-Toronto,_Canada-7aa2f7?style=flat&labelColor=1a1b26" alt="location" />
<img src="https://img.shields.io/badge/Certifications-25+-e0af68?style=flat&labelColor=1a1b26" alt="25 plus certifications" />
</p>

<h3><a href="https://tyfsadik.org" target="_blank" rel="noopener">www.tyfsadik.org</a></h3>

<a href="mailto:taki@tyfsadik.org"><img src="https://skillicons.dev/icons?i=gmail" alt="Gmail" /></a>
<a href="https://www.linkedin.com/in/md-taki-yasir-faraji-sadik-63a026278/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" /></a>
<a href="https://github.com/TYFSADIK"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" /></a>

---

<h2>About Me</h2>

</div>

I'm Taki Sadik, and I build things to understand how they break: a zero-trust homelab, a bare-metal
Kubernetes cluster, sensor and robotics builds for Canadian defence challenges, a language model
trained from scratch, and open-source tools people can use every day. Everything is documented on
[tyfsadik.org](https://tyfsadik.org) with real commands, parts lists and measured results.

> *I don't fully trust a system until I've tried to break it myself.*

<div align="center">

<p>
<img src="https://img.shields.io/badge/Lab_Writeups-116-9ece6a?style=for-the-badge&labelColor=1a1b26" alt="116 labs" />
<img src="https://img.shields.io/badge/K8s_Cluster-7_Nodes-7aa2f7?style=for-the-badge&labelColor=1a1b26" alt="7 node k8s" />
<img src="https://img.shields.io/badge/Defence_Builds-11-bb9af7?style=for-the-badge&labelColor=1a1b26" alt="11 defence builds" />
<img src="https://img.shields.io/badge/Self_Hosted_Services-9-e0af68?style=for-the-badge&labelColor=1a1b26" alt="9 self hosted services" />
</p>

---

<h2>Latest Release</h2>

<a href="https://github.com/TYFSADIK/mobile-chrome-adblock">
<img src="https://raw.githubusercontent.com/TYFSADIK/mobile-chrome-adblock/main/docs/img/banner.png" alt="Mobile Chrome AdBlock" width="720" />
</a>

<h3><a href="https://github.com/TYFSADIK/mobile-chrome-adblock">Mobile Chrome AdBlock</a></h3>

</div>

Chrome on Android and iPhone can't run ad-blocking extensions, so I built a way around it that works
at the DNS level, blocking about 400,000 ad, tracker and malware domains in Chrome and every other app.

| Part | What it does | Stack |
| --- | --- | --- |
| Android app | On-device filter through a DNS-only local VPN, with blocking levels, allowlist, Quick Settings tile and CNAME-cloak detection | Kotlin, VpnService |
| iOS app | The same filter as a packet tunnel, with Siri and Shortcuts on/off | Swift, SwiftUI, NetworkExtension |
| Termux command | `adblock on/off/status` controls the app; root mode runs the whole blocker inside Termux with iptables | Bash, iptables |
| Self-hosted server | Encrypted DNS (DoH and DoT) with automatic Let's Encrypt certificates and a one-line installer | Go, Docker |

<div align="center">

[Get it](https://tyfsadik.github.io/mobile-chrome-adblock/) · [Source](https://github.com/TYFSADIK/mobile-chrome-adblock)

---

<h2>Now Building</h2>

</div>

| Focus | Status |
| --- | --- |
| Canadian Defence Hardware Program | Shipping 11 sensor and robotics builds, each with BOMs, prices and build guides |
| Mobile Chrome AdBlock | Android, iOS, Termux and server releases; open source under MIT |
| Homelab | 7-node K8s and 3-node Proxmox HA, 9 self-hosted services, zero public ingress |
| Lab write-ups | 116 hands-on labs published, each with real commands and measurable outcomes |
| CompTIA Security+ | In progress |

<div align="center">

---

<h2>Highlights</h2>

</div>

| Highlight |
| --- |
| Built ad blocking for mobile Chrome across Android, iOS, Termux and a self-hosted server, blocking about 400,000 domains on-device |
| Running an 11-project defence hardware program: passive radar scored against ADS-B truth, GPS-denied rover EKF, thermal SAR drone, cold-soak battery dataset |
| Built a 7-node bare-metal Kubernetes cluster (Calico, MetalLB, Longhorn, Prometheus/Grafana) on consumer hardware |
| Eliminated all public IP exposure with a 3-node Proxmox HA cluster behind Cloudflare Tunnel with Tailscale fallback |
| Hand-built a ~7B decoder-only transformer in PyTorch, pretrained on 100B+ tokens and served 24/7 as GGUF |
| Served 296K requests to visitors from 113 countries from a homelab that exposes no public ports |

<div align="center">

---

<h2>Flagship Infrastructure &amp; Security Projects</h2>

</div>

| Project | What it is | Stack |
| --- | --- | --- |
| 7-Node Bare-Metal Kubernetes Cluster | Production K8s on 3 desktops and 4 laptops: VLAN-segmented networking, Calico and NetworkPolicy, MetalLB LoadBalancers, 3x-replicated Longhorn storage, Prometheus/Grafana/Loki observability | Kubernetes, Calico, MetalLB, Longhorn, Prometheus, Grafana, Proxmox |
| TYF-AI: Self-Hosted Local AI Security Platform | Hardened local inference: llama.cpp and CUDA behind authenticated Caddy, per-model Firejail sandboxing, SHA-256-pinned GGUF weights, GPU passthrough; 50+ concurrent queries at sub-2s latency | llama.cpp, CUDA, Caddy, Firejail, Proxmox |
| Proxmox VE Zero-Trust Private Cloud | 3-node HA cluster on Ceph, four trust-tiered VLANs, zero public ingress via Cloudflare Tunnel with Tailscale fallback, automated ZFS snapshots | Proxmox VE, Ceph, Cloudflare Tunnel, Tailscale, ZFS |
| Data Sovereignty & Secure Media Stack | Nextcloud AIO and Immich replacing Drive/Photos on zstd BTRFS with per-user ACLs; 3-2-1 backup (BTRFS to BorgBase to rsync.net), zero data-loss events | Nextcloud, Immich, BTRFS, BorgBase, rsync.net |
| Chakor: Self-Hosted AI Workspace (MIT) | Next.js 15 workspace for local engines or your own cloud keys: model fit tagging, in-app GGUF downloads, web search, doc chat, blind A/B compare, local SQLite, no telemetry | Next.js 15, TypeScript, SQLite, llama.cpp, Ollama |
| Chakor: Custom 7B LLM from Scratch | ~7B decoder-only transformer hand-built in PyTorch (RoPE, RMSNorm), pretrained on 100B+ tokens via DDP, instruction-tuned, served as GGUF 24/7 | PyTorch, DDP, GGUF, llama.cpp, Next.js |
| Automated SOC Pipeline | Wazuh detections into TheHive with MISP enrichment, MITRE ATT&CK-tagged rules, automated active response | Wazuh, TheHive, Cortex, MISP |
| Active Directory Threat Hunting Lab | AD forest instrumented with Sysmon and Splunk; hunted Kerberoasting, PtH and Golden Ticket; honeypot SPN; PtH detected in 2 minutes | BloodHound, Sysmon, Splunk, Kerberos |

<div align="center">

---

<h2>From the Workbench</h2>

</div>

Deep build guides from [tyfsadik.org](https://tyfsadik.org), each with real parts lists, prices, commands and measured results:

| Build | What you get |
| --- | --- |
| [Sky: Passive Aerial Early-Warning Node](https://tyfsadik.org/work/defence/sky-passive-radar-node.html) | Receive-only passive radar on KrakenSDR, scored against ADS-B ground truth |
| [TYF-AI: Self-Hosted Local AI Security Platform](https://tyfsadik.org/work/infrastructure/tyf-ai-platform.html) | Hardened llama.cpp inference with Firejail sandboxing and GPU passthrough |
| [7-Node Bare-Metal Kubernetes Cluster](https://tyfsadik.org/work/infrastructure/kubernetes-infrastructure.html) | Calico, MetalLB, Longhorn and full observability on consumer hardware |
| [Automated SOC Pipeline lab](https://tyfsadik.org/blog/labs/security/automated-soc-pipeline.html) | Wazuh, TheHive and MISP with MITRE ATT&CK-mapped detections, step by step |
| [Cloud Security Posture Management lab](https://tyfsadik.org/blog/labs/cloud-azure/cspm-azure-aws.html) | CIS-benchmark audits of AWS and Azure with Prowler and ScoutSuite |

<div align="center">

---

<h2>Canadian Defence Hardware Program</h2>

</div>

Eleven active sensor and robotics builds across sky, water and ground, each mapped to a stated requirement from Canada's Defence Drone Initiative or the Army's MINERVA challenges, with full parts lists, prices and step-by-step build guides. See the [program hub](https://tyfsadik.org/work/defence/defence-hardware-program.html).

| Build | Description | Stack |
| --- | --- | --- |
| Sky: Passive Aerial Early-Warning Node | Receive-only passive radar on KrakenSDR with pyAPRiL, scored against ADS-B ground truth | KrakenSDR, pyAPRiL, RTL-SDR, ADS-B, MQTT |
| Water: Passive Acoustic Vessel Monitor | Solar hydrophone node classifying vessels by acoustic signature, validated against AIS | Hydrophone, Beamforming, GCC-PHAT, AIS, Solar |
| Ground: Seismic & Acoustic Perimeter Mesh | Solar ESP32 LoRa nodes (915 MHz) telling vehicles from footsteps at the edge | ESP32, LoRa Mesh, Edge ML, Seismic |
| GPS-Denied Navigation Rover + Convoy Mesh | ROS 2 EKF navigation (LiDAR, BNO085 IMU) with GNSS cut, plus convoy robots on degraded links | ROS 2, EKF, LiDAR, ArduPilot, Zenoh |
| Thermal SAR Drone + Drone Detector | ArduPilot/Pixhawk FLIR Lepton and Hailo HAT+ edge AI for the MINERVA Arctic ISR gap, plus a passive acoustic counter-drone detector | ArduPilot, FLIR Lepton, Hailo, MAVLink |
| Cold-Soak Battery Rig + Secure Fleet Updates | Cold-weather battery dataset (runtime, sag, failure vs temperature) and TPM 2.0 signed OTA with A/B rollback | TPM 2.0, Secure Boot, Signed OTA, Ed25519 |
| Fusion layer | Multi-Domain Common Operating Picture: MQTT/Zenoh transport, Kalman-filter sensor fusion, Ed25519-signed tracks on Kubernetes | MQTT, Zenoh, Kalman, Ed25519 |

<details>
<summary><strong>Six completed software defence builds</strong></summary>
<br>

| Build | What it does |
| --- | --- |
| Arctic Domain Awareness Digital Twin | Fuses ADS-B, AIS and Sentinel-1 radar over the North; dark-vessel and route-deviation alerts |
| DDIL-Proof DevOps | CI/CD and telemetry that survive denied, degraded, intermittent links; store-and-forward to k3s edge nodes |
| Counter-Drone Sensor Fusion Simulator | Synthetic radar/RF/acoustic/camera tracks with Kalman fusion and human-in-the-loop triage (defensive simulation only) |
| Decision Black Box | Tamper-evident, hash-chained audit log with replay and OPA policy checks |
| Zero-Trust Air-Gapped Supply Chain | SBOM, sigstore signing and reproducible builds across a simulated one-way transfer |
| Operation LENTUS-Style Drone Mapping | Simulated disaster-response flights with edge computer vision and a live situational-awareness map |

</details>

<details>
<summary><strong>Self-hosted services</strong></summary>
<br>

| Service | Stack | Endpoint |
| --- | --- | --- |
| Private Search | SearXNG meta-search, no tracking | `search.tyfsadik.org` |
| Cloud Storage | Nextcloud, MariaDB, Docker | `cloud.tyfsadik.org` |
| Photo Management | Immich, PostgreSQL, ML face recognition | `photo.tyfsadik.org` |
| Wiki Mirror | Kiwix, full Wikipedia mirror | `wiki.tyfsadik.org` |
| DNS | Pi-hole and Unbound, recursive resolution | Internal |
| Email | Postfix, Dovecot and DKIM | `@tyfsadik.org` |
| OSINT Dashboard | FastAPI with 22 security tools, SQLite storage | `osint.tyfsadik.org` |
| Remote Desktop | Arch Linux and XFCE via WSL2, no port forwarding | 5 GitHub stars |

</details>

<div align="center">

---

<h2>Web Development Portfolio</h2>

</div>

Responsive, accessibility-first business websites built from client brief through deployment on GitHub Pages.

| Project | Description | Stack |
| --- | --- | --- |
| GTA High Glass | Glass and glazing contractor site: filterable project gallery (CSS Grid auto-fill), quote form, mobile-first, WebP, Safari hero fixes | HTML5, CSS3, CSS Grid, Flexbox |
| Hakimi Fruits | Produce business site: seasonal highlights, category-filterable listings, order inquiry form | HTML5, CSS3, JavaScript |
| HomeBound Aisha (4 GitHub stars) | Cleaning service site: landing, pricing tiers, trust signals, validated enquiry form; BEM, ARIA, focus management | HTML5, CSS3, JavaScript, Accessibility |
| Pharmacy Website | WCAG AA pharmacy site: live search with aria-live, schema.org SEO, keyboard navigation, responsive Maps embed | HTML5, CSS3, JavaScript, WCAG AA |

<div align="center">

---

<h2>Complete Project Index</h2>

</div>

Every build documented on [tyfsadik.org](https://tyfsadik.org), with full write-ups, parts lists and code.

<details>
<summary><strong>Defence projects (18)</strong></summary>
<br>

| Project | Description |
| --- | --- |
| [Canadian Defence Hardware Program](https://tyfsadik.org/work/defence/defence-hardware-program.html) | Program hub: all 11 hardware builds with BOMs, prices and step-by-step guides |
| [Sky: Passive Aerial Early-Warning Node](https://tyfsadik.org/work/defence/sky-passive-radar-node.html) | Receive-only KrakenSDR passive radar with pyAPRiL, scored against ADS-B ground truth |
| [Water: Passive Acoustic Vessel Monitor](https://tyfsadik.org/work/defence/water-passive-acoustic-vessel-monitor.html) | Solar hydrophone node classifying vessels by acoustic signature, validated against AIS |
| [Ground: Seismic and Acoustic Perimeter Mesh](https://tyfsadik.org/work/defence/ground-seismic-perimeter-mesh.html) | Solar ESP32 LoRa mesh telling vehicles from footsteps with on-edge classification |
| [GPS-Denied Navigation Rover](https://tyfsadik.org/work/defence/gps-denied-navigation-rover.html) | ROS 2 EKF rover on wheel odometry, BNO085 IMU and 2D LiDAR with the GNSS cut |
| [Convoy-Following Robots on a Degraded Mesh](https://tyfsadik.org/work/defence/convoy-robots-degraded-mesh.html) | Rover convoy holding formation through induced LoRa and Wi-Fi link drops |
| [Passive Acoustic Drone Detector](https://tyfsadik.org/work/defence/acoustic-drone-detector.html) | MEMS microphone array detecting rotor harmonics with beamforming direction finding |
| [Thermal Search-and-Rescue Drone](https://tyfsadik.org/work/defence/thermal-sar-drone.html) | ArduPilot quad with FLIR Lepton thermal and Hailo AI HAT+ for the MINERVA Arctic ISR gap |
| [Cold-Soak Battery Characterization Rig](https://tyfsadik.org/work/defence/cold-soak-battery-rig.html) | Drone battery runtime, voltage sag and failure modes vs temperature as a public dataset |
| [Secure Robot-Fleet Updates](https://tyfsadik.org/work/defence/secure-fleet-updates.html) | TPM 2.0 measured boot, YubiKey-signed OTA updates and automatic A/B rollback |
| [Mini Airspace Deconfliction Manager](https://tyfsadik.org/work/defence/airspace-deconfliction-manager.html) | ESP32 tracker beacons plus ArduPilot SITL drones with 3D geofences and human override |
| [Multi-Domain Common Operating Picture](https://tyfsadik.org/work/defence/multi-domain-common-operating-picture.html) | Kalman-fused air, water and ground tracks over MQTT/Zenoh with signed detections |
| [Arctic Domain Awareness Digital Twin](https://tyfsadik.org/work/defence/arctic-domain-awareness.html) | ADS-B, AIS and Sentinel-1 fusion flagging dark vessels over Canada's North |
| [DDIL-Proof DevOps](https://tyfsadik.org/work/defence/ddil-proof-devops.html) | Store-and-forward CI/CD and telemetry that survive denied and degraded links |
| [Counter-Drone Sensor Fusion Simulator](https://tyfsadik.org/work/defence/counter-drone-sensor-fusion.html) | Synthetic radar, RF, acoustic and camera tracks with Kalman fusion and human triage |
| [Decision Black Box](https://tyfsadik.org/work/defence/decision-black-box.html) | Hash-chained, Ed25519-signed audit log with replay and OPA policy checks |
| [Zero-Trust Air-Gapped Supply Chain](https://tyfsadik.org/work/defence/zero-trust-air-gapped-supply-chain.html) | SBOM, sigstore signing and reproducible builds across a simulated one-way transfer |
| [Operation LENTUS-Style Drone Mapping](https://tyfsadik.org/work/defence/lentus-drone-mapping.html) | Simulated disaster-response flights with edge computer vision and OR-Tools routing |

</details>

<details>
<summary><strong>Infrastructure projects (14)</strong></summary>
<br>

| Project | Description |
| --- | --- |
| [Kubernetes Infrastructure](https://tyfsadik.org/work/infrastructure/kubernetes-infrastructure.html) | 7-node bare-metal K8s with Calico, MetalLB, Longhorn, and Prometheus and Grafana |
| [TYF-AI: Self-Hosted Local AI Security Platform](https://tyfsadik.org/work/infrastructure/tyf-ai-platform.html) | Hardened llama.cpp inference with CUDA, authenticated Caddy proxy and Firejail sandboxing |
| [Proxmox VE Zero-Trust Private Cloud](https://tyfsadik.org/work/infrastructure/proxmox-zero-trust.html) | 3-node HA cluster on Ceph with zero public ingress via Cloudflare Tunnel |
| [Data Sovereignty and Secure Media Stack](https://tyfsadik.org/work/infrastructure/data-sovereignty-stack.html) | Nextcloud and Immich on BTRFS with 3-2-1 backup to BorgBase and rsync.net |
| [Chakor: Self-Hosted AI Workspace](https://tyfsadik.org/work/infrastructure/chakor.html) | MIT-licensed Next.js AI workspace for local models with no telemetry |
| [Private AI Model](https://tyfsadik.org/work/infrastructure/private-ai-model.html) | Self-hosted LLM with web search at ai.tyfsadik.org and no cloud subscriptions |
| [Proxmox Homelab](https://tyfsadik.org/work/infrastructure/proxmox-homelab.html) | Full KVM and LXC virtualization stack for servers, VMs and network testing |
| [Self-Hosted DNS](https://tyfsadik.org/work/infrastructure/self-hosted-dns.html) | Pi-hole and Unbound for network-wide ad blocking and recursive resolution |
| [Private Email Server](https://tyfsadik.org/work/infrastructure/email-server.html) | Postfix and Dovecot SMTP and IMAP on @tyfsadik.org with DKIM |
| [Self-Hosted Cloud Storage](https://tyfsadik.org/work/infrastructure/nextcloud-storage.html) | Private Nextcloud instance replacing Google Drive across all devices |
| [Self-Hosted Photo Server](https://tyfsadik.org/work/infrastructure/photo-server.html) | Immich photo management with ML face recognition and mobile auto-backup |
| [Public Search Engine](https://tyfsadik.org/work/infrastructure/search-engine.html) | SearXNG meta-search at search.tyfsadik.org with no tracking |
| [Public Wiki Server](https://tyfsadik.org/work/infrastructure/wiki-server.html) | Full Kiwix Wikipedia mirror at wiki.tyfsadik.org |
| [Arch Linux Remote Desktop via WSL2](https://tyfsadik.org/work/infrastructure/arch-linux-remote-desktop.html) | Arch and XFCE remote desktop over WSL2 with no router port forwarding |

</details>

<details>
<summary><strong>Applications and tools (4)</strong></summary>
<br>

| Project | Description |
| --- | --- |
| [Mobile Chrome AdBlock](https://github.com/TYFSADIK/mobile-chrome-adblock) | Ad blocking for Chrome on Android and iPhone: Android and iOS apps, Termux command and self-hosted DNS server |
| [GateArch](https://tyfsadik.org/work/applications/gatearch.html) | Student portal and course-management system with full CRUD and authentication |
| [TaxGlobe](https://tyfsadik.org/work/applications/taxglobe.html) | Multi-jurisdiction tax calculator with real-time federal and provincial breakdowns |
| [Wonder Learning](https://tyfsadik.org/work/applications/wonder-learning.html) | E-learning platform with course listings and embedded video |

</details>

<details>
<summary><strong>Games (1)</strong></summary>
<br>

| Project | Description |
| --- | --- |
| [Depot Gato](https://tyfsadik.org/work/games/depot-gato.html) | 2D tower defense game in Godot with wave spawning, placement mechanics and pixel art |

</details>

<div align="center">

---

<h2>Technical Skills</h2>

</div>

<table>
<tr>
<td valign="top" align="center" width="33%">

### Cloud & DevOps

<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare,docker,kubernetes,nginx,ansible,terraform,prometheus,grafana,git&perline=4" alt="cloud and devops skills" />

</td>
<td valign="top" align="center" width="33%">

### Systems & Security

<img src="https://skillicons.dev/icons?i=linux,ubuntu,kali,debian,bash,powershell,vim,regex&perline=4" alt="systems and security skills" />

</td>
<td valign="top" align="center" width="33%">

### Languages & Data

<img src="https://skillicons.dev/icons?i=python,go,kotlin,swift,ts,js,php,rust,mysql,postgres,mongodb&perline=4" alt="languages and data skills" />

</td>
</tr>
</table>

<div align="center">

| Area | Tools |
| --- | --- |
| Security | Splunk, Wireshark, Nmap, Metasploit, Burp Suite, Wazuh, TheHive, Cortex, MISP, BloodHound, Sysmon, YARA, nftables |
| Mobile and networking | Android VpnService, iOS NetworkExtension, DNS-over-HTTPS/TLS, iptables, Cloudflare Tunnel, Tailscale |
| Defence hardware and robotics | KrakenSDR, RTL-SDR, pyAPRiL, ROS 2, ArduPilot/Pixhawk, ESP32 and LoRa, Hailo HAT+, FLIR Lepton, MAVLink, MQTT/Zenoh, Kalman fusion, TPM 2.0 |

---

<h2>Certifications</h2>

<p>25+ certifications across security, cloud and networking. Full list at <a href="https://tyfsadik.org/resume.html">tyfsadik.org/resume.html</a>.</p>

</div>

<details>
<summary><strong>Selected certifications</strong></summary>
<br>

| Certification | Issuer | Status |
| --- | --- | --- |
| CompTIA A+ | CompTIA | Active |
| Cybersecurity Defense Analyst | Cisco | May 2026 |
| Azure Cloud Architecture (AZ-900) | Microsoft | Active |
| AWS Cloud Practitioner + Cloud Security | Amazon Web Services | Active |
| Foundations of Cybersecurity | Google | Feb 2026 |
| Certified Information Professional (CIP) | OPSWAT Academy | exp. Feb 2027 |
| Critical Infrastructure Protection (ICIP) | OPSWAT | exp. Mar 2027 |
| Cybersecurity Virtual Experience | MasterCard (Forage) | Mar 2026 |
| EASY Framework for Threat Intelligence | AttackIQ | Mar 2026 |
| Introduction to Model Context Protocol | Anthropic | Mar 2026 |
| Cisco Routing Course | APNIC Academy | exp. Mar 2029 |
| ISC2 Candidate (CC) | ISC2 | exp. Aug 2026 |
| Diploma in Ethical Hacking | Alison | Mar 2026 |
| Computer Networks and Network Security | IBM iX | Apr 2026 |
| MSSQL Certification | Microsoft | Active |
| CCNA Fundamentals | Cisco Networking Academy | Active |
| CompTIA Security+ | CompTIA | In Progress |

</details>

<div align="center">

---

<h2>Live Infrastructure</h2>

<p>31 DNS records managed across <code>tyfsadik.org</code>, all fronted by Cloudflare Tunnels. No service on the homelab exposes a public port directly.</p>

<p>
<img src="https://img.shields.io/badge/Requests-296K-7aa2f7?style=flat-square&labelColor=1a1b26" alt="296k requests" />
<img src="https://img.shields.io/badge/Visits-101K-9ece6a?style=flat-square&labelColor=1a1b26" alt="101k visits" />
<img src="https://img.shields.io/badge/Countries-113-e0af68?style=flat-square&labelColor=1a1b26" alt="113 countries" />
<img src="https://img.shields.io/badge/TLS_1.3-65.8%25-bb9af7?style=flat-square&labelColor=1a1b26" alt="65.8% TLS 1.3" />
</p>

---

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

---

<h2>Daily Fuel</h2>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="daily dev quote" />

</div>
