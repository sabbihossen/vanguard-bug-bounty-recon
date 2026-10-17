# 🛡️ Reconnaissance Methodology

<p align="center">
  <strong>ATTACK SURFACE DISCOVERY | WEB RECONNAISSANCE</strong>
</p>

---

## 🎯 01. Project Overview

This document presents the reconnaissance methodology followed during a practical exercise associated with the **Vanguard Vulnerability Disclosure Program (VDP)**.

The exercise focused on identifying eligible subdomains, verifying accessible hosts, fingerprinting observable technologies, discovering web directories, and collecting URLs for structured security analysis.

The methodology emphasizes scope awareness, evidence-based observations, and responsible security research.

## 🔍 02. Reconnaissance Objectives

- **Asset Discovery:** Identify and organize subdomain candidates within the authorized scope.
- **Host Verification:** Assess host availability using permitted techniques.
- **Technology Fingerprinting:** Identify observable web technologies and infrastructure components.
- **Directory Discovery:** Review potentially relevant paths and publicly accessible resources.
- **URL Collection:** Organize discovered URLs and endpoints for further review.
- **Evidence Documentation:** Record observations, limitations, and areas requiring additional validation.

## ⚙️ 03. Reconnaissance Workflow

### Phase 01 — Scope Verification

Review the program's eligibility criteria, target scope, testing restrictions, and disclosure requirements before conducting reconnaissance.

### Phase 02 — Subdomain Discovery

Collect subdomain candidates using the tools and techniques documented in the original practical assignment. Organize the results and remove duplicate entries where appropriate.

### Phase 03 — Live-Host Verification

Verify host accessibility using permitted methods. Classify responsive hosts as live observations without assuming that availability indicates a security weakness.

### Phase 04 — Technology Fingerprinting

Analyze observable technology indicators, including web servers, content delivery networks (CDNs), application frameworks, and authentication services.

Treat automated fingerprints as indicators that may require further verification.

### Phase 05 — Directory & Content Discovery

Review discovered paths and HTTP responses to identify potentially relevant resources. Distinguish redirects, generic error responses, and confirmed resource access.

### Phase 06 — URL & Endpoint Collection

Collect, organize, and review discovered URLs to support structured attack-surface analysis. Any subsequent testing must remain within the applicable authorization and program rules.

## 🧰 04. Tools & Technical Documentation

The tools, commands, and configurations used should be documented from the original assignment and supporting evidence.

| Activity | Documentation Required |
|---|---|
| Subdomain Discovery | Verified tools, commands, and output |
| Host Verification | Actual verification methods |
| Technology Fingerprinting | Tools and observed indicators |
| Directory Discovery | Command configuration and response analysis |
| URL Collection | Collection, organization, and deduplication methods |

> **Technical integrity:** Only document tools, commands, and results that were actually used and can be supported by evidence.

## 📁 05. Evidence Management

Supporting screenshots and sanitized outputs should be organized within the repository's `evidence/` directory.

- Use descriptive filenames and clear captions.
- Remove credentials, tokens, and personal information.
- Review target details against the program's disclosure policy.
- Publish only evidence that is safe and permitted for public disclosure.
- Ensure every reported observation is supported by appropriate evidence.

## 🔐 06. Security, Scope & Limitations

- Follow the program's current scope, policies, and rate limits.
- Do not test assets without explicit authorization.
- Do not equate a discovered endpoint or technology fingerprint with a confirmed vulnerability.
- Validate observations only through permitted testing methods.
- Avoid publishing sensitive information or unreported vulnerabilities without authorization.
- Clearly distinguish verified observations from assumptions and unconfirmed leads.

## ✅ 07. Conclusion

This methodology establishes a structured approach to external attack-surface reconnaissance, covering asset discovery, host verification, technology fingerprinting, directory discovery, and URL collection.

The resulting documentation supports further authorized security review while maintaining a clear distinction between reconnaissance observations and validated security findings.

---

**Author:** Sheikh Sabbir Hossain

**Focus Areas:** Cybersecurity · Web Security · VAPT · Bug Bounty Reconnaissance
