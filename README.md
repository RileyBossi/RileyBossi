# Hello, I'm Riley Bossi

<a href="https://www.linkedin.com/in/riley-bossi-b08729295">
  <img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

---

I'm a passionate and ambitious **Computer Science student** at Central Connecticut State University. I hold **CompTIA CYSA+, Security+,** and **Network+** certifications and have hands-on experience gained both on the job and through personal labs focused on **network security**, **firewall configuration**, and **intrusion detection**.

---

## My Current Role - IT Support Technician
I currently work as an IT Support Technician at a Managed Service Provider (MSP), supporting multiple client environments with a focus on security operations, monitoring, zero trust, and traditional Level 1 and Level 2 help desk responsibilities.

This role allows me to apply SOC concepts in real production environments while supporting day-to-day IT operations across diverse networks.

### Security Responsibilites
- Investigate phishing emails by analyzing indicators of compromise and detonating attachments and URLs in sandbox environments. 
- Create and maintain custom allow/deny policies with ringfencing and setting up detection rules in ThreatLocker to enforce application control and reduce the attack surface; leverage Unified Audit to identify anomalies and suspicious activity. 
- Investigate security alerts through an MSSP provided SIEM, including endpoint activity, authentication anomolies, and suspicious process execution.
- Using PowerShell via the RMM to query and analyze Windows Event Logs, investigate login failures, and validate alerts.

### IAM Responsibilites
- Managing users and security settings across the Microsoft Admin and Google Workspace ecosystem.
- Onboarding and offboarding users securely.
- Ensuring Zero Trust through least privilege, verify explicitly, and assume beach.
- Improving tenant security posture by reviewing and increasing Microsoft Secure Score, enforcing MFA and security defaults, and addressing risky behaviour.

### IT Operations
- Providing Tier 1-2 IT support across multiple client enviorments.
- Troubleshoot and resolve workstation, printer, DNS, and Network issues.
- Configuring and maintaining firewall rules, ThreatLocker Application Control, and network devices.
- Supporting patch management procedures.
- Documenting incidents, fixes, and configurations clearly for tracking and to prevent similar issues in the future. 

---

## How I Stay Informed

I actively stay up to date with cybersecurity trends, tools, and threat intelligence by:

