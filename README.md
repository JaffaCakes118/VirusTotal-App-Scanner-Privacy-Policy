# Privacy Policy for VirusTotal App Scanner

**Last updated: April 16, 2026**

JaffaCakes118 ("we", "us", or "our") operates the VirusTotal App Scanner mobile application (the "Service").

This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our Service and the choices you have associated with that data.

## 1. Information Collection and Use

We collect several different types of information for various purposes to provide and improve our Service to you.

### Types of Data Collected

#### Package Information
To provide the core functionality of scanning your device for potential threats, the Service accesses the list of installed applications on your device. Specifically:
* We collect the **Package Names** and **APK Hashes** (SHA-256) of your installed apps.
* **If an app's hash is not recognized by VirusTotal, the Service will upload the complete application file (APK) from your device to VirusTotal for a full security analysis.**
* This information and the files are sent directly to **VirusTotal** (a third-party service) to retrieve security analysis reports.

#### API Keys
To use the Service, you are required to provide your own **VirusTotal API Key**.
* This key is stored locally on your device using encrypted storage.
* It is only used to authenticate your requests directly to the VirusTotal API.

#### Firebase Data
We use Google Firebase to enhance the Service:
* **Firebase Authentication:** We use anonymous authentication to securely interact with backend services. No personal identity (like email or name) is required or collected for this.
* **Firebase Analytics:** We collect anonymous usage data to understand how the app is used.
* **Firebase Crashlytics:** We collect anonymous crash reports to help us fix bugs and improve stability.

## 2. Permissions

The Service requires the following permissions to function:
* **INTERNET:** Required to communicate with VirusTotal and Firebase services.
* **QUERY_ALL_PACKAGES:** Required to list the applications installed on your device so they can be selected for scanning.

## 3. Third-Party Services

We use third-party Service Providers to facilitate our Service:

* **VirusTotal:** For app security analysis. By using this app, you agree to the [VirusTotal Terms of Service](https://www.virustotal.com/en/about/terms-of-service/) and [Privacy Policy](https://www.virustotal.com/en/about/privacy/).
* **Google Firebase:** For analytics, crash reporting, and backend security. You can find their Privacy Policy here: [Google Privacy & Terms](https://policies.google.com/privacy).

## 4. Data Storage

* **Local Storage:** We use a local database (Room) and Preferences (DataStore) to cache scan results and store your settings (like Dark Mode and API Key) locally on your device.
* **No Developer Servers:** We do not operate our own servers. Your data is sent directly from your device to VirusTotal or Google Firebase.

## 5. Security of Data

The security of your data is important to us, but remember that no method of transmission over the Internet, or method of electronic storage is 100% secure. While we strive to use commercially acceptable means to protect your personal data, we cannot guarantee its absolute security.

## 6. Children's Privacy

Our Service does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from anyone under the age of 13.

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.

You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted on this page.

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact us:
* contactjaffacakes118@protonmail.com
