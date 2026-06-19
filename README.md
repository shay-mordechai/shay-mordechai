הנה עדכון מקיף לפרופיל/README שלך. המטרה כאן היא למזג את החלקים החזקים מהגרסה הישנה יחד עם הישגי הארכיטקטורה של **MyLeads AI** והניסיון המעשי שלך מרשות המיסים, תוך שמירה על המיקוד המבוקש ב-**AI Security & OS Internals**:

---

# Shay Mordechai

**Security Researcher & AppSec Engineer** focused on OS internals, secure systems architecture, and runtime security boundaries.
I specialize in reverse engineering, structural threat modeling, and breaking isolation barriers across native code, compilers, mobile runtimes, and AI-driven platforms.

### 🎯 Areas of Focus

* **OS & Runtime Internals:** Linux namespaces, Android framework infrastructure, Binder IPC, and compiler isolation mechanics.
* **Secure Architecture & Threat Modeling:** Implementing Zero Trust cloud topologies, API protection gateways, and defense-in-depth orchestration.
* **Reverse Engineering & Instrumentation:** Runtime analysis, hooking native boundaries (`JNI`, `ptrace` bypasses), and memory extraction using Frida, JADX, and IDA Pro.
* **AI & Platform Security:** Analyzing security assumptions and systemic risks within Large Language Model (LLM) application interfaces and API gatekeepers.

---

### 🔬 Featured Research & Disclosures

#### Compiler Security Research (CERT-IL #11265 & MITRE)

* Developed a semantic fuzzing workflow targeting SBCL compiler internals.
* Disclosed three compile-time trust boundary flaws regarding lexical scope isolation.

#### Android Framework Lifecycle Analysis

* Reverse engineered Android framework execution flow to analyze malware loading behaviors before UI initialization.
* Investigated early lifecycle hooks (`ContentProvider`, `attachBaseContext`, `LoadedApk`) utilizing Frida and runtime memory extraction.
* Published findings in *Digital Whisper*.

#### Platform Quota & API Invalidation Bypass (OpenAI / Bugcrowd)

* Identified an architectural session invalidation flaw in the ChatGPT backend allowing established in-flight API streams to bypass UI layer quota locks.
* Demonstrated scalable resource exhaustion capabilities ($N\times$ compute multi-streaming) via direct server-side token exploitation.

---

### 🛠️ Production Projects & Tooling

#### MyLeads AI — Secure SaaS Architecture (AWS)

* **Zero Attack Surface:** Architected an inbound-less production environment on AWS EC2 via outbound-only Cloudflare Tunnels, completely eliminating public listening ports (`0.0.0.0/0`). Workloads run inside Rootless Podman on RHEL 10.1.
* **Envoy WASM DLP Firewall:** Engineered a custom data loss prevention filter in Rust, deployed within an Envoy Proxy to intercept `5xx` payloads and dynamically sanitize runtime stack traces (*CWE-209 mitigation*).
* **In-Memory Bootstrapping:** Discarded static `.env` configuration files by leveraging `boto3` to pull environment secrets directly from AWS SSM Parameter Store into volatile memory at runtime, hardened by AWS IMDSv2 token validation.
* **Identity Resolution:** Enforced centralized authorization using cryptographically signed JWT Claims fetched via isolated dependencies, completely eliminating user-supplied ID parameters to systematically prevent IDOR vectors.

#### Network & Security Infrastructure

* **Scapy TLS Creator:** Built a programmatic TLS 1.2 handshake simulation and cryptographic traffic decryption tool.
* **Operation Blackbird:** Designed a specialized CTF training platform focusing on covert network channels and advanced data exfiltration primitives.

---

### 💼 Professional Experience

* **Independent Security Researcher** | *Aug 2025 – Present*
Investigating trust boundaries across application layers, distributed backend frameworks, and specialized runtimes.
* **Application Security Analyst** | *Israel Tax Authority* | *Aug 2024 – Jul 2025*
* Served as the AppSec Lead for a flagship multi-GB financial ingestion platform; mapped system-wide data pipelines alongside R&D stakeholders.
* Designed end-to-end security requirements for a high-throughput external-to-internal CDR (Content Disarm and Reconstruction) sanitization infrastructure.
* Orchestrated enterprise-grade SAST/SCA tooling operations (*Checkmarx / Checkmarx One*), dramatically reducing false-positive overhead and engineering optimized remediation cycles for critical assets.



---

### 💻 Technical Stack

* **Languages:** C/C++, Rust, Python, Python (Async), Java, Assembly (x86/ARM), JavaScript
* **Tooling:** Frida, IDA Pro, Ghidra, JADX, Burp Suite, Checkmarx, Scapy, Docker, Podman
* **Cloud & Infrastructure:** AWS (EC2, SSM, RDS, CloudWatch), Cloudflare Zero Trust (Tunnels/IAP), Linux Internals, Envoy Proxy (WASM)

---

### 🔗 Connect

* **Portfolio / Blog:** [shay-mordechai.github.io](https://shay-mordechai.github.io)
* **LinkedIn:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)
* **Email:** [shay.mordechai@proton.me](mailto:shay.mordechai@proton.me)

---

### 🎓 Education & Service

* **B.Sc. in Computer Science** | Jerusalem College of Technology (JCT) | *Graduated July 2025* (GPA: 89)
* **IDF Combat Intelligence** | Reconnaissance Specialist | *2016 – 2018*
