<img src="assets/banner.svg" alt="Mihir Singh Choudhary — Digital Forensics & Incident Response" width="100%">

<p align="center">
  <a href="https://www.linkedin.com/in/mihir-choudhary/"><img src="https://img.shields.io/badge/LinkedIn-mihir--choudhary-0A66C2?style=for-the-badge&labelColor=0D1117" alt="LinkedIn"></a>
  <a href="mailto:mihirsinghchoudhary777@gmail.com"><img src="https://img.shields.io/badge/Email-reach_out-3FB950?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"></a>
  <a href="https://github.com/Mihir-Choudhary?tab=repositories"><img src="https://img.shields.io/badge/Repos-DFIR_tooling-3FB950?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="Repositories"></a>
</p>

<img src="assets/stats.svg" alt="40+ cases investigated · 3 forensic tools built · 2 years DFIR experience · GCFA" width="100%">

<br>

## ▍whoami

DFIR analyst at **Tata Consultancy Services**, running end-to-end investigations across Windows, Linux, mobile and cloud. Forensic acquisition of endpoints, EC2 snapshots, EBS volumes and memory dumps; malware analysis and reverse engineering; Active Directory and server compromise; cloud account compromise and misuse.

Most of my time goes into correlating logs and telemetry into an attack timeline that actually holds up. When a tool doesn't exist for the artifact in front of me, I write one — that's where everything below came from.

```yaml
disk_forensics:   E01 / AFF4 / RAW acquisition · NTFS artifacts · registry · prefetch · timeline reconstruction
memory_forensics: Volatility 3 · process & handle analysis · injected code · API hook detection
mobile_forensics: Cellebrite UFED · manual SQLite carving · deleted-record recovery · Indian fintech apps
cloud_forensics:  EC2 snapshot acquisition · EBS imaging · CloudTrail & VPC Flow Logs · OneDrive / GDrive
malware_analysis: Ghidra · IDA Pro · static & dynamic triage · reverse engineering
automation:       parser development · AI-assisted analysis · scripting
```

<br>

## ▍Tooling I've Built

<table>
<tr>
<td width="33%" valign="top">

### [EventHawk](https://github.com/Mihir-Choudhary/EventHawk)
![stars](https://img.shields.io/github/stars/Mihir-Choudhary/EventHawk?style=flat-square&labelColor=0D1117&color=3FB950)
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3FB950)

Windows **EVTX log analysis** for DFIR — fast parsing, ATT&CK mapping, IOC extraction and Sentinel anomaly detection.

*Juggernaut Mode* (Arrow/DuckDB) chews through 10M+ events.

</td>
<td width="33%" valign="top">

### [Android-PhonePe-Forensics](https://github.com/Mihir-Choudhary/Android-Phonepe-Forensics)
![stars](https://img.shields.io/github/stars/Mihir-Choudhary/Android-Phonepe-Forensics?style=flat-square&labelColor=0D1117&color=3FB950)
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3FB950)

Forensic parser and analysis dashboard for **PhonePe Android** extractions.

Recovers deleted records straight out of the SQLite stores.

</td>
<td width="33%" valign="top">

