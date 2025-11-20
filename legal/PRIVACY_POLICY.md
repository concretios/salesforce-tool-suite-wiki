# Privacy Policy

**Developer:** concret.io  
**Extension:** Salesforce Tool Suite  
**Last Updated:** November 20, 2025  
**Effective Date:** November 20, 2025

---

## KEY HIGHLIGHTS

**No Backend Servers:** We do not operate any servers. Your Salesforce data stays on your device and is never transmitted to us.

**Local Processing:** All Salesforce data processing happens entirely on your local machine (laptop/desktop/workstation).

**Usage Analytics:** We collect anonymous usage statistics via Google Analytics (page views and file exports) to improve the Extension. No Salesforce data or personal information is included.

**Direct Salesforce Communication:** All Salesforce data exchanges happen directly between your browser and Salesforce servers over HTTPS. We never see, intercept, or have access to your Salesforce data.

**Your Control:** You maintain complete control over your data. Uninstalling the Extension removes our access, though locally cached data may remain on your device.

---

## 1. Introduction

This Privacy Policy explains how Salesforce Tool Suite ("Extension," "we," "us," or "our"), developed by concret.io, collects, uses, and protects information when you use our Chrome browser extension.

**By installing and using the Extension, you agree to the collection and use of information in accordance with this Privacy Policy.**

This Privacy Policy should be read in conjunction with our [Terms of Service](TERMS_OF_SERVICE.md) and [End User License Agreement (EULA)](EULA.md).

---

## 2. Information We Collect

### 2.1 Information We DO NOT Collect

**We do NOT collect, store, or have access to:**
- Your Salesforce data, records, or metadata
- Your Salesforce credentials, passwords, or authentication tokens
- Personally identifiable information (PII)
- Your name, email address, or contact information
- Organization names, user names, or account identifiers
- IP addresses or precise geolocation data
- Content of files you export or download
- Browser history or activity outside the Extension
- Any data stored in your Salesforce organizations

### 2.2 Usage Analytics Data (Google Analytics)

**We collect anonymous usage statistics via Google Analytics 4 to improve the Extension:**

**Data Collected:**
- **Page Navigation Events:** Which features/modules you use within the Extension (e.g., "Debug Logs," "Schema Explorer," "Reports")
- **File Export Events:** When you export data, including:
  - File type (e.g., "xlsx", "csv")
  - Sanitized filename patterns (e.g., "Debug Logs.xlsx")
  - Page/module where export occurred
- **Session Data:**
  - Timestamp of usage
  - Duration of sessions
  - Engagement time within the Extension
- **Technical Data:**
  - Browser type and version
  - Extension version
  - Generic device type (desktop/laptop)

**Data Sanitization & Privacy Protections:**
- **Automatic PII Scrubbing:** All data is sanitized before transmission:
  - Email addresses are replaced with `[redacted]`
  - Salesforce IDs (15/18 characters) are masked as `[sfid]`
  - Special characters and potential identifiers are removed
  - URL query parameters and fragments are stripped
- **No Salesforce Data:** No actual Salesforce records, field values, or metadata from exports is collected
- **No Organization Info:** No organization names, user names, or account identifiers
- **Anonymized:** Analytics data is anonymized and aggregated
- **Generic Client ID:** Client ID used for analytics is not linked to your personal identity

**Third-Party Service:**
This analytics data is transmitted to and processed by Google Analytics. Google's use of this data is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

**Purpose:**
We use this data to:
- Understand which features are most valuable to users
- Identify areas for improvement
- Track adoption of new features
- Diagnose technical issues
- Make data-driven product decisions

### 2.3 Local Data Storage (On Your Device Only)

**The following data is stored exclusively on your local device:**

**Salesforce Data (Cached Locally):**
- Metadata from your Salesforce organizations (profiles, permission sets, objects, fields, classes, triggers, flows, validation rules, etc.)
- Debug logs and trace flags
- Schema information and object relationships
- Event monitoring logs
- Query results from SOQL queries
- Saved queries and search history

**Configuration Data:**
- Salesforce session tokens and OAuth tokens (stored in Chrome's encrypted storage)
- Organization nicknames and preferences
- Extension settings and user preferences
- Custom configurations for features
- History of queries and operations

**Important:** This data is stored using Chrome's local storage APIs and never leaves your device to reach our servers (we don't have any).

---

