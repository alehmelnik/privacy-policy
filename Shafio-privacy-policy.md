Privacy Policy – Shafio
Last updated: May 13, 2026

Shafio ("we", "our", "the app") is a pantry management app that helps you track food items, scan barcodes, and get recipe suggestions. This policy explains what data we collect, why, and how it is handled.

1. No Personal Identification
We do not collect your name, email address, phone number, or any other personally identifying information. The app creates an anonymous, randomly generated user ID on first launch. This ID is stored only on your device and on our server solely to sync your pantry data between app sessions.

2. Device Authentication
We use a cryptographic key pair (Ed25519) generated on your device to authenticate requests to our server. The private key never leaves your device. We store only the corresponding public key and a device ID on our server for the purpose of verifying your identity and preventing unauthorized access.

3. Camera
The app requests camera access to:

Scan product barcodes to identify items quickly.
Capture photos of products for AI-assisted recognition of product name and details.
Photos are sent to our server only to perform recognition and are not stored permanently. We do not use images for any other purpose.

4. Pantry Data
Your pantry items (product names, quantities, expiry dates, categories) are stored locally on your device using an encrypted local database and are synced to our server to persist your data across reinstalls and devices. This data is associated only with your anonymous user ID.

5. Notifications
If you grant notification permission, the app sends local on-device notifications to remind you of approaching expiry dates. These notifications are generated entirely on your device; no notification content is transmitted to our servers or any third party.

6. Data Sharing
We do not sell, rent, or share your data with advertisers, data brokers, or any third parties. Data is transmitted only between your device and our own backend server.

7. Third-Party Services
The app does not integrate any third-party analytics, advertising, crash-reporting, or social login SDKs. No data is sent to Google, Apple, Meta, or similar platforms by the app itself.

8. Data Retention and Deletion
Your data is retained for as long as you use the app. You can delete your account and all associated server-side data at any time from Settings → Delete Account. After deletion, your anonymous user ID, device record, and synced pantry data are permanently removed from our server within 24 hours. Local data on your device is removed when you uninstall the app.

9. Security
All communication between the app and our server uses HTTPS/TLS. Authentication is performed via cryptographic signatures; we never transmit passwords. Local data is stored in an encrypted SQLite database.

10. Children
The app is not directed at children under 13 (or the applicable age in your jurisdiction). We do not knowingly collect data from children.

11. Changes to This Policy
If we make material changes to this policy, we will update the "Last updated" date above and notify you via an in-app message on your next launch.
