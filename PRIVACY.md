# VenomStrike Privacy Notice

**Effective date:** 24 June 2026  
**Applies to:** VenomStrike 4.2.7

## Summary

VenomStrike is designed to process security-test information locally in the browser extension wherever practical. It does not require a cloud account in version 4.2.7 and does not intentionally sell user data.

## Data the extension may access

When the user starts a feature on an authorized page, VenomStrike may access information required for that feature, including:

- The active tab URL, origin, links, forms, parameters, and page structure
- Response indicators and readable response headers used for detection
- Locally generated payloads, controls, timing, and comparison evidence
- Scan scope, request limits, settings, progress, findings, and history
- User-supplied controlled callback URLs or canaries for authorized validation

Depending on the tested application, page content may contain personal, confidential, authentication, or business information. Users must restrict testing to authorized systems and minimize unnecessary data collection.

## Local storage

VenomStrike may store settings, scan state, findings, and history using Chrome extension storage. Temporary progress may be stored in session storage. The exact retention depends on the feature and the user’s browser data settings.

## Redaction

Before evidence is displayed, stored, or exported, VenomStrike attempts to redact common sensitive fields such as passwords, cookies, authorization headers, session identifiers, CSRF tokens, access tokens, API keys, client secrets, OTP values, JWTs, and email addresses.

Redaction is a safety control, not a guarantee. Users must review every exported report or HAR trace before sharing it.

## Exports

Users may export reports or HAR-style traces to their own device. Exported files are controlled by the user after download. Do not upload them to public issue trackers or repositories without reviewing and sanitizing them.

## External transmission

Version 4.2.7 does not intentionally transmit complete page content, cookies, authorization headers, or scan evidence to a VenomStrike-operated cloud service by default. Browser requests used for authorized testing are sent to targets within the configured engagement scope.

Third-party websites, browser stores, GitHub, and distribution platforms have their own privacy practices.

## Permissions

The extension uses browser permissions to access the active tab, inject its authorized content bridge, store settings and scan state, manage tabs used by crawler functions, support the side panel, and observe navigation required for lifecycle handling. Broad website access should be limited through user-configured scope controls and browser site-access settings.

## Deleting data

Users can remove locally stored extension data by clearing VenomStrike history/settings where available, removing the extension, or clearing extension data through browser settings. Exported files must be deleted separately from the user’s filesystem.

## Security reports and support

Do not include real credentials, session cookies, private customer data, or unredacted evidence in support requests. Use GitHub private vulnerability reporting where available.

## Changes

This notice may be updated when data practices or features change. The effective date and applicable version will be updated accordingly.
