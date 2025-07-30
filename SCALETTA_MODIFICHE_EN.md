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
- [ ] Summarize organizational and technical measures:
  - [ ] Encryption in transit and at rest
  - [ ] Backup and disaster recovery
  - [ ] Access controls and authentication
  - [ ] Security audits and monitoring
- [ ] Include security disclaimer ("we don't guarantee 100% protection")

### 2.6 Data Subject Rights
- [ ] Expand GDPR rights exercise methods:
  - [ ] Right of access
  - [ ] Right of rectification
  - [ ] Right of erasure (right to be forgotten)
  - [ ] Right to data portability
  - [ ] Right to restriction of processing
  - [ ] Right to object
- [ ] Detail:
  - [ ] Identity verification process
  - [ ] Response times (max 30 days)
  - [ ] Contact methods

### 2.7 Dispute Resolution
- [ ] Streamline arbitration and liability limitation clauses
- [ ] Move details to appendices if necessary
- [ ] Maintain synthetic reference in main document

---

## 🏪 3. Store Requirements

### 3.1 Apple App Store & Privacy Nutrition Labels
- [ ] Integrate summary compliant with Apple Privacy Nutrition Labels:
  - [ ] "Data Used to Track You"
  - [ ] "Data Linked to You"
  - [ ] "Data Not Linked to You"
- [ ] Ensure App Store Connect declarations exactly match policies
- [ ] Update labels with each new app version

### 3.2 Google Play Data Safety
- [ ] Prepare Data Safety section in Play Console:
  - [ ] Types of data collected
  - [ ] Collection purposes
  - [ ] Third-party sharing
  - [ ] Data security
- [ ] Attach Privacy Policy link in every update

---

## 📱 4. Permission Declarations

### 4.1 iOS Info.plist
- [ ] Add fields with clear contextual explanations:
  - [ ] `NSCameraUsageDescription` - "Camera access for taking photos"
  - [ ] `NSLocationWhenInUseUsageDescription` - "Location access for local services"
  - [ ] `NSMicrophoneUsageDescription` - "Microphone access for audio recordings"
  - [ ] `NSPhotoLibraryUsageDescription` - "Photo library access for selecting images"

### 4.2 Android Runtime Permissions
- [ ] Provide permission rationale messages justifying use of:
  - [ ] Camera
  - [ ] Location
  - [ ] Microphone
  - [ ] Storage
- [ ] Document permissions in manifest and explain in-app why they're requested

---

## 🌍 5. Localization

### 5.1 Multilingual Versions
- [ ] Publish Privacy Policy and Terms in EN, IT, CN with separate files
- [ ] Indicate links in app menu
- [ ] Ensure legal compliance in all languages

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
- [x] 8.1 Repository Setup
- [x] 8.2 Commit Flow

### Pending Tasks ⏳
- [ ] 2.5 Security Measures
- [ ] 2.6 Data Subject Rights
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
*Status: 6/18 tasks completed (33.3%)* 