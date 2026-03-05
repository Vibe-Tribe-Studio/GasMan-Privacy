# GasMan Pro – Privacy Policy (UK)

Last updated: 5 March 2026

---

## 1. Introduction

GasMan Pro ("the App") is a professional productivity tool for gas engineers, developed by **Vibe Tribe Studio** ("we", "us", "our").

We take privacy seriously. GasMan Pro is designed to minimise data collection and operate **offline-first**, with all core data stored locally on your device. We do not operate servers, cloud databases, or user accounts for app data.

This Privacy Policy explains:
- what data is (and is not) collected
- how data is stored and used
- when data may leave your device
- your rights under UK data protection law

This Privacy Policy should be read alongside our Terms & Conditions.

---

## 2. Data Controller

### Your Customer Data

You are the **data controller** for all personal data you collect, enter, and store using the App (e.g. customer names, addresses, phone numbers, landlord details). We do not access, process, or store this data on any system we operate.

As data controller, you are responsible for:
- having a lawful basis for collecting and processing your customers' personal data
- complying with UK GDPR and the Data Protection Act 2018
- responding to data subject access requests from your customers
- ensuring the security of personal data on your device

### Our Role

**Vibe Tribe Studio** is the developer of the App. We are not a data processor for your customer data because we never access, receive, or process it. Our only role is providing the software tool.

For any questions about how the App itself works or about this Privacy Policy, contact:

**Vibe Tribe Studio**
Email: support@vibetribestudio.dev

---

## 3. Data We Do NOT Collect

GasMan Pro does **not**:
- require user accounts or registration with us
- collect analytics, telemetry, or usage tracking data
- transmit personal data or business data to our servers (we have none)
- access your contacts, location, or files outside the App
- include advertising, ad tracking, or third-party tracking SDKs
- include crash reporting SDKs
- fingerprint your device or browser
- use cookies (the App is not web-based)

We have **no servers, no databases, and no cloud infrastructure** for user data. We cannot see, access, or retrieve any data you enter into the App.

---

## 4. Data Stored Locally on Your Device

All app data is stored **locally on your device only** using Android's Room database (SQLite) and local file storage. This includes:

### Business Data (entered by you)
- Company details (name, address, phone, email, website)
- VAT registration number and VAT settings
- Bank account details (account name, sort code, account number) for invoice generation
- Gas Safety registration number and engineer details
- Company logo image
- Price lists and rate settings
- App preferences and settings

### Customer & Job Data (entered by you)
- Customer names, addresses, phone numbers, and email addresses
- Landlord and letting agent contact details
- Tenant details
- Appliance and boiler records (make, model, serial number, location)
- Service history, scheduled appointments, and due dates
- Gas safety certificates (CP12, CP15, CP16, CP42, CP44, CP2, and others)
- Warning notices (Immediately Dangerous, At Risk, Not to Current Standards)
- Installation and commissioning records
- Building regulations compliance records
- Invoices and quotes with line items and pricing
- Gas rate readings, measurements, and notes
- On-site observations and checklist records

### Photos & Images (captured by you)
- Gas Safety card photo
- Boiler and appliance photos
- Company logo
- All stored in the App's internal storage, not in shared device galleries

### App-Generated Data
- Service reminders and notification schedules
- Notification delivery logs
- Subscription status cache (stored in a separate local DataStore)
- Internal record identifiers
- Wizard completion and consent timestamps

### Generated Documents
- PDF certificates, invoices, quotes, and warning notices are saved to your device's shared Documents folder (`Documents/GasMan/`). These files are accessible to other apps and file managers on your device.

This data **never leaves your device** unless you explicitly share it (see Section 8).

---

## 5. Lawful Basis for Processing

### Data We Process

We process minimal data in connection with the App:
- **Subscription status** — processed by Google Play on the basis of **contract performance** (delivering the subscription you purchased)
- **Consent timestamps** — recorded locally when you accept the Terms & Conditions and Privacy Policy, on the basis of **legitimate interest** (demonstrating your acceptance)

