#Release Notes

- Version: v4.0.0
  - Feature: Added tab-based navigation to the Global Search menu for faster switching between result types.
  - Update: Enhanced the UI/UX for the Tools and Reports modules (layout and styling improvements).
  - Update: Enhanced org authentication: Users can now login or refresh inactive org sessions directly within any component without navigating to the Settings page.
  - Bug Fix: Fixed blurred and frozen UI issue during login authentication in the Tools and Reports modules.
  
- Version: v3.2.0
  - Bug Fix: Fixed hard-coded encryption key/IV vulnerability.
  - Update: Enhanced security by replacing the hard-coded encryption key with a random per-installation master key.
  - Bug Fix: Fixed XSS vulnerability in object report export.
  - Bug Fix: Fixed storage async calls.
  - Update: Enhanced the security for external URLs.
  - Update: Enhanced the UI/UX.

- Version: v3.1.2
  - Bug Fix: Fixed issue with Profile Creation & Modified Details and Visualforce Page Details while exporting metadata.
  - Bug Fix: Fixed a refresh issue that occurred when navigating between routes.
  - Bug Fix: Resolved an issue where buttons were not visible when filtering data using the search bar.
  - Update: Updated button hover colors to align with the theme.
  - Bug Fix: Fixed sandbox refresh issue.
  - Feature: Replaced localStorage with Chrome storage and encrypted sensitive data.
  - Feature: Added EULA, Privacy Policy, and TOS to website and Chrome Store listing.
  - Feature: Implemented opt-in flow for Google Analytics.
  - Update: Reviewed and updated analytics events to remove PII or identifiers.

- Version: v3.1.1
  - Bug Fix: Fixed sandbox authorization issue.
  - Bug Fix: Fixed sandbox refresh issue.

- Version: v3.1.0
  - Update: Enhanced the UI for better usability and performance.
  - Bug Fix: Fixed the validations for all objects & fields in Bulk Field Creation.
  - Bug Fix: Fixed issue where Add Field button disappeared after deleting a field during editing.
  - Bug Fix: Fixed the authorization issue for new orgs.

- Version: v2.10.8
  - Feature: Built a feature for org limits and added more types of metadata comparison.

- Version: v2.10.8
  - Bug Fix: Resolved an issue preventing workflow downloads during metadata export.

- Version: v2.10.7
  - Feature: Implemented delimiter option in Schema Explorer for CSV export.
  - Update: Introduced an enhanced light mode with a balanced theme.
  - Update: Added subroutes for each sub-feature, accessible via the left navbar.
  - Update: Integrated YouTube links for each feature in the Reports and Tools sections.
  - Update: Reorganized elements on the Settings page for improved usability.
  - Bug Fix: Fixed an issue preventing the extension from opening in sandbox environments.

- Version: v2.10.6
  - Feature: Added feedback form and subscription hyperlink.
  - Update: Shortened the extension name to "Salesforce Tool Suite."
  - Update: Added YouTube link to the footer for all extension videos.
  - Update: Updated the company logo.
  - Update: Provided guidance on enabling event monitoring settings.
  - Update: Displayed an illustration when no records are found.

- Version: v2.10.5
  - Feature: Generate metadata differences between Salesforce orgs for permission sets, objects, and Apex classes.
  - Feature: Export field-level differences between orgs to Excel.
  - Feature: Assign nicknames to orgs for easy reference.
  - Update: Assign profiles and permission sets to fields during bulk field creation.
  - Bug Fix: Performance optimizations and general bug fixes.

- Version: v2.10.4
  - Feature: Export user app permissions report to Excel.
  - Feature: Save multiple queries in Schema Explorer for future use.
  - Feature: Switch orgs within the extension.
  - Feature: Share org sessions with other users.
  - Update: Export more than 2,000 records in Schema Explorer.
  - Bug Fix: General performance improvements and bug fixes.

- Version: v2.10.3
  - Feature: Generate reports of users with app access.
  - Feature: Generate reports of users assigned to permission sets.
  - Bug Fix: Fixed sandbox login issue in settings.
  - Bug Fix: Corrected user ID bug in metadata reports.
  - Update: Added settings tab for quick navigation.

