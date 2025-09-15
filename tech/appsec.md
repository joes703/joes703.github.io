---
title: "How to Get Into AppSec"
layout: default
---
# How to Get Into AppSec

## Section A — New to Tech (start here)

- **Productivity basics**  
  - Spreadsheets: formulas, pivot tables, charts  
  - Free: [Google Sheets Training](https://support.google.com/a/users/answer/9282959), [Microsoft Excel Training](https://support.microsoft.com/excel)

- **Git basics**  
  - Free: [GitHub Skills – Introduction to GitHub](https://skills.github.com/)

- **Programming intro (Python recommended)**  
  - [CS50’s Introduction to Programming with Python](https://cs50.harvard.edu/python/2022/)  
  - Core topics: variables, loops, functions, lists/dicts, exceptions, reading stack traces

- **Web fluency**  
  - HTTP request/response, status codes, headers  
  - Cookies, sessions, JSON, DOM basics  
  - Free: [MDN Web Docs](https://developer.mozilla.org/en-US/) (start with HTTP, web security, and JavaScript basics)

- **SQL basics**  
  - FreeCodeCamp: [SQL Tutorial – Full Database Course for Beginners](https://www.youtube.com/watch?v=HXV3zeQKqGY)

- **Small project**  
  - Build a simple CRUD app (Python + SQLite or Node + SQLite)

---

## Section B — Already Write Software (or after Section A)

- **Engineering literacy**  
  - Frontend vs backend vs APIs  
  - Production vs dev vs staging (deployment basics)  
  - CI/CD concepts

- **Security mindset**  
  - CIA triad (confidentiality, integrity, availability)

---

## Section C — Threat Modeling (core AppSec skill)

- **What to learn**  
  - [Threat Modeling Manifesto](https://threatmodelingmanifesto.org/)  
  - *Threat Modeling: Designing for Security* (Adam Shostack)  
  - [OWASP Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html)  
  - Tools: [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/), [Microsoft Threat Modeling Tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool)

- **How to do it**  
  1. Diagram system (DFD: processes, data stores, arrows)  
  2. Identify assets (user data, money, secrets)  
  3. Enumerate threats (STRIDE: Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege)  
  4. Prioritize (likelihood + impact)  
  5. Mitigate (auth, validation, rate limits, monitoring)  
  6. Review yourself (did you miss obvious paths?)

- **Practice**  
  - Threat model your CRUD app  
  - Pick a public app → sketch flows + threats  
  - Map threats to OWASP Top 10 categories

- **Portfolio deliverable**  
  - Diagram + list of threats (mapped to STRIDE) + mitigations + short README

---

## Section D — Core AppSec Syllabus

- **OWASP Top 10** — learn each vuln as WHAT / HOW / DEFEND  
  - Broken Access Control  
  - Cryptographic Failures  
  - Injection  
  - Insecure Design  
  - Security Misconfiguration  
  - Vulnerable/Outdated Components  
  - Identification & Authentication Failures  
  - Software & Data Integrity Failures  
  - Logging & Monitoring Failures  
  - SSRF / Other

- **Tools**  
  - Browser DevTools (network tab, storage, console)  
  - Burp Suite Community Edition  
  - OWASP ZAP  
  - GitHub/GitLab PR review workflow

---

## Section E — Labs (do these in order)

1. [PortSwigger Web Security Academy](https://portswigger.net/web-security)  
2. [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)  
3. [Google Gruyere](http://google-gruyere.appspot.com/)  
4. [WebGoat](https://owasp.org/www-project-webgoat/)  
5. [DVWA](http://www.dvwa.co.uk/)  
6. [Mutillidae](https://github.com/webpwnized/mutillidae)  
7. [Cryptopals](https://cryptopals.com/) (crypto challenges)  
8. [PentesterLab free exercises](https://pentesterlab.com/exercises)  
9. [TryHackMe free rooms](https://tryhackme.com/) — “Pre Security” + “Web Fundamentals”  
10. [HackTheBox free tier](https://www.hackthebox.com/)  
11. [PicoCTF](https://picoctf.org/)

---

## Section F — Code Review & Open Source Tools

- **Static analysis / SAST**  
  - [Semgrep](https://semgrep.dev/)  
  - [CodeQL](https://codeql.github.com/)  
  - [Bandit](https://bandit.readthedocs.io/en/latest/) (Python)  
  - [FindSecBugs](https://find-sec-bugs.github.io/) (Java)

- **Dependency / SCA**  
  - [OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/)  
  - [Trivy](https://aquasecurity.github.io/trivy/)  
  - [retire.js](https://retirejs.github.io/retire.js/)

- **Secrets detection**  
  - [Gitleaks](https://github.com/gitleaks/gitleaks)  
  - [git-secrets](https://github.com/awslabs/git-secrets)

- **Workflow**  
  - Pre-commit hooks, Dependabot, GitHub Actions + CodeQL scan

---

## Section G — Build & Break (capstone project)

- Build a small app with: auth + sessions + DB + REST API + frontend  
- Intentionally add: SQLi, XSS, auth bypass  
- Exploit, then fix  
- Write up steps → publish on GitHub/blog

---

## Section H — Practice & Portfolio

- Publish 3+ lab reports (PortSwigger / Juice Shop / PentesterLab)  
- GitHub repo: CRUD app, threat model, security tool configs  
- Optional: responsible disclosure write-up

---

## Section I — Next Steps

- Optional certs: Security+ early, OSWE/OSCP later  
- Target roles: AppSec engineer, secure code reviewer, security-minded developer  
- Continuous learning: follow OWASP, AppSec blogs, r/AskNetsec, conferences

---

## Section J — How AI Can Help You

- Debugging: explain stack traces, error messages  
- Study mode: turn notes into flashcards, generate practice quizzes  
- Summaries: OWASP pages, RFCs, docs  
- Mentor mode: ask “what am I missing?” during labs  
- Use AI to **check your thinking**, not to hand you answers