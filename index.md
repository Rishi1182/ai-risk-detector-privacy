# Privacy Policy – Sentinel Gate

**Last updated:** 3 February 2026

Sentinel Gate is a browser extension designed to help users assess the risk of AI-generated content, phishing attempts, impersonation, and coordinated scam campaigns by analyzing user-requested website content.

## Data Collection

Sentinel Gate does **not** collect personally identifiable information such as names, email addresses, passwords, payment details, authentication credentials, or precise location data.

The extension processes **website content only**, including visible page text and links, solely when the user explicitly initiates an analysis (for example, by selecting text, scanning a page, or using the extension interface).

Sentinel Gate does **not** monitor browsing activity in the background and only accesses page content when the user explicitly triggers a scan.

## Data Usage

The selected website content is transmitted to the Sentinel Gate backend analysis service (ai-risk-detector.onrender.com) exclusively to perform risk analysis and return results to the user.

The data is used only to:
* assess content risk signals (such as AI-style indicators or link safety), and
* identify potential campaign-level patterns when enabled by the user.

The data is **not** used for advertising, tracking, profiling, or marketing purposes.

## Campaign Detection & Fingerprinting

When the Campaign Detection feature is enabled, Sentinel Gate may generate anonymized style fingerprints derived from analyzed content. These fingerprints are:
* generated from writing patterns, not raw text,
* anonymized and non-reversible,
* used only to help identify potential coordinated scam patterns.

Campaign detection data may include anonymized style hashes, coarse domain indicators, and timestamps. This data is retained for a limited period (for example, up to 48 hours) and is never associated with personal identities.

Users can opt out of contributing anonymized campaign data at any time via the Settings tab.

## Data Storage

Sentinel Gate stores analysis results, fingerprints, and user preferences **locally on the user's device** using browser storage. This allows users to:
* review recent scans,
* compare writing styles across their own analyses, and
* maintain extension settings.

**No personal data is stored remotely** by the extension. All stored data remains local to the user's browser.

## User Control & Data Deletion

All analysis actions are **initiated by the user**. The extension does not run automatically or access page content without explicit user action.

Users can delete all locally stored Sentinel Gate data at any time using the "Delete all data" option in the Settings tab. This clears stored analysis results, fingerprints, and preferences from the device.

## Data Sharing

Sentinel Gate does **not** sell or transfer user data to third parties.

Website content is transmitted only to the Sentinel Gate backend service for the sole purpose of performing the requested analysis. This service is operated by Sentinel Gate and is not a third-party service.

## Remote Services

The extension communicates with a backend API (ai-risk-detector.onrender.com) to process analysis requests and return non-executable results.

No executable code is loaded remotely into the browser, and all extension logic is bundled locally within the extension package.

## Permissions Used

Sentinel Gate requests the following permissions:
* **contextMenus** - To provide right-click menu options for initiating scans
* **activeTab** - To temporarily access the active tab when user initiates analysis
* **storage** - To store analysis results and preferences locally on your device
* **notifications** - Reserved for potential future features (not currently used)
* **host_permissions** - To communicate with the Sentinel Gate analysis backend

All permissions are used solely for the extension's stated purpose of content analysis and risk detection.

## Contact

If you have questions about this privacy policy or Sentinel Gate's data practices, please contact:

**Email:** sentinelgate25@gmail.com

---

*This privacy policy may be updated from time to time. Users will be notified of significant changes through the extension's update notes.*
