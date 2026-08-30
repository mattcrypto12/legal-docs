---
title: Privacy Policy
description: Privacy Policy for Vigil.
permalink: /vigil/privacy/
project_slug: vigil
project_name: Vigil
---

**Effective Date:** August 29, 2026

This Privacy Policy explains how Matt Crypto ("Company," "we," "us," or "our") handles information in connection with Vigil (the "App").

## 1. Summary

Vigil has no servers, no accounts, no analytics, and no telemetry. The only network traffic the App generates is read-only JSON-RPC queries about public blockchain addresses you choose to watch or check, sent to the Solana RPC endpoint you configure.

## 2. Scope

This Privacy Policy applies to information processed through the App, including watched public addresses and labels, trusted-contact entries, locally cached public transaction activity, RPC network requests, camera-based QR scanning, and notifications.

## 3. Information We Collect

None. We do not operate servers and do not receive, collect, or store any information about you or your use of the App.

## 4. Information Stored Locally on Your Device

- public wallet addresses you watch, and the labels you assign;
- public addresses you save as trusted contacts, and their labels;
- a local cache of parsed public transaction activity, balances, and derived statistics for watched addresses;
- suspected address-poisoning flags and your dismissals of them; and
- app settings (RPC endpoint, polling interval, notification preferences).

The App contains no private keys, seed phrases, or signing capability of any kind. All locally stored data is public-chain information plus your own labels; you can delete it at any time by removing wallets/contacts or uninstalling the App.

## 5. Network Requests and Your RPC Provider

The App sends read-only queries (balances, transaction signatures, transaction details, account probes) for the public addresses you watch or check to the Solana RPC endpoint configured in Settings (default: `api.mainnet-beta.solana.com`). Your chosen RPC provider necessarily sees these queries and your device's IP address, subject to that provider's own privacy policy. Choose a provider you trust. The App contacts no other endpoints.

## 6. Device Features the App Accesses

- **Camera** — only while you actively scan an address QR code; frames are processed on-device and never stored or transmitted.
- **Notifications** — used to alert you about activity on watched wallets and suspected address-poisoning attempts. You can control notification behavior in the App and in system settings.

## 7. Third Parties

Other than the RPC provider you configure (Section 5), the App shares no information with any third party and embeds no third-party analytics, advertising, or tracking technologies.

## 8. Children's Privacy

The App does not knowingly collect information from anyone, including children under 13.

## 9. Changes to This Policy

If a future version of the App changes any of the practices described above, we will update this policy and the App's store listing before releasing that version.

## 10. Contact

Questions about this Privacy Policy can be raised via the support contact listed on the App's Solana dApp Store listing or by opening an issue at https://github.com/mattcrypto12/Vigil.
