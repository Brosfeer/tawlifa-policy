# Privacy Policy for Tawlifa (تَوْلِيفَة)
*Last Updated: October 17, 2026*

**Official Hosted GitHub Page (Google Play Compliance URL):**  
👉 [https://brosfeer.github.io/tawlifa-policy/](https://brosfeer.github.io/tawlifa-policy/)

---

Welcome to **Tawlifa** ("we", "our", or "us"). We respect your privacy and are committed to protecting it. This Privacy Policy explains our data practices for the Tawlifa mobile application (the "App", Package Name: `com.sayasky.tawlifa`).

Tawlifa is engineered with a **local-first, privacy-first architecture**: we do not collect personal accounts, do not run third-party advertising trackers, and store your custom recipes and spice formulations strictly on your physical device.

---

## 1. Information Collection & Use

### A. Information We Do NOT Collect
- **No Personal Identifiers:** We do not require registration, login, or accounts. We do not collect names, email addresses, phone numbers, postal addresses, or contacts.
- **No Location Tracking:** We do not request, access, or track GPS, fine location, or coarse location coordinates.
- **No Financial Data:** We do not collect credit card details, bank information, or payment transactions.
- **No Biometrics or Sensor snooping:** No camera, microphone, or health sensors are monitored or accessed.

### B. On-Device Local Storage (Local-First)
Tawlifa saves your culinary data directly in your device's isolated application sandbox via encrypted storage (`AsyncStorage`):
- Customized spice blend formulas, weight calculations, and Scoville heat levels
- Saved bookmarks and favorite recipes
- Temporary ingredient shopping lists and checked grocery items
- Personal recipe notes and cooking simmer countdown states
- Language selection (Arabic / English) and currency preference

> **Guarantee:** This local data **never leaves your device** and is never uploaded to external servers.

---

## 2. Analytics & Crash Diagnostics

To maintain application stability, diagnose crashes, and improve recipe offerings:
- **Firebase Crashlytics (`@react-native-firebase/crashlytics`):** Collects anonymous crash stack traces, device hardware model, and operating system versions to diagnose unhandled exceptions.
- **Firebase Analytics (`@react-native-firebase/analytics`):** Collects pseudonymous app interaction metrics (such as recipe views, search queries, and screen transitions) to identify popular culinary trends.

**No Third-Party Advertising:** Tawlifa contains **zero third-party advertisements**, no ad tracking SDKs, and does not sell or share data with data brokers. All diagnostic telemetry is transmitted securely over TLS/HTTPS directly to Google Firebase servers.

---

## 3. Android System Permissions Hygiene

The App requests only standard, essential Android permissions:
- `android.permission.INTERNET`: Used to load online culinary catalog photography and recipe updates over HTTPS.
- `android.permission.VIBRATE`: Delivers subtle tactile haptic pulses when cooking timers complete and when adjusting spice heat levels.
- `android.permission.READ_EXTERNAL_STORAGE` (`maxSdkVersion="32"`): Legacy compatibility fallback for legacy Android devices (Android 12 and below).

---

## 4. Google Play Data Safety Reference

| Data Category | Collected? | Shared? | Processing Type | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **Personal Identifiers** (Name, Email, Phone) | **No** | **No** | N/A | No accounts required |
| **Location Data** (GPS/Coarse) | **No** | **No** | N/A | Not requested |
| **Financial Info** | **No** | **No** | N/A | No payments in app |
| **Spice Formulas & Notes** | **On-Device** | **No** | Local Sandbox | Core App Functionality |
| **Crash Diagnostics** | **Yes** | **No** | Encrypted Transit | App Stability (Firebase) |
| **App Performance Metrics** | **Yes** | **No** | Encrypted Transit | Diagnostics (Firebase) |
| **Device / Instance Identifiers** | **Yes** | **No** | Encrypted Transit | Firebase App Check / Token |

- **Security in Transit:** All telemetry transmitted to Firebase is encrypted using TLS/HTTPS.
- **Account Deletion:** Because all user data is stored locally and no server accounts exist, users can delete all data permanently at any time by clearing application storage or uninstalling the app.

---

## 5. Data Retention & Deletion

You retain absolute control over your culinary data:
1. **Within the App:** You can clear search history and remove cart items directly at any time.
2. **Android System Settings:** You can wipe all data by going to:  
   *Settings > Apps > Tawlifa > Storage > Clear Storage / Clear Data*.
3. **App Uninstallation:** Uninstalling Tawlifa immediately and irreversibly deletes the on-device sandbox.

---

## 6. Children's Privacy (COPPA)

Tawlifa is a general-audience culinary utility designed for users aged 13 and above. We do not knowingly solicit or collect personal information from children under the age of 13.

---

## 7. Native Sharing

When using the "Share Recipe" feature, Tawlifa invokes the native Android Share dialog. Any recipe text shared is routed solely through the third-party application you explicitly choose (e.g., WhatsApp, Telegram, Messages).

---

## 8. Developer Contact & Support

If you have questions or feedback regarding this Privacy Policy:
- **Developer / Publisher:** Sharafaldain Al-Sheikh
- **Email:** [sharafaldain@nexumind.com](mailto:sharafaldain@nexumind.com)
- **Repository:** [https://github.com/Brosfeer/tawlifa-mobile](https://github.com/Brosfeer/tawlifa-mobile)
- **Live Policy GitHub Page:** [https://brosfeer.github.io/tawlifa-policy/](https://brosfeer.github.io/tawlifa-policy/)
- **Application ID:** `com.sayasky.tawlifa`
