<!-- Profile README for MUSFIRA-ZAFAR/MUSFIRA-ZAFAR -->
<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0d1117%2C50%3A12395c%2C100%3A22d3ee&amp;height=230&amp;section=header&amp;text=MUSFIRA+ZAFAR&amp;fontSize=46&amp;fontColor=ffffff&amp;fontAlignY=35&amp;desc=Security+Operations+%7C+Detection+Engineering+%7C+Cloud+Security&amp;descAlignY=56&amp;descSize=16&amp;animation=fadeIn" width="100%" alt="Musfira Zafar — Security Operations, Detection Engineering and Cloud Security"></p>
<h1 align="center">Hi, I'm Musfira 👋</h1>
<p align="center"><strong>Aspiring SOC Analyst · Cybersecurity Practitioner · Blue Team</strong></p>
<p align="center"><img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&amp;weight=500&amp;size=19&amp;duration=3000&amp;pause=1300&amp;color=22D3EE&amp;center=true&amp;vCenter=true&amp;width=740&amp;height=45&amp;lines=Turning+endpoint+telemetry+into+tested+detections%3BFollowing+attack+timelines+through+cloud+logs%3BBuilding+automation+for+security+operations" width="740" alt="Turning endpoint telemetry into tested detections · Investigating cloud logs · Building security automation"></p>
<p align="center">
<a href="https://www.linkedin.com/in/musfira-zafar/"><img src="https://img.shields.io/static/v1?label=LinkedIn&amp;message=Connect&amp;color=0A66C2&amp;labelColor=0d1117&amp;style=flat" height="24" alt="LinkedIn Connect"></a> &nbsp; <img src="https://img.shields.io/static/v1?label=Primary+SIEM&amp;message=Splunk&amp;color=115e59&amp;labelColor=0d1117&amp;style=flat&amp;logo=splunk&amp;logoColor=67e8f9" height="24" alt="Primary SIEM Splunk"> &nbsp; <img src="https://img.shields.io/static/v1?label=Open+to&amp;message=Entry-level+SOC+roles&amp;color=166534&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Open to Entry-level SOC roles">
</p>
<p align="center"><a href="#about">About</a> · <a href="#projects">Projects</a> · <a href="#evidence">Evidence</a> · <a href="#skills">Skills</a> · <a href="#credentials">Credentials</a> · <a href="#direction">Goals</a> · <a href="#connect">Connect</a></p>

---

<a id="about"></a>

## 👩‍💻 Behind the Portfolio

I'm a cybersecurity practitioner from Multan, Pakistan, working toward my first **SOC Analyst / Cybersecurity Analyst role**. I completed an **EduQual Level 3 Diploma in Cloud Cyber Security with 91%** and earned the **Cybrixen Certified SOC Analyst (CCSA)** certification.

My interest is in understanding what happened behind an alert: which account was involved, what process ran, how the activity developed, and what evidence supports the next response step. My projects cover Windows endpoint monitoring, Splunk detections, malware behavior analysis, AWS log investigations, and automated containment.

**Splunk is my primary SIEM.** I also have project experience with Wazuh, Sysmon, Sigma, Chainsaw, Wireshark, AWS CloudTrail, Amazon Athena, and Shuffle.

I share my work through investigation reports, detection queries, screenshots, and troubleshooting notes so others can follow the reasoning and reproduce the labs.

<p align="center"><code>Build → Observe → Investigate → Detect → Validate → Document</code></p>

<table>
<tr>
<td width="25%" align="center"><strong>10</strong><br>Featured repositories</td>
<td width="25%" align="center"><strong>2</strong><br>Agent Tesla Sigma rules validated</td>
<td width="25%" align="center"><strong>6 / 356</strong><br>Key cloud incident events / logged actions</td>
<td width="25%" align="center"><strong>2 branches</strong><br>SOAR isolation and skip paths tested</td>
</tr>
</table>

<details>
<summary><strong>📊 Portfolio snapshot — expand to see my areas of practical work</strong></summary>

## 📌 Portfolio at a Glance

