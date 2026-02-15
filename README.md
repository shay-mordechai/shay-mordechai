# Hi there, I'm Shay! 👋

### 🛡️ Security Researcher | Web Architecture & OS Internals

I specialize in **Vulnerability Discovery**, **Web Security**, and **Automated Threat Hunting**.
My work bridges the gap between **Low-Level Architecture** (Binary Analysis, Memory Isolation) and **Network Defense** (L2-L7 Protocol Engineering, Zero Trust). As a daily **Fedora Kinoite** user, I have a deep appreciation for immutable architectures and container isolation, leveraging this environment to deconstruct complex systems and identify structural flaws.

---

### 🔭 Featured Research & Projects

**🐛 AI-Augmented Vulnerability Research (SBCL Compiler)**
* **Zero-Day Discovery:** Orchestrated an AI-driven fuzzing workflow identifying **3 Zero-Day vulnerabilities** (Memory Corruption, Buffer Overflow, Stack Exhaustion) in the SBCL compiler.
* **Technical Analysis:** Performed binary analysis on symbol flag modification processes and memory boundary violations.
* **Impact:** Verified 100% success rate for DoS attack vectors; findings reported to **Israel National CERT** (#11265) and MITRE.

**📡 TLS 1.2 Handshake & PCAP Simulator**
* **Protocol Engineering:** Engineered a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshake sessions and generate accurate PCAP traffic.
* **Low-Level Cryptography:** Implemented cryptographic operations from scratch, including RSA key exchange, Master Secret PRF derivation, and AES-128-CBC application data encryption.
* **Forensics Tooling:** Developed an automated SSLKeyLog generator to enable traffic decryption and deep packet inspection in Wireshark.

**🌐 Modern Web Internals & Protocol Research**
* **V8 JIT & Memory Internals:** Authored a deep-dive analysis on **V8 JIT engines**, focusing on RWX memory page exploitation and the collapse of Code/Data isolation.
* **React Server Components (RSC):** Researching the **Flight Protocol** for insecure deserialization and logic bypass vectors in Next.js environments.
* **Architectural Hardening:** Proposed a deterministic TTL-based mitigation for DNS Rebinding (LANJack), validated through collaboration with industry vendors (TP-Link PSIRT).

**🔐 LeadFlowAI (Secure-by-Design SaaS)**
* **Zero Trust Architecture:** Engineered a "Dark Server" environment on AWS with **zero public inbound ports**, routing traffic exclusively via **Cloudflare Argo tunnels**.
* **OS-Level Hardening:** Implemented rootless **Podman** containers natively on Linux, utilizing User Namespaces and Cgroups to mitigate breakout vulnerabilities.
* [🚀 Live Demo](https://my-leads.app/)

**🦁 Predator: Hybrid-Core Trading Engine**
* **Quantitative AI Stack:** Architected an automated trading engine fusing **XGBoost ML** models with a **Google Gemini LLM** integration for real-time market anomaly detection.
* **Dynamic Risk Management:** Leveraged 6+ years of fundamental market research to translate real-world geopolitical and financial anomalies into automated execution logic.

---

### 🛠️ Tech Stack & Methodology

**Security & OS Internals**
* **OS & Infrastructure:** Linux Internals (Namespaces, Cgroups, eBPF), Fedora Kinoite (Immutable OS), Rootless Podman, AWS Architecture.
* **Vulnerability Research:** Zero-Days, Fuzzing, Binary Analysis, JIT Internals, Insecure Deserialization.

**Network Engineering & Data**
* **Network Analysis:** Deep L2-L7 Protocol understanding, Scapy, Raw Sockets, PCAP Parsing, IPv4/IPv6, Wireshark.
* **Data & Analytics:** Statistical Analysis, Complex Data Sets, Data Manipulation, SQL.

**Development & Automation**
* **Languages:** Python (AsyncIO, Pandas), JavaScript, Bash, C/C++, x86 Assembly.
* **AI & ML:** Custom Fuzzer Development, LLM-Augmented Research, XGBoost.

---

### 📚 Knowledge Base & Articles

* [📝 **The Rise of FullStack Security Research**](https://www.linkedin.com/pulse/%D7%94%D7%9E%D7%A7%D7%A6%D7%95%D7%A2-%D7%94%D7%97%D7%93%D7%A9-fullstack-security-researcher-shay-mordechai-r2e8e/)
  A deep-dive technical analysis into modern browser engines, focusing on how JIT compilers bypass traditional memory isolation boundaries.

* [📂 **Network Security Toolbox**](https://github.com/shay-mordechai/Network-Security-Toolbox) - Custom tools for packet manipulation and protocol analysis.
* [📂 **Academic CS Summaries**](https://github.com/shay-mordechai/Academic-CS-Summaries) - Deep dives into Operating Systems and Network Analysis.

---

📫 **How to reach me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"Detecting the signal within the noise. From Packet Headers to Kernel Namespaces."*
