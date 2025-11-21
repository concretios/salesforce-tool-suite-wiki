# End User License Agreement (EULA)

**Developer:** concret.io  
**Last Updated:** November 21, 2025

---

## KEY HIGHLIGHTS

**Free Software:** This is free software. No fees are charged for use.

**Authentication:** The Software uses (1) your current Salesforce browser session from cookies when launched from a Salesforce tab, and (2) standard OAuth flow for connecting additional organizations. All authentication happens directly between your browser and Salesforce.

**No External Servers:** This Software operates entirely on your local machine (laptop/desktop/workstation where the extension is installed). We do not operate any servers. All your Salesforce data is processed and stored exclusively on your device—never transmitted to our servers. When needed, your data is exchanged directly between your browser and Salesforce APIs over HTTPS. We never see, intercept, or have access to your data.

**Usage Analytics:** This Software uses Google Analytics to collect anonymous usage statistics (page navigation and file export events) to help improve the product. You can disable analytics collection at any time in Settings → Privacy. This analytics data does NOT include any of your Salesforce data, credentials, or personally identifiable information. All data is automatically sanitized to remove potential PII before transmission.

**Security Model:** Your data security depends on your local machine security. The only way your data could be compromised through this Software is if your local device is infected with viruses, malware, or otherwise hacked or compromised. We have no servers that could be breached.

**No Warranty:** This Software is provided "AS IS" without warranty. See full disclaimers below.

---

## IMPORTANT - READ CAREFULLY

This End User License Agreement ("EULA," "Agreement") is a legal agreement between you (either an individual or a single entity, "You," "Your," or "Licensee") and concret.io, the developer of Salesforce Tool Suite ("Licensor," "we," "us," or "our") for the Salesforce Tool Suite Chrome Extension software product ("Software," "Extension," or "Product").

**BY INSTALLING, COPYING, OR OTHERWISE USING THE SOFTWARE, YOU AGREE TO BE BOUND BY THE TERMS OF THIS EULA. IF YOU DO NOT AGREE TO THE TERMS OF THIS EULA, DO NOT INSTALL OR USE THE SOFTWARE.**

## 1. Grant of License

### 1.1 License Grant
Subject to the terms and conditions of this EULA, Licensor hereby grants You a limited, non-exclusive, non-transferable, non-sublicensable, revocable license to:

- Install and use the Software on devices under Your control
- Access and use the Software's features and functionality for Your personal or internal business purposes
- Use the Software to interact with Your authorized Salesforce organizations

### 1.2 License Type
This is a **FREE SOFTWARE LICENSE**. No fees are charged for the use of this Software.

### 1.3 License Restrictions
This license does NOT grant You the right to:

- Use the Software for commercial redistribution or resale
- Modify, adapt, translate, reverse engineer, decompile, or disassemble the Software
- Create derivative works based on the Software
- Remove, alter, or obscure any proprietary notices, labels, or marks on the Software
- Rent, lease, lend, sell, sublicense, or transfer the Software to third parties
- Use the Software in any manner that violates applicable laws or regulations
- Use the Software to develop competing products or services
- Extract or harvest data from Salesforce organizations without proper authorization
- Circumvent any technical limitations or security measures in the Software

## 2. Software Description and Features

### 2.1 Product Overview
Salesforce Tool Suite is a Chrome browser extension designed to enhance Salesforce productivity through the following modules:

**Reports Module:**
- Profile and permission set comparison across multiple Salesforce organizations
- Metadata export (classes, triggers, flows, validation rules, Visualforce pages, workflow rules)
- Super user security audit reports
- Approval process configuration export
- User app permissions and permission set assignment reports

**Debug Logs Module:**
- Hierarchical log viewer with organized navigation
- Real-time tail logs monitoring
- Trace flags and debug levels management
- User-specific debugging capabilities
- Multi-log Excel export

**Schema Explorer Module:**
- Interactive schema navigation with field and relationship browsing
- SOQL query builder with support for complex queries
- Batch and inline record editing capabilities
- Data filtering, sorting, and Excel export
- Multi-query saving and management

