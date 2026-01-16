# Contributing to MSI Abuse Toolkit

Thank you for your interest in contributing to this repository.

This project aims to be a **comprehensive knowledge base and research framework** focused on **Windows Installer (MSI/MSP) abuse techniques**, covering offensive, defensive, and detection perspectives.

Due to the nature of the subject, contributions are welcome — but **not unrestricted**. This repository intentionally documents **real-world abuse techniques**, including exploitation and evasion aspects, while maintaining a clear research and defensive intent.

---

## Project Philosophy

This repository is intended to:

- Document **how Windows Installer can be abused in real environments**
- Preserve **technical knowledge** that is often fragmented or undocumented
- Enable **defenders to understand attacker tradecraft**
- Serve as a **reference for red, blue, and purple teams**

This is **not** a turnkey exploitation framework, but it **does not shy away from offensive reality**.

---

## Scope of Accepted Contributions

### ✅ Accepted and Encouraged Contributions

- Detailed documentation of MSI/MSP abuse techniques
- Proof-of-concept tooling demonstrating:
  - execution
  - persistence
  - privilege escalation
  - lateral or indirect effects
- Detection strategies (logs, heuristics, Sigma rules, correlations)
- EDR / AV evasion **as a research subject**, including:
  - behavioral observations
  - detection gaps
  - comparative analysis
- Hardening and mitigation guidance
- Reverse engineering insights
- Lab environments and reproducible research setups
- CI/CD, testing, or automation improvements
- Analysis of historical or publicly known vulnerabilities
- Zero-day research **at a conceptual or non-weaponized level**

---

### ❌ Contributions That Will Be Rejected

- Fully automated, one-click exploitation frameworks
- Undocumented obfuscated payloads without explanation
- Malware-as-a-service style components
- Live C2 infrastructure or production-ready implants
- Contributions designed solely to bypass safeguards without analysis
- Content that violates GitHub Terms of Service or applicable laws

If a contribution focuses on evasion or exploitation, it **must include explanation, context, and limitations**.

---

## Zero-Day & Sensitive Research

Zero-day related research is allowed **under strict conditions**:

- No active exploitation of unpatched systems
- No weaponized payloads targeting unknown vulnerabilities
- Clear documentation of impact and scope
- Responsible handling and intent declaration

If you are unsure whether your contribution qualifies, **open an issue before submitting a pull request**.

---

## Contribution Workflow

1. Fork the repository
2. Create a branch using one of the following prefixes:
   - `feature/<short-description>`
   - `fix/<short-description>`
3. Commit with clear and descriptive messages
4. Open a Pull Request including:
   - Description of the contribution
   - Offensive / defensive / research intent
   - Known limitations or risks
   - Any ethical or operational considerations

Pull requests may be reviewed for:
- technical accuracy
- safety
- clarity
- alignment with project goals

---

## Code & Documentation Guidelines

- Prefer **clarity over stealth**
- Avoid unnecessary obfuscation unless explicitly explained
- Comment non-obvious behaviors
- Document prerequisites and side effects
- Ensure demonstrations are **reproducible and reversible**
- Keep destructive actions clearly marked

---

## Legal & Ethical Notice

By contributing, you confirm that:

- You have the right to submit the content
- The contribution is for research and educational purposes
- You understand the potential impact of the documented techniques
- You accept that contributions may be modified or rejected by the maintainer

The maintainer reserves the right to restrict, redact, or remove content if required.

---

## Reporting Concerns

If you believe a contribution introduces:
- legal risk
- ethical concerns
- unintended weaponization

Do not open a public issue.  
Contact the maintainer directly via GitHub.

---

Thank you for contributing to responsible and realistic security research.
