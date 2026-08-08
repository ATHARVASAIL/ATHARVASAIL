<!--
  ATHARVA SAIL — GitHub Profile README  (v3)
  Repo name must be exactly: ATHARVASAIL
  Palette: void #0a0e1a · deep #003554 · signal #00b4ff · ion #22d3ee · bone #e6edf3
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,45:003554,100:00b4ff&height=200&section=header&text=ATHARVA%20SAIL&fontSize=58&fontColor=e6edf3&fontAlignY=36&animation=fadeIn&desc=VAPT%20Analyst%20%C2%B7%20Offensive%20Security&descSize=17&descAlignY=57" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1200&color=00B4FF&center=true&vCenter=true&width=780&height=55&lines=%3E+initializing+operator+profile...;Web+%E2%80%A2+Mobile+%E2%80%A2+Network+%E2%80%A2+API+%E2%80%A2+LLM+security;25%2B+web+apps+%7C+15%2B+networks+%7C+30%2B+reports+delivered;I+break+it+before+someone+else+does." alt="typing" />

<a href="https://www.linkedin.com/in/atharva-sail"><img src="https://img.shields.io/badge/LinkedIn-0a0e1a?style=for-the-badge&logo=linkedin&logoColor=00B4FF" /></a>
<a href="https://atharvasail.github.io"><img src="https://img.shields.io/badge/Portfolio-0a0e1a?style=for-the-badge&logo=firefoxbrowser&logoColor=22D3EE" /></a>
<a href="https://tryhackme.com/p/kirahack10669"><img src="https://img.shields.io/badge/TryHackMe-0a0e1a?style=for-the-badge&logo=tryhackme&logoColor=00B4FF" /></a>
<a href="https://profile.hackthebox.com/profile/019fe129-f91a-73fb-b789-334a41568712"><img src="https://img.shields.io/badge/HackTheBox-0a0e1a?style=for-the-badge&logo=hackthebox&logoColor=22D3EE" /></a>
<a href="https://github.com/ATHARVASAIL?tab=repositories"><img src="https://komarev.com/ghpvc/?username=ATHARVASAIL&style=for-the-badge&color=00b4ff&label=RECON+HITS" /></a>

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[*]` Scan report

```console
┌──[ RECON ]──────────────────────────────────────────────────────────────┐
│  $ nmap -sV -A --script vuln atharva.sail                               │
└─────────────────────────────────────────────────────────────────────────┘

Host is up (0.0021s latency).

PORT      STATE     SERVICE        VERSION
443/tcp   open      vapt-analyst   full-scope security assessments
8080/tcp  open      web-vapt       SQLi, XSS, CSRF, SSRF, IDOR, business-logic
5555/tcp  open      mobile-vapt    Android/iOS · static + dynamic analysis
9000/tcp  open      network-vapt   enumeration -> exploitation
3000/tcp  open      api-vapt       authn bypass, BOLA, mass assignment
11434/tcp open      llm-vapt       prompt injection, data leakage
22/tcp    filtered  downtime       chess | sudoku | packet captures

┌──[ SIGNAL ]─────────────────────────────────────────────────────────────┐
│  web       ████████████████████░░░░   api       ██████████████████░░░░░░ │
│  network   ██████████████████░░░░░░   llm       ████████████████░░░░░░░░ │
│  mobile    ██████████████████░░░░░░   reporting ██████████████████████░░ │
└─────────────────────────────────────────────────────────────────────────┘

Service Info: OWASP Top 10, MASVS, PTES, NIST
Nmap done: 1 host up — findings triaged, reported, retested.
```

I map attack surface, chain low-severity findings into real compromise paths, and
write the report that actually gets the bug fixed. Between engagements I build the
tooling I wish I'd had on the last one.

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[>]` Arsenal

<table>
<tr>
<th width="34%">Daily drivers</th>
<th width="33%">Currently loading</th>
<th width="33%">In the armory</th>
</tr>
<tr valign="top">
<td>

