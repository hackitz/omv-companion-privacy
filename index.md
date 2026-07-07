---
meta-viewport: width=device-width, initial-scale=1.0
title: OMV Companion — Privacy Policy
---

# OMV Companion

Privacy Policy

**Effective date:** July 6, 2026 · **App version:** 1.0 and later · **Developer:** Hackitz Labs

_OMV Companion is an independent, unofficial app and is not affiliated with, endorsed by, or connected to the OpenMediaVault project._

## The short version

- OMV Companion does not collect, store, or transmit any of your data to us or any third party.
- Your server login is stored only on your device, in encrypted storage.
- The app connects only to the OpenMediaVault server you choose — nothing else.
- No analytics, no advertising, no tracking of any kind.
- There is no cloud service and no account to create.

## 1. Information we collect

**We collect nothing.** OMV Companion does not collect, transmit, or store any personal
information on our servers. There are no servers operated by Hackitz Labs that receive any data from the app.

The following information is processed and stored *locally on your device only*:

- **Server login** — the address (host/URL), username, and password of the OpenMediaVault
server you connect to, plus the session cookie your server returns. These are used only to sign in to
that server and are never sent anywhere except directly to the server you specify.
- **App data and settings** — your preferences (theme, alert settings, thresholds, ignored
devices, alert history, etc.) are stored locally in your device's private app storage.

## 2. How your data is used

All data processed by OMV Companion is used solely to provide the core functionality of the app —
showing the status of, and performing the actions you request on, the OpenMediaVault server whose
details you provide. Your credentials are used only to authenticate with that server. No data is used
for advertising, profiling, analytics, or any purpose other than operating the app.

## 3. Network connections and third-party services

OMV Companion does not integrate with any analytics platforms, advertising networks, or data brokers.
It makes network connections only to the server you choose:

- **Your OpenMediaVault server** — the app communicates only with the server address you
enter, to read its status and carry out the actions you initiate. This is typically a server on your own
local network.
- **Optional "Send feedback" / "Send logs" (user-initiated)** — if, and only if, you tap
these buttons, the app opens *your own email app* with a pre-filled message to the developer that may
include your app version, device model, Android version, and recent app logs. Nothing is sent unless
you review it and press send. App logs are scrubbed of passwords and session tokens, though they may
contain server hostnames; you can edit the message before sending.

All connections are configured and initiated by you. Hackitz Labs has no visibility into, access to, or
control over them or the data exchanged.

## 4. Data sharing and disclosure

We do not share your data with any third party, because we never receive your data in the first place.
There is no central server, no cloud storage operated by us, and no telemetry. The only parties who can
access your data are you, on your own device, and your OpenMediaVault server, through the connection you
configured.

## 5. Data storage and security

All app data (server login, session, settings) is stored in your device's private app storage, which is
only accessible to OMV Companion and protected by Android's application sandbox. Your credentials are
kept in encrypted storage backed by the Android Keystore.

The connection to your server uses the address you configure. Where your server supports it, we
recommend using HTTPS; on a trusted local network a plain HTTP connection may be used, which is a choice
you control. We do not operate any servers and therefore cannot experience a server-side data breach
affecting your information.

## 6. Permissions

OMV Companion requests the following Android permissions:

- **INTERNET** — required to connect to your OpenMediaVault server.
- **ACCESS_NETWORK_STATE** — used to detect whether your server is reachable, so background
alerts are not attempted while you are away from your network.
- **POST_NOTIFICATIONS** — used to display server-health alerts (optional; you can decline or disable).
- **USE_BIOMETRIC** — used only for the optional app-lock feature (biometric or device-credential authentication).

None of the data accessed through these permissions is transmitted to Hackitz Labs or any third party.

## 7. Children's privacy

OMV Companion is a server-administration tool intended for a general, adult audience. It is not directed
at children under 13, and we do not knowingly collect personal information from children.

## 8. Changes to this policy

If we update this privacy policy, the new version will be published at this URL and the "Effective date"
at the top of this page will be updated. Because OMV Companion does not collect personal data, any
updates are unlikely to affect how your information is handled.

## 9. Contact

If you have any questions about this privacy policy or about OMV Companion's data practices, please open
an issue on the app's [GitHub page](https://github.com/hackitz) or contact us at the address listed in
the Google Play Store listing.

© 2026 Hackitz Labs · OMV Companion · <https://hackitz.github.io/omv-companion-privacy/>