### [Paytm-Forensics](https://github.com/Mihir-Choudhary/Paytm-Forensics)
![stars](https://img.shields.io/github/stars/Mihir-Choudhary/Paytm-Forensics?style=flat-square&labelColor=0D1117&color=3FB950)
![WIP](https://img.shields.io/badge/status-WIP-D29922?style=flat-square&labelColor=0D1117)

Offline parser for the **Paytm Android** app (`net.one97.paytm`).

Read-only by construction — never writes to evidence.

</td>
</tr>
</table>

<br>

## ▍Upstream Contributions

Contributions to the forensic tools the DFIR community runs every day.

| | Contribution | Project |
| :--- | :--- | :--- |
| ![open](https://img.shields.io/badge/open-3FB950?style=flat-square&labelColor=0D1117) | [`--ads` switch to scan alternate data streams for hidden prefetch](https://github.com/EricZimmerman/PECmd/pull/17) | **PECmd** — Eric Zimmerman's EZ Tools |
| ![open](https://img.shields.io/badge/open-3FB950?style=flat-square&labelColor=0D1117) | [`windows.malware.apihooks` plugin for Windows API hook detection](https://github.com/volatilityfoundation/volatility3/pull/1968) | **Volatility 3** |

<br>

## ▍Arsenal

<table>
<tr><td><b>Forensic&nbsp;Suites</b></td><td>

![Magnet Axiom](https://img.shields.io/badge/Magnet_Axiom-161B22?style=flat-square&labelColor=161B22)
![Cellebrite UFED](https://img.shields.io/badge/Cellebrite_UFED-161B22?style=flat-square&labelColor=161B22)
![Cellebrite PA](https://img.shields.io/badge/Cellebrite_PA-161B22?style=flat-square&labelColor=161B22)
![Cellebrite Inseyets](https://img.shields.io/badge/Inseyets-161B22?style=flat-square&labelColor=161B22)
![FTK](https://img.shields.io/badge/FTK-161B22?style=flat-square&labelColor=161B22)
![OpenText](https://img.shields.io/badge/OpenText-161B22?style=flat-square&labelColor=161B22)
![Cado](https://img.shields.io/badge/Cado-161B22?style=flat-square&labelColor=161B22)
![EZ Tools](https://img.shields.io/badge/EZ_Tools-161B22?style=flat-square&labelColor=161B22)
![Volatility](https://img.shields.io/badge/Volatility-161B22?style=flat-square&labelColor=161B22)

</td></tr>
<tr><td><b>Malware&nbsp;&amp;&nbsp;RE</b></td><td>

![Ghidra](https://img.shields.io/badge/Ghidra-3FB950?style=flat-square&labelColor=161B22&color=161B22)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-161B22?style=flat-square&labelColor=161B22)
![Memory Forensics](https://img.shields.io/badge/Memory_Forensics-161B22?style=flat-square&labelColor=161B22)
![Reverse Engineering](https://img.shields.io/badge/Reverse_Engineering-161B22?style=flat-square&labelColor=161B22)

</td></tr>
<tr><td><b>Disciplines</b></td><td>

![Endpoint Forensics](https://img.shields.io/badge/Endpoint_Forensics-1F6F35?style=flat-square&labelColor=1F6F35)
![Mobile Forensics](https://img.shields.io/badge/Mobile_Forensics-1F6F35?style=flat-square&labelColor=1F6F35)
![Cloud Forensics](https://img.shields.io/badge/Cloud_Forensics-1F6F35?style=flat-square&labelColor=1F6F35)
![Incident Response](https://img.shields.io/badge/Incident_Response-1F6F35?style=flat-square&labelColor=1F6F35)
![Threat Hunting](https://img.shields.io/badge/Threat_Hunting-1F6F35?style=flat-square&labelColor=1F6F35)
![Log Analysis](https://img.shields.io/badge/Log_Analysis-1F6F35?style=flat-square&labelColor=1F6F35)

</td></tr>
<tr><td><b>Platforms&nbsp;&amp;&nbsp;Code</b></td><td>

![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3FB950&labelColor=161B22)
![Rust](https://img.shields.io/badge/Rust-161B22?style=flat-square&logo=rust&logoColor=3FB950&labelColor=161B22)
![C#](https://img.shields.io/badge/C%23-161B22?style=flat-square&logo=dotnet&logoColor=3FB950&labelColor=161B22)
![Bash](https://img.shields.io/badge/Bash-161B22?style=flat-square&logo=gnubash&logoColor=3FB950&labelColor=161B22)
![SQLite](https://img.shields.io/badge/SQLite-161B22?style=flat-square&logo=sqlite&logoColor=3FB950&labelColor=161B22)
![Splunk](https://img.shields.io/badge/Splunk-161B22?style=flat-square&logo=splunk&logoColor=3FB950&labelColor=161B22)
![Linux](https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=3FB950&labelColor=161B22)
![Windows](https://img.shields.io/badge/Windows-161B22?style=flat-square&labelColor=161B22)
![AWS](https://img.shields.io/badge/AWS-161B22?style=flat-square&labelColor=161B22)
![Azure](https://img.shields.io/badge/Azure-161B22?style=flat-square&labelColor=161B22)

</td></tr>
</table>

<br>

## ▍Credentials

![GCFA](https://img.shields.io/badge/GCFA-GIAC_Certified_Forensic_Analyst-3FB950?style=for-the-badge&labelColor=0D1117)
![GIAC Advisory Board](https://img.shields.io/badge/GIAC-Advisory_Board_Member-3FB950?style=for-the-badge&labelColor=0D1117)

![SC-200](https://img.shields.io/badge/SC--200-Security_Operations_Analyst-0078D4?style=flat-square&labelColor=0D1117)
![eJPT](https://img.shields.io/badge/eJPT-Junior_Penetration_Tester-E6EDF3?style=flat-square&labelColor=0D1117)
![ICCA](https://img.shields.io/badge/ICCA-Certified_Cloud_Associate-E6EDF3?style=flat-square&labelColor=0D1117)

<br>

<details>
<summary><b>▍ Case history — experience &amp; education</b></summary>

<br>

**Digital Forensic Analyst** · Tata Consultancy Services · Hyderabad, India · *07/2025 – Present*

- Digital forensics investigations across multiple operating systems: DLP incidents, server compromises, breaches and malware intrusions
- Ransomware outbreaks and Domain Controller breaches — rapid triage, evidence acquisition, malware analysis and attack-timeline reconstruction to drive containment and remediation within SLA
- Cloud forensics: EC2 snapshot acquisition, EBS volume imaging, memory dumps, CloudTrail and VPC Flow Log analysis
- Malware analysis and reverse engineering with Ghidra and IDA Pro
- Forensic tool assessment for a German financial firm post-cyberattack — evaluated the environment and IR process, identified gaps, recommended improvements to forensics, IR and threat hunting
- Mobile forensics with Cellebrite UFED plus manual SQLite parsing for complex cases; custom tooling for Indian apps to uncover fraud patterns
- Forensically sound image acquisition (E01, AFF4, RAW) of laptops, desktops and servers
- Cloud account acquisitions for OneDrive and Google Drive in compromise and data-theft investigations
- Strict evidence handling, chain of custody, secure storage and documentation at every stage

**Cybersecurity Intern** · Requin Solutions Pvt Ltd · Jaipur, India · *08/2023 – 04/2024*

- SIEM tuning: rule adjustment and alert-relevance improvement
- SIEM agent deployment and configuration for reliable log collection
- Built SIEM use cases for login monitoring, endpoint events and anomaly detection
- Vulnerability assessment with Nessus and Nmap; prioritised findings by cost-impact and recommended remediation

**B.Tech, Computer Science and Engineering** *(Cyber Security)* · Vellore Institute of Technology · 2021 – 2025 · CGPA 8.3/10

</details>

<br>

<p align="center">
  <sub>Always up for a conversation about DFIR, forensic tooling and parser development.</sub><br>
  <a href="https://www.linkedin.com/in/mihir-choudhary/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&labelColor=0D1117&color=0A66C2" alt="LinkedIn"></a>
  <a href="mailto:mihirsinghchoudhary777@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117&color=3FB950" alt="Email"></a>
</p>
