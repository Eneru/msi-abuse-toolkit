# 🧩 MSI Abuse Toolkit

## Overview

This project explores how Windows Installer (MSI/MSP) can be abused as an attack vector in enterprise Windows environments.

It provides:
* reproducible **abuse scenarios**
* **offensive demonstrations**
* **detection strategies**
* **hardening recommendations**

The goal is to help **red teams, blue teams and security engineers** understand and mitigate a largely undocumented attack surface.

## Why Windows Installer?

Windows Installer is:
* trusted
* signed
* widely deployed
* often ignored by security tooling

Yet it offers:
* elevated execution
* persistence mechanisms
* repair & self-healing behaviors
* complex execution flows

This makes it a powerful **living-off-the-land vector**.

## Project Structure

```
msi-abuse-toolkit/
│
├── offensive/ -> controlled abuse techniques
│   ├── custom-actions/
│   ├── persistence/
│   └── repair-abuse/
│
├── defensive/ -> detection & mitigation
│   ├── detections/
│   ├── sigma/
│   └── hardening/
│
├── labs/ -> vulnerable MSI samples
│   ├── vulnerable-msi/
│   └── walkthrough.md
│
├── docs/ -> detailed explanations
│   ├── attack-scenarios.md
│   ├── detection.md
│   └── mitigations.md
│
└── README.md
```

## CI/CD

This project uses GitHub Actions to:
* build MSI samples
* validate installer logic
* run static checks
* publish documentation automatically to GitHub Pages

This ensures **reproducibility, safety and transparency**.

## Disclaimer

This project is for **educational and defensive purposes only**.  
No weaponized payloads are provided.