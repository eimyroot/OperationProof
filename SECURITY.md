# Security Policy

## Reporting

Do not disclose vulnerabilities through public issues. Report them privately to the repository owner with the affected component, reproduction steps, expected impact, and a minimal proof where appropriate. Do not include third-party secrets or sensitive production data.

## Security expectations

- fail closed when identity, authorization, provenance, continuity, or evidence is missing or ambiguous;
- never commit secrets or production credentials;
- do not weaken signature, attestation, replay, expiry, or verification checks without explicit review;
- validate untrusted input at trust boundaries;
- preserve separation between execution success and independent verification;
- add tests for security-sensitive changes where practical.

The latest default-branch state is the maintained development version unless a release says otherwise.
