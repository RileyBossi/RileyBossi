# Hello, I'm Riley Bossi

<a href="https://www.linkedin.com/in/riley-bossi-b08729295">
  <img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

---

I'm a passionate and ambitious **Computer Science student** with a **3.8 GPA**, currently studying at Central Connecticut State University.  
I'm certified in **CompTIA Security+** and **Network+**, and have hands-on experience through personal labs focused on **network security**, **firewall configuration**, and **intrusion detection**.

---

## How I Stay Informed

I actively stay up to date with cybersecurity trends, tools, and threat intelligence by:

- Listening to [**Gerald Auger's Simply Cyber Podcast**](https://www.youtube.com/@SimplyCyber)
- Reading articles on **CSO Online** and other industry blogs
- Participating in **TryHackMe** labs and training pathways

---

## Certifications

-  CompTIA Security+
-  CompTIA Network+
-  CompTIA CySA+ *(studying for August 2025 exam)*
-  Microsoft SC-900: Security, Compliance & Identity Fundamentals
-  Google Cybersecurity Professional Certificate

---

## Projects

### TryHackMe Labs – SOC Training Path

Completed modules from **SOC Level 1** as well as their **SOC Simulator** and actively progressing through **SOC Level 2**, focusing on real-world analyst skills.

#### Key Topics Covered:
- Cyber Defense Frameworks including MITRE frameworks and threat actor mapping
- Cyber Threat Intelligence with **OpenCTI**, **Yara**, and **MISP**
- Endpoit secuirty monitoring with **Sysmon**, **Wazuh**, **Windows Event Logs**
- SIEM fundamentals and log analysis with **Splunk** and **ELK Stack**
- Network forensics with **Wireshark**, **Brim**, and **Snort**
- Malware analysis basics with tools like **Autopsy**
- Phishing prevention with tools like **any.run**, **Messageheader**, **Talos**, **Hybrid Analysis**, and **PhishTool**
#### Hands-On Experience:
- Accessed simulated virtual machines to complete lab exercises and answer security incident questions
- Monitored and analyzed **live alert data** as part of a simulated attack scenario
- Identified and documented critical events such as:
  - PowerShell execution
  - Reverse shell connections
  - Suspicious DNS requests
- Created detailed **case reports** highlighting:
  - Indicators of Compromise (IOCs)
  - Timeline of attacker activity
  - Defensive recommendations
- Investigated phishing scenarios using `.LNK` file masquerading as a PDF:
  - File downloaded PowerShell payload from GitHub
  - Reverse shell established
  - Documented full attack chain and mitigations

---

### At-Home Cybersecurity Lab

A custom-built virtual network lab designed for testing firewall rules, VLANs, and intrusion detection techniques.

#### Objective
To build a hands-on cybersecurity lab environment using **pfSense**, **Kali Linux**, and **Windows VMs** for:
- Firewall configuration
- Network segmentation
- Intrusion detection and response
- Traffic capture and analysis

#### Environment Setup
- Host: **macOS** running **VMware Fusion**
- Network: **Bridged over Wi-Fi**
- VMs:
  - `pfSense`: Configured as firewall, DHCP server, and IDS
  - `Windows 10`: Two VMs simulating endpoint behavior
  - `Kali Linux`: Used for scanning, exploitation, and packet crafting
- Network Layout:
  - LAN: `192.168.2.0/24`
  - WAN: `192.168.1.0/24`
  - VLAN: `192.168.10.0/24`

#### Skills Practiced
- Static IP configuration in **Windows** and **Kali**
- Bridging virtual interfaces over Wi-Fi
- Configuring **VLANs** and routing rules in **pfSense**
- Enabling and tuning **Snort** for packet inspection and alerting
- Capturing and analyzing traffic via:
  - `pfSense`'s built-in capture tool
  - Deep packet inspection in **Wireshark**
- Verifying **ICMP traffic**, troubleshooting DNS, and rule testing
- Installing and configuring **pfBlockerNG** for enhanced firewall and ad-blocking capabilities

### Microsoft Sentinel Log Ingestion Lab
**Tools:** Microsoft Entra ID, Microsoft Sentinel, Azure Logic Apps, Log Analytics, Azure Storage  
**Skills:** SIEM log ingestion, cloud automation, cross-tenant integration, KQL queries

To gain hands-on experience with Microsoft Sentinel, I built a lab simulating real-world log ingestion from a separate Azure tenant.

Since Sentinel was only available in my school's tenant and Microsoft Entra was available in my personal tenant, I developed a solution to bridge the two using native Azure services:

- 📤 Exported **Entra sign-in logs** (.csv) from my personal/test tenant.
- ☁️ Created an **Azure Storage Account** and blob container in my school tenant to host the log file.
- ⚙️ Deployed a **Logic App** that:
  - Runs on a scheduled trigger
  - Reads the uploaded `.csv` from blob storage
  - Sends each log entry to a **custom table** in my Log Analytics workspace
- 🔍 Queried the ingested logs in Microsoft Sentinel using **KQL** for visibility and analysis.
