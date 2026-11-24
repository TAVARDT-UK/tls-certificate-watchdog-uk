# TLS/SSL Certificate Watchdog

[![Scope of Perimeter Verification](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/uk/security-headers-check/)
Automated monitoring of SSL/TLS certificate expiry, cryptographic chain integrity, and encrypted transport compliance in the UK.

Developed and maintained by the cybersecurity and infrastructure defence division of **TAVARDT**.

***

## 1. Scope of Perimeter Verification

This command-line utility audits certificate validity periods, cipher negotiation, and root authority chains:

* **Preventative Expiry Warning:** Calculates remaining days until certificate expiry with configurable thresholds.
* **Cipher and Protocol Audit:** Verifies TLS 1.3 support and ensures revocation of legacy cipher suites.
* **Certificate Authority (CA) Validation:** Inspects the trust chain issuer and Subject Alternative Names (SAN).
* **Zero External Dependencies:** Built strictly with Python native ssl and socket standard library modules.

***

## 2. Quick Start Guide

Run this tool directly via Python without installing third-party packages:

```bash
python watchdog.py example.co.uk
```

***

## 3. Online Diagnostic Tools (United Kingdom)

Audit the public infrastructure of your web properties using the TAVARDT diagnostic suite:

* HTTP Security Headers Checker
* [Consent Mode v2 & UK GDPR Validator](https://tools.tavardt.com/uk/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/uk/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/uk/exposed-files-scanner/)
* [Full UK Technical Tools Portal](https://tools.tavardt.com/uk/)

***

## 4. Technical Advisory & Remediation

For server cryptographic hardening, automated rotation, and enterprise zero-trust consulting in the UK, contact **TAVARDT**.

***

© 2026 TAVARDT. All rights reserved.
