## Description
<!-- What does this change do, and why is it needed? -->

## Ticket
https://animoto.atlassian.net/browse/<TICKET-KEY>

## How has this been tested?
<!-- Tests, commands, or manual steps, and what they showed. -->

## Dependencies
<!-- PRs, config changes, flags or deploys that must land first. Delete if none. -->

## Blast Radius Impact (required)
<!--
Check exactly one. Use the highest tier that applies: one matching item is enough.
Judge what the change could do if it is wrong, not how confident you are that it is right.
-->
- [ ] **High**: billing, payments or entitlements; infrastructure; authentication or authorization; anything that can delete, overwrite or orphan persisted data; anything hard to reverse once shipped (a destructive migration, a published package version, a production flag default).
  **A human review must be completed before merge.**
- [ ] **Medium**: new endpoints; schema changes that are not destructive; non-trivial logic changes; changes whose blast radius crosses services or repos.
  **May merge without a pre-merge human review, but is flagged for human review after merge.**
- [ ] **Low**: documentation, tests, refactors with no behavior change, dependency bumps.
  **Existing review norms apply; no added gate.**

Why this tier:
<!-- One or two lines: what is the worst plausible outcome if this change is wrong? -->

## Agent Decision Log
<!--
Written by the implementing agent (or by you, if no agent was involved).
For Medium and High PRs, complete this thoroughly: it is the reviewer's primary tool
for verifying decisions the agent made on its own. For Low PRs, a line or two is enough.
Write "N/A: no agent involved" only if that is true.
-->

### Assumptions
<!-- Things taken as true without confirming them. Say how each could be checked. -->
-

### Decisions
<!-- Choices made where the ticket or code did not dictate the answer, with the alternative rejected and why. -->
-

### What the reviewer should verify
<!-- The specific claims above that a human should check, most important first. -->
-
