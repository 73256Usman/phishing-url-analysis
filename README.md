# Phishing URL Analysis Report

**SOC Threat Investigation | IOC Documentation | MITRE ATT&CK Mapping**

---

## Overview

End-to-end phishing URL investigation conducted on a typosquatted 
delivery service domain. The investigation involved passive URL analysis, 
multi-tool threat intelligence verification, IOC documentation, and 
formal MITRE ATT&CK technique mapping.

---

## Target URL
hxxps://delivry-4you[.]site/3416a36
*URL has been defanged to prevent accidental clicks*

---

## Initial Indicators Identified

| Indicator | Detail |
|---|---|
| Typosquatting | "delivry" misspells "delivery" |
| Suspicious TLD | .site — low cost, high abuse rate |
| Randomized path | /3416a36 — phishing redirect pattern |
| Trust Score | 1/100 — confirmed malicious |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Gridinsoft | URL reputation and trust score |
| VirusTotal | Multi-vendor malware and URL scanning |
| URLScan.io | Safe passive site analysis and screenshot |
| AbuseIPDB | Hosting IP reputation check |
| MXToolbox | Domain blacklist verification |

---

## MITRE ATT&CK Mapping

| Tactic | Technique ID | Technique Name |
|---|---|---|
| Resource Development | T1583.001 | Acquire Infrastructure: Domains |
| Initial Access | T1566.002 | Phishing: Spearphishing Link |
| Credential Access | T1056 | Input Capture |

---

## Key Findings

- Domain confirmed malicious with trust score of 1/100
- Blacklisted across multiple threat intelligence vendors
- Attack technique consistent with credential harvesting campaigns
- Delivery service impersonation used as social engineering lure

---

## Containment Recommendations

- Block domain at email gateway and perimeter firewall
- Block hosting IP at perimeter firewall
- Submit URL to VirusTotal and PhishTank for community blacklisting
- Review email logs for internal delivery of this domain
- Issue security awareness advisory to affected organization

---

## Full Report

The complete investigation report with detailed findings, defanged 
IOCs, and formal containment recommendations is available in the 
PDF above.

---

## Skills Demonstrated

`Threat Intelligence` `IOC Documentation` `MITRE ATT&CK` 
`Phishing Analysis` `Incident Response` `SOC Investigation`
`URL Analysis` `Defanging` `Containment Recommendations`

---

## Contact

**Usman Zaffar**  
732.usman@gmail.com  
[LinkedIn](https://linkedin.com/in/usmanzaffar)
