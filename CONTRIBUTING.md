# Contributing

Thanks for your interest in Commons OSS.

## Before you start

- Read the [Code of Conduct](./CODE_OF_CONDUCT.md).
- For non-trivial changes, open an issue first to discuss the approach.
- For security issues, see [SECURITY.md](./SECURITY.md) — do not open a public issue.

## Contributor License Agreement (CLA)

All contributions require signing our [CLA](./CLA.md). On your first pull request, the [CLA Assistant](https://github.com/apps/cla-assistant) bot will comment with a link and a one-line phrase to reply with — that reply counts as your signature. Subsequent PRs are not re-prompted.

The CLA grants Commons OSS the right to re-license contributions under the commercial license (proceeds fund maintenance), while everything stays AGPL-3.0-or-later for the community.

If you can't or don't want to sign, your contribution can't be merged — but we appreciate the time regardless.

## Workflow

1. Fork and branch from `main`.
2. Conventional Commits for commit messages: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`.
3. Run the repo's lint + test scripts before pushing.
4. Open a PR. Fill in the template. Link the issue.
5. A maintainer reviews. Expect a response within 7 days.

## Local development

Each repo has its own setup steps in its README. The monorepo at [commons-oss/commons-oss](https://github.com/commons-oss/commons-oss) uses pnpm + Turborepo — `pnpm install` then `pnpm build`.

## What we're looking for

- Bug fixes with a reproduction.
- Documentation improvements (typos, clarifications, translations).
- Features that match the project's scope — open an issue first.
- Translations into other languages — German and English are first-class; others welcome.

## What we're not looking for

- Cosmetic refactors that change formatting without behavior change.
- New abstractions without a concrete use case.
- Vendor lock-in (cloud-only features, proprietary services).

## License

By contributing, you agree your contributions are licensed under AGPL-3.0-or-later, and you grant the project the rights described in the CLA.
