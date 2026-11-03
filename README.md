# Cybersecurity-CTF-Labs-Collection-Reverse-Engineering-PKI-Trust-Cryptanalysis
A curated, searchable index of hands-on CTF labs covering binary exploitation, Ghidra reverse engineering, assembly basics, dynamic analysis, PKI certificate chains, HMAC integrity, digital signatures, and cryptanalysis from Learn SecByte.
# Reverse Engineering, PKI Trust & Cryptanalysis CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Binary Analysis & Reverse Engineering (Crackme challenges, Ghidra disassembly, x86/x64 assembly fundamentals, static/dynamic binary analysis), Public Key Infrastructure (PKI certificate chains, TLS incident response, trust misuses), and Applied Cryptography & Cryptanalysis (HMAC integrity, digital signatures, breaking simple ciphers) hosted on Learn SecByte.

This collection is designed for reverse engineers, malware analysts, PKI specialists, cryptography researchers, and security analysts seeking practical experience in binary analysis and cryptographic system validation.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Reverse Engineering & Binary Analysis](#reverse-engineering--binary-analysis)
  - [Public Key Infrastructure (PKI) & TLS Security](#public-key-infrastructure-pki--tls-security)
  - [Applied Cryptography & Cryptanalysis](#applied-cryptography--cryptanalysis)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Modern cybersecurity defense requires a deep understanding of executable internals and cryptographic trust anchors. Dissecting unknown binaries through static disassembly and dynamic sandbox debugging reveals key software logic, anti-analysis traps, and vulnerability vectors. Concurrently, cryptographic mechanisms—ranging from TLS certificate validation to digital signature verification and HMAC integrity—form the backbone of trusted digital interactions.

This repository organizes hands-on reverse engineering, PKI, and cryptography labs from Learn SecByte into structured learning paths covering binary analysis and cryptographic security.

---

## Lab Collection & Index

| Lab Title | Domain Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **Binary Breadcrumbs** | Reversing | Crackme Challenge & Logic Reversing | [Access Lab](https://learn.secbyte.org/ctf/binary-breadcrumbs-crackme-challenge) |
| **Binary Exploitation Basics** | Reversing / Pwn | From Crash to Instruction Control | [Access Lab](https://learn.secbyte.org/ctf/binary-exploitation-basics-from-crash-to-control) |
| **Ghidra Essentials** | Reversing | Reverse Engineering Bootcamp | [Access Lab](https://learn.secbyte.org/ctf/ghidra-essentials-reverse-engineering-bootcamp) |
| **Assembly Language Basics** | Low-Level | Registers, Stack Frames to ROP | [Access Lab](https://learn.secbyte.org/ctf/assembly-language-basics-from-registers-to-rop) |
| **Dynamic Analysis Deep Dive** | Reversing | Process Behavior, Sandboxing & Debugging | [Access Lab](https://learn.secbyte.org/ctf/dynamic-analysis-deep-dive) |
| **Binary Echo** | Static Analysis | Inspecting Suspicious Utilities | [Access Lab](https://learn.secbyte.org/ctf/binary-echo-static-analysis-suspicious-utility) |
| **Binary Whisper** | Reversing | Reverse Engineering Fundamentals | [Access Lab](https://learn.secbyte.org/ctf/binary-whisper-reverse-engineering-fundamentals) |
| **TLS & HTTPS Certificate Chain** | PKI / Incident Response | Certificate Validation & Chain IR | [Access Lab](https://learn.secbyte.org/ctf/tls-and-https-certificate-chain-incident-response) |
| **PKI Fundamentals** | PKI Security | Trust Chains, Certificates & Misuse | [Access Lab](https://learn.secbyte.org/ctf/pki-fundamentals-trust-certificates-and-misuse) |
| **HMAC Essentials** | Cryptography | Message Authentication & Integrity | [Access Lab](https://learn.secbyte.org/ctf/hmac-essentials-message-integrity) |
| **Digital Signatures** | Cryptography | Trust, Non-Repudiation & Tamper Checks | [Access Lab](https://learn.secbyte.org/ctf/digital-signatures-trust-tamper-verification) |
| **Cryptanalysis Basics** | Cryptography | Breaking Simple & Classical Ciphers | [Access Lab](https://learn.secbyte.org/ctf/cryptanalysis-basics-breaking-simple-ciphers) |

---

## Categories

### Reverse Engineering & Binary Analysis
Hands-on CTF labs detailing binary decompilation, assembly register manipulation, static code auditing, and dynamic process monitoring:

* **Assembly Language Basics:** Understanding CPU registers (`RAX`, `RBP`, `RSP`), stack navigation, memory addressing modes, and control flow instructions.
  * Lab Link: https://learn.secbyte.org/ctf/assembly-language-basics-from-registers-to-rop
* **Binary Whisper & Binary Echo:** Applying static analysis techniques, extracting string references, analyzing import/export tables, and evaluating suspicious utility binaries.
  * Lab Links:
    * Binary Whisper: https://learn.secbyte.org/ctf/binary-whisper-reverse-engineering-fundamentals
    * Binary Echo: https://learn.secbyte.org/ctf/binary-echo-static-analysis-suspicious-utility
* **Ghidra Essentials Bootcamp:** Utilizing the Ghidra SRE framework for decompilation, script automation, data structure reconstruction, and function renaming.
  * Lab Link: https://learn.secbyte.org/ctf/ghidra-essentials-reverse-engineering-bootcamp
* **Binary Breadcrumbs (Crackme Challenge):** Solving reverse engineering challenges, bypassing key validation checks, and patching binary execution logic.
  * Lab Link: https://learn.secbyte.org/ctf/binary-breadcrumbs-crackme-challenge
* **Dynamic Analysis Deep Dive:** Executing binaries in sandbox environments, tracing system calls (`strace`/`ltrace`), and monitoring memory changes with debuggers.
  * Lab Link: https://learn.secbyte.org/ctf/dynamic-analysis-deep-dive
* **Binary Exploitation Basics:** Transitioning from binary crashes to register control, offset calculation, and initial shellcode execution.
  * Lab Link: https://learn.secbyte.org/ctf/binary-exploitation-basics-from-crash-to-control

### Public Key Infrastructure (PKI) & TLS Security
Practical security labs focused on certificate trust verification, root/intermediate CAs, and investigating broken TLS handshake incidents:

* **PKI Fundamentals (Trust & Misuse):** Examining X.509 certificate fields, root anchor trust models, path validation rules, and common PKI misconfigurations.
  * Lab Link: https://learn.secbyte.org/ctf/pki-fundamentals-trust-certificates-and-misuse
* **TLS & HTTPS Certificate Chain Incident Response:** Investigating invalid TLS certificate chains, expired intermediate certificates, hostname mismatch alerts, and interception proxies.
  * Lab Link: https://learn.secbyte.org/ctf/tls-and-https-certificate-chain-incident-response

### Applied Cryptography & Cryptanalysis
Security engineering labs detailing key hashing algorithms, digital signature validation, message authentication codes, and cipher breakdown techniques:

* **HMAC Essentials:** Implementing and verifying Hash-based Message Authentication Codes (HMAC) to guarantee data origin authenticity and payload integrity.
  * Lab Link: https://learn.secbyte.org/ctf/hmac-essentials-message-integrity
* **Digital Signatures (Trust & Verification):** Analyzing asymmetric signature algorithms (RSA/ECDSA), verifying public key certificates, and detecting message tampering.
  * Lab Link: https://learn.secbyte.org/ctf/digital-signatures-trust-tamper-verification
* **Cryptanalysis Basics:** Evaluating classical ciphers, frequency analysis, key recovery techniques, and cryptographic implementation weaknesses.
  * Lab Link: https://learn.secbyte.org/ctf/cryptanalysis-basics-breaking-simple-ciphers

---

## Learning Path

Follow this structured roadmap to master binary reverse engineering and cryptographic validation:

1. **Assembly Foundations & Static Binary Inspection**
   - Study Assembly Language Basics to master register usage and stack management.
   - Use Binary Echo and Binary Whisper to conduct initial static analysis on compiled binaries.
2. **Ghidra Reversing & Dynamic Sandboxing**
   - Master decompilation and control flow analysis using Ghidra Essentials.
   - Track dynamic execution flows using Dynamic Analysis Deep Dive and solve the Binary Breadcrumbs Crackme.
3. **PKI Trust Chains & TLS IR**
   - Analyze Public Key Infrastructure models via PKI Fundamentals.
   - Investigate broken HTTPS connections and trust chain flaws in TLS Incident Response scenarios.
4. **Applied Cryptography & Cryptanalysis**
   - Enforce message integrity using HMAC Essentials and Digital Signatures.
   - Practice cipher breaking and vulnerability identification in Cryptanalysis Basics.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using reverse engineering, network, and cryptographic toolsets (Ghidra, GDB, Wireshark, OpenSSL, CyberChef, Python crypto libraries, and Process Monitor).
4. Review post-lab solution writeups, cryptographic hardening recommendations, and binary patch files to consolidate your learning.

---

## Disclaimer

This repository is strictly intended for educational research, authorized reverse engineering, and defensive security training. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise software and network infrastructure. Unsanctioned reverse engineering of commercial software, unauthorized binary exploitation, or malicious attacks against external networks are strictly illegal.
