# Security

Our project repositories are private and have no external users, so most of the usual public security process does not apply. This file covers what still matters.

## Reporting a concern

> [!IMPORTANT]
> Never report a leaked credential or a vulnerability in a public place. Report it privately so it can be fixed before it spreads.

- **A leaked token, key or password:** tell an organisation owner privately and straight away so it can be replaced. The owners are listed on the [People tab](https://github.com/orgs/ENGNERDS/people).
- **A vulnerability in anything we publish:** use the private report on the affected repository: the Security tab, then Report a vulnerability.

## What we never commit

Tokens, keys, passwords, webhook addresses, signing secrets, personal data and raw datasets. Every repository blocks the common ones with automated checks. A replaced secret is harmless, so reporting a leak quickly is always the right move.

Each project repository can add its own `SECURITY.md` for risks specific to it.
