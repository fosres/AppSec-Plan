# 🛡️ 26-Week Application Security Engineering Plan

> **Transforming from Intel Security Engineer to AppSec Engineer through systematic, hands-on learning**

[![Week Progress](https://img.shields.io/badge/Week-1%2F26-blue?style=flat-square)](https://github.com/fosres/AppSec-Plan)
[![Labs Completed](https://img.shields.io/badge/PortSwigger%20Labs-8%2F211-success?style=flat-square)](https://portswigger.net/web-security)
[![Blog Posts](https://img.shields.io/badge/Blog%20Posts-0%2F8-orange?style=flat-square)](https://dev.to/fosres)
[![Tools Built](https://img.shields.io/badge/Security%20Tools-2%2F20-red?style=flat-square)](https://github.com/fosres)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Why This Plan?](#-why-this-plan)
- [Background](#-background)
- [Learning Objectives](#-learning-objectives)
- [26-Week Breakdown](#-26-week-breakdown)
- [Resources & Books](#-resources--books)
- [Progress Tracking](#-progress-tracking)
- [Portfolio Goals](#-portfolio-goals)
- [Connect With Me](#-connect-with-me)

---

## 🎯 Overview

This repository documents my **26-week intensive journey** from Intel Security Engineering to Application Security Engineering. The curriculum combines offensive security skills (web exploitation, API security) with defensive engineering (SAST/DAST, CI/CD security) to build a comprehensive AppSec skillset.

**Timeline:** December 2, 2025 - June 1, 2026  
**Commitment:** 22 hours/week (572 total hours)  
**Target:** Remote AppSec Engineer role ($125K-$145K)  
**Target Companies:** Trail of Bits, NCC Group, Anthropic, GitLab, Stripe, Coinbase

---

## 💡 Why This Plan?

Most AppSec engineers come from either:
1. **Offensive security** (pentesters learning to build) → Strong exploitation, weak development
2. **Software engineering** (developers learning security) → Strong development, weak security mindset

**My advantage:** Combining Intel's enterprise-scale threat modeling experience with modern AppSec offensive skills creates a rare profile that understands both architecture-level security AND real-world exploitation.

### Unique Differentiators

✅ **Intel Threat Modeling at Scale:** Documented 553+ threats using STRIDE methodology (65.83% of Intel's TMT database)  
✅ **Reusable Security Frameworks:** Created threat model templates used by 100+ Intel engineers  
✅ **Systems Programming Background:** C/C++/Golang experience provides deep understanding of memory safety, performance implications, and low-level security concepts  
✅ **Cryptographic Implementation:** Intel Crypto Academy Level I, implemented XMSS signatures, ChaCha20 encryption, Argon2 KDFs  
✅ **Public Learning Journey:** Documenting entire transition through blog posts and open-source exercises

---

## 🔍 Background

### Intel Corporation | Product Assurance and Security (IPAS) Division
- **Threat Modeling Engineer:** Systematic security analysis of Intel products
- **Scale Achievement:** 553+ documented threats representing 65.83% of Intel's threat modeling database
- **Framework Development:** Created reusable threat model templates adopted by 100+ engineers
- **Methodologies:** STRIDE, attack trees, data flow diagrams, security requirements derivation

### Technical Foundation
- **Languages:** C (primary), C++, Golang, Python (learning)
- **Security Training:** Intel Crypto Academy Level I
- **Cryptography:** Implemented XMSS post-quantum signatures, ChaCha20 stream cipher, Argon2 KDFs
- **Education:** Pursuing UC Berkeley MICS, considering Stanford MSCS

---

## 🎓 Learning Objectives

By Week 26, I will have mastered:

### Technical Skills
- **Web Security:** Complete OWASP Top 10, 120+ PortSwigger labs across all vulnerability categories
- **API Security:** REST, GraphQL, gRPC security testing and implementation
- **Authentication/Authorization:** OAuth 2.0, JWT, session management, MFA, RBAC/ABAC
- **Security Automation:** SAST/DAST tools (Semgrep, Bandit, OWASP ZAP), custom rules, CI/CD integration
- **Cloud Security:** AWS (IAM, S3, Lambda), Kubernetes (RBAC, network policies), IaC scanning
- **DevSecOps:** GitHub Actions/GitLab CI security, HashiCorp Vault, supply chain security
- **Python Security Engineering:** Production-quality security tools, async patterns, OOP design

### Portfolio Deliverables
- **20+ Security Tools:** SQLi scanner, XSS payload generator, OAuth analyzer, CSRF PoC generator, SAST dashboard, API scanner, vulnerability aggregator, AWS security scanner, GraphQL testing suite, and more
- **8-10 Blog Posts:** Technical deep-dives published on [dev.to/fosres](https://dev.to/fosres)
- **15+ P2P Exercises:** LeetCode-style secure coding challenges with comprehensive test suites (part of larger open-source project to curate secure code datasets for AI training)
- **Portfolio Website:** Professional showcase of all projects and technical capabilities
- **System Design Expertise:** STRIDE-based threat modeling, secure architecture design

---

## 📅 26-Week Breakdown

### Phase 1: Foundation (Weeks 1-3, 66 hours)
**Focus:** Python fundamentals + Web security basics

- **Week 1:** Python Fundamentals & Web Security Basics
  - Python Workout Ch 1-2, Effective Python Items 1-5
  - OWASP Top 10 2021 complete overview
  - PortSwigger SQL Injection guide (8 labs)
  - **Deliverable:** SQLi detection script, 8 labs complete

- **Week 2:** Functions, Decorators & XSS Fundamentals
  - Python Workout Ch 3-4, Effective Python Items 6-10
  - PortSwigger XSS complete guide
  - CSP bypasses and context-aware encoding
  - **Deliverable:** XSS payload generator with encoding decorators, 18 labs

- **Week 3:** Files, Data Processing & Authentication Attacks
  - Python Workout Ch 5, Effective Python Items 11-15
  - Authentication vulnerabilities, password storage (Argon2id/bcrypt/scrypt)
  - API Security in Action Ch 3
  - **Deliverable:** Credential analysis tool, 26 labs

### Phase 2: Exploitation (Weeks 4-6, 66 hours)
**Focus:** Access control, CSRF/SSRF, business logic

- **Week 4:** Functions Deep Dive & Access Control
  - IDOR scanning, privilege escalation testing
  - BOLA/BFLA exploitation patterns
  - **Deliverable:** IDOR scanner, 36 labs

- **Week 5:** List Comprehensions & CSRF/SSRF
  - Token bypass techniques, SameSite exploitation
  - Cloud metadata exploitation (169.254.169.254)
  - **Deliverable:** CSRF PoC generator, 47 labs

- **Week 6:** Review & Foundation Assessment
  - Consolidate all tools into unified security toolkit
  - **Deliverable:** Security toolkit v1.0, blog post, 55 labs

### Phase 3: Authentication & Authorization (Weeks 7-9, 66 hours)
**Focus:** OAuth 2.0, JWT, session management, RBAC

- **Week 7:** Modules/Packages & OAuth 2.0 Deep Dive
  - OAuth2 flows, PKCE, refresh tokens, OpenID Connect
  - JWT claims, JOSE header, encrypted JWTs
  - **Deliverable:** OAuth analyzer package, 65 labs

- **Week 8:** OOP Part 1 & Complete Authentication System
  - Secure authentication module using OOP patterns
  - Session management with secure token generation
  - **Deliverable:** Auth module with MFA, 75 labs

- **Week 9:** OOP Part 2 & P2P Exercise Creation
  - RBAC/ABAC demonstration framework
  - Create 5 P2P authentication/authorization exercises
  - **Deliverable:** RBAC framework, 5 P2P exercises (150+ tests), blog post

### Phase 4: Security Automation (Weeks 10-12, 66 hours)
**Focus:** SAST/DAST, CI/CD security

- **Week 10:** Iterators/Generators & SAST Tools
  - Semgrep custom rules, Bandit configuration
  - SAST orchestrator using generators
  - **Deliverable:** SAST orchestrator, 5 custom Semgrep rules

- **Week 11:** Async Foundations & CI/CD Security
  - GitHub Actions/GitLab CI security hardening
  - Pre-commit framework for security hooks
  - **Deliverable:** CI/CD scanner, secure workflow templates

- **Week 12:** Review & Security Framework Dashboard
  - Integrate SAST, DAST, dependency scanning, secret scanning
  - **Deliverable:** Security dashboard v1.0, blog post

### Phase 5: Research & Discovery (Weeks 13-14, 44 hours)
**Focus:** API security, PyJWT audit

- **Week 13:** Advanced Iteration & API Security Scanner
  - Endpoint discovery, parameter fuzzing, auth bypass testing
  - **Deliverable:** API scanner v1.0, 85 labs

- **Week 14:** Review & PyJWT Security Audit
  - Comprehensive security audit of PyJWT library
  - **Deliverable:** PyJWT audit report, blog post

### Phase 6: Enterprise Production Tools (Weeks 15-17, 66 hours)
**Focus:** Enterprise frameworks, aggregation, Dockerization

- **Week 15:** Enterprise Security Framework Design
  - Factory, Strategy, Observer patterns for security tools
  - **Deliverable:** Framework architecture document, 95 labs

- **Week 16:** Vulnerability Aggregator Implementation
  - Multi-tool integration, deduplication, severity normalization
  - **Deliverable:** Vulnerability aggregator v1.0, 103 labs

- **Week 17:** Dockerization & Documentation
  - Multi-stage Dockerfile, Docker Compose, Trivy scanning
  - **Deliverable:** Dockerized framework, PyPI-ready package

### Phase 7: Portfolio & System Design (Week 18, 22 hours)
**Focus:** Portfolio launch, AppSec system design practice

- **Week 18:** Portfolio Polish & AppSec System Design
  - GitHub Pages portfolio site
  - 3 system design scenarios (microservices auth, multi-tenant SaaS, CI/CD secrets)
  - **Deliverable:** Portfolio live, system design portfolio, interview-ready

### Phase 8: Cloud Security Deep Dive (Weeks 19-20, 44 hours)
**Focus:** AWS, Kubernetes, IaC scanning

- **Week 19:** AWS Security & IaC Scanning
  - IAM policy analyzer, S3 bucket auditor, Terraform/CloudFormation scanning
  - **Deliverable:** AWS security scanner, IaC templates

- **Week 20:** Kubernetes Security & CloudGoat
  - RBAC auditing, network policies, CloudGoat exploitation labs
  - **Deliverable:** CloudGoat completion, K8s security templates

### Phase 9: DevSecOps & Modern APIs (Weeks 21-22, 44 hours)
**Focus:** CI/CD gates, HashiCorp Vault, GraphQL

- **Week 21:** CI/CD Security Gates & HashiCorp Vault
  - Vault integration for runtime secrets injection
  - **Deliverable:** Production CI/CD pipeline, blog post

- **Week 22:** GraphQL Security & Service Mesh
  - GraphQL introspection, batching attacks, Istio security
  - **Deliverable:** GraphQL scanner, 113 labs

### Phase 10: Final Preparation (Weeks 23-26, 88 hours)
**Focus:** Async Python, interview prep, job applications

- **Week 23:** Async Python & Final Interview Prep
  - Async security scanner, technical interview practice
  - **Deliverable:** Async scanner, interview-ready

- **Week 24:** Tool Polish & Documentation
  - 80%+ test coverage, comprehensive documentation
  - **Deliverable:** All tools production-ready

- **Week 25:** Advanced Interview Prep & Mock Interviews
  - 3-4 mock interviews, system design practice
  - **Deliverable:** Mock feedback incorporated

- **Week 26:** Active Job Applications & Networking
  - 2-3 applications daily, OWASP LA networking
  - **Deliverable:** 15+ applications submitted, network expanded

---

## 📚 Resources & Books

### Primary Books (Owned)
- [**Python Workout, Second Edition**](https://www.manning.com/books/python-workout-second-edition) - Reuven M. Lerner (Manning, 2024)
- [**Effective Python, Third Edition**](https://effectivepython.com/) - Brett Slatkin (Addison-Wesley, 2024)
- [**API Security in Action**](https://www.manning.com/books/api-security-in-action) - Neil Madden (Manning, 2020)
- [**Secure by Design**](https://www.manning.com/books/secure-by-design) - Dan Bergh Johnsson, Daniel Deogun, Daniel Sawano (Manning, 2019)
- [**Full Stack Python Security**](https://www.manning.com/books/full-stack-python-security) - Dennis Byrne (Manning, 2021)
- [**Hacking APIs**](https://nostarch.com/hacking-apis) - Corey J. Ball (No Starch Press, 2022)

### Primary Online Resources
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - 211 hands-on labs
- [OWASP Top 10 2021](https://owasp.org/Top10/)
- [OWASP API Security Top 10](https://owasp.org/API-Security/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [OWASP Application Security Verification Standard (ASVS)](https://owasp.org/www-project-application-security-verification-standard/)

### Practice Environments
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) - Intentionally insecure web application
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) - AWS exploitation scenarios
- [OWASP WebGoat](https://owasp.org/www-project-webgoat/) - Educational platform

---

## 📊 Progress Tracking

### Current Status (Week 1)
- ✅ **PortSwigger Labs:** 8/211 (3.8%)
- ✅ **Security Tools Built:** 2/20 (10%)
- ✅ **Blog Posts Published:** 0/8 (0%)
- ✅ **P2P Exercises Created:** 0/15 (0%)
- ✅ **Python Fluency:** 5.5/10

### Weekly Updates
I'll update this README every Sunday with:
- Labs completed that week
- Tools built
- Blog posts published
- Key learnings
- Challenges faced

Follow along on [dev.to/fosres](https://dev.to/fosres) for detailed technical writeups!

### Milestone Tracking

| Milestone | Target Week | Status |
|-----------|-------------|--------|
| Foundation Complete (55 labs) | Week 6 | 🔄 In Progress |
| First Blog Post Published | Week 6 | ⏳ Pending |
| Auth/Authz Mastery (75 labs) | Week 9 | ⏳ Pending |
| P2P Project Initialized | Week 9 | ⏳ Pending |
| SAST/DAST Automation | Week 12 | ⏳ Pending |
| PyJWT Security Audit Complete | Week 14 | ⏳ Pending |
| All 211 Labs Complete | Week 22 | ⏳ Pending |
| Portfolio Website Live | Week 18 | ⏳ Pending |
| Job Applications Begin | Week 23 | ⏳ Pending |
| Target: Offer Accepted | Week 26+ | ⏳ Pending |

---

## 🎯 Portfolio Goals

### Security Tools Repository
All tools will be published at [github.com/fosres/AppSec-Exercises](https://github.com/fosres/AppSec-Exercises)

**Planned Tools:**
1. ✅ SQL Injection Detection Script (Week 1)
2. ✅ Password Strength Validator (Week 1)
3. ⏳ XSS Payload Generator (Week 2)
4. ⏳ Credential Analysis Tool (Week 3)
5. ⏳ IDOR Scanner (Week 4)
6. ⏳ CSRF PoC Generator (Week 5)
7. ⏳ OAuth Flow Analyzer (Week 7)
8. ⏳ Authentication Module with MFA (Week 8)
9. ⏳ RBAC/ABAC Framework (Week 9)
10. ⏳ SAST Orchestrator (Week 10)
11. ⏳ CI/CD Security Scanner (Week 11)
12. ⏳ Security Framework Dashboard (Week 12)
13. ⏳ API Security Scanner (Week 13)
14. ⏳ JWT Attack Tool (Week 14)
15. ⏳ Vulnerability Aggregator (Week 16)
16. ⏳ AWS Security Scanner (Week 19)
17. ⏳ Kubernetes RBAC Auditor (Week 20)
18. ⏳ GraphQL Security Testing Suite (Week 22)
19. ⏳ Async Concurrent Scanner (Week 23)
20. ⏳ [Additional tools as developed]

### Blog Posts (dev.to/fosres)
**Planned Topics:**
1. ⏳ "Building Your First Security Testing Toolkit in Python: Lessons from 55 Labs" (Week 6)
2. ⏳ "5 Authorization Bugs AI Code Generation Consistently Misses" (Week 9)
3. ⏳ "Building a Python Security Dashboard: Integrating 5 Tools in 200 Lines" (Week 12)
4. ⏳ "What I Learned Auditing PyJWT: A Junior Security Engineer's Perspective" (Week 14)
5. ⏳ "From Script to Production: Dockerizing a Python Security Tool" (Week 17)
6. ⏳ "Implementing Zero-Trust CI/CD: From Hardcoded Secrets to HashiCorp Vault" (Week 21)
7. ⏳ [Additional posts as developed]

### Open Source Project: Secure Code Datasets for AI
**Vision:** Create LeetCode-style secure coding exercises to curate high-quality secure code datasets for training AI models to write more secure code.

**Problem:** Current AI models are trained on billions of lines of public code containing unsafe patterns, creating a cycle where AI tools generate vulnerable code.

**Solution:** Comprehensive secure coding exercises with test suites that demonstrate correct security patterns for AI training.

**Progress:** Repository initialized at [github.com/fosres/AppSec-Exercises](https://github.com/fosres/AppSec-Exercises)

---

## 🤝 Connect With Me

- **GitHub:** [github.com/fosres](https://github.com/fosres)
- **Blog:** [dev.to/fosres](https://dev.to/fosres)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/tanveer-salim/)
- **Email:** Available upon request for collaboration or opportunities

### I'm Looking For:
- **Feedback:** If you're an experienced AppSec engineer, I'd love feedback on my learning plan
- **Collaboration:** Interested in contributing to the P2P secure coding exercise project
- **Opportunities:** Open to remote AppSec Engineer roles starting June 2026
- **Networking:** Always happy to connect with security professionals on LinkedIn or at OWASP LA meetups

---

## 📄 License

This curriculum and all associated exercises are available under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Intel Security Team:** Jonathan Valamehr, Tony Martin, Brian Nutter for mentorship and references
- **OWASP Community:** For incredible free resources and documentation
- **PortSwigger:** For the comprehensive Web Security Academy
- **Manning Publications:** For excellent security and Python books
- **Security Community:** Everyone sharing knowledge on blogs, Twitter, Reddit, and HackerNews

---

## 📝 Notes

This is a **living document**. The plan will evolve as I learn and adapt. Weekly updates will be posted every Sunday. Follow my [blog](https://dev.to/fosres) for detailed technical writeups and lessons learned.

**Started:** December 2, 2025  
**Last Updated:** December 7, 2025  
**Current Week:** 1/26

---

**⭐ If you find this plan helpful, please star this repository! ⭐**

**Questions? Open an issue or reach out on LinkedIn!**