**Event Monitoring Module:**
- Comprehensive monitoring of 50+ Salesforce event types
- Event log download and analysis
- Access to exclusive API features

**Salesforce Tools Module:**
- Apex test suite execution with code coverage metrics
- Bulk operations for validation rules, workflow rules, fields, and objects
- Object limits monitoring
- Bulk cloning, creation, and deletion operations
- Report, dashboard, flow, and record type management

### 2.2 Technical Specifications
- **Platform**: Google Chrome Browser Extension (Manifest V3)
- **Version**: 2.10.9
- **Framework**: Angular 13.1.0
- **Required Permissions**: Downloads, Background, Notifications, Cookies, Tabs
- **Host Permissions**: *.force.com, *.lightning.force.com

## 3. System Requirements and Compatibility

### 3.1 Minimum Requirements
- Google Chrome browser (latest stable version recommended)
- Active internet connection
- Authorized access to at least one Salesforce organization
- Sufficient local storage space for cache and history data

### 3.2 Compatibility
- The Software is designed for use with Salesforce production and sandbox environments
- Compatibility with future Salesforce releases is not guaranteed
- The Software requires specific Salesforce API access and permissions

## 4. Installation and Activation

### 4.1 Installation Process
- The Software is distributed through the Chrome Web Store
- Installation requires acceptance of Chrome's extension permissions
- No additional registration or activation keys are required
- The Software may update automatically through the Chrome Web Store

### 4.2 Multi-User Installation
- Each user must install the Software individually on their browser
- Session tokens and authentication data are stored per browser profile
- Organization-specific settings are maintained locally per user

## 5. Data Privacy and Security

### 5.1 Data Processing - No External Servers
**CRITICAL**: This Software operates entirely on Your local machine. We do not operate any servers.

- **Local Processing Only**: All Salesforce data accessed through the Software is processed and stored exclusively on Your device
- **Direct HTTPS Communication**: All data processing happens locally on Your device. When needed, your data is exchanged directly between Your browser and Salesforce APIs over HTTPS encryption—we never see, intercept, or have access to this data
- **No Remote Storage**: We do not collect, store, or transmit Your Salesforce data to any external servers operated by us
- **No Data Transmission to Us**: No sensitive data leaves Your machine through this Software to any servers we control
- **Session Management**: Salesforce authentication tokens are stored securely in Your browser's local storage and never transmitted to our servers
- **Cache and History**: Query history, cached data, and user preferences are stored locally on Your device
- **Direct Authentication**: All authentication occurs directly between Your browser and Salesforce servers (we are not intermediaries)

### 5.2 Authentication Methods
The Software uses two authentication methods to access Salesforce:

**Session-Based Authentication:**
- When launched from a Salesforce tab, the Software uses Your current Salesforce browser session from cookies to call Salesforce APIs
- This leverages Your existing authenticated session without requiring additional login

**OAuth Flow:**
- For connecting additional Salesforce organizations, the Software initiates a standard OAuth authentication flow directly with Salesforce
- OAuth tokens are obtained directly from Salesforce and stored locally on Your device
- We do not intercept, store, or have access to Your Salesforce credentials

### 5.3 Usage Analytics
This Software uses Google Analytics 4 to collect anonymous usage data to help us understand how users interact with the Software and improve its features. The data collected includes:

**Data Collected:**
- Page navigation events (which features/pages you visit within the Software)
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
- **In-App Control (Recommended):** Navigate to Settings → Privacy within the Software and toggle "Share anonymous usage analytics" to OFF. When disabled, NO analytics data is sent to Google Analytics.
- **Browser Extensions:** You can also use browser extensions like Google Analytics Opt-out Add-on or similar privacy tools.

### 5.4 Data You Provide
You may provide the following data when using the Software (all stored locally on Your device):
- Salesforce login credentials (processed directly with Salesforce servers, not accessible to us)
- Organization nicknames and preferences
- Custom SOQL queries and saved searches
- Settings and configuration preferences

