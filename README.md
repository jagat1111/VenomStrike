# VenomStrike

> Authorized browser-based web security validation with controlled scope, redacted evidence, reproducible findings, and non-destructive proof checks.

VenomStrike is a proprietary Manifest V3 browser extension designed for authorized web-application security testing, security education, internal assessments, and controlled vulnerability labs.

This public repository contains product documentation, privacy and security policies, screenshots, release information, and support resources. The readable source code, tests, and build pipeline are maintained separately in a private repository.

---

## Current version

**VenomStrike 4.2.7**

Status: **Microsoft Edge Add-ons submission in progress**

---

## Core capabilities

VenomStrike provides:

- Guided and autonomous security-validation workflows
- Target scope, excluded-path, request-limit, and duration controls
- Passive WAF fingerprinting
- Form, parameter, endpoint, and page-structure discovery
- Controlled crawling and monitoring
- Non-destructive proof validation
- Redacted evidence and HAR-style request traces
- Reproducible findings with control/test comparisons
- Scan cancellation and lifecycle recovery
- Local browser processing without a required VenomStrike cloud account

---

## Supported security findings

Depending on the target application, selected test categories, authorization settings, and available input surfaces, VenomStrike can help identify or validate findings related to:

- SQL injection
- Reflected and stored cross-site scripting
- Authentication and login-form weaknesses
- Authorization and IDOR indicators
- Local file inclusion and path traversal
- Server-side request forgery indicators
- Open redirects
- CSRF observations
- Command-injection indicators
- Header-injection indicators
- Server-side template injection
- JWT configuration weaknesses
- Prototype-pollution indicators
- Sensitive endpoints and exposed application metadata
- Passive WAF and infrastructure fingerprints

VenomStrike distinguishes between:

- **Confirmed** — supported by a reproducible proof signal
- **Probable** — meaningful evidence exists but requires manual verification
- **Observation** — a security-relevant condition or lead was identified

A submitted payload, response-length difference, generic error, or reflected marker alone is not treated as confirmed exploitation.

---

## Finding evidence

Where available, a VenomStrike finding may include:

- Finding title and category
- Severity and confidence
- Affected URL, form, or parameter
- Baseline or negative-control request
- Test request and payload
- Observed response signal
- Reproduction steps
- Copyable request formats
- Redacted response evidence
- Impact and remediation guidance
- Scope and request-trace information

Sensitive values such as passwords, cookies, authorization headers, access tokens, CSRF tokens, session identifiers, API keys, JWTs, OTP values, and email addresses are redacted where detected. Redaction is a safety control, not a guarantee; exported reports must always be reviewed before sharing.

---

## Important safety notice

VenomStrike must only be used on:

- Systems you own
- Systems for which you have explicit written authorization
- Intentionally vulnerable local training applications
- Controlled internal security-testing environments

Do not use VenomStrike to access, disrupt, exploit, or test third-party systems without permission.

Destructive payloads are disabled. Active proof-validation features require explicit user authorization and remain limited by configured scope and request controls.

---

## Recommended test environments

Use VenomStrike with authorized local labs such as:

- DVWA
- OWASP Juice Shop
- OWASP WebGoat
- PortSwigger Web Security Academy labs
- A locally hosted custom test application

Do not use public demonstration instances for unrestricted scanning.

---

## Installation

The official production extension will be distributed through a browser-store listing.

### Microsoft Edge Add-ons

**Store link:** Coming soon

Once approved, the official installation link will be published here.

For authorized beta testing, use only a package supplied through the official project distribution channel. Do not download VenomStrike from unofficial mirrors.

---

## Privacy

VenomStrike 4.2.7 processes security-testing information locally in the browser and does not require a VenomStrike cloud account.

The extension may process website content, authentication-related form data, selected target URLs, scan activity, and locally stored findings when required for a user-requested assessment.

Read the full [Privacy Notice](PRIVACY.md).

---

## Security and responsible disclosure

Found a security issue in VenomStrike itself?

Please do **not** publish:

- Working exploit code
- Real credentials
- Session cookies
- Access tokens
- Private customer information
- Unredacted scan evidence
- Sensitive screenshots or HAR files

Report the issue privately by email:

**jagat0422@gmail.com**

Include:

- A clear description
- Affected VenomStrike version
- Browser and operating system
- Reproduction steps
- Expected and actual behavior
- Sanitized screenshots or logs
- Security impact

Read the complete [Security Policy](SECURITY.md).

---

## Reporting incorrect findings

False positives and false negatives are useful for improving detector quality.

When reporting an incorrect finding, include:

- VenomStrike version
- Vulnerability category
- Authorized test environment
- Selected scan settings
- Expected result
- Actual result
- Whether active proof validation was enabled
- Sanitized baseline and test evidence
- Reproduction steps

Never submit sensitive production data through a public GitHub issue.

---

## Support VenomStrike

VenomStrike is independently developed and maintained. Your support helps fund testing, documentation, browser compatibility work, bug fixes, and future improvements.

### Support via UPI

**UPI ID:** `Jagat.p@slc`


### Bank transfer

For bank-transfer details, please contact:

**Email:** [jagat0422@gmail.com](mailto:jagat0422@gmail.com)

Bank information is shared privately for security reasons.

Support is optional and does not provide permission to use VenomStrike on systems without explicit authorization. 

---

## Documentation

- [Privacy Notice](PRIVACY.md)
- [Security Policy](SECURITY.md)
- [Disclaimer](DISCLAIMER.md)
- [Support](SUPPORT.md)
- [Changelog](CHANGELOG.md)

---

## Project status

VenomStrike is under active development. Findings produced by automated security tools should always be reviewed by a qualified tester before being used in a professional report.

Features, permissions, screenshots, and data-handling disclosures may change in later versions. Refer to the version-specific documentation before installing or updating.

---

## Contact

**Publisher:** Jagatpati Parida  
**Email:** jagat0422@gmail.com  
**Public repository:** https://github.com/jagat1111/VenomStrike

---

## Ownership

Copyright © 2026 Jagatpati Parida. All rights reserved.

VenomStrike is proprietary software. This public repository provides documentation and project information only. It does not grant access to the private source code or permission to copy, modify, redistribute, reverse engineer, or create derivative products from the software.
