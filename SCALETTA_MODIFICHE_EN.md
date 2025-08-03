# 📋 LEGAL DOCUMENTS UPDATE ROADMAP
*Comprehensive checklist for updating and aligning Privacy Policy and Terms of Use to GDPR, CCPA/CalOPPA, App Store Connect and Google Play Data Safety requirements, runtime permissions management, localization, cookie policy and EULA standard implementation*

---

## 📅 1. Metadata and Versioning

### 1.1 "Last updated" and Changelog
- [x] Insert "Last updated: January 15, 2025" at the top of Privacy Policy and Terms of Use
- [x] Add a brief changelog (date + summary of changes) at the beginning of each document to track evolutions and revisions
- [x] Create HTML template with complete Privacy Policy content

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

### 2.4 Third-Party Sharing
- [x] List service providers and third-party categories:
  - [x] Payment processors (Stripe, PayPal, Apple Pay, Google Pay)
  - [x] Analytics services (Google Analytics, Firebase)
  - [x] Cloud storage (AWS, Google Cloud)
  - [x] Customer support tools (Zendesk, Intercom)
  - [x] Marketing platforms (Mailchimp, SendGrid)
  - [x] App store platforms (Apple App Store, Google Play)
- [x] Describe:
  - [x] Security measures adopted
  - [x] Data processing agreements with sub-processors
  - [x] International data transfers

### 2.5 Security Measures
- [x] Summarize organizational and technical measures:
  - [x] Encryption in transit and at rest
  - [x] Backup and disaster recovery
  - [x] Access controls and authentication
  - [x] Security audits and monitoring
- [x] Include security disclaimer ("we don't guarantee 100% protection")

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

### 3.1 Apple App Store & Privacy Nutrition Labels
- [x] Integrate summary compliant with Apple Privacy Nutrition Labels:
  - [x] "Data Used to Track You"
  - [x] "Data Linked to You"
  - [x] "Data Not Linked to You"
- [x] Ensure App Store Connect declarations exactly match policies
- [x] Update labels with each new app version

### 3.2 Google Play Data Safety
- [x] Prepare Data Safety section in Play Console:
  - [x] Types of data collected
  - [x] Collection purposes
  - [x] Third-party sharing
  - [x] Data security
- [x] Attach Privacy Policy link in every update

---

## 📱 4. Permission Declarations

### 4.1 iOS Info.plist
- [x] Add fields with clear contextual explanations:
  - [x] `NSCameraUsageDescription` - "Camera access for taking photos"
  - [x] `NSLocationWhenInUseUsageDescription` - "Location access for local services"
  - [x] `NSMicrophoneUsageDescription` - "Microphone access for audio recordings"
  - [x] `NSPhotoLibraryUsageDescription` - "Photo library access for selecting images"

### 4.2 Android Runtime Permissions
- [x] Provide permission rationale messages justifying use of:

  - [x] Camera
  - [x] Location
  - [x] Microphone
  - [x] Storage
- [x] Document permissions in manifest and explain in-app why they're requested

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
- [ ] 6. EULA
- [ ] 7.1 Naming Convention
- [ ] 7.2 Folders

---

## 🎯 Next Steps
1. **Complete Translation Best Practices** (Task 5.2)
2. **Create EULA** (Task 6)
3. **Organize File Structure** (Tasks 7.1-7.2)
4. **Deploy HTML templates** for all languages

---

*Last updated: January 15, 2025*
*Status: 15/18 tasks completed (83.3%)*
*HTML Privacy Policy Template: ✅ COMPLETED* 