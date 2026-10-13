# TiMe — Privacy Policy

**Last updated:** [RELEASE DATE]
**Effective:** [RELEASE DATE]

---

## In short

TiMe is a menstrual cycle tracking app. Your data is **stored on your
device by default.** No account is required. We do not keep your cycle
data on our servers. We do not share data with advertising networks. The
app contains no analytics software.

Your data leaves your device only in these situations, each requiring your
explicit choice:

1. **AI commentary and chat** — when the on-device model is unavailable
   and you have given consent
2. **Apple Health (HealthKit)** exchange — when you grant permission
3. **Subscription purchases**

Details below.

---

## 1. Data controller

| | |
|---|---|
| Name | Batuhan Atabek |
| Address | [ADDRESS — TO BE COMPLETED] |
| Email | atabeksoft+privacy@gmail.com |

This policy applies to the TiMe iOS application.

---

## 2. Data we process

### 2.1 Data that stays on your device

Stored in your device's local database and **never sent to our servers:**

- Period start and end dates, cycle lengths
- Flow intensity
- Symptoms (physical, mood, discharge, skin, digestion, sleep, energy)
- Sexual activity logs
- Basal body temperature, weight, ovulation test results
- Your free-text notes
- App preferences (language, units, reminder times)
- Your AI chat history

Some of this constitutes **special category data** (health data and data
concerning sex life) under GDPR Article 9. This is why our default
architecture is on-device storage.

### 2.2 Data that may leave your device

**a) AI commentary and chat**

TiMe first uses **your device's own AI model** to generate commentary. In
this case no data leaves your device.

If your device does not support this model, you are asked once, and **only
if you consent** is the following sent over an encrypted connection to a
proxy server and from there to an AI provider:

Sent:
- Your cycle lengths (numbers only)
- Your current cycle phase
- Symptom tags you selected
- Messages **you type** in the chat screen
- Your interface language

Not sent:
- Your name, email, date of birth
- Location
- Device or advertising identifier
- Exact dates
- Free-text notes from your daily logs

You can withdraw this consent at any time in Settings. The app then
returns to rule-based commentary and continues to work.

**Important:** Text you type into chat is transmitted to the provider as
written. We recommend not typing identifying information into chat.

**b) Apple Health (HealthKit)**

With your permission, menstrual flow, basal body temperature and related
records are exchanged with Apple Health. This data stays on your device
and is not sent to us.

We do **not use HealthKit data for advertising, marketing, or data mining,
and do not share it with third parties.**

**c) Subscriptions**

Purchases are processed by Apple. We have **no access to your payment
details.** We use RevenueCat to track subscription status; only an
anonymous user identifier and subscription state are sent, never your
cycle data.

**d) Abuse prevention**

To prevent abuse of AI requests, a randomly generated identifier (UUID) is
created on your device. It cannot be linked to you, is used only to count
daily requests, and resets when the app is deleted.

### 2.3 Data we do not collect

- Name, email, phone number
- Location
- Advertising identifier (IDFA)
- Contacts, photos, camera, microphone
- Usage analytics (the app contains no analytics SDK)

### 2.4 Features not currently offered

The app does **not** offer cloud sync (iCloud). Your data is not synced
between devices. If this feature is added later, this policy will be
updated and your consent requested separately.

---

## 3. Legal basis (GDPR)

| Purpose | Data | Legal basis |
|---|---|---|
| Cycle prediction and tracking | Cycle and symptom data | Explicit consent, Art. 9(2)(a) |
| AI commentary (on-device) | Cycle and symptom data | Explicit consent |
| AI commentary (remote) | Data in §2.2(a) | Separate explicit consent |
| Apple Health integration | Health records | Explicit consent |
| Notifications | Prediction dates, chosen times | Consent |
| Subscription management | Anonymous ID, subscription state | Contract, Art. 6(1)(b) |
| Abuse prevention | Random device identifier | Legitimate interest, Art. 6(1)(f) |

---

## 4. International transfers

If you consent to remote AI commentary, the data listed in §2.2(a) is
transferred to servers outside your country.

| Recipient | Role | Country |
|---|---|---|
| Cloudflare, Inc. | Proxy server | USA |
| Google LLC | AI provider (Gemini) | USA |

This transfer relies on your **explicit consent.** If you do not consent,
no data is transferred and the app continues to work on-device.

Our proxy does **not log** your health data.

Google's data handling: https://ai.google.dev/gemini-api/terms

---

## 5. Retention

- **On-device data:** until you delete it. Deleting the app deletes it.
- **Data sent to the AI provider:** not retained by us after the response
  is generated.
- **Abuse-prevention identifier:** 24 hours.
- **Subscription records:** as required by law, held by Apple and
  RevenueCat.

---

## 6. Your rights

Under GDPR you have the right to access, rectification, erasure,
restriction of processing, data portability, objection, and to withdraw
consent at any time. You also have the right to lodge a complaint with
your supervisory authority.

**In practice:** because most of your data lives only on your device, you
can exercise several of these rights directly in the app:

- **Access / portability:** Settings → Export data
- **Erasure:** Settings → Delete all data
- **Withdraw consent:** Settings → AI consent

For other requests: atabeksoft+privacy@gmail.com. We respond within 30
days.

---

## 7. Children

TiMe is not directed at children under 13 and we do not knowingly collect
data from them. If you are a parent or guardian and believe your child is
using the app, contact atabeksoft+privacy@gmail.com.

---

## 8. Security

- Data is stored within the standard iOS application sandbox.
- Optional app lock (Face ID / Touch ID).
- All network traffic is encrypted with TLS.
- Our proxy does not log health data.
- Data sent to the AI provider is minimised.

No system is completely secure. We recommend keeping your device updated
and using a device passcode.

---

## 9. Medical disclaimer

TiMe is for informational and personal tracking purposes. It is **not a
medical diagnosis, treatment, or method of contraception.** Predictions
are statistical and can be wrong. Consult a healthcare professional for
decisions about your health.

---

## 10. Changes

If we change this policy we will show an in-app notice and update the date
above. For material changes we will ask for your consent again.

---

## 11. Contact

**Batuhan Atabek**
[ADDRESS — TO BE COMPLETED]
atabeksoft+privacy@gmail.com
