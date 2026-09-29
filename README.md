<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Pulsevia Privacy Policy</title>
  <meta name="description" content="How Pulsevia for iPhone handles your data: camera pulse readings processed on-device, health data that stays on your phone, optional Apple Health sync, ads, analytics, crash reports, and your rights.">
  <style>
    :root {
      color-scheme: light dark;
      --bg: #ffffff;
      --fg: #1c1c1e;
      --muted: #6e6e73;
      --rule: #e5e5ea;
      --accent: #0a84ff;
      --table-head: #f2f2f7;
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #000000;
        --fg: #f2f2f7;
        --muted: #98989d;
        --rule: #2c2c2e;
        --accent: #0a84ff;
        --table-head: #1c1c1e;
      }
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--fg);
      font: 17px/1.6 -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
    }
    main {
      max-width: 44rem;
      margin: 0 auto;
      padding: 3rem 1.25rem 4rem;
    }
    h1 { font-size: 2rem; line-height: 1.2; margin: 0 0 .5rem; }
    h2 { font-size: 1.35rem; margin: 2.25rem 0 .75rem; padding-top: 1rem; border-top: 1px solid var(--rule); }
    p, li { margin: 0 0 .9rem; }
    ul { padding-left: 1.25rem; }
    li { margin-bottom: .4rem; }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .meta { color: var(--muted); margin-bottom: 2rem; }
    .summary {
      background: var(--table-head);
      border-radius: 12px;
      padding: 1rem 1.25rem;
      margin: 1.5rem 0;
    }
    .summary h2 { border: 0; margin: 0 0 .5rem; padding: 0; font-size: 1.1rem; }
    .summary ul { margin: 0; }
    .notice {
      border-left: 4px solid var(--accent);
      padding: .5rem 1rem;
      margin: 1.25rem 0;
      color: var(--muted);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1rem 0 1.25rem;
      font-size: .95rem;
    }
    th, td {
      text-align: left;
      vertical-align: top;
      padding: .6rem .5rem;
      border-bottom: 1px solid var(--rule);
    }
    th { background: var(--table-head); font-weight: 600; }
    @media (max-width: 600px) {
      table, thead, tbody, th, td, tr { display: block; }
      thead { display: none; }
      tr { border: 1px solid var(--rule); border-radius: 10px; padding: .5rem; margin-bottom: .75rem; }
      td { border: 0; padding: .25rem .25rem; }
      td::before { content: attr(data-label); display: block; font-weight: 600; color: var(--muted); font-size: .8rem; }
    }
    footer { margin-top: 3rem; color: var(--muted); font-size: .9rem; }
  </style>
