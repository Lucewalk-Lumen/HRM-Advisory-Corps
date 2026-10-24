# hrm-advisory-corps

**HRM 实战参谋团** · v1.0.1 · `team`

> China-market HRM consulting: one orchestrator plus eight specialists across org planning, recruiting pipeline, talent sourcing, talent development, performance management, compensation strategy, personality assessment and **labor compliance**, gated by a unified compliance layer.

Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.

## What it does

An HR consulting bench organized along the **HR value chain**, not generic chat. Give it a real problem — "restructure a 200-person sales org", "build a hiring pipeline for a hard-to-fill engineering role", "check our new attendance policy against labor-law risk" — and the orchestrator routes it to the right specialist, runs a standard operating procedure, and returns structured deliverables: org charts, screening lists, scorecards, pay-band proposals, compliance checklists.

Specialist coverage:

- **Org planning** — structure design and headcount planning
- **Recruitment pipeline** — role scoping, funnel design, process control
- **Talent sourcing** — channel strategy and candidate outreach; candidate PII handled the compliant way (desensitized archives, encrypted PII vault, plaintext never touching ordinary files)
- **Talent development** — development paths and training design
- **Performance management** — KPI/OKR systems and appraisal design
- **Compensation strategy** — pay bands and incentive structures
- **Personality assessment** — structured personality-based evaluation (SBTI)
- **Labor compliance** — China labor-law risk checks before any HR decision lands

A shared `hr-practice-library` grounds all eight specialists in the same practice base; `hrm-solution` provides cross-domain solution templates.

## How it works

- **Single routing baseline** — intent routing reads one `routing.yaml`; every request lands on exactly one specialist or one SOP. No ad-hoc guessing, no double dispatch.
- **Standard SOPs, pure orchestration** — the lead composes phases, assigns each phase to a member, and assembles the final report. Specialists execute their phase and return on contract.
- **Preset workflows** — scenario-triggered shortcuts for recurring engagements, so you don't re-explain your situation every session.
- **Observable collaboration** — every SOP phase emits a three-column status table (task / owner / state). Member return contracts include timeout fallbacks, so a stalled member never silently drops your request.
- **Hard guardrails** — an explicit forbidden-behavior list; anything touching termination, salary cuts or legal exposure is escalated to the labor-compliance specialist before output.

## Agent roster

| Agent | Role |
|---|---|
| `hrm-advisory-corps-lead` | Orchestrator — routing, SOP composition, final assembly (韩明轩) |
| `org-planning` | Org structure & headcount |
| `recruitment-pipeline` | Hiring funnel design & control |
| `talent-sourcing` | Sourcing & compliant candidate outreach |
| `talent-development` | Development paths & training |
| `performance-management` | KPI/OKR & appraisal systems |
| `compensation-strategy` | Pay bands & incentives |
| `personality-assessment` | Personality-based evaluation (SBTI) |
| `labor-compliance` | China labor-law risk control |

## Skills

`hrm-solution` · `hr-practice-library` · `org-planning` · `recruitment-pipeline` · `talent-sourcing` · `talent-development` · `performance-management` · `compensation-strategy` · `personality-assessment` · `labor-compliance`

## Privacy engineering

Candidate and employee data get dedicated treatment: talent archives store **desensitized views only**, plaintext contact details live in an **encrypted PII vault**, and the package ships with its own `PRIVACY.md` describing exactly what is stored where.

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/hrm-advisory-corps/releases) or clone this repo;
2. Unzip keeping the `.codebuddy-plugin/` manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.1**. See the package manifest for details.

## License

MIT — see [LICENSE](LICENSE).