- Listening to [**Gerald Auger's Simply Cyber Podcast**](https://www.youtube.com/@SimplyCyber)
- Reading articles on **CSO Online** and other industry blogs
- Participating in **TryHackMe** labs and training pathways
- Reading DFIR Reports

 ### Lessons Learned

Staying informed isn’t just about consuming information—it’s about applying it to sharpen your mindset as a defender. Here are some key takeaways I’ve gained from my continuous learning:
<br><br>
- **Security is about fundamentals, not magic tools** <br>
Reading through DFIR Reports showed me that most breaches don’t involve zero-days, they succeed due to poor hygiene like weak credentials, unpatched systems, and excessive privileges. Solid security practices often matter more than expensive tools.<br>
- **There is no silver bullet to stop infiltration** <br>
Even advanced environments get compromised. Whether it’s phishing via .LNK files or living-off-the-land attacks, attackers often take advantage of legitimate tools. What matters is visibility, response readiness, and limiting the blast radius.<br>
- **Logs tell a story—context makes it actionable** <br>
Working with Sentinel, ELK, and Splunk taught me that raw alerts mean little without understanding why they happened. Correlating login anomalies, PowerShell execution, or DNS tunneling attempts helps uncover real threats hiding in noise. <br>
- **Threat actor behavior is more important than malware signatures** <br>
Following MITRE ATT&CK and hands-on labs in TryHackMe has helped me focus on TTPs (Tactics, Techniques, and Procedures) rather than just IOCs. This mindset helps in catching novel or evolving threat. <br>
- **Staying updated is a discipline, not a task** <br>
Whether it’s podcast discussions, new malware analysis reports, or fresh CVEs, I treat staying informed as part of my cybersecurity hygiene—just like patching a system or reviewing firewall rules.

---

## Certifications

-  CompTIA Security+
-  CompTIA Network+
-  CompTIA CySA+
-  Microsoft SC-900: Security, Compliance & Identity Fundamentals
-  Google Cybersecurity Professional Certificate

---

## Projects

### TryHackMe Labs – SOC Training Path

Completed modules from **SOC Level 1** and **SOC Level 2** as well as their **SOC Simulator**, focusing on real-world analyst skills.

#### Key Topics Covered:
- SOC operations including alert triage, escalation, and incident response workflows
- Cyber defense frameworks with **MITRE ATT&CK** and threat actor behavior mapping
- Cyber Threat Intelligence with **OpenCTI**, **Yara**, and **MISP**
- Endpoit secuirty monitoring with **Sysmon**, **Wazuh**, **Windows Event Logs**
- SIEM and log correlation using **Splunk** and the **ELK Stack**
- Network forensics with **Wireshark**, **Brim**, and **Snort**
- Malware analysis fundamentals including PE header analysis, static analysis and dynamic analysis.
- Detection of living-off-the-land techniques, persistence, and lateral movement
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
**Skills:** SIEM log ingestion, KQL queries, identity and access management, MFA configuration, Conditional Access, cross-tenant automation
#### Objectives
To gain hands-on experience with Microsoft Sentinel and Microsoft Entra ID, I created a lab that simulates log ingestion and analysis from a separate Azure tenant. Since Sentinel was only available in my **school tenant**, and full admin access to Microsoft Entra was available in my **personal test tenant**, I set up both environments independently and bridged them using Azure-native services.
#### Enviorment Setup And Skills Practiced
In my **Microsoft Entra ID test tenant**, I built a realistic identity environment by:
- Creating multiple test users with various roles (e.g., Global Reader, User Administrator)
- Organizing users into security groups such as Finance, IT, Sales, and HR.
- Enabling MFA for selected users through both per-user settings and Conditional Access policies
- Creating and applying **Conditional Access policies** that:
  - Enforce MFA when logging in from outside the U.S.
  - Block access from legacy authentication clients
- Enabling **Identity Protection features**, including user risk and sign-in risk policies
- Simulating sign-ins, risky behavior, and policy triggers to generate activity in Entra audit and sign-in logs

Since I couldn’t connect Microsoft Sentinel directly to a different tenant, I used the following method to ingest the logs:

- Exported **Microsoft Entra sign-in logs** as `.csv` from the test tenant
- Created an **Azure Storage Account** and private **blob container** in the school tenant
- Uploaded the log file to blob storage
- Deployed a **Logic App** that:
  - Runs on a scheduled trigger
  - Reads and parses the `.csv` from blob storage
  - Sends each log entry to a **custom Log Analytics table** (`EntraLog_CL`) linked to Microsoft Sentinel


 ---

 ### JavaScript Project

 **Amazon Project Link:** <a href="https://rileybossi.github.io/amazon-project/javascript-amazon-project-main/amazon.html">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon Project" height="30"/>
</a><br>
 

[**JavaScript Tutorial That I Followed**](https://www.youtube.com/watch?v=EerdGm-ehJQ&t=1s) 

 #### Objective

To expand my programming foundation beyond Java, Python, SQL, Assembly Language, HTML, and CSS by learning JavaScript. I found this important because JavaScript is a critical language for understanding web application security. This project was designed to deepen my knowledge of client-side code execution, data handling, and the attack surface present in modern web applications.

#### Project Overview
Amazon Clone Project

- Built a functional e-commerce application featuring:
- Dynamic product catalog with real-time cart management
- Interactive UI with event-driven programming
- Local storage implementation for cart persistence
- Order processing and checkout workflow
- Responsive design across multiple pages
- Work with git tools
- Work with API's

#### Security-Focused Takeaways
While building this project, I gained valuable insights into web application security: 
- <b>Client-Side Attack Surface </b><br> Understanding how JavaScript executes in the browser helped me recognize common vulnerabilities like DOM-based XSS, where unsanitized user input can manipulate page behavior.
- <b>Data Handling and Storage </b><br> Implementing local storage for cart data illustrated the security implications of client-side data persistence, including the risks of storing sensitive information in the browser.
- <b>Input Validation Importance</b> <br> Working with user interactions (product selection, quantity inputs, form submissions) reinforced the need for proper input validation and the dangers of trusting client-side controls.<br>
- <b>Code Obfuscation and Reverse Engineering </b><br> Building the application from scratch gave me insight into how attackers might analyze JavaScript code to identify business logic flaws or API endpoints.

#### Skills Developed
- JavaScript fundamentals including functions, objects, classes, and arrays
- DOM manipulation and event handling for dynamic user interfaces
Asynchronous JavaScript concepts relevant to API security
- Understanding of how modern web applications handle state and user data
- Foundation for identifying client-side vulnerabilities during security assessments

This project bridges my backend scripting experience with frontend development, providing a more complete picture of web application architecture—essential knowledge for conducting thorough security assessments and understanding the full attack chain in web-based threats.

