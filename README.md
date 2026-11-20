# TLS/SSL Certificate Watchdog | TAVARDT UK

[![Monitor de Certificados](https://img.shields.io/badge/TAVARDT-Diagn%C3%B3stico%20T%C3%A9cnico-5b3cf5.svg)](https://tools.tavardt.com/uk/security-headers-check/)
[![Conformidade](https://img.shields.io/badge/Jurisdi%C3%A7%C3%A3o-United Kingdom-00C853.svg)](https://ag.tavardt.com/uk/cybersecurity/)

Automated TLS/SSL certificate expiration watchdog, chain integrity inspection, and NCSC crypto compliance for UK organisations.

Desenvolvido e mantido pela divisão de proteção de infraestruturas da **[TAVARDT UK](https://ag.tavardt.com/uk/)**.

---

## 1. Continuous Monitoring Capabilities

This command-line utility inspects real-time validity, cipher suites, and trust chains of secure endpoints:

* **Expiration Watchdog:** Calculates real-time days remaining with alert thresholds to prevent unplanned downtime.
* **Cipher Suite Auditing:** Enforces modern TLS 1.3 standards and confirms the deprecation of legacy algorithms.
* **Certificate Authority Inspection:** Validates issuer identity, trust chain integrity, and SAN coverage.
* **Zero External Dependencies:** Built with native Python socket and ssl modules for lightweight operational monitoring.

---

## 2. Quick Start Guide

Execute a ferramenta diretamente via Python sem necessidade de instalar dependências externas:

```bash
python watchdog.py exemplo.com
```

---

## 3. Online Diagnostic Tools (United Kingdom)

Audite a infraestrutura pública das suas aplicações utilizando a suíte de diagnósticos da TAVARDT:

* [HTTP Security Headers Checker](https://tools.tavardt.com/uk/security-headers-check/)
* [Consent Mode v2 & UK GDPR Validator](https://tools.tavardt.com/uk/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/uk/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/uk/exposed-files-scanner/)
* [Full UK Technical Tools Portal](https://tools.tavardt.com/uk/)

---

## 4. Cryptographic Hardening & Advisory

For enterprise cryptographic architecture, server hardening, and cyber defence in the UK, contact **[TAVARDT UK](https://ag.tavardt.com/uk/contact/)**.