### 5.5 Data We Access
The Software accesses the following data from Your Salesforce organizations:
- Metadata (profiles, permission sets, objects, fields, classes, triggers, flows, etc.)
- Debug logs and trace flags
- Schema information
- Event monitoring logs
- User and permission data
- Apex test results

### 5.6 Data Security Model
**The security of Your data depends on Your local machine security:**

- **Local Machine Security**: The only way Your data accessed through this Software could be compromised is if Your local machine is infected with viruses, malware, or other security threats, or if Your device is hacked or otherwise compromised
- **Direct Salesforce Communication**: All data processing happens locally on Your device. When needed, your data is exchanged directly between Your browser and Salesforce APIs over HTTPS encryption. Since we operate no servers, we never see, intercept, or have access to Your data in transit or at rest
- **No Risk from Our Infrastructure**: There is no risk of compromise from our infrastructure because we have none—Your data never passes through any servers we control
- **Token Storage**: Authentication tokens are managed securely using Chrome's storage APIs with local-only storage
- **Your Responsibility**: You are responsible for:
  - Maintaining the security of Your device and browser
  - Using antivirus and anti-malware software
  - Keeping Your operating system and browser updated
  - Following security best practices for Your device
- **Browser Security**: We recommend enabling appropriate browser security features and using strong authentication for Your device

### 5.7 Data Retention
- Cached data is retained based on Your settings preferences
- History entries can be individually or bulk deleted at Your discretion
- Upon uninstallation, cached data may remain on Your device unless manually cleared
- We do not retain any of Your data on remote servers

## 6. Intellectual Property Rights

### 6.1 Ownership
The Software, including but not limited to its source code, object code, algorithms, design, structure, organization, user interface, documentation, and all intellectual property rights therein, is and shall remain the exclusive property of Licensor and its licensors.

### 6.2 Trademarks
"Salesforce Tool Suite" and associated logos and branding are trademarks of Licensor. "Salesforce" and related marks are trademarks of Salesforce, Inc. You may not use any trademarks without prior written permission.

### 6.3 Third-Party Components
The Software incorporates various open-source and third-party components, including but not limited to:
- Angular Framework (MIT License)
- Bootstrap (MIT License)
- Various npm packages

These components are subject to their respective licenses. A complete list of dependencies can be found in the Software's package.json file.

### 6.4 Feedback
If You provide suggestions, feedback, or ideas about the Software ("Feedback"), You grant Licensor a worldwide, perpetual, irrevocable, royalty-free license to use, modify, and incorporate such Feedback into the Software without any obligation to You.

## 7. User Obligations and Responsibilities

### 7.1 Authorized Use
You represent and warrant that:
- You have authorized access to all Salesforce organizations You connect through the Software
- You have appropriate permissions to view, export, and modify data as performed through the Software
- You will use the Software in compliance with Your organization's security policies
- You will not use the Software to access data You are not authorized to view

### 7.2 Compliance
You agree to:
- Comply with all applicable local, state, national, and international laws and regulations
- Comply with Salesforce's Terms of Service and Acceptable Use Policy
- Comply with data protection laws (GDPR, CCPA, etc.) when exporting or processing data
- Maintain appropriate safeguards for any exported data
- Not use the Software for any illegal or unauthorized purpose

### 7.3 Account Security
You are responsible for:
- Maintaining the confidentiality of Your Salesforce credentials and OAuth tokens
- All activities that occur through Your authenticated sessions (whether session-based or OAuth)
- Ensuring Your browser sessions are properly secured when using session-based authentication
- Immediately notifying Salesforce of any unauthorized use or security breach of Your Salesforce account
- Using strong passwords and enabling multi-factor authentication where available on Your Salesforce accounts
- Securing Your local machine to protect stored authentication tokens

### 7.4 Prohibited Activities
You shall NOT:
- Share Your Salesforce credentials or session tokens
- Use the Software to access unauthorized Salesforce organizations
- Export data in violation of contractual obligations or data protection laws
- Attempt to bypass or circumvent any security measures
- Use the Software to distribute malware or harmful code
- Interfere with or disrupt the integrity or performance of Salesforce services
- Use the Software in any manner that could damage or overburden Salesforce systems

