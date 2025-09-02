# Hello, I'm Tay Jia Yi
<a href="https://linkedin.com"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I am a graduate from Nanyang Technological University with a Bachelor’s degree in Computer Science and a minor in Cybersecurity.

## Objective

This repository aggregates my hands-on exercises and self-driven projects in malware analysis, reverse engineering, and exploitation. Each project demonstrates practical application of cybersecurity knowledge with a focus on **malware behavior, exploitation techniques, and defensive countermeasures**.

## Skills

| Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| Golang Malware Analysis          | <a href="https://github.com/Innuerr/Malware-Analysis-of-Go-based-Keylogger/tree/main">Malware Analysis of Go-based Keylogger</a>|
| Detection of Node.js Exploitation Techniques  | <a href="https://github.com/Innuerr/Malicious-Electron-Application/tree/main">Malicious-Electron-Application</a>|
| Network Traffic and Static Analysis       | <a href="https://github.com/Innuerr/Malicious-Electron-Application/tree/main">Malicious-Electron-Application</a>||
| Disassembly & Decompilation      | <a href="https://github.com/Innuerr/Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication/tree/main">Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication</a>|
| Debugging & Reverse Engineering                | <a href="https://github.com/Innuerr/Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication/tree/main">Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication</a>|
| Custom Decryption & Automation Scripting  | <a href= https://github.com/Innuerr/Malware-Deobfuscation-Lab-Reversing-Base64-XOR-Payload-Encryption/tree/main>Malware-Deobfuscation-Lab-Reversing-Base64-XOR-Payload-Encryption</a>|
| HTTP Request Interception & Manipulation  |  <a href="https://github.com/Innuerr/picoCTF-Web-Exploitation/tree/main">picoCTF Web Exploitation</a>|


## Tools


🔍 Static Analysis
<div>
    <img src="https://img.shields.io/badge/-Ghidra-FE5F55?&style=for-the-badge&logo=ghidra&logoColor=white" />
    <img src="https://img.shields.io/badge/-IDA%20Free-5C2D91?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-PEStudio-333333?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-Cutter-FF6C37?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-CFF%20Explorer-006699?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-DIE%20(Detect%20It%20Easy)-990000?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-PE--BEAR-555555?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-PE--TREE-228B22?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-capa-4CAF50?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-FLOSS-795548?&style=for-the-badge" />
</div>

⚙️ Dynamic Analysis & Debugging
<div>
    <img src="https://img.shields.io/badge/-x64dbg-006400?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-ProcMon-444444?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-Process%20Explorer-003366?&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-API%20Monitoring-800080?&style=for-the-badge" />
</div>

🌐 Network Analysis
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-REMnux-DD0031?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-TCPView-000000?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-Nmap-004F9F?&style=for-the-badge&logo=nmap&logoColor=white" />
</div>

🌐 Web Security Testing
<div>
    <img src="https://img.shields.io/badge/-Burp%20Suite-FF6633?&style=for-the-badge&logo=burp-suite&logoColor=white" />
</div>
  
⚔️ Offensive Security & Penetration Testing  
<div>
    <img src="https://img.shields.io/badge/-Metasploit-007ACC?&style=for-the-badge&logo=metasploit&logoColor=white" />
    <img src="https://img.shields.io/badge/-searchsploit-FF0000?&style=for-the-badge" />
</div>
  
## Certifications

<div>
    <a href="https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/">
        <img src="https://img.shields.io/badge/-CEH-000000?&style=for-the-badge&logo=EC-Council&logoColor=white" />
    </a>
</div>

## Projects
### 1. Malware Analysis of Go-based Keylogger 
- **Description:** Reverse engineered a compact Go-based keylogger that exfiltrates kernel-level keystrokes. 
- **Techniques:** Traffic analysis, string deobfuscation, static binary inspection.
- **Outcome:** Confirmed the binary logged keystrokes and exfiltrated them via network traffic.
- [<a href="https://github.com/Innuerr/Malware-Analysis-of-Go-based-Keylogger/tree/main">Malware Analysis of Go-based Keylogger</a>]

### 2. Malicious Electron Application Analysis 
- **Description:** Dissected a malicious Electron app with insecure settings (`nodeIntegration: true`) that captured keystrokes and delivered payloads. 
- **Techniques:** ASAR unpacking (`npx @electron/asar extract`), script decoding, WebSocket communication analysis. 
- **Outcome:** Discovered keylogging functionality and attacker C2 communication over WebSockets.
- [<a href="https://github.com/Innuerr/Malicious-Electron-Application/tree/main">Malicious-Electron-Application</a>]

### 3. Malware Sandbox Evasion & Process Injection  
- **Description:** Investigated a malware sample that used sandbox evasion, process injection, and C2 communication.
- **Techniques:** x64dbg debugging, API tracing (`VirtualAlloc`, `CreateThread`).
- **Outcome:** Demonstrated how malware bypasses analysis environments and establishes remote control.
- [<a href="https://github.com/Innuerr/Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication/tree/main">Malware-Analysis-Lab-Sandbox-Evasion-Process-Injection-and-C2-Communication</a>]
 
### 4. Malware Deobfuscation Lab – Base64 + XOR  
- **Description:** Built a custom Python script to reverse Base64 and XOR encryption applied to a malicious payload.
- **Techniques:** Buffer decryption, automation scripting.
- **Outcome:** Successfully recovered plaintext shellcode, enabling further reverse engineering.
- [<a href= https://github.com/Innuerr/Malware-Deobfuscation-Lab-Reversing-Base64-XOR-Payload-Encryption/tree/main>Malware-Deobfuscation-Lab-Reversing-Base64-XOR-Payload-Encryption</a>]

### 5. Web Exploitation – picoCTF Challenges  
- **Description:** Solved web challenges involving logic bypasses and OTP manipulation.
- **Techniques:** Burp Suite-based request manipulation, web logic analysis.
- **Outcome:** Exploited poor validation to bypass OTP and extract application flags.
- [<a href="https://github.com/Innuerr/picoCTF-Web-Exploitation/tree/main">picoCTF Web Exploitation</a>]
