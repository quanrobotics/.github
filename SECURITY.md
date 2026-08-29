# QuanRobotics Security Policy

## Reporting a Security Issue

Do not report the following through a public GitHub issue:

- Passwords
- API keys
- Access tokens
- Private keys
- Cloud credentials
- Security vulnerabilities
- Confidential QuanRobotics information
- Sensitive personal or partner data

Use the approved private QuanRobotics communication channel for security-sensitive reports.

## Information to Include

Where safe, provide:

- Affected repository
- Affected component
- Commit or version
- Description of the issue
- Reproduction steps
- Potential impact
- Suggested mitigation
- Non-sensitive evidence

Never paste real credentials into the report.

## Credential Exposure

If a credential is accidentally committed:

1. Treat the credential as compromised.
2. Revoke or rotate it immediately.
3. Notify the responsible technical owner.
4. Notify the appropriate operational owner where required.
5. Remove the credential from active code.
6. Review repository history and logs where appropriate.
7. Document the corrective action.
8. Determine why preventive controls failed.

## Responsible Disclosure

Do not publicly disclose unresolved vulnerabilities before QuanRobotics has had a reasonable opportunity to investigate and remediate the issue.

## Security Review

Changes involving the following require additional security consideration:

- Authentication
- Authorization
- CI/CD credentials
- Infrastructure
- Cloud access
- Deployment
- Model or dataset publication
- Confidential information
- External integrations
