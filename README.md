# LetsDefend SOC Alert Investigations

This repository contains my documented investigations, analysing various attack vectors from the LetsDefend SOC learning platform (simulating a real SOC environment). I am actively building my foundational SOC skills, and these reports serve as a continuous, practical record of my training in triaging alerts, investigating malicious activity, and producing professional incident documentation.

---

### Endpoint & Malware Investigations
These reports document the triage and analysis of endpoint compromises, malicious executables, LOLBin abuse, and Command & Control (C2) activity.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC104 - Malware Detected (Event 21)](lets_defend/SOC104_Malware-Detected_21_Malware.pdf) | Malware |
| [SOC104 - Malware Detected (Event 31)](lets_defend/SOC104_Malware-Detected_31_Malware.pdf) | Malware |
| [SOC104 - Malware Detected (Event 36)](lets_defend/SOC104_Malware-Detected_36_Malware.pdf) | Malware |
| [SOC104 - Malware Detected (Event 84)](lets_defend/SOC104_Malware-Detected_84_Malware.pdf) | Malware |
| [SOC106 - Found Suspicious File - TI Data](lets_defend/SOC106_Found-Suspicious-File-TI-Data_17_Malware.pdf) | Suspicious File |
| [SOC107 - Privilege Escalation Detected (Event 19)](lets_defend/SOC107_Privilege-Escalation-Detected_19_Malware.pdf) | Privilege Escalation |
| [SOC107 - Privilege Escalation Detected (Event 48)](lets_defend/SOC107_Privilege-Escalation-Detected_48_Malware.pdf) | Privilege Escalation |
| [SOC108 - Malicious Remote Access Software Detected](lets_defend/SOC108_Malicious-Remote-Access-Software-Detected_38_Malware.pdf) | Remote Access |
| [SOC109 - Emotet Malware Detected (Event 39)](lets_defend/SOC109_Emotet-Malware-Detected_39_Malware.pdf) | Malware / Trojan |
| [SOC109 - Emotet Malware Detected (Event 85)](lets_defend/SOC109_Emotet-Malware-Detected_85_Malware.pdf) | Malware / Trojan |
| [SOC113 - Suspicious hh.exe Usage](lets_defend/SOC113_Suspicious-hh.exe-Usage_44_Malware.pdf) | LOLBin |
| [SOC115 - Wscript.exe Usage as Dropper](lets_defend/SOC115_Wscript.exe-Usage-as-Dropper_47_Malware.pdf) | Dropper |
| [SOC116 - DNS Hijacking Detected](lets_defend/SOC116_DNS-Hijacking-Detected_49_Malware.pdf) | DNS Hijacking |
| [SOC117 - Suspicious .reg File](lets_defend/SOC117_Suspicious-.reg-File_50_Malware.pdf) | Persistence |
| [SOC118 - Internal Port Scan Activity](lets_defend/SOC118_Internal-Port-Scan-Activity_51_Malware.pdf) | Network Scan |
| [SOC124 - Scheduled Task Created](lets_defend/SOC124_Scheduled-Task-Created_57_Malware.pdf) | Persistence |
| [SOC125 - Suspicious Rundll32 Activity](lets_defend/SOC125_Suspicious-Rundll32-Activity_58_Malware.pdf) | LOLBin |
| [SOC126 - Suspicious New Autorun Value Detected](lets_defend/SOC126_Suspicious-New-Autorun-Value-Detected_61_Malware.pdf) | Persistence |
| [SOC128 - Malicious File Upload Attempt](lets_defend/SOC128_Malicious-File-Upload-Attempt_62_Malware.pdf) | Malicious File Upload |
| [SOC130 - Event Log Cleared](lets_defend/SOC130_Event-Log-Cleared_64_Malware.pdf) | Defence Evasion |
| [SOC131 - Reverse TCP Backdoor Detected](lets_defend/SOC131_Reverse-TCP-Backdoor-Detected_67_Malware.pdf) | C2 / Backdoor |
| [SOC132 - Same Malicious File Found on Multiple Sources](lets_defend/SOC132_Same-Malicious-File-Found-on-Multiple-Sources_68_Malware.pdf) | Malware / Spread |
| [SOC134 - Suspicious WMI Activity (Event 71)](lets_defend/SOC134_Suspicious-WMI-Activity_71_Malware.pdf) | Ransomware / WMI |
| [SOC134 - Suspicious WMI Activity (Event 81)](lets_defend/SOC134_Suspicious-WMI-Activity_81_Malware.pdf) | Ransomware / WMI |
| [SOC137 - Malicious File or Script Download Attempt](lets_defend/SOC137_Malicious-File-or-Script-Download-Attempt_76_Malware.pdf) | Malicious Script |
| [SOC139 - Meterpreter or Empire Activity](lets_defend/SOC139_Meterpreter-or-Empire-Activity_78_Malware.pdf) | C2 / Cobalt Strike |
| [SOC144 - New Scheduled Task Created](lets_defend/SOC144_New-scheduled-task-created_91_Malware.pdf) | Persistence |
| [SOC145 - Ransomware Detected](lets_defend/SOC145_Ransomware-Detected_92_Malware.pdf) | Ransomware |
| [SOC147 - SSH Scan Activity](lets_defend/SOC147_SSH-Scan-Activity_94_Malware.pdf) | Network Scan / Recon |
| [SOC153 - Suspicious Powershell Script Executed (Event 101)](lets_defend/SOC153_Suspicious-Powershell-Script-Executed_101_Malware.pdf) | PowerShell |
| [SOC153 - Suspicious Powershell Script Executed (Event 238)](lets_defend/SOC153_Suspicious-Powershell-Script-Executed_238_Malware.pdf) | PowerShell |
| [SOC163 - Suspicious Certutil.exe Usage](lets_defend/SOC163_Suspicious-Certutil.exe-Usage_113_LOLBin.pdf) | LOLBin |
| [SOC164 - Suspicious Mshta Behavior](lets_defend/SOC164_Suspicious-Mshta-Behavior_114_LOLBin.pdf) | LOLBin |
| [SOC173 - Follina 0-Day Detected](lets_defend/SOC173_Follina-0-Day-Detected_123_Malware.pdf) | Zero-Day Exploit |
| [SOC189 - VBScript Suspicious Behavior Detected](lets_defend/SOC189_VBScript-Suspicious-Behavior-Detected_139_Malware.pdf) | Malicious Script |
| [SOC205 - Malicious Macro has been executed](lets_defend/SOC205_Malicious-Macro-has-been-executed_231_Malware.pdf) | Malicious Macro |
| [SOC211 - Utilman.exe Winlogon Exploit Attempt](lets_defend/SOC211_Utilman.exe-Winlogon-Exploit-Attempt_161_LOLBin.pdf) | Privilege Escalation |
| [SOC289 - Suspicious Invoke-WebRequest Execution With DirectIP](lets_defend/SOC289_Suspicious-Invoke-WebRequest-Execution-With-DirectIP_265_Malware.pdf) | PowerShell / Download |
| [SOC336 - Windows OLE Zero-Click RCE Exploitation Detected (CVE-2025-21298)](lets_defend/SOC336_Windows-OLE-Zero-Click-RCE-Exploitation-Detected-(CVE-2025-21298)_314_Malware.pdf) | Zero-Click / CVE |

