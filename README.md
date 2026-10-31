<p align="center"><img src="docs/icon.png" width="96" alt="FieldVault icon"></p>

# FieldVault

A private, offline notebook for security and engineering work. Survey notes, IP lists, configs, credentials, photos and tasks stay encrypted on your phone, with no internet access and no cloud account.

**[Download FieldVault.apk](FieldVault.apk)** (v2.4, Android 7.0 or newer) · **[Brochure (PDF)](FieldVault-brochure.pdf)**

## Install
1. Open this page on your Android phone and download **FieldVault.apk**.
2. Tap the downloaded file. If Android blocks it, tap **Settings**, turn on **Allow from this source**, then go back and tap **Install**.
3. If Play Protect warns about an unknown app, tap **More details** then **Install anyway**. The app is self-signed rather than from the Play Store, so this warning is expected.

Updates install over the previous version and keep your notes.

## Security
- **Fully offline:** the app has no internet permission. Nothing syncs or uploads, and data only leaves when you export it.
- **Encrypted at rest:** with a password set, pages, pictures and backups are encrypted with AES-256-GCM (key from PBKDF2-SHA256, 600,000 rounds).
- **Fingerprint or face unlock** (Android 10+): the password is sealed by the phone's secure hardware and resets if biometrics change.
- **Auto-lock** when you leave the app or go idle, plus a growing wait after repeated wrong passwords.
- **No shoulder surfing:** screenshots and the recent-apps preview are blocked, the keyboard is asked not to learn what you type, and copied passwords clear after a minute.
- **Erase everything** in one step (type ERASE to confirm).

## Features
Notes with headings, checklists, tables and photos · IP and host lists · credentials · code and config snippets · tasks with due dates · bookmarks · templates · encrypted backup files you can share to another phone · print or save any page as an A4 PDF.

## Checksum
SHA-256 of FieldVault.apk: `59bd0a04033d87a86f96808ceb052309a02f56620c52924464371e5c7d3a6cdb`
