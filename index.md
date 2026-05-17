  # Privacy Policy — Kisan Dost

_Last updated: 2026-05-17

Kisan Dost ("the app", "we") is an Android and iOS application that helps Indian farmers manage crops, detect crop disease, view local mandi prices and weather, connect with agricultural experts, and trade produce in a marketplace.

This policy explains what personal information the app collects, why, how it is stored, with whom it is shared, and how you can request its deletion. Host this document at a public HTTPS URL and link to it from the Play Store listing and the in-app Profile screen before publishing.

---

## 1. Introduction

Mittee Seeds Private Limited respects your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your personal information when you use the Kisan Dost mobile application ("App").

By using the App, you consent to the data practices described in this policy.

## 2. Information We Collect

### A. Information You Provide Directly

- **Registration Information:** Mobile phone number (for OTP login). Optionally, name, village, state.
- **Profile details** — full name, role (Farmer / Expert / Buyer / Organization / OrgEmployee), optional organisation name and designation.
- **Field details** — polygon coordinates, sowing date, crop name, optional crop variety, and notes that you draw or type when registering a field.
- **User Content:** Photos, videos, text, or audio you upload (e.g., crop scans, community posts, queries to experts).
- **Communication:** Any messages, emails, or call recordings (with your consent) from video calls with experts.
- **Marketplace listings** — crop name, quantity, price, location (district/state), notes, and listing photos.
- **Crop analysis inputs** — photos or short videos of your crops, plus any notes you add.
- **Soil-test certificate** — for users who register as soil testers, the certification image/PDF.
- **Expert profile information** — qualifications, organisation, bio, and pricing if you register as an expert.

### B. Information Collected Automatically

- **Device location** — used while the app is in use, to show local weather and mandi prices, and to centre maps when adding a field. Coarse and fine location.
- **Location Data:** GPS coordinates (with your permission) to provide weather, market prices, and satellite imagery for your fields.
- **Usage Data:** App features you use, time stamps, clickstream, crash logs (via analytics tools like Firebase).
- **Photos/Media:** When you use the crop analyzer, we process the image or video file on our servers to generate the AI result. We may retain anonymized images to improve the model.
- **Push notification token (FCM token)** — used to send you weather, advisory, mandi-price, and chat notifications. Tied to your account on our server.
- **Diagnostic data** — Firebase Crashlytics receives anonymised crash reports (stack traces, OS version, device model). Firebase Analytics records anonymised feature usage events.

### C. Information from Third Parties

- **Satellite Data Providers (Sentinel Hub, Planet):** Provide imagery based on your field polygon.
- **Market Price APIs (www.data.gov.in).**
- **Weather APIs (e.g., OpenWeatherMap, IMD).**
- **Authentication:** If you later allow sign‑in via Google/Facebook, we receive your name and email as per their permissions.

## 3. How We Use Your Information

We use your information for the following purposes:

| Purpose | Legal Basis (under Indian law / GDPR‑inspired) |
|---------|------------------------------------------------|
| To provide, operate, and maintain the App (login, field mapping, AI analysis, video calls) | Performance of contract |
| To generate personalised AI advisory, budget estimates, and health reports of crop | Legitimate interest / consent |
| To display mandi rates, weather, and government schemes relevant to your location | Performance of contract |
| To improve our AI models, satellite processing, and user experience | Legitimate interest (with anonymisation where possible) |
| To communicate with you (notifications, updates, support) | Legitimate interest / consent |
| To prevent fraud, enforce our Terms, and comply with legal obligations | Legal obligation / legitimate interest |
| To serve personalised or non‑personalised advertisements (if any) | Consent (opt‑out available) |

## 4. Why We Collect your Information

| Data type | Purpose |
|-----------|---------|
| Phone number | Account authentication and recovery |
| Profile + organisation | Personalisation and role-based access |
| Field details | Per-field advisories, satellite imagery, alerts |
| Location | Weather, mandi prices, map centring |
| Camera / photos | Crop disease analysis, marketplace and farm-post media |
| Microphone | Expert video calls, farming tip videos |
| FCM token | Push notifications |
| Crashlytics + Analytics | Crash investigation and product improvement |
| Chat messages | Delivery between the two parties of a conversation |

## 5. Sharing of Your Information

We do not sell your personal data. We may share your information in the following situations:

