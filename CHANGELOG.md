# Changelog

## 4.2.7 — Release hardening

### Security and privacy

- Added centralized evidence redaction for sensitive headers, parameters, bodies, and exported traces.
- Added engagement scope controls, excluded paths, wildcard exclusions, request budgets, and duration limits.
- Added redacted HAR-style exploit trace export.
- Kept destructive payloads disabled and active proof validation authorization-gated.

### Detection and runtime

- Added passive WAF response-header fingerprinting.
- Improved content-script recovery, exploit surface discovery, form handling, and proof evidence.
- Added browser extension smoke-test harness and expanded positive/negative detector regression coverage.

### User interface

- Repaired category navigation, pinned Bug Hunter state, findings/report rendering, and exploit category controls.
- Added clearer executed/skipped category diagnostics and proof-status explanations.

### Private release pipeline

- Consolidated all authoritative runtime code under `src/`.
- Added parser-aware JavaScript, CSS, and HTML production transforms.
- Added source, distribution, and freshly extracted ZIP verification.
- Added dynamic versioned packaging and SHA-256 generation.
- Removed regex-based JavaScript comment stripping that could corrupt MIME strings.