## 8. Updates and Maintenance

### 8.1 Software Updates
- We may provide updates, patches, bug fixes, and new features from time to time
- Updates may be delivered automatically through the Chrome Web Store
- We are under no obligation to provide any updates or support
- Updates may modify, add, or remove features without prior notice
- Continued use of updated Software constitutes acceptance of such changes

### 8.2 Backward Compatibility
- We strive to maintain backward compatibility but do not guarantee it
- Major version updates may require changes to Your workflows or saved data
- Release notes are provided with significant updates

### 8.3 Deprecation
- We reserve the right to deprecate features with reasonable notice
- Deprecated features will be documented in release notes
- We may remove deprecated features in future versions

## 9. Support and Maintenance

### 9.1 No Guaranteed Support
This is free software provided "as is." We are under no obligation to provide:
- Technical support
- Bug fixes
- Feature enhancements
- Documentation
- Training

### 9.2 Community Support
- Support resources may be available through our Chrome Web Store listing
- We may provide optional support channels (email, feedback forms)
- Response times are not guaranteed
- Support is provided at our sole discretion

### 9.3 Bug Reporting
You may report bugs through:
- The Chrome Web Store support section
- Feedback forms within the Software
- Email to our support address (if provided)

We appreciate bug reports but are not obligated to address them.

## 10. Disclaimers and Warranties

### 10.1 NO WARRANTY
THE SOFTWARE IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, AND NON-INFRINGEMENT.

### 10.2 NO GUARANTEE OF FUNCTIONALITY
LICENSOR DOES NOT WARRANT THAT:
- The Software will meet Your specific requirements or expectations
- The Software will operate uninterrupted, timely, secure, or error-free
- The results obtained from using the Software will be accurate, reliable, or complete
- The quality of the Software will meet Your expectations
- Any errors, bugs, or defects in the Software will be corrected
- The Software will be compatible with future versions of Chrome or Salesforce
- Data exported or processed by the Software will be accurate or complete

### 10.3 THIRD-PARTY SERVICES
THE SOFTWARE RELIES ON THIRD-PARTY SERVICES (SALESFORCE, CHROME) WHICH ARE BEYOND OUR CONTROL. WE ARE NOT RESPONSIBLE FOR:
- Changes to Salesforce APIs or services that affect the Software
- Chrome browser updates that impact functionality
- Salesforce organization configurations that prevent proper operation
- Third-party service outages or performance issues

### 10.4 SECURITY DISCLAIMER
THE SOFTWARE PROCESSES DATA LOCALLY ON YOUR MACHINE AND DOES NOT TRANSMIT YOUR SALESFORCE DATA TO OUR SERVERS (WE OPERATE NONE). THE SECURITY OF YOUR DATA DEPENDS ON YOUR LOCAL MACHINE SECURITY. YOU USE THE SOFTWARE AT YOUR OWN RISK. WE ARE NOT RESPONSIBLE FOR:
- Security of Your local machine, including viruses, malware, hacking, or other compromises of Your device
- Unauthorized access to Your device or browser
- Security vulnerabilities in Chrome or Salesforce services
- Data breaches resulting from Your security practices or compromised device
- Compromise of Your Salesforce credentials or OAuth tokens stored locally
- Any security issues arising from Your local machine being compromised by third-party threats

SINCE WE DO NOT OPERATE SERVERS AND YOUR DATA REMAINS ON YOUR LOCAL MACHINE, THE PRIMARY SECURITY CONSIDERATIONS ARE YOUR LOCAL DEVICE SECURITY AND YOUR DIRECT AUTHENTICATION WITH SALESFORCE.

## 11. Limitation of Liability

### 11.1 MAXIMUM LIABILITY
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL LICENSOR, ITS AFFILIATES, OFFICERS, DIRECTORS, EMPLOYEES, AGENTS, OR SUPPLIERS BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, EXEMPLARY, OR PUNITIVE DAMAGES, INCLUDING BUT NOT LIMITED TO:

