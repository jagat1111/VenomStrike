# VenomStrike Privacy Notice

**Effective date:** 24 June 2026
**Applies to:** VenomStrike version 4.2.7
**Publisher:** Jagatpati Parida
**Privacy contact:** [jagat0422@gmail.com](mailto:jagat0422@gmail.com)

## 1. Overview

VenomStrike is a browser extension for authorized web-application security validation.

Version 4.2.7 processes security-testing information locally within the browser extension. It does not require a VenomStrike account and does not send scan evidence to a VenomStrike-operated cloud service.

VenomStrike does not sell user data, use user data for advertising, use user data to determine creditworthiness, or transfer user data to data brokers.

VenomStrike does not include advertising SDKs, third-party analytics SDKs, or third-party AI services in version 4.2.7.

## 2. Data accessed and processed

When a user explicitly starts a feature on a website that the user owns or is authorized to test, VenomStrike may access and process the following categories of information.

### Website content

VenomStrike may process:

* Page text and document structure
* Links and internal endpoints
* Forms and form fields
* Query and body parameters
* Scripts and page metadata
* Readable response indicators and headers
* Security-related error messages
* Locally generated test payloads and comparison evidence

This information is used only to perform the user-requested security-validation feature.

### Authentication information

During an authorized assessment, a tested page may contain:

* Password fields
* Login-form values
* CSRF tokens
* Session identifiers
* Authorization headers
* Cookies
* Access tokens
* Other authentication-related values

VenomStrike processes this information locally only when required for the user-selected feature. Sensitive authentication values are not intentionally transmitted to VenomStrike or stored in unredacted reports.

Users should use disposable test accounts and avoid using production credentials wherever possible.

### Web history

VenomStrike does not collect or monitor the user’s complete browsing history.

It may access and locally store:

* The URL and origin of the website selected for testing
* URLs discovered within the configured engagement scope
* Navigation events associated with the active assessment
* Dates and times associated with locally stored scan history

This information is used to manage scan scope, restore scan state, associate findings with a target, and generate reports.

### User activity

When the user enables monitoring, crawling, Hook, Spider, or related features on an authorized target, VenomStrike may observe:

* User-initiated page navigation
* Single-page application route changes
* Fetch and XMLHttpRequest activity
* WebSocket endpoint information
* Form submissions
* Scan start, pause, cancellation, and completion events

VenomStrike does not use these features to monitor general browsing activity outside the user-selected assessment.

## 3. Information supplied by the user

VenomStrike may process information entered directly by the user, including:

* Allowed target origins
* Excluded paths
* Request limits
* Authorization confirmations
* Controlled callback URLs
* Response canaries
* Scan configuration
* Report notes

Users must not enter callback URLs or other information belonging to a third party without authorization.

## 4. Purpose of processing

The information described in this notice is used only to:

* Identify user-selected security-testing targets
* Enforce target scope and excluded paths
* Discover forms, parameters, links, and endpoints
* Perform user-requested, non-destructive security validation
* Compare control and test responses
* Display findings and supporting evidence
* Generate redacted reports and HAR-style traces
* Restore interrupted scans
* Maintain local settings and scan history
* Diagnose extension errors

VenomStrike does not use this information for advertising, profiling, unrelated analytics, credit decisions, or resale.

## 5. Local storage

VenomStrike may use Microsoft Edge extension storage and temporary session storage to save:

* Extension settings
* Allowed origins and exclusions
* Request and duration limits
* Scan progress
* Crawler checkpoints
* Redacted findings
* Scan history
* Interface preferences
* Temporary lifecycle state

Data remains in the user’s browser profile until it is deleted by the user, cleared through the extension or browser settings, removed by browser storage management, or deleted when the extension is uninstalled.

VenomStrike does not define a separate cloud-retention period because version 4.2.7 does not operate a VenomStrike cloud-storage service.

## 6. Redaction

Before evidence is displayed, stored, copied, or exported, VenomStrike attempts to redact common sensitive information, including:

