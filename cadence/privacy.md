---
title: Privacy Policy
description: Privacy Policy for Cadence.
permalink: /cadence/privacy/
project_slug: cadence
project_name: Cadence
---

**Effective Date:** August 31, 2026

This Privacy Policy explains how Matt Crypto ("Company," "we," "us," or "our") handles information in connection with Cadence (the "App").

## 1. Summary

Cadence has no servers, no accounts, no analytics, and no telemetry. Its only network traffic is JSON-RPC requests to the Solana endpoint you configure, used to schedule, sign-prepare, broadcast, and confirm the payments you set up.

## 2. Scope

This Privacy Policy applies to information processed through the App, including your public wallet address, saved payees, standing orders and payment history stored locally, RPC network requests, camera-based QR scanning, and notifications.

## 3. Information We Collect

None. We operate no servers and do not receive, collect, or store any information about you or your use of the App.

## 4. Information Stored Locally on Your Device

- your public wallet address (never your private key or seed phrase);
- payees you save (name, public Solana address, optional note);
- standing orders you create and your payment history; and
- app settings (RPC endpoint, cluster, notification preferences).

All of this is public-chain data plus your own labels. You can delete it at any time by removing payees/orders, disconnecting your wallet, or uninstalling the App.

## 5. Network Requests and Your RPC Provider

The App sends JSON-RPC requests (recent blockhash, balances, token accounts, transaction broadcast, and confirmation) to the Solana RPC endpoint configured in Settings (default: `api.mainnet-beta.solana.com`). Your chosen RPC provider necessarily sees these requests and your device's IP address, subject to that provider's own privacy policy. Choose a provider you trust. The App contacts no other endpoints.

## 6. Signing and Keys

Payments are signed by the device's Seed Vault. The private key never leaves the secure element. The App receives only your public key and per-transaction signatures, and only after you approve each payment with your fingerprint. The App cannot move funds without that approval.

## 7. Device Features the App Accesses

- **Camera** — only while you actively scan a payee address QR code; frames are processed on-device and never stored or transmitted.
- **Notifications** — used to remind you when a scheduled payment is due.

## 8. Third Parties

Other than the RPC provider you configure (Section 5), the App shares no information with any third party and embeds no third-party analytics, advertising, or tracking technologies.

## 9. Children's Privacy

The App does not knowingly collect information from anyone, including children under 13.

## 10. Changes to This Policy

If a future version of the App changes any of the practices described above, we will update this policy and the App's store listing before releasing that version.

## 11. Contact

Questions about this Privacy Policy can be raised via the support contact listed on the App's Solana dApp Store listing or by opening an issue at https://github.com/mattcrypto12/Cadence.