## 3. How We Use Information

### 3.1 Usage Analytics
- **Product Improvement:** Understand feature usage patterns and prioritize development
- **Performance Monitoring:** Identify and resolve bugs or performance issues
- **Feature Adoption:** Measure success of new features
- **User Experience:** Optimize navigation and workflows based on actual usage

### 3.2 Local Data (Never Transmitted to Us)
Your Salesforce data and cached information is used solely to:
- Provide the core functionality of the Extension
- Enable offline access to recently viewed data
- Improve performance by reducing repeated API calls to Salesforce
- Maintain your preferences and settings across sessions

**We never access, view, or transmit this locally stored data to our servers.**

---

## 4. Data Sharing and Third Parties

### 4.1 No Data Sales
**We do NOT sell your data to anyone.** We do not operate a business model based on data monetization.

### 4.2 Third-Party Services

**Google Analytics:**
- Anonymous usage statistics are shared with Google Analytics for analytics processing
- Governed by [Google's Privacy Policy](https://policies.google.com/privacy)
- Google may use this data in accordance with their privacy practices

**Salesforce:**
- All Salesforce data exchanges happen directly between your browser and Salesforce servers
- We are not an intermediary in these communications
- Salesforce's handling of your data is governed by [Salesforce's Privacy Policy](https://www.salesforce.com/company/privacy/)

### 4.3 No Other Third Parties
We do not share, sell, rent, or trade your information with any other third parties for their commercial purposes.

### 4.4 Legal Requirements
We may disclose information if required by law, such as to comply with a subpoena, court order, or legal process. However, given that we don't collect or store your Salesforce data, there is minimal information we could provide even if compelled.

---

## 5. Data Security

### 5.1 Our Security Model

**No External Servers = No Server-Side Breaches**
- We do not operate any backend servers or databases
- Your Salesforce data cannot be breached from our infrastructure (we have none)
- There is no centralized data repository that could be hacked

### 5.2 Your Responsibility

**The security of your data depends on:**

**Local Machine Security:**
- Keep your device free from viruses, malware, and security threats
- Use antivirus and anti-malware software
- Keep your operating system and browser updated
- Follow security best practices for your device

**Browser Security:**
- Use the latest stable version of Chrome
- Enable browser security features
- Be cautious with other browser extensions
- Log out of sensitive sessions when done

**Salesforce Authentication:**
- Use strong, unique passwords for Salesforce
- Enable multi-factor authentication (MFA)
- Don't share your Salesforce credentials
- Review and revoke OAuth tokens periodically
- Be cautious when connecting to multiple organizations

### 5.3 Chrome Storage Security
- Authentication tokens are stored using Chrome's encrypted storage APIs
- Storage is sandboxed per Chrome profile
- Data is isolated from other extensions and websites
- Tokens are never transmitted to external servers we control

### 5.4 HTTPS Encryption
- All communication between your browser and Salesforce uses HTTPS encryption
- Google Analytics requests are also transmitted over HTTPS
- No sensitive data is transmitted over unencrypted connections

---

## 6. Data Retention

### 6.1 Analytics Data (Google Analytics)
- Google Analytics retains data according to their retention policies
- Default retention is 14 months from the last user interaction
- Data is automatically deleted after the retention period
- We do not have direct control over Google's retention policies

### 6.2 Local Data (On Your Device)
- Cached Salesforce data is retained based on your settings preferences
- You can configure auto-delete timers in Extension settings
- History entries can be deleted individually or in bulk
- Upon uninstallation, most data is removed, but some may persist in Chrome's storage

**To completely remove all data:**
1. Uninstall the Extension from Chrome
2. Clear your browser cache and site data
3. Optionally, manually remove Chrome extension data from your local storage

---

## 7. Your Rights and Choices

### 7.1 Opt-Out of Analytics

**Extension-Level Opt-Out (Recommended):**
- Navigate to Settings → Privacy tab within the Extension
- Toggle "Share anonymous usage analytics" to OFF
- When disabled, NO analytics data is sent to Google Analytics
- The Extension continues to work normally with analytics disabled

**Browser-Level Opt-Out:**
- Install [Google Analytics Opt-out Browser Add-on](https://tools.google.com/dlpage/gaoptout)
- Use privacy-focused browser extensions that block analytics
- Enable "Do Not Track" in your browser settings (limited effectiveness)

### 7.2 Access and Control of Local Data

**View Your Data:**
- All cached data can be viewed within the Extension interface
- Settings page shows saved queries, history, and cached records

**Delete Your Data:**
- Use the Extension's clear cache and history features
- Uninstall the Extension to remove most local data
- Use Chrome's built-in extension data clearing tools

**Export Your Data:**
- Any data displayed in the Extension can be exported to Excel/CSV
- This data comes from Salesforce and is yours to keep

### 7.3 European Union (GDPR) Rights

If you are located in the European Economic Area (EEA), you have certain data protection rights:

- **Right to Access:** Request information about data we process about you
- **Right to Rectification:** Correct inaccurate data
- **Right to Erasure:** Request deletion of your data
- **Right to Restrict Processing:** Limit how we use your data
- **Right to Data Portability:** Receive your data in a portable format
- **Right to Object:** Object to processing of your data
- **Right to Withdraw Consent:** Withdraw consent at any time

**Important Note:** Because we do not collect or store your Salesforce data on our servers, most GDPR requests are not applicable. However, for analytics data, you may contact us at the email provided in Section 13.

### 7.4 California Privacy Rights (CCPA)

If you are a California resident, you have the following rights:

- **Right to Know:** What personal information is collected, used, shared, or sold
- **Right to Delete:** Request deletion of your personal information
- **Right to Opt-Out:** Opt-out of the sale of personal information (we don't sell data)
- **Right to Non-Discrimination:** Not be discriminated against for exercising privacy rights

**Sale of Personal Information:** We do NOT sell your personal information.

---

## 8. Chrome Permissions Explained

The Extension requires the following Chrome permissions to function:

### 8.1 Required Permissions

| Permission | Purpose | Data Access |
|------------|---------|-------------|
| **Downloads** | Export reports and data to Excel/CSV files | Can initiate downloads to your local machine |
| **Background** | Run background processes for monitoring and notifications | No additional data access |
| **Notifications** | Alert you about debug logs and monitoring events | No additional data access |
| **Cookies** | Access Salesforce session cookies for authentication | Read Salesforce authentication cookies only |
| **Tabs** | Interact with Salesforce tabs in your browser | Detect when you're on a Salesforce tab |
| **Storage** | Store settings, cache, and preferences locally | Local storage only (no server sync) |

### 8.2 Host Permissions

**Domains Accessed:**
- `*.force.com` - Salesforce production and sandbox instances
- `*.lightning.force.com` - Salesforce Lightning Experience
- `*.my.salesforce.com` - Salesforce Classic and MyDomain instances
- `*.visual.force.com` - Visualforce pages

**Purpose:** These permissions allow the Extension to interact with Salesforce pages and make API calls on your behalf using your authenticated session.

**Data Access:** The Extension can read and modify data on Salesforce domains to provide its functionality (e.g., query data, export metadata, manage debug logs). All this data remains local to your device.

---

## 9. Children's Privacy

The Extension is not intended for use by individuals under the age of 18. We do not knowingly collect personal information from children under 18. If you become aware that a child has provided us with personal information, please contact us, and we will take steps to delete such information.

**Age Requirement:** By using the Extension, you represent that you are at least 18 years of age or have reached the age of majority in your jurisdiction.

---

## 10. International Data Transfers

### 10.1 No Direct International Transfers by Us
Because we do not operate servers or collect your Salesforce data, we do not engage in international data transfers of your Salesforce information.

### 10.2 Google Analytics
Usage analytics data may be transmitted to and processed by Google Analytics servers, which may be located in the United States or other countries. Google's international data transfer practices are governed by their privacy policy and data processing agreements.

### 10.3 Salesforce
Your Salesforce data remains within Salesforce's infrastructure. Any international transfers are governed by your agreement with Salesforce and their data processing practices.

---

## 11. Changes to This Privacy Policy

### 11.1 Updates
We reserve the right to update or modify this Privacy Policy at any time. When we make material changes, we will:
- Update the "Last Updated" date at the top of this Privacy Policy
- Notify users through the Extension interface or Chrome Web Store listing
- Request acceptance of the updated Privacy Policy if required by law

### 11.2 Your Continued Use
Your continued use of the Extension after any changes to this Privacy Policy constitutes your acceptance of the revised Privacy Policy.

### 11.3 Review
We encourage you to periodically review this Privacy Policy to stay informed about how we are protecting your privacy.

---

## 12. Third-Party Links and Services

The Extension may contain links to third-party websites, services, or resources (e.g., documentation, support forums, Salesforce help). This Privacy Policy applies only to our Extension. We are not responsible for the privacy practices of third-party websites or services. We encourage you to read the privacy policies of any third-party services you access.

**Third-Party Services Referenced:**
- Google Analytics: [Privacy Policy](https://policies.google.com/privacy)
- Salesforce: [Privacy Policy](https://www.salesforce.com/company/privacy/)
- Chrome Web Store: [Privacy Policy](https://myaccount.google.com/privacypolicy)

---

## 13. Contact Information

If you have questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Salesforce Tool Suite by concret.io**

**Developer:** Concretio Apps / concret.io  
**Website:** [https://concret.io](https://concret.io)  
**Email:** schema-browser@concret.io  
**Chrome Web Store:** [Salesforce Tool Suite](https://chromewebstore.google.com/detail/salesforce-tool-suite/fiaakhiohminpblhmlihfcdhclmphjcd)  
**Support:** Available through Chrome Web Store support section and in-app feedback forms

**Address:**  
Concretio Apps  
2nd Floor, M, F-28, Malviya Nagar Industrial Area  
Jaipur, Rajasthan, India

---

## 14. Compliance and Certifications

### 14.1 Industry Standards
We strive to follow industry best practices for privacy and security, including:
- Chrome Web Store Developer Program Policies
- Google's Limited Use Policy for Chrome Extensions
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) requirements

### 14.2 Salesforce Partnership
Concretio Apps is a Salesforce Crest (Gold) Partner. We are committed to maintaining the trust placed in us by Salesforce and our users.

### 14.3 No Server Compliance
Because we do not operate servers or collect Salesforce data, many traditional compliance frameworks (SOC 2, ISO 27001, etc.) related to data storage and transmission are not applicable to our architecture.

---

## 15. Data Processing Addendum (DPA)

For enterprise customers requiring a Data Processing Addendum under GDPR or other data protection regulations:

**Standard Position:** Because we do not process your Salesforce data on our servers (we have none), we are generally not considered a "data processor" under GDPR. Your data processing relationship is directly with Salesforce.

**Analytics Data:** For Google Analytics data, Google acts as the data processor. Refer to [Google's Data Processing Terms](https://business.safety.google/adsprocessorterms/).

**Custom DPA:** If your organization requires a custom DPA, please contact us at schema-browser@concret.io to discuss your specific requirements.

---

## 16. Transparency Report

### 16.1 Government Requests
**To Date:** We have received zero (0) government requests for user data.

**Future Requests:** In the event we receive a government request for user information, we will:
- Carefully review the request for legal validity
- Publish information about the request in future transparency reports (if permitted by law)

**Limited Data Available:** Even if compelled by law, the only data we could potentially provide is aggregate analytics data, as we do not collect or store individual Salesforce data.

---

## 17. Accountability

### 17.1 Our Commitment
We are committed to:
- **Transparency:** Clearly communicate our data practices
- **Minimization:** Collect only data necessary for product improvement
- **Security:** Implement appropriate safeguards for any data we handle
- **User Control:** Provide users with control over their data
- **Compliance:** Adhere to applicable privacy laws and regulations

### 17.2 Privacy by Design
Our architecture is designed with privacy as a core principle:
- **No unnecessary data collection:** We don't collect data we don't need
- **Local processing:** Salesforce data never leaves your device to reach our servers
- **Minimal analytics:** Only anonymous usage statistics, no personal data
- **No tracking across sites:** We don't track your browsing outside the Extension

---

## 18. Acknowledgment

**BY INSTALLING AND USING THE EXTENSION, YOU ACKNOWLEDGE THAT YOU HAVE READ, UNDERSTOOD, AND AGREE TO BE BOUND BY THIS PRIVACY POLICY.**

If you do not agree with this Privacy Policy, please do not install or use the Extension.

---

**Privacy Policy Version:** 1.1.0  
**Effective Date:** November 20, 2025  
**Last Updated:** November 20, 2025

---

*This Privacy Policy is part of a comprehensive legal framework that includes our [Terms of Service](TERMS_OF_SERVICE.md) and [End User License Agreement (EULA)](EULA.md). Please review all documents to fully understand your rights and obligations.*
