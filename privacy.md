Here's a complete, copy-paste-ready privacy policy tailored to what LifeLens AI actually does. Save it as privacy.md in your GitHub repo.

# LifeLens AI — Privacy Policy

**Effective date:** February 15, 2026  
**Last updated:** February 15, 2026

## 1. Who we are

LifeLens AI ("LifeLens," "we," "us," or "our") is a mobile application that
builds a searchable memory of your life from photos, voice notes, receipts,
text, and location. This Privacy Policy explains what we collect, how we use
it, and the rights you have over your data.

If you have any questions, contact us at **support@lifelens.ai**.

## 2. Information we collect

### 2.1 Information you provide

- **Account information:** email address, name (optional), and a hashed
  password. If you use email-code sign-in, we also store a temporary
  verification code that expires within minutes.
- **Memories:** anything you save into LifeLens, including text notes, voice
  recordings, photos, receipts, and forwarded emails. Memories may include
  metadata (location, timestamp) you choose to attach.
- **Payment information:** if you subscribe to Premium, our payment processor
  (Stripe) collects your payment details. **We never see or store your card
  number.** Stripe returns only a customer ID and a subscription status to us.

### 2.2 Information we collect automatically

- **Device information:** device model, OS version, app version, language,
  and time zone.
- **Location data (only if you grant permission):** foreground location for
  features like "Where did I park?", business-dwell prompts, and smart-recall
  notifications. Background location is used only if you enable it in
  Settings → Location.
- **Health data (only if you connect Health Connect or Apple Health):**
  steps, sleep sessions, distance walked, and active calories. This data is
  read via the Android Health Connect / iOS HealthKit APIs and pulled only
  when you have granted explicit permission.
- **Usage information:** in-app actions (memories created, questions asked)
  used solely to power the app's core features and to help you find your own
  memories through search.

### 2.3 Information we do NOT collect

- We do **not** collect data from other apps on your device.
- We do **not** read your SMS, contacts, or calendar unless you explicitly
  attach or forward that content into LifeLens.
- We do **not** track your web browsing.
- We do **not** sell your data to advertisers.

## 3. How we use your information

We use the information we collect to:

- Provide the core functionality (save your memories, answer questions about
  them, generate summaries).
- Deliver push notifications you have opted into (reminders, smart-recall
  prompts, weekly digest).
- Sync health metrics you have explicitly connected.
- Attach weather at the time and place of a memory (via Open-Meteo, a
  free public API with no personal identifiers).
- Look up business details you save (via Google Places).
- Process subscription payments (via Stripe).
- Send transactional emails such as password resets (via Resend).
- Detect and prevent fraud, abuse, and security incidents.
- Comply with legal obligations.

## 4. AI processing

To power features such as summarization, natural-language search, and
"Where did I park?" style Q&A, LifeLens sends the text of relevant memories
(never your raw photos, and never your entire history at once) to one or
more Large Language Model providers we contract with (currently OpenAI and
Anthropic). These providers process content on our behalf under agreements
that prohibit them from training their models on your data.

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
- **Third-party storage:** photos and files may be stored via Cloudinary,
  which provides its own encryption at rest and in transit.

No system is perfectly secure. We cannot guarantee absolute security, but
we work continuously to reduce risk.

## 6. Data sharing

We share information only in these limited circumstances:

- **Service providers** that operate the app under contract:
  - **OpenAI / Anthropic** — AI processing.
  - **Google (Places, Maps, Health Connect)** — place lookups, maps, and
    device-level health data access.
  - **Cloudinary** — media storage.
  - **Stripe** — payment processing.
  - **Resend** — transactional email.
  - **Open-Meteo** — weather (no personal identifiers sent).
- **Family members you add** — memories tagged as "family" become readable
  by everyone in your family circle. You can leave a family circle at any
  time in Profile → Family.
- **Legal requirements** — if compelled by valid legal process (subpoena,
  court order) or to protect the safety of a person or property.
- **Business transfers** — if LifeLens is acquired or merged, we will notify
  you before your data is transferred, and you may delete your account
  first if you prefer.

We do **not** sell your personal information.

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
  them, then are permanently deleted.
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

- **Email:** support@lifelens.ai
- **In-app:** Profile → Help & feedback