### Data You Process

As the data controller for your customers' personal data, you must determine your own lawful basis for processing under UK GDPR. Common bases for gas engineers include:
- **Contract performance** — processing customer data to perform a service you have been engaged to provide
- **Legal obligation** — retaining gas safety certificates and warning notices as required by law
- **Legitimate interest** — maintaining service records and scheduling follow-up appointments

We do not advise on data protection compliance. If you are unsure about your obligations, seek independent legal advice.

---

## 6. Camera & Photos

The App uses the device camera to:
- capture photos of boilers and appliances for record-keeping
- photograph your Gas Safety card for reference
- scan barcodes and serial numbers on appliances

All images:
- are stored locally on your device in the App's internal storage
- are not uploaded, transmitted, or shared automatically
- remain fully under your control
- can be deleted at any time within the App

---

## 7. Permissions Used

GasMan Pro requests only the permissions necessary to function. All permissions are optional except Internet (required for subscription management).

### Camera (Optional)
- Used to photograph appliances, Gas Safety cards, and scan barcodes
- Images are stored locally and never uploaded
- Camera access can be denied without affecting core functionality

### Calendar — Read & Write (Optional)
- Used to create and manage service appointments via Android's Calendar Provider
- When enabled, appointment details including customer name, address, phone number, and boiler information are written to your device's calendar
- This data is then subject to your Google account's sync settings and Google's Privacy Policy
- The App does not access Google servers directly
- Calendar sync can be disabled at any time in Settings

### Notifications (Optional)
- Used to show service reminders and Gas Safety card expiry alerts
- Notifications are generated and delivered locally on the device
- **Note:** notification content (which may include customer names) may be visible on your device's lock screen depending on your device settings. You can control this in your device's notification settings.
- Notification permission can be denied without affecting core functionality

### Internet
- Used **solely** for subscription management via Google Play Billing
- The App does not use this permission for analytics, tracking, advertising, crash reporting, or any other purpose
- No customer or business data is transmitted over the internet by the App

### Other Permissions
- **Vibrate** — used for notification feedback
- **Boot Completed** — used to reschedule service reminders after device restart

---

## 8. Data Sharing & Third-Party Services

We do not share your data with third parties. We do not sell, rent, or trade any personal data.

Data only leaves your device in the following circumstances, all of which are **initiated by you**:

### Sharing Documents
- Emailing PDF certificates, invoices, quotes, or warning notices via your device's email app
- Sharing documents via Android's system share functionality (e.g. messaging apps, cloud storage)
- Printing via Android print services
- Documents may contain personal data (customer names, addresses, contact details). You are responsible for ensuring appropriate consent or lawful basis before sharing.

