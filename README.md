# Hi there, I'm Shay! 👋

### ⚔️ Mobile & Browser Security Researcher | OS Internals

I specialize in **Execution Flow Analysis**, **Reverse Engineering**, and **OS/Network Internals**. My work focuses on dissecting security boundaries—whether it's **Kernel-level Anti-Debugging**, **JNI Interop Bridges**, or **Encrypted Network Protocols**. As a daily **Fedora Kinoite** user, I leverage isolated environments to dynamically analyze binary execution, perform runtime code manipulation, and uncover logic flaws from the instruction pointer up to the application logic.

---

### 🔬 Featured Research & Mobile Internals

**📱 Mobile Native Security & Execution Interception (Android/iOS)**
* **Anti-Analysis Bypass:** Reverse-engineering Android Native libraries (`.so`) to neutralize Linux-level anti-debugging mechanisms like **`ptrace`** and integrity checks.
* **JNI Interop Analysis:** Utilizing **Frida (DBI)** to perform inline hooking on JNI boundaries, intercepting data flows crossing from Managed (Java) to Native (C/C++) contexts.
* **Artifact Extraction:** Solved **OWASP UnCrackable Level 2** by bypassing runtime debugger detection and extracting decrypted assets directly from memory.
* [📂 View Mobile RE Write-ups](https://shay-mordechai.github.io)

**📖 Security Research Journal & Whitepapers**
* **Browser Internals (V8 JIT & FFI):** Authored a deep-dive on V8 engines, focusing on **JIT-Compiled FFI Bridges** and the paradox of RWX memory page allocation in modern browsers.
* **Network Protocols (DNS Rebinding):** Proposed a deterministic network-layer defense against LANJack exfiltration. Acknowledged by **Palo Alto Networks PSIRT** & **TP-Link PSIRT**.
* **Compiler Security:** Investigated **SBCL Compiler isolation boundaries** via AI-assisted semantic fuzzing, discovering security-relevant edge cases and DoS conditions (CERT-IL #11265).
* [📚 Read Research Papers](https://github.com/shay-mordechai/security-research-journal)

---

### 🌐 Offensive Infrastructure & Protocol Engineering

**🦅 Operation Blackbird (Network Exfiltration & C2)**
* **Covert Channels:** Engineered an advanced CTF platform modeling nation-state exfiltration tactics, implementing custom **ICMP covert channels** and PKI MITM scenarios.
* [📂 View Project Source](https://github.com/shay-mordechai/Operation-Blackbird)

**🔐 TLS 1.2 Cryptographic Simulator**
* **Low-Level Implementation:** Authored a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshakes from scratch (RSA, PRF, AES-CBC).
* **Forensics Tooling:** Developed an automated SSLKeyLog generator for Deep Packet Inspection (DPI) and traffic decryption in Wireshark.
* [📂 View Framework Source](https://github.com/shay-mordechai/Scapy-TLS-Creator)

**🛡️ Secure API Architecture & Egress Redaction**
* **Zero-Trust Enforcement:** Architected Envoy Proxy tunnels with Wasm filters to dynamically redact sensitive payloads from API egress traffic, preventing data leakage.
* [🔗 View Architecture](https://github.com/shay-mordechai/wasm-dlp-firewall)

---

### 🛠️ Tech Stack & Methodology

* **Reverse Engineering:** IDA Pro, Ghidra, JADX, WinDbg, x64dbg, Binary Patching, ARM64/x86 Assembly.
* **Dynamic Instrumentation:** Frida, Objection, Java/Native Hooking, Runtime Code Manipulation.
* **Network & AppSec:** Burp Suite (Advanced TTPs), Wireshark, Protocol Fuzzing, L2-L7 Analysis.
* **OS Internals:** Linux Namespaces, Network Namespaces, Memory Isolation (NX/ASLR Evasion), Immutable OS (Kinoite).
* **Languages:** **Python** (Automation), C/C++, **Rust** (`no_std` for Wasm), Java, JavaScript.

---

### 📚 Knowledge Base & Portfolio

* [🌐 **Personal Portfolio & Full Write-ups**](https://shay-mordechai.github.io)
* [🏗️ **MyLeads AI Showcase**](https://github.com/shay-mordechai/myleads-saas-showcase) - Zero-Trust Architecture & Infrastructure Hardening.

---

📫 **Connect with me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"From JNI Bridge Hooking to OS-Level Hardening. Mapping the undisclosed."*
