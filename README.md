<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:161b22&height=130&section=header&text=SAHIL%20RANA&fontSize=38&fontColor=ffffff&fontAlignY=45&desc=Security%20Engineer%20|%20Systems%20Internals,%20Detection%20Engineering%20%26%20Offensive%20Research&descAlignY=75&descSize=14&descColor=8b949e" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=15&pause=1200&color=58A6FF&center=true&vCenter=true&width=750&lines=Security+Engineer+%40+Innspark;Detection+Engineering+%26+Adversary+Emulation;Low-Level+Systems+Internals+(C%2C+Rust%2C+C%2B%2B);Active+Directory+Attack+Paths+%26+Windows+Telemetry;Machine+Learning+Applied+to+Security+Operations" />

<br/>

[![Company](https://img.shields.io/badge/Organization-Innspark-0d1117?style=flat-square&logo=shield&logoColor=58a6ff)](https://github.com/nexus8222)
[![Role](https://img.shields.io/badge/Focus-Detection%20%26%20Red%20Teaming-0d1117?style=flat-square&logo=target&logoColor=58a6ff)](https://github.com/nexus8222)
[![Location](https://img.shields.io/badge/Location-New%20Delhi%2C%20India-0d1117?style=flat-square&logo=googlemaps&logoColor=58a6ff)](https://github.com/nexus8222)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sahil%20Rana-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://www.linkedin.com/in/sahil-rana-754680285/)
[![Email](https://img.shields.io/badge/Email-ProtonMail-0d1117?style=flat-square&logo=protonmail&logoColor=58a6ff)](mailto:mommamommame@proton.me)

</div>

---

## Executive Overview

I am a Security Engineer at **Innspark** focused on detection engineering, adversary emulation, systems internals, and security operations telemetry. My work operates at the intersection of low-level offensive techniques and high-fidelity defensive architectures:

- **Offensive Systems Research:** Dissecting operating system internals, executing direct system calls, bypassing Win32 API hooks, and developing high-throughput systems-level enumeration tools in C and Rust.
- **Defensive Engineering & Detection:** Engineering high-signal detection logic, parsing Windows event log architectures, modeling Active Directory attack graphs, and building automated threat intelligence harvesting pipelines.
- **Applied AI & Security Automation:** Exploring reinforcement learning, predictive modeling, and machine learning pipelines applied to log correlation, anomaly identification, and automated threat response.

---

## Core Focus Areas

### 01. Low-Level Systems & Offensive Security
- **Windows Internals & API Evasion:** Researching manual PE loader mechanics, direct syscall invocation, NTAPI resolution via in-memory TEB/PEB traversal, and custom in-memory section remapping without standard Win32 exports.
- **Stealth & Concurrency in Rust:** Building concurrent privilege escalation and reconnaissance engines utilizing parallel thread pools (Rayon) for high execution speed, minimal CPU overhead, and reduced artifact generation.
- **Secure Network Transport:** Implementing cryptographically hardened, low-level client-server socket communication protocols in C to mitigate active interception and eavesdropping.

### 02. Detection Engineering & Threat Hunting
- **Telemetry Pipelines:** Architecting detection strategies across raw Windows XML event logs, Sysmon telemetry, and host audit policies.
- **Graph-Based Attack Path Analysis:** Translating forensic event logs into actionable relationship graphs to trace lateral movement, privilege elevation, and credential access.
- **Threat Intelligence Automation:** Automating bulk ingestion, reputation indexing, and verification workflows for Indicators of Compromise (IOCs) across multiple threat intelligence feeds.

### 03. Enterprise Identity & Active Directory Security
- **Attack Graph Orchestration:** Simulating enterprise AD compromises including Kerberoasting, AS-REP roasting, ACL abuse, unconstrained delegation, and DC shadow attacks.
- **Lab Infrastructure as Code:** Developing automated Vagrant and PowerShell environments designed for active certification preparation (CRTP, CRTO, CRTE).

### 04. Applied AI, ML & DevSecOps
- **Machine Learning for Security:** Training models on security datasets for anomaly detection, feature classification, and IOC behavior scoring.
- **Infrastructure Security:** Hardening cloud workloads with Terraform, containerizing services via Docker, managing orchestration with Kubernetes, and enforcing automated security baselines in CI/CD pipelines.

---

## Technical Competencies

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Languages** | C, C++, Rust, Python, Bash, PowerShell, Go, x86/x64 Assembly (Fundamentals) |
| **Systems Internals** | PE Format Parsing, TEB/PEB Traversal, Native API / Syscalls, Process Injection, Thread Pools |
| **Detection & Analysis** | Windows XML Event Logs, Sysmon, SIEM/EDR Telemetry, Log Analysis, Wireshark |
| **Offensive & Identity** | Active Directory Pentesting, BloodHound / Log-hound, Privilege Escalation, Kerberos Abuse |
| **Cloud & Infrastructure** | Docker, Kubernetes, Terraform, Ansible, Vagrant, AWS, Azure, Linux (Debian, Arch), Windows Server |
| **AI & Data Science** | PyTorch, Scikit-learn, Reinforcement Learning, Pandas, NumPy, Jupyter |

<br/>

<div align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,rust,py,bash,powershell,linux,windows,docker,kubernetes,terraform,ansible,git,aws,azure&theme=dark" alt="Technical Stack" />
</div>

---

## Featured Security Projects & Research

### [PE-Loader-No-API](https://github.com/nexus8222/PE-Loader-No-API)
*Low-Level Windows Internals & Loader Development in C*
- Custom in-memory PE loader written entirely in C without calling standard Win32 API functions (`LoadLibraryA`, `GetProcAddress`, `VirtualAlloc`).
- Resolves module addresses and API pointers via manual traversal of the Process Environment Block (PEB) and Thread Environment Block (TEB).
- Manually maps PE sections into memory, applies base relocations, and reconstructs the Import Address Table (IAT) directly from raw headers.

### [Rust_Enum_Peas](https://github.com/nexus8222/Rust_Enum_Peas)
*High-Performance Privilege Escalation Engine in Rust*
- Fast, multi-threaded privilege escalation and system interrogation utility engineered natively in Rust.
- Utilizes work-stealing thread pools via Rayon for parallel execution across enumeration vectors.
- Designed to minimize memory footprint, eliminate external shell process spawning, and evade signature-based detection mechanisms common to script-based tools.

### [Log-hound](https://github.com/nexus8222/Log-hound)
*Log-Based Graph Threat Hunting Engine in Rust*
- Security analysis tool inspired by BloodHound, tailored to parse and map security relationships directly from Windows XML event logs.
- Reconstructs active session histories, privilege transitions, and suspicious lateral movement paths into structured relational data for forensic analysis.

### [Vuln-AD](https://github.com/nexus8222/Vuln-AD)
*Automated Active Directory Lab Orchestration*
- Automated deployment scripts utilizing Vagrant and PowerShell to spin up realistic, multi-tiered vulnerable Active Directory environments.
- Pre-configured misconfigurations covering ACL abuse paths, constrained and unconstrained delegation, vulnerable certificate services, and Kerberos exploitation vectors for CRTP/CRTO/CRTE preparation.

### [VirusTotal-Automated-Crawl](https://github.com/nexus8222/VirusTotal-Automated-Crawl)
*Automated Threat Intelligence & IOC Pipeline*
- Scalable Python tool for automated extraction, scraping, and verification of threat indicators from bulk CSV feeds.
- Supports heterogeneous IOC types (IP addresses, domain names, file hashes, URLs) with automated reputation reporting and visual verification artifact generation.

### [Kukupu-Chat](https://github.com/nexus8222/Kukupu-Chat)
*Secure Socket Communication Protocol in C*
- Low-level network communication client/server system engineered in C.
- Implements encrypted transport channels over raw network sockets to ensure end-to-end confidentiality and protection against active eavesdropping and man-in-the-middle attacks.

---

## GitHub Telemetry

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nexus8222&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nexus8222&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="165" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=nexus8222&theme=dark&hide_border=true&background=0D1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=8b949e" alt="Streak Stats" />
</div>

---

## Correspondence & Verification

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sahil%20Rana-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-rana-754680285/)
[![ProtonMail](https://img.shields.io/badge/ProtonMail-mommamommame@proton.me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white)](mailto:mommamommame@proton.me)
[![GitHub](https://img.shields.io/badge/GitHub-nexus8222-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nexus8222)

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161b22,100:0d1117&height=90&section=footer" width="100%"/>
</div>
