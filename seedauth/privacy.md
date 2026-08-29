---
title: Privacy Policy
description: Privacy Policy for SeedAuth.
permalink: /seedauth/privacy/
project_slug: seedauth
project_name: SeedAuth
---

**Effective Date:** August 29, 2026

This Privacy Policy explains how Matt Crypto ("Company," "we," "us," or "our") handles information in connection with SeedAuth (the "App").

## 1. Summary

The App collects nothing and transmits nothing. It has no servers, no accounts, no analytics, no telemetry, no crash reporting, and no advertising identifiers. The App does not request the Android INTERNET permission, so it is technically incapable of transmitting data off your device.

## 2. Scope

This Privacy Policy applies to information processed through the App, including locally stored authenticator secrets and settings, camera-based QR scanning, biometric unlock, optional Seed Vault integration, and user-initiated encrypted backup files.

## 3. Information We Collect

None. We do not collect, receive, store, or process any information about you or your use of the App on any server or third-party service, because the App has no network access.

## 4. Information Stored Locally on Your Device

Depending on how you use the App, the following is stored only on your device:

- two-factor authentication secrets, account labels, notes, and preferences you add to the App;
- vault metadata such as creation and modification timestamps; and
- app settings (auto-lock interval, clipboard clearing, screenshot blocking).

All secrets are encrypted at rest with AES-256-GCM under a master key protected by your device's secure hardware (Android Keystore / StrongBox) and, if you enable seed recovery, additionally sealed by a key derived from a Seed Vault signature. This local data never leaves your device unless you export an encrypted backup file.

## 5. Encrypted Backups

Backup files are created only when you explicitly export them, are encrypted before they are written, and are saved only to the location you choose. A backup can be unlocked only with a Seed Vault signature from the same seed phrase or with the backup password you set. We have no access to backup files or the keys that open them.

## 6. Device Features the App Accesses

- **Camera** — used only while you actively scan a QR code. Frames are processed on-device to decode the QR content and are never stored or transmitted.
- **Biometrics / device credential** — used to unlock the vault. Biometric data is handled entirely by the Android system; the App receives only a success or failure result.
- **Seed Vault** (optional) — if you enable seed recovery, the App requests signatures over a fixed message on a dedicated derivation path. The App never sees, stores, or transmits your seed phrase or private keys.

## 7. Third Parties

The App shares no information with third parties and embeds no third-party analytics, advertising, or tracking technologies.

## 8. Children's Privacy

The App does not knowingly collect information from anyone, including children under 13.

## 9. Data Retention and Deletion

All App data lives on your device. You can delete it at any time via the App's "Delete vault" setting or by uninstalling the App. Exported backup files you created remain wherever you saved them and are under your control.

## 10. Changes to This Policy

If a future version of the App changes any of the practices described above, we will update this policy and the App's store listing before releasing that version. The Effective Date above reflects the latest revision.

## 11. Contact

Questions about this Privacy Policy can be raised via the support contact listed on the App's Solana dApp Store listing or by opening an issue at https://github.com/mattcrypto12/SeedAuth.
