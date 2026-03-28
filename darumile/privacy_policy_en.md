# Privacy Policy

Last Updated: January 2025

## 1. Introduction

warking Team (hereinafter "we," "us," or "our") respects the privacy of users of our iOS application "warking" (hereinafter "the App") and is committed to protecting your personal information.

This Privacy Policy (hereinafter "Policy") explains what information we collect and how we use and protect it. Please read this Policy carefully before using the App.

The App is not intended for children under 13 years of age. We do not intentionally collect personal information from children under 13.

## 2. Information We Collect

### 2.1 HealthKit Data

| Data Type | Collection Method | Purpose | External Transfer |
|-----------|------------------|---------|-------------------|
| Step Count | Reading from Apple HealthKit | Calculating Daruma/miniature building progress | None |

- We **only read** step data and do not write to HealthKit
- Step data is processed only on the device and is **not sent to external servers**
- Step data is not used for advertising or marketing purposes

### 2.2 Identification Information

| Data Type | Storage Location | Purpose |
|-----------|-----------------|---------|
| Anonymous User ID | Keychain (device) + Firestore (cloud) | User identification, data sync |
| Recovery Code | Keychain (device) + Firestore (cloud) | Data recovery |

- Login is not required. An anonymous user ID is automatically generated when the App is first launched
- We do not collect personally identifiable information such as names, email addresses, or phone numbers

### 2.3 Usage Data

| Data Type | Destination | Purpose |
|-----------|------------|---------|
| Analytics Events | Firebase Analytics | App improvement, usage analysis |
| Crash Reports | Firebase Crashlytics | Bug identification and fixes |

Examples of analytics events collected:
- App launch
- Daruma completion
- Premium plan purchase
- Screen views

### 2.4 Purchase Information

| Data Type | Processor | Purpose |
|-----------|----------|---------|
| Subscription Status | RevenueCat | Managing Premium features |

- We do not directly collect or store payment information such as credit card numbers or bank account details
- Payment processing is conducted through the Apple App Store

### 2.5 Advertising Data

| Data Type | Condition | Destination |
|-----------|-----------|-------------|
| Ad impressions/clicks | Non-Premium users | Google AdMob |
| Advertising Identifier (IDFA) | With ATT consent only | Google AdMob |

- Ads are displayed only to non-Premium users
- On iOS 14.5 and later, explicit consent through App Tracking Transparency (ATT) is required for ad tracking

### 2.6 Locally Stored Data

| Data Type | Storage Location | Purpose |
|-----------|-----------------|---------|
| Daruma progress data | SharedDefaults (App Groups) | Sharing between app and widgets |
| Theme settings | SharedDefaults | Storing user preferences |
| Cached images | App cache directory | Faster display |

- This data is stored only on the device and is used for widget functionality integration

## 3. How We Use Information

We use the collected information for the following purposes:

1. **Service Provision**: Enabling the Daruma/miniature building features based on steps
2. **Premium Feature Management**: Verifying subscription status and providing benefits
3. **App Improvement**: Analyzing usage, identifying and fixing bugs
4. **Ad Display**: Delivering ads to non-Premium users (personalized ads with consent)
5. **Data Recovery**: Restoring user data using Recovery Codes
6. **Customer Support**: Responding to inquiries

## 4. Information Sharing with Third Parties

The App uses the following third-party services to provide its services. Each service has its own privacy policy.

| Service | Company | Purpose | Privacy Policy |
|---------|---------|---------|----------------|
| Firebase Authentication | Google LLC | Anonymous authentication | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Analytics | Google LLC | Usage analysis | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Google LLC | Crash reporting | [Google Privacy Policy](https://policies.google.com/privacy) |
| Cloud Firestore | Google LLC | Data sync | [Google Privacy Policy](https://policies.google.com/privacy) |
| RevenueCat | RevenueCat, Inc. | Subscription management | [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy) |
| Google AdMob | Google LLC | Ad delivery | [Google Privacy Policy](https://policies.google.com/privacy) |
| Cloudflare | Cloudflare, Inc. | CDN/content delivery | [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/) |

We do not sell, rent, or share user information with third parties other than these services, except when required by law.

## 5. Data Storage and Protection

### 5.1 Storage Locations

| Data Type | Storage Location | Security |
|-----------|-----------------|----------|
| User ID, Recovery Code | iOS Keychain | Protected by Apple encryption |
| Daruma progress, settings | SharedDefaults | Access restricted by App Groups |
| Cloud data | Firebase Firestore | Firebase security rules |

### 5.2 Communication Protection

- All data communications are encrypted using HTTPS (TLS)

### 5.3 Data Retention Period

- **Local data**: Stored on the device until the App is deleted
- **Cloud data**: Stored in Firestore until the account is deleted
- **Cache**: Automatically deleted after 7 days
- **Analytics data**: Subject to Google's data retention policy

## 6. User Rights

Users have the following rights:

### 6.1 Access to Data

- You can view your stored data (progress, Recovery Code, etc.) from the settings screen

### 6.2 Data Deletion

- **Local data deletion**: Deleting the App from your device will delete all locally stored data
- **Cloud data deletion**: If you wish to delete data stored in the cloud, please contact us at the address below

### 6.3 Withdrawal of Consent

- **HealthKit access**: You can revoke access permissions from iOS "Settings" > "Privacy & Security" > "Health"
- **Ad tracking**: You can change settings from iOS "Settings" > "Privacy & Security" > "Tracking"

### 6.4 Inquiries

- To exercise the above rights or if you have questions about data handling, please contact us at the address below

## 7. App Tracking Transparency (ATT)

On devices running iOS 14.5 or later, we request permission through App Tracking Transparency (ATT) before tracking for advertising purposes.

### 7.1 If You Allow Tracking

- Personalized ads may be displayed by Google AdMob
- Data may be used for ad effectiveness measurement

### 7.2 If You Do Not Allow Tracking

- You can continue to use the App
- Ads will still be displayed but will not be personalized
- Ad relevance may be reduced

If you use the Premium Plan, ads are not displayed, so ad tracking is not performed regardless of ATT settings.

## 8. Changes to This Policy

1. We may change this Policy due to changes in laws, changes to our services, or other reasons.

2. If there are significant changes, we will notify you through in-app notifications or on our website.

3. If you continue to use the App after changes are made, you will be deemed to have agreed to the updated Policy.

## 9. Contact

For inquiries regarding this Policy or requests for data deletion or disclosure, please contact us at:

**Operator**: warking Team
**Email**: darumanomori@gmail.com

---

End of Policy
