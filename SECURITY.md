# Security Policy

## Supported Versions

These repositories are primarily documentation and tooling resources.
The following versions receive security updates:

| Version | Supported |
|---------|-----------|
| Latest main branch | ✅ |
| Older releases | ❌ |

## Reporting a Vulnerability

If you discover a security vulnerability in any code within these repositories
(scripts, CLI tools, GitHub Actions workflows), please **do not** open a public issue.

Instead, please report it via one of these channels:

1. **GitHub Private Vulnerability Reporting** — Use the "Report a vulnerability" button
   in the Security tab of the affected repository (if enabled)
2. **Direct contact** — Open a regular GitHub issue with the title prefix `[SECURITY]`
   and avoid including exploit details in the public issue body; we will follow up privately

## Response Timeline

- **Acknowledgment**: Within 48 hours of report
- **Assessment**: Within 7 days
- **Fix or mitigation**: Within 30 days for confirmed vulnerabilities

## Scope

Security reports are relevant primarily for:
- Python scripts and CLI tools (`airc` package and related tooling)
- GitHub Actions workflow files
- Any configuration parsers or validators

Documentation-only repositories (pure Markdown) have a reduced security surface
but dependency injection or script injection in YAML/JSON examples is still in scope.

## Disclosure Policy

We follow coordinated disclosure. Once a fix is available, we will:
1. Release a patched version
2. Credit the reporter in the release notes (unless they prefer anonymity)
3. Publish a brief advisory in the repository's Security tab
