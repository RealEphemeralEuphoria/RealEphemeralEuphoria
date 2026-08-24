# Alice

**IT engineer focused on identity infrastructure, lifecycle automation, and reliable internal systems.**

A lot of my work starts with the same kinds of problems: access changes, onboarding, integrations that need babysitting, and processes that only one person understands. I build systems with one place for policy, safe defaults, useful logs, less manual upkeep, and a clear recovery path when something breaks.

[LinkedIn](https://linkedin.com/in/alice-l-248502224)

![A systems landscape showing source attributes flowing through policy and lifecycle orchestration to SaaS, endpoint, and cloud state.](./assets/identity-platform-landscape.svg)

## Identity platform work

| Identity architecture | Lifecycle automation | Reliability &amp; controls |
| --- | --- | --- |
| Led a phased Identity Provider migration for 400 users with zero downtime, validation checkpoints, and rollback planning. Configured 200+ SaaS SSO/SAML integrations, including attribute mappings and authorization troubleshooting. | Built HRIS-to-Okta onboarding that reduced setup from 4 hours to 30 minutes. Built 50+ Okta Workflows and API/webhook integrations across 15+ SaaS platforms for lifecycle, licensing, compliance, and operational data sync. | Built security triage and remediation workflows that reduced response time from 4 hours to 15 minutes. That work is backed by monitoring, audit evidence, runbooks, and recovery paths. |

## How I approach identity

Identity touches nearly every internal system. I start with a reliable source of truth, make roles and policies explicit, and automate joiner, mover, and leaver changes so people are not fixing the same account problems by hand. Workflows need logs, clear ownership, and a way to recover when something goes wrong. The goal is a safer default path and less manual work for the operators who support it.

## Selected public work

### [Meshtastic Hardware Guide](https://github.com/RealEphemeralEuphoria/mesh-guide)

<a href="https://github.com/RealEphemeralEuphoria/mesh-guide"><img src="https://raw.githubusercontent.com/RealEphemeralEuphoria/mesh-guide/main/docs/mesh-guide.png" alt="Meshtastic Hardware Guide interface" width="680"></a>

Independent hardware research in an offline-first, single-file web application. It brings device comparisons, radio constraints, power, antennas, sensors, and self-build paths into one field-friendly guide.

### [Dalamud Release Skill](https://github.com/RealEphemeralEuphoria/dalamud-release-skill)

[![Dalamud release workflow](./assets/dalamud-release-flow.svg)](https://github.com/RealEphemeralEuphoria/dalamud-release-skill)

Release automation for FFXIV plugins that computes manifest metadata, preserves intentionally small diffs, and makes stable, testing, and promotion workflows repeatable.

## Current focus

I am experimenting with Terraform-managed Okta configuration so identity changes can move from click-driven wizards toward reviewable code. Recent platform work has included AWS Lambda, Kubernetes, Terraform, Terragrunt, and Temporal workflows.

I support AI-enabled delivery infrastructure and deployed Hindsight on Kubernetes so internal teams can share operational context across AI workflows. I prefer local-first, self-hosted AI systems and open tooling. I build vendor-independent alternatives when data control, portability, or shared team context matter. OpenAI, Anthropic, and Cursor can be useful, but I do not want a team's workflow or knowledge trapped in one vendor ecosystem.

I use AI as workflow leverage when it has human review, access controls, and a clear recovery path. It is not a substitute for operations.

<details>
<summary><strong>Platform toolkit</strong></summary>

Identity: Okta · Microsoft Entra ID · JumpCloud · SAML · OAuth · OIDC · SCIM · RBAC<br>
SaaS &amp; endpoint: Google Workspace · Slack · Microsoft 365 · Workspace ONE · Kandji<br>
Automation: Python · PowerShell · REST APIs · Temporal<br>
Infrastructure: AWS · Kubernetes · Terraform · Terragrunt · Docker · PostgreSQL
AI systems: Hindsight · self-hosted models · open tooling · local-first workflows

</details>
