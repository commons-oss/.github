# Security Policy

## Reporting a vulnerability

Please **do not** open public issues for security vulnerabilities.

Report privately via [GitHub Security Advisories](https://github.com/commons-oss/.github/security/advisories/new). This creates a private channel between you and the maintainers.

If you can't use GitHub Security Advisories, email `security@commons-oss.org` (pending domain registration).

## What to include

- Affected repo and version (or commit SHA).
- A short description of the issue and its impact.
- Steps to reproduce, ideally with a minimal proof of concept.
- Your disclosure preference (credit, anonymous, embargo timeline).

## Response

- Acknowledgement within 72 hours.
- Triage and severity assessment within 7 days.
- Fix or mitigation plan within 30 days for high/critical issues.
- Coordinated disclosure once a fix is available, with credit unless you prefer otherwise.

## Supported versions

Commons OSS is in early development. Only the `main` branch of each repo receives security fixes until we cut tagged releases.

## Out of scope

- Vulnerabilities in third-party dependencies (please report upstream first; we'll bump versions promptly).
- Issues in self-hosted deployments caused by misconfiguration outside the project's defaults.
- Denial-of-service via resource exhaustion in development tooling.
