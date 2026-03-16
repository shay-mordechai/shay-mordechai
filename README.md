# Hi there, I'm Shay! 👋

### ⚔️ Offensive Security Researcher | Reverse Engineering & Network Internals

I specialize in **Vulnerability Discovery**, **Reverse Engineering**, and **Red Teaming**. My work bridges the gap between **Low-Level Architecture** (Binary Analysis, Runtime Code Manipulation) and **Network Exploitation** (L2-L7 Protocol Engineering, TTPs). As a daily **Fedora Kinoite** user, I leverage isolated environments to dynamically analyze (לנתח באופן דינמי) complex systems, bypass security mechanisms, and uncover zero-day logic flaws from the network layer up to the application logic.

---

### 🔭 Featured Research & Architectural Projects

**🦀 Hardware-Enforced Network Guard (Rust/ESP32)**

* **Embedded Security:** Developing a bare-metal (`no_std`) secure network gateway on an ESP32 microcontroller using **Rust**.
* **Layer-7 Mitigation:** Implementing Deep Packet Inspection (DPI) to enforce strict TTL policies and intercept DNS Rebinding attempts at the hardware edge.
* **Adversarial Testing:** Conducting packet injection attacks using an AR9271 (Atheros) chipset to validate hardware-level isolation and bypass resistance (עמידות לעקיפות).

**🐛 AI-Augmented Red Teaming (SBCL Compiler)**

* **Zero-Day Discovery:** Led Red Team research and pre-deployment testing via an AI-driven semantic fuzzing workflow, discovering **3 pending Zero-Days** (CERT-IL #11265) in the SBCL compiler.
* **Bypass Techniques:** Discovered and documented bypass techniques for lexical scope and memory boundary violations.
* [🔗 View Methodology & Showcase](https://github.com/shay-mordechai/ai-augmented-sbcl-research-showcase)

**📱 Browser Internals & JIT Exploitation (V8 Engine)**

* **Runtime Manipulation:** Authored a deep-dive analysis on **V8 JIT engines**, utilizing runtime code manipulation concepts and execution hooking (התחברות לתהליכים) techniques.
* **Memory Isolation Bypass:** Analyzed RWX (Read-Write-Execute) memory page allocation patterns and their implications on bypassing Control Flow Integrity (CFI).
* [🔗 Read Article](https://www.linkedin.com/pulse/%D7%94%D7%9E%D7%A7%D7%A6%D7%95%D7%A2-%D7%94%D7%97%D7%93%D7%A9-fullstack-security-researcher-shay-mordechai-r2e8e/)

**🌐 Network Protocol Hardening & Vulnerability Disclosure**

* **DNS Rebinding Exploitation:** Discovered local management interface bypasses via DNS Rebinding (LANJack), targeting vectors where mobile devices act as proxies.
* **Reporting & Remediation:** Authored comprehensive and technically rigorous reports detailing the exploit chain (שרשרת התקיפה), leading to mitigation validations by **TP-Link & Palo Alto PSIRT**.
* **TLS 1.2 Handshake Simulator:** Engineered a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshake sessions, dissecting TCP/IP flows for network forensics and IPS evasion testing.

**🛡️ Data Hop Firewall (Envoy Wasm DLP)**

* **Egress Redaction:** Engineered a high-performance WebAssembly (Wasm) filter written in **Rust** for Envoy Proxy.
* **Zero-Trust Enforcement:** Deep-scans response payloads to identify and mask sensitive keys in real-time, preventing Information Disclosure (CWE-209) using a strict "Fail-Closed" architecture.
* [🔗 View Repository](https://github.com/shay-mordechai/wasm-dlp-firewall)

---

### 🛠️ Tech Stack & Methodology

**Offensive Security & Reverse Engineering**

* 
**Reverse Engineering:** Conducted static analysis using IDA and dynamic analysis with WinDbg and x32dbg.


* 
**Evasion & Exploitation:** Bypassing anti-debugging mechanisms , deobfuscating self-modifying code, Runtime Code Manipulation, Hooking, Fuzzing.


* **Red Teaming:** TTPs analysis, Threat Hunting, Web Penetration Testing, Bug Bounty (Vulnerability Disclosure).

**OS Internals & Infrastructure**

* **OS Architecture:** Linux Internals (Namespaces, Cgroups, eBPF), Fedora Kinoite (Immutable OS), Systemd, Memory Isolation.
* **Cloud & Edge:** AWS Architecture, Rootless Podman, Envoy Proxy, Cloudflare Tunnels (Zero-Trust).

**Network Engineering & Development**

* **Network Analysis:** Deep L2-L7 Protocol understanding, Scapy, Raw Sockets, PCAP Parsing, DPI.
* **Languages:** Rust (`no_std`, Wasm), Python (Scapy, AsyncIO), C/C++, x86/x64 Assembly, Bash, JavaScript.

---

### 🌱 Continuous Research

Actively mastering advanced malware analysis by reverse-engineering proprietary logic, focusing on extracting IoCs, unpacking evasive payloads, and writing custom **Yara rules** for proactive threat detection.

---

### 📚 Knowledge Base

* [📂 **Network Security Toolbox](https://github.com/shay-mordechai/Network-Security-Toolbox)** - Custom tools for packet manipulation and protocol analysis.
* [🔐 **MyLeads AI Showcase](https://github.com/shay-mordechai/myleads-saas-showcase)** - A secure-by-design "Dark Server" architecture highlighting Zero-Trust engineering.

---

📫 **How to reach me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"Detecting the signal within the noise. From Runtime Execution Hooking to Kernel Namespaces."*