### Google Calendar Sync (Optional)
- When calendar sync is enabled, appointment details (customer name, address, phone, email, boiler information, appointment notes) are written to your selected device calendar via Android's Calendar Provider
- This data may be synced to Google's servers by your device's calendar sync settings, which is outside our control
- Google Calendar data is subject to [Google's Privacy Policy](https://policies.google.com/privacy)
- You are responsible for the security of your Google account

### Navigation
- When you choose to navigate to a customer address, the address is shared with your device's maps application

### Phone & Email
- When you choose to call or email a customer, the phone number or email address is passed to your device's phone or email app via standard Android intents
- Pre-filled email templates are editable before sending. You control the final content.

### Backups
- When you create a backup, the App generates an AES-256 encrypted, password-protected file containing your database and optionally your photos and company logo
- Backups are saved to a location you choose or shared via an app you select
- The backup file is encrypted; we cannot decrypt it and do not have access to it

### Diagnostic Data
- The database health check feature allows you to copy diagnostic logs to the clipboard for troubleshooting purposes. These logs contain table names and record counts only, not personal data.

### Google Play Billing
- Subscription purchases, renewals, and status checks are processed by Google Play
- Google may collect data about your purchase activity in accordance with [Google's Privacy Policy](https://policies.google.com/privacy)
- We receive only your subscription status (active, expired, or trial) and the associated product identifier. We do not receive your payment details, Google account information, or any other personal data from Google.

All data sharing uses standard Android system functionality. We never initiate data sharing without your explicit action.

---

## 9. International Data Transfers

We do not transfer your data internationally because we do not collect or store it.

However, when you use optional features that interact with Google services (Google Calendar sync, Google Play Billing), Google may process data on servers located outside the United Kingdom. This is governed by Google's own data transfer mechanisms and privacy policy, and is outside our control.

---

## 10. Data Retention

We do not define retention periods because all data is controlled by you on your device.

- Data remains on your device until you delete it within the App or uninstall the App
- Uninstalling the App will delete the App's internal storage (database, photos, settings). PDF documents saved to `Documents/GasMan/` may persist after uninstallation as they are in shared storage.
- The App does not auto-delete safety records (certificates, warning notices)

You are responsible for:
- creating regular backups using the App's backup feature
- retaining records for legally required periods (e.g. minimum 2 years for gas safety certificates, 6 years for warning notices)
- securely deleting data when no longer needed or when required by a data subject

---

## 11. Data Security

We take reasonable steps to ensure the App stores data securely on your device:
- Database and photos are stored in the App's private internal storage, inaccessible to other apps under normal Android security
- Backups are encrypted with AES-256 and protected by a password you set
- Generated PDF documents are saved to shared device storage (`Documents/GasMan/`) and are accessible to other apps and file managers

You are responsible for:
- securing your device with a screen lock (PIN, pattern, password, or biometrics)
- enabling device encryption (enabled by default on modern Android devices)
- preventing unauthorised physical access to your device
- keeping backup passwords secure and not sharing them
- managing who has access to your Google account (if calendar sync is enabled)

We are not responsible for unauthorised access to your data resulting from:
- device loss, theft, or compromise
- malware or malicious software on your device
- failure to secure your device
- sharing your device or backup passwords

---

## 12. Data Portability

The App provides several ways to export your data:
- **CSV export** of your customer list (available on both free and premium tiers)
- **PDF export** of certificates, invoices, quotes, and warning notices
- **Full encrypted backup** containing your complete database, photos, and settings (restore available on premium tier)

---

## 13. Your Rights (UK GDPR)

Under the UK General Data Protection Regulation and the Data Protection Act 2018, you have rights including:

- **Right of access** — you can view all data stored in the App at any time
- **Right to rectification** — you can edit any record within the App
- **Right to erasure** — you can delete any record within the App, or uninstall the App to remove all internal data
- **Right to data portability** — you can export your data via CSV, PDF, or encrypted backup (see Section 12)
- **Right to restrict processing** — as data is stored locally and we do not process it, this right is exercised by your own use of the App
- **Right to object** — you can stop using the App at any time

Because all data is stored locally on your device and we never access it, you can exercise all of these rights directly without contacting us.

### Right to Complain

If you believe your data protection rights have been infringed, you have the right to lodge a complaint with:

**Information Commissioner's Office (ICO)**
Website: [ico.org.uk](https://ico.org.uk)
Telephone: 0303 123 1113

---

## 14. Children's Privacy

GasMan Pro is a professional tool intended for use by qualified adults aged 18 or over.

We do not knowingly collect data from anyone under the age of 18. If you believe a minor is using the App, please contact us.

---

## 15. Changes to This Policy

We may update this Privacy Policy from time to time to reflect changes in the App's features or applicable law.

If changes are made:
- the updated policy will be available within the App and on our website
- the "last updated" date will be revised
- if changes are material, we will notify you through the App (e.g. by requiring re-acceptance in the startup wizard)

---

## 16. Contact Us

If you have questions about this Privacy Policy, your data, or our privacy practices, contact:

**Vibe Tribe Studio**
Email: support@vibetribestudio.dev

---

## 17. Acceptance

By using the App, you acknowledge that you have read and understood this Privacy Policy.
