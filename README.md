# SOC Alert Investigations

This repository contains my documented incident response investigations, analysing various attack vectors using SIEM, EDR, and OSINT telemetry. I am actively building my foundational SOC skills, and these reports serve as a continuous, practical record of my training in triaging alerts, investigating malicious activity, and producing professional incident documentation.

### LetsDefend Endpoint & Malware Investigations
These reports document the triage and analysis of endpoint compromises, malicious executables, and Command & Control (C2) activity on the LetsDefend SOC Training Platform.

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
| [SOC130 - Event Log Cleared](lets_defend/SOC130_Event-Log-Cleared_64_Malware.pdf) | Defense Evasion |
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
| [SOC173 - Follina 0-Day Detected](lets_defend/SOC173_Follina-0-Day-Detected_123_Malware.pdf) | Zero-Day Exploit |
| [SOC189 - VBScript Suspicious Behavior Detected](lets_defend/SOC189_VBScript-Suspicious-Behavior-Detected_139_Malware.pdf) | Malicious Script |
| [SOC205 - Malicious Macro has been executed](lets_defend/SOC205_Malicious-Macro-has-been-executed_231_Malware.pdf) | Malicious Macro |
| [SOC289 - Suspicious Invoke-WebRequest Execution With DirectIP](lets_defend/SOC289_Suspicious-Invoke-WebRequest-Execution-With-DirectIP_265_Malware.pdf) | PowerShell / Download |
| [SOC336 - Windows OLE Zero-Click RCE Exploitation Detected](lets_defend/SOC336_Windows-OLE-Zero-Click-RCE-Exploitation-Detected-(CVE-2025-21298)_314_Malware.pdf) | Zero-Click / CVE |

---

### LetsDefend Web Application Investigations
These reports document the analysis of web server traffic, HTTP requests, and common web-based attack vectors on LetsDefend.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC127 - SQL Injection Detected](lets_defend/SOC127_SQL-Injection-Detected_235_Web-Attack.pdf) | SQL Injection |
| [SOC165 - Possible SQL Injection Payload Detected](lets_defend/SOC165_Possible-SQL-Injection-Payload-Detected_115_Web-Attack.pdf) | SQL Injection |
| [SOC166 - Javascript Code Detected in Requested URL](lets_defend/SOC166_Javascript-Code-Detected-in-Requested-URL_116_Web-Attack.pdf) | Cross-Site Scripting (XSS) |
| [SOC167 - LS Command Detected in Requested URL](lets_defend/SOC167_LS-Command-Detected-in-Requested-URL_117_Web-Attack.pdf) | Command Injection |
| [SOC168 - Whoami Command Detected in Request Body](lets_defend/SOC168_Whoami-Command-Detected-in-Request-Body_118_Web_Attack.pdf) | Command Injection |
| [SOC169 - Possible IDOR Attack Detected](lets_defend/SOC169_Possible-IDOR-Attack-Detected_Event-119_Web-Attack.pdf) | IDOR |
| [SOC175 - PowerShell Found in Requested URL (Possible CVE-2022-41082)](lets_defend/SOC175_PowerShell-Found-in-Requested-URL-Possible-CVE-2022-41082-Exploitation_125_Web-Attack.pdf) | RCE / Web Exploit |
| [SOC235 - Atlassian Confluence Broken Access Control 0-Day (CVE-2023-22515)](lets_defend/SOC235_Atlassian-Confluence-Broken-Access-Control-0-Day-CVE-2023-22515_197_Web-Attack.pdf) | Zero-Day Exploit / Web Attack |
| [SOC246 - Forced Authentication Detected](lets_defend/SOC246_Forced-Authentication-Detected_208_Web-Attack.pdf) | Brute Force |
| [SOC274 - Palo Alto Networks PAN-OS Command Injection Vulnerability Exploitation (CVE-2024-3400)](lets_defend/SOC274_Palo-Alto-Networks-PAN-OS-Command-Injection-Vulnerability-Exploitation-(CVE-2024-3400)_249_Web-Attack.pdf) | Command Injection / Web Exploit |
| [SOC287 - Arbitrary File Read on Checkpoint Security Gateway (CVE-2024-24919)](lets_defend/SOC287_Arbitrary-File-Read-on-Checkpoint-Security-Gateway_[CVE-2024-24919]_263_Web-Attack.pdf) | Arbitrary File Read |
| [SOC325 - Unauthorized Cloud Region Access Attempt Detected](lets_defend/SOC325_Unauthorized-Cloud-Region-Access-Attempt-Detected_303_Web-Attack.pdf) | Brute Force / Defence Evasion |
| [SOC342 - CVE-2025-53770 SharePoint ToolShell Auth Bypass and RCE](lets_defend/SOC342_CVE‑2025‑53770_SharePoint-ToolShell-Auth-Bypass-and-RCE_320_Web-Attack.pdf) | Auth Bypass / RCE |
