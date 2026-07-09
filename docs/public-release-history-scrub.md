# Public-Release History Scrub Checklist

Use this checklist before making a repository public or promoting it as part of the portfolio. A clean search of the current default branch is useful, but it is not the same as a full repository-history review.

## Scope to review

Check all of the following before treating a repository as publication-ready:

- current default branch files
- non-default branches
- tags and releases
- closed and open pull requests
- issues and issue comments
- GitHub Actions logs and artifacts
- attached images, datasets, exports, notebooks, and generated reports
- full git history reachable from all refs

## Public-safety boundaries

Do not publish material that reveals or implies:

- employer, customer, supplier, or colleague-specific information
- unreleased product behavior, roadmap details, release criteria, internal architecture, or decision records
- proprietary metrics, incident reports, escalation paths, internal tooling, prompts, endpoints, or configuration
- personal emails, phone numbers, account IDs, keys, tokens, private URLs, or credentials
- real user data, telemetry, location traces, vehicle identifiers, logs, or screenshots

Use fictional or fully sanitized examples. Make limits explicit when a repo is a prototype, checklist, framework, or illustrative starter kit rather than a production system, legal tool, safety case, or compliance certification.

## Suggested local commands

Run from a fresh clone after fetching all refs:

```bash
git fetch --all --tags --prune

git grep -nI -E 'Mercedes|MB\.OS|Daimler|BBAC|@mercedes-benz\.com|@daimler\.com|ghp_|github_pat_|AKIA|BEGIN (RSA|OPENSSH|EC|DSA) PRIVATE KEY' $(git rev-list --all)

git log --all --decorate --oneline --stat

git branch -a

git tag -l
```

Also search for any project-specific names, suppliers, internal acronyms, personal contacts, and example data that could be traced back to a real person, company, program, or decision.

## If sensitive material is found

Removing a file from `main` is not enough if the material exists in git history, PRs, releases, logs, or artifacts.

Recommended response:

1. Revoke exposed credentials or tokens immediately.
2. Remove public releases, artifacts, or logs that expose the material.
3. Rewrite repository history only when needed and only after understanding the impact on forks and clones.
4. Force-push rewritten refs only when the repository owner intentionally accepts that disruption.
5. Re-run the full scrub after remediation.
6. Document the remediation privately; do not describe the sensitive material in public issue or PR text.

## Review record

When a manual scrub is completed, record:

- repository name
- date
- refs reviewed
- search terms used
- whether Actions logs/artifacts and releases were checked
- whether any history rewrite or credential revocation was required

Do not claim that a repo passed a full privacy scrub unless the full scope above was actually reviewed.
