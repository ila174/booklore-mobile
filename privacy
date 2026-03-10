# BookLore

### Privacy Policy

*Last updated: March 9, 2026*

---

## Overview

BookLore is a mobile client for your self-hosted BookLore server. Your library data stays on your devices and your server. We do not operate central servers, and we do not collect, store, or transmit your personal data or library contents.

## Data stored on your device

BookLore stores the following data locally on your device:

- Library metadata, reading and listening progress, chapter positions
- Highlights, annotations, and notes
- Downloaded ebooks and audiobooks for offline use
- Cached book cover artwork
- Server connection URL and authentication tokens (stored in encrypted platform storage)
- Reader preferences, theme settings, and TTS configuration

Authentication tokens are stored using platform-specific encrypted storage (Keychain on iOS, EncryptedSharedPreferences on Android). We do not store your password on device after login.

## Your BookLore server connection

BookLore connects directly to the BookLore server you configure. All library data, book files, and playback progress are exchanged between the app and your server.

- Authentication is handled via JWT tokens issued by your server
- The app syncs reading and listening progress, annotations, and highlights with your server
- A WebSocket connection is used for real-time updates from your server

We do not proxy, intercept, or have access to any communication between the app and your server.

## Third-party services

BookLore uses the following third-party services:

**In-app reader tools**

- **Google Translate** - When you use the translation feature, selected text is sent to the Google Translate API. Subject to [Google's Privacy Policy](https://policies.google.com/privacy).
- **Wiktionary** - Word lookups are sent to the Wiktionary REST API. Subject to [Wikimedia's Privacy Policy](https://foundation.wikimedia.org/wiki/Privacy_policy).
- **Free Dictionary API** - Word lookups are sent to the Free Dictionary API.

These services are only contacted when you explicitly use the dictionary or translation features within the reader.

**Subscriptions**

- **RevenueCat** - Used to manage in-app subscriptions via the App Store and Google Play. RevenueCat generates an anonymous device identifier. No personal data is shared. Subject to [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/).

## ISBN scanning

BookLore includes a barcode scanner for looking up books by ISBN. The camera is used only when you open the scanner. Scanned ISBN numbers are sent to your BookLore server for metadata lookup. No camera data is stored or transmitted elsewhere.

## Analytics and crash reporting

BookLore does not include any analytics, telemetry, or crash reporting SDKs. We do not collect usage data, device information, or crash reports.

## Cloud sync

BookLore does not use iCloud, Google Drive, or any cloud sync services. All sync is directly between the app and your self-hosted BookLore server.

## Your choices

- Log out from the app to remove authentication tokens from your device
- Delete downloaded books from within the app to free local storage
- Delete the app to remove all local data
- Dictionary and translation features are opt-in - no text is sent to third-party services unless you use them

## Children's privacy

BookLore is not directed at children under the age of 13. We do not knowingly collect personal information from children.

## Changes to this policy

We may update this privacy policy from time to time. Changes will be posted on this page with an updated date.

## Contact

If you have questions about this privacy policy, please [open an issue](https://github.com/ila174/booklore-mobile/issues) on our support repository.