---

### Web Application Investigations
These reports document the analysis of web server traffic, HTTP requests, and common web-based attack vectors.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC127 - SQL Injection Detected](lets_defend/SOC127_SQL-Injection-Detected_235_Web-Attack.pdf) | SQL Injection |
| [SOC165 - Possible SQL Injection Payload Detected](lets_defend/SOC165_Possible-SQL-Injection-Payload-Detected_115_Web-Attack.pdf) | SQL Injection |
| [SOC166 - Javascript Code Detected in Requested URL](lets_defend/SOC166_Javascript-Code-Detected-in-Requested-URL_116_Web-Attack.pdf) | Cross-Site Scripting (XSS) |
| [SOC167 - LS Command Detected in Requested URL](lets_defend/SOC167_LS-Command-Detected-in-Requested-URL_117_Web-Attack.pdf) | Command Injection |
| [SOC168 - Whoami Command Detected in Request Body](lets_defend/SOC168_Whoami-Command-Detected-in-Request-Body_118_Web_Attack.pdf) | Command Injection |
| [SOC169 - Possible IDOR Attack Detected](lets_defend/SOC169_Possible-IDOR-Attack-Detected_Event-119_Web-Attack.pdf) | IDOR |
| [SOC175 - PowerShell Found in Requested URL (Possible CVE-2022-41082)](lets_defend/SOC175_PowerShell-Found-in-Requested-URL-Possible-CVE-2022-41082-Exploitation_125_Web-Attack.pdf) | RCE / Web Exploit |
| [SOC227 - Microsoft SharePoint Server Elevation of Privilege (CVE-2023-29357)](lets_defend/SOC227_Microsoft-SharePoint-Server-Elevation-of-Privilege-Possible-CVE-2023-29357-Exploitation_189_Web-Attack.pdf) | Web Exploit / CVE |
| [SOC235 - Atlassian Confluence Broken Access Control 0-Day (CVE-2023-22515)](lets_defend/SOC235_Atlassian-Confluence-Broken-Access-Control-0-Day-CVE-2023-22515_197_Web-Attack.pdf) | Zero-Day Exploit |
| [SOC246 - Forced Authentication Detected](lets_defend/SOC246_Forced-Authentication-Detected_208_Web-Attack.pdf) | Brute Force |
| [SOC274 - Palo Alto Networks PAN-OS Command Injection Vulnerability Exploitation (CVE-2024-3400)](lets_defend/SOC274_Palo-Alto-Networks-PAN-OS-Command-Injection-Vulnerability-Exploitation-(CVE-2024-3400)_249_Web-Attack.pdf) | Command Injection / CVE |
| [SOC287 - Arbitrary File Read on Checkpoint Security Gateway (CVE-2024-24919)](lets_defend/SOC287_Arbitrary-File-Read-on-Checkpoint-Security-Gateway_[CVE-2024-24919]_263_Web-Attack.pdf) | Arbitrary File Read |
| [SOC325 - Unauthorized Cloud Region Access Attempt Detected](lets_defend/SOC325_Unauthorized-Cloud-Region-Access-Attempt-Detected_303_Web-Attack.pdf) | Brute Force / Defence Evasion |
| [SOC342 - CVE-2025-53770 SharePoint ToolShell Auth Bypass and RCE](lets_defend/SOC342_CVE‑2025‑53770_SharePoint-ToolShell-Auth-Bypass-and-RCE_320_Web-Attack.pdf) | Auth Bypass / RCE |

