# Kyunghwan Byun (변경환) 🛡️

**Offensive Security Researcher** | Web & API Security · Distributed Systems · Bug Bounty  
*Undergraduate Researcher, Korea University (School of Smart Security)*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/kyunghwan-byun)
[![Email](https://img.shields.io/badge/Email-byunkh02@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:byunkh02@gmail.com)

---

## 🔍 About Me
I am an undergraduate security researcher at **Korea University (School of Smart Security)** specializing in **Web & API access control flaws (BFLA, BOLA/IDOR)**, distributed middleware vulnerabilities, and offensive security automation. 

I focus on manual business logic auditing combined with custom automated test harnesses to uncover high-impact vulnerabilities in production ecosystems.

---

## 🎯 Verified Security Research & CVE Disclosures

### 🚗 Robotics & Autonomous Systems Middleware
- **Fast-DDS (eProsima)** — Widely used DDS middleware in ROS 2 and autonomous driving stacks:
  - **`CVE-2026-45097`**: Critical CDR deserialization vulnerability causing Out-Of-Memory (OOM) and immediate process termination (`SIGKILL`).
  - **`CVE-2026-63340`**: RTPS malformed submessage parsing vulnerability leading to remote Denial of Service (DoS).
  - *Responsible disclosure with upstream maintainers, developed functional C++ PoCs demonstrating unauthenticated default impact.*

### 🌐 Web & API Bug Bounty
- **Qwant (YesWeHack, `#YWH-PGM16-705`)**: Accepted report on Server-Side Rendering (SSR) sensitive data exposure flaw in major European search engine.
- **Active Platforms**: KYC-verified researcher on **YesWeHack**, active on **Bugcrowd**, **HackerOne**, and authorized private programs on **FindTheGap** (GS Retail, Busan Bank).

### ⛓️ Distributed & Smart Contract Security
- **`CVE-2026-39171`** & **`CVE-2026-39172`**: Disclosed logic and asset locking vulnerabilities in cross-chain / proxy contracts.

---

## 🛠️ Featured Security Repositories

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| [**FaultLoom**](https://github.com/Koreahwan/FaultLoom) | Authorization-first security research harness designed for automated testing of complex access control boundaries. | Python, Burp Suite |
| [**api-security-review-sample**](https://github.com/Koreahwan/api-security-review-sample) | Real-world API access control audit sample (OWASP crAPI) showcasing manual verification, scoping, and remediation. | Markdown, Postman, API Specs |
| [**wraith-mcp**](https://github.com/Koreahwan/wraith-mcp) | AI-native stealth browser Model Context Protocol (MCP) server for automated offensive reconnaissance. | Python, Patchright |

---

## 🧰 Technical Competencies
- **Vulnerability Assessment**: Web & API Security, BFLA / IDOR, SSRF, Deserialization Flaws, DoS Analysis
- **Security Tooling**: Burp Suite (Custom Extensions), Agentic-Bug-Hunter, Frida, Ghidra, Wireshark, Docker
- **Languages**: Python, C / C++, Go, JavaScript / Node.js, Solidity
