# 🧩 MSI Abuse Toolkit

## Overview

This project explores how Windows Installer (MSI/MSP) can be abused as an attack vector in enterprise Windows environments.

> ⚠️ **Important Notice**
>
> This repository documents real-world abuse techniques related to Windows Installer.
> Some content includes exploitation and evasion research.
> All demonstrations are intended for controlled environments only.

It provides:
* reproducible **abuse scenarios**
* **offensive demonstrations**
* **detection strategies**
* **hardening recommendations**

The goal is to help **red teams, blue teams and security engineers** understand and mitigate a largely undocumented attack surface.

## Intended Audience

This project is intended for:
- Red team operators
- Blue team & detection engineers
- Security engineers
- Windows / Active Directory specialists
- SOC and DFIR practitioners

It assumes basic familiarity with Windows internals and enterprise environments.

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

## Scope & Non-Goals

### In Scope
- Windows Installer (MSI/MSP/MST) abuse techniques
- Execution, persistence, and repair mechanisms
- Detection gaps and behavioral analysis
- EDR / AV evasion as a research topic
- Hardening and mitigation strategies
- Reproducible lab environments

### Out of Scope
- Turnkey exploitation frameworks
- Malware-as-a-service tooling
- Live C2 infrastructure
- Blind copy-paste attack playbooks

## Research Focus

This repository focuses on:
- Under-documented MSI behaviors
- Living-off-the-land abuse scenarios
- Enterprise-relevant attack paths
- Detection blind spots
- Defensive trade-offs and limitations

The emphasis is on **understanding behaviors**, not maximizing stealth.

## Project Structure

```
msi-abuse-toolkit/
│
├── offensive/        -> controlled abuse techniques (lab only)
├── defensive/        -> detection & mitigation
├── labs/             -> vulnerable MSI samples and walkthroughs
└── docs/             -> research documentation
```

## CI/CD

This project uses GitHub Actions orchestrating Dagger pipelines to:
- build and validate MSI samples
- ensure reproducible research environments
- run static and consistency checks
- publish documentation automatically

Using Dagger ensures pipeline portability and reproducibility across environments.

## Disclaimer

This project is provided for **research and educational purposes only**.

All techniques must be used in controlled environments and with explicit authorization.
The author assumes no responsibility for misuse.