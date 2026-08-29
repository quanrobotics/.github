# Contributing to QuanRobotics

Thank you for contributing to QuanRobotics.

All technical contributions should follow the workflow below.

## 1. Start With an Issue

Non-trivial work should begin with an approved GitHub issue.

Select the appropriate issue type:

- Bug Report
- Feature Request
- Engineering Task
- Research Task
- Documentation Task

The issue should clearly define:

- Objective
- Scope
- Acceptance criteria
- Dependencies
- Owner
- Reviewer
- Required evidence

## 2. Branch Naming

Use one of the following formats:

- `feature/<short-name>`
- `fix/<short-name>`
- `docs/<short-name>`
- `research/<short-name>`
- `infra/<short-name>`
- `test/<short-name>`

Examples:

`feature/perception-config-validator`

`fix/ci-import-path`

`docs/update-contributor-guide`

Do not develop directly on protected branches such as `main`.

## 3. Commits

Keep commits focused and use clear messages.

Recommended examples:

- `feat: add perception configuration validator`
- `fix: resolve Python import path in CI`
- `docs: update contributor setup`
- `test: add output schema validation`

Do not commit:

- Passwords
- API keys
- Access tokens
- Private keys
- Real `.env` files
- Cloud credentials
- Confidential information

## 4. Pull Requests

Every pull request should:

1. Link to an approved issue.
2. Explain its purpose.
3. Describe the changes.
4. Provide testing evidence.
5. Include reproduction steps.
6. Identify security implications.
7. Document dependency changes.
8. Update relevant documentation.
9. State known limitations.
10. Pass required CI checks.
11. Receive required reviewer and CODEOWNER approval.

## 5. Testing

Run the repository's documented tests before requesting review.

A pull request should not be considered ready if required tests are known to fail.

## 6. Code Review

Authors must address reviewer comments before merging.

Review conversations should only be resolved after the underlying concern has actually been addressed.

New commits after approval may require re-review.

## 7. Security

Never disclose vulnerabilities, credentials, tokens, or confidential information in public issues.

Follow `SECURITY.md` for security reporting.

## 8. Documentation

Update documentation when a change affects:

- Installation
- Configuration
- Interfaces
- Inputs or outputs
- Dependencies
- Deployment
- User-visible behavior
- Reproduction procedures

## 9. Definition of Done

A contribution is complete only when:

- Acceptance criteria are satisfied.
- Required tests pass.
- CI is green.
- Required reviews are complete.
- Security implications are reviewed.
- Documentation is updated.
- Reproduction information is available.
- Known limitations are recorded.
- Required evidence is linked.
