# QuanRobotics Code Review Checklist

## Scope and Correctness

- [ ] The change matches the linked issue.
- [ ] Acceptance criteria are satisfied.
- [ ] No unrelated changes are included.
- [ ] Expected failure cases have been considered.

## Code Quality

- [ ] Code is readable.
- [ ] Naming is clear.
- [ ] Structure is maintainable.
- [ ] Unnecessary duplication is avoided.
- [ ] Configuration is not unnecessarily hard-coded.

## Testing

- [ ] Required tests exist.
- [ ] Tests pass.
- [ ] CI passes.
- [ ] Failure cases are tested where appropriate.

## Interfaces

- [ ] Input/output changes are documented.
- [ ] Configuration/schema changes are documented.
- [ ] Compatibility impact has been considered.

## Dependencies

- [ ] New dependencies are necessary.
- [ ] Dependency versions are controlled.
- [ ] Security implications are reviewed.
- [ ] Licensing implications are considered.

## Security

- [ ] No credentials or secrets are committed.
- [ ] Authentication/authorization impact is reviewed.
- [ ] Sensitive-data handling is appropriate.
- [ ] Security-sensitive changes received appropriate review.

## Reproducibility

- [ ] Setup instructions are available.
- [ ] Required configuration is documented.
- [ ] Another contributor can reproduce the result.
- [ ] Relevant software/model/configuration versions are recorded.

## Documentation

- [ ] README/docs are updated where needed.
- [ ] Known limitations are stated.
- [ ] Public technical claims are supported by evidence.

## Evidence

- [ ] CI link is available.
- [ ] Test evidence is available.
- [ ] Benchmark evidence is attached where applicable.
- [ ] Screenshots/logs are attached where useful.

## Final Review

- [ ] Required CODEOWNER approval is complete.
- [ ] Required reviewer count is satisfied.
- [ ] Review conversations are resolved.
- [ ] The change is safe to merge.