- **Railway** (hosting and database provider, US/EU regions).
- **Google Firebase** — Crashlytics, Analytics, Cloud Messaging, Phone Auth.
- **Anthropic / Google AI** — crop image and video analysis prompts. Images may be transmitted to these providers for inference; they do not train on your data per their default API terms.
- **EOSDA** — satellite imagery for your registered field polygons (field coordinates only).
- **Open-Meteo + Nominatim** — anonymous weather and reverse-geocoding lookups (lat/long only).
- **data.gov.in (AGMARKNET)** — anonymous mandi price queries.
- **Agora.io** — encrypted video/voice call routing for expert consultations.
- **Twilio or MSG91** — SMS delivery for OTP login.
- **Google Maps Platform** — map tiles and places autocomplete (anonymous).
- **Soil-test counterparties / expert counterparties / buyers** — they see only what you publish in your listing or chat with them.
- **With experts:** For video calls, your name, photo (if provided), and crop query may be shared with the independent expert.
- **With marketplace counterparties:** If you list or buy a product, your user name, contact number, and location may be shared with the counterparty to complete the transaction.
- **For legal reasons:** To comply with a court order, government request, or to enforce our rights.
- **Business transfers:** In case of merger, acquisition, or asset sale, your data may be transferred (we will notify you).
- **With your consent:** For any other purpose you authorise.

## 6. Data Retention

We retain your personal information as long as your account is active or as needed to provide you services. After account deletion:

- Account data (name, phone, land details) will be deleted within 90 days.
- Anonymised crop scan images and AI analysis results may be retained to improve our algorithms.
- Marketplace transaction records may be retained for 7 years per tax laws.
- Chat logs and video call recordings (if any) will be deleted after [6 months] unless required for legal proceedings.

## 7. How Long We Keep it

- **Account data:** while your account exists. You can request deletion.
- **Crop analysis history:** while your account exists.
- **Mandi price history per slice:** 180 days rolling.
- **Mandi slice query rows:** 90 days idle (then auto-purged by a daily job).
- **Crashlytics / Analytics:** per Firebase defaults (≈90 days for events, 60 days for crashes).
- **Backups:** rolling backups retained per our cloud provider’s defaults (currently Railway PostgreSQL backups).

## 8. Your Rights and Choices

You have the following rights regarding your personal data:

- **Access and rectification:** You can view and update your profile and land details in the App.
- **Deletion:** You may request account deletion by contacting our Grievance Officer. Some data may be retained as required by law.
- **Opt‑out of analytics/personalised ads:** You can disable analytics tracking (if option provided in App settings).
- **Location permissions:** You can enable/disable GPS location via your device settings. However, some features (e.g., weather, satellite view) may not work properly.
- **Withdraw consent:** For any processing based on your consent, you may withdraw it by emailing us. Withdrawal may affect your ability to use certain features.

To exercise any of these rights, please contact us at **info@mitteeseeds.com**

## 9. Security

- All network traffic uses HTTPS.
- Authentication tokens are stored in the platform secure storage (Android Keystore, iOS Keychain).
- Passwords (for the legacy email/password path) are hashed with ASP.NET Identity defaults (PBKDF2).
- The backend is hosted on Railway with TLS-terminated edge.
- Access to production secrets is limited to the operator account.

No system is perfectly secure. If you discover a vulnerability, please report it to **Info@mitteeseeds.com**.

We implement reasonable technical and organisational measures (encryption, access controls, secure servers) to protect your data. However, no method of transmission over the internet is 100% secure. You use the App at your own risk.

## 10. Children's Privacy

The App is not intended for children under 13. We do not knowingly collect personal information from children. If we become aware, we will delete it promptly.

## 11. Changes to this Privacy Policy

We may update this policy from time to time. Material changes will be notified via the App or by email. Your continued use after the effective date constitutes acceptance.

## 12. Grievance Officer

**Name:** Nakirikanti Manikanta  
**Designation:** Director  
**Email:** Info@mitteeseeds.com  
**Address:**  
MSP MITTEE SEEDS PRIVATE LIMITED  
P NO-86, Padmanagar Phase - II,  
Quthbullapur, Medchal-Malkajgiri,  
Telangana, 500054 India.

You may contact the Grievance Officer for any privacy‑related concerns.

## 13. Governing Law

This Privacy Policy is governed by the laws of India, including the Information Technology Act, 2000, and the SPDI Rules, 2011 (and the Digital Personal Data Protection Act, 2023 once notified).
