  # Privacy Policy — Kisan Dost

_Last updated: 2026-05-11._

Kisan Dost ("the app", "we") is an Android and iOS application that helps Indian farmers manage crops, detect crop disease, view local mandi prices and weather, connect with agricultural experts, and trade produce in a marketplace.

This policy explains what personal information the app collects, why, how it is stored, with whom it is shared, and how you can request its deletion. Host this document at a public HTTPS URL and link to it from the Play Store listing and the in-app Profile screen before publishing.

---

## 1. Information we collect

### 1.1 Information you provide
- **Phone number** — used as your account identifier. Verified via SMS OTP.
- **Profile details** — full name, role (Farmer / Expert / Buyer / Organization / OrgEmployee), optional organisation name and designation.
- **Field details** — polygon coordinates, sowing date, crop name, optional crop variety, and notes that you draw or type when registering a field.
- **Marketplace listings** — crop name, quantity, price, location (district/state), notes, and listing photos.
- **Crop analysis inputs** — photos or short videos of your crops, plus any notes you add.
- **Soil-test certificate** — for users who register as soil testers, the certification image/PDF.
- **Expert profile information** — qualifications, organisation, bio, and pricing if you register as an expert.
- **Chat and consultation messages** — text exchanged with experts and marketplace counterparties.
- **Ratings and reviews** — scores and text you submit for experts and listings.

### 1.2 Information collected automatically
- **Device location** — used while the app is in use, to show local weather and mandi prices, and to centre maps when adding a field. Coarse and fine location.
- **Camera and microphone** — accessed only when you tap Analyse, start a video call, or record a farming tip video.
- **Photos** — accessed only when you pick an existing image from your library.
- **Push notification token (FCM token)** — used to send you weather, advisory, mandi-price, and chat notifications. Tied to your account on our server.
- **Diagnostic data** — Firebase Crashlytics receives anonymised crash reports (stack traces, OS version, device model). Firebase Analytics records anonymised feature usage events.

### 1.3 Information we do NOT collect
- We do not collect your contacts, SMS messages, call logs, browser history, or device-stored files outside the ones you explicitly select.
- We do not sell your data.
- We do not show third-party advertising.

---

## 2. Why we collect it

| Data type | Purpose |
|---|---|
| Phone number | Account authentication and recovery |
| Profile + organisation | Personalisation and role-based access |
| Field details | Per-field advisories, satellite imagery, alerts |
| Location | Weather, mandi prices, map centring |
| Camera / photos | Crop disease analysis, marketplace and farm-post media |
| Microphone | Expert video calls, farming tip videos |
| FCM token | Push notifications |
| Crashlytics + Analytics | Crash investigation and product improvement |
| Chat messages | Delivery between the two parties of a conversation |

---

## 3. How long we keep it

- **Account data**: while your account exists. You can request deletion (see §6).
- **Crop analysis history**: while your account exists.
- **Mandi price history per slice**: 180 days rolling.
- **Mandi slice query rows**: 90 days idle (then auto-purged by a daily job).
- **Crashlytics / Analytics**: per Firebase defaults (≈90 days for events, 60 days for crashes).
- **Backups**: rolling backups retained per our cloud provider's defaults (currently Railway PostgreSQL backups).

---

## 4. Who we share it with

We share data with the following processors **only** to operate the app:

- **Railway** (hosting and database provider, US/EU regions).
- **Google Firebase** — Crashlytics, Analytics, Cloud Messaging, Phone Auth.
- **Anthropic / Google AI** — crop image and video analysis prompts. Images may be transmitted to these providers for inference; they do not train on your data per their default API terms.
- **EOSDA** — satellite imagery for your registered field polygons (field coordinates only).
- **Open-Meteo** + **Nominatim** — anonymous weather and reverse-geocoding lookups (lat/long only).
- **data.gov.in (AGMARKNET)** — anonymous mandi price queries.
- **Agora.io** — encrypted video/voice call routing for expert consultations.
- **Twilio or MSG91** — SMS delivery for OTP login.
- **Google Maps Platform** — map tiles and places autocomplete (anonymous).
- **Soil-test counterparties / expert counterparties / buyers** — they see only what you publish in your listing or chat with them.

We do not share data with any other third party for marketing, profiling, or sale.

---

## 5. Security

- All network traffic uses HTTPS.
- Authentication tokens are stored in the platform secure storage (Android Keystore, iOS Keychain).
- Passwords (for the legacy email/password path) are hashed with ASP.NET Identity defaults (PBKDF2).
- The backend is hosted on Railway with TLS-terminated edge.
- Access to production secrets is limited to the operator account.

No system is perfectly secure. If you discover a vulnerability, please report it to **narenderreddy80@gmail.com**.

---

## 6. Your rights

You can:

- **Access** the data we hold about you — email us.
- **Correct** profile information from the in-app Profile screen.
- **Delete** your account by emailing **narenderreddy80@gmail.com** with the subject "Delete my Kisan Dost account" from the phone-number-linked email, OR by using the in-app Delete Account option when present. Deletion removes your profile, fields, listings, posts, ratings, chats, and crop-analysis history within 30 days. Aggregated analytics and SMS provider logs may persist longer per those providers' own retention policies.
- **Opt out of analytics** — disable Firebase Analytics via your device's app settings.

---

## 7. Children

Kisan Dost is not directed at users under 13. We do not knowingly collect data from anyone under 13. If you believe a child has registered, email us and we will remove the account.

---

## 8. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top reflects the latest revision. Material changes will be announced in-app.

---

## 9. Contact

**Operator**: Kisan Dost development team
**Email**: narenderreddy80@gmail.com
**Country of operation**: India
