# Privacy Policy – AI Risk Detector

**Last updated: 28 January 2026**

AI Risk Detector is a browser extension that helps users identify AI-generated content, phishing attempts, impersonation, and coordinated fraud patterns.

---

## Data Collection

AI Risk Detector does not collect personal information such as names, email addresses, passwords, payment details, or precise location data.

The extension processes only website content (such as visible text and links) that the user explicitly selects or initiates for analysis. The extension does not automatically monitor browsing activity.

---

## Data Usage

Selected content is transmitted to a remote analysis service solely to perform risk classification and return results to the user.

The data is not used for advertising, tracking, behavioral profiling, or marketing purposes.

---

## Data Storage

Analysis results may be stored locally on the user’s device to allow users to review recent scans, view explanations, and compare writing styles.

AI Risk Detector does not sell, rent, or share user data with third parties.

---

## Anonymized Scam Campaign Detection

AI Risk Detector includes an optional feature designed to detect coordinated scam and impersonation campaigns appearing across multiple websites.

To support this functionality, the extension may process and transmit **anonymized writing-style fingerprints** derived from text that the user explicitly chooses to analyze. These fingerprints are generated from statistical features of writing style and **cannot be reversed to reconstruct the original text**.

**AI Risk Detector does not store or transmit:**
- Raw page content or message text  
- Full URLs or URL paths  
- Personal identifiers  
- User accounts, cookies, or browsing history  

---

## Data Collected for Campaign Detection

When campaign detection is enabled, the backend may temporarily process and store the following **anonymized metadata**:

- A writing-style fingerprint hash  
- A coarse website domain (hostname only, without URL paths)  
- A timestamp indicating when the fingerprint was observed  

This data is used solely to identify when the same scam or impersonation template appears across multiple unrelated websites within a short time window.

All data transmission occurs over encrypted HTTPS connections.

---

## Data Retention

Anonymized campaign detection data is retained for a **short rolling window (typically up to 48 hours)** and is automatically deleted after this period.

AI Risk Detector does not maintain long-term historical storage of campaign detection data.

---

## User Control and Opt-Out

All analysis actions are initiated by the user.

Users may opt out of contributing anonymized fingerprints to the campaign detection system at any time via the extension’s privacy settings.

If a user opts out:
- Their analyzed content is **not added** to the global campaign detection system  
- They may still **receive campaign warnings** based on anonymized data contributed by other users  

Opting out does not affect core features such as local analysis, link risk detection, or on-device similarity checks.

---

## Remote Services

The extension communicates with a backend API for analysis purposes only.

No executable code is loaded remotely into the browser.

---

## Privacy-First Design

AI Risk Detector is built with privacy by default:

- Text analysis is performed transiently and not retained  
- Campaign detection relies on irreversible anonymized hashes  
- No personal or sensitive user data is collected  
- No user accounts or sign-ins are required  

---

## Contact

For questions about this privacy policy, contact:

**sentinelgate25@gmail.com**
