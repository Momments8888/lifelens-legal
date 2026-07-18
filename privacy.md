# LifeLens AI — Privacy Policy

**Effective date:** February 15, 2026

**Last updated:** July 17, 2026

## 1. Who we are

LifeLens AI ("LifeLens," "we," "us," or "our") is a mobile application that
builds a searchable memory of your life from photos, voice notes, receipts,
prescriptions, text, and location. This Privacy Policy explains what we
collect, how we use it, and the rights you have over your data.

If you have any questions, contact us at **support@lifelens.app**.

## 2. Information we collect

### 2.1 Information you provide

- **Account information:** email address, name (optional), and a hashed
  password. If you use email-code sign-in, we also store a temporary
  verification code that expires within minutes.
- **Memories:** anything you save into LifeLens, including text notes, voice
  recordings, photos, receipts, and forwarded emails. Memories may include
  metadata (location, timestamp) you choose to attach.
- **Prescription and medication information (only if you use the
  prescription feature):** when you scan a prescription or medication label,
  we store the photo and the extracted details — medication name, dosage,
  frequency, prescriber, instructions, your dose schedule times, dose-taken
  logs, and any personal notes you add. This is sensitive health
  information; it is stored against your account only and is never shared
  with advertisers or sold.
- **Payment information:** if you subscribe to Premium, our payment processor
  (Stripe) collects your payment details. **We never see or store your card
  number.** Stripe returns only a customer ID and a subscription status to us.

### 2.2 Information we collect automatically

- **Device information:** device model, OS version, app version, language,
  and time zone.
- **Location data (only if you grant permission):** foreground location for
  features like "Where did I park?", business-dwell prompts, and smart-recall
  notifications. **Precise (GPS-level) location** is used for these features;
  coordinates are also used to attach a weather stamp to the moment.
  **Background location** is used only if you enable Smart Recall in
  Settings → Location AND grant "Allow all the time" in the system prompt —
  it powers automatic "capture this moment?" and "you just left…" nudges,
  and you can turn it off at any time.
- **Health data (only if you connect Health Connect or Apple Health):**
  steps, distance walked, active calories, and heart-rate measurements
  (daily average, minimum, maximum, and resting BPM). This data is read via
  the Android Health Connect / iOS HealthKit APIs and pulled only when you
  have granted explicit permission. Health data is never shared with third
  parties and never used for advertising.
- **Usage information:** in-app actions (memories created, questions asked)
  used solely to power the app's core features, to show you your own usage
  statistics, and to help you find your own memories through search.

### 2.3 Information we do NOT collect

- We do **not** collect data from other apps on your device.
- We do **not** read your SMS, call logs, contacts, or calendar. The only
  contact interaction is **creating** a contact card on your device when you
  explicitly tap "Save as contact" — we never read or upload your contact
  list.
- We do **not** track your web browsing.
- We do **not** sell your data to advertisers.

## 3. How we use your information

We use the information we collect to:

- Provide the core functionality (save your memories, answer questions about
  them, generate summaries).
- Read prescription labels you scan and build medication schedules, dose
  reminders, and refill running-low alerts you ask for.
- Deliver notifications you have opted into (reminders, medication doses,
  smart-recall prompts, weekly digest).
- Sync health metrics you have explicitly connected (steps, heart rate).
- Attach weather at the time and place of a memory (via Open-Meteo and
  similar public weather APIs, with no personal identifiers).
- Look up business details you save (via Google Places).
- Save a memory's photo back to your device's photo library, only when you
  tap "Save photo".
- Process subscription payments (via Stripe).
- Send transactional emails such as password resets and, if you opt in,
  weekly digest emails summarizing your recent memories (via Resend).
- Detect and prevent fraud, abuse, and security incidents.
- Comply with legal obligations.

## 4. AI processing (third-party AI — limited use)

To power features such as summarization, natural-language search, photo
understanding, prescription reading, and "Where did I park?" style Q&A,
LifeLens sends relevant content to AI providers we contract with (currently
OpenAI). Depending on the feature, this content can include:

- the **text** of relevant memories (never your entire history at once);
- **photos you choose to capture or upload**, which are analyzed by a vision
  model to produce a searchable text description (including prescription
  label photos, which are read to extract medication details);