- Loss of profits, revenue, or business opportunities
- Loss of data or information
- Business interruption or downtime
- Loss of goodwill or reputation
- Cost of substitute goods or services
- Failure to realize expected savings
- Any other commercial damages or losses

ARISING OUT OF OR IN CONNECTION WITH THE SOFTWARE, WHETHER BASED ON WARRANTY, CONTRACT, TORT (INCLUDING NEGLIGENCE), STRICT LIABILITY, OR ANY OTHER LEGAL THEORY, EVEN IF LICENSOR HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

### 11.2 CAP ON LIABILITY
LICENSOR'S TOTAL CUMULATIVE LIABILITY TO YOU FOR ALL CLAIMS ARISING OUT OF OR RELATED TO THIS EULA OR THE SOFTWARE SHALL NOT EXCEED THE GREATER OF (A) THE AMOUNT YOU PAID FOR THE SOFTWARE IN THE TWELVE (12) MONTHS PRECEDING THE CLAIM, OR (B) ONE HUNDRED DOLLARS ($100.00 USD).

### 11.3 ESSENTIAL PURPOSE
YOU ACKNOWLEDGE THAT THE DISCLAIMERS AND LIMITATIONS OF LIABILITY IN THIS EULA REFLECT A REASONABLE AND FAIR ALLOCATION OF RISK BETWEEN YOU AND LICENSOR, AND THAT THESE LIMITATIONS ARE AN ESSENTIAL BASIS OF LICENSOR'S DECISION TO OFFER THE SOFTWARE AT NO CHARGE.

### 11.4 JURISDICTIONAL LIMITATIONS
SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THE ABOVE LIMITATIONS MAY NOT APPLY TO YOU. IN SUCH JURISDICTIONS, LICENSOR'S LIABILITY SHALL BE LIMITED TO THE GREATEST EXTENT PERMITTED BY LAW.

## 12. Indemnification

