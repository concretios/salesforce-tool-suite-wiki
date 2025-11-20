# Terms of Service

**Developer:** concret.io  
**Last Updated:** November 20, 2025

---

## KEY HIGHLIGHTS

**Authentication:** This Extension uses 

(1) your current Salesforce browser session from cookies when launched from a Salesforce tab, and 

(2) standard OAuth flow for connecting additional organizations.

**Data Privacy:** This Extension operates entirely on your local machine (laptop/desktop/workstation where the extension is installed). We do not operate any servers. All your Salesforce data is processed and stored locally on your device—never transmitted to our servers. When needed, your data is exchanged directly between your browser and Salesforce APIs over HTTPS. We never see, intercept, or have access to your data.

**Usage Analytics:** This Extension uses Google Analytics to collect anonymous usage statistics (page navigation and file export events) to help improve the product. You can disable analytics collection at any time in Settings → Privacy. This analytics data does NOT include any of your Salesforce data, credentials, or personally identifiable information. All data is automatically sanitized to remove potential PII before transmission.

**Security:** Your data security depends on your local machine security. Since we have no servers and your data never leaves your machine through this Extension, the only security risks are from your local device being compromised (viruses, malware, hacking, etc.).

---

## 1. Acceptance of Terms

By installing, accessing, or using the Salesforce Tool Suite Chrome Extension ("Extension," "Service," "we," "us," or "our"), developed by concret.io, you ("User," "you," or "your") agree to be bound by these Terms of Service ("Terms"). If you do not agree to these Terms, do not install or use the Extension.

## 2. Description of Service

Salesforce Tool Suite is a free Chrome browser extension designed to enhance productivity for Salesforce administrators, developers, architects, and consultants. The Extension provides the following key features:

- **Reports Module**: Profile and permission set comparison, metadata export, super user reports, and approval process details
- **Debug Logs Management**: Hierarchical log viewer, tail logs monitoring, trace flags and debug levels management
- **Schema Explorer**: Schema navigation, SOQL query builder, data management, and Excel export capabilities
- **Event Monitoring**: Comprehensive event log monitoring for Salesforce events
- **Salesforce Tools**: Apex testing, bulk management operations, object limits monitoring, and bulk operations for fields, objects, reports, and dashboards

## 3. User Eligibility

By using this Extension, you represent and warrant that:

- You are at least 18 years of age or have reached the age of majority in your jurisdiction
- You have the legal capacity to enter into binding contracts
- You have authorized access to the Salesforce organizations you connect through this Extension
- You will use the Extension in compliance with all applicable laws and regulations

## 4. User Accounts and Security

### 4.1 Salesforce Authentication
The Extension uses two authentication methods:
- **Session-Based Authentication**: When launched from a Salesforce tab, the Extension uses your current Salesforce browser session from cookies to call Salesforce APIs
- **OAuth Flow**: For connecting additional Salesforce organizations, the Extension initiates a standard OAuth authentication flow directly with Salesforce

You are solely responsible for:
- Maintaining the confidentiality of your Salesforce credentials
- All activities that occur through your authenticated sessions
- Ensuring proper authorization before connecting to any Salesforce organization
- Notifying Salesforce immediately of any unauthorized use of your Salesforce account

### 4.2 Multi-Organization Access
- The Extension supports multi-organization access through OAuth authentication
- You must have proper authorization to access each Salesforce organization you connect
- Session tokens are stored locally on your device and are never transmitted to any servers operated by us

## 5. Acceptable Use Policy

You agree NOT to:

- Use the Extension for any unlawful purpose or in violation of these Terms
- Access Salesforce data without proper authorization
- Reverse engineer, decompile, disassemble, or attempt to derive the source code of the Extension
- Remove, alter, or obscure any proprietary notices on the Extension
- Use the Extension to transmit any viruses, malware, or other harmful code
- Attempt to gain unauthorized access to any systems, networks, or data
- Use the Extension in any manner that could damage, disable, overburden, or impair our services
- Violate Salesforce's Terms of Service or Acceptable Use Policy
- Export or re-export data in violation of applicable data protection laws
- Share your Salesforce credentials or session tokens with unauthorized parties

## 6. Data Privacy and Storage

### 6.1 No External Servers - Local Processing Only
**IMPORTANT**: This Extension operates entirely on your local machine. We do not operate any servers.

- **All data accessed through the Extension is processed and stored exclusively on your device**
- **Direct HTTPS Communication**: All data processing happens locally on your device. When needed, your data is exchanged directly between your browser and Salesforce APIs over HTTPS encryption—we never see, intercept, or have access to this data
- **We do not collect, store, or transmit your Salesforce data to any external servers operated by us**
- **No sensitive data leaves your machine through this Extension to any servers we control**
- Cache and history data are maintained locally per your settings preferences
- Authentication is handled directly between your browser and Salesforce servers (we are not intermediaries)

