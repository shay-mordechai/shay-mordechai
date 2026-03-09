# Hi there, I'm Shay! 👋

### 🛡️ Security Researcher | Web Architecture, OS Internals & Network Defense

I specialize in **Vulnerability Discovery**, **Network Protocol Hardening**, and **Automated Threat Hunting**.
My work bridges the gap between **Low-Level Architecture** (Binary Analysis, Memory Isolation) and **Network Defense** (L2-L7 Protocol Engineering, Endpoint Security). As a daily **Fedora Kinoite** user, I have a deep appreciation for immutable architectures and container isolation, leveraging this environment to deconstruct complex systems and identify structural flaws.

---

### 🔭 Featured Research & Architectural Projects

**🐛 AI-Augmented Vulnerability Research (SBCL Compiler)**
* **Zero-Day Discovery:** Orchestrated an AI-driven fuzzing workflow identifying **3 Zero-Day vulnerabilities** (Memory Corruption, Buffer Overflow, Stack Exhaustion) in the SBCL compiler.
* **Technical Analysis:** Performed binary analysis on symbol flag modification processes and memory boundary violations.
* **Impact:** Verified 100% success rate for DoS attack vectors; findings reported to **Israel National CERT** (#11265) and MITRE.
* [🔗 View Methodology & Showcase](https://github.com/shay-mordechai/ai-augmented-sbcl-research-showcase)

**🦀 Data Hop Firewall (Envoy Wasm DLP)**
* **Egress Redaction:** Engineered a high-performance WebAssembly (Wasm) filter written in **Rust** for Envoy Proxy.
* **L7 Inspection:** Deep-scans response payloads to identify and mask sensitive keys, preventing API Over-fetching and Information Disclosure (CWE-209).
* **Zero-Trust Enforcement:** Utilizes a strict "Fail-Closed" architecture directly within the infrastructure layer.
* [🔗 View Repository](https://github.com/shay-mordechai/wasm-dlp-firewall)

**🔐 MyLeads AI (Secure-by-Design SaaS Architecture)**
* **Zero Trust Environment:** Engineered a "Dark Server" environment on AWS with **zero public inbound ports**, routing traffic exclusively via **Cloudflare Argo tunnels**.
* **Modern Stack Security:** Leverages **Next.js 14 (RSC)** to eliminate external attack surfaces, with container lifecycles managed via user-space **Systemd** and Rootless Podman on RHEL.
* **Privacy-First AI:** Implemented local audio transcription (Faster-Whisper) ensuring sensitive data never leaves the edge server.
* [🔗 View Architecture Showcase](https://github.com/shay-mordechai/myleads-saas-showcase) | [🌐 Live Demo](https://my-leads.app/)

**📱 Mobile & Browser Security Internals**
* **V8 JIT & Memory Internals:** Authored a deep-dive analysis on **V8 JIT engines** (core to Android Webview and mobile exploit chains), focusing on RWX memory page exploitation and the collapse of Code/Data isolation.
* **React Server Components (RSC):** Researching the **Flight Protocol** for insecure deserialization and logic bypass vectors in Next.js environments.

**🌐 Network Protocol Hardening & Analysis**
* **Deterministic TTL Mitigations:** Proposed an architectural Layer-3 mitigation for DNS Rebinding (LANJack), specifically addressing vectors where **mobile devices** are used as proxies to exploit local internal networks. Validated through collaboration with industry vendors (**TP-Link PSIRT**).
* **TLS 1.2 Handshake Simulator:** Engineered a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshake sessions. Implemented cryptographic operations from scratch (RSA, PRF, AES-128-CBC) and an automated SSLKeyLog generator for Wireshark traffic decryption.

---

### 🛠️ Tech Stack & Methodology

**Security, OS & Incident Response**
* **OS & Infrastructure:** Linux Internals (Namespaces, Cgroups, eBPF), Fedora Kinoite (Immutable OS), Rootless Podman, AWS Architecture.
* **Vulnerability Research:** Zero-Days, Fuzzing, Binary Analysis, JIT Internals, Insecure Deserialization.
* **Threat Detection:** Malware Analysis, Yara Rules, Device Log Parsing, Incident Response workflows.

**Network Engineering & Data**
* **Network Analysis:** Deep L2-L7 Protocol understanding, Scapy, Raw Sockets, PCAP Parsing, IPv4/IPv6, Wireshark.
* **Data & Analytics:** Statistical Analysis, Complex Data Sets, Data Manipulation, SQL/KQL.

**Development & Automation**
* **Languages:** Python (AsyncIO, Pandas), Rust, JavaScript/TypeScript, Bash, C/C++, x86 Assembly.
* **AI & ML:** Custom Fuzzer Development, LLM-Augmented Research, AI Agents orchestration.

---

### 🌱 Currently Learning
Deepening expertise in **Advanced Malware Analysis & Reverse Engineering**, extracting IoCs/IoAs, unpacking Ransomware payloads, and writing custom **Yara rules** for proactive threat detection.

---

### 📚 Knowledge Base & Articles

* [📝 **V8 JIT Internals & RWX Exploitation**](https://www.linkedin.com/pulse/%D7%94%D7%9E%D7%A7%D7%A6%D7%95%D7%A2-%D7%94%D7%97%D7%93%D7%A9-fullstack-security-researcher-shay-mordechai-r2e8e/)
  A deep-dive technical analysis into modern browser engines, focusing on how JIT compilers bypass traditional memory isolation boundaries.
* [📂 **Network Security Toolbox**](https://github.com/shay-mordechai/Network-Security-Toolbox) - Custom tools for packet manipulation and protocol analysis.
* [📂 **Academic CS Summaries**](https://github.com/shay-mordechai/Academic-CS-Summaries) - Deep dives into Design Patterns, SOLID principles, and Network Analysis.

---

📫 **How to reach me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"Detecting the signal within the noise. From Packet Headers to Kernel Namespaces."*
