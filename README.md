# Hi there, I'm Shay! 👋

### ⚔️ Offensive Security Researcher | Vulnerability Research & Malware Analysis

I specialize in **Vulnerability Discovery**, **Reverse Engineering**, and **OS/Network Internals**. My work bridges the gap between **Low-Level Architecture** (Binary Analysis, Runtime Code Manipulation) and **Network Exploitation** (L2-L7 Protocol Engineering, TTPs). As a daily **Fedora Kinoite** user, I leverage isolated environments to dynamically analyze complex systems, bypass anti-analysis mechanisms, and uncover zero-day logic flaws from the network layer up to the application logic.

---

### 🔬 Featured Research & Reverse Engineering

**🦠 Advanced Reverse Engineering & Malware Analysis Labs**
* **Anti-Analysis Evasion:** Reverse-engineering multi-stage Windows executables, successfully bypassing **TLS Callbacks** and `IsDebuggerPresent` checks.
* **Control Flow Hijacking:** Solved the highly selective **ISA (Shabak) Level 1 challenge** via static/dynamic patching, and executed Entry Point Hijacking (Code Caves) in graphical WinMain applications.
* [📂 View RE Labs & Write-ups](https://github.com/shay-mordechai/malware-reversing-labs)

**📖 Security Research Journal & Whitepapers**
* **Browser Internals (V8 JIT):** Authored a deep-dive analysis on V8 engines, utilizing runtime code manipulation, **hooking/detours**, and RWX memory page allocation to achieve CFI bypasses.
* **Network Protocols (DNS Rebinding):** Proposed a deterministic network-layer defense (`TTL=1` enforcement) against LANJack exfiltration. Acknowledged by **Palo Alto Networks PSIRT** & **TP-Link PSIRT**.
* **Compiler Security:** Analyzed execution flow differences between Macros and Functions, and their impact on AST manipulation and vulnerability research.
* [📚 Read Research Papers](https://github.com/shay-mordechai/security-research-journal)

**🐛 AI-Augmented Vulnerability Research (SBCL Compiler)**
* **Zero-Day Discovery:** Led Red Team research and pre-deployment testing via an AI-driven semantic fuzzing workflow, discovering **3 pending Zero-Days** (CERT-IL #11265) in the SBCL compiler.
* **Bypass Techniques:** Discovered and documented bypass techniques for lexical scope and memory boundary violations.
* [🔍 View Methodology & PoC](https://github.com/shay-mordechai/ai-augmented-sbcl-research-showcase)

---

### 🌐 Offensive Infrastructure & Protocol Engineering

**🦅 Operation Blackbird (Network Exfiltration & C2)**
* **Covert Channels:** Engineered an advanced CTF platform modeling nation-state exfiltration tactics, implementing custom **ICMP covert channels** via Scapy.
* **Infrastructure Infiltration:** Simulated advanced malware communication protocols using PKI MITM techniques (Burp Suite).
* [📂 View Project Source](https://github.com/shay-mordechai/Operation-Blackbird)

**🔐 TLS 1.2 Cryptographic Simulator**
* **Low-Level Implementation:** Authored a 4,000+ line Python framework using **Scapy** to simulate full TLS 1.2 handshake sessions from scratch (RSA, PRF, AES-128-CBC).
* **Forensics Tooling:** Developed an automated SSLKeyLog generator to enable traffic decryption and Deep Packet Inspection (DPI) in Wireshark.
* [📂 View Framework Source](https://github.com/shay-mordechai/Scapy-TLS-Creator)

**🛡️ Secure API Architecture & Egress Redaction**
* **Zero-Trust Enforcement:** Architected encrypted microservice tunnels using Envoy Proxy. Engineered a WebAssembly (Wasm) filter to dynamically parse and redact sensitive payloads from outbound traffic, preventing browser-side data leakage.
* [🔗 View Architecture](https://github.com/shay-mordechai/wasm-dlp-firewall)

**🦀 Hardware-Enforced Network Guard (Rust/ESP32)**
* **Embedded Security:** Developing a bare-metal (`no_std`) secure network gateway on an ESP32 microcontroller using **Rust**.
* **Adversarial Testing:** Implementing Deep Packet Inspection (DPI) to enforce strict TTL policies, conducting packet injection attacks via AR9271 (Atheros) to validate hardware-level isolation.

---

### 🛠️ Tech Stack & Methodology

* **Reverse Engineering & Malware Analysis:** IDA Pro, Ghidra, WinDbg, x64dbg, PE Format internals, Unpacking, Yara Rules.
* **Offensive Security:** Binary Patching, Hooking, Detours, Semantic Fuzzing, TTPs, Burp Suite, Evasion techniques.
* **OS Internals:** Linux Internals (Namespaces, eBPF), Memory Isolation, W^X / NX Evasion, Fedora Kinoite.
* **Network Engineering:** Deep L2-L7 Protocol understanding, Scapy, Raw Sockets, PCAP Parsing, DPI.
* **Languages:** C/C++, x86/x64 Assembly, Bash. Proficient in **Python** (Automation & Security Tooling). Knowledge & Analysis of JS, Java, C#, Rust, Raku.

---

### 📚 Additional Knowledge Base

* [🌐 **Personal Portfolio & Full Write-ups**](https://shay-mordechai.github.io)
* [⚙️ **Network Security Toolbox**](https://github.com/shay-mordechai/Network-Security-Toolbox) - Custom tools for packet manipulation and protocol analysis.
* [🏗️ **MyLeads AI Showcase**](https://github.com/shay-mordechai/myleads-saas-showcase) - A secure-by-design "Dark Server" architecture highlighting Zero-Trust engineering.

---

📫 **How to reach me:** [linkedin.com/in/shay-mordechai](https://www.linkedin.com/in/shay-mordechai/)

> *"Detecting the signal within the noise. From Runtime Execution Hooking to Kernel Namespaces."*
