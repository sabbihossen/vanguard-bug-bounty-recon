# 🛡️ Findings & Limitations

## 01. Overview

This document summarizes the observations, results, and limitations recorded during the Vanguard VDP reconnaissance exercise.

The purpose is to present reconnaissance outcomes clearly while distinguishing observed information from confirmed security vulnerabilities.

## 02. Reconnaissance Results

The assignment notes report the following metrics:

| Metric | Reported Result |
|---|---:|
| Unique subdomains discovered | 4,343 |
| Live hosts identified | 1,110 |
| Unique URLs collected | 4,705 |

*These figures are based on the original assignment notes and should be supported by the corresponding evidence.*

## 03. Key Observations

The exercise covered the following areas:

- **Asset Discovery:** Identification and organization of subdomain candidates.
- **Host Verification:** Assessment of discovered host availability.
- **Technology Fingerprinting:** Collection of observable technology and infrastructure indicators.
- **Directory Discovery:** Identification of potentially relevant paths for review.
- **URL Collection:** Organization of discovered URLs and application routes.

These activities helped build a preliminary picture of the target's external attack surface.

## 04. Unconfirmed Observations

Reconnaissance may identify paths, technologies, and endpoints that warrant further review. However:

- A discovered path does not prove that a file is exposed.
- A detected technology does not prove that a vulnerability exists.
- A responsive host does not establish security impact.
- A redirect or generic response does not confirm unauthorized access.

Any potential security issue requires appropriate evidence and validation within the program's permitted testing boundaries.

## 05. Limitations

- Automated tools may return incomplete results or false positives.
- Technology fingerprints may not accurately reflect the current application stack.
- Host availability and endpoint behavior may change over time.
- The results represent the scope and conditions of the original exercise.
- Findings should not be described as independently verified unless supporting validation was performed.

## 06. Responsible Disclosure

All reconnaissance and any subsequent validation must comply with the program's current scope, rules, and disclosure policy.

Sensitive information, credentials, tokens, restricted scan output, and unreported vulnerabilities must not be published without appropriate authorization.

## 07. Conclusion

The exercise demonstrates a structured approach to reconnaissance and external attack-surface discovery. The documented results provide a foundation for further authorized security review, without overstating the existence or impact of vulnerabilities.

---

**Author:** Sheikh Sabbir Hossain  
**Focus:** Cybersecurity · Web Security · VAPT · Bug Bounty Reconnaissance
