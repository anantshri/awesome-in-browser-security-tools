# Awesome In-Browser Security Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source information security tools that run entirely in your browser — no backend, no installation required.

## Philosophy

These tools embrace a client-side-first approach to security tooling:

- **Data Privacy** — No user data storage on servers
- **No Persistent API Keys** — Keys input as needed, never stored
- **No CORS Proxying** — Prevents third-party data interception
- **Client-Side Operations** — All processing happens in your browser
- **Transparent Hosting** — Open-source code hosted on GitHub Pages

Read more: [Making Security Tools Accessible: Why I Chose the Browser](https://blog.anantshri.info/making-security-tools-accessible-why-i-chose-the-browser/)

---

## Contents

- [SBOM & Dependency Analysis](#sbom--dependency-analysis)
- [DNS & Network Analysis](#dns--network-analysis)
- [Cloud Security](#cloud-security)
- [Authentication & Keys](#authentication--keys)
- [Mobile Security](#mobile-security)
- [Encoding & Cryptography](#encoding--cryptography)
- [Multi-Purpose Security](#multi-purpose-security)
- [Password Security](#password-security)
- [Compliance & Risk Assessment](#compliance--risk-assessment)
- [Infrastructure as Code](#infrastructure-as-code)
- [Web Security](#web-security)
- [Contributing](#contributing)

---

## SBOM & Dependency Analysis

### AIBOMmaker

AI Bill of Materials generator for documenting AI/ML model dependencies and components.

| Property | Value |
|----------|-------|
| **Author** | Cyfinoid |
| **Demo** | [cyfinoid.github.io/aibommaker/](https://cyfinoid.github.io/aibommaker/) |
| **Repository** | [github.com/cyfinoid/aibommaker](https://github.com/cyfinoid/aibommaker) |
| **Keywords** | `AIBOM`, `AI`, `ML`, `Bill of Materials` |
| **License** | ![License](https://badgen.net/github/license/cyfinoid/aibommaker) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/cyfinoid/aibommaker) |
| **Sponsor** | [GitHub Sponsors](https://github.com/sponsors/anantshri) · [Buy Me a Coffee](https://buymeacoffee.com/anantshri) |

---
### SBOM Play

A privacy-focused SBOM visualization tool with vulnerability insights, license analysis, and cross-repo visibility.

| Property | Value |
|----------|-------|
| **Author** | Cyfinoid |
| **Demo** | [cyfinoid.github.io/sbomplay/](https://cyfinoid.github.io/sbomplay/) |
| **Repository** | [github.com/cyfinoid/sbomplay](https://github.com/cyfinoid/sbomplay) |
| **Keywords** | `SBOM`, `vulnerability`, `license`, `CycloneDX`, `SPDX` |
| **License** | ![License](https://badgen.net/github/license/cyfinoid/sbomplay) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/cyfinoid/sbomplay) |
| **Sponsor** | [GitHub Sponsors](https://github.com/sponsors/anantshri) · [Buy Me a Coffee](https://buymeacoffee.com/anantshri) |

---

## DNS & Network Analysis

### 3P-Tracer

Comprehensive DNS analysis, certificate transparency discovery, service detection, and security checks — all within your browser.

| Property | Value |
|----------|-------|
| **Author** | Cyfinoid |
| **Demo** | [cyfinoid.github.io/3ptracer/](https://cyfinoid.github.io/3ptracer/) |
| **Repository** | [github.com/cyfinoid/3ptracer](https://github.com/cyfinoid/3ptracer) |
| **Keywords** | `DNS`, `certificate transparency`, `third-party`, `service detection` |
| **License** | ![License](https://badgen.net/github/license/cyfinoid/3ptracer) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/cyfinoid/3ptracer) |
| **Sponsor** | [GitHub Sponsors](https://github.com/sponsors/anantshri) · [Buy Me a Coffee](https://buymeacoffee.com/anantshri) |

---

## Cloud Security

### Cloud IAM Policy Explorer

IAM policy analysis tool for understanding and auditing cloud access permissions.

| Property | Value |
|----------|-------|
| **Author** | Cyfinoid |
| **Demo** | [cyfinoid.github.io/cloud-iam-policy-explorer/](https://cyfinoid.github.io/cloud-iam-policy-explorer/) |
| **Repository** | [github.com/cyfinoid/cloud-iam-policy-explorer](https://github.com/cyfinoid/cloud-iam-policy-explorer) |
| **Keywords** | `IAM`, `AWS`, `Azure`, `GCP`, `policy`, `permissions` |
| **License** | ![License](https://badgen.net/github/license/cyfinoid/cloud-iam-policy-explorer) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/cyfinoid/cloud-iam-policy-explorer) |
| **Sponsor** | [GitHub Sponsors](https://github.com/sponsors/anantshri) · [Buy Me a Coffee](https://buymeacoffee.com/anantshri) |

---

## Authentication & Keys

### GH Navigator

A client-side repository browser and bulk token analyzer that inspects token validity and scopes to assess the control plane of GitHub environments.

| Property | Value |
|----------|-------|
| **Author** | Cyfinoid |
| **Demo** | [cyfinoid.github.io/ghnavigator/](https://cyfinoid.github.io/ghnavigator/) |
| **Repository** | [github.com/cyfinoid/ghnavigator](https://github.com/cyfinoid/ghnavigator) |
| **Keywords** | `GitHub`, `token`, `authentication`, `repository`, `API` |
| **License** | ![License](https://badgen.net/github/license/cyfinoid/ghnavigator) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/cyfinoid/ghnavigator) |
| **Sponsor** | [GitHub Sponsors](https://github.com/sponsors/anantshri) · [Buy Me a Coffee](https://buymeacoffee.com/anantshri) |

---
### JWT Auditor

Advanced JWT security testing platform for analyzing, decoding, and pentesting JWT vulnerabilities entirely in the browser.

| Property | Value |
|----------|-------|
| **Author** | dr34mhacks |
| **Demo** | [jwtauditor.com/](https://jwtauditor.com/) |
| **Repository** | [github.com/dr34mhacks/jwtauditor](https://github.com/dr34mhacks/jwtauditor) |
| **Keywords** | `JWT`, `token`, `authentication`, `pentesting`, `security` |
| **License** | ![License](https://badgen.net/github/license/dr34mhacks/jwtauditor) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/dr34mhacks/jwtauditor) |

---

## Mobile Security

### ADB Auditor

Browser-based Android security auditing tool — requires device connected via USB with debugging enabled.

| Property | Value |
|----------|-------|
| **Author** | thecybersandeep |
| **Demo** | [adbauditor.com/](https://adbauditor.com/) |
| **Repository** | [github.com/thecybersandeep/adbauditor](https://github.com/thecybersandeep/adbauditor) |
| **Keywords** | `Android`, `APK`, `mobile`, `security`, `audit` |
| **License** | ![License](https://badgen.net/github/license/thecybersandeep/adbauditor) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/thecybersandeep/adbauditor) |

---
### Frida Web

Browser-based Frida client for dynamic instrumentation — requires Frida server with WebSocket endpoint on target device.

| Property | Value |
|----------|-------|
| **Author** | zahidaz |
| **Demo** | [zahidaz.github.io/frida_web/](https://zahidaz.github.io/frida_web/) |
| **Repository** | [github.com/zahidaz/frida_web](https://github.com/zahidaz/frida_web) |
| **Keywords** | `Frida`, `dynamic instrumentation`, `reverse engineering`, `Android`, `iOS` |
| **License** | ![License](https://badgen.net/github/license/zahidaz/frida_web) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/zahidaz/frida_web) |

---
### IPA Auditor

Browser-based iOS IPA security analyzer.

| Property | Value |
|----------|-------|
| **Author** | thecybersandeep |
| **Demo** | [ipaauditor.com/](https://ipaauditor.com/) |
| **Repository** | [github.com/thecybersandeep/ipaauditor](https://github.com/thecybersandeep/ipaauditor) |
| **Keywords** | `iOS`, `IPA`, `mobile`, `security`, `audit` |
| **License** | ![License](https://badgen.net/github/license/thecybersandeep/ipaauditor) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/thecybersandeep/ipaauditor) |

---

## Encoding & Cryptography

### CyberChef

The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis.

| Property | Value |
|----------|-------|
| **Author** | GCHQ |
| **Demo** | [gchq.github.io/CyberChef](https://gchq.github.io/CyberChef) |
| **Repository** | [github.com/gchq/CyberChef](https://github.com/gchq/CyberChef) |
| **Keywords** | `encryption`, `encoding`, `hashing`, `compression`, `data-analysis` |
| **License** | ![License](https://badgen.net/github/license/gchq/CyberChef) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/gchq/CyberChef) |

---

## Multi-Purpose Security

### Security Webtools

Local-first browser-based security tools for developers and defenders. No backend, no data sent anywhere.

| Property | Value |
|----------|-------|
| **Author** | dmtkfs |
| **Demo** | [dmtkfs.github.io/security-webtools/](https://dmtkfs.github.io/security-webtools/) |
| **Repository** | [github.com/dmtkfs/security-webtools](https://github.com/dmtkfs/security-webtools) |
| **Keywords** | `security`, `blue-team`, `log-analysis`, `threat-simulation`, `MITRE ATT&CK` |
| **License** | ![License](https://badgen.net/github/license/dmtkfs/security-webtools) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/dmtkfs/security-webtools) |

---

## Password Security

### Password Security Analyzer

A browser-based tool to analyze password strength, estimate entropy, generate secure passwords, and check breach exposure locally.

| Property | Value |
|----------|-------|
| **Author** | NaveenJc10 |
| **Demo** | [naveenjc10.github.io/Password-Security-Analyzer/](https://naveenjc10.github.io/Password-Security-Analyzer/) |
| **Repository** | [github.com/NaveenJc10/Password-Security-Analyzer](https://github.com/NaveenJc10/Password-Security-Analyzer) |
| **Keywords** | `password`, `entropy`, `security`, `breach-check` |
| **License** | ![License](https://badgen.net/github/license/NaveenJc10/Password-Security-Analyzer) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/NaveenJc10/Password-Security-Analyzer) |

---

## Compliance & Risk Assessment

### HIPAA SRA

A comprehensive client-side HIPAA Security Risk Assessment tool with 33+ controls, policy library, workforce training modules, risk register, and multi-dimensional compliance dashboard. No backend, no tracking — all data stays in the browser.

| Property | Value |
|----------|-------|
| **Author** | l0lsec |
| **Demo** | [l0lsec.github.io/hipaa-sra/](https://l0lsec.github.io/hipaa-sra/) |
| **Repository** | [github.com/l0lsec/hipaa-sra](https://github.com/l0lsec/hipaa-sra) |
| **Keywords** | `HIPAA`, `compliance`, `risk-assessment`, `healthcare`, `security`, `SRA` |
| **License** | ![License](https://badgen.net/github/license/l0lsec/hipaa-sra) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/l0lsec/hipaa-sra) |

---
### HIPAA-SRA-Tool

A client-side only, no-data-retained HIPAA Security Risk Assessment (SRA) tool. Runs 100% in the browser with no backend, no trackers, no storage. Supports PDF export and JSON import/export.

| Property | Value |
|----------|-------|
| **Author** | SaberGuard-LLC |
| **Demo** | [saberguard-llc.github.io/HIPAA-SRA-Tool/](https://saberguard-llc.github.io/HIPAA-SRA-Tool/) |
| **Repository** | [github.com/SaberGuard-LLC/HIPAA-SRA-Tool](https://github.com/SaberGuard-LLC/HIPAA-SRA-Tool) |
| **Keywords** | `HIPAA`, `SRA`, `compliance`, `risk-assessment`, `healthcare` |
| **License** | ![License](https://badgen.net/github/license/SaberGuard-LLC/HIPAA-SRA-Tool) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/SaberGuard-LLC/HIPAA-SRA-Tool) |

---
### SITF

SDLC Infrastructure Threat Framework for analyzing supply chain attacks with interactive attack flow visualizer and technique library.

| Property | Value |
|----------|-------|
| **Author** | Wiz |
| **Demo** | [wiz-sec-public.github.io/SITF/](https://wiz-sec-public.github.io/SITF/) |
| **Repository** | [github.com/wiz-sec-public/SITF](https://github.com/wiz-sec-public/SITF) |
| **Keywords** | `SDLC`, `supply-chain`, `threat-framework`, `CI/CD`, `attack-flow`, `risk-assessment` |
| **License** | ![License](https://badgen.net/github/license/wiz-sec-public/SITF) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/wiz-sec-public/SITF) |

---

## Infrastructure as Code

### IaC Security Scanner

Free Browser Based IAC security scanner for Terraform, Kubernetes, Docker, and CloudFormation with PDF reporting. Everything runs in your browser - no data leaves your device.

| Property | Value |
|----------|-------|
| **Author** | peachycloudsecurity |
| **Demo** | [peachycloudsecurity.com/apps/scanner](https://peachycloudsecurity.com/apps/scanner) |
| **Repository** | [github.com/peachycloudsecurity/iac-security-scanner](https://github.com/peachycloudsecurity/iac-security-scanner) |
| **Keywords** | `IaC`, `infrastructure as code`, `Terraform`, `Kubernetes`, `Docker`, `CloudFormation`, `security scanner` |
| **License** | ![License](https://badgen.net/github/license/peachycloudsecurity/iac-security-scanner) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/peachycloudsecurity/iac-security-scanner) |
| **Sponsor** | [Support the author](https://github.com/sponsors/peachycloudsecurity) |

---

## Web Security

### ClobberX

A browser-focused tool for generating DOM Clobbering payloads across different browsers (FireFox, Chrome)

| Property | Value |
|----------|-------|
| **Author** | Alfin Joseph |
| **Demo** | [clobberx.netlify.app/](https://clobberx.netlify.app/) |
| **Repository** | [github.com/AlfinJ0se/ClobberX](https://github.com/AlfinJ0se/ClobberX) |
| **Keywords** | `Web Security`, `security`, `client-side-security` |
| **License** | ![License](https://badgen.net/github/license/AlfinJ0se/ClobberX) |
| **Last Update** | ![Last Commit](https://badgen.net/github/last-commit/AlfinJ0se/ClobberX) |

---

## Contributing

Contributions are welcome! To add a new tool:

1. Fork this repository
2. Edit `data/tools.json` — add your tool entry
3. Submit a pull request

That's it! Our automation will validate your entry and update the README and website automatically.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the tool entry format and criteria.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

---

<sub>Last generated: 2026-05-19 08:17 UTC</sub>