- Version: v2.10.2
  - Update: Added multi-org support for cloning flows, global picklists, and validation rules.
  - Bug Fix: General performance optimizations and bug fixes.

- Version: v2.10.1
  - Update: Enhanced login and token refresh functionality in profile and permission set comparisons, super user reports, and approval process reports.
  - Bug Fix: General performance improvements and bug fixes.

- Version: v2.10.0
  - Update: Compare profiles and permission sets across multiple orgs in a single instance.
  - Update: Compare super users across multiple orgs in a single instance.
  - Update: Compare approval processes across multiple orgs in a single instance.
  - Update: Login with multiple orgs and refresh tokens from settings.
  - Bug Fix: General performance optimizations and bug fixes.
  - Feature: Bulk toggle record types (beta).

- Version: v2.9.4
  - Update: Added support for aggregate queries in Schema Explorer.
  - Update: Included support for Fields(ALL), Fields(Standard), and Fields(Custom) functions in Schema Explorer.
  - Bug Fix: Resolved parsing issues in Schema Explorer.
  - Bug Fix: General performance improvements and minor bug fixes.

- Version: v2.9.3
  - Update: Download multiple debug logs into a single Excel file.
  - Update: Added object information in process builders and flows metadata reports.
  - Bug Fix: Fixed Excel export issue in Schema Explorer.
  - Bug Fix: General performance optimizations and minor bug fixes.

- Version: v2.9.2
  - Feature: Bulk toggle and delete flows.
  - Feature: Bulk clone flows.
  - Update: Enhanced user experience for toggling and deleting validation and workflow rules.
  - Bug Fix: General performance improvements and bug fixes.

- Version: v2.9.0
  - Feature: Bulk clone and delete reports.
  - Feature: Apex test execution with code coverage results (beta).
  - Bug Fix: General bug fixes.

- Version: v2.8.3 (Released: Nov 4, 2022)
  - Feature: Bulk clone global picklists.
  - Feature: Monitor object limits in your org.
  - Bug Fix: Fixed column header issue in Schema Explorer.
  - Bug Fix: Resolved issues in bulk object creation and editing.
  - Update: Improved user experience for bulk object and field creation.

- Version: v2.8.2 (Released: September 2, 2022)
  - Features: Bulk creation and deletion of objects. Bulk deletion of fields.
  - Bug Fixes: Resolved case sensitivity issues in field queries. Fixed updates for validation rules on custom metadata types. Corrected graph display for login event types.
  - Updates: Enhanced user interface for bulk field creation. Optimized API calls in bulk field creation and workflow rules, reducing the number of requests.

- Version: v2.8.0 (Released: June 10, 2022)
  - UI/UX Improvements: Expanded toolbar options. Reduced API call volume by 80% for super user and metadata reports. Implemented a reactive pattern-based IndexedDB wrapper for stable history and cache transactions.
  - New Features: User settings and preferences. Selection of preferred API version. Option to enable or disable notifications. Toolbar functionality to clear all notifications. Breadcrumb navigation toggle. Cache and history settings with auto-delete and time limits. Global control for background processes, allowing individual or bulk stoppage. Bug reporting and feedback submission links. Global and temporary caching for frequently accessed API requests. Preservation of login tokens for multi-user access within a single extension instance. Distinct history and cache management for multiple orgs and users. New reports module with a searchable menu. Addition of eight metadata export reports. Capability to export multiple reports simultaneously. Global toolbar access for cache clearing. Fullscreen navigation via the toolbar's "Go-to" feature. Throttled export clicks to prevent duplicate exports from accidental clicks. Sequential file naming for all Excel exports.
  - Bug Fixes: Addressed repeated export issues.

- Version: v2.7.0 (Released: May 9, 2022)
  - Updates: Improved themes with balanced grayscale for dark mode. Enhanced stability, performance, and browser compatibility using the latest Angular framework. Multithreaded processing for better performance…
