# SOC Alert Investigations

This repository contains my documented incident response investigations, analysing various attack vectors using SIEM, EDR, and OSINT telemetry. I am actively building my foundational SOC skills, and these reports serve as a continuous, practical record of my training in triaging alerts, investigating malicious activity, and producing professional incident documentation.

### Endpoint & Malware Investigations
These reports document the triage and analysis of endpoint compromises, malicious executables, and Command & Control (C2) activity.

| Alert & Investigation | Attack Category |
| :--- | :--- |
| [SOC104 - Malware Detected](lets_defend/SOC104_Malware-Detected_84_Malware.pdf) | Malware |
| [SOC109 - Emotet Malware Detected](lets_defend/SOC109_Emotet-Malware-Detected_85_Malware.pdf) | Malware / Trojan |
| [SOC131 - Reverse TCP Backdoor Detected](lets_defend/SOC131_Reverse-TCP-Backdoor-Detected_67_Malware.pdf) | C2 / Backdoor |
| [SOC132 - Same Malicious File Found on Multiple Sources](lets_defend/SOC132_Same-Malicious-File-Found-on-Multiple-Sources_68_Malware.pdf) | Malware / Spread |
| [SOC134 - Suspicious WMI Activity (Event 71)](lets_defend/SOC134_Suspicious-WMI-Activity_71_Malware.pdf) | Ransomware / WMI |
| [SOC134 - Suspicious WMI Activity (Event 81)](lets_defend/SOC134_Suspicious-WMI-Activity_81_Malware.pdf) | Ransomware / WMI |
| [SOC137 - Malicious File or Script Download Attempt](lets_defend/SOC137_Malicious-File-or-Script-Download-Attempt_76_Malware.pdf) | Malicious Script |
| [SOC139 - Meterpreter or Empire Activity](lets_defend/SOC139_Meterpreter-or-Empire-Activity_78_Malware.pdf) | C2 / Cobalt Strike |
| [SOC144 - New Scheduled Task Created](lets_defend/SOC144_New-scheduled-task-created_91_Malware.pdf) | Persistence |
| [SOC145 - Ransomware Detected](lets_defend/SOC145_Ransomware-Detected_92_Malware.pdf) | Ransomware |
| [SOC147 - SSH Scan Activity](lets_defend/SOC147_SSH-Scan-Activity_94_Malware.pdf) | Network Scan / Recon |
| [SOC153 - Suspicious Powershell Script Executed](lets_defend/SOC153_Suspicious-Powershell-Script-Executed_238_Malware.pdf) | PowerShell |
| [SOC173 - Follina 0-Day Detected](lets_defend/SOC173_Follina-0-Day-Detected_123_Malware.pdf) | Zero-Day Exploit |
| [SOC205 - Malicious Macro has been executed](lets_defend/SOC205_Malicious-Macro-has-been-executed_231_Malware.pdf) | Malicious Macro |
| [SOC289 - Suspicious Invoke-WebRequest Execution With DirectIP](lets_defend/SOC289_Suspicious-Invoke-WebRequest-Execution-With-DirectIP_265_Malware.pdf) | PowerShell / Download |
| [SOC336 - Windows OLE Zero-Click RCE Exploitation Detected](lets_defend/SOC336_Windows-OLE-Zero-Click-RCE-Exploitation-Detected-(CVE-2025-21298)_314_Malware.pdf) | Zero-Click / CVE |

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
