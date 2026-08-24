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
| `CVE-2026-77647` | SPIP | SPIP < 4.4.20 | Code Injection / RCE | Critical | [Read](./analyses/cve-2026-77647-spip-pre-auth-rce/) |
| `CVE-2026-19478` | GitLab B.V. | GitLab CE/EE 18.2-19.2.3 | Authorization Bypass | Critical | [Read](./analyses/cve-2026-19478-gitlab-graphql-bypass/) |
| `CVE-2026-55674` | Discourse Project | Discourse 3.5.0.beta2 - 2026.6.0 | XSS (Cache Poisoning) | Critical | [Read](./analyses/cve-2026-55674-discourse-xss/) |
| `CVE-2026-75143` | FFmpeg | FFmpeg 4.4 - 9.0 | Heap Buffer Overflow | Critical | [Read](./analyses/cve-2026-75143-ffmpeg-rist-heap-oob-write/) |
| `CVE-2026-18051` | BoldGrid | W3 Total Cache < 2.10.5 | Path Traversal (Arbitrary File Write) | Critical | [Read](./analyses/cve-2026-18051-w3-total-cache-arbitrary-file-write/) |
| `CVE-2026-18366` | Automast Ltd | Events Manager 7.1 - 7.4.0.1 | Privilege Escalation | Critical | [Read](./analyses/cve-2026-18366-events-manager-privilege-escalation/) |
| `CVE-2026-47686` | patriksimek (vm2 project) | vm2 <= 3.11.5 | Sandbox Escape / RCE | Critical | [Read](./analyses/cve-2026-47686-vm2-sandbox-escape-rce/) |
| `CVE-2026-15571` | Keycloak | Keycloak 26.7.x, 26.6.x | Authentication Bypass | High | [Read](./analyses/cve-2026-15571-keycloak-account-linking-auth-bypass/) |
| `CVE-2026-42945` | F5 / NGINX Inc | NGINX Open Source, NGINX Plus 0.6.27-1.30.0 | Heap Buffer Overflow | Critical | [Read](./analyses/cve-2026-42945-nginx-rift-heap-overflow/) |
| `CVE-2021-20295` | QEMU Project | QEMU 2.6.0-5.0.x; libslirp <= 4.3.0 | Out-of-Bounds Read | Medium | [Read](./analyses/cve-2021-20295-qemu-slirp-ipv6-oob-read/) |
| `CVE-2026-56654` | Gitea Project | Gitea 1.26.4 and earlier | Privilege Escalation | Critical | [Read](./analyses/cve-2026-56654-gitea-token-scope-escalation/) |
| `CVE-2026-19598` | The Pods Team | Pods - Custom Content Types and Fields 3.3.0-3.3.9 | Authorization Bypass | Critical | [Read](./analyses/cve-2026-19598-pods-auth-bypass/) |
| `CVE-2026-28185` | rtCamp | Log in with Google 1.4.2 | Auth Bypass | Critical | [Read](./analyses/cve-2026-28185-login-with-google-auth-bypass/) |
| `CVE-2026-34486` | Apache Software Foundation | Apache Tomcat 9.0.116, 10.1.53, 11.0.20 | Encryption Bypass / RCE | High | [Read](./analyses/cve-2026-34486-tomcat-tribes-rce/) |
| `CVE-2026-3195` | QEMU Project | QEMU 8.2.0-10.2.1 | Heap Buffer Overflow | High | [Read](./analyses/cve-2026-3195-qemu-virtio-sound-heap-oob/) |
| `CVE-2025-12464` | QEMU Project | QEMU 8.1.0 - 10.1.2 (e1000 network device) | Buffer Overflow | Medium | [Read](./analyses/cve-2025-12464-qemu-e1000-stack-oob/) |
| `CVE-2019-10349` | Jenkins Project | Jenkins Dependency Graph Viewer Plugin 0.13 | Stored XSS | Medium | [Read](./analyses/cve-2019-10349-jenkins-dependency-graph-stored-xss/) |
| `CVE-2026-3842` | QEMU Project | QEMU 7.1.0 - 10.2.1 | Out-of-Bounds Write | High | [Read](./analyses/cve-2026-3842-qemu-hv-syndbg-oob-write/) |
| `CVE-2026-18391` | Automattic (WooCommerce) | WooCommerce Subscriptions < 9.1.0 | PHP Object Injection / RCE | Critical | [Read](./analyses/cve-2026-18391-woocommerce-subscriptions-rce/) |
| `CVE-2026-67282` | fabrikar.com | Fabrik 1.0.0-4.6.7 | PHP Code Injection (RCE) | Critical | [Read](./analyses/cve-2026-67282-fabrik-rce/) |
| `CVE-2026-72772` | n8n | n8n <= 2.31.4, 2.32.0 | Authentication Bypass | High | [Read](./analyses/cve-2026-72772-n8n-auth-bypass/) |
| `CVE-2026-59083` | Apache Software Foundation | Apache Tomcat 8.5.0-11.0.23 | Auth Bypass (URL-Encoding Mismatch) | Critical | [Read](./analyses/cve-2026-59083-tomcat-url-encoding-bypass/) |
| `CVE-2026-59851` | libssh | libssh 0.12.0 | Authorization Bypass | High | [Read](./analyses/cve-2026-59851-libssh-gssapi-keyex-auth-bypass/) |
| `CVE-2026-12080` | QEMU Project / Red Hat | QEMU Guest Agent 5.2.0 - 11.0.3 | Privilege Escalation | High | [Read](./analyses/cve-2026-12080-qemu-guest-agent-privesc/) |
| `CVE-2026-72585` | Grafana Labs | Grafana 11.6.9 - 13.1.3 | Authorization Bypass | Medium | [Read](./analyses/cve-2026-72585-grafana-authorization-bypass/) |
| `CVE-2026-66915` | Fabrik | Fabrik 1.0.0-4.6.6 | Pre-Auth RCE | Critical | [Read](./analyses/cve-2026-66915-fabrik-rce/) |
| `CVE-2026-72568` | Redis Labs | Redis through 8.8.1 | Out-of-Bounds Read | High | [Read](./analyses/cve-2026-72568-redis-oob-read/) |
| `CVE-2026-72899` | Metabase | Metabase 0.58.0-0.63.4 (0.58.x - 0.63.x vulnerable range) | SQL Injection | Critical | [Read](./analyses/cve-2026-72899-metabase-sqli/) |
| `CVE-2026-72898` | Metabase | Metabase 0.58.0-0.63.4 | SQL Injection | Critical | [Read](./analyses/cve-2026-72898-metabase-sqli/) |
| `CVE-2024-7347` | F5 Networks / nginx project | nginx 1.5.13 - 1.27.0 | Buffer Over-read / DoS | Medium | [Read](./analyses/cve-2024-7347-nginx-mp4-dos/) |
| `CVE-2025-24813` | Apache Software Foundation | Apache Tomcat 9.0.0-9.0.98, 10.1.0-10.1.34, 11.0.0-11.0.2, 8.5.0-8.5.100 | Path Equivalence + Unsafe Deserialization | Critical | [Read](./analyses/cve-2025-24813-tomcat-rce/) |
| `CVE-2026-13001` | Podlove Project | Podlove Podcast Publisher 4.5.1 | RCE via Arbitrary File Upload | Critical | [Read](./analyses/cve-2026-13001-podlove-rce/) |
| `CVE-2026-34966` | Gitea | Gitea 1.26.4 and earlier | SSRF | High | [Read](./analyses/cve-2026-34966-gitea-ssrf/) |
| `CVE-2026-71285` | Uptime Kuma (louislam) | Uptime Kuma 2.1.0-2.5.0 | Stored XSS | High | [Read](./analyses/cve-2026-71285-uptime-kuma-matomo-stored-xss/) |
| `CVE-2026-71327` | Traefik Labs | Traefik 3.0.0-3.6.24 and 3.7.0-3.7.9 | Authorization Bypass | High | [Read](./analyses/cve-2026-71327-traefik-route-identity-collision/) |
| `CVE-2026-14364` | Automattic Inc. (WordPress plugin ecosystem) | TrueBooker - Appointment Booking and Scheduler System <= 1.2.3 | Auth Bypass / Account Takeover | Critical | [Read](./analyses/cve-2026-14364-truebooker-auth-bypass/) |
| `CVE-2026-4878` | kernel.org (libcap maintainers) | libcap 2.04 - 2.77 | TOCTOU Race Condition | Medium | [Read](./analyses/cve-2026-4878-libcap-toctou-race-privilege-escalation/) |
| `CVE-2026-17594` | Sonatype | Nexus Repository 3 (CE and Pro) 3.0.0-3.94.x | Privilege Escalation | High | [Read](./analyses/cve-2026-17594-nexus-privilege-escalation/) |
| `CVE-2026-64638` | WordPress | WordPress Core 4.7.0-7.0.2 | Pre-Auth RCE via XSS | High | [Read](./analyses/cve-2026-64638-wordpress-xss2shell-rce/) |
| `CVE-2026-71238` | DjangoCRM | DjangoCRM 0.91 - 2.4.0 | Information Disclosure | Critical | [Read](./analyses/cve-2026-71238-djangocrm-debug-disclosure/) |
| `CVE-2026-71269` | OpenJS Foundation | Node-RED 3.0.0-5.0.4 | Denial of Service | High | [Read](./analyses/cve-2026-71269-node-red-dos/) |
| `CVE-2026-35210` | OpenCTI Platform / Filigran | OpenCTI < 7.260326.0 | Authorization Bypass | High | [Read](./analyses/cve-2026-35210-opencti-authorization-bypass/) |
| `CVE-2026-9082` | Drupal | Drupal core 8.9.0 - 11.3.9 (PostgreSQL) | SQL Injection | Critical | [Read](./analyses/cve-2026-9082-drupal-sql-injection/) |
| `CVE-2026-42208` | BerriAI | LiteLLM 1.81.16-1.83.6 | SQL Injection | Critical | [Read](./analyses/cve-2026-42208-litellm-pre-auth-sqli/) |
| `CVE-2026-69251` | FlowiseAI | Flowise <= 3.1.2 | Code Injection / RCE | Critical | [Read](./analyses/cve-2026-69251-flowise-authenticated-rce/) |
| `CVE-2025-8110` | Gogs Project | Gogs 0.13.0-0.13.3 | Arbitrary File Write via Symlink Following | High | [Read](./analyses/cve-2025-8110-gogs-symlink-rce/) |
| `CVE-2026-66012` | SiYuan (Open Source) | SiYuan kernel 3.7.0 - 3.7.1 | Auth Bypass | Critical | [Read](./analyses/cve-2026-66012-siyuan-auth-bypass-admin-takeover/) |
| `CVE-2026-18363` | osTicket / Enhancesoft LLC | osTicket 1.17.x and 1.18.0-1.18.3 | Auth Bypass | Critical | [Read](./analyses/cve-2026-18363-osticket-password-reset-bypass/) |
| `CVE-2026-44966` | shepherdwind / Apache Velocity project | Velocity.js (velocityjs) 0.3.1 - 2.1.5 | Prototype Pollution | High | [Read](./analyses/cve-2026-44966-velocityjs-prototype-pollution/) |
| `CVE-2026-45668` | TriliumNext | Trilium Notes 0.0.9 - 0.102.1 | Path Traversal + RCE | Critical | [Read](./analyses/cve-2026-45668-trilium-notes-rce-path-traversal/) |
| `CVE-2026-47668` | DbGate | DbGate 7.1.8 and prior | Remote Code Execution | Critical | [Read](./analyses/cve-2026-47668-dbgate-rce/) |
| `CVE-2026-24061` | GNU Project | GNU Inetutils telnetd 1.9.3-2.7 | Argument Injection / Auth Bypass | Critical | [Read](./analyses/cve-2026-24061-inetutils-telnetd-auth-bypass/) |
| `CVE-2026-63030` | WordPress | WordPress 6.9.0-6.9.4, 7.0.0-7.0.1 | Route Confusion / RCE | Critical | [Read](./analyses/cve-2026-63030-wordpress-wp2shell-rce/) |
| `CVE-2026-42151` | Prometheus | Prometheus 2.48.0-3.5.2, 3.6.0-3.11.2 | Information Disclosure | High | [Read](./analyses/cve-2026-42151-prometheus-info-disclosure/) |
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
