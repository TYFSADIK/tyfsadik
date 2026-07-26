<!-- markdownlint-disable-file MD033 -->
<div align="center">
<img width="1942" height="809" alt="Home_Lab" src="https://github.com/user-attachments/assets/6612a807-aafc-4007-8dd2-1385fafa17c6" />


<a href="https://tyfsadik.org">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=800&height=45&lines=Security+Operations+Center+(SOC)+%26+Incident+Response;Cloud+Security+(Azure,+AWS)+%26+Infrastructure+Defense;25-Project+Homelab+%26+7-Node+Bare-Metal+K8s+Cluster;Full-Stack+Web+Developer+%7C+Open+Source+Contributor" alt="specializations" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=TYFSADIK&label=Profile%20views&color=7aa2f7&style=flat" alt="profile views" />
  <img src="https://img.shields.io/badge/Open_to-SOC_%2F_Cloud_Security_Roles-9ece6a?style=flat&labelColor=1a1b26" alt="open to work" />
  <img src="https://img.shields.io/badge/Based_in-Toronto,_CA-7aa2f7?style=flat&labelColor=1a1b26" alt="location" />
  <img src="https://img.shields.io/badge/Homelab_Projects-25-e0af68?style=flat&labelColor=1a1b26" alt="25 projects" />
</p>

<img src="https://github-profile-trophy-fork-two.vercel.app/?username=TYFSADIK&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7&title=Commits,Repositories,Stars,Followers,PullRequest,MultiLanguage,Experience" alt="trophies" />

<h3><a href="https://tyfsadik.org" target="_blank" rel="noopener">www.tyfsadik.org</a></h3>

