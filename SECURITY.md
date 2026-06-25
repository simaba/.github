# Security Policy

## Supported Versions

These repositories are primarily documentation and lightweight tooling resources.
The following versions receive security updates on a best-effort basis:

| Version | Supported |
|---------|-----------|
| Latest `main` branch | ✅ |
| Older releases | ❌ |

## Reporting a Vulnerability

If you discover a security vulnerability in code within these repositories
(scripts, CLI tools, workflows, parsers, validators, or template-generation utilities), please **do not include exploit details in a public issue, discussion, or pull request**.

Use one of the following channels instead:

1. **GitHub Private Vulnerability Reporting**  
   Use the **Report a vulnerability** button in the Security tab of the affected repository, if it is enabled.
2. **Fallback when private reporting is unavailable**  
   Open a minimal public issue with the title prefix `[SECURITY]` **without** including reproduction steps, payloads, logs, or exploit details. The issue should only request a private follow-up channel.

## What to include in a report

Please include, when possible:

- affected repository and file path
- brief description of the issue
- impact assessment
- conditions required to reproduce
- suggested mitigation, if known

## Response expectations

These are personal, volunteer-maintained repositories. Response timing depends on severity, reproducibility, and maintainer availability.

- **Acknowledgment:** normally within 7 days when contact details are sufficient
- **Initial assessment:** best effort after acknowledgment
- **Fix or mitigation:** prioritized for confirmed issues with material impact

No response or remediation timeline is guaranteed. Please do not publicly disclose exploit details while a report is being assessed.

## Scope

Security reports are relevant primarily for:

- Python packages and command-line tools
- GitHub Actions workflow files
- configuration parsers and validators
- template-generation and benchmark-scoring utilities
- unsafe public examples, script-injection vectors, and dangerous automation guidance

Documentation-only repositories have a reduced security surface, but unsafe examples and misleading operational guidance are still in scope.

## Disclosure Policy

We follow coordinated disclosure. Once a fix is available, we will:

1. release a patched version or mitigation when appropriate
2. credit the reporter in release notes, unless they prefer anonymity
3. publish a brief advisory when the issue merits one