### 6.2 Security Model
The security of your data when using this Extension depends on:
- **The security of your local machine**: If your device is compromised by viruses, malware, or other security threats, your data accessed through the Extension could be at risk
- **Your browser security**: Maintain up-to-date browser versions and security settings
- **Your device security**: Use antivirus software, firewalls, and follow security best practices
- **Direct Salesforce Communication**: All data processing happens locally on your device. When needed, your data is exchanged directly between your browser and Salesforce APIs over HTTPS encryption. Since we operate no servers, we never see, intercept, or have access to your data in transit or at rest

From this Extension's perspective, your data remains local and secure. The only potential compromise vectors are threats to your local machine itself, not from our Extension transmitting data externally to our servers (we have none).

### 6.3 Usage Analytics
This Extension uses Google Analytics 4 to collect anonymous usage data to help us understand how users interact with the Extension and improve its features. The data collected includes:

**Data Collected:**
- Page navigation events (which features/pages you visit within the Extension)
- File export events (when you export data, including the file type and sanitized filename patterns)
- Timestamp and duration of usage sessions

**Data Sanitization & Privacy Protections:**
- **Automatic PII Scrubbing:** All data is sanitized before transmission to remove potential personally identifiable information:
  - Email addresses are replaced with `[redacted]`
  - Salesforce IDs (15/18 characters) are masked as `[sfid]`
  - Special characters and potential identifiers are removed
  - URL query parameters and fragments are stripped
- **No Salesforce Data:** Your Salesforce data, records, or metadata are never collected
- **No Credentials:** Salesforce credentials, tokens, or authentication information are never collected
- **No Organization Info:** Organization names, user names, or account details are not collected
- **No File Content:** Actual content of exported files is never transmitted

**Third-Party Service:**
Analytics data is transmitted to Google Analytics servers. This service is governed by Google's Privacy Policy. You can learn more at https://policies.google.com/privacy

**Opt-Out Options:**
- **In-App Control (Recommended):** Navigate to Settings → Privacy within the Extension and toggle "Share anonymous usage analytics" to OFF. When disabled, NO analytics data is sent to Google Analytics.
- **Browser Extensions:** You can also use browser extensions like Google Analytics Opt-out Add-on or similar privacy tools.

### 6.4 Permissions
The Extension requires the following Chrome permissions:
- **Downloads**: To export reports and data to Excel files
- **Background**: To run background processes for monitoring and notifications
- **Notifications**: To alert you about debug logs and monitoring events
- **Cookies**: To manage Salesforce authentication tokens
- **Tabs**: To interact with Salesforce tabs in your browser

### 6.5 Host Permissions
The Extension accesses the following Salesforce domains:
- `*.force.com`
- `*.lightning.force.com`

For complete information about data collection and privacy practices, please refer to our Privacy Policy.

## 7. Intellectual Property Rights

### 7.1 Ownership
The Extension, including all content, features, functionality, source code, and design, is owned by us and is protected by international copyright, trademark, patent, trade secret, and other intellectual property laws.

### 7.2 License Grant
Subject to your compliance with these Terms, we grant you a limited, non-exclusive, non-transferable, non-sublicensable, revocable license to install and use the Extension for your personal or internal business purposes.

### 7.3 Restrictions
You may not:
- Copy, modify, or create derivative works of the Extension
- Sell, rent, lease, sublicense, or distribute the Extension
- Use the Extension to develop competing products or services

## 8. Third-Party Services

### 8.1 Salesforce Integration
This Extension integrates with Salesforce services. Your use of Salesforce is governed by Salesforce's Terms of Service and Privacy Policy. We are not responsible for Salesforce's services or any changes they make that may affect the Extension's functionality.

### 8.2 Third-Party Libraries
The Extension uses various open-source libraries and components. These components are subject to their respective licenses.

## 9. Updates and Modifications

### 9.1 Extension Updates
- We may release updates, bug fixes, and new features from time to time
- Updates may be installed automatically through the Chrome Web Store
- Continued use of the Extension after updates constitutes acceptance of changes

### 9.2 Terms Updates
- We reserve the right to modify these Terms at any time
- Material changes will be notified through the Extension or via the Chrome Web Store listing
- Your continued use after such modifications constitutes acceptance of the updated Terms

## 10. Disclaimers and Limitations of Liability

### 10.1 Service "AS IS"
THE EXTENSION IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.

### 10.2 No Warranty
WE DO NOT WARRANT THAT:
- The Extension will meet your specific requirements
- The Extension will be uninterrupted, timely, secure, or error-free
- The results obtained from using the Extension will be accurate or reliable
- Any errors in the Extension will be corrected