| Area | What I've built or investigated |
| --- | --- |
| **SOC monitoring** | Windows log collection, RDP brute-force detection, SPL searches, and Splunk dashboards |
| **Detection engineering** | Sigma rules validated against Sysmon logs, command-line hunting, and MITRE ATT&CK mapping |
| **Cloud security** | CloudTrail → S3 → Athena logging and SQL investigation of simulated IAM compromise |
| **Security automation** | Shuffle playbook connecting IP enrichment, conditional EC2 isolation, and Slack notification |
| **Network investigations** | Emotet traffic analysis, C2 identification, IOC extraction, and Windows attack investigations |
| **Security tooling** | Python web scanner with a CLI, Flask interface, and Markdown/PDF reporting |
| **Industrial security** | MQTT authentication and TLS, Node-RED monitoring, and Wazuh alerts in an Industry 4.0 demo |

</details>

<a id="projects"></a>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🦠 Agent Tesla Detection</h3>
<p>Turned sandbox observations into persistence and C2 Sigma rules, validated using controlled reproductions.</p>
<p><code>ANY.RUN · Sigma · Sysmon · Chainsaw</code></p>
<p><strong>Evidence:</strong> Two rules matched real endpoint telemetry.</p>
<p><a href="https://github.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab"><strong>Explore project →</strong></a></p>
</td>
<td width="50%" valign="top">
<h3>☁️ Cloud Incident Investigation</h3>
<p>Built cloud logging and investigated a simulated IAM compromise using raw CloudTrail evidence.</p>
<p><code>CloudTrail · S3 · Athena SQL · IAM</code></p>
<p><strong>Evidence:</strong> Six key events reconstructed from 356 logged actions.</p>
<p><a href="https://github.com/MUSFIRA-ZAFAR/secops-cloud-log-auditing"><strong>Explore project →</strong></a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>⚙️ Automated Threat Isolation</h3>
<p>Connected IP reputation enrichment to conditional quarantine of a lab EC2 instance and analyst notification.</p>
<p><code>Shuffle · AbuseIPDB · Lambda · EC2</code></p>
<p><strong>Evidence:</strong> Low-score skip and high-score isolation paths verified.</p>
<p><a href="https://github.com/MUSFIRA-ZAFAR/automated-IP-threat-isolation-playbook"><strong>Explore project →</strong></a></p>
</td>
<td width="50%" valign="top">
<h3>🔎 Splunk Endpoint Detection</h3>
<p>Built Windows log forwarding, SPL detections, and a dashboard for RDP brute-force investigation.</p>
<p><code>Splunk · SPL · Sysmon · Forwarder</code></p>
<p><strong>Evidence:</strong> 15 failed logons followed by one successful authentication.</p>
<p><a href="https://github.com/MUSFIRA-ZAFAR/RDP-Brute-Force-Detection"><strong>Explore project →</strong></a></p>
</td>
</tr>
</table>

## 📁 More of My Work