- **voice recordings**, which are transmitted for speech-to-text
  transcription, and text that is converted to audio if you enable the
  premium voice feature.

**Limited use:** your content is sent to these providers **only** to provide
the specific feature you invoked, is retained by them only as long as needed
to process the request, is **never** used for advertising or profiling, and
these providers process content on our behalf under agreements that prohibit
them from training their models on your data.

You can turn off AI features from Profile → Settings; the app will continue
to work as a plain memory archive.

## 5. Storage and security

- **Encryption at rest:** memory content is encrypted at rest with a
  per-user encryption key. Even if our database were accessed by a third
  party, memories are unreadable without the corresponding key.
- **Encryption in transit:** all communication between the app and our
  backend uses TLS 1.2 or higher.
- **Access controls:** only the account owner (and family members you
  explicitly add) can decrypt and read your memories.
- **Third-party media storage:** photos and voice recordings are stored in
  Google Firebase Storage (Google Cloud) under private, per-user paths.
  Files are accessible only through unguessable per-file URLs issued to your
  account, and Google provides its own encryption at rest and in transit.

No system is perfectly secure. We cannot guarantee absolute security, but
we work continuously to reduce risk.

## 6. Data sharing

We share information only in these limited circumstances:

- **Service providers** that operate the app under contract:
  - **OpenAI** — AI processing (text, vision, speech-to-text,
    text-to-speech), under the limited-use terms described in Section 4.
  - **Google (Places, Maps, Firebase Storage, Health Connect)** — place
    lookups, maps, media storage, and device-level health data access.
  - **Stripe** — payment processing.
  - **Resend** — transactional and weekly-digest email.
  - **Open-Meteo and similar weather APIs** — weather (no personal
    identifiers sent).
- **Family members you add** — memories tagged as "family" become readable
  by everyone in your family circle. You can leave a family circle at any
  time in Profile → Family.
- **Legal requirements** — if compelled by valid legal process (subpoena,
  court order) or to protect the safety of a person or property.
- **Business transfers** — if LifeLens is acquired or merged, we will notify
  you before your data is transferred, and you may delete your account
  first if you prefer.

We do **not** sell your personal information. Location and health data are
**never** shared with third parties for their own purposes.

## 7. Your rights

Depending on where you live, you may have the right to:

- **Access** your personal information.
- **Correct** or update it.
- **Delete** your account and everything associated with it. You can do this
  yourself in Profile → Account → Delete account, or by contacting us.
- **Export** your data. Profile → Account → Export my data downloads every
  memory as JSON.
- **Withdraw consent** for optional features (push, location, health).
- **Object** to processing or **restrict** it in certain cases.
- **Lodge a complaint** with your local data-protection authority.

Californian residents have additional rights under the CCPA, including the
right to know and the right to opt out of "sales" (we do not sell).

European residents have additional rights under the GDPR, including the
right to data portability and to lodge a complaint with a supervisory
authority.

## 8. Data retention

- **Active accounts:** we keep your data as long as your account is active.
- **Deleted memories:** stay in Trash for **30 days** so you can restore
  them, then are permanently deleted (including the associated photo and
  voice files in Firebase Storage).
- **Deleted accounts:** all associated data is permanently deleted within
  30 days of account deletion, except for records we must retain for tax
  or legal reasons (usually anonymized).
- **Payment records:** Stripe retains transaction records per its own
  policies to comply with tax law.

## 9. Children's privacy

LifeLens is **not intended for children under 13** (or the equivalent age
in your jurisdiction). We do not knowingly collect information from
children. If you believe a child has provided us with data, please contact
us and we will delete it.

## 10. International transfers

Our servers are located in the United States. If you use LifeLens from
outside the United States, your data will be transferred to and processed
in the United States, where privacy laws may differ from your country. By
using the app, you consent to this transfer.

## 11. Changes to this policy

We may update this Privacy Policy from time to time. If we make material
changes, we will notify you inside the app and by email. The "Last updated"
date at the top always reflects the current version.

## 12. Contact us

Questions, concerns, or data-rights requests:

- **Email:** support@lifelens.app
- **In-app:** Profile → Help & feedback
