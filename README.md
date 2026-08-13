<h1 align="center">Mihir Singh Choudhary</h1>

<p align="center">
  <b>Digital Forensics &amp; Incident Response Analyst</b><br>
  <sub>GCFA · GIAC Advisory Board Member · Hyderabad, India</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mihir-choudhary/"><img src="https://img.shields.io/badge/LinkedIn-mihir--choudhary-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:mihirsinghchoudhary777@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-2EA043?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/Mihir-Choudhary?tab=repositories"><img src="https://img.shields.io/badge/Projects-DFIR_Tooling-24292F?style=for-the-badge&logo=github&logoColor=white" alt="Projects"></a>
</p>

---

### whoami

DFIR analyst with **2 years** of end-to-end investigation experience across Windows, Linux, mobile and cloud environments — currently at **Tata Consultancy Services**.

Day to day that means forensic acquisition and analysis of endpoints, EC2 snapshots, EBS volume images and memory dumps; malware analysis and reverse engineering; Active Directory and server compromise investigations; and cloud account compromise/misuse cases. I spend a lot of time correlating logs and telemetry to build attack timelines and scope incidents.

On the mobile side I work with Cellebrite and a fair amount of **manual SQLite analysis**, including fraud cases involving Indian fintech applications — which is where most of my open-source parsers come from.

- 🔬 **40+** forensic cases investigated — malware, insider threat, ransomware, fraud, data theft
- 🛠️ I build the tooling I wish existed mid-investigation, then open-source it
- 🤖 Interested in automation and AI-assisted analysis in DFIR
- 🧩 Happiest doing full kill-chain reconstruction and artifact-level analysis

---

### Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[EventHawk](https://github.com/Mihir-Choudhary/EventHawk)** ⭐ | Windows EVTX log analysis for DFIR — fast parsing, ATT&CK mapping, IOC extraction and Sentinel anomaly detection. Juggernaut Mode (Arrow/DuckDB) handles 10M+ events. | Python · DuckDB · Arrow |
| **[Android-PhonePe-Forensics](https://github.com/Mihir-Choudhary/Android-Phonepe-Forensics)** | Forensic parser and analysis dashboard for PhonePe Android extractions, with deleted-record recovery. | Python · SQLite |
| **[Paytm-Forensics](https://github.com/Mihir-Choudhary/Paytm-Forensics)** | Offline, read-only forensic parser for the Paytm Android app (`net.one97.paytm`). *WIP* | Python · SQLite |
| **[SOC-Automation-Project](https://github.com/Mihir-Choudhary/SOC-Automation-Project)** | Alarm collection from Wazuh → ticketing in TheHive → analyst notification, orchestrated with Shuffle. | Wazuh · TheHive · Shuffle |
| **[EDR-SOAR-Automation-Project](https://github.com/Mihir-Choudhary/EDR-SOAR-Automation-Project)** | Detection, alerting and response workflow integrating LimaCharlie, Tines and Slack. | LimaCharlie · Tines · Slack |

---

### Open Source Contributions

Upstream work on tools the DFIR community actually uses:

| Contribution | Project | Status |
| :--- | :--- | :--- |
| [`--ads` switch to scan alternate data streams for hidden prefetch](https://github.com/EricZimmerman/PECmd/pull/17) | **PECmd** *(Eric Zimmerman's EZ Tools)* | Open |
| [`windows.malware.apihooks` plugin for Windows API hook detection](https://github.com/volatilityfoundation/volatility3/pull/1968) | **Volatility 3** | Open |
| [Fixed a critical credential-vault bug (dead S3 upload) + GUI overhaul](https://github.com/sujayadkesar/IR-Agent-Builder/pull/1) | **IR-Agent-Builder** | Merged |
| [Self-contained collector: static CRT, configurable output path, verbose diagnostics](https://github.com/sujayadkesar/IR-Agent-Builder/pull/2) | **IR-Agent-Builder** | Merged |
| [Security audit fixes: IAM/SSE-KMS deny (HIGH), sidecar encryption, hardening](https://github.com/sujayadkesar/IR-Agent-Builder/pull/3) | **IR-Agent-Builder** | Merged |
| [Fixed collector OOM on large collections — chunked X509 encryption](https://github.com/sujayadkesar/IR-Agent-Builder/pull/4) | **IR-Agent-Builder** | Merged |
| [Forensic-integrity and correctness fixes in the shared engine](https://github.com/sujayadkesar/PhonePe-Forensics/pull/3) | **PhonePe-Forensics** | Merged |
| [Unified launcher for the iOS and Android analysers](https://github.com/sujayadkesar/PhonePe-Forensics/pull/4) | **PhonePe-Forensics** | Merged |
| [Timeline filters, browse button, timeline-completeness fix](https://github.com/sujayadkesar/PhonePe-Forensics/pull/1) | **PhonePe-Forensics** | Merged |

---

### Toolbox

**Forensic Suites**

![Magnet Axiom](https://img.shields.io/badge/Magnet_Axiom-1F2937?style=flat-square)
![Cellebrite UFED](https://img.shields.io/badge/Cellebrite_UFED-1F2937?style=flat-square)
![Cellebrite PA](https://img.shields.io/badge/Cellebrite_PA-1F2937?style=flat-square)
![Cellebrite Inseyets](https://img.shields.io/badge/Cellebrite_Inseyets-1F2937?style=flat-square)
![FTK](https://img.shields.io/badge/FTK-1F2937?style=flat-square)
![OpenText](https://img.shields.io/badge/OpenText-1F2937?style=flat-square)
![Cado](https://img.shields.io/badge/Cado-1F2937?style=flat-square)
![EZ Tools](https://img.shields.io/badge/EZ_Tools-1F2937?style=flat-square)
![Volatility](https://img.shields.io/badge/Volatility-1F2937?style=flat-square)

**Reverse Engineering & Malware**

![Ghidra](https://img.shields.io/badge/Ghidra-8B1A1A?style=flat-square)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-8B1A1A?style=flat-square)
![Malware Analysis](https://img.shields.io/badge/Malware_Analysis-8B1A1A?style=flat-square)
![Memory Forensics](https://img.shields.io/badge/Memory_Forensics-8B1A1A?style=flat-square)

**Disciplines**

![Endpoint Forensics](https://img.shields.io/badge/Endpoint_Forensics-2EA043?style=flat-square)
![Mobile Forensics](https://img.shields.io/badge/Mobile_Forensics-2EA043?style=flat-square)
![Cloud Forensics](https://img.shields.io/badge/Cloud_Forensics-2EA043?style=flat-square)
![Incident Response](https://img.shields.io/badge/Incident_Response-2EA043?style=flat-square)
![Log Analysis](https://img.shields.io/badge/Log_Analysis-2EA043?style=flat-square)
![Threat Hunting](https://img.shields.io/badge/Threat_Hunting-2EA043?style=flat-square)

**Platforms & Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square)

---

### Certifications

![GCFA](https://img.shields.io/badge/GCFA-GIAC_Certified_Forensic_Analyst-2EA043?style=flat-square)
![GIAC Advisory Board](https://img.shields.io/badge/GIAC-Advisory_Board_Member-2EA043?style=flat-square)
![SC-200](https://img.shields.io/badge/SC--200-Security_Operations_Analyst_Associate-0078D4?style=flat-square)
![eJPT](https://img.shields.io/badge/eJPT-Junior_Penetration_Tester-1F2937?style=flat-square)
![ICCA](https://img.shields.io/badge/ICCA-Certified_Cloud_Associate-1F2937?style=flat-square)

---

<details>
<summary><b>Experience &amp; Education</b></summary>

<br>

**Digital Forensic Analyst** — Tata Consultancy Services · Hyderabad, India · *07/2025 – Present*

- Digital forensics investigations across multiple operating systems: DLP incidents, server compromises, breaches and malware intrusions
- Ransomware outbreaks and Domain Controller breaches — rapid triage, evidence acquisition, malware analysis and attack-timeline reconstruction to drive containment and remediation within SLA
- Cloud forensics: EC2 snapshot acquisition, EBS volume imaging, memory dumps, CloudTrail and VPC Flow Log analysis
- Malware analysis and reverse engineering with Ghidra and IDA Pro
- Forensic tool assessment for a German financial firm post-cyberattack — evaluated the environment and IR process, identified gaps and recommended improvements to forensics, IR and threat hunting
- Mobile forensics with Cellebrite UFED plus manual SQLite parsing for complex cases; custom tooling for Indian apps to uncover fraud patterns
- Forensically sound image acquisition (E01, AFF4, RAW) of laptops, desktops and servers
- Cloud account acquisitions for OneDrive and Google Drive in compromise and data-theft investigations
- Strict evidence handling, chain of custody, secure storage and documentation at every stage

**Cybersecurity Intern** — Requin Solutions Pvt Ltd · Jaipur, India · *08/2023 – 04/2024*

- SIEM tuning: rule adjustment and alert-relevance improvement
- SIEM agent deployment and configuration for reliable log collection
- Built SIEM use cases for login monitoring, endpoint events and anomaly detection
- Vulnerability assessment with Nessus and Nmap; prioritised findings by cost-impact and recommended remediation

**B.Tech, Computer Science and Engineering** *(Cyber Security)* — Vellore Institute of Technology · 2021 – 2025 · CGPA 8.3/10

</details>

---

<p align="center">
  <sub>Open to conversations about DFIR, forensic tooling and parser development — <a href="https://www.linkedin.com/in/mihir-choudhary/">LinkedIn</a> · <a href="mailto:mihirsinghchoudhary777@gmail.com">Email</a></sub>
</p>
