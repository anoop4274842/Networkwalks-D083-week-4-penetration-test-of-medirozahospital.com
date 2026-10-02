# Networkwalks-D083-week-4-penetration-test-of-medirozahospital.com
# W Penetration Testing – Mediroza Hospital

This project documents a web application penetration testing assessment conducted as an external, unauthenticated black-box security assessment. The assessment focused on identifying vulnerabilities related to authentication, authorization, sensitive information exposure, PDF security, and publicly exposed web resources.

🎯 **Objectives**

* Perform web application reconnaissance
* Identify exposed services and technologies
* Test authentication mechanisms
* Identify authorization and access-control weaknesses
* Assess web application vulnerabilities
* Test the security of protected PDF documents
* Identify sensitive information exposure
* Analyze security risks and their potential impact
* Document findings and remediation recommendations

🧰 **Lab Environment**

| Component         | Configuration                                                            |
| ----------------- | ------------------------------------------------------------------------ |
| Target            | Mediroza Hospital Web Application                                        |
| Domain            | medirozahospital.com                                                     |
| Assessment Type   | External, Unauthenticated Black-Box                                      |
| Methodology       | OWASP Testing Guide v4.2                                                 |
| Assessment Phases | Reconnaissance → Scanning → Exploitation → Post-Exploitation → Reporting |

🛠️ **Tools & Purpose**

| Tool     | Purpose                             |
| -------- | ----------------------------------- |
| WHOIS    | Domain registration information     |
| Nslookup | DNS resolution                      |
| HTTPX    | HTTP/service fingerprinting         |
| Gobuster | Directory enumeration               |
| Nmap     | Port scanning and service detection |
| Browser  | Web application testing             |
| Hashcat  | Password security testing           |
| pdfcrack | PDF password recovery               |

⚙️ **Penetration Testing Activities**

**Reconnaissance & Enumeration**
Information about the target domain, services, technologies, and publicly exposed resources was collected.

**Technology & Service Identification**
HTTP services and exposed technologies were identified using fingerprinting and network-scanning techniques.

**Directory Enumeration**
Web directories and accessible paths were tested to identify potentially exposed resources.

**Authentication Testing**
The patient portal authentication mechanism was assessed for weaknesses.

**Authorization Testing**
Access controls surrounding patient laboratory reports were evaluated to determine whether users could access resources belonging to other accounts.

**PDF Security Testing**
Protected laboratory-report PDFs were assessed to evaluate the strength of their password protection.

📊 **Key Findings**

* **F-01 – SQL Injection / Authentication Bypass** — Critical, CVSS 9.8
* **F-02 – Broken Access Control / Unauthorized Patient Lab Report Access** — Critical, CVSS 9.1
* **F-03 – Weak PDF Encryption Passwords** — High, CVSS 7.5
* **F-04 – Sensitive Data / PHI Exposure** — Critical, CVSS 9.1
* **F-05 – Excessive Service Exposure** — Medium, CVSS 5.3
* **F-06 – Directory / Path Information Disclosure** — Low, CVSS 3.7

📚 **Learning Outcomes**

* Understanding the web application penetration testing lifecycle
* Practicing reconnaissance and service enumeration
* Learning authentication and authorization testing
* Understanding SQL injection vulnerabilities
* Learning about broken access control and IDOR
* Practicing PDF password-security testing
* Understanding sensitive-data exposure risks
* Learning vulnerability severity and CVSS classification
* Improving penetration-testing documentation and reporting skills

👤 **Author**

**Anoop Gangadharan**

Cybersecurity Learner | Offensive Security & VAPT

📌 **Project Status**

**Status: Completed – week 4 Penetration Testing Project**


