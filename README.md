# Hi, I'm Ben 👋

### SOC Manager | Detection Engineer | Security Automation Advocate

I run the SOC day-to-day. My focus is detection engineering, incident response, and building automation that removes grunt work from the analyst queue. The goal is always the same: find real threats faster and cut the noise.

---

## 🔒 What I Do

- **Security Operations Leadership**: Managing SOC teams, shift coverage, SLA governance, and analyst development
- **Detection Engineering**: Writing and tuning detection rules (Sigma, KQL, SPL) mapped to MITRE ATT&CK
- **Incident Response**: Running IR playbooks from phishing to ransomware; P1 incident commander
- **Security Automation**: Building Python tools for alert triage, IOC enrichment, and SOAR integration
- **Threat Intelligence**: Actor profiling, TI feed management, IOC lifecycle, MISP integration
- **Compliance & Reporting**: NIST CSF, ISO 27001; board-level executive summaries and CISO dashboards

---

## 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=reninjk&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=reninjk&layout=compact&theme=dark&hide_border=true" height="165" alt="Top Languages" />
</p>
<p align="center">
<img src="https://streak-stats.demolab.com?user=reninjk&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

---

## 🚧 Currently Building

| Project | Status | Description |
|---------|--------|-------------|
| SOAR Webhook Listener | ✅ Complete | FastAPI receiver with auto-triage and IOC enrichment |
| ATT&CK Coverage Expansion | 🔄 In Progress | Growing Sigma rule library across all tactics |
| DNS Beaconing Detection | ✅ Complete | High-fidelity C2 detection via DNS frequency analysis |
| Threat Actor Profiles | 🔄 In Progress | Structured actor profiles with full TTP mapping |
| Quarterly Compliance Reporting | ⏳ Planned | Automated NIST CSF gap analysis + board pack |

---

## 🛠 SOC Repositories

| Repository | Description | CI |
|---|---|---|
| 🚨 [soc-incident-response](https://github.com/reninjk/soc-incident-response) | IR playbooks, runbooks, and incident report templates covering phishing through ransomware | ![CI](https://github.com/reninjk/soc-incident-response/actions/workflows/validate.yml/badge.svg) |
| 🔍 [soc-detection-rules](https://github.com/reninjk/soc-detection-rules) | Sigma detection rules and threat hunting queries mapped to MITRE ATT&CK | ![CI](https://github.com/reninjk/soc-detection-rules/actions/workflows/validate.yml/badge.svg) |
| ⚙️ [soc-automation](https://github.com/reninjk/soc-automation) | Python tools for alert triage, IOC enrichment, SOAR webhook integration, and metrics | ![CI](https://github.com/reninjk/soc-automation/actions/workflows/ci.yml/badge.svg) |
| 📊 [soc-compliance-reporting](https://github.com/reninjk/soc-compliance-reporting) | NIST CSF audit checklists, SOC KPI metrics, weekly/monthly executive report templates | ![CI](https://github.com/reninjk/soc-compliance-reporting/actions/workflows/validate.yml/badge.svg) |
| 🌐 [soc-threat-intelligence](https://github.com/reninjk/soc-threat-intelligence) | IOC feeds, threat actor profiles with TTP mapping, TI reports, and MISP integration | ![CI](https://github.com/reninjk/soc-threat-intelligence/actions/workflows/validate.yml/badge.svg) |
| 🛡️ [soc-vulnerability-management](https://github.com/reninjk/soc-vulnerability-management) | Vulnerability workflows, patch SLA tracking, CVSS risk scoring, and remediation processes | ![CI](https://github.com/reninjk/soc-vulnerability-management/actions/workflows/validate.yml/badge.svg) |
| 🎓 [soc-training-lab](https://github.com/reninjk/soc-training-lab) | Analyst onboarding, training scenarios, tabletop exercises (ransomware + BEC), cert roadmap | ![CI](https://github.com/reninjk/soc-training-lab/actions/workflows/validate.yml/badge.svg) |

---

## 🧰 Tech & Tools

**SIEM / Detection** &nbsp; ![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white) ![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white) ![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat&logo=elastic&logoColor=white)

**Languages & Scripting** &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white) ![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logo=yaml&logoColor=white)

**Detection Formats** &nbsp; ![Sigma](https://img.shields.io/badge/Sigma-Rules-blueviolet?style=flat) ![KQL](https://img.shields.io/badge/KQL-Sentinel-0078D4?style=flat) ![SPL](https://img.shields.io/badge/SPL-Splunk-000000?style=flat)

**Frameworks & Standards** &nbsp; ![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-E4002B?style=flat) ![NIST CSF](https://img.shields.io/badge/NIST_CSF-003087?style=flat) ![ISO 27001](https://img.shields.io/badge/ISO_27001-00843D?style=flat)

**DevOps & Automation** &nbsp; ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## 🎯 MITRE ATT&CK Coverage

Current Sigma rule coverage across tactics (soc-detection-rules):

| Tactic | Rules | Key Techniques |
|--------|-------|----------------|
| Initial Access | 1 | T1566 Phishing |
| Execution | 1 | T1059 Scripting |
| Persistence | 1 | T1053 Scheduled Task |
| Privilege Escalation | 1 | T1053.005 Scheduled Task |
| Defence Evasion | 1 | T1562 Disable Tools |
| Credential Access | 2 | T1003.001 LSASS, T1110 Brute Force |
| Discovery | 1 | T1082 System Info |
| Lateral Movement | 2 | T1021.001 RDP, T1021.002 SMB |
| Command & Control | 1 | T1071.004 DNS Beaconing |
| Impact | 1 | T1486 Ransomware |
| **TOTAL** | **12** | Expanding monthly |

---

## 🧠 My SOC Philosophy

> *"A SOC that can't measure itself, can't improve itself."*

I believe in three pillars for effective security operations:

1. **Detect more, alert less**: High-fidelity detections beat alert fatigue every time. Tune ruthlessly.
2. **Automate the repeatable**: Every manual task a machine can do is analyst time freed for real hunting.
3. **Communicate clearly**: A P1 incident handled perfectly but reported poorly loses stakeholder trust.

---

## 📁 Repository Structure Philosophy

All my SOC repos follow the same principles:

- ✅ **Version-controlled**: every playbook, rule, and script change tracked in Git
- ✅ **CI/CD validated**: GitHub Actions check structure, syntax, and links on every push
- ✅ **Framework-mapped**: detection rules and playbooks tagged to MITRE ATT&CK tactics
- ✅ **Tool-agnostic where possible**: Sigma rules convert to Splunk SPL, Microsoft KQL, Elastic EQL
- ✅ **Peer-reviewed**: all production changes go through PR review
- ✅ **OPSEC-first**: no real credentials, IOCs, or employer data in any repo

---

## 📬 Get in Touch

- GitHub: [@reninjk](https://github.com/reninjk)
- Open to connecting with fellow SOC practitioners, detection engineers, and IR professionals

---

*"Security is not a product, but a process." - Bruce Schneier*
