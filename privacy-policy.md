# Privacy Policy for Rhyme-IT

**Last updated:** 15-08-2026

Rhyme-IT ("the app", "we", "us") is a nursery-rhyme reading app for parents, grandparents and their children. This policy explains what information the app handles, why, and the choices you have. It's written to be read by a parent, not a lawyer — but you (the developer) should have it reviewed before publishing, and fill in the bracketed placeholders below.

## The short version

Rhyme-IT has no server, no user accounts, and no advertising or analytics SDKs. Everything you create in the app — your child's favourites, your theme preference, and any voice recordings you make — stays stored on your own device unless you explicitly choose to export it somewhere yourself. We never see it.

## Information the app stores on your device

Rhyme-IT stores the following data locally, in the app's own private storage on your device. None of it is transmitted to us, because we don't operate any servers the app talks to.

- **Voice recordings.** If you record yourself (or another family member) reading a rhyme, that audio is saved as a file in the app's private storage and never leaves your device unless you use the export feature described below.
- **Voice profiles.** The name, an optional relationship label (e.g. "Mum", "Nani"), and a colour tag you choose for each person who records rhymes.
- **Favourites.** Which rhymes you've marked as favourites.
- **App preferences.** Your chosen theme (light/dark/system) and text-size setting.
- **Purchase status.** Whether you've purchased the full version, and which plan — see [In-app purchases](#in-app-purchases) below for how this is actually determined.

None of the above requires creating an account, and none of it is linked to your identity beyond what's stored on your own device.

## Permissions the app requests

| Permission | Why |
|---|---|
| **Microphone** (`RECORD_AUDIO`) | Only used when you actively tap "record" to capture a voice reading of a rhyme. The app does not access the microphone at any other time. |
| **Notifications** (`POST_NOTIFICATIONS`) | Used to show the playback controls on your lock screen / notification shade while Background Play is running. |
| **Foreground service / media playback** | Lets recordings keep playing in the background (screen off, app minimised) once Background Play is started, and shows the associated system media notification. |

The app does not request access to your contacts, precise location, camera, or any other permission beyond what's listed above.

## Data backup and export — a choice you make, not something we do

Rhyme-IT includes an optional "Backup recordings" / "Restore recordings" feature in Settings. When you use it:

- **Backup** bundles your recordings and voice profile details into a single file and hands it to Android's standard "Save to…" picker. You choose where it goes — your device's storage, an SD card, Google Drive, or any other location/app your phone offers in that picker. The app never uploads this file itself; it only exists wherever *you* chose to save it.
- **Restore** works the same way in reverse: you pick a previously saved backup file, and the app reads it back in.

If you choose to save a backup to Google Drive, Dropbox, or any other cloud storage app, that copy is then subject to *that service's* privacy policy — not this one — since it's stored and managed by them, not by us.

## Children's privacy

Rhyme-IT is designed to be used by parents and children together, with an adult managing recordings, purchases and settings. We do not knowingly collect personal information directly from children, and the app does not include chat, social features, user-generated content sharing, behavioural advertising, or third-party analytics/advertising SDKs of any kind.

Any name, voice recording, or profile label you enter for a child or family member is stored only on your own device, under your control, and can be deleted at any time from within the app.

## In-app purchases

Rhyme-IT offers an optional full-version purchase (a monthly subscription or a one-time lifetime purchase) to unlock the complete rhyme library and additional features. All payments are handled entirely by **Google Play Billing** — Rhyme-IT never sees or stores your payment card details, billing address, or other payment information. Google's handling of that transaction is governed by the [Google Play Terms of Service](https://play.google.com/about/play-terms/) and [Google's Privacy Policy](https://policies.google.com/privacy), not this policy.

The app checks your purchase status with Google Play to determine what to unlock; this check does not involve sending any of your recordings, profiles, or other in-app data to Google.

## Third-party services

- **Google Play Billing** — processes purchases, as described above.
- **Google Play services** on your device may be involved in delivering app updates and (if applicable) crash diagnostics as part of standard Android platform behaviour — this is Google Play Store infrastructure, not something Rhyme-IT integrates directly.

Rhyme-IT does not include any advertising network, analytics SDK, or crash-reporting SDK of its own.

## Data retention and deletion

Everything Rhyme-IT stores lives in the app's private storage on your device. You can delete any individual recording, voice profile, or favourite at any time from within the app. Uninstalling the app removes all of this data from your device (any backup file you separately saved elsewhere is unaffected, since it's outside the app's control once exported).

## Security

Voice recordings and profile data are stored in the app's private, sandboxed storage area, which other apps on your device cannot access under normal Android security rules. Files you choose to export via the backup feature are not currently encrypted before being handed to the system file picker — treat any backup file with the same care you'd give any other file containing family recordings.

## Changes to this policy

If this policy changes, we'll update the "Last updated" date at the top of this document. Significant changes will be reflected in the app's release notes.

## Contact

Questions about this policy or your data can be sent to:

**climbedapps@gmail.com**
**ClimbedApps**
