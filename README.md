<!--
  ATHARVA SAIL — GitHub Profile README  (v2)
  Repo name must be exactly: ATHARVASAIL
  Theme: ink #0b0c10 · crimson #d62828 · ember #f77f00 · bone #eae0d5
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0c10,50:6a040f,100:d62828&height=200&section=header&text=ATHARVA%20SAIL&fontSize=58&fontColor=EAE0D5&fontAlignY=36&animation=fadeIn&desc=VAPT%20Analyst%20%C2%B7%20Offensive%20Security&descSize=17&descAlignY=57" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1200&color=D62828&center=true&vCenter=true&width=780&height=55&lines=Web+%E2%80%A2+Mobile+%E2%80%A2+Network+%E2%80%A2+API+%E2%80%A2+LLM+Security;25%2B+web+apps+%7C+15%2B+networks+%7C+30%2B+reports+delivered;OWASP+%7C+PTES+%7C+NIST+aligned;I+break+it+before+someone+else+does." alt="typing" />

<a href="https://www.linkedin.com/in/atharvasail"><img src="https://img.shields.io/badge/LinkedIn-0b0c10?style=for-the-badge&logo=linkedin&logoColor=EAE0D5" /></a>
<a href="https://atharvasail.github.io"><img src="https://img.shields.io/badge/Portfolio-0b0c10?style=for-the-badge&logo=firefoxbrowser&logoColor=F77F00" /></a>
<a href="https://tryhackme.com/p/ATHARVASAIL"><img src="https://img.shields.io/badge/TryHackMe-0b0c10?style=for-the-badge&logo=tryhackme&logoColor=88CC14" /></a>
<img src="https://komarev.com/ghpvc/?username=ATHARVASAIL&style=for-the-badge&color=d62828&label=RECON+HITS" />

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[*]` Scan report

```console
$ nmap -sV -A atharva.sail