</head>
<body>
<main>
  <h1>Pulsevia Privacy Policy</h1>
  <p class="meta"><strong>Effective date:</strong> September 29, 2026</p>

  <p>Pulsevia (formerly named PulseLab) is a research-prototype app for iPhone. It uses the rear camera and flash to read your fingertip pulse, reports heart rate, and produces an experimental blood-pressure estimate that you can calibrate against readings from an upper-arm cuff. This policy explains what information the app handles, what stays on your phone, what reaches third parties, and the choices you have.</p>

  <div class="notice">
    <p>Pulsevia is not a medical device. Its blood-pressure estimates are not clinically validated and must not be used to diagnose, treat, or change medication. Always confirm blood pressure with a validated cuff.</p>
  </div>

  <h2 id="who-we-are">Who we are</h2>
  <p>Pulsevia is developed and published by Moaloop, an individual developer based in Brazil. Moaloop is the data controller for any personal data described in this policy.</p>
  <p>Contact: <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a></p>

  <section class="summary" aria-labelledby="short-version">
    <h2 id="short-version">The short version</h2>
    <ul>
      <li>Your pulse is measured entirely on your phone. The camera never saves or sends an image. Only an average colour value per frame is used, and it is discarded as soon as the reading is computed.</li>
      <li>Your heart rate, blood-pressure estimates, cuff readings, and health profile are stored only on your device. We have no server and never receive them.</li>
      <li>Apple Health sync is off by default. When you turn it on, data moves between Pulsevia and the Health app on your phone only.</li>
      <li>We do not create accounts and never ask for your name or email.</li>
      <li>The app shows ads through Google AdMob. It asks for tracking permission with Apple's App Tracking Transparency prompt. If you decline, ads are still shown but without the advertising identifier.</li>
      <li>We receive anonymous usage analytics and crash reports through Google Firebase. These never include your health measurements or profile.</li>
      <li>We do not sell personal information.</li>
    </ul>
  </section>

  <h2 id="on-device">Information processed on your device only</h2>
  <p>The features below use device permissions. What they read is processed in memory on your phone and is never transmitted to us.</p>
  <table>
    <thead>
      <tr><th>Permission</th><th>Feature</th><th>What happens</th></tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="Permission">Camera and flash</td>
        <td data-label="Feature">Pulse capture</td>
        <td data-label="What happens">For 30 seconds the app lights your fingertip with the flash and reads the average red, green, and blue level of the centre of each camera frame. No image is captured, saved, previewed, or transmitted. The colour values are turned into a pulse waveform in memory and discarded.</td>
      </tr>
      <tr>
        <td data-label="Permission">Apple Health (optional)</td>
        <td data-label="Feature">Sync with Apple Health</td>
        <td data-label="What happens">Reads and writes health records on your phone as described in the Apple Health section below. Nothing read from Health leaves your device.</td>
      </tr>
      <tr>
        <td data-label="Permission">Notifications (optional)</td>
        <td data-label="Feature">Measurement reminders</td>
        <td data-label="What happens">Schedules local notifications at times you choose. Reminder settings are stored on your phone and never sent to a server.</td>
      </tr>
    </tbody>
  </table>
  <p>You can grant or revoke any of these permissions at any time in the iOS Settings app. Without camera access the app cannot take a reading, but every other screen remains usable.</p>

  <h2 id="local-storage">Health information stored on your device</h2>
  <p>Pulsevia keeps your readings in a local database on your phone so you can review history and trends. This data is protected by the iOS app sandbox, is included in your normal iCloud or computer device backup like any other app data, and is deleted when you delete the app. It is never uploaded to us.</p>
  <ul>
    <li><strong>Capture sessions:</strong> date, duration, heart rate, signal quality, the blood-pressure estimate with its confidence, and a small set of pulse-shape values (how quickly each beat rises and how wide it is) used to refine later estimates.</li>
    <li><strong>Cuff readings:</strong> systolic and diastolic values you type in, when they were taken, and the monitor model if you choose to enter it.</li>
    <li><strong>Health profile (optional):</strong> age, biological sex, height, and weight. These only adjust the estimate on your device. You can leave the profile empty.</li>
    <li><strong>Preferences:</strong> whether Apple Health sync is on, whether onboarding and the profile prompt have been completed, reminder times, and a count of completed readings used to space out full-screen ads and the App Store rating prompt.</li>
  </ul>
  <p><strong>Exports.</strong> From the History screen you can export sessions as JSON, CSV, or a PDF report. The file is created on your phone with complete file protection and handed to the iOS share sheet. Where it goes from there is your choice. We do not receive a copy.</p>

  <h2 id="apple-health">Apple Health</h2>
  <p>Health sync is off until you enable it in the profile screen. When enabled, and only for the categories you approve in the Health permission sheet, Pulsevia:</p>
  <ul>
    <li><strong>Writes</strong> your heart rate after each successful capture, and blood pressure from the cuff readings you enter. It never writes camera-estimated blood pressure to Health.</li>
    <li><strong>Reads</strong> heart-rate and blood-pressure records from other apps and devices, to show them on the Trends screen and to use cuff readings from a connected monitor as calibration references.</li>
    <li><strong>Reads</strong> date of birth, biological sex, height, and weight, only when you tap "Fill in from Apple Health", to prefill the profile form. You review the values before saving.</li>
  </ul>
  <p>In line with Apple's HealthKit rules, information obtained from Apple Health is used solely to provide these features. It is never used for advertising or analytics, never sold, and never shared with anyone, including us. You can change or withdraw Health access at any time in the Health app under Sharing, Apps and Services, Pulsevia.</p>

  <h2 id="advertising">Advertising (Google AdMob)</h2>
  <p>Pulsevia shows a banner ad at the bottom of the History and Learn screens, a full-screen ad after launch, and a full-screen ad after some completed readings. Ads are served by Google AdMob, part of Google LLC.</p>
  <p><strong>Tracking permission.</strong> On first launch the app shows Apple's App Tracking Transparency prompt. If you allow tracking, Google may use your device's advertising identifier (IDFA) to select ads that are more relevant to you and to measure ad performance across apps. If you decline, the identifier is not available and ads are selected from context alone, such as the app, your approximate region, and the current session. Declining does not limit any feature of the app.</p>
  <p><strong>Consent.</strong> In the European Economic Area, the United Kingdom, Switzerland, and other regions where the law requires it, Pulsevia uses Google's User Messaging Platform to show a consent message before ads are requested. Your choice is stored on your device.</p>
  <p><strong>What Google receives.</strong> To serve and measure ads, the Google Mobile Ads SDK may process your IP address (from which an approximate location is derived), device model and operating system version, app identifier and version, language, screen size, ad interaction events such as impressions and taps, and, with your permission, the advertising identifier. Google may also use Apple's SKAdNetwork framework and on-device conversion measurement to attribute app installs in aggregate. Google acts as an independent controller for this processing under its own terms:</p>
  <ul>
    <li><a href="https://policies.google.com/privacy" rel="noopener">Google Privacy Policy</a></li>
    <li><a href="https://policies.google.com/technologies/partner-sites" rel="noopener">How Google uses information from apps that use its services</a></li>
    <li><a href="https://support.google.com/admob/answer/6128543" rel="noopener">Google Ads and Ad Manager privacy</a></li>
  </ul>
  <p>Your health measurements, cuff readings, and profile are never shared with Google or used to select ads.</p>

  <h2 id="analytics">Analytics (Firebase Analytics)</h2>
  <p>We use Google Firebase Analytics to understand how the app is used in aggregate, so we can prioritise improvements. Collection starts when the app launches.</p>
  <p>Pulsevia does not log any custom analytics events. Only the standard events Firebase collects automatically are sent: first open, session start, screen views, app updates, and operating system updates. Firebase assigns a random app-instance identifier to group events from the same installation and, if you allowed tracking in the prompt described above, may also receive the advertising identifier. Analytics events never contain your heart rate, blood-pressure values, cuff readings, profile, or Apple Health data.</p>
  <p>Firebase Analytics is operated by Google LLC as a processor on our behalf. Event data is retained for the period configured in our Firebase project and then deleted automatically.</p>

  <h2 id="crash-reports">Crash reports (Firebase Crashlytics)</h2>
  <p>If the app crashes, Firebase Crashlytics sends us a report so we can fix the bug. A report contains the stack trace, device model, operating system version, app version, free memory and storage at the time, and a random installation identifier. Reports never include your readings, profile, or Health data.</p>

  <h2 id="remote-config">Remote configuration (Firebase Remote Config)</h2>
  <p>The app fetches a few configuration values from Firebase Remote Config: the minimum supported app version, a recommended version, and the message to show if an update is needed. This lets us ask you to update when a critical fix is required. The fetch carries only the standard information any network request does (IP address, app identifier and version, device platform) plus the installation identifier. No personal data is stored for this purpose.</p>

  <h2 id="app-store">App Store rating prompt</h2>
  <p>After a few completed readings the app may ask iOS to show Apple's standard rating prompt. Apple handles the prompt and any rating you leave under <a href="https://www.apple.com/legal/privacy/" rel="noopener">Apple's Privacy Policy</a>. Pulsevia has no in-app purchases and no accounts.</p>

  <h2 id="how-we-use">How we use information</h2>
  <ul>
    <li>To take pulse readings and produce estimates on your device</li>
    <li>To store your history, cuff readings, and profile on your device</li>
    <li>To sync with Apple Health when you ask for it</li>
    <li>To show ads</li>
    <li>To understand aggregate usage and fix crashes</li>
    <li>To keep the app compatible by checking the minimum supported version</li>
  </ul>

  <h2 id="legal-bases">Legal bases (GDPR, UK GDPR, LGPD)</h2>
  <ul>
    <li><strong>Health data:</strong> your readings, cuff values, profile, and Health records are processed only by the app on your phone. Because they never reach us or any third party, we do not process this special-category data as a controller. Apple Health access is granted through your explicit permission in iOS.</li>
    <li><strong>Consent:</strong> tracking for advertising, and advertising in regions where consent is required.</li>
    <li><strong>Legitimate interests:</strong> non-personalised ad serving where consent is not required, aggregate usage analytics, crash reporting, and the minimum-version check. Each is limited to technical and usage data that does not identify you.</li>
  </ul>

  <h2 id="recipients">Who receives information</h2>
  <p>Pulsevia has no server of its own. Information leaves your device only to the following recipients:</p>
  <table>
    <thead>
      <tr><th>Recipient</th><th>Purpose</th><th>Role</th></tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="Recipient">Google LLC (AdMob, User Messaging Platform)</td>
        <td data-label="Purpose">Ad serving and measurement, consent management</td>
        <td data-label="Role">Independent controller</td>
      </tr>
      <tr>
        <td data-label="Recipient">Google LLC (Firebase Analytics, Crashlytics, Remote Config)</td>
        <td data-label="Purpose">Usage analytics, crash reports, minimum-version check</td>
        <td data-label="Role">Processor on our behalf</td>
      </tr>
      <tr>
        <td data-label="Recipient">Apple Inc. (App Store)</td>
        <td data-label="Purpose">Rating prompt, app distribution</td>
        <td data-label="Role">Independent controller</td>
      </tr>
    </tbody>
  </table>
  <p>Apple Health data stays on your phone within Apple's HealthKit store and is not a transfer to Apple or anyone else. We do not sell personal information and do not disclose it to anyone else except where required by law.</p>

  <h2 id="transfers">International transfers</h2>
  <p>Moaloop is based in Brazil. Google and Apple process data in the United States and other countries where they operate. Where personal data is transferred out of the EEA, UK, Switzerland, or Brazil, our providers rely on recognised safeguards such as the European Commission's Standard Contractual Clauses and equivalent mechanisms under UK and Brazilian law.</p>

  <h2 id="retention">Data retention</h2>
  <ul>
    <li>Camera frames are processed in real time and never stored.</li>
    <li>Readings, cuff values, profile, and preferences remain on your device until you delete individual sessions, delete the app, or clear them.</li>
    <li>Records written to Apple Health remain in the Health app under Apple's controls until you delete them there.</li>
    <li>Consent and tracking choices are stored on your device until you change them or delete the app.</li>
    <li>Analytics and crash data are retained by Google for the periods configured in our Firebase project. Ad-serving data is retained by Google under its own retention policies.</li>
  </ul>

  <h2 id="children">Children</h2>
  <p>Pulsevia is a general-audience app and is not directed at children under 13, or under the applicable age of digital consent in your region. We do not knowingly collect personal information from children. If you believe a child has provided personal information through the app, contact us and we will address it.</p>

  <h2 id="rights">Your rights and choices</h2>
  <p><strong>Permissions.</strong> Turn Camera and Notifications on or off in iOS Settings under Pulsevia. Manage Apple Health access in the Health app under Sharing, Apps and Services.</p>
  <p><strong>Tracking.</strong> Change your tracking choice at any time in iOS Settings, Privacy &amp; Security, Tracking. Turning tracking off stops the advertising identifier from being shared with Google.</p>
  <p><strong>Ad consent.</strong> If you are in a region where the consent message was shown, you can revisit your choice by contacting us, and we will explain how to reset it. Deleting and reinstalling the app also clears the stored choice.</p>
  <p><strong>Delete your data.</strong> Swipe to delete individual sessions in History, or delete the app to remove everything Pulsevia stored locally. Records already written to Apple Health are deleted from the Health app. To ask Google to delete analytics data associated with your installation, contact us and we will submit the request through the Firebase console, or reset the identifier yourself by deleting and reinstalling the app.</p>
  <p><strong>Regional rights.</strong></p>
  <ul>
    <li><em>EEA, UK, Switzerland:</em> you may request access, rectification, erasure, restriction, portability, and object to processing based on legitimate interests. You may withdraw consent at any time without affecting prior processing. You may lodge a complaint with your local data protection authority.</li>
    <li><em>Brazil (LGPD):</em> you may request confirmation of processing, access, correction, anonymisation or deletion of unnecessary data, portability, information about sharing, and revocation of consent. You may file a complaint with the Autoridade Nacional de Proteção de Dados (ANPD).</li>
    <li><em>California (CCPA/CPRA) and other U.S. states:</em> you have the right to know what personal information is collected, to delete it, to correct it, and to be free from discrimination for exercising these rights. Personalised advertising with your permission may count as "sharing" under the CCPA. You can opt out by declining or turning off tracking in iOS Settings as described above.</li>
  </ul>
  <p>To exercise any right, email <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a>. We will respond within the timeframe required by applicable law, typically within 30 days. Because we hold no account or server-side record about you, we may ask for enough information to relate the request to your installation.</p>

  <h2 id="security">Security</h2>
  <p>Your health data never leaves your phone except into Apple Health at your request, so it is protected by the iOS app sandbox, device encryption, and your passcode. Exported files are written with complete file protection. Communication with Google and Apple uses encrypted HTTPS connections only. No method of transmission or storage is completely secure, and we cannot guarantee absolute security.</p>

  <h2 id="changes">Changes to this policy</h2>
  <p>We may update this policy when the app changes or the law requires. The effective date at the top will change, and the current policy is always available at this address, which is linked from the app's Learn tab. Material changes that affect how your data is handled will be highlighted in the app.</p>

  <h2 id="contact">Contact</h2>
  <p>Moaloop (individual developer), Brazil<br>
  Email: <a href="mailto:hello.moaloop@gmail.com">hello.moaloop@gmail.com</a></p>

  <footer>
    <p>&copy; 2026 Moaloop. Pulsevia is available on the App Store for iPhone.</p>
  </footer>
</main>
</body>
</html>
