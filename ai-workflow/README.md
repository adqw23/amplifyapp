# Engineer–Developer Workflow

This folder coordinates two distinct roles:

- **Codex/ChatGPT — Engineer:** investigates, creates the technical plan, defines safety and acceptance criteria, and reviews results.
- **Claude — Developer:** implements the approved plan, tests the change, and reports the evidence.
- **User — Approval Authority:** approves scope and every commit, push, merge, migration, deployment, or production action.

## Files

- `ENGINEERING_PLAN.md` — approved requirements and implementation plan.
- `IMPLEMENTATION_REPORT.md` — Developer preflight, changes, tests, and risks.
- `ENGINEERING_REVIEW.md` — Engineer decision and required corrections.
- `WORKFLOW_RULES.md` — shared roles, safety rules, evidence, and approval gates.

## Normal cycle

1. The Engineer investigates and completes `ENGINEERING_PLAN.md`.
2. The user approves the plan.
3. The Developer performs preflight, implements only the approved scope, tests it, and completes `IMPLEMENTATION_REPORT.md`.
4. The Engineer reviews the report, diff, and test evidence, then completes `ENGINEERING_REVIEW.md`.
5. The Developer makes any required corrections.
6. The user separately approves the next Git or production action.

Never have both roles edit the same working tree at the same time. Preserve all unrelated and uncommitted work.