You agree to indemnify, defend, and hold harmless Licensor, its affiliates, and their respective officers, directors, employees, agents, licensors, and suppliers from and against any and all claims, liabilities, damages, losses, costs, expenses, or fees (including reasonable attorneys' fees and court costs) arising from or related to:

- Your use or misuse of the Software
- Your violation of this EULA
- Your violation of any applicable laws or regulations
- Your violation of Salesforce's Terms of Service
- Your violation of any third-party rights, including intellectual property rights or privacy rights
- Your unauthorized access to or use of Salesforce organizations
- Any data breach or security incident resulting from Your actions
- Your negligence or willful misconduct

This indemnification obligation shall survive termination of this EULA.

## 13. Term and Termination

### 13.1 Term
This EULA is effective from the date You first install or use the Software and continues until terminated.

### 13.2 Termination by You
You may terminate this EULA at any time by:
- Uninstalling the Software from Your Chrome browser
- Ceasing all use of the Software
- Deleting all locally stored data (optional)

### 13.3 Termination by Licensor
Licensor may terminate this EULA immediately, with or without notice, if:
- You breach any term of this EULA
- You engage in prohibited activities
- Required by law or legal process
- We discontinue offering the Software
- At our sole discretion for any reason or no reason

### 13.4 Effect of Termination
Upon termination of this EULA:
- Your license to use the Software immediately terminates
- You must immediately cease all use of the Software
- You must uninstall the Software from all devices
- Locally stored data may remain on Your device unless manually deleted
- Sections of this EULA that by their nature should survive termination shall continue in effect

### 13.5 Survival
The following sections shall survive termination: Intellectual Property Rights, User Obligations, Disclaimers and Warranties, Limitation of Liability, Indemnification, and General Provisions.

## 14. Export Compliance

### 14.1 Export Control Laws
The Software may be subject to export control laws and regulations of various countries, including but not limited to the United States Export Administration Regulations (EAR). You agree to comply with all applicable export and import control laws and regulations.

### 14.2 Prohibited Jurisdictions
You represent and warrant that:
- You are not located in, under the control of, or a national or resident of any country to which the United States or other applicable jurisdiction has embargoed goods
- You are not listed on any government list of prohibited or restricted parties
- You will not use the Software in violation of any export laws or regulations

## 15. Governing Law and Dispute Resolution

### 15.1 Governing Law
This EULA shall be governed by and construed in accordance with the laws of India, without regard to its conflict of law provisions. Any disputes arising from this EULA shall be subject to the exclusive jurisdiction of the courts located in Jaipur, Rajasthan, India. The United Nations Convention on Contracts for the International Sale of Goods shall not apply.

### 15.2 Informal Resolution
Before initiating any formal dispute resolution, You agree to attempt to resolve any dispute informally by contacting us. We will attempt to resolve the dispute informally within sixty (60) days of receiving notice.

### 15.3 Binding Arbitration
If informal resolution fails, any dispute, controversy, or claim arising out of or relating to this EULA, or the breach, termination, or invalidity thereof, shall be resolved by binding arbitration in accordance with the Arbitration and Conciliation Act, 1996 of India.

The arbitration shall be conducted by a single arbitrator, and the arbitrator's decision shall be final and binding. The seat and venue of arbitration shall be as specified in Section 15.1 (Governing Law) above.

### 15.4 Class Action Waiver
YOU AND LICENSOR AGREE THAT EACH PARTY MAY BRING CLAIMS AGAINST THE OTHER ONLY IN AN INDIVIDUAL CAPACITY AND NOT AS A PLAINTIFF OR CLASS MEMBER IN ANY PURPORTED CLASS, COLLECTIVE, REPRESENTATIVE, MULTIPLE PLAINTIFF, OR SIMILAR PROCEEDING.

### 15.5 Injunctive Relief
Notwithstanding the arbitration provision, either party may seek injunctive or other equitable relief in any court of competent jurisdiction to prevent the actual or threatened infringement, misappropriation, or violation of intellectual property rights.

### 15.6 Jurisdiction
If arbitration is not enforceable, You consent to the exclusive jurisdiction as specified in Section 15.1 (Governing Law) above for any disputes arising out of this EULA.

## 16. General Provisions

### 16.1 Entire Agreement
This EULA, together with our Terms of Service and Privacy Policy, constitutes the entire agreement between You and Licensor regarding the Software and supersedes all prior or contemporaneous understandings, agreements, representations, and warranties, whether written or oral.

### 16.2 Amendments
We reserve the right to modify this EULA at any time. We will provide notice of material changes through:
- The Chrome Web Store listing
- In-app notifications
- Email (if contact information is available)

Your continued use of the Software after changes become effective constitutes Your acceptance of the modified EULA. If You do not agree to the modified EULA, You must stop using the Software.

### 16.3 Severability
If any provision of this EULA is held to be invalid, illegal, or unenforceable by a court of competent jurisdiction, such provision shall be modified to the minimum extent necessary to make it valid and enforceable, or if such modification is not possible, such provision shall be severed from this EULA. The remaining provisions shall continue in full force and effect.

### 16.4 No Waiver
No waiver of any term or condition of this EULA shall be deemed a further or continuing waiver of such term or any other term. Our failure to assert any right or provision under this EULA shall not constitute a waiver of such right or provision.

### 16.5 Assignment
You may not assign, transfer, or delegate this EULA or Your rights hereunder, in whole or in part, without our prior written consent. Any attempted assignment in violation of this provision shall be null and void. We may assign, transfer, or delegate this EULA and our rights and obligations without restriction.

### 16.6 Force Majeure
Licensor shall not be liable for any failure or delay in performance due to causes beyond its reasonable control, including but not limited to acts of God, war, terrorism, riots, embargoes, acts of civil or military authorities, fire, floods, accidents, pandemics, strikes, or shortages of transportation, facilities, fuel, energy, labor, or materials.

### 16.7 Independent Contractors
You and Licensor are independent contractors. This EULA does not create a partnership, franchise, joint venture, agency, fiduciary, or employment relationship between the parties.

### 16.8 No Third-Party Beneficiaries
This EULA is for the sole benefit of You and Licensor and does not create any third-party beneficiary rights.

### 16.9 Notices
Notices to Licensor should be sent to the contact information provided in the Chrome Web Store listing or within the Software. Notices to You may be sent to any email address You have provided or displayed within the Software.

### 16.10 Language
This EULA is executed in English. Any translation is provided for convenience only. In the event of any conflict between the English version and any translation, the English version shall prevail.

### 16.11 Government Use
If You are a government entity or the Software is being acquired by or on behalf of any government entity, the Software is "commercial computer software" and "commercial computer software documentation" as defined in FAR 12.212 and DFARS 227.7202, and Your rights are limited to those expressly granted in this EULA.

## 17. Special Provisions for Different User Types

### 17.1 Individual Users
If You are using the Software as an individual:
- This EULA is between You personally and Licensor
- You represent that You have authority to access the Salesforce organizations You connect
- You are personally liable for any violations of this EULA

### 17.2 Corporate/Enterprise Users
If You are using the Software on behalf of an organization:
- You represent that You have authority to bind that organization to this EULA
- "You" refers to both You individually and the organization
- The organization is responsible for ensuring compliance with this EULA by all its users
- The organization is responsible for maintaining appropriate data security and privacy controls

### 17.3 Consultants and Service Providers
If You are a consultant or service provider using the Software to access client Salesforce organizations:
- You represent that You have proper authorization from clients
- You are responsible for compliance with client contracts and agreements
- You must maintain appropriate professional standards and confidentiality

## 18. Acknowledgments and Representations

BY INSTALLING AND USING THE SOFTWARE, YOU ACKNOWLEDGE AND REPRESENT THAT:

- You have read, understood, and agree to be bound by this EULA
- You have the legal capacity and authority to enter into this EULA
- You have authorized access to any Salesforce organizations You will access through the Software
- You understand that this is free software provided without warranty
- You accept all risks associated with using the Software
- You will use the Software in compliance with all applicable laws and regulations
- **You understand the authentication methods**: The Software uses (1) your browser's Salesforce session from cookies when launched from a Salesforce tab, and (2) OAuth flow for additional organizations
- **You understand the local-only processing model**: All data is processed and stored exclusively on your local device; we operate no servers
- **You understand the security model**: Your data security depends on your local machine security; the only compromise risk is from your device being infected with malware, viruses, or otherwise compromised
- You understand that Your Salesforce data never leaves Your machine to any servers we control
- You understand that we do not have access to Your Salesforce data, credentials, or OAuth tokens
- **You understand the analytics opt-out control:** You can disable anonymous usage analytics at any time in Settings → Privacy, and the Software continues to work normally
- **You understand data sanitization:** All analytics data is automatically sanitized to remove potential PII before transmission to Google Analytics
- You have reviewed the Software's required permissions and accept them
- You are responsible for securing Your local machine and maintaining device security
- You are responsible for maintaining backups of any critical data
- You will not hold Licensor liable for any damages or losses, including those from Your local machine being compromised

## 19. Contact Information

For questions about this EULA, please contact us at:

**Salesforce Tool Suite by concret.io**  
Website: https://concret.io  
Chrome Web Store: https://chromewebstore.google.com/detail/salesforce-tool-suite/fiaakhiohminpblhmlihfcdhclmphjcd  
Support: Available through Chrome Web Store support section and in-app feedback forms

For bug reports, feature requests, and general support, please use the feedback mechanisms provided within the Software or on the Chrome Web Store listing.

---

**Software Name**: Salesforce Tool Suite  
**Version**: 2.10.9  
**EULA Version**: 1.2  
**Effective Date**: November 21, 2025  
**Last Updated**: November 21, 2025

---

## ACCEPTANCE

BY CLICKING "I AGREE," INSTALLING, COPYING, OR OTHERWISE USING THE SOFTWARE, YOU ACKNOWLEDGE THAT YOU HAVE READ THIS EULA, UNDERSTAND IT, AND AGREE TO BE BOUND BY ITS TERMS AND CONDITIONS. IF YOU DO NOT AGREE TO THE TERMS OF THIS EULA, DO NOT INSTALL OR USE THE SOFTWARE AND DELETE ALL COPIES IN YOUR POSSESSION.
