# Security Policy

## Supported Versions

These repositories are primarily documentation and tooling resources.
The following versions receive security updates:

| Version | Supported |
|---------|-----------|
| Latest `main` branch | ✅ |
| Older releases | ❌ |

## Reporting a Vulnerability

If you discover a security vulnerability in any code within these repositories
(scripts, CLI tools, GitHub Actions workflows), please **do not include exploit
details in a public issue, discussion, or pull request**.

Use one of the following channels instead:

1. **GitHub Private Vulnerability Reporting**  
   Use the **Report a vulnerability** button in the Security tab of the affected
   repository, if it is enabled.
2. **Fallback when private reporting is unavailable**  
   Open a minimal public issue with the title prefix `[SECURITY]` **without**
   including reproduction steps, payloads, logs, or exploit details. The issue
   should only request a private follow-up channel.

## What to include in a report

Please include, when possible:

- affected repository and file path
- brief description of the issue
- impact assessment
- conditions required to reproduce
- suggested mitigation, if known

## Response Timeline

- **Acknowledgment:** within 48 hours
- **Initial assessment:** within 7 days
- **Fix or mitigation:** within 30 days for confirmed vulnerabilities, when feasible

## Scope

Security reports are relevant primarily for:

- Python scripts and CLI tools (`airc` package and related tooling)
- GitHub Actions workflow files
- configuration parsers, validators, and template-generation utilities

Documentation-only repositories (pure Markdown) have a reduced security surface,
but unsafe examples, script injection vectors, and dangerous automation guidance
are still in scope.

## Disclosure Policy

We follow coordinated disclosure. Once a fix is available, we will:

1. release a patched version or mitigation
2. credit the reporter in the release notes, unless they prefer anonymity
3. publish a brief advisory when appropriate
