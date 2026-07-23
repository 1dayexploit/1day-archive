<div align="center">

<picture>
  <img src="https://1dayexploit.com/assets/Logo-PNG.png" alt="1dayexploit" width="200" />
</picture>

# 1dayexploit - archive

**Technical deep-dives and root cause analyses of recently disclosed CVEs.**

[![Website](https://img.shields.io/badge/web-1dayexploit-443A48?style=flat-square)](https://1dayexploit.com)

</div>

---

## About

This repository collects technical write-ups of recently disclosed CVEs — the 1-day window between patch release and widespread exploitation.

Each analysis contains:

- Affected product, vendor, and version range
- Patch diff and root cause analysis
- Proof-of-concept demonstrating the vulnerability
- Detection guidance for defenders
- References to the original disclosure

---

## Analyses

| CVE | Vendor | Product | Class | Severity | Write-up |
|-----|--------|---------|-------|----------|----------|
| `CVE-2026-37709` | Grokability | Snipe-IT 8.4.0 and before | Authorization Bypass | Critical | [Read](./analyses/cve-2026-37709-snipe-it-authorization-bypass/) |
| `CVE-2026-33589` | - | Open Notebook 1.8.3 | Path Traversal / LFI | High | [Read](./analyses/cve-2026-33589-open-notebook-lfi/) |
| `CVE-2026-7482` | Ollama Project | Ollama < 0.17.1 | Heap Out-of-Bounds Read / Info Disclosure | Critical | [Read](./analyses/cve-2026-7482-ollama-heap-oob-read/) |
| `CVE-2026-27960` | OpenCTI-Platform | OpenCTI 6.6.0-6.9.12 | Authentication Bypass | Critical | [Read](./analyses/cve-2026-27960-opencti-auth-bypass/) |

> Full analyses live in their own subdirectories. Browse [`/analyses`](./analyses) for the complete list.

---

## The Collective

1dayexploit is a small, closed team of offensive security researchers publishing technical deep-dives into recently disclosed vulnerabilities.

For our own coordinated-disclosed CVEs, see [`advisories`](https://github.com/1dayexploit/advisories).

---

<div align="center">

<sub>Responsible research. Defenders and red teamers alike.</sub>

</div>
