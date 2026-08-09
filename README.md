# TryHackMe: OWASP Top 10 (2025) – Write-ups & Walkthroughs

Welcome to the central repository for **CYber_Task-3**. This repository contains detailed write-ups, vulnerability analyses, and step-by-step walkthroughs for various security tasks in the **TryHackMe: OWASP Top 10 (2025)** room.

---

## 📌 Repository Structure

| Folder Directory | Primary Focus / Topic | Documentation |
| :--- | :--- | :--- |
| `📁 Cryptographic_Failures/` | Sensitive data exposure, hardcoded secrets, weak ciphers | [View Readme](./Cryptographic_Failures/README.md) |
| `📁 Insecure_Design/` | Missing threat modeling, unauthenticated REST APIs | [View Readme](./Insecure_Design/README.md) |
| `📁 Security_Misconfiguration/` | Default credentials, open ports, default settings | [View Readme](./Security_Misconfiguration/README.md) |
| `📁 Software_Supply_Chain_Failures/` | Vulnerable third-party dependencies & supply chain risks | [View Readme](./Software_Supply_Chain_Failures/README.md) |

---

## 📁 Tasks Summary Matrix

| OWASP Category | Target App | Core Vulnerability | Key Tools Used | Status |
| :--- | :--- | :--- | :--- | :---: |
| **AS04: Cryptographic Failures** | Secure Document Viewer | Hardcoded client secrets & weak decryption logic | DevTools, Python | `Completed` |
| **Insecure Design** | SecureChat | Unauthenticated internal API (`/api/messages/admin`) | Gobuster, DevTools | `Completed` |
| **Security Misconfiguration** | Lab Environment | Verbose errors, default configurations | Nmap, Gobuster | `Completed` |
| **Software Supply Chain Failures** | Application Dependencies | Compromised / vulnerable package imports | Dependency Check | `Completed` |

---

## 🛠️ Tools & Methodology

| Phase | Tool / Technology | Purpose |
| :--- | :--- | :--- |
| **Reconnaissance** | `Gobuster`, `Nmap` | Directory brute-forcing and network port discovery |
| **Web Analysis** | Firefox DevTools | Network traffic monitoring, cookie & JSON analysis |
| **Exploitation** | `cURL`, Python (`requests`) | Interacting with unauthenticated REST APIs |
| **OS & Shell** | Kali Linux | Terminal execution environment |

---

## 🚩 Captured Flags

| Vulnerability Category | Flag |
| :--- | :--- |
| **Insecure Design** | `THM{1NS3CUR3_D3S1GN_4SSUMPT10N}` |
| **Cryptographic Failures** | *(Documented in task folder)* |
| **Security Misconfiguration** | *(Documented in task folder)* |
| **Software Supply Chain Failures** | *(Documented in task folder)* |

---

## 🔒 Disclaimer

*All write-ups, scripts, and commands documented in this repository are created solely for educational purposes and authorized penetration testing within TryHackMe labs. Unsanctioned testing against external targets is strictly illegal.*
