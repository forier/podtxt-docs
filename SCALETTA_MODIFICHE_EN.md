# 📋 LEGAL DOCUMENTS UPDATE ROADMAP
*Comprehensive checklist for updating and aligning Privacy Policy and Terms of Use to GDPR, CCPA/CalOPPA, App Store Connect and Google Play Data Safety requirements, runtime permissions management, localization, cookie policy and EULA standard implementation*

---

## 📅 1. Metadata and Versioning

### 1.1 "Last updated" and Changelog
- [x] Insert "Last updated: April 28, 2025" at the top of Privacy Policy and Terms of Use
- [x] Add a brief changelog (date + summary of changes) at the beginning of each document to track evolutions and revisions

---

## 📄 2. Core Sections to Add or Improve

### 2.1 GDPR Legal Bases and Retention Periods
- [x] Specify the legal bases for processing (consent, contract, legitimate interest)
- [x] Define justified retention periods for each data category, documenting the reasons (e.g., diagnostic logs for 6 months)
- [x] Define retention periods for each data category:
  - [x] Navigation data: 6 months
  - [x] Contact data: until consent revocation
  - [x] Diagnostic logs: 12 months
  - [x] Document reasons for each period

### 2.2 CCPA / CalOPPA
- [x] Integrate specific clauses for California consumer rights:
  - [x] Shine The Light Law (Section 1798.83)
  - [x] Right to Know
  - [x] Right to Delete
  - [x] Right to Opt-Out
- [x] Add information about:
  - [x] Data enrichment
  - [x] Non-discrimination based on rights exercise
  - [x] Identity verification process

### 2.3 Cookie Policy & Tracking Technologies
- [x] Create a dedicated Cookie Policy section:
  - [x] Cookie classification by purpose (necessary, analytics, marketing)
  - [x] Clear opt-out options
  - [x] Link to extended cookie notice
- [x] Indicate use of:
  - [x] Web beacons
  - [x] Tracking pixels
  - [x] Similar technologies
  - [x] Local storage and session storage

### 2.4 Third-Party Services and SDKs
- [x] List of SDKs and third-party services:
  - [x] Firebase (Google Analytics, Firebase, Messaging)
  - [x] Cloud storage (AWS, Google Cloud)
  - [x] RevenueCat or in_app_purchase for subscriptions
  - [x] Apple StoreKit and Google Play Billing for native payment systems
  - [x] App store platforms (Apple App Store, Google Play)
- [x] Type of data accessed:
  - [x] Device ID, error logs, anonymous usage data, transaction information
- [x] All third parties are bound by a Data Processing Agreement (DPA)
- [x] Some services perform cross-border data transfers (example: Firebase to the US)

### 2.5 Security Practices for Mobile
- [x] Secure local storage:
  - [x] Android: flutter_secure_storage or EncryptedSharedPreferences
  - [x] iOS: iOS Keychain
- [x] Encrypted communication using HTTPS/TLS
- [x] Runtime protection:
  - [x] Obfuscation and ProGuard for Android
  - [x] Flutter build optimization for all platforms
- [x] Do not store sensitive data permanently on the device
- [x] Does not record personal data in application logs or crash logs

### 2.6 Data Subject Rights
- [x] Expand GDPR rights exercise methods:
  - [x] Right of access
  - [x] Right of rectification
  - [x] Right of erasure (right to be forgotten)
  - [x] Right to data portability
  - [x] Right to restriction of processing
  - [x] Right to object
- [x] Detail:
  - [x] Identity verification process
  - [x] Response times (max 30 days)
  - [x] Contact methods

### 2.7 Dispute Resolution
- [x] Streamline arbitration and liability limitation clauses
- [x] Move details to appendices if necessary
- [x] Maintain synthetic reference in main document

---

## 🏪 3. Store Requirements

### 3.1 Apple App Store (Privacy + Subscription Compliance)
- [x] Provide a working link to:
  - [x] Privacy Policy
  - [x] Terms of Use (EULA)
- [x] Subscription information displayed:
  - [x] Name: Premium Access
  - [x] Price and duration: displayed within the app (e.g. monthly/yearly)
  - [x] Automatic renewal: valid unless cancelled at least 24 hours before the end of the period
- [x] Users can manage subscriptions in Settings > Apple ID > Subscriptions.
- [x] ATT was implemented before the tracking SDK was active.
- [x] Privacy Nutrition labels correspond to the data actually collected (device ID, crashes, analytics).

### 3.2 Google Play Store (Data Safety + Billing)
- [x] The Data Safety Form is completed as follows:
  - [x] Data type: Device ID, crash log, analytics, email (if login is used)
  - [x] Purpose: Analytics, performance improvement, account management
  - [x] Third-party SDKs: Firebase, RevenueCat
