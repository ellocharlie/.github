# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any ellocharlie repository, please report it responsibly.

**Do NOT open a public GitHub issue for security vulnerabilities.** Public disclosure before a fix is in place puts everyone at risk.

### How to Report

Email: [security@ellocharlie.com](mailto:security@ellocharlie.com)

Please include:

- A description of the vulnerability and its potential impact
- The repository and file(s) affected (if known)
- Steps to reproduce or a proof-of-concept (if you have one)
- Your GitHub username or email so we can credit you if appropriate

### What to Expect

| Timeline | What happens |
|----------|-------------|
| Within 48 hours | We acknowledge receipt of your report |
| Within 7 days | We provide a detailed response: whether we can reproduce it, our assessment of severity, and a remediation plan |
| As needed | We may follow up to clarify details or test proposed fixes |
| On resolution | We notify you when the fix is deployed and coordinate public disclosure if appropriate |

We treat all security reports seriously. If you report something that turns out not to be a vulnerability, we will tell you why — we won't dismiss the report without explanation.

### Coordinated Disclosure

We follow a coordinated disclosure model. We ask that you:

- Give us a reasonable time (typically 90 days) to remediate before public disclosure
- Avoid accessing, modifying, or deleting data that does not belong to you
- Avoid disrupting service for other users

If we cannot remediate within the agreed timeline, we will work with you on a public disclosure plan.

---

## Supported Versions

We actively maintain and patch the following versions:

| Repository | Version | Supported |
|-----------|---------|-----------|
| `ellocharlie-engine` | 0.1.x | ✅ Yes |
| `ellocharlie-agents` | 0.1.x | ✅ Yes |
| `ellocharlie.com` | 0.1.x | ✅ Yes |
| `ellocharlie-content` | 0.1.x | ✅ Yes |

Older versions (once they exist) will receive security patches for 6 months after a major version release.

---

## Security Practices

The ellocharlie org follows these practices to reduce risk:

- **No secrets in version control.** API keys, tokens, and credentials are stored in GitHub Secrets and read from environment variables at runtime. Any committed secret is treated as compromised and rotated immediately.
- **Mandatory canary deploys.** All production deployments use a 5% canary with automatic rollback, limiting blast radius on bad deploys.
- **100% review coverage.** Every PR to `main` requires an approved review. No one self-merges.
- **Principle of least privilege.** Agent GITHUB_TOKENs are scoped to the minimum permissions required for each workflow.
- **Dependencies pinned.** Critical dependencies are pinned to specific versions and reviewed before bumping.

---

## Bug Bounty

We do not currently have a formal bug bounty program. We will always publicly credit researchers who responsibly disclose security vulnerabilities (if they consent to being credited). For significant findings, we may offer a goodwill token of our appreciation — reach out to discuss.

---

*This policy applies to all repositories in the [ellocharlie](https://github.com/ellocharlie) GitHub organization.*