### 10.3 Limitation of Liability
TO THE MAXIMUM EXTENT PERMITTED BY LAW, IN NO EVENT SHALL WE BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, INCLUDING BUT NOT LIMITED TO LOSS OF PROFITS, DATA, USE, GOODWILL, OR OTHER INTANGIBLE LOSSES, RESULTING FROM:
- Your use or inability to use the Extension
- Any unauthorized access to or alteration of your data
- Any conduct or content of any third party on the Extension
- Any interruption or cessation of the Extension
- Any bugs, viruses, or similar harmful components
- Any errors or omissions in any content or data

### 10.4 Maximum Liability
OUR TOTAL LIABILITY TO YOU FOR ALL CLAIMS ARISING FROM OR RELATED TO THE EXTENSION SHALL NOT EXCEED THE AMOUNT YOU PAID TO USE THE EXTENSION IN THE TWELVE (12) MONTHS PRECEDING THE CLAIM, OR ONE HUNDRED DOLLARS ($100.00), WHICHEVER IS GREATER.

## 11. Indemnification

You agree to indemnify, defend, and hold harmless us, our affiliates, officers, directors, employees, agents, and licensors from and against any and all claims, liabilities, damages, losses, costs, expenses, or fees (including reasonable attorneys' fees) arising from:

- Your use or misuse of the Extension
- Your violation of these Terms
- Your violation of any rights of another party
- Your violation of any applicable laws or regulations
- Your unauthorized access to Salesforce organizations

## 12. Termination

### 12.1 Termination by You
You may terminate your use of the Extension at any time by uninstalling it from your Chrome browser.

### 12.2 Changes, Suspension, and Discontinuation by Us
We may modify, suspend, or discontinue the Extension (in whole or in part) at any time, including by removing it from the Chrome Web Store, limiting availability in certain regions, or issuing an update that disables or restricts certain features. These actions may be taken with or without notice, for reasons including:
- Violation of these Terms
- Suspicious, abusive, or fraudulent activity related to the Extension
- Technical, security, legal, or business reasons

### 12.3 Effect of Termination
Upon termination:
- Your license to use the Extension will immediately cease
- You must uninstall the Extension from all devices
- Locally stored data may be retained on your device unless manually deleted
- Provisions that by their nature should survive termination shall survive

## 13. Dispute Resolution

### 13.1 Informal Resolution
Before filing a claim, you agree to attempt to resolve any dispute informally by contacting us first. We will attempt to resolve the dispute informally within 60 days.

### 13.2 Binding Arbitration
If we cannot resolve the dispute informally, any dispute arising out of or relating to these Terms or the Extension shall be resolved through binding arbitration in accordance with the Arbitration and Conciliation Act, 1996 of India. The seat and venue of arbitration shall be as specified in Section 14.1 (Governing Law) below.

### 13.3 Class Action Waiver
YOU AND WE AGREE THAT EACH PARTY MAY BRING CLAIMS AGAINST THE OTHER ONLY IN AN INDIVIDUAL CAPACITY AND NOT AS A PLAINTIFF OR CLASS MEMBER IN ANY PURPORTED CLASS OR REPRESENTATIVE PROCEEDING.

## 14. General Provisions

### 14.1 Governing Law
These Terms shall be governed by and construed in accordance with the laws of India, without regard to its conflict of law provisions. Any disputes arising from these Terms shall be subject to the exclusive jurisdiction of the courts located in Jaipur, Rajasthan, India.

### 14.2 Severability
If any provision of these Terms is found to be unenforceable or invalid, that provision shall be limited or eliminated to the minimum extent necessary so that these Terms shall otherwise remain in full force and effect.

### 14.3 Entire Agreement
These Terms, together with our Privacy Policy and EULA, constitute the entire agreement between you and us regarding the Extension and supersede all prior agreements and understandings.

### 14.4 No Waiver
Our failure to enforce any right or provision of these Terms will not be deemed a waiver of such right or provision.

### 14.5 Assignment
You may not assign or transfer these Terms or your rights hereunder without our prior written consent. We may assign these Terms without restriction.

### 14.6 Force Majeure
We shall not be liable for any failure or delay in performance due to circumstances beyond our reasonable control, including acts of God, war, terrorism, riots, natural disasters, or governmental actions.

### 14.7 Export Compliance
You agree to comply with all applicable export and import control laws and regulations in your use of the Extension.

## 15. Contact Information

For questions, concerns, or notices regarding these Terms, please contact us at:

**Salesforce Tool Suite by concret.io**  
Website: https://concret.io  
Chrome Web Store: https://chromewebstore.google.com/detail/salesforce-tool-suite/fiaakhiohminpblhmlihfcdhclmphjcd  
Support: Available through Chrome Web Store support section and in-app feedback forms

## 16. Acknowledgment

BY INSTALLING AND USING THE EXTENSION, YOU ACKNOWLEDGE THAT YOU HAVE READ, UNDERSTOOD, AND AGREE TO BE BOUND BY THESE TERMS OF SERVICE.

---

**Version**: 2.10.9  
**Terms of Service Version**: 1.1  
**Effective Date**: November 20, 2025  
**Last Updated**: November 20, 2025
