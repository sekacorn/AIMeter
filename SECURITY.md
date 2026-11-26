# Security policy

## Supported versions

AIMeter is Beta software. Security fixes are applied to the latest release only.
Upgrade with `pip install -U aimeter-oss`.

## Published advisories

No security advisories have been published for `aimeter-oss`.

All advisories: [github.com/sekacorn/AIMeter/security/advisories](https://github.com/sekacorn/AIMeter/security/advisories).

## Reporting a vulnerability

Please do not report a suspected vulnerability in a public issue.

Report a suspected vulnerability privately with **Report a vulnerability** on the repository's
[Security tab](https://github.com/sekacorn/AIMeter/security) (direct link: [github.com/sekacorn/AIMeter/security/advisories/new](https://github.com/sekacorn/AIMeter/security/advisories/new)).
This is GitHub's private vulnerability reporting: the report stays private between you and the
maintainers until an advisory is published.

Include the affected version, reproduction steps and the impact you observed.
Never include real credentials or private data.

## Product notes


AIMeter is local-first and should not receive secrets in usage records. The CLI uses safe YAML loading, parameterized SQLite queries, CSV formula escaping, and metadata depth limits.
