# .github

Organisation defaults for The Detail Department.

| Path | What it does |
|---|---|
| `profile/README.md` | The public organisation profile |
| `brand/` | The mark, light and dark fields |
| `SECURITY.md` `CONTRIBUTING.md` `CODE_OF_CONDUCT.md` `SUPPORT.md` | Inherited by every repository without its own |
| `.github/ISSUE_TEMPLATE/` `.github/PULL_REQUEST_TEMPLATE.md` | Default issue and pull request templates |
| `.github/dependabot.yml` | **Not inherited.** Copy into each repository. |

## Agent support

Ads, Data, Website and Brand each maintain a standalone `AGENTS.md`, a Claude
import, a concise Copilot adapter and `docs/AGENT-SETUP.md`. Their dependency
setup workflows prepare ephemeral Linux agents without production credentials.
Product build/test workflows remain owned and runnable in each repository.

`CODEOWNERS`, workflows and Dependabot configuration are repository-specific;
they are not inherited defaults. This repository checks its own workflow
configuration. [CONTRIBUTING.md](CONTRIBUTING.md) describes shared work, review and
handoff practice. Do not assume a private repository has enforced branch rules:
verify its actual settings and plan support before claiming that protection.
