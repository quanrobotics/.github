# QuanRobotics CI Repository Matrix

| Repository | Status | Language | Package Manager | Install Command | Lint Command | Test Command | Default Branch |
|---|---|---|---|---|---|---|---|
| qr-governance-sandbox-test | Active pilot | Python 3.12 | pip | pip install -r requirements.txt | ruff check . | python -m pytest -v | main |
| .github | Governance/configuration only | N/A | N/A | N/A | N/A | N/A | main |
| demo-repository | Pending scope confirmation | TBD | TBD | TBD | TBD | TBD | TBD |

## Scope Note

SUN-05 CI controls are first validated on qr-governance-sandbox-test.

Repositories without executable code are documented as not applicable rather
than being given artificial test commands.

The status of demo-repository must be confirmed before SUN-05 closure.
