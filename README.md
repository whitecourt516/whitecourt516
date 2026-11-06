### Hi, I'm Eddie 👋

Entry-level security analyst. **CompTIA Security+** certified, top 1% on TryHackMe, and I build tools in Python with security designed in from the start.

I'm looking for a **SOC Analyst** or junior security role, remote, hybrid, or on-site in the Pittsburgh area, and I'm open to relocating.

---

#### 🔐 Featured project: [PocketAI](https://github.com/whitecourt516/PocketAI)

A fully offline AI desktop assistant (Python, Electron, Docker, local LLM) that can run commands and edit files, but only with my explicit approval.

- **Approval gate and audit log.** Every AI-proposed action needs a y/n and is written to an append-only JSON Lines log.
- **Audited my own code.** The command filter blocked only 1 of 10 destructive test commands. I replaced substring matching with `shlex` parsing and closed a path that exposed the `.env` secrets file.
- **Found my own network exposure.** The local LLM API had no authentication and was published on every interface through Docker Compose. I restricted it to loopback and verified the fix from the LAN.

---

#### 🛠️ Skills

**Security operations:** alert triage, log analysis, phishing analysis, incident response, MITRE ATT&CK
**Tools (lab experience):** Splunk, Wireshark, CyberChef, Sysmon, Windows Event Logs
**Application security:** input validation, command-injection prevention, prompt-injection mitigation, secrets handling
**Systems:** Linux, Windows, WSL2, Docker and Docker Compose, Git
**Languages:** Python, JavaScript, PowerShell

---

#### 📈 Training

- CompTIA Security+ (SY0-701), October 2026
- TryHackMe SOC Level 1 and Cyber Security 101 paths, Legend rank (top 1%): [tryhackme.com/p/whitecourt516](https://tryhackme.com/p/whitecourt516)

---

#### 📫 Connect

[LinkedIn](https://www.linkedin.com/in/edward-jeunelot-938057168/) · [TryHackMe](https://tryhackme.com/p/whitecourt516)
