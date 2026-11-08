<div align="center">

# 🛡️ Md. Shihab Ahmed
### Cybersecurity Engineering Undergraduate • Systems & Secure Software Developer
**[University of Frontier Technology, Bangladesh (UFTB)](https://uftb.ac.bd/)**

[![GitHub Profile Views](https://komarev.com/ghpvc/?username=md-shihab-ahmed&color=00d2ff&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/md-shihab-ahmed)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Md._Shihab_Ahmed-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/md-shihab-ahmed-32b703438/)
[![Fiverr](https://img.shields.io/badge/Fiverr-shihab__55-10B981?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/shihab_55)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdshihabahmed14796178@gmail.com)

<p align="center">
  <em>"Security is not an afterthought or a plugin — it is an engineering discipline built from first principles."</em>
</p>

---

</div>

## 📌 Executive Summary & Philosophy

I am an undergraduate **Cybersecurity Engineering** student at UFTB with a relentless curiosity for how computing systems operate at their lowest levels and how modern distributed applications can be hardened against real-world threats.

While many developers begin by assembling pre-built components without understanding the underlying mechanics, my approach is grounded in fundamentals:
* **Understanding Memory & Execution:** Writing procedural C to master pointer safety, stack vs. heap allocations, and buffer protection.
* **Network Protocol Analysis:** Dissecting TCP/IP handshakes, packet headers, and routing behavior using Wireshark and Packet Tracer.
* **Proactive Application Defense:** Engineering full-stack web platforms with enterprise authentication (Argon2id, JWT), role-based isolation (RBAC), and direct mitigation of OWASP Top 10 vulnerabilities (SQLi, XSS, CSRF, IDOR).

I balance academic theory with concrete, verifiable engineering deliverables.

---

## 🛠️ Technical Competencies & Toolchain

<table>
  <tr>
    <th width="33%">🔐 Systems & Security</th>
    <th width="33%">🌐 Full-Stack & Web</th>
    <th width="34%">⚙️ Tooling & Protocols</th>
  </tr>
  <tr>
    <td valign="top">
      • <b>C Language</b> (Win32 API, File I/O, Pointers)<br/>
      • <b>Linux Systems</b> (Kali, Ubuntu, Bash CLI)<br/>
      • <b>Cryptographic Hashing</b> (FNV-1a, Argon2id)<br/>
      • <b>File Integrity Monitoring</b> (FIM)<br/>
      • <b>Vulnerability Auditing</b> (OWASP Top 10)<br/>
      • <b>Threat Analysis</b> (Nmap, Wireshark)
    </td>
    <td valign="top">
      • <b>Next.js 15</b> (App Router, Server Actions)<br/>
      • <b>React 19</b> & <b>TypeScript</b><br/>
      • <b>Tailwind CSS</b> (Mobile-First UI/UX)<br/>
      • <b>NestJS</b> (Modular Monolith, REST APIs)<br/>
      • <b>PostgreSQL 16+</b> & <b>Prisma ORM</b><br/>
      • <b>PWA Architecture</b> (Manifest, Workers)
    </td>
    <td valign="top">
      • <b>Git & GitHub</b> (Conventional Commits)<br/>
      • <b>Networking:</b> TCP/IP, OSI, Subnetting<br/>
      • <b>Security Headers:</b> CSP, HSTS, CORS<br/>
      • <b>Vercel CI/CD</b> & Cloud Deployments<br/>
      • <b>VS Code</b> & MinGW / GCC Toolchain<br/>
      • <b>Swagger / OpenAPI 3.1</b> Documentation
    </td>
  </tr>
</table>

---

## 🔬 Featured Engineering Deliverables

### 1. 🛡️ [SentinelC — Lightweight File Integrity Monitoring Engine](https://github.com/md-shihab-ahmed/SentinelC)
> **Technologies:** C Language, Windows Win32 API, FNV-1a Hashing, Binary File I/O  
> **Repository:** [github.com/md-shihab-ahmed/SentinelC](https://github.com/md-shihab-ahmed/SentinelC)

A native systems-programming security utility written in C to detect real-time file system tampering, unauthorized injections, or malicious modifications:
* **Baseline Cryptographic Database:** Computes and serializes file sizes and 32-bit FNV-1a hashes into a binary `baseline.db`.
* **State Change Classification:** Automatically detects and reports `[MATCH]`, `[MODIFIED]`, `[NEW FILE]`, and `[DELETED]` states across target directories.
* **Deterministic Event Audit Logging:** Maintains chronological security event logs for incident forensics.

---

### 2. 🌐 [EarnXpress — Full-Stack Crowdsourcing Task Marketplace](https://github.com/md-shihab-ahmed/earnxpress)
> **Technologies:** Next.js 15, React 19, TypeScript, Tailwind CSS, NestJS 10, PostgreSQL 16, Prisma ORM, Argon2id  
> **Status:** Production Deployed • Verified 28/28 Routes Passed (100% Audit)  
> 🔗 **Live Platform:** [https://earnxpress-marketplace.vercel.app](https://earnxpress-marketplace.vercel.app)  
> 🎬 **System Documentary:** [https://earnxpress-marketplace.vercel.app/documentary](https://earnxpress-marketplace.vercel.app/documentary)

An open, high-concurrency international microtask marketplace engineered with defense-in-depth principles:
* **Multi-Role Privilege Separation:** Isolated authenticated workflows for Workers (deliverable evidence lockers, milestone trackers) and Buyers (campaign creation wizard, review queues, deposit management).
* **Hardened Security Architecture:** Password security utilizing memory-hard `Argon2id` hashing, rate-limiting brute-force lockouts, and a completely cloaked administrative surface (`/admin` returns a genuine `404 Not Found`; private Founder console isolated at `/shihab-vault-7860`).
* **Double-Entry Simulated Escrow:** Built with integer USD cent accounting (`BigInt`) to prevent rounding vulnerabilities, backed by automated 72-hour review SLAs.
* **Progressive Web App (PWA):** Fully responsive mobile-first architecture tested across 28 production endpoints with zero console errors.

---

### 3. 💻 [C-Programming — Structured Systems & Algorithmic Practice](https://github.com/md-shihab-ahmed/C-Programming)
> **Technologies:** C Language, GCC Compiler, MinGW  
> **Repository:** [github.com/md-shihab-ahmed/C-Programming](https://github.com/md-shihab-ahmed/C-Programming)

A structured collection of 90+ algorithmic implementations documenting continuous academic rigor:
* **Memory & Pointer Logic:** Deep dive into pointer arithmetic, memory addressing, and array bounds safety.
* **Algorithmic Problem Solving:** Mathematical logic, number theory algorithms (GCD/LCM, Prime factorizations), Fibonacci sequences, and complex series summation.

---

## 📈 Activity & Engineering Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=md-shihab-ahmed&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=00d2ff&icon_color=00ff88" alt="Shihab's GitHub Metrics" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=md-shihab-ahmed&layout=compact&theme=tokyonight&hide_border=true&title_color=00d2ff" alt="Shihab's Top Languages" width="45%" />
</div>

---

## 🎯 Current Academic Roadmap & Research Goals

- [x] Systems Programming Foundations in C (Memory, File I/O, Win32 API)
- [x] File Integrity & Cryptographic Hashing Engine (`SentinelC`)
- [x] Full-Stack Secure Marketplace Architecture (`EarnXpress` Next.js 15 + NestJS)
- [ ] Computer Networking Deep Dive (Packet analysis, VLANs, Routing in Cisco Packet Tracer)
- [ ] Advanced Linux System Administration & Kernel Security Concepts
- [ ] Socket Programming in C (Custom multi-threaded TCP/IP server)
- [ ] Hands-on Red Team / Blue Team Virtual Labs (TryHackMe & PicoCTF)

---

## 📬 Let's Connect

I am actively open to **Cybersecurity Internships (AppSec, SOC, Penetration Testing)**, research collaborations, and open-source contributions:

* 🌐 **LinkedIn:** [linkedin.com/in/md-shihab-ahmed-32b703438](https://www.linkedin.com/in/md-shihab-ahmed-32b703438/)
* 💼 **Fiverr Profile:** [fiverr.com/shihab_55](https://www.fiverr.com/shihab_55)
* 📧 **Primary Email:** [mdshihabahmed14796178@gmail.com](mailto:mdshihabahmed14796178@gmail.com)
* 📍 **Location:** Bangladesh
