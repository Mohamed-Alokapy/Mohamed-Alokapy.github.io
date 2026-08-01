# Privacy Policy — ( ذاكر و حل ) (Study & Solve)

**Effective date:** 2026-08-01
**Last updated:** 2026-08-01


## 1. Introduction

Study & Solve ("the App") is an educational platform for students. This policy
explains what data we collect, why, and how you can contact us.

## 2. Data We Collect

| Category | Data | Purpose |
|---|---|---|
| **Account identity** | Name, Email address, Phone number | Create & secure your account, communicate subscription status |
| **Device fingerprint** | Android Build ID, device model/brand/codename | Bind your account to one trusted device (anti account sharing) |
| **Learning activity** | Quiz answers, scores, attempt times | Show you progress and results |
| **Purchase / subscription** | Enrollment list + expiry date (manually granted by admins; **no payment card data** is collected) | Unlock premium content |
| **Crash & diagnostics** | Firebase logs (no PII in release builds) | Stability monitoring |

## 3. What We Do NOT Collect

- ❌ Payment card information
- ❌ Precise location
- ❌ Contacts, photos, microphone, camera content
- ❌ Advertising identifiers

## 4. Data Sharing

We do **not** sell your data. We share it only with:

- **Google Firebase** (Auth, Firestore, Functions, App Check) — data processor
- **WhatsApp / Telegram** — only when *you* tap "Contact support"; your name
  and email are pre-filled in the chat message and sent to the support number
  you already have in your contacts.

## 5. Security

- All data is transmitted over HTTPS.
- Access rules in Firestore restrict every user to their own data.
- Quiz grading happens server-side; your device never sees answer keys.
- Firebase App Check prevents scripted/bot access.

## 6. Your Rights

You may request **access**, **correction**, or **deletion** of your data at any
time by contacting support (see below). Deleting your account removes your
profile within 30 days.

## 7. Children's Privacy

The App targets students; it is not directed at children under 13. We do not
knowingly collect data from children under 13.

## 8. Contact

- **WhatsApp:** (see in-app Settings → Contact)
- **Telegram:** (see in-app Settings → Contact)

---

## Appendix A — Google Play "Data Safety" cheat-sheet

Use this when filling the Data Safety form in Play Console:

| Question | Answer |
|---|---|
| Collects personal info? | **Yes** — Name, Email, Phone number |
| Data encrypted in transit? | **Yes** (HTTPS/TLS) |
| User can request deletion? | **Yes** — via support contact |
| Data shared with third parties? | **Only on user action** — WhatsApp/Telegram support messages |
| Data used for ads? | **No** |
| Device identifiers? | **Yes** — coarse fingerprint for anti-sharing |
| Financial info? | **No** |
| Location? | **No** |
| Files, photos, contacts? | **No** |
