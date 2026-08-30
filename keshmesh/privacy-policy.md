# Keshmesh Privacy Policy

**Effective date:** August 30, 2026  
**Product:** Keshmesh Chrome Extension

Keshmesh is designed as a local-first safe-browsing, visual-content protection, parental-control, and digital-wellbeing extension.

## 1. Data Keshmesh handles

To provide its core features, Keshmesh may process the following information locally in your browser:

- Website domains and URLs you visit.
- Visible website text, page titles, metadata, and nearby text used for content classification.
- Image and video-frame pixels used by Visual Guard for local classification.
- Image URLs when an image must be fetched by the extension so it can be analyzed locally.
- Local perceptual image hashes, verdicts, and confidence/score metadata.
- User-created allowlists, blocklists, custom sensitive terms, profiles, schedules, and protection preferences.
- Local protection events such as the domain, reason, time, and local score for a blocked or blurred item.
- Parental-control state. A parental PIN is not stored in plain text; Keshmesh stores a salted cryptographic hash for local verification.

Website content and browsing activity are sensitive user data under Chrome Web Store policy. Keshmesh handles them only because they are required for the safe-browsing and content-protection functionality that users install Keshmesh to provide.

## 2. Local processing and transmissions

Keshmesh performs content classification on the user's device. Keshmesh does **not** transmit page text, image pixels, perceptual image hashes, parental PINs, or browsing reports to a Keshmesh-operated classification server.

For cross-origin images that cannot be read directly by a content script, the extension may request the original image URL from the website or its content-delivery host so that the image can be analyzed locally. This request is made to the resource's existing host, not to a Keshmesh classification service.

Keshmesh does not include analytics or advertising SDKs in the extension package.

## 3. How data is used

Data handled by Keshmesh is used only to provide user-facing features, including:

- Blocking known or user-selected domains.
- Detecting sensitive text and visual content.
- Blurring, warning about, or blocking content according to the selected policy.
- Remembering user-approved or user-blocked image verdicts in the local visual database.
- Enforcing schedules, profiles, parental controls, temporary unlocks, commitments, and cooling-off rules.
- Showing local protection reports and diagnostics.

Keshmesh does not use browsing content for advertising, marketing profiles, credit decisions, or purposes unrelated to the extension's stated functionality.

## 4. Data sharing and sale

Keshmesh does not sell user data. Keshmesh does not share page content, browsing activity, image pixels, PIN data, or local visual verdicts with advertisers, data brokers, or unrelated third parties.

## 5. Storage and retention

Keshmesh stores settings and reports in Chrome extension local storage and stores visual verdict records in extension-scoped IndexedDB. The visual verdict database stores perceptual hashes and metadata, not copies of the original images.

Automatic visual verdicts may expire according to the user's configured cache period. Manual verdicts may remain until the user deletes them or resets the extension. Other local settings and reports remain until the user clears them, resets Keshmesh, removes the extension, or the browser removes extension storage.

## 6. Security

Keshmesh uses browser-provided extension isolation and local storage mechanisms. Parent PIN verification uses a salted cryptographic hash rather than storing the PIN in plain text. Users should still protect access to their browser profile and operating-system account.

## 7. User controls

Users can:

- Enable or disable protection where allowed by the current parental/self-control policy.
- Manage allowlists and blocklists.
- Review and clear local protection reports.
- Export or import settings.
- Export, import, or clear the local visual verdict database.
- Reset Keshmesh from the extension control center.
- Remove the extension from an unmanaged Chrome profile.

On administrator-managed Chrome installations, an administrator may force-install Keshmesh using Chrome Enterprise policies. In that case, the browser administrator controls installation and removal.

## 8. Children's use and parental controls

Keshmesh includes optional parental-control features. Keshmesh does not require a child to create an account and does not send a child's browsing content to Keshmesh servers for classification. Parents or administrators are responsible for configuring the extension appropriately for their household or managed environment.

## 9. Chrome Web Store Limited Use disclosure

Keshmesh's use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Keshmesh uses browsing and website content only to provide and improve the user-facing protection functionality described in the product and does not transfer this data for personalized advertising, unrelated profiling, or sale to third parties.

## 10. Changes to this policy

If Keshmesh's data practices materially change, this policy will be updated before or when the corresponding extension update is released. The effective date at the top of this document will be updated accordingly.

## 11. Contact

For privacy or support questions, use the public Keshmesh project page on the developer's GitHub profile:  
https://github.com/aradinan/aradinan