<a href="https://portswigger.net/burp"><img src="https://img.shields.io/badge/Burp_Suite-0a0e1a?style=flat-square&logo=burpsuite&logoColor=FF6633" /></a>
<a href="https://nmap.org"><img src="https://img.shields.io/badge/Nmap-0a0e1a?style=flat-square&logo=nmap&logoColor=00B4FF" /></a>
<a href="https://www.wireshark.org"><img src="https://img.shields.io/badge/Wireshark-0a0e1a?style=flat-square&logo=wireshark&logoColor=1679A7" /></a>
<a href="https://www.tenable.com/products/nessus"><img src="https://img.shields.io/badge/Nessus-0a0e1a?style=flat-square&logo=tenable&logoColor=00558C" /></a>
<a href="https://github.com/MobSF/Mobile-Security-Framework-MobSF"><img src="https://img.shields.io/badge/MobSF-0a0e1a?style=flat-square&logo=android&logoColor=3DDC84" /></a>
<a href="https://frida.re"><img src="https://img.shields.io/badge/Frida-0a0e1a?style=flat-square&logo=frida&logoColor=F5A623" /></a>
<a href="https://github.com/skylot/jadx"><img src="https://img.shields.io/badge/JADX-0a0e1a?style=flat-square&logo=java&logoColor=E76F00" /></a>
<a href="https://apktool.org"><img src="https://img.shields.io/badge/Apktool-0a0e1a?style=flat-square&logo=androidstudio&logoColor=3DDC84" /></a>
<a href="https://www.postman.com"><img src="https://img.shields.io/badge/Postman-0a0e1a?style=flat-square&logo=postman&logoColor=FF6C37" /></a>
<a href="https://www.kali.org"><img src="https://img.shields.io/badge/Kali-0a0e1a?style=flat-square&logo=kalilinux&logoColor=557C94" /></a>
<a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-0a0e1a?style=flat-square&logo=python&logoColor=3776AB" /></a>
<a href="https://www.gnu.org/software/bash/"><img src="https://img.shields.io/badge/Bash-0a0e1a?style=flat-square&logo=gnubash&logoColor=4EAA25" /></a>

</td>
<td>

<a href="https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview"><img src="https://img.shields.io/badge/Active_Directory-0a0e1a?style=flat-square&logo=microsoft&logoColor=00A4EF" /></a>
<a href="https://github.com/SpecterOps/BloodHound"><img src="https://img.shields.io/badge/BloodHound-0a0e1a?style=flat-square&logo=hackthebox&logoColor=9FEF00" /></a>
<a href="https://aws.amazon.com/security/"><img src="https://img.shields.io/badge/Cloud_Security-0a0e1a?style=flat-square&logo=amazonwebservices&logoColor=FF9900" /></a>
<a href="https://ghidra-sre.org"><img src="https://img.shields.io/badge/Ghidra-0a0e1a?style=flat-square&logo=ghidra&logoColor=FF3B30" /></a>
<a href="https://www.docker.com"><img src="https://img.shields.io/badge/Docker-0a0e1a?style=flat-square&logo=docker&logoColor=2496ED" /></a>
<a href="https://www.offsec.com/courses/pen-200/"><img src="https://img.shields.io/badge/OSCP_prep-0a0e1a?style=flat-square&logoColor=e6edf3" /></a>

</td>
<td>

