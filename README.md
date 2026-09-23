# Penetration Testing Project - Phase 2

## Executive Summary
This repository contains the technical documentation and deliverables for Phase 2 of an enterprise penetration testing engagement. The assessment simulates realistic threat actor tactics, techniques, and procedures (TTPs) across target environments to evaluate network security boundaries, identify exploitable vulnerabilities, and validate internal defensive controls.

## Scope & Target Environment
* *Target Systems:* Enterprise Network Architecture & Metasploitable 2 Environments
* *Assessment Framework:* OWASP Top 10, PTES (Penetration Testing Execution Standard), and NIST SP 800-115
* *Primary Objective:* Execute network discovery, identify high-risk service vulnerabilities, attempt authorized exploitation, and recommend actionable risk mitigations.

## Technical Execution & Methodology
1. *Reconnaissance & Network Discovery:* Executed host discovery and port scanning with Nmap to enumerate active service versions, open ports, and operating system fingerprints.
2. *Vulnerability Analysis:* Identified known CVEs, unpatched service vulnerabilities, and misconfigurations across active web and network protocols using Nikto and automated scanning assets.
3. *Exploitation & Risk Validation:* Leveraged the Metasploit Framework to validate initial access vectors, execute post-exploitation checks, and evaluate potential privilege escalation paths.
4. *Risk Scoring & Reporting:* Classified findings using the Common Vulnerability Scoring System (CVSS v3) to prioritize remediation strategies based on exploitability and operational impact.

## Primary Deliverables
* *PENETRATION TESTING PROJECT P2.pdf*: The full technical report outlining host discovery output, exploitation logs, CVSS threat severity scores, and executive remediation roadmaps.

## Tools & Technical Stack
* *Network Reconnaissance:* Nmap (Port Scanning, OS Detection, NSE Scripts)
* *Web & Service Auditing:* Nikto Web Vulnerability Scanner
* *Exploitation Frameworks:* Metasploit Framework
* *Target Environments:* Metasploitable 2 / Linux Virtual Machine Assets
* *Methodologies:* CVSS v3 Risk Rating, PTES Standard
