# Phishing Email Investigation

## Scenario
A suspicious email was reported by a user. The goal was to analyze the email, identify malicious indicators, and determine if it posed a threat to the organization.

## Tools Used
- Email headers analysis
- Links and URL inspection
- VirusTotal and other threat intelligence sites
- SIEM dashboard (to check logs related to sender IP)

## Investigation Steps
- Examined the email headers to verify the sender
- Checked all links for malicious behavior
- Reviewed attachments for malware
- Correlated sender IP with past alerts in SIEM
- Classified the email as phishing and flagged it

## Findings
The email contained a malicious link and a spoofed sender address. It was successfully blocked before reaching other users.

## What I Learned
- How to identify phishing attempts
- How to analyze email headers and links
- How SOC teams validate threats using SIEM and threat intelligence
