# Contributing

## Working context

Read the selected repository's `AGENTS.md`, `README.md` and relevant product
specifications. The current task and supplied working agreement govern authority.
Keep product policy in its owning repository; these defaults describe shared practice.

## Before you start

Use an issue or the user's task as the work reference. Name the outcome, current
base commit, owned files and validation before editing. Check dirty paths,
worktrees and open PRs; preserve active work and use an isolated task branch.

## Branches

- Branch from current `origin/main`: `type/short-description`.
- Fetch and recheck a moving base before integration; preserve shared branches.
- Verify actual repository rules. Guidance and green CI do not establish an
  enforced protection, publication approval or a deployable artifact.

## Commits

Conventional commits: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`.

Write the subject so it completes the sentence "this commit will…".

## Pull requests

- Small enough that a reviewer can hold it in their head
- Description explains the change and how it was verified
- Appropriate checks, with exact commands and results
- Independent review of the current head, clearly attributed
- Existing merge/deployment authority and any remaining live checks

An agent reviewing its own change is not an independent review. A separate
reviewer may be used when the task authorizes it; record its scope and limitations.
Merge only under the authority already supplied for the task. Do not infer it
from passing checks or introduce a new approval gate when it is already supplied.

## What a reviewer is checking

A reviewer checks the intended behavior, relevant failure paths, data/tenant
boundaries and whether the evidence supports the claims. Source validation must
not use production credentials or write to real user data. A live action needs
its applicable authority and evidence. Keep implemented, locally verified,
merged, deployed and observed results distinct.

## Tools and handoff

Prefer a suitable CLI or connector; use browser automation for UI work and gaps.
Batch independent reads, keep searches bounded and reuse results until inputs
change. Avoid duplicating agent instructions, skills or external integrations.
Read a relevant skill once and add a hook or MCP only for a demonstrated need.

Finish with changed files, checks, limitations and the next authorized action.
Keep detailed task evidence in its task or PR, not in persistent agent guidance.
Archive unique work reversibly and remove linked worktrees through Git only
after checking their commits and dirty files.
