# 🛡️ 28-Week Full-Time Application Security Engineering Plan

> **Intensive journey to Security Engineering through systematic, hands-on learning**

[![Duration](https://img.shields.io/badge/duration-28%20weeks-blue?style=flat-square)](https://github.com/fosres/AppSec-Plan)
[![Hours](https://img.shields.io/badge/total%20hours-1,120-green?style=flat-square)](https://github.com/fosres/AppSec-Plan)
[![Intensity](https://img.shields.io/badge/weekly%20commitment-40%20hours-orange?style=flat-square)](https://github.com/fosres/AppSec-Plan)

---

## 📋 Table of Contents

* [Overview](#-overview)
* [Why This Plan?](#-why-this-plan)
* [Background](#-background)
* [Learning Objectives](#-learning-objectives)
* [28-Week Breakdown](#-28-week-breakdown)
* [Resources & Books](#-resources--books)
* [Portfolio Goals](#-portfolio-goals)
* [Connect With Me](#-connect-with-me)

---

## 🎯 Overview

This repository documents my **28-week full-time intensive journey** to transition into Application Security Engineering. The curriculum combines offensive security skills (web exploitation, API security) with defensive engineering (SAST/DAST, CI/CD security) to build comprehensive AppSec expertise.

**Timeline:** 28 weeks (1,120 total hours)  
**Commitment:** 40 hours/week (full-time study)  
**Target:** Remote AppSec Engineer role  
**Lab Coverage:** 211/211 PortSwigger labs (100% completion)

---

## 💡 Why This Plan?

Most AppSec engineers come from either:

1. **Offensive security** (pentesters learning to build) → Strong exploitation, weak development
2. **Software engineering** (developers learning security) → Strong development, weak security mindset

**My advantage:** Combining enterprise-scale threat modeling experience with modern AppSec offensive skills creates a rare profile that understands both architecture-level security AND real-world exploitation.

### Unique Differentiators

✅ **Enterprise Threat Modeling at Scale:** Documented 553+ threats using STRIDE methodology (65.83% of database coverage)  
✅ **Reusable Security Frameworks:** Created threat model templates used by 100+ engineers  
✅ **Systems Programming Background:** C/C++/Golang experience provides deep understanding of memory safety, performance implications, and low-level security concepts  
✅ **Cryptographic Implementation:** Implemented XMSS signatures, ChaCha20 encryption, Argon2 KDFs  
✅ **Public Learning Journey:** Documenting entire transition through blog posts and open-source exercises

---

## 🔍 Background

### Security Software Engineering Experience

* **Threat Modeling Engineer:** Systematic security analysis at enterprise scale
* **Scale Achievement:** 553+ documented threats representing 65.83% of organizational threat modeling database
* **Framework Development:** Created reusable threat model templates adopted by 100+ engineers
* **Methodologies:** STRIDE, attack trees, data flow diagrams, security requirements derivation

### Technical Foundation

* **Languages:** C (primary), C++, Golang, Python (advancing to mastery)
* **Security Training:** Cryptography fundamentals, secure coding principles
* **Cryptography:** Implemented XMSS post-quantum signatures, ChaCha20 stream cipher, Argon2 KDFs

---

## 🎓 Learning Objectives

By Week 28, I will have mastered:

### Technical Skills

* **Web Security:** Complete OWASP Top 10, **all 211 PortSwigger labs** across every vulnerability category
* **API Security:** REST, GraphQL, gRPC security testing, OAuth 2.0, JWT, modern API patterns
* **Authentication/Authorization:** OAuth 2.0, JWT, session management, MFA, RBAC/ABAC implementations
* **Security Automation:** SAST/DAST tools (Semgrep, Bandit, OWASP ZAP), custom rules, CI/CD integration
* **Cloud Security:** AWS (IAM, S3, Lambda), Kubernetes (RBAC, network policies), IaC scanning
* **DevSecOps:** GitHub Actions/GitLab CI security, HashiCorp Vault, supply chain security, policy-as-code
* **Python Mastery:** Production-quality security tools, async patterns, advanced OOP, comprehensive testing

### Portfolio Deliverables

* **25+ Production Security Tools:** Complete toolkit including SQL injection scanner, XSS payload generator, OAuth analyzer, CSRF PoC generator, SAST dashboard, API scanner, vulnerability aggregator, AWS security scanner, GraphQL testing suite, async concurrent scanner, and more
* **26+ Blog Posts:** Weekly technical deep-dives published on [dev.to/fosres](https://dev.to/fosres) (1 post per week)
* **15+ P2P Exercises:** LeetCode-style secure coding challenges with 500+ comprehensive test cases (part of larger open-source project to curate secure code datasets for AI training)
* **Portfolio Website:** Professional showcase of all projects and technical capabilities
* **System Design Expertise:** STRIDE-based threat modeling, secure architecture design, AppSec interview mastery

---

## 📅 28-Week Breakdown

### Phase 1: Foundation (Weeks 1-3, 120 hours)

**Focus:** Python fundamentals + SQL injection mastery

* **Week 1:** Python Fundamentals & SQL Injection Foundation (40 hours)
	+ Python Workout Ch 1-2 COMPLETE, Effective Python Items 1-10 REQUIRED
	+ OWASP Top 10 2021, PortSwigger SQL Injection complete guide
	+ SQLBolt (18 lessons) + PortSwigger SQLi labs (15 labs)
	+ Build 3 tools: password validator with entropy, SQLi pattern recognizer (50+ patterns), vulnerable Flask app
	+ **Deliverable:** 3 tools, 15 labs (15/211), blog post, Python 6/10

* **Week 2:** Strings, Lists & Advanced SQL Injection (40 hours)
	+ Python Workout Ch 3-4 COMPLETE, Effective Python Items 11-20 REQUIRED
	+ Secure by Design Ch 1-3, API Security in Action Ch 2
	+ Build 3 tools: SQLi code review scanner (AST-based), JWT security analyzer, input validation library
	+ PortSwigger SQLi advanced (15 labs including UNION attacks)
	+ **Deliverable:** 6 tools total, 30 labs (30/211), 2 blogs, Python 7/10

* **Week 3:** Dictionaries, Sets & Burp Suite Mastery (40 hours)
	+ Python Workout Ch 5 COMPLETE, Effective Python Items 21-30 REQUIRED
	+ API Security in Action Ch 1-3, Burp Suite complete documentation
	+ Build advanced SQLi detector with dict/set deduplication, Burp Suite extension
	+ PortSwigger XSS (15 labs: reflected/stored/DOM)
	+ **Deliverable:** 7 tools + Burp extension, 45 labs, 3 blogs, Burp proficient, Python 7.5/10

### Phase 2: Blind SQL Injection & XSS Mastery (Weeks 4-5, 80 hours)

**Focus:** Blind SQLi techniques, XSS deep dive

* **Week 4:** Files, Context Managers & Blind SQL Injection Mastery (40 hours)
	+ Python Workout Ch 6 COMPLETE, Effective Python Items 31-40 REQUIRED
	+ Hacking APIs Ch 1-3, PortSwigger Blind SQLi MASTERY
	+ Build production blind SQLi framework: Boolean exploiter, time-based detector, automated data exfiltration
	+ PortSwigger blind SQLi intensive (15 labs including OAST)
	+ **Deliverable:** Advanced blind SQLi framework, 60 labs, 4 blogs, SQL MASTERY, Python 8/10

* **Week 5:** Functions, Decorators & XSS Deep Dive (40 hours)
	+ Python Workout Ch 7 COMPLETE, Effective Python Items 41-50 REQUIRED
	+ Full Stack Python Security Ch 1-3, PortSwigger XSS advanced techniques
	+ Build XSS exploitation framework with context-aware payloads
	+ PortSwigger XSS advanced (15 labs), CSRF (10 labs)
	+ **Deliverable:** XSS framework, 85 labs, 5 blogs, XSS/CSRF mastery, Python 8.5/10

### Phase 3: SSRF & Authentication (Week 6, 40 hours)

**Focus:** SSRF exploitation, OAST techniques

* **Week 6:** SSRF Exploitation & Burp Collaborator Mastery (40 hours)
	+ Python Workout Ch 8 partial, Effective Python Items 51-60 REQUIRED
	+ Hacking APIs Ch 8-9, PortSwigger SSRF complete guide
	+ Build SSRF scanner with Burp Collaborator integration
	+ PortSwigger SSRF (15 labs), XXE (10 labs)
	+ **Deliverable:** SSRF scanner, Burp Collaborator automation, 110 labs, 6 blogs, Phase 2 complete

### Phase 4: Authorization & Business Logic (Week 7, 40 hours)

**Focus:** IDOR, BOLA, privilege escalation

* **Week 7:** Authorization Exploitation & Business Logic Flaws (40 hours)
	+ Python Workout remainder, advanced list/dict/set comprehensions
	+ PortSwigger Access Control complete, Business Logic, Hacking APIs Ch 10
	+ Build authorization toolkit: IDOR detector, privilege escalation checker, A-B testing logic
	+ PortSwigger access control (15 labs) + business logic (10 labs)
	+ **Deliverable:** Authorization toolkit, 130 labs, 7 blogs, Phase 2 complete

### Phase 5: OAuth & JWT Security (Weeks 8-9, 80 hours)

**Focus:** OAuth 2.0, JWT vulnerabilities

* **Week 8:** Modules, Packages & OAuth 2.0 Deep Dive (40 hours)
	+ Python Workout Ch 8 COMPLETE, Effective Python Items 61-70 REQUIRED
	+ API Security in Action Ch 6-7 (JWT/JOSE, OAuth2 flows, PKCE), Full Stack Python Security Ch 11
	+ Build OAuth analyzer package: token inspection, misconfiguration detection
	+ PortSwigger OAuth (10 labs) + JWT (10 labs)
	+ **Deliverable:** OAuth analyzer, JWT decoder, 150 labs, 8 blogs

* **Week 9:** OOP Part 1 & Complete Authentication System (40 hours)
	+ Python Workout Ch 9, Effective Python Items 71-80 REQUIRED
	+ Full Stack Python Security Ch 7-9 (sessions, authentication, passwords), API Security in Action Ch 4
	+ Build secure authentication module: User class, Session class, AuthManager, MFA integration
	+ PortSwigger Authentication advanced (10 labs)
	+ **Deliverable:** Authentication module with MFA, 160 labs, 9 blogs

### Phase 6: SAST & CI/CD Security (Weeks 10-13, 160 hours)

**Focus:** Security automation, SAST tools, CI/CD hardening

* **Week 10:** OOP Part 2 & RBAC/ABAC Implementation (40 hours)
	+ Advanced OOP patterns, Python Workout Ch 10-11
	+ API Security in Action Ch 8-9 (RBAC, ABAC, capability-based security)
	+ Build RBAC/ABAC demonstration framework
	+ Create 5 P2P authentication/authorization exercises
	+ **Deliverable:** RBAC framework, 5 P2P exercises (150+ tests), 10 blogs

* **Week 11:** Iterators/Generators & SAST Tools (40 hours)
	+ Advanced iteration patterns, custom generators for security
	+ Semgrep documentation, Bandit, OWASP Code Review Guide
	+ Build SAST orchestrator with custom Semgrep rules (15+)
	+ OWASP Juice Shop (20 challenges) + PortSwigger WebSockets (5 labs)
	+ **Deliverable:** SAST orchestrator, 15 Semgrep rules, 170 labs, 11 blogs

* **Week 12:** Async Foundations & CI/CD Security (40 hours)
	+ asyncio basics, async/await patterns
	+ GitHub Actions security, GitLab CI/CD, Pre-commit framework
	+ Build CI/CD scanner: analyzes workflows, detects insecure patterns
	+ CI/CD security implementation + PortSwigger Cache Poisoning (5 labs)
	+ **Deliverable:** CI/CD scanner, secure workflows, 175 labs, 12 blogs

* **Week 13:** Security Framework Dashboard & Tool Integration (40 hours)
	+ Advanced Python patterns, concurrent programming
	+ OWASP ZAP API scanning, Nuclei templates, Hacking APIs Ch 4
	+ Build security dashboard: SAST/DAST/dependency/secret scanning aggregation
	+ PortSwigger HTTP Request Smuggling (10 labs)
	+ **Deliverable:** Security dashboard v1.0, 185 labs, 13 blogs, Phase 4 complete

### Phase 7: API Security & Research (Weeks 14-15, 80 hours)

**Focus:** API scanner development, PyJWT audit

* **Week 14:** Advanced Iteration & API Security Scanner (40 hours)
	+ Master itertools module, custom security-focused iterators
	+ Hacking APIs Ch 5-7, OWASP API Security Top 10 full review
	+ Build API scanner: endpoint discovery, parameter fuzzing, auth bypass, rate limit detection
	+ PortSwigger API Testing (10 labs) + Business Logic (5 labs)
	+ **Deliverable:** API scanner v1.0, 200 labs, 14 blogs

* **Week 15:** PyJWT Security Audit & CVE Research Methodology (40 hours)
	+ Advanced data structures, Python security review
	+ Hacking APIs Ch 13-14, PortSwigger JWT attacks, CVE research
	+ Conduct PyJWT security audit: clone repo, review crypto, test algorithm confusion
	+ Build JWT attack tool
	+ **Deliverable:** PyJWT audit report, JWT attack tool, 200 labs, 15 blogs, Phase 5 complete

### Phase 8: Enterprise Production Tools (Weeks 16-18, 120 hours)

**Focus:** Enterprise frameworks, vulnerability aggregator, Dockerization

* **Week 16:** Enterprise Security Framework Design (40 hours)
	+ Design patterns (Factory, Strategy, Observer)
	+ Secure by Design Ch 7-8, Full Stack Python Security Ch 4-6, OWASP ASVS
	+ Design enterprise framework architecture with UML diagrams
	+ PortSwigger Insecure Deserialization (6 labs) + Prototype Pollution (5 labs)
	+ **Deliverable:** Framework architecture doc, 211 labs COMPLETE, 16 blogs

* **Week 17:** Vulnerability Aggregator Implementation (40 hours)
	+ Framework implementation, Python packaging
	+ Secure by Design Ch 9-10, Snyk API, GitLeaks, TruffleHog
	+ Build vulnerability aggregator: multi-tool integration, deduplication, REST API
	+ **Deliverable:** Vulnerability aggregator v1.0, REST API docs, 17 blogs, 211 labs maintained

* **Week 18:** Dockerization & Production Documentation (40 hours)
	+ Python packaging final (setup.py/pyproject.toml), Docker security
	+ Trivy container scanning, Full Stack Python Security Ch 12
	+ Dockerize framework: multi-stage Dockerfile, Docker Compose, Trivy scanning in CI/CD
	+ **Deliverable:** Dockerized framework, PyPI-ready, 18 blogs, Phase 6 complete

### Phase 9: Portfolio & System Design (Week 19, 40 hours)

**Focus:** Portfolio launch, AppSec system design practice

* **Week 19:** Portfolio Website & AppSec System Design (40 hours)
	+ Create GitHub Pages portfolio: tool demos, lab statistics, blog collection
	+ P2P project finalization: comprehensive tests, onboarding docs, GitHub org
	+ System design practice: 5 scenarios (microservices auth, multi-tenant SaaS, CI/CD secrets, zero-trust, threat modeling)
	+ Interview preparation: Security Design Portfolio, AppSec Q&A bank, OWASP ASVS review
	+ **Deliverable:** Portfolio live, system design portfolio, interview-ready, 19 blogs

### Phase 10: Cloud Security Deep Dive (Weeks 20-21, 80 hours)

**Focus:** AWS, Kubernetes, IaC scanning, CloudGoat

* **Week 20:** AWS Security Mastery & IaC Scanning (40 hours)
	+ AWS IAM, S3, Lambda, API Gateway security best practices
	+ Checkov IaC scanning, Terraform/CloudFormation
	+ Build AWS scanner (boto3): IAM policy analyzer, S3 config audit, Lambda security review
	+ AWS exercises, Terraform security labs
	+ **Deliverable:** AWS security scanner, IaC templates, 20 blogs

* **Week 21:** Kubernetes Security & CloudGoat Exploitation (40 hours)
	+ Kubernetes RBAC, network policies, Pod Security Standards
	+ CloudGoat by Rhino Security Labs, Trivy K8s scanning
	+ CloudGoat AWS labs: IAM privesc, EC2 SSRF, S3 exfiltration, CodeBuild secrets
	+ K8s security: deploy vulnerable pods, network policies, RBAC hardening, Falco rules
	+ **Deliverable:** CloudGoat completion, K8s security templates, 21 blogs, Phase 8 complete

### Phase 11: DevSecOps & Modern APIs (Weeks 22-23, 80 hours)

**Focus:** CI/CD gates, HashiCorp Vault, GraphQL

* **Week 22:** Advanced CI/CD Security & HashiCorp Vault (40 hours)
	+ GitHub Actions advanced security (CodeQL, secret scanning), GitLab security scanning
	+ HashiCorp Vault: secret engines, auth methods, CI/CD integration
	+ Build advanced CI/CD pipeline: security gates, Vault integration, dynamic DB credentials, policy-as-code
	+ Vault tutorials, GitHub Advanced Security exercises
	+ **Deliverable:** Production CI/CD pipeline, Vault patterns, 22 blogs

* **Week 23:** GraphQL Security & Service Mesh (40 hours)
	+ PortSwigger GraphQL vulnerabilities, OWASP GraphQL cheat sheet
	+ Hacking APIs Ch 14, Istio security documentation
	+ Build GraphQL testing suite: introspection analyzer, query complexity calculator, batching attack detector
	+ PortSwigger GraphQL labs, service mesh security exercises
	+ **Deliverable:** GraphQL scanner, service mesh checklist, 23 blogs, Phase 9 complete

### Phase 12: Final Preparation (Weeks 24-28, 200 hours)

**Focus:** Async Python mastery, interview prep, job applications

* **Week 24:** Async Python Mastery & Tool Integration (40 hours)
	+ asyncio advanced patterns, aiohttp for async HTTP
	+ Distributed systems security, modern authentication standards, AI/ML security
	+ Build async scanner: concurrent port scanning, async API fuzzing, parallel vuln verification
	+ **Deliverable:** Async scanner, interview-ready, 24 blogs

* **Week 25:** Tool Polish & Production Readiness (40 hours)
	+ Review all 25+ tools: fix bugs, add error handling, 80%+ test coverage
	+ Comprehensive documentation: README, API docs, ADRs, video demos
	+ GitHub profile optimization: pin 6 repos, GitHub Actions, badges
	+ **Deliverable:** All tools production-ready, GitHub optimized, 25 blogs

* **Week 26:** Advanced Interview Preparation (40 hours)
	+ Deep dive into target companies (Trail of Bits, NCC Group, Anthropic, GitLab, Stripe, Coinbase)
	+ Mock interviews: 5-6 sessions with peers/mentors
	+ System design practice: additional scenarios (secure file upload, fraud detection, API gateway)
	+ **Deliverable:** Mock feedback incorporated, 26 blogs

* **Week 27:** Active Job Applications & Networking (40 hours)
	+ Apply to 2-3 positions daily at target companies
	+ Networking: OWASP LA, Null Space Labs, LinkedIn outreach
	+ Prepare cover letters, track applications, follow-up
	+ **Deliverable:** Active job search, network expanded

* **Week 28:** Final Portfolio Polish & Interview Pipeline (40 hours)
	+ Portfolio final updates, all links tested, demos verified
	+ Interview pipeline management: schedule interviews, prepare for specific companies
	+ Continued applications and networking
	+ **Deliverable:** Interview-ready, active pipeline, curriculum complete

---

## 📚 Resources & Books

### Primary Books (Owned)

* [**Python Workout, Second Edition**](https://www.manning.com/books/python-workout-second-edition) - Reuven M. Lerner (Manning, 2024)
* [**Effective Python, Third Edition**](https://effectivepython.com/) - Brett Slatkin (Addison-Wesley, 2024)
* [**API Security in Action**](https://www.manning.com/books/api-security-in-action) - Neil Madden (Manning, 2020)
* [**Secure by Design**](https://www.manning.com/books/secure-by-design) - Dan Bergh Johnsson, Daniel Deogun, Daniel Sawano (Manning, 2019)
* [**Full Stack Python Security**](https://www.manning.com/books/full-stack-python-security) - Dennis Byrne (Manning, 2021)
* [**Hacking APIs**](https://nostarch.com/hacking-apis) - Corey J. Ball (No Starch Press, 2022)

### Primary Online Resources

* [PortSwigger Web Security Academy](https://portswigger.net/web-security) - **211 hands-on labs (100% completion goal)**
* [SQLBolt](https://sqlbolt.com/) - 18 SQL lessons
* [OWASP Top 10 2021](https://owasp.org/Top10/)
* [OWASP API Security Top 10](https://owasp.org/API-Security/)
* [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
* [OWASP Application Security Verification Standard (ASVS)](https://owasp.org/www-project-application-security-verification-standard/)
* [Semgrep Documentation](https://semgrep.dev/docs/)
* [HashiCorp Vault Tutorials](https://developer.hashicorp.com/vault/tutorials)

### Practice Environments

* [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) - Intentionally insecure web application (100+ challenges)
* [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) - AWS exploitation scenarios (10+ scenarios)
* [OWASP WebGoat](https://owasp.org/www-project-webgoat/) - Educational platform

---

## 🎯 Portfolio Goals

### Security Tools Repository

All tools will be published at [github.com/fosres/AppSec-Exercises](https://github.com/fosres/AppSec-Exercises)

**Planned Tools (25+):**

1. Advanced Password Validator with Entropy
2. SQL Injection Pattern Recognizer (50+ patterns)
3. Vulnerable Flask App for SQLi Testing
4. SQLi Code Review Scanner (AST-based)
5. JWT Security Analyzer
6. Input Validation Library (OWASP-compliant)
7. Advanced SQLi Detector with Deduplication
8. Burp Suite Extension
9. Blind SQLi Framework (Boolean/Time-based/OAST)
10. XSS Exploitation Framework
11. SSRF Scanner with Burp Collaborator
12. Authorization Toolkit (IDOR detector, privilege escalation)
13. OAuth Flow Analyzer Package
14. Authentication Module with MFA
15. RBAC/ABAC Demonstration Framework
16. SAST Orchestrator (15+ Custom Semgrep Rules)
17. CI/CD Security Scanner
18. Security Framework Dashboard
19. API Security Scanner v1.0
20. JWT Attack Tool
21. Vulnerability Aggregator
22. Dockerized Security Framework
23. AWS Security Scanner (IAM, S3, Lambda)
24. GraphQL Security Testing Suite
25. Async Concurrent Scanner
26. [Additional tools as developed]

### Blog Posts (dev.to/fosres)

**Planned Topics (26+, 1 per week):**

1. "SQL Injection in 2025: Why Parameterized Queries Aren't Enough"
2. "Building Secure-by-Design: Threat Modeling at Scale"
3. "From Cryptography to Python AppSec"
4. "Blind SQL Injection: Boolean to OAST Techniques"
5. "XSS Exploitation Framework: Context-Aware Payload Generation"
6. "SSRF in Microservices: From Discovery to Exploitation"
7. "5 Authorization Bugs AI Code Generation Misses"
8. "OAuth 2.0 Security: From Authorization Code to PKCE Bypasses"
9. "Building Production MFA: Beyond TOTP"
10. "RBAC vs ABAC: When to Use Which"
11. "Building Production SAST: From Semgrep to Custom Rules"
12. "Shift-Left Security: Implementing Pre-Commit Hooks at Scale"
13. "Building a Python Security Dashboard: 5 Tools in 200 Lines"
14. "API Security Scanner Architecture: From Discovery to Exploitation"
15. "What I Learned Auditing PyJWT: A Security Engineer's Perspective"
16. "Enterprise AppSec Architecture: Design Patterns That Scale"
17. "Building a Vulnerability Aggregator: From Chaos to Clarity"
18. "From Script to Production: Dockerizing Security Tools"
19. "AppSec System Design: Thinking Like an Architect"
20. "AWS Security Automation: From IAM to Infrastructure-as-Code"
21. "Kubernetes RBAC Gone Wrong: From Pod to Cluster Admin"
22. "Zero-Trust CI/CD: From Hardcoded Secrets to Vault"
23. "GraphQL Security: Beyond Query Depth Limiting"
24. "Async Python for Security: 10x Faster Vulnerability Scanning"
25. "From Learning to Production: 25 Security Tools in 7 Months"
26. "Preparing for AppSec Interviews: What I Learned"
27. [Additional posts as developed]

### Open Source Project: Secure Code Datasets for AI

**Vision:** Create LeetCode-style secure coding exercises to curate high-quality secure code datasets for training AI models to write more secure code.

**Problem:** Current AI models are trained on billions of lines of public code containing unsafe patterns, creating a cycle where AI tools generate vulnerable code.

**Solution:** Comprehensive secure coding exercises with 500+ test suites that demonstrate correct security patterns for AI training.

**Repository:** [github.com/fosres/AppSec-Exercises](https://github.com/fosres/AppSec-Exercises)

**Target:** 15+ exercises covering authentication, authorization, injection vulnerabilities, cryptography, and API security

---

## 🤝 Connect With Me

* **GitHub:** [github.com/fosres](https://github.com/fosres)
* **Blog:** [dev.to/fosres](https://dev.to/fosres)
* **LinkedIn:** [Connect with me](https://www.linkedin.com/in/tanveer-salim/)
* **Email:** Available upon request for collaboration or opportunities

### I'm Looking For:

* **Feedback:** If you're an experienced AppSec engineer, I'd love feedback on my learning plan
* **Collaboration:** Interested in contributing to the P2P secure coding exercise project
* **Opportunities:** Open to remote AppSec Engineer roles
* **Networking:** Always happy to connect with security professionals on LinkedIn or at OWASP LA meetups

---

## 📄 License

This curriculum and all associated exercises are available under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

* **Security Mentors:** For guidance and professional references
* **OWASP Community:** For incredible free resources and documentation
* **PortSwigger:** For the comprehensive Web Security Academy (211 labs!)
* **Manning Publications:** For excellent security and Python books
* **Security Community:** Everyone sharing knowledge on blogs, Twitter, Reddit, and HackerNews

---

## 📝 Notes

This is a **living document**. The plan evolves as I learn and adapt. Follow my [blog](https://dev.to/fosres) for detailed technical writeups and lessons learned throughout this journey.

**Key Differences from Part-Time Plans:**
- **Full-time commitment:** 40 hours/week vs typical 20-25 hours/week
- **Complete lab coverage:** All 211 PortSwigger labs vs partial coverage
- **Intensive tool development:** 25+ production tools vs 15-20 tools
- **Weekly blog posts:** 26+ posts (1 per week) vs sporadic posting
- **Accelerated timeline:** 28 weeks (7 months) vs 6-12 months for similar outcomes

---

**⭐ If you find this plan helpful, please star this repository! ⭐**

**Questions? Open an issue or reach out on LinkedIn!**