<a href="https://openjdk.org"><img src="https://img.shields.io/badge/Java-0a0e1a?style=flat-square&logo=openjdk&logoColor=e6edf3" /></a>
<a href="https://en.cppreference.com/w/c"><img src="https://img.shields.io/badge/C-0a0e1a?style=flat-square&logo=c&logoColor=A8B9CC" /></a>
<a href="https://soliditylang.org"><img src="https://img.shields.io/badge/Solidity-0a0e1a?style=flat-square&logo=solidity&logoColor=e6edf3" /></a>
<a href="https://flask.palletsprojects.com"><img src="https://img.shields.io/badge/Flask-0a0e1a?style=flat-square&logo=flask&logoColor=e6edf3" /></a>
<a href="https://react.dev"><img src="https://img.shields.io/badge/React-0a0e1a?style=flat-square&logo=react&logoColor=61DAFB" /></a>
<a href="https://firebase.google.com"><img src="https://img.shields.io/badge/Firebase-0a0e1a?style=flat-square&logo=firebase&logoColor=FFCA28" /></a>
<a href="https://www.mysql.com"><img src="https://img.shields.io/badge/MySQL-0a0e1a?style=flat-square&logo=mysql&logoColor=4479A1" /></a>
<a href="https://git-scm.com"><img src="https://img.shields.io/badge/Git-0a0e1a?style=flat-square&logo=git&logoColor=F05032" /></a>

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[+]` Field record

Live client engagements — not lab exercises.

| Assessment | Volume | Representative findings |
| :--- | :---: | :--- |
| 🌐 **Web Application VAPT** | `25+` | SQLi, XSS, CSRF, SSRF, IDOR, business logic |
| 📱 **Mobile VAPT (Android/iOS)** | `10+` | Insecure data storage, broken authentication |
| 🛰️ **Network VAPT** | `15+` | Service enumeration → exploitation of high-risk hosts |
| 🔌 **API Security Testing** | `8+` | Authentication bypass, broken object-level authz |
| 🤖 **LLM Security Testing** | `live` | Prompt injection, sensitive data leakage |
| 📄 **Reports delivered** | `30+` | CVSS, PoC, remediation — 90%+ fix rate on retest |

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[!]` Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🐚 [greysh3ll](https://github.com/ATHARVASAIL/greysh3ll)
`JavaScript` · engagement console

512-case VAPT methodology console across 10 domains — network, web, API, LLM,
cloud, mobile, thick client, WiFi, source review, social engineering. Imports
Nmap/Nuclei/Burp output, links findings into attack chains, holds evidence
attachments. Fully client-side, zero backend.

<a href="https://github.com/ATHARVASAIL/greysh3ll"><img src="https://img.shields.io/badge/View_repo-0a0e1a?style=flat-square&logo=github&logoColor=00B4FF" /></a>

</td>
<td width="50%" valign="top">

### 🕸️ [kompromap](https://github.com/ATHARVASAIL/kompromap)
`Python` · attack-path graph

Ingests scanner output and ranks compromise paths by **attacker effort per hop**,
not raw CVSS. FastAPI + PostgreSQL + NetworkX behind a React/Cytoscape graph.
Multi-engagement with full report generation.

<a href="https://github.com/ATHARVASAIL/kompromap"><img src="https://img.shields.io/badge/View_repo-0a0e1a?style=flat-square&logo=github&logoColor=00B4FF" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [WebGuard](https://github.com/ATHARVASAIL/WebGuard-Advanced_Web_Vulnerability_Scanner)
`Python` · vulnerability scanner

Detects SQLi, XSS, CSRF, SSRF and directory traversal, then emits PDF and JSON
reports with remediation guidance. Benchmarked against Burp Suite and OWASP ZAP.

<a href="https://github.com/ATHARVASAIL/WebGuard-Advanced_Web_Vulnerability_Scanner"><img src="https://img.shields.io/badge/View_repo-0a0e1a?style=flat-square&logo=github&logoColor=00B4FF" /></a>

</td>
<td width="50%" valign="top">

### ⛓️ [Evidence Management System](https://github.com/ATHARVASAIL/Evidence-Management-System)
`Solidity · IPFS · React`

Tamper-proof digital evidence custody. Hashes anchored on-chain, payloads on
IPFS — a chain of custody that can't be quietly rewritten.

<a href="https://github.com/ATHARVASAIL/Evidence-Management-System"><img src="https://img.shields.io/badge/View_repo-0a0e1a?style=flat-square&logo=github&logoColor=00B4FF" /></a>

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[#]` Telemetry

<div align="center">

<a href="https://github.com/ATHARVASAIL?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0a0e1a?style=for-the-badge&logo=github&logoColor=00B4FF" /></a>
<a href="https://github.com/ATHARVASAIL?tab=stars"><img src="https://img.shields.io/badge/Starred-0a0e1a?style=for-the-badge&logo=github&logoColor=22D3EE" /></a>
<a href="https://github.com/ATHARVASAIL?tab=followers"><img src="https://img.shields.io/badge/Followers-0a0e1a?style=for-the-badge&logo=github&logoColor=00B4FF" /></a>

<br/><br/>

<!-- Dashboard — generated daily by .github/workflows/metrics.yml -->
<a href="https://github.com/ATHARVASAIL?tab=repositories">
  <img src="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/main/metrics.svg" width="88%" alt="metrics dashboard" />
</a>

<br/><br/>

<a href="https://github.com/ATHARVASAIL">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=ATHARVASAIL&bg_color=0a0e1a&color=e6edf3&line=00b4ff&point=22d3ee&area=true&area_color=003554&hide_border=true&custom_title=Contribution%20Activity" alt="activity graph" />
</a>

<!-- Snake — generated every 12h by .github/workflows/snake.yml -->
<a href="https://github.com/ATHARVASAIL">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/output/snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/output/snake.svg" width="96%" />
  </picture>
</a>

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[✓]` Credentials

<div align="center">

| Certification | Issuer | Year |
| :--- | :--- | :---: |
| CyberOps & Professional Edge Program | — | 2025 |
| Tata Cybersecurity Analyst Simulation | Forage | 2025 |
| Cyber Security Internship | — | 2024 |
| Python Bootcamp | Udemy | 2024 |
| Ethical Hacking Certification | NPTEL | 2023 |
| **50+ hands-on labs** | [TryHackMe](https://tryhackme.com/p/kirahack10669) · [HackTheBox](https://profile.hackthebox.com/profile/019fe129-f91a-73fb-b789-334a41568712) · [PortSwigger](https://portswigger.net/web-security) | ongoing |

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[?]` Off duty

<div align="center">

<a href="https://www.chess.com/member/kira10669"><img src="https://img.shields.io/badge/Chess-0a0e1a?style=for-the-badge&logo=chessdotcom&logoColor=81B64C" /></a>
<a href="https://sudoku.com"><img src="https://img.shields.io/badge/Sudoku-0a0e1a?style=for-the-badge&logoColor=e6edf3" /></a>
<a href="https://portswigger.net/web-security"><img src="https://img.shields.io/badge/PortSwigger_Labs-0a0e1a?style=for-the-badge&logo=burpsuite&logoColor=FF6633" /></a>

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

<div align="center">

### `[~]` Open to VAPT roles & security engagements

<a href="https://www.linkedin.com/in/atharva-sail"><img src="https://img.shields.io/badge/START_ENGAGEMENT-00b4ff?style=for-the-badge&logo=minutemailer&logoColor=0a0e1a" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4ff,55:003554,100:0a0e1a&height=130&section=footer" width="100%" />

</div>