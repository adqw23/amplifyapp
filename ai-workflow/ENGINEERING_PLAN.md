# Engineering Plan

## Status

- Plan ID:
- Project:
- Repository:
- Prepared by: Codex/ChatGPT — Engineer
- Date:
- Status: Draft | Ready for approval | Approved | Superseded
- User approval reference:

## Problem statement

Describe the observed problem, affected users, and business or technical impact.

## Verified current state

List evidence confirmed from the repository, logs, environment, documentation, or reproduction steps.

## Assumptions and unknowns

List anything not yet verified. Do not present assumptions as facts.

## Required outcome

State the behavior that must exist after implementation.

## In scope

-

## Out of scope

-

## Proposed technical approach

Describe the architecture, data flow, interfaces, algorithms, and expected files or components.

## Safety and preservation constraints

- Preserve all unrelated and uncommitted work.
- No destructive Git operations.
- No commit, push, merge, deployment, migration, or production change without separate user approval.
- Add project-specific constraints here.

## Implementation sequence

1. Perform and record repository preflight.
2.

## Test plan

### Automated tests

-

### Manual verification

-

### Regression checks

-

## Acceptance criteria

- [ ]

## Rollback plan

Describe how to reverse the application change safely. Production rollback remains a separate operation.

## Stop conditions requiring engineering review

- Repository state differs materially from this plan.
- Required behavior cannot be achieved without expanding scope.
- Existing data, compatibility, or security could be affected unexpectedly.
- Tests fail for reasons not explained by the approved change.
- Production access or irreversible action would be required.

## Instructions to Claude

Follow `CLAUDE.md` and `ai-workflow/WORKFLOW_RULES.md`. Implement only after user approval. Complete `ai-workflow/IMPLEMENTATION_REPORT.md` and stop before commit, push, merge, deployment, migration, or production action unless the user explicitly approves that exact action.
