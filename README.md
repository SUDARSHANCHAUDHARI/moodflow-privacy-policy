# MoodFlow Privacy Policy 📱🔒

<div align="center">

**Official Privacy Policy Repository for MoodFlow Android Application**

[![Privacy](https://img.shields.io/badge/Privacy-First-green.svg)](./PRIVACY_POLICY.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com/SUDARSHANCHAUDHARI/MoodFlow)

*Your privacy is our priority. All your personal data stays on your device.*

</div>

---

## 📋 About This Repository

This repository hosts the official privacy policy for the **MoodFlow** Android application. It is maintained for:

- **Public Access**: Easy access to our privacy policy
- **Google Play Store**: Required privacy policy link for app listing
- **Transparency**: Clear communication about how we handle your data
- **Compliance**: Meeting privacy regulations (GDPR, CCPA, etc.)

---

## 🎯 About MoodFlow

**MoodFlow** is a beautiful native Android app designed for mood tracking, emotional wellness, and mental health management. The app helps you:

- 📊 **Daily Mood Tracking**: Track your emotions (Happy, Sad, Anxious, Calm, Angry) with intensity levels
- 📔 **Mood Journal**: Visual calendar view with detailed mood entries, notes, and triggers
- 🤖 **AI-Powered Insights**: Weekly pattern analysis powered by Google Gemini AI
- 💡 **Coping Strategies**: 20+ evidence-based strategies personalized to your mood
- 📈 **Analytics & Charts**: Beautiful visualizations of your mood trends and patterns
- 🔥 **Streak Tracking**: Build consistent self-care habits with streak milestones
- 📄 **PDF Reports**: Export detailed mood reports for healthcare providers (Premium)
- 🔔 **Smart Notifications**: Customizable daily reminders for mood check-ins

**Learn more**: [Main MoodFlow Repository](https://github.com/SUDARSHANCHAUDHARI/MoodFlow)

---

## 🔒 Privacy-First Design

MoodFlow is built with **privacy as a core principle**. We believe your personal mood data, journal entries, and emotional insights should remain private and secure.

### Core Privacy Principles

1. **Local-First Storage**: All your personal data is stored locally on your device
2. **No Cloud Storage**: We don't store your data on any remote servers
3. **No User Accounts**: No account creation required - reducing data exposure
4. **Minimal Data Collection**: We only collect what's necessary for app functionality
5. **Transparent Practices**: Clear communication about what data we access and why

---

## 📊 What Data We Collect

### Personal Content (Stored Locally Only)

- **Mood Entries**: Your daily mood tracking data, including:
  - Emotion type (Happy, Sad, Anxious, Calm, Angry)
  - Intensity level (1-10 scale)
  - Optional notes and journal entries
  - Trigger tags (Work, Relationships, Health, Sleep, Weather, Social, Other)
  - Date and timestamp
- **Coping Strategies**: Your usage data, including:
  - Strategies you've used
  - Favorite strategies
  - Usage frequency
- **Activity Logs**: Your app usage data for streak tracking and statistics
- **Statistics**: Aggregated mood data for insights and charts

### App Preferences (Stored Locally Only)

- Theme settings (Light, Dark, System Default)
- Notification preferences (reminder times, frequency)
- Premium subscription status (stored locally)
- API key (if you provide your own Google Gemini API key)

### What We DON'T Collect

- ❌ Personal identification information (name, email, phone)
- ❌ Location data
- ❌ Contact information
- ❌ Payment information (handled by Google Play)
- ❌ Biometric data
- ❌ Device identifiers for tracking
- ❌ Health records or medical information

---

## 💾 Data Storage & Security

### Local Storage

**All your personal data is stored locally on your device using:**

- **Room Database**: Encrypted local database for mood entries, coping strategies, and activity logs
- **DataStore**: Secure local storage for app preferences
- **EncryptedSharedPreferences**: For sensitive data like premium status
- **No Cloud Sync**: Your data never leaves your device

### Security Measures

- ✅ **Encryption**: All local data is encrypted using Android's built-in encryption
- ✅ **No Network Transmission**: Mood entries and notes are never sent over the network
- ✅ **Secure API Keys**: API keys stored securely using DataStore
- ✅ **FileProvider**: Secure file sharing for exported data and PDF reports
- ✅ **Regular Updates**: Security patches and updates applied regularly

### Data Retention

- **Mood Entries**: Retained until you delete them manually
- **Coping Strategies**: Pre-populated strategies remain; your usage data is retained locally
- **Activity Logs**: Retained for streak calculation and statistics
- **Exported Data**: Files you export are stored in your device's Downloads folder
- **Uninstall**: All data is deleted when you uninstall the app

---

## 🌐 Third-Party Services

### Google Gemini API

- **Purpose**: Generate AI-powered mood insights and pattern analysis
- **Data Sent**: Only aggregated mood data (emotion types, intensity, dates) - **NOT your personal notes or journal entries**
- **Data NOT Sent**: 
  - ❌ Your journal notes or text entries
  - ❌ Personal information
  - ❌ Device identifiers
  - ❌ Trigger details
- **Privacy Policy**: [Google Privacy Policy](https://policies.google.com/privacy)

### Google Play Billing

- **Purpose**: Process premium subscription purchases
- **Data Collected**: Handled entirely by Google Play Services
- **No Personal Data**: We don't receive or store payment information
- **Privacy Policy**: [Google Play Privacy Policy](https://policies.google.com/privacy)

### Google Play Services (Optional)

- **Purpose**: Analytics and crash reporting (if enabled)
- **Data Collected**: Aggregated, anonymized usage statistics
- **No Personal Data**: No personally identifiable information is collected

---

## 🔐 Permissions Explained

### Required Permissions

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **INTERNET** | Connect to Google Gemini API | Generate AI insights (optional - app works offline for mood tracking) |
| **POST_NOTIFICATIONS** | Send push notifications | Daily mood check-in reminders based on your preferences |

### Privacy Controls

- ✅ **Offline Mode**: App works without internet connection for mood tracking
- ✅ **Notification Control**: Enable/disable notifications anytime in Settings
- ✅ **API Key Control**: Use your own Gemini API key or default (if available)
- ✅ **Data Export**: Export your mood entries to JSON or PDF anytime
- ✅ **Data Deletion**: Delete individual entries or all data in Settings

---

## 👤 Your Rights

### Data Control

- **View Your Data**: Access all your mood entries, statistics, and insights in the app
- **Edit Your Data**: Modify or delete mood entries anytime
- **Export Your Data**: Export mood entries to JSON or PDF (Settings → Export)
- **Delete Your Data**: Clear individual entries or all data (Settings → Clear All Data)
- **Uninstall**: Uninstalling removes all local data

### GDPR Rights (EU Users)

If you're in the European Union, you have additional rights:

- ✅ **Right to Access**: View all your personal data
- ✅ **Right to Rectification**: Edit inaccurate data
- ✅ **Right to Erasure**: Delete your data at any time
- ✅ **Right to Data Portability**: Export your data in JSON or PDF format
- ✅ **Right to Object**: Disable analytics (if implemented)

**How to Exercise**: Use the app's built-in features or contact us directly.

---

## 📱 App Information

- **Package Name**: `com.sudarshantechlabs.moodflow`
- **Version**: 1.0.0
- **Min SDK**: 26 (Android 8.0)
- **Target SDK**: 34 (Android 14)
- **Platform**: Android only
- **Language**: Kotlin
- **Architecture**: MVVM with Jetpack Compose

---

## 📄 Privacy Policy

The complete, detailed privacy policy is available in [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).

**Key Sections:**
- Information We Collect
- How We Use Your Information
- Data Storage & Retention
- Data Sharing
- Your Rights and Controls
- Children's Privacy
- Permissions Explained
- Security Measures
- GDPR Rights
- Contact Information

---

## 🚨 Important Privacy Highlights

### ✅ What We Do

- Store all data locally on your device
- Use encryption for local storage
- Only send aggregated mood data to Gemini API (not your notes)
- Allow you to export or delete your data anytime
- Work offline for mood tracking
- Respect your privacy choices

### ❌ What We DON'T Do

- Store your data in the cloud
- Share your data with third parties
- Sell your data
- Track you across apps or websites
- Require user accounts
- Collect location data
- Access your contacts or photos
- Read your personal notes or journal entries

---

## 📞 Contact & Support

### Privacy-Related Questions

If you have questions about:
- How we handle your data
- Your privacy rights
- Data deletion requests
- GDPR compliance
- Security concerns

**Contact Us:**
- **Email**: sudarshantechlabs@gmail.com
- **Developer Email**: sunny.sudarshan@gmail.com
- **Website**: https://sudarshantechlabs.com
- **GitHub Issues**: [MoodFlow Repository](https://github.com/SUDARSHANCHAUDHARI/MoodFlow/issues)

### Response Time

We aim to respond to privacy-related inquiries within **48 hours**.

---

## 🔄 Policy Updates

We may update this privacy policy from time to time to reflect:
- Changes in app features
- Legal requirements
- Best practices
- User feedback

**How We Notify You:**
- In-app notifications for significant changes
- App update release notes
- Updated "Last updated" date in the policy

**Last Updated**: January 2025

---

## 📚 Additional Resources

- **[Main App Repository](https://github.com/SUDARSHANCHAUDHARI/MoodFlow)**: Source code and documentation
- **[Google Privacy Policy](https://policies.google.com/privacy)**: Third-party service privacy
- **[GDPR Information](https://gdpr.eu/)**: European privacy regulations
- **[CCPA Information](https://oag.ca.gov/privacy/ccpa)**: California privacy regulations

---

## 🏢 About Sudarshan Tech Labs

**MoodFlow** is developed and published by **Sudarshan Tech Labs**.

- **Company**: Sudarshan Tech Labs
- **Website**: https://sudarshantechlabs.com
- **Email**: sudarshantechlabs@gmail.com
- **Developer**: Sudarshan Kishor Chaudhari
- **Developer Email**: sunny.sudarshan@gmail.com

---

## 📜 License

This privacy policy repository is licensed under the **MIT License**.

See [LICENSE](./LICENSE) file for details.

---

## ⭐ Quick Privacy Summary

<div align="center">

### 🔒 Your Data Stays Local

**All your personal content (mood entries, notes, journal entries) is stored on your device and never sent to any server.**

| Feature | Privacy Status |
|---------|---------------|
| Mood Entries | ✅ 100% Local |
| Journal Notes | ✅ 100% Local |
| Coping Strategies | ✅ 100% Local |
| Statistics | ✅ Calculated Locally |
| App Preferences | ✅ Stored Locally |
| AI Insights | ⚠️ Aggregated Data Only (No Notes) |
| Analytics | ⚠️ Optional (Anonymized) |

</div>

---

<div align="center">

**Made with ❤️ by Sudarshan Tech Labs**

*Privacy is not a feature - it's a fundamental right.*

[View Full Privacy Policy](./PRIVACY_POLICY.md) | [Main App Repository](https://github.com/SUDARSHANCHAUDHARI/MoodFlow)

</div>
