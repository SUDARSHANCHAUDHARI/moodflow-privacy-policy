# MoodFlow Privacy Policy

**Last Updated**: January 13, 2025

**Effective Date**: January 13, 2025

---

## 1. Introduction

Welcome to **MoodFlow** ("we," "our," or "us"). We are committed to protecting your privacy and ensuring the security of your personal information. This Privacy Policy explains how we collect, use, store, and protect your data when you use the MoodFlow Android application.

By using MoodFlow, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Collect

### 2.1 Personal Content (Stored Locally Only)

MoodFlow collects the following personal content, which is **stored exclusively on your device**:

#### Mood Entries
- **Emotion Type**: One of five emotions (Happy, Sad, Anxious, Calm, Angry)
- **Intensity Level**: A value from 1 to 10
- **Notes**: Optional text notes you write (up to 500 characters)
- **Triggers**: Optional tags you select (Work, Relationships, Health, Sleep, Weather, Social, Other)
- **Timestamp**: Date and time of each mood entry

#### Coping Strategies Data
- **Usage History**: Which coping strategies you've used
- **Favorites**: Strategies you've marked as favorites
- **Usage Frequency**: How often you use each strategy
- **Effectiveness**: Your interaction with strategies

#### Activity Logs
- **Daily Activity**: Whether you logged a mood entry each day
- **Streak Information**: Current and longest streak counts
- **Entry Counts**: Total number of mood entries

#### Statistics
- **Aggregated Data**: Calculated statistics such as:
  - Total entries
  - Average intensity
  - Most common emotion
  - Days active
  - Mood trends over time

### 2.2 App Preferences (Stored Locally Only)

- **Theme Settings**: Light, Dark, or System Default theme preference
- **Notification Preferences**: Reminder times and frequency settings
- **Premium Status**: Whether you have an active premium subscription (stored locally)
- **API Configuration**: Your Google Gemini API key (if you provide your own)

### 2.3 What We DON'T Collect

We do **NOT** collect:
- Personal identification information (name, email address, phone number)
- Location data or GPS coordinates
- Contact information from your device
- Payment information (handled by Google Play)
- Biometric data (fingerprints, face recognition)
- Device identifiers for tracking purposes
- Health records or medical information
- Photos or images from your device

---

## 3. How We Use Your Information

### 3.1 Local Data Usage

All data collected by MoodFlow is used **exclusively on your device** for:

- **Mood Tracking**: Storing and displaying your mood entries
- **Journal Functionality**: Creating calendar views and entry lists
- **Statistics Calculation**: Generating insights and analytics
- **Streak Tracking**: Calculating and displaying your consistency streaks
- **Coping Strategy Recommendations**: Suggesting strategies based on your mood patterns
- **App Customization**: Applying your theme and notification preferences

### 3.2 AI Insights (Google Gemini API)

When you use the AI Insights feature:

- **Data Sent**: Only aggregated, anonymized mood data:
  - Emotion types (without personal notes)
  - Intensity levels
  - Dates (without specific timestamps)
  - Trigger categories (without details)
- **Data NOT Sent**:
  - ❌ Your personal notes or journal text
  - ❌ Personal information
  - ❌ Device identifiers
  - ❌ Specific trigger details
- **Purpose**: Generate weekly pattern analysis and insights
- **Privacy**: Your personal notes and journal entries remain completely private

### 3.3 Premium Features

- **Subscription Status**: Stored locally to enable/disable premium features
- **Payment Processing**: Handled entirely by Google Play Billing
- **No Payment Data**: We never receive or store your payment information

---

## 4. Data Storage & Security

### 4.1 Local Storage

All your personal data is stored **locally on your device** using:

- **Room Database**: Encrypted local database for:
  - Mood entries
  - Coping strategies usage data
  - Activity logs
- **DataStore**: Secure local storage for:
  - App preferences
  - Theme settings
  - Notification preferences
- **EncryptedSharedPreferences**: For sensitive data like premium status
- **FileProvider**: Secure file sharing for exported data and PDF reports

