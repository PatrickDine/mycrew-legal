---
title: Privacy Policy
---

# Privacy Policy — MyCrew Roster & MyCrew Partner

**Effective date:** 27 October 2026  
**Developer:** Mohamed BOUDINE  
**Contact:** [mohamed-aero@hotmail.com](mailto:mohamed-aero@hotmail.com)

This policy covers two iOS apps: **MyCrew Roster** (for Air Algérie flight crew) and **MyCrew Partner** (for the family of a crew member who chooses to share their roster). Neither app contains advertising, analytics or tracking SDKs, and no data is sold or shared for advertising.

MyCrew is an independent app. It is not made, endorsed or operated by Air Algérie.

---

## 1. MyCrew Roster

### 1.1 Your eCrew sign-in
- Your eCrew user ID and password are stored in the iOS Keychain on your device.
- They are sent over HTTPS to Air Algérie eCrew, and to the MyCrew relay (a server function we operate on Supabase) for features that eCrew only answers from a server: flight information, crew lists for your flights, the logbook report and the swap marketplace.
- The relay never stores your password. It keeps a keyed hash (HMAC) of the password eCrew last accepted, so that a cached eCrew session is only served back to you, and it keeps the eCrew session itself for up to 12 minutes so that features do not sign you in repeatedly.

### 1.2 Data kept on your device
Your roster, pairings, crew lists, layovers, logbook, payroll estimates, preferences and fatigue data are stored in the app on your device. If iCloud is enabled, some settings sync through your own iCloud account. You can clear the cached roster in Settings, and signing out removes your credentials from the device.

### 1.3 Data stored on our server
| Data | Why | Linked to |
|---|---|---|
| Crew ID and a push-notification token | To deliver chat and roster-change notifications | Your crew ID |
| Crew chat messages, photos, voice notes and documents | To deliver messages to other crew | Stored end-to-end encrypted (AES-GCM); the server sees only sender and recipient crew IDs and timestamps |
| Swap marketplace listings you publish | To show your offer to other crew | Your crew ID |
| Diagnostic reports (errors, crash and hang reports, app and iOS version, device model) | Only if you turn on Diagnostics in Settings, to fix bugs | Your crew ID |

### 1.4 Permissions used on the device only
Location (travel time to the airport and the Radar's AR view), Health sleep data (fatigue estimate), Contacts (matching colleagues with your saved contacts), Calendar (adding a duty when you ask), Camera, Photos and Microphone (profile photo and chat attachments you choose), Bluetooth (relaying crew messages between nearby iPhones when there is no network), Face ID (app lock). This data is not sent to us; chat attachments you choose to send are sent encrypted to the recipients.

### 1.5 Other services the app contacts
Air Algérie eCrew (your roster), Apple (iCloud, push notifications, Maps, WeatherKit), Open-Meteo (weather for airports), public flight-tracking and ADS-B data via our relay (looked up by flight number or aircraft registration only) and Planespotters (aircraft photos by registration). No personal data is sent to these services beyond what each request needs.

---

## 2. MyCrew Partner

- MyCrew Partner has no account. A crew member shares their roster from MyCrew Roster through Apple iCloud (CloudKit sharing). The shared roster lives in the crew member's and your iCloud accounts; we cannot access it.
- The crew member chooses what is shared and can stop sharing at any time; the shared data then stops updating.
- Camera is used only to scan a pairing QR code. Calendar access is used only if you export the roster to a calendar on your device. Siri is used only for the questions you ask it.
- Live flight tracking looks up the flight number in public ADS-B services (adsb.lol, airplanes.live, OpenSky) and the MyCrew relay. Weather comes from Open-Meteo for the airports in the roster. Notifications are scheduled on your device.
- We do not collect any data from MyCrew Partner on our server.

---

## 3. Retention and deletion
Server data is kept only as long as its feature needs it. You can remove your marketplace listings in the app. To have all your server data deleted, email [mohamed-aero@hotmail.com](mailto:mohamed-aero@hotmail.com) with your crew ID.

## 4. Children
Both apps are intended for adults and are not directed to children.

## 5. Changes
If this policy changes, the new version is published on this page with a new effective date.

## 6. Contact
**Mohamed BOUDINE** — [mohamed-aero@hotmail.com](mailto:mohamed-aero@hotmail.com)
