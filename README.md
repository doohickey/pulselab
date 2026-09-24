PulseLab — Privacy Policy

Last updated: September 24, 2026

Moaloop ("we", "us", or "our") built PulseLab as a research-prototype mobile application. This Privacy Policy explains what information the app collects, how it is used, and the choices you have.

1. Information We Collect

1.1 Health & Measurement Data
• Camera-derived readings: heart rate (BPM), signal quality, and estimated blood pressure generated from the rear camera and flash.
• Cuff readings: systolic and diastolic blood pressure values you enter manually from an upper-arm cuff monitor.
• Measurement sessions: date, duration, quality score, and blood-pressure estimates for each capture.

1.2 Health Profile (Optional)
If you choose to create a profile, we collect:
• Age, biological sex, height, and weight.

This information is used solely to improve blood-pressure estimates on your device.

1.3 Apple Health (Optional)
If you enable the Apple Health integration, PulseLab:
• Writes heart rate after each camera capture and blood pressure from cuff readings.
• Reads heart rate and blood pressure data recorded by other apps or devices to display alongside your measurements.

PulseLab only accesses Apple Health data with your explicit permission.

1.4 Device & Crash Data
We use Firebase Crashlytics to collect anonymous crash reports, including device model, OS version, and stack traces. This helps us identify and fix bugs. Crash data does not include your health measurements or profile.

We use Firebase Remote Config to check whether your app version is still supported and to deliver non-personalized configuration values (e.g., minimum supported version).

1.5 Advertising Data
PulseLab displays ads provided by Google AdMob. If you grant permission through the App Tracking Transparency prompt, AdMob may use your device's advertising identifier (IDFA) to show more relevant ads. You can deny this permission with no loss of app functionality — you will simply see non-personalized ads.

AdMob and the Google User Messaging Platform (UMP) may collect:
• Device identifiers (IDFA, if authorized)
• IP address (for general location-based ad targeting)
• Ad interaction data (impressions, taps)

For details, see Google's Privacy Policy.

1.6 Notification Preferences
If you enable measurement reminders, PulseLab schedules local notifications on your device. Notification times are stored locally and are not transmitted to any server.

2. How Your Data Is Stored

| Data | Storage location |
|---|---|
| Measurement sessions | On-device (SwiftData) |
| Health profile | On-device (SwiftData) |
| App preferences | On-device (UserDefaults) |
| Apple Health data | On-device (Apple HealthKit) |
| Crash reports | Firebase Crashlytics servers |
| Ad-related identifiers | Google AdMob servers |

Your health measurements, profile, and session history never leave your device unless you explicitly export them using the in-app export feature (JSON, CSV, or PDF). Exported files are handled through the iOS share sheet and are entirely under your control.

3. Data We Do NOT Collect

• We do not create user accounts.
• We do not collect your name, email address, or phone number.
• We do not upload camera images or video — all PPG processing happens on-device in real time.
• We do not sell or share your health data with any third party.

4. Third-Party Services

| Service | Purpose | Privacy Policy |
|---|---|---|
| Firebase Crashlytics | Crash reporting | firebase.google.com/support/privacy |
| Firebase Remote Config | Version checking | firebase.google.com/support/privacy |
| Google AdMob | Advertising | policies.google.com/privacy |

5. Your Choices

• Apple Health: Toggle sync on or off in the Health Profile screen at any time.
• Ad tracking: You can change your tracking preference in Settings → Privacy & Security → Tracking on your device.
• Notifications: Disable reminders in the app, or revoke notification permission in Settings → PulseLab → Notifications.
• Delete your data: Uninstalling PulseLab removes all locally stored sessions, profile data, and preferences. Apple Health data you wrote can be managed in the Health app.
• Export your data: Use the History tab to export your sessions as JSON, CSV, or PDF before deleting the app.

6. Children's Privacy

PulseLab is not intended for children under 13. We do not knowingly collect information from children.

7. Medical Disclaimer

PulseLab is a research prototype. Camera-based blood-pressure estimates are not medically validated and may be inaccurate. Do not use them to diagnose, treat, or change medication. Always confirm blood pressure with a validated upper-arm cuff and consult a healthcare professional for medical decisions.

8. Changes to This Policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top of this page will reflect any changes. Continued use of the app after changes constitutes acceptance of the revised policy.

9. Contact Us

If you have questions about this Privacy Policy, contact us at:

Email: drigonlac@gmail.com
