# Task 3: Basic Vulnerability Scan on Your PC

## 🔧 Tools Used

- **Nessus Essentials (Free)**
  - Installed on Windows 11

## 🖥️ Target

- **Local Machine IP**: 192.168.1.103

## 📋 Steps Performed

1. **Installation**
   - Registered for Nessus Essentials using email and received the activation code.
   - Installed Nessus on my Windows machine.
   - Accessed the interface at `https://localhost:8834`.

2. **Scan Setup**
   - Created a new scan under the "Advanced Scan" option.
   - Named the scan "Task" and added the local IP: `192.168.1.103` as the target.

3. **Scan Execution**
   - Launched the scan.
   - The scan ran for about 20 minutes and completed successfully.

4. **Result Review**
   - Found a total of **27 vulnerabilities**:
     - **Medium**: 1
     - **Info/Mixed**: 26
   - Key issues included:
     - SMB Signing not required
     - SSL Certificate cannot be trusted
     - TLS and HTTP multiple issues

5. **Reporting**
   - Exported scan results.
   - Took screenshots:
     - Scan configuration with target IP
     - List of vulnerabilities
     - Detailed view of one vulnerability (SSL Certificate issue)

## 📂 Repository Structure

```
cybersecurity-task-3-vulnerability-scan/
│
├── README.md             # This file
├── vulnerability_report.md
└── screenshots/
    ├── scan_setup.png
    ├── vulnerabilities_list.png
    ├── ssl_certificate_issue.png
```

## 📄 Files Included

- `vulnerability_report.md`: Detailed summary of key findings.
- `screenshots/`: Contains the captured evidence from the scan process.

## ✅ Outcome

- Gained hands-on experience with running a real vulnerability scan.
- Learned to identify and understand common issues like SSL and SMB-related risks.
- Got a practical understanding of CVSS scores and their impact.
