# 🔓 Penetration Testing Lab Series: Metasploitable2

## 📖 Overview

This repository contains the comprehensive and  final penetration test report for a 20-day hands-on lab series targeting the **Metasploitable2** vulnerable machine. The goal of this project was to develop and demonstrate practical penetration testing skills in a controlled environment—from reconnaissance and exploitation to reporting.

---

## 🎯 Objectives

- Perform comprehensive security assessment of Metasploitable2
- Identify and exploit vulnerabilities across network services and web applications
- Practice manual and automated exploitation techniques
- Document findings in a professional penetration test report
- Develop repeatable methodologies for real-world engagements

---

## 🧰 Tools Used

- **Nmap** – Network scanning & enumeration
- **Metasploit** – Exploitation framework
- **SQLMap** – SQL injection automation
- **BeEF** – Browser Exploitation Framework
- **Burp Suite** – Web proxy and testing
- **John the Ripper** – Password cracking
- **Custom Bash/Python Scripts** – Manual exploitation

---

## 🔍 Key Vulnerabilities Exploited

| Service           | Port  | CVE / Vulnerability Type         | Impact       |
|-------------------|-------|----------------------------------|--------------|
| vsftpd            | 21    | CVE-2011-2523 (Backdoor)         | RCE as Root  |
| Samba             | 445   | CVE-2007-2447 (Usermap Script)   | RCE as Root  |
| UnrealIRCd        | 6667  | CVE-2010-2075 (Backdoor)         | RCE as Root  |
| DistCC            | 3632  | CVE-2004-2687 (Command Injection)| RCE as Root  |
| Java RMI          | 1099  | Deserialization                  | RCE as Root  |
| Apache Tomcat     | 8180  | Authentication Bypass            | WAR Deployment |
| MySQL             | 3306  | Default Credentials              | DB Access    |
| PostgreSQL        | 5432  | Weak Authentication              | DB Access    |
| NFS               | 2049  | no_root_squash Misconfiguration  | Root Access  |

---

## 📑 Final Report Highlights

- **Executive Summary**
- **Methodology** (PTES Alignment)
- **Risk Ratings** (CVSS, DREAD)
- **Detailed Findings** per service
- **Proof-of-Concept Exploitation Steps**
- **Remediation Recommendations**
- **Conclusion & Lessons Learned**

---

## 🧪 Lab Environment

| Role          | System           | IP Address       |
|---------------|------------------|------------------|
| Target        | Metasploitable2  | 192.168.56.101   |
| Attacker      | Parrot Security  | 192.168.56.102   |
| Network       | VirtualBox Host-Only | Isolated        |

---

## 👨‍💻 Author

**CYB3RLEO**  
Penetration Tester & Security Enthusiast  

- 🔗 [LinkedIn](https://linkedin.com/in/cyb3rle0)  
- 🐦 [Twitter](https://twitter.com/_cyb3rleo)  
- 📧 Email: abdulazeezhibullahikolade@gmail.com

---

## 📜 License

This repository is for educational purposes only. Use only in environments you own or have explicit permission to test. Unauthorized use is prohibited.

---

## ⚠️ Disclaimer

All activities documented in this repository were conducted in a controlled lab environment. The author is not responsible for any misuse of this information.

---

## 🙌 Acknowledgments

- **Metasploitable2** team for providing a vulnerable test environment
- **Offensive Security** for inspiration and methodology
- The infosec community for continuous learning and support

---

### 🔎 See the full report here:  
👉 [**Final Penetration Test Report**](/Metasploitable2_Penetration_Test_Report.pdf)
