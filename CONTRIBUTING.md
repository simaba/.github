# Contributing Guidelines

Thank you for your interest in contributing. These repositories focus on AI governance,
release readiness, responsible AI deployment, evaluation, agent systems, program-management tooling, and operational improvement.

## What We Welcome

- **New use cases** with realistic constraints
- **Documentation improvements** that make guidance clearer or more actionable
- **Framework extensions** such as new checklists, mappings, or governance patterns
- **Worked examples** with realistic inputs and outputs
- **Tooling improvements** for validators, CLIs, templates, and demo apps
- **Translations** that preserve technical accuracy

## Before you contribute

Use only fictional, synthetic, public, or fully sanitized material. Do not submit employer, customer, supplier, colleague, contract, pricing, road-map, architecture, prompt, benchmark, or user-data material that is not clearly safe to publish.

## How to Contribute

### 1. Open an issue first

Before opening a pull request, open an issue describing:

- what you want to add or change
- why it would help practitioners
- any relevant industry, regulatory, or implementation context

This avoids duplicated effort and helps keep each repository within scope.

### 2. Fork and branch

```bash
git clone https://github.com/simaba/<repo-name>
git checkout -b feature/your-descriptive-branch-name
```

### 3. Make the change practical

Please prefer:

- concrete examples over abstract claims
- reusable templates over one-off prose
- truthful maturity labels over aspirational wording
- clear boundaries between what is shipped, planned, and illustrative
- verifiable public sources over unsupported compliance or benchmark claims

### 4. Open a pull request

Include:

- a concise summary of the change
- the reason for the change
- any user-visible behavior change
- linked issue number when relevant
- tests or example validation when code, schemas, or structured artifacts change

## Contribution priorities by repository

| Repository | Strongest contribution types |
|---|---|
| [`everything-program-management`](https://github.com/simaba/everything-program-management) | program-management templates, fictional examples, schemas, CLI validation, tests |
| [`release-checklist`](https://github.com/simaba/release-checklist) | validator rules, example configs, tests, reporting improvements |
| [`release-governance`](https://github.com/simaba/release-governance) | release-stage criteria, gate definitions, lifecycle examples |
| [`governance-playbook`](https://github.com/simaba/governance-playbook) | operating-model patterns, governance artifacts, worked examples |
| [`ai-platform-pm-playbook`](https://github.com/simaba/ai-platform-pm-playbook) | AI-product templates, evaluation plans, build-versus-buy artifacts, fictional examples |
| [`automotive-llm-eval-harness`](https://github.com/simaba/automotive-llm-eval-harness) | synthetic evaluation cases, scoring tests, dataset documentation, reporting |
| [`agent-eval`](https://github.com/simaba/agent-eval) | evaluation scenarios, rubric design, measurable pass/fail criteria |
| [`agent-simulator`](https://github.com/simaba/agent-simulator) | new scenarios, simulator logic, evaluation extensions |
| [`harness-bench`](https://github.com/simaba/harness-bench) | synthetic benchmark tasks, scoring methodology, variance reporting, run schemas |
| [`prompt-harness-translator`](https://github.com/simaba/prompt-harness-translator) | supported-format fixtures, compatibility documentation, translation tests |
| [`decision-journal-agent`](https://github.com/simaba/decision-journal-agent) | fictional decision lifecycles, privacy-safe workflows, CLI and parsing tests |
| [`mcp-agent-risk-checklist`](https://github.com/simaba/mcp-agent-risk-checklist) | fictional MCP reviews, risk scoring, mitigation patterns, source-backed controls |
| [`ai-act-compliance-agents`](https://github.com/simaba/ai-act-compliance-agents) | provenance-aware traceability examples, schemas, tests, public source maintenance |
| [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance) | trust models, failure handling, governance controls |
| [`agent-orchestration`](https://github.com/simaba/agent-orchestration) | orchestration patterns, runnable examples, control-flow tradeoffs |
| [`accountability-patterns`](https://github.com/simaba/accountability-patterns) | accountability patterns, redress flows, oversight examples |
| [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide) | implementation examples, mappings, gap-closure guidance |
| [`regulated-ai`](https://github.com/simaba/regulated-ai) | template improvements, starter workflows, CI validation examples |
| [`ai-prism`](https://github.com/simaba/ai-prism) | high-quality curated resources, broken-link fixes, better categorization |
| [`lean-ai-ops`](https://github.com/simaba/lean-ai-ops) | app quality, analytics rigor, examples, export quality, tests |

## Quality bar

A contribution is much more likely to be accepted if it:

- matches the repository's actual scope
- improves clarity or practical usefulness
- includes at least one realistic example when adding a new concept
- avoids placeholder content presented as shipped capability
- keeps naming and cross-repo references consistent
- does not introduce public-safety, privacy, security, licensing, or attribution risk

## Code of Conduct

By contributing, you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions

Use [GitHub Discussions](https://github.com/simaba/governance-playbook/discussions) for broader questions about framework usage, repo direction, or contribution fit.
