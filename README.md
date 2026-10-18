<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:090d16,50:0d1b2a,100:1b263b&height=180&section=header&text=SAHIL%20RANA&fontSize=52&fontColor=38bdf8&fontAlignY=42&desc=SECURITY%20ENGINEER%20//%20SYSTEMS%20INTERNALS%20%26%20DETECTION%20RESEARCH&descAlignY=66&descSize=16&descColor=94a3b8" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=16&duration=3000&pause=1000&color=38BDF8&background=00000000&center=true&vCenter=true&width=750&lines=%3E_Security+Engineer+%40+Innspark;%3E_Adversary+Emulation+%26+Offensive+Tooling;%3E_Low-Level+Systems+Internals+%5BC%2C+Rust%2C+Assembly%5D;%3E_Detection+Pipelines+%26+Windows+Telemetry;%3E_Applied+Reinforcement+Learning+%26+AI+Defenses" />

<br/>

[![Status](https://img.shields.io/badge/System-ONLINE-00c853?style=flat-square&logo=statuspage&logoColor=white)](https://github.com/nexus8222)
[![Organization](https://img.shields.io/badge/Unit-Innspark-0284c7?style=flat-square&logo=shield&logoColor=white)](https://github.com/nexus8222)
[![Role](https://img.shields.io/badge/Role-Security%20Engineer-0f172a?style=flat-square&logo=target&logoColor=38bdf8)](https://github.com/nexus8222)
[![Location](https://img.shields.io/badge/Location-New%20Delhi%2C%20IN-0f172a?style=flat-square&logo=googlemaps&logoColor=38bdf8)](https://github.com/nexus8222)
[![Email](https://img.shields.io/badge/Email-nebulahartmaan%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:nebulahartmaan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Network-Sahil%20Rana-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-rana-754680285/)

</div>

---

### [>] SYSTEM DIAGNOSTICS & TELEMETRY

```ini
[HOST_CONFIG]
User            = nexus8222 (Sahil Rana)
Designation     = Security Engineer
Division        = Innspark [Threat Detection & Cyber Operations]
Primary_Focus   = Detection Engineering, Adversary Emulation & Systems Internals
Core_Toolchain  = [ Rust, C, C++, Python, PowerShell, Bash, Go ]
Infrastructure  = [ Linux (Debian/Arch), Windows Server, Docker, Kubernetes, Terraform ]
Current_Status  = Engineering low-level loaders & high-throughput log analysis engines
Comms_Endpoint  = nebulahartmaan@gmail.com
```

---

### [>] OPERATIONAL ARCHITECTURE & FOCUS MODULES

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>// 01. OFFENSIVE INTERNALS & SYSTEMS TOOLING</h4>
      <ul>
        <li><b>Windows Native Internals:</b> In-memory PE parsing, direct syscall execution, TEB/PEB traversal, and manual IAT reconstruction without standard Win32 exports.</li>
        <li><b>High-Throughput Concurrency in Rust:</b> Developing multi-threaded system enumeration engines utilizing Rayon thread pools for maximum speed with minimal memory footprint.</li>
        <li><b>Network Protocol Engineering:</b> Crafting custom socket-level encrypted transport protocols in C to eliminate interception and MITM vectors.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>// 02. DETECTION ENGINEERING & THREAT HUNTING</h4>
      <ul>
        <li><b>Telemetry Pipelines:</b> Ingesting, parsing, and extracting intelligence from Windows XML event logs, Sysmon pipelines, and endpoint sensors.</li>
        <li><b>Graph-Based Attack Correlation:</b> Mapping lateral movement, credential access, and privilege escalation using graph theory applied to forensic log data.</li>
        <li><b>Threat Intelligence Pipelines:</b> Automated batch extraction, enrichment, and reputation analysis for multi-vector Indicators of Compromise (IOCs).</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>// 03. ENTERPRISE IDENTITY & ACTIVE DIRECTORY</h4>
      <ul>
        <li><b>AD Attack Vectors:</b> Simulating Kerberoasting, AS-REP roasting, ACL abuse, unconstrained delegation, and shadow credentials in complex environments.</li>
        <li><b>Automated Lab Orchestration:</b> Engineering reproducible Vagrant/PowerShell environments tailored for CRTP, CRTO, and CRTE practical training.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>// 04. APPLIED AI & CLOUD SECURITY</h4>
      <ul>
        <li><b>AI-Driven Security Operations:</b> Investigating reinforcement learning and deep learning architectures applied to automated triage and anomaly detection.</li>
        <li><b>DevSecOps & Infrastructure as Code:</b> Hardening Terraform templates, securing container runtimes, and embedding policy enforcement in CI/CD pipelines.</li>
      </ul>
    </td>
  </tr>
</table>

---

### [>] TECHNICAL ARSENAL

| Layer | Technologies & Implementations |
| :--- | :--- |
| **Languages** | `Rust` `C` `C++` `Python` `Bash` `PowerShell` `Go` `x86/x64 Assembly` |
| **Systems & Internals** | PE Header Parsing, Direct Syscalls, Native NTAPI, In-Memory Relocations, Process Injection |
| **Detection & Telemetry** | Windows XML Event Logs, Sysmon, SIEM/EDR Telemetry, Network Packet Forensics (Wireshark) |
| **Identity & Red Team** | Active Directory Pentesting, BloodHound / Log-hound, Privilege Escalation, Kerberos Exploitation |
| **Infrastructure & Cloud** | Docker, Kubernetes, Terraform, Ansible, Vagrant, Linux (Debian, Arch), Windows Server, AWS, Azure |
| **Applied AI & Analytics** | PyTorch, Scikit-learn, Reinforcement Learning, Pandas, NumPy, Jupyter |

<br/>

<div align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,rust,py,bash,powershell,linux,windows,docker,kubernetes,terraform,ansible,git,aws,azure&theme=dark" alt="Technical Arsenal" />
</div>

---

### [>] PROJECT DOSSIER // SELECTED REPOSITORIES

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/PE-Loader-No-API">PE-Loader-No-API</a></h4>
      <code>C</code> &bull; <code>WINDOWS INTERNALS</code> &bull; <code>EVASION</code>
      <p>Custom in-memory PE loader written entirely in C without calling standard Win32 export APIs (e.g. LoadLibraryA, VirtualAlloc, GetProcAddress). Resolves module addresses via in-memory TEB/PEB traversal, allocates sections, applies base relocations, and manually reconstructs the Import Address Table.</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/Rust_Enum_Peas">Rust_Enum_Peas</a></h4>
      <code>RUST</code> &bull; <code>CONCURRENCY</code> &bull; <code>PRIVILEGE ESCALATION</code>
      <p>High-throughput local enumeration engine written natively in Rust. Leverages Rayon thread pools for parallel vector assessment, reducing execution time while maintaining stealth and minimizing artifacts compared to shell-based scripts.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/Log-hound">Log-hound</a></h4>
      <code>RUST</code> &bull; <code>DETECTION ENGINEERING</code> &bull; <code>GRAPH ANALYSIS</code>
      <p>A BloodHound-inspired forensic utility engineered in Rust. Ingests Windows XML event logs and translates telemetry events into graph relationships to discover adversary lateral movement and privilege abuse paths.</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/Vuln-AD">Vuln-AD</a></h4>
      <code>POWERSHELL</code> &bull; <code>VAGRANT</code> &bull; <code>ACTIVE DIRECTORY</code>
      <p>Infrastructure-as-code automation using Vagrant and PowerShell to deploy a complete, multi-tiered vulnerable Active Directory lab. Emulates enterprise privilege chains and delegation misconfigurations for CRTP/CRTO/CRTE training.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/VirusTotal-Automated-Crawl">VirusTotal-Automated-Crawl</a></h4>
      <code>PYTHON</code> &bull; <code>THREAT INTELLIGENCE</code> &bull; <code>AUTOMATION</code>
      <p>Multi-threaded IOC processing engine capable of bulk reputation assessment across IPs, domains, hashes, and URLs from CSV feeds, generating structured output and visual verification captures for SOC analysis.</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/nexus8222/Kukupu-Chat">Kukupu-Chat</a></h4>
      <code>C</code> &bull; <code>SOCKETS</code> &bull; <code>CRYPTOGRAPHY</code>
      <p>Low-level client/server socket application written in C with an encrypted transport layer designed to protect network communications against packet sniffing and active man-in-the-middle attacks.</p>
    </td>
  </tr>
</table>

---

### [>] LIVE METRICS & ACTIVITY

<div align="center">
  <table border="0">
    <tr>
      <td align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=nexus8222&show_icons=true&bg_color=090d16&title_color=38bdf8&text_color=94a3b8&icon_color=38bdf8&border_color=1e293b" height="165" alt="GitHub Stats" />
      </td>
      <td align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nexus8222&layout=compact&bg_color=090d16&title_color=38bdf8&text_color=94a3b8&border_color=1e293b" height="165" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=nexus8222&background=090D16&stroke=1E293B&ring=38BDF8&fire=38BDF8&currStreakLabel=94A3B8&sideLabels=94A3B8&dates=64748B" alt="Streak Stats" />
</div>

---

### [>] DIRECT COMM LINK // VERIFICATION

<div align="center">

[![Email](https://img.shields.io/badge/Direct_Comms-nebulahartmaan%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nebulahartmaan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sahil_Rana-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-rana-754680285/)
[![GitHub](https://img.shields.io/badge/GitHub-nexus8222-090D16?style=for-the-badge&logo=github&logoColor=38BDF8)](https://github.com/nexus8222)

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:0d1b2a,100:1b263b&height=100&section=footer" width="100%"/>
</div>
