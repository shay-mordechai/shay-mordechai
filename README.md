# Hi there, I'm Shay! 👋

### ⚔️ Offensive Security Researcher | Vulnerability Research & OS Internals

I specialize in **Vulnerability Discovery**, **Reverse Engineering**, and **OS/Network Internals**. My work focuses on bypassing complex security boundaries—whether it's **Kernel-level Anti-Debugging**, **JIT-Compiled FFI Bridges**, or **Encrypted Network Protocols**. As a daily **Fedora Kinoite** user, I leverage isolated environments to dynamically analyze binary execution, perform runtime code manipulation, and uncover logic flaws from the instruction pointer up to the application logic.

---

### 🔬 Featured Research & Mobile Internals

**📱 Mobile Native Security & Forensic Extraction (Android/iOS)**
* **Anti-Analysis Bypass:** Reverse-engineering Android Native libraries (`.so`) to neutralize Linux-level anti-debugging mechanisms like **`ptrace`** and integrity checks.
* **JNI Interop Analysis:** Utilizing **Frida (DBI)** to perform inline hooking on JNI boundaries, intercepting data flows crossing from Managed (Java) to Native (C/C++) contexts.
* **Artifact Extraction:** Solved the **OWASP UnCrackable Level 2** challenge by identifying undisclosed API patterns and extracting hardcoded runtime secrets via memory manipulation.
* [📂 View Mobile RE Write-ups](https://shay-mordechai.github.io)

**📖 Security Research Journal & Whitepapers**
* **Browser Internals (V8 JIT & FFI):** Authored a deep-dive on V8 engines, focusing on **JIT-Compiled FFI Bridges** and RWX memory page allocation to achieve CFI bypasses via runtime hooking.
* **Network Protocols (DNS Rebinding):** Proposed a deterministic network-layer defense against LANJack exfiltration. Acknowledged by **Palo Alto Networks PSIRT** & **TP-Link PSIRT**.
* **Compiler Security:** Discovered **3 pending Zero-Days** (CERT-IL #11265) in the SBCL compiler via AI-driven semantic fuzzing and pre-deployment red-teaming.
* [📚 Read Research Papers](https://github.com/shay-mordechai/security-research-journal)

---

### 🌐 Offensive Infrastructure & Protocol Engineering

**🦅 Operation Blackbird (Network Exfiltration & C2)**
* **Covert Channels:** Engineered an advanced CTF platform modeling nation-state exfiltration tactics, implementing custom **ICMP covert channels** and PKI MITM.
* [📂 View Project Source](https://github.com/shay-mordechai/Operation-Blackbird)

**🔐 TLS 1.2 Cryptographic Simulator**
* **Low-Level Implementation:** Authored a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshakes from scratch (RSA, PRF, AES-CBC).
* **Forensics Tooling:** Developed an automated SSLKeyLog generator for Deep Packet Inspection (DPI) and traffic decryption in Wireshark.
* [📂 View Framework Source](https://github.com/shay-mordechai/Scapy-TLS-Creator)

**🛡️ Secure API Architecture & Egress Redaction**
* **Zero-Trust Enforcement:** Architected Envoy Proxy tunnels with Wasm filters to dynamically redact sensitive payloads from **undisclosed API endpoints**, preventing data leakage.
* [🔗 View Architecture](https://github.com/shay-mordechai/wasm-dlp-firewall)

---

### 🛠️ Tech Stack & Methodology

* **Reverse Engineering:** IDA Pro, Ghidra, JADX, WinDbg, x64dbg, Binary Patching, ARM64/x86 Assembly.
* **Dynamic Instrumentation:** Frida, Objection, Hooking/Detours, Runtime Code Manipulation.
* **Network & AppSec:** Burp Suite (Advanced TTPs), Wireshark, Fiddler, Protocol Fuzzing, L2-L7 Analysis.
* **OS Internals:** Linux Namespaces, Memory Isolation (NX/ASLR Evasion), Immutable OS (Fedora Kinoite).
* **Languages:** **Python** (Automation), **C# / .NET** (OOP), C/C++, Rust (`no_std`), GoLang, Java, JS.

---

### 📚 Knowledge Base & Portfolio

* [🌐 **Personal Portfolio & Full Write-ups**](https://shay-mordechai.github.io)
* [🏗️ **MyLeads AI Showcase**](https://github.com/shay-mordechai/myleads-saas-showcase) - Zero-Trust "Dark Server" Architecture.

---

📫 **Connect with me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"From JNI Bridge Hooking to Kernel-Level Hardening. Mapping the undisclosed."**
