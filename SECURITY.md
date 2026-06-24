# Security Policy

## Supported version

Security fixes are currently provided for the latest privately distributed VenomStrike release. Version 4.2.7 is the active supported version when this file was published.

## Reporting a vulnerability

Do not publish a vulnerability affecting VenomStrike in a public issue.

Preferred reporting method:

1. Open the private GitHub repository.
2. Select **Security**.
3. Use **Report a vulnerability** / private vulnerability reporting when enabled.
4. Otherwise contact the owner privately through the official GitHub profile: `@jagat1111`.

Include:

- A clear description and impact
- Affected version and browser version
- Reproduction steps using a harmless local fixture where possible
- Relevant console errors or sanitized traces
- Suggested mitigation, if known

Do not include live credentials, access tokens, customer records, unredacted HAR files, or unauthorized target data.

## Disclosure process

The maintainer will attempt to acknowledge a complete report, assess severity, prepare a fix, and coordinate disclosure. Timelines depend on reproducibility, impact, and release complexity. Reporters should avoid public disclosure until a fix or coordinated disclosure date is agreed.

## Scope

Examples of in-scope issues include:

- Extension privilege or origin-boundary bypass
- Popup or side-panel script injection
- Sensitive evidence escaping redaction
- Scope-control bypass
- Unauthorized external data transmission
- Destructive payload activation
- Remote code execution in extension contexts

Detector false positives and false negatives should use the detector-accuracy issue template unless they create a direct security risk.