[![Gmail](https://skillicons.dev/icons?i=gmail)](mailto:taki@tyfsadik.org)
[![LinkedIn](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/md-taki-yasir-faraji-sadik-63a026278/)
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/TYFSADIK)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>About Me</h2>

</div>

I'm a cybersecurity analyst focused on the detection, triage, and response side of the SOC — reading alerts, tracing root cause, and closing the loop before a small anomaly becomes an incident. I split my time between hardening Azure and AWS infrastructure professionally and running a production-grade homelab that hosts everything from a self-trained LLM to a zero-public-ingress private cloud, built, broken, and rebuilt by hand.

> *I don't fully trust a system until I've tried to break it myself — the homelab below is where that happens before it happens on the job.*

I also design and deploy responsive business websites for local Toronto clients, from initial brief through deployment on GitHub Pages — whether that's a glass contractor in the GTA or a pharmacy that needs WCAG-compliant accessibility.

<div align="center">

<p>
  <img src="https://img.shields.io/badge/Lab_Writeups-116-9ece6a?style=for-the-badge&labelColor=1a1b26" alt="116 labs" />
  <img src="https://img.shields.io/badge/K8s_Cluster-7_Nodes-7aa2f7?style=for-the-badge&labelColor=1a1b26" alt="7 node k8s" />
  <img src="https://img.shields.io/badge/DNS_Records-31-bb9af7?style=for-the-badge&labelColor=1a1b26" alt="31 dns records" />
  <img src="https://img.shields.io/badge/Web_Projects-8%2B-e0af68?style=for-the-badge&labelColor=1a1b26" alt="8 web projects" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>Flagship Infrastructure &amp; Security Projects</h2>

</div>

<table>
<tr>
<td valign="top" width="50%">

**7-Node Bare-Metal Kubernetes Cluster**
Production-grade K8s across 3 desktop PCs and 4 laptops on a Proxmox/kubeadm base, with VLAN-segmented networking (Mgmt/Cluster/Storage), Calico CNI and NetworkPolicy, MetalLB for bare-metal LoadBalancers, Longhorn for 3x-replicated storage, and a Prometheus + Grafana + Loki observability stack. Hosts every other self-hosted service in production.
<br>`Kubernetes` `Calico` `MetalLB` `Longhorn` `Prometheus` `Grafana` `Proxmox`

</td>
<td valign="top" width="50%">

**TYF-AI — Self-Hosted Local AI Security Platform**
Hardened local inference stack that treats the model runtime as an untrusted workload: llama.cpp with CUDA behind an authenticated Caddy reverse proxy, per-model Firejail sandboxing (`--net=none`), SHA-256-pinned GGUF weights, and GPU passthrough on Proxmox. STRIDE-modeled end to end. Serves 50+ concurrent queries at sub-2s latency with zero external AI API calls.
<br>`llama.cpp` `CUDA` `Caddy` `Firejail` `Proxmox` `GPU Passthrough`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**Proxmox VE Zero-Trust Private Cloud**
3-node Proxmox VE HA cluster on Ceph with four trust-tiered VLANs and zero public ingress — the only path in is a policy-gated Cloudflare Tunnel, with a Tailscale mesh as authenticated fallback. Automated hourly/daily/30-day ZFS snapshots via sanoid/syncoid. Eliminated 100% of public IP exposure at sub-50ms global tunnel latency.
<br>`Proxmox VE` `Ceph` `Cloudflare Tunnel` `Tailscale` `ZFS`

</td>
<td valign="top" width="50%">

**Data Sovereignty & Secure Media Stack**
Nextcloud AIO and Immich replacing Google Drive/Photos entirely, running on a zstd-compressed BTRFS pool across external SSDs with per-user ACL isolation. A 3-2-1 backup pipeline (local BTRFS snapshot → BorgBase → rsync.net) has run with zero data-loss events, at ~2.5 Gbps sustained read/write.
<br>`Nextcloud` `Immich` `BTRFS` `BorgBase` `rsync.net`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**Chakor — Self-Hosted AI Workspace** · MIT, open source
A Next.js 15 / TypeScript AI workspace you run on your own hardware: local engines (llama.cpp, Ollama, LM Studio) or your own cloud keys, one-tap model switching, hardware-aware `FITS`/`TIGHT`/`TOO BIG` fit tagging to prevent OOM loads, in-app GGUF downloads from Hugging Face, web search, document chat, blind model A/B compare, and cross-conversation memory — all in a local SQLite store, no telemetry.
<br>`Next.js 15` `TypeScript` `SQLite` `llama.cpp` `Ollama`

</td>
<td valign="top" width="50%">

**Chakor — Custom 7B LLM from Scratch**
A ~7B-parameter decoder-only transformer (32 layers, 32 heads, 4096 hidden dim) written and trained from random initialization in PyTorch — attention, RoPE, RMSNorm, and the training loop all hand-built. Pretrained on a 100B+ token curated corpus via distributed multi-GPU DDP, instruction-tuned, then converted to GGUF and served 24/7 through a custom SSE-streaming llama.cpp front end.
<br>`PyTorch` `Distributed Training` `GGUF` `llama.cpp` `Next.js`

</td>
</tr>
<tr>
<td valign="top" width="50%">

**Automated SOC Pipeline**
Wazuh detections wired into TheHive case management with MISP threat-intel enrichment; custom detection rules tagged to MITRE ATT&CK technique IDs, with automated active response blocking brute-force sources.
<br>`Wazuh` `TheHive` `Cortex` `MISP` `MITRE ATT&CK`

</td>
<td valign="top" width="50%">

**Active Directory Threat Hunting Lab**
Instrumented an AD forest with Sysmon and Splunk; hunted Kerberoasting, Pass-the-Hash, and Golden Ticket attacks, with a honeypot SPN account deployed for high-fidelity early warning. Detected PtH within 2 minutes and mapped 15+ lateral-movement paths to Domain Admin.
<br>`BloodHound` `Sysmon` `Splunk` `Kerberos` `Threat Hunting`

</td>
</tr>
</table>

<div align="center">

<details>
<summary><strong>Additional self-hosted services (click to expand)</strong></summary>
<br>

| Service | Stack | Endpoint |
|---|---|---|
| Private Search | SearXNG meta-search, no tracking | `search.tyfsadik.org` |
| Cloud Storage | Nextcloud, MariaDB, Docker | `cloud.tyfsadik.org` |
| Photo Management | Immich, PostgreSQL, ML face recognition | `photo.tyfsadik.org` |
| Wiki Mirror | Kiwix, full Wikipedia mirror | `wiki.tyfsadik.org` |
| DNS | Pi-hole + Unbound, recursive resolution | Internal |
| Email | Postfix + Dovecot + DKIM | `@tyfsadik.org` |
| OSINT Dashboard | FastAPI + 22 security tools, SQLite storage | `osint.tyfsadik.org` |
| Remote Desktop | Arch Linux + XFCE via WSL2, no port forwarding | ★ 5 GitHub stars |

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>Professional Experience</h2>

</div>

<table>
<tr>
<td valign="top" width="50%">

**Incident Manager** · CN Tower / Tour CN
`Aug 2025 – Present · Toronto, ON`
- Lead end-to-end incident lifecycle at critical national infrastructure: detection, triage, prioritization, escalation, resolution, and post-incident review.
- Coordinate cross-functional response teams during security and operational events.

**Incident Analyst** · Shield Security Systems
`Nov 2025 – Present · North York, ON`
- Monitor security systems and databases; triage alerts and escalate events per defined SOPs.
- Perform ongoing threat assessments and vulnerability analysis using industry tools.

**Cloud Support Engineer (Intern)** · Microsoft
`May 2025 – Sep 2025 · Toronto, ON`
- Provided cloud support engineering for Azure-based enterprise customers.
- Diagnosed and resolved infrastructure, networking, and identity issues in Microsoft cloud environments.

</td>
<td valign="top" width="50%">

**Network Analyst Intern** · CardiOCare
`Jan 2025 – Sep 2025 · Hybrid`
- Monitored and maintained network infrastructure; identified and resolved connectivity and performance issues.
- Performed packet analysis and traffic monitoring using IDS to detect anomalies.

**Server Operator (Junior)** · Fiera Foods
`Jun 2024 – Jul 2025 · Contract, Part-time`
- Managed server alerts on Linux and Windows Server with priority-based response.
- Performed daily maintenance: backup verification, system updates, patch application, performance monitoring.

**Surveillance Operator / Help Desk** · Elite Force / Rogers Centre
`Sep 2022 – Nov 2023 · Contract, Part-time`
- Monitored multi-camera CCTV and IP surveillance systems, ensuring 24/7 security coverage.
- Detected and reported suspicious activity, coordinating with on-ground teams for rapid response.

</td>
</tr>
</table>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>Web Development Portfolio</h2>

</div>

Responsive, accessibility-first business websites built from client brief through deployment on GitHub Pages.

<table>
<tr>
<td valign="top" width="50%">

**GTA High Glass**
Multi-page site for a glass and glazing contractor in the GTA. Services showcase, filterable project gallery with CSS Grid auto-fill and aspect-ratio locking, and a quote request form. Mobile-first, WebP-optimized, with Safari-specific hero fixes.
<br>`HTML5` `CSS3` `CSS Grid` `Flexbox` `Responsive`

**Hakimi Fruits**
Online presence for a local fruit and produce business — seasonal highlights, product listings filterable by category (citrus, berries, tropical) via `data-*` attributes, and an order inquiry form. CSS Grid auto-fill for responsive product cards.
<br>`HTML5` `CSS3` `JavaScript` `E-commerce`

**HomeBound Aisha** · ★ 4 GitHub stars
Multi-page site for a home-based cleaning and domestic service provider — landing, services with pricing tiers, about/trust signals, and a validated enquiry form. BEM naming, ARIA labels, and focus management for accessible navigation.
<br>`HTML5` `CSS3` `JavaScript` `Accessibility` `GitHub Pages`

</td>
<td valign="top" width="50%">

**Pharmacy Website**
Accessibility-first medical/pharmacy site built to WCAG AA contrast standards (4.5:1 minimum). Live product search with `aria-live` announcements, schema.org structured data for SEO, full keyboard navigation, and a responsive Google Maps embed.
<br>`HTML5` `CSS3` `JavaScript` `WCAG AA` `Healthcare`

**GateArch**
Student portal and course-management system with full CRUD for courses, students, and enrollment tracking.
<br>`PHP` `MySQL` `JavaScript`

**TaxGlobe**
Multi-jurisdiction tax calculator handling federal and provincial brackets with real-time computation and dynamic output rendering.
<br>`JavaScript` `HTML` `CSS`

</td>
</tr>
</table>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

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
<img src="https://skillicons.dev/icons?i=python,ts,js,php,rust,mysql,postgres,mongodb&perline=4" alt="languages and data skills" />

</td>
</tr>
</table>

<div align="center">

**SOC / Security Tooling**
`Splunk` `Wireshark` `Nmap` `Metasploit` `Burp Suite` `Wazuh` `TheHive` `Cortex` `MISP` `BloodHound` `Sysmon` `YARA` `nftables`

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>Live Infrastructure</h2>

<p>31 DNS records managed across <code>tyfsadik.org</code>, all fronted by Cloudflare Tunnels — no service on the homelab exposes a public port directly.</p>

<p>
  <img src="https://img.shields.io/badge/Requests-296K-7aa2f7?style=flat-square&labelColor=1a1b26" alt="296k requests" />
  <img src="https://img.shields.io/badge/Visits-101K-9ece6a?style=flat-square&labelColor=1a1b26" alt="101k visits" />
  <img src="https://img.shields.io/badge/Countries-113-e0af68?style=flat-square&labelColor=1a1b26" alt="113 countries" />
  <img src="https://img.shields.io/badge/TLS_1.3-65.8%25-bb9af7?style=flat-square&labelColor=1a1b26" alt="65.8% TLS 1.3" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

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

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=3" alt="divider" />

<h2>Activity Graph</h2>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TYFSADIK&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" alt="contribution activity graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:7aa2f7,100:1a1b26&height=120&section=footer&text=Securing%20infrastructure%20from%20the%20ground%20up&fontSize=15&fontColor=c0caf5&fontAlignY=75" alt="footer wave" />

</div>