* Passwords
* Cookies
* Authorization headers
* Session identifiers
* CSRF tokens
* Access tokens
* API keys
* Client secrets
* One-time passwords
* JSON Web Tokens
* Email addresses
* Other fields recognized as sensitive

Redaction is a safety control and cannot guarantee that every sensitive value will be detected.

Users must review and sanitize every report, screenshot, copied value, and HAR-style export before sharing it.

## 7. Network requests and external transmission

VenomStrike sends browser requests only when required by a user-selected security-validation feature.

These requests are sent directly from the browser to websites within the configured engagement scope. The tested website, its hosting provider, security provider, proxy, content-delivery network, or network administrator may receive and log those requests according to their own practices.

Version 4.2.7 does not transmit complete page content, cookies, authorization headers, credentials, scan evidence, or exported reports to a VenomStrike-operated backend service.

VenomStrike does not download or execute remotely hosted extension code.

Microsoft Edge Add-ons, Microsoft Edge, GitHub, and other websites used for distribution or support operate independently and are governed by their own privacy policies.

## 8. Exports and clipboard use

VenomStrike allows users to copy or export information only after an explicit user action.

Exports may include:

* Security reports
* Reproduction steps
* Request and response evidence
* JSON data
* Markdown reports
* HAR-style traces

Exported or copied information is controlled by the user after it leaves the extension. Users must not upload unreviewed exports to public repositories, public issue trackers, messaging services, or third-party platforms.

## 9. User controls

Users can control VenomStrike’s processing by:

* Choosing whether to start a scan
* Selecting the target website
* Defining allowed origins
* Allowing or disallowing subdomains
* Excluding paths
* Setting request and duration limits
* Selecting individual test categories
* Confirming or declining active validation
* Stopping an active scan
* Clearing locally stored history or settings
* Removing the extension
* Managing the extension’s site access through Microsoft Edge settings

VenomStrike does not perform active proof validation unless initiated and authorized by the user.

## 10. Accessing and deleting information

VenomStrike does not maintain a separate online user profile.

Users can view locally stored findings and history through the extension interface where available.

Users can delete locally stored information by:

* Using available clear-history or reset controls
* Clearing the extension’s site data through Microsoft Edge
* Removing VenomStrike from Microsoft Edge

Exported files must be deleted separately from the user’s device, cloud-storage provider, backup system, or any platform to which the user uploaded them.

Because locally stored extension information is not transmitted to VenomStrike, the publisher generally cannot access or remotely delete that information on the user’s behalf.

## 11. Data sharing

VenomStrike does not sell user information.

Version 4.2.7 does not share extension-processed page content, authentication information, scan history, user activity, or security evidence with advertisers, analytics providers, data brokers, or unrelated third parties.

Information may be disclosed only when required by applicable law or when the user independently chooses to copy, export, or share it.

## 12. Security

VenomStrike uses local processing, engagement scope controls, request limits, evidence redaction, and non-destructive validation controls to reduce privacy and security risks.

No software or redaction process can guarantee complete security. Users must:

* Test only systems they own or are explicitly authorized to assess
* Use disposable test accounts where possible
* Avoid production credentials
* Review exported evidence
* Keep Microsoft Edge and VenomStrike updated
* Protect exported files appropriately

## 13. Children’s privacy

VenomStrike is a professional security-testing and educational tool and is not directed to children.

The publisher does not knowingly operate a service that collects children’s personal information through VenomStrike.

## 14. Changes to this notice

This notice may be updated when VenomStrike’s features, permissions, storage practices, integrations, or data-handling practices change.

The effective date and applicable version will be updated when material changes are made.

Users should review the latest privacy notice before installing or updating the extension.

## 15. Contact

Questions about this privacy notice or VenomStrike’s data practices may be sent to:

**Jagatpati Parida**
**Email:** [jagat0422@gmail.com](mailto:jagat0422@gmail.com)

Do not include real credentials, session cookies, access tokens, private customer data, or unredacted security evidence in an email or support request.
