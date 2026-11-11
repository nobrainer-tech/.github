# Security policy

This policy covers every repository owned by
[nobrainer-tech](https://github.com/nobrainer-tech) that has no security policy
of its own. A repository with its own `SECURITY.md` follows that file instead.

## Reporting a vulnerability

Please do not report a vulnerability in a public issue, pull request or
discussion. Report it privately through GitHub:

1. Open the affected repository.
2. Go to **Security** → **Report a vulnerability**
   (`https://github.com/nobrainer-tech/<repository>/security/advisories/new`).

Include:

- the repository and the commit, tag or release you tested;
- what an attacker can do, and what they need first;
- the smallest steps that reproduce it;
- a safe way to check a fix.

Remove passwords, tokens, keys and personal data from the report. If you found
a secret that was committed by mistake, say where it is; do not use it.

## What happens next

We try to reply within 7 days. We confirm whether we can reproduce the issue,
fix it in the latest version, and credit you in the advisory unless you prefer
to stay anonymous. If we decide it is not a vulnerability, we say why.

Please give us a reasonable time to release a fix before you disclose the issue
publicly.

## Supported versions

Only the latest commit on the default branch, and the latest release where a
project publishes releases, receive security fixes.

## Out of scope

- Vulnerabilities in third-party tools, models or services, unless our code
  causes them. Report those to their maintainers.
- Forks of other projects: report to the upstream project.
- Findings that need physical access to a user's machine or an already
  compromised account.
