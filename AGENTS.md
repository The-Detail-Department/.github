# Organisation defaults

This public repository owns shared contribution/security guidance, issue and PR
templates, and the organisation profile. Product policy and private release
evidence belong in Ads, Data, Website or Brand.

Read `README.md` and `CONTRIBUTING.md`. Check current main, dirty files and open
PRs before editing; preserve concurrent work. Follow the current task's authority.
Do not copy credentials, client records, private evidence or personal local paths
into this public repository. Keep the profile and brand marks unchanged unless
they are part of the requested change.

For workflow changes, install `.github/requirements-ci.txt` in an isolated Python
environment and run `zizmor --offline --strict-collection .github/workflows .github/dependabot.yml`.
Validate changed template YAML and local links. Report review, CI and integration
separately. Dependabot, CODEOWNERS and workflows must be configured in each
consumer; GitHub does not inherit them from this defaults repository.