Starting Nmap ( https://github.com/ATHARVASAIL )
Host is up (0.0021s latency).

PORT      STATE     SERVICE        VERSION
443/tcp   open      vapt-analyst   full-scope security assessments
8080/tcp  open      web-vapt       SQLi, XSS, CSRF, SSRF, IDOR, business-logic
5555/tcp  open      mobile-vapt    Android/iOS · static + dynamic analysis
9000/tcp  open      network-vapt   enumeration -> exploitation
3000/tcp  open      api-vapt       authn bypass, BOLA, mass assignment
11434/tcp open      llm-vapt       prompt injection, data leakage
22/tcp    filtered  downtime       chess | sudoku | packet captures

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

<img src="https://img.shields.io/badge/Burp_Suite-0b0c10?style=flat-square&logo=burpsuite&logoColor=FF6633" />
<img src="https://img.shields.io/badge/Nmap-0b0c10?style=flat-square&logo=nmap&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/Wireshark-0b0c10?style=flat-square&logo=wireshark&logoColor=1679A7" />
<img src="https://img.shields.io/badge/Nessus-0b0c10?style=flat-square&logo=tenable&logoColor=00558C" />
<img src="https://img.shields.io/badge/MobSF-0b0c10?style=flat-square&logo=android&logoColor=3DDC84" />
<img src="https://img.shields.io/badge/Frida-0b0c10?style=flat-square&logo=frida&logoColor=F5A623" />
<img src="https://img.shields.io/badge/JADX-0b0c10?style=flat-square&logo=java&logoColor=E76F00" />
<img src="https://img.shields.io/badge/Apktool-0b0c10?style=flat-square&logo=androidstudio&logoColor=3DDC84" />
<img src="https://img.shields.io/badge/Postman-0b0c10?style=flat-square&logo=postman&logoColor=FF6C37" />
<img src="https://img.shields.io/badge/Kali-0b0c10?style=flat-square&logo=kalilinux&logoColor=557C94" />
<img src="https://img.shields.io/badge/Python-0b0c10?style=flat-square&logo=python&logoColor=3776AB" />
<img src="https://img.shields.io/badge/Bash-0b0c10?style=flat-square&logo=gnubash&logoColor=4EAA25" />

</td>
<td>

<img src="https://img.shields.io/badge/Active_Directory-0b0c10?style=flat-square&logo=microsoft&logoColor=00A4EF" />
<img src="https://img.shields.io/badge/BloodHound-0b0c10?style=flat-square&logo=hackthebox&logoColor=9FEF00" />
<img src="https://img.shields.io/badge/Cloud_Security-0b0c10?style=flat-square&logo=amazonwebservices&logoColor=FF9900" />
<img src="https://img.shields.io/badge/Ghidra-0b0c10?style=flat-square&logo=ghidra&logoColor=FF3B30" />
<img src="https://img.shields.io/badge/Docker-0b0c10?style=flat-square&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/OSCP_prep-0b0c10?style=flat-square&logo=offensivesecurity&logoColor=EAE0D5" />

</td>
<td>

<img src="https://img.shields.io/badge/Java-0b0c10?style=flat-square&logo=openjdk&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/C-0b0c10?style=flat-square&logo=c&logoColor=A8B9CC" />
<img src="https://img.shields.io/badge/Solidity-0b0c10?style=flat-square&logo=solidity&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/Flask-0b0c10?style=flat-square&logo=flask&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/React-0b0c10?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Firebase-0b0c10?style=flat-square&logo=firebase&logoColor=FFCA28" />
<img src="https://img.shields.io/badge/MySQL-0b0c10?style=flat-square&logo=mysql&logoColor=4479A1" />
<img src="https://img.shields.io/badge/Git-0b0c10?style=flat-square&logo=git&logoColor=F05032" />

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

</td>
<td width="50%" valign="top">

### 🕸️ [kompromap](https://github.com/ATHARVASAIL/kompromap)
`Python` · attack-path graph

Ingests scanner output and ranks compromise paths by **attacker effort per hop**,
not raw CVSS. FastAPI + PostgreSQL + NetworkX behind a React/Cytoscape graph.
Multi-engagement with full report generation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [WebGuard](https://github.com/ATHARVASAIL/WebGuard-Advanced_Web_Vulnerability_Scanner)
`Python` · vulnerability scanner

Detects SQLi, XSS, CSRF, SSRF and directory traversal, then emits PDF and JSON
reports with remediation guidance. Benchmarked against Burp Suite and OWASP ZAP.

</td>
<td width="50%" valign="top">

### ⛓️ [Evidence Management System](https://github.com/ATHARVASAIL/Evidence-Management-System)
`Solidity · IPFS · React`

Tamper-proof digital evidence custody. Hashes anchored on-chain, payloads on
IPFS — a chain of custody that can't be quietly rewritten.

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[#]` Telemetry

<div align="center">

<!-- Full dashboard — generated by .github/workflows/metrics.yml -->
<img src="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/main/metrics.svg" width="88%" alt="metrics" />

<br/><br/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ATHARVASAIL&show_icons=true&hide_border=true&bg_color=0b0c10&title_color=d62828&icon_color=f77f00&text_color=eae0d5&include_all_commits=true&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ATHARVASAIL&layout=compact&hide_border=true&bg_color=0b0c10&title_color=d62828&text_color=eae0d5&langs_count=8" />

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=ATHARVASAIL&bg_color=0b0c10&color=eae0d5&line=d62828&point=f77f00&area=true&area_color=6a040f&hide_border=true&custom_title=Contribution%20Activity" />

<!-- Snake — generated by .github/workflows/snake.yml -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/output/snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/ATHARVASAIL/ATHARVASAIL/output/snake.svg" width="96%" />
</picture>

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
| **50+ hands-on labs** | TryHackMe · HackTheBox · PortSwigger | ongoing |

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

## `[?]` Off duty

<div align="center">

<img src="https://img.shields.io/badge/Chess-0b0c10?style=for-the-badge&logo=chessdotcom&logoColor=81B64C" />
<img src="https://img.shields.io/badge/Sudoku-0b0c10?style=for-the-badge&logo=sudoku&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/Steam-0b0c10?style=for-the-badge&logo=steam&logoColor=EAE0D5" />
<img src="https://img.shields.io/badge/Spotify-0b0c10?style=for-the-badge&logo=spotify&logoColor=1DB954" />
<img src="https://img.shields.io/badge/HackTheBox-0b0c10?style=for-the-badge&logo=hackthebox&logoColor=9FEF00" />

</div>

<img src="https://raw.githubusercontent.com/Trinib/Trinib/main/images/line.gif" width="100%" />

<div align="center">

### `[~]` Open to VAPT roles & security engagements

<a href="https://www.linkedin.com/in/atharvasail"><img src="https://img.shields.io/badge/START_ENGAGEMENT-d62828?style=for-the-badge&logo=minutemailer&logoColor=EAE0D5" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:d62828,50:6a040f,100:0b0c10&height=130&section=footer" width="100%" />

</div>