- [x] Privacy Policy link is available and consistent across all distribution channels
- [x] If using Google Play Billing:
  - [x] Automatic renewal and refund policy information is explained in the app

---

## 📱 4. Permission Declarations

### 4.1 iOS Info.plist Usage Descriptions
- [x] Declare permissions only if the feature is used:
  - [x] `NSCameraUsageDescription` – "to upload profile picture"
  - [x] `NSPhotoLibraryUsageDescription` - "to select a photo from the gallery"
  - [x] `NSMicrophoneUsageDescription` - "only if the app uses voice input"
  - [x] `NSUserTrackingUsageDescription` - "to request ATT tracking permission"
- [x] Not using `NSLocationWhenInUseUsageDescription` because there is no location feature
- [x] All reasons for use are clearly written in Info.plist

### 4.2 Android Permissions & Justifications
- [x] Use the permission_handler package for runtime permissions management.
- [x] Justification for its use is displayed via a dialog before the request:
  - [x] Camera: “To take a profile picture”
  - [x] Microphone: “To record audio (if enabled)”
  - [x] Storage: “To import or export files”
- [x] Does not ask for location, unless the feature is added in the future
- [x] Permissions are only requested when needed (runtime), and are optional if not a core part of the feature.

---

## 🌍 5. Localization

### 5.1 Multilingual Versions
- [x] Publish Privacy Policy and Terms in EN, IT, CN with separate files
- [x] Indicate links in app menu
- [x] Ensure legal compliance in all languages

### 5.2 Translation Best Practices
- [ ] Guarantee terminological consistency and legal compliance in all languages
- [ ] Use technical translators or professional services
- [ ] Review and validate translations with legal experts

---

## 📜 6. EULA (End User License Agreement)
- [ ] Create or adapt standard EULA for app covering:
  - [ ] Use license
  - [ ] IP ownership
  - [ ] Updates
  - [ ] Liability limitations

---

## 📁 7. App File Structure

### 7.1 Naming Convention
- [ ] Use names like privacy_en.html, terms_it.html, cookie_policy_cn.html
- [ ] Maintain consistent naming across all languages

### 7.2 Folders
- [ ] Organize in assets/legal/ or www/legal/ for WebView loading
- [ ] Implement caching hit management
- [ ] Ensure easy access and maintenance

---

## 🔧 8. Operational Steps

### 8.1 Repository Setup
- [x] Create podtxt-legal-docs repo with original branch (original files) and updated branch (updated files)
- [x] Set up proper versioning and tracking

### 8.2 Commit Flow
- [x] First commit: original versions (privacy-policy-original.md, terms-of-use-original.md)
- [x] Second commit: updated versions with all improvements listed above
- [x] Maintain clear commit history and documentation

---

## 📊 Progress Tracking

### Completed Tasks ✅
- [x] 1.1 Metadata and Versioning
- [x] 2.1 GDPR Legal Bases and Retention Periods
- [x] 2.2 CCPA / CalOPPA
- [x] 2.3 Cookie Policy & Tracking Technologies
- [x] 2.4 Third-Party Sharing
- [x] 2.5 Security Measures
- [x] 2.6 Data Subject Rights
- [x] 2.7 Dispute Resolution
- [x] 3.1 Apple App Store & Privacy Nutrition Labels
- [x] 3.2 Google Play Data Safety
- [x] 4.1 iOS Info.plist
- [x] 4.2 Android Runtime Permissions
- [x] 5.1 Multilingual Versions
- [x] 8.1 Repository Setup
- [x] 8.2 Commit Flow

### Pending Tasks ⏳
- [ ] 5.2 Translation Best Practices
- [ ] 2.7 Dispute Resolution
- [ ] 3.1 Apple App Store & Privacy Nutrition Labels
- [ ] 3.2 Google Play Data Safety
- [ ] 4.1 iOS Info.plist
- [ ] 4.2 Android Runtime Permissions
- [ ] 5.1 Multilingual Versions
- [ ] 5.2 Translation Best Practices
- [ ] 6. EULA
- [ ] 7.1 Naming Convention
- [ ] 7.2 Folders
\
---

## 🎯 Next Steps
1. **Complete Task 2.5** - Security Measures
2. **Complete Task 2.6** - Data Subject Rights
3. **Complete Task 2.7** - Dispute Resolution
4. **Move to Store Requirements** (Tasks 3.1-3.2)
5. **Implement Permission Declarations** (Tasks 4.1-4.2)
6. **Add Localization** (Tasks 5.1-5.2)
7. **Create EULA** (Task 6)
8. **Organize File Structure** (Tasks 7.1-7.2)

---

*Last updated: April 28, 2025*
*Status: 14/18 tasks completed (77.8%)* 