| Project | What I did | Main tools |
| --- | --- | --- |
| [AD Kerberoasting Detection](https://github.com/MUSFIRA-ZAFAR/AD-Kerberoasting-Detection) | Built an AWS-hosted Samba AD lab, simulated Kerberoasting, investigated RC4 service-ticket requests in Samba logs, and documented response actions and a Sigma detection rule | Samba AD, Impacket, Kerberos tools, John the Ripper, Sigma |
| [FortifyWebX Scanner](https://github.com/MUSFIRA-ZAFAR/fortifywebx-scanner) | Built a crawler with five passive checks, severity scoring, CLI/web interfaces, and Markdown/PDF reports; tested with Juice Shop and DVWA | Python, Flask, Requests, BeautifulSoup, Docker |
| [SOC Investigations](https://github.com/MUSFIRA-ZAFAR/soc-investigations) | Investigated Emotet PCAP traffic, RDP brute-force activity, and Windows attack simulations; extracted IOCs and wrote investigation reports | Wireshark, VirusTotal, Event Viewer, Hydra |
| [Industry 4.0 Security](https://github.com/MUSFIRA-ZAFAR/Industry-4.0-Security) | Implemented MQTT authentication and TLS, built a sensor dashboard, and demonstrated Wazuh brute-force alerts with IEC 62443/NIST CSF mappings | Mosquitto, OpenSSL, Node-RED, Wazuh, Ubuntu |
| [Networking Notes](https://github.com/MUSFIRA-ZAFAR/networking-notes) | Documented networking fundamentals, protocols, subnetting, monitoring, and their relevance to SOC investigations | OSI/TCP-IP, DNS, DHCP, VLANs, VPNs, IDS/IPS |

<a id="evidence"></a>

## 🧪 Inside the Investigations

<details>
<summary><strong>🦠 Agent Tesla — analysis, validation, and scope</strong></summary>

[Explore the repository](https://github.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab)

- Analyzed an existing **ANY.RUN public sandbox report** to identify Agent Tesla scheduled-task persistence and SMTP-based C2 behavior.
- Extracted indicators and mapped findings to **T1053.005** and **T1071.003**.
- Wrote **two Sigma rules**: a behavior-based persistence rule and an indicator-based C2 rule.
- Reproduced the persistence pattern and a DNS lookup on an AWS Windows host, then confirmed both rules matched **real Sysmon logs using Chainsaw**.

**Scope:** validation used controlled behavior reproduction; the malware binary was not executed on the AWS host. The rules remain experimental.

</details>

<details>
<summary><strong>☁️ AWS compromise — evidence and behavioral detections</strong></summary>

[Explore the repository](https://github.com/MUSFIRA-ZAFAR/secops-cloud-log-auditing)

- Built a **CloudTrail → S3 → Amazon Athena** pipeline.
- Simulated compromised credentials, a login without MFA, IAM privilege escalation, and an unauthorized EC2 launch in my own lab account.
- Investigated the raw logs with SQL and reconstructed **six key events from 356 logged actions**.
- Added behavioral queries for self-escalation and baseline deviation, including review of legitimate activity flagged as anomalous.

</details>

<details>
<summary><strong>⚙️ SOAR playbook — tested branches and lab boundaries</strong></summary>

[Explore the repository](https://github.com/MUSFIRA-ZAFAR/automated-IP-threat-isolation-playbook)

- Built a **Shuffle → AbuseIPDB → AWS Lambda → EC2 quarantine → Slack** workflow.
- Used an abuse-confidence threshold **greater than 80** to trigger a security-group change on the lab instance.
- Verified both branches: low-score input skipped isolation; high-score input triggered isolation and notification.
- Documented troubleshooting and the authentication, IAM, and asset-mapping changes needed before production use.

</details>

<details>
<summary><strong>🔎 Splunk labs — RDP correlation and command-line hunting</strong></summary>

[RDP Brute-Force Detection](https://github.com/MUSFIRA-ZAFAR/RDP-Brute-Force-Detection) · [LotL Command-Line Hunting](https://github.com/MUSFIRA-ZAFAR/Lotl-command-line-hunting)

- Built a Windows-to-Splunk log pipeline using **Sysmon and Splunk Universal Forwarder**.
- Investigated **15 failed RDP logons followed by one successful authentication**, using Windows events **4625 and 4624**.
- Created SPL searches and a dashboard to show failed attempts and the subsequent successful logon.
- Captured the `vssadmin.exe delete shadows` command pattern with **Sysmon Event ID 1**, examined process context, and validated an SPL hunt against the ingested evidence.

</details>

<details>
<summary><strong>🖼️ View Agent Tesla detection evidence</strong></summary>

**Persistence rule:** Chainsaw match for the controlled scheduled-task reproduction.

![Chainsaw persistence match](https://raw.githubusercontent.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab/main/screenshots/05-validation/04-chainsaw-persistence-rule-hit.png)

**C2 indicator rule:** Chainsaw match for a DNS lookup of the analyzed indicator.

![Chainsaw DNS indicator match](https://raw.githubusercontent.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab/main/screenshots/05-validation/07-chainsaw-c2-rule-hit-final.png)

[Read the complete validation record](https://github.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab#-validation--proof-of-detection)

</details>

<details>
<summary><strong>🧭 View the SOAR playbook decision flow</strong></summary>

This diagram represents the individual IP threat isolation lab.

```mermaid
flowchart TD
    A["Suspicious IP alert"] --> B["AbuseIPDB enrichment"]
    B --> C{"Score greater than 80?"}
    C -->|Yes| D["Lambda: quarantine lab EC2"]
    C -->|No| E["Skip isolation"]
    D --> F["Slack notification"]
```

</details>

<a id="skills"></a>

## 🛠️ Technical Toolkit

**SIEM & Detection**

<p>
<img src="https://img.shields.io/static/v1?label=&amp;message=Splunk&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=splunk&amp;logoColor=67e8f9" height="24" alt="Splunk"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Sysmon&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Sysmon"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Sigma&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Sigma"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Chainsaw&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Chainsaw"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Wazuh&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Wazuh">
</p>

**Cloud & Automation**

<p>
<img src="https://img.shields.io/static/v1?label=&amp;message=AWS&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="AWS"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=CloudTrail&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="CloudTrail"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Athena+SQL&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Athena SQL"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Lambda&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Lambda"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Shuffle+SOAR&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="Shuffle SOAR"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=AbuseIPDB&amp;color=172033&amp;labelColor=0d1117&amp;style=flat" height="24" alt="AbuseIPDB">
</p>

**Investigation & Development**

<p>
<img src="https://img.shields.io/static/v1?label=&amp;message=Wireshark&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=wireshark&amp;logoColor=67e8f9" height="24" alt="Wireshark"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Python&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=python&amp;logoColor=67e8f9" height="24" alt="Python"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Flask&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=flask&amp;logoColor=67e8f9" height="24" alt="Flask"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Linux&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=linux&amp;logoColor=67e8f9" height="24" alt="Linux"> &nbsp;
<img src="https://img.shields.io/static/v1?label=&amp;message=Docker&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=docker&amp;logoColor=67e8f9" height="24" alt="Docker">
</p>

<details>
<summary><strong>📋 Expand the skills and practical experience matrix</strong></summary>

| Domain | Tools and practical experience |
| --- | --- |
| **SIEM & log analysis** | Splunk Enterprise, SPL, Universal Forwarder, dashboards, Windows Event Logs; Wazuh project experience |
| **Endpoint detection** | Sysmon, Event Viewer, Sigma, Chainsaw, process lineage and command-line analysis |
| **Threat intelligence** | ANY.RUN report analysis, VirusTotal, AbuseIPDB, IOC extraction and MITRE ATT&CK mapping |
| **Cloud security** | AWS EC2, IAM, security groups, CloudTrail, S3, Athena SQL and Lambda |
| **Automation & scripting** | Shuffle workflows, API integration, Python, boto3, Flask; Bash fundamentals |
| **Networking & systems** | Wireshark, TCP/IP, DNS, Linux/Ubuntu, Windows Server, VirtualBox and Docker |
| **Security testing** | Nmap, Hydra, Impacket, DVWA and OWASP Juice Shop in authorized labs |
| **Reporting** | Incident timelines, detection documentation, screenshots, troubleshooting and remediation recommendations |

</details>

<a id="credentials"></a>

## 🎓 Education & Certification

<p>
<img src="https://img.shields.io/static/v1?label=CCSA&amp;message=Certified&amp;color=155e75&amp;labelColor=0d1117&amp;style=flat" height="24" alt="CCSA Certified"> &nbsp; <img src="https://img.shields.io/static/v1?label=EduQual+Level+3&amp;message=91%25&amp;color=115e59&amp;labelColor=0d1117&amp;style=flat" height="24" alt="EduQual Level 3 91%">
</p>

| Qualification | Achievement |
| --- | --- |
| **EduQual Level 3 Diploma in Cloud Cyber Security** | Al Nafi International College · **91%** |
| **Cybrixen Certified SOC Analyst (CCSA)** | Practical SIEM/EDR assessment: investigations, alert correlation, timelines, true/false positives, and escalation |
| **FSc · 2024** | **89.583%** |
| **Student of the Year** | Awarded by my FSc college |

## 💼 Experience & Community

**FortifyWebX — Cybersecurity Internship · July–September 2026**  
Completed practical assignments involving reconnaissance, vulnerability assessment, Linux/Windows security testing, web application testing, scanner development, and technical reporting.

**Cybrixen — Ambassador**  
Refer interested learners to Cybrixen and share cybersecurity learning opportunities through professional outreach.

**Pakistan Network Solutions (PakNS) — Freelance Business Development Specialist**  
Support outreach for cybersecurity consultancy and PECB professional training. This role is helping me develop communication skills and understand organizational security and training needs.

<a id="direction"></a>

## 🎯 Goals & Next Steps

My immediate goal is to join a team as an **entry-level SOC Analyst or Cybersecurity Analyst**, where I can contribute to monitoring, investigation, and clear incident documentation while learning from experienced analysts. I'm open to **remote opportunities that accept candidates based in Pakistan**.

My next steps are to:

- Deepen my Splunk skills in alert correlation, detection tuning, and false-positive analysis.
- Expand investigations across endpoint, network, and cloud evidence.
- Improve Python/Bash scripting and Linux administration.
- Strengthen automation with authentication, least-privilege access, reliable asset mapping, and analyst approval where appropriate.
- Explore AI-assisted SOC workflows for enrichment and investigation summaries while keeping decisions grounded in evidence.

Longer term, I plan to pursue a **BS in Computer Science** and grow into detection engineering and cloud security. I want to build useful security tools and detections that help analysts understand threats and respond with confidence.

## 📈 GitHub Activity

<p align="center">
<a href="https://github.com/MUSFIRA-ZAFAR?tab=followers"><img src="https://img.shields.io/github/followers/MUSFIRA-ZAFAR?style=flat&amp;label=Followers&amp;labelColor=0d1117&amp;color=155e75&amp;logo=github&amp;logoColor=white" height="24" alt="GitHub Followers"></a> &nbsp; <a href="https://github.com/MUSFIRA-ZAFAR?tab=repositories"><img src="https://img.shields.io/github/stars/MUSFIRA-ZAFAR?style=flat&amp;label=Stars&amp;labelColor=0d1117&amp;color=115e59&amp;logo=github&amp;logoColor=white" height="24" alt="GitHub Stars"></a>
</p>

<details>
<summary><strong>🗓️ Explore recent project updates and contributions</strong></summary>

| Project | Latest repository commit |
| --- | --- |
| [Agent Tesla detection lab](https://github.com/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab/commits) | ![Latest Agent Tesla commit](https://img.shields.io/github/last-commit/MUSFIRA-ZAFAR/agenttesla-sigma-detection-lab?style=flat&label=Updated&labelColor=0d1117&color=155e75) |
| [Cloud log auditing](https://github.com/MUSFIRA-ZAFAR/secops-cloud-log-auditing/commits) | ![Latest cloud auditing commit](https://img.shields.io/github/last-commit/MUSFIRA-ZAFAR/secops-cloud-log-auditing?style=flat&label=Updated&labelColor=0d1117&color=155e75) |
| [IP isolation playbook](https://github.com/MUSFIRA-ZAFAR/automated-IP-threat-isolation-playbook/commits) | ![Latest SOAR commit](https://img.shields.io/github/last-commit/MUSFIRA-ZAFAR/automated-IP-threat-isolation-playbook?style=flat&label=Updated&labelColor=0d1117&color=155e75) |

[View my contribution calendar on GitHub](https://github.com/MUSFIRA-ZAFAR) · [Browse all repositories](https://github.com/MUSFIRA-ZAFAR?tab=repositories)

</details>

<a id="connect"></a>

## 🤝 Let's Connect

I'm interested in **blue-team collaboration, detection engineering, cloud investigations, and entry-level security opportunities**.

<p align="center">
<a href="https://www.linkedin.com/in/musfira-zafar/"><img src="https://img.shields.io/static/v1?label=LinkedIn&amp;message=Musfira+Zafar&amp;color=0A66C2&amp;labelColor=0d1117&amp;style=flat" height="28" alt="LinkedIn Musfira Zafar"></a> &nbsp; <a href="https://github.com/MUSFIRA-ZAFAR"><img src="https://img.shields.io/static/v1?label=GitHub&amp;message=Explore+my+work&amp;color=172033&amp;labelColor=0d1117&amp;style=flat&amp;logo=github&amp;logoColor=67e8f9" height="28" alt="GitHub Explore my work"></a>
</p>

<p align="center"><sub>Based in Pakistan · Open to remote opportunities accepting candidates in Pakistan</sub></p>

---

<p align="center"><em>Build the environment. Follow the evidence. Validate the detection. Share the learning.</em></p>
<p align="center"><a href="#about">↑ Back to top</a></p>

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0d1117%2C50%3A12395c%2C100%3A22d3ee&amp;height=100&amp;section=footer" width="100%" alt="Blue and cyan wave footer"></p>