### 4.2 Security Measures

We implement the following security measures:

- ✅ **Encryption**: All local data is encrypted using Android's built-in encryption
- ✅ **No Network Transmission**: Your mood entries and notes are never transmitted over the network
- ✅ **Secure API Keys**: API keys stored securely using DataStore
- ✅ **FileProvider**: Secure file sharing mechanism for exported files
- ✅ **HTTPS Only**: All network communication uses HTTPS
- ✅ **No Cloud Storage**: Your data never leaves your device
- ✅ **Regular Updates**: Security patches and updates applied regularly

### 4.3 Data Retention

- **Mood Entries**: Retained on your device until you manually delete them
- **Coping Strategies**: Pre-populated strategies remain; your usage data is retained locally
- **Activity Logs**: Retained for streak calculation and statistics
- **Exported Files**: Stored in your device's Downloads folder (you control these files)
- **Uninstall**: All app data is automatically deleted when you uninstall the app

---

## 5. Data Sharing

### 5.1 We Do NOT Share Your Data

**MoodFlow does NOT:**
- Share your data with third parties
- Sell your data to advertisers or data brokers
- Use your data for marketing purposes
- Share your data with other apps
- Upload your data to cloud servers

### 5.2 Third-Party Services

#### Google Gemini API
- **Purpose**: Generate AI-powered mood insights
- **Data Shared**: Only aggregated, anonymized mood statistics (no personal notes)
- **Privacy Policy**: [Google Privacy Policy](https://policies.google.com/privacy)

#### Google Play Billing
- **Purpose**: Process premium subscription purchases
- **Data Shared**: Handled entirely by Google Play Services
- **Privacy Policy**: [Google Play Privacy Policy](https://policies.google.com/privacy)

#### Google Play Services (Optional)
- **Purpose**: Analytics and crash reporting (if enabled)
- **Data Shared**: Aggregated, anonymized usage statistics only
- **No Personal Data**: No personally identifiable information is shared

---

## 6. Your Rights and Controls

### 6.1 Data Access

You can access all your data directly in the app:
- View all mood entries in the Journal screen
- View statistics in the Profile screen
- View insights in the Insights screen
- View coping strategies in the Resources screen

### 6.2 Data Modification

You have full control to:
- **Edit Entries**: Modify mood entries (emotion, intensity, notes, triggers)
- **Delete Entries**: Delete individual mood entries or all entries
- **Update Preferences**: Change theme, notifications, and other settings
- **Manage Strategies**: Mark/unmark favorites, track usage

### 6.3 Data Export

You can export your data at any time:
- **JSON Export**: Export all mood entries to a JSON file
- **PDF Export**: Generate detailed mood reports in PDF format (Premium feature)
- **Location**: Exported files are saved to your device's Downloads folder
- **Control**: You can share, move, or delete exported files as you wish

### 6.4 Data Deletion

You can delete your data:
- **Individual Entries**: Delete specific mood entries from the Journal screen
- **All Data**: Clear all data from Settings → Clear All Data
- **Uninstall**: Uninstalling the app removes all local data

---

## 7. Children's Privacy

MoodFlow is not intended for children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us immediately.

If we discover that we have collected information from a child under 13, we will delete that information promptly.

---

## 8. Permissions Explained

### 8.1 Required Permissions

#### INTERNET
- **Purpose**: Connect to Google Gemini API for AI insights
- **When Used**: Only when you request AI insights
- **Privacy**: App works fully offline for mood tracking without this permission

#### POST_NOTIFICATIONS
- **Purpose**: Send daily mood check-in reminder notifications
- **When Used**: Based on your notification preferences
- **Control**: You can disable notifications anytime in Settings

### 8.2 Optional Permissions

MoodFlow does not require any other permissions. All core features work without additional permissions.

---

## 9. GDPR Rights (European Users)

If you are located in the European Economic Area (EEA), you have the following rights under the General Data Protection Regulation (GDPR):

### 9.1 Right to Access
You have the right to access all personal data we hold about you. You can view all your data directly in the app.

### 9.2 Right to Rectification
You have the right to correct inaccurate or incomplete data. You can edit mood entries directly in the app.

### 9.3 Right to Erasure
You have the right to request deletion of your data. You can delete entries or all data using the app's built-in features.

### 9.4 Right to Data Portability
You have the right to receive your data in a portable format. Use the Export feature to export your data to JSON or PDF.

### 9.5 Right to Object
You have the right to object to processing of your data. You can disable features that process your data (e.g., AI insights).

### 9.6 Right to Restrict Processing
You have the right to restrict how we process your data. Since all processing is local, you can simply stop using features.

### 9.7 Right to Withdraw Consent
You can withdraw consent at any time by deleting the app or clearing all data.

**To Exercise Your Rights**: Use the app's built-in features or contact us at sudarshantechlabs@gmail.com

---

## 10. CCPA Rights (California Users)

If you are a California resident, you have the following rights under the California Consumer Privacy Act (CCPA):

- **Right to Know**: You can request information about what personal information we collect
- **Right to Delete**: You can request deletion of your personal information
- **Right to Opt-Out**: You can opt-out of the sale of personal information (we don't sell data)
- **Right to Non-Discrimination**: We will not discriminate against you for exercising your rights

**To Exercise Your Rights**: Contact us at sudarshantechlabs@gmail.com

---

## 11. International Data Transfers

Since all your data is stored locally on your device, there are no international data transfers. Your data never leaves your device unless you explicitly export it.

---

## 12. Data Breach Notification

In the unlikely event of a data breach affecting your personal information, we will:
- Notify you within 72 hours of becoming aware of the breach
- Provide details about what data was affected
- Explain steps we're taking to address the breach
- Offer guidance on steps you can take to protect yourself

---

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the new Privacy Policy in the app (if applicable)
- Notifying you through app updates for significant changes

Your continued use of MoodFlow after any changes constitutes acceptance of the updated Privacy Policy.

---

## 14. Contact Information

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Sudarshan Tech Labs**
- **Email**: sudarshantechlabs@gmail.com
- **Developer Email**: sunny.sudarshan@gmail.com
- **Website**: https://sudarshantechlabs.com
- **GitHub**: [MoodFlow Repository](https://github.com/SUDARSHANCHAUDHARI/MoodFlow)

**Response Time**: We aim to respond to privacy-related inquiries within 48 hours.

---

## 15. Legal Basis for Processing (GDPR)

For users in the EEA, our legal basis for processing your personal data is:
- **Consent**: You provide consent by using the app and its features
- **Legitimate Interest**: Processing is necessary for app functionality
- **Contract Performance**: Processing is necessary to provide app services

You can withdraw consent at any time by deleting the app or clearing all data.

---

## 16. Data Protection Officer

For privacy-related inquiries, please contact:
- **Email**: sudarshantechlabs@gmail.com
- **Subject**: "Privacy Inquiry - MoodFlow"

---

## 17. Supervisory Authority

If you are in the EEA and believe we have not addressed your privacy concerns, you have the right to file a complaint with your local data protection authority.

---

## 18. Consent

By using MoodFlow, you consent to:
- The collection and use of information as described in this Privacy Policy
- Local storage of your data on your device
- Optional use of Google Gemini API for AI insights (with aggregated data only)

You can withdraw consent at any time by:
- Disabling AI insights in Settings
- Clearing all app data
- Uninstalling the app

---

## 19. Summary

**Key Points:**
- ✅ All your data is stored locally on your device
- ✅ Your personal notes are never sent to any server
- ✅ We don't share your data with third parties
- ✅ You have full control over your data
- ✅ You can export or delete your data anytime
- ✅ The app works offline for mood tracking

**Your Privacy Matters**: We are committed to protecting your privacy and ensuring your personal mood data remains secure and private.

---

**Last Updated**: January 13, 2025

**Version**: 1.0

---

*This Privacy Policy is effective as of the date listed above and will remain in effect except with respect to any changes in its provisions in the future, which will be in effect immediately after being posted in the app or on this page.*
