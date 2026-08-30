# Contributing

## The one rule

**One person builds. A different person checks. Nobody merges their own work.**

This is not a code-review preference. It is how the whole operation runs, and it applies here without exception.

## Before you start

Open an issue first. A pull request that arrives without one is usually a pull request built against the wrong assumption.

Say what you are changing, why, and how you will know it worked.

## Branches

- `main` is protected and always deployable
- Branch from `main`: `type/short-description` — `fix/consent-mode-firing`, `feat/plan-versioning`
- Rebase before opening a pull request

## Commits

Conventional commits: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`.

Write the subject so it completes the sentence "this commit will…".

## Pull requests

- Small enough that a reviewer can hold it in their head
- Description explains the change and how it was verified
- Green checks before review, not after
- A reviewer who did not write the code

## What a reviewer is checking

Not style. Style is the linter's job.

A reviewer checks that the change does what it says, that failure is handled, that nothing reaches a live account without an approved instruction, and that the record makes sense to somebody reading it in six months.
