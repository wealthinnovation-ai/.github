# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

**Do NOT open a public GitHub issue.**

Instead, email: **security@streamkinetics.com**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

## Response Timeline

| Action | Timeline |
|--------|----------|
| Acknowledgment | Within 24 hours |
| Initial assessment | Within 72 hours |
| Fix deployed | Within 7 days (critical) / 30 days (non-critical) |

## Supported Versions

Only the latest release on `main` and `staging` branches receive security updates.

## Infrastructure

Our infrastructure runs on Cloudflare's global network with:
- **Zero Trust** access controls (Cloudflare Access)
- **WAF** and DDoS protection
- **Encrypted at rest** (D1, R2, KV)
- **Encrypted in transit** (TLS 1.3)
- **IP allowlisting** for sensitive endpoints
