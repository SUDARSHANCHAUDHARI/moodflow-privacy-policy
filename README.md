# MoodFlow — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

MoodFlow is a mood tracking and mental wellness app for Android. It helps you log daily moods, identify patterns through charts, and optionally receive AI-powered insights via Google Gemini. Mood data is stored locally on your device. The App uses Firebase for analytics and crash reporting.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Mood entries (mood rating, notes, date, time) | Core mood tracking | Room database (encrypted) |
| Mood tags and categories | Entry organisation | Room database (encrypted) |
| App preferences and notification settings | Personalisation | DataStore on your device |
| PDF mood reports | Data export | App private storage |

### Data Collected by Third-Party Services

**Firebase Analytics:**
- App usage events (e.g., mood logged, screen views, feature used)
- Device model, OS version, app version, language
- Session duration and navigation paths
- No mood content or personal notes are included

**Firebase Crashlytics:**
- Device model, OS version, app version
- Crash stack traces
- No mood data or personal information is included

**Google Gemini API (user-initiated only):**
When you request AI mood insights, anonymised mood pattern data (ratings and dates, no personal notes) is sent to the Gemini API. Sudarshan Tech Labs does not retain this data.

**Google Play Billing:**
In-app purchases for premium features are processed by Google Play. Sudarshan Tech Labs does not receive or store payment information.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Log and display mood entries | Local encrypted mood data |
| Show mood trends and charts | Local mood history |
| Send mood reminder notifications | Local WorkManager schedules |
| Generate AI mood insights (on request) | Mood ratings sent to Gemini API |
| Export mood data to PDF | Local data (iText7, on-device) |
| Improve app quality | Firebase Analytics (aggregated) |
| Fix crashes | Firebase Crashlytics |

---

## Data Storage and Security

- **Mood data:** Stored in an encrypted Room database (security-crypto)
- **No Sudarshan Tech Labs cloud storage:** We operate no backend server
- **Firebase:** Google's infrastructure with encryption in transit and at rest
- **Android sandbox:** Protected by Android's application isolation

## Data Retention

| Data | Retention |
|---|---|
| Local mood data | Until you delete it or uninstall the App |
| Firebase Analytics | Aggregated, 14 months (Firebase default) |
| Firebase Crashlytics | 90 days (Firebase default) |

---

## Data Sharing

We do not sell your mood data. Data is shared only with:

- **Google (Firebase Analytics, Crashlytics, Gemini, Play Billing):** https://policies.google.com/privacy

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `INTERNET` | Required for Firebase, Gemini API, and Google Play Billing |
| `POST_NOTIFICATIONS` | Send daily mood reminder notifications |

---

## Your Rights and Controls

- **Delete individual mood entries:** Use the delete function in the App
- **Delete all data:** Uninstall or go to Android Settings > Apps > MoodFlow > Storage > Clear Data
- **Disable AI insights:** Turn off the feature in App Settings

---

## Children's Privacy

MoodFlow is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of MoodFlow after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Mood data | Local only (encrypted) | No | App functionality |
| App interactions | Yes (Firebase Analytics) | No | Analytics |
| Crash logs | Yes (Crashlytics) | No | App stability |
| Mood ratings (Gemini) | On request | Google (Gemini) | AI insights |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