---

### Email Security & Phishing Investigations
These reports cover the analysis of malicious emails, attachments, and social engineering campaigns targeting end users.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC146 - Phishing Mail Detected - Excel 4.0 Macros](lets_defend/SOC146_Phishing-Mail-Detected-Excel-4.0-Macros_93_Exchange.docx.pdf) | Phishing / Malicious Attachment |
| [SOC251 - Quishing Detected (QR Code Phishing)](lets_defend/SOC251_Quishing-Detected-(QR-Code-Phishing)_214_Exchange.pdf) | Quishing / Social Engineering |

---

### Identity & Access Investigations
These reports focus on attempts to compromise authentication mechanisms and bypass perimeter defences.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC176 - RDP Brute Force Detected](lets_defend/SOC176_RDP-Brute-Force-Detected_234_Brute-Force.pdf) | Brute Force |
| [SOC210 - Possible Brute Force Detected on VPN](lets_defend/SOC210_Possible-Brute-Force-Detected-on-VPN_162_Brute-Force.pdf) | Brute Force |

---

### Data Leakage & Insider Threats
These reports detail investigations into unauthorised data exfiltration and tools designed to harvest sensitive information.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC202 - FakeGPT Malicious Chrome Extension](lets_defend/SOC202_FakeGPT-Malicious-Chrome-Extension_153_Data-Leakage.pdf) | Data Leakage / Browser Extension |
| [SOC250 - APT35 HyperScrape Data Exfiltration Tool Detected](lets_defend/SOC250_APT35-HyperScrape-Data-Exfiltration-Tool-Detected_212_Data-Leakage.pdf) | Data Exfiltration / APT |
| [SOC338 - Lumma Stealer DLL Side-Loading via Click-Fix Phishing](lets_defend/SOC338_Lumma-Stealer-DLL-Side-Loading-via-Click-Fix-Phishing_316_Data-Leakage.pdf) | Info Stealer / Phishing |

---

### Threat Intelligence & OSINT
These investigations rely heavily on cross-referencing external telemetry and open-source intelligence to identify broader attack infrastructure.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC105 - Requested T.I. URL address](lets_defend/SOC105_Requested-T.I.-URL-address_75_ThreatIntel.docx.pdf) | Threat Intelligence |
| [SOC326 - Impersonating Domain MX Record Change Detected](lets_defend/SOC326_Impersonating-Domain-MX-Record-Change-Detected_304_ThreatIntel.pdf) | Threat Intelligence / DNS |
