# LifeLensAI - Privacy Policy

**Effective date:** February 15, 2026

**Last updated:** July 20, 2026

## 1. Who we are

LifeLensAI ("LifeLensAI," "we," "us," or "our") is a mobile application that
builds a searchable memory of your life from photos, voice notes, receipts,
text, and location. This Privacy Policy explains what we
collect, how we use it, and the rights you have over your data.

If you have any questions, contact us at **support@lifelens.app**.

## 2. Information we collect

### 2.1 Information you provide

- **Account information:** email address, name (optional), and a hashed
  password. If you use email-code sign-in, we also store a temporary
  verification code that expires within minutes.
- **Memories:** anything you save into LifeLensAI, including text notes, voice
  recordings, photos, receipts, and forwarded emails. Memories may include
  metadata (location, timestamp) you choose to attach.
- **Payment information:** if you subscribe to Premium, our payment processor
  (Stripe) collects your payment details. **We never see or store your card
  number.** Stripe returns only a customer ID and a subscription status to us.
  We keep records of your subscription status, plan, billing events, and
  invoices (via Stripe) as long as needed for accounting, tax, and
  dispute-resolution obligations. We also send transactional billing emails
  (subscription welcome, cancellation confirmations, payment-failure notices)
  via Resend - these are service emails, not marketing.

### 2.2 Information we collect automatically

- **Device information:** device model, OS version, app version, language,
  and time zone.
- **Location data (only if you grant permission):** foreground location for
  features like "Where did I park?", business-dwell prompts, and smart-recall
  notifications. **Precise (GPS-level) location** is used for these features;
  coordinates are also used to attach a weather stamp to the moment.
  **Background location** is used only if you enable Smart Recall in
  Settings -> Location AND grant "Allow all the time" in the system prompt - 
  it powers automatic "capture this moment?" and "you just left..." nudges,
  and you can turn it off at any time.
- **Usage information:** in-app actions (memories created, questions asked)
  used solely to power the app's core features, to show you your own usage
  statistics, and to help you find your own memories through search.

### 2.3 Information we do NOT collect

- We do **not** collect data from other apps on your device.
- We do **not** read your SMS, call logs, contacts, or calendar. The only
  contact interaction is **creating** a contact card on your device when you
  explicitly tap "Save as contact" - we never read or upload your contact
  list.
- We do **not** track your web browsing.
- We do **not** sell your data to advertisers.

## 3. How we use your information

We use the information we collect to:

- Provide the core functionality (save your memories, answer questions about
  them, generate summaries).
- Deliver notifications you have opted into (reminders, smart-recall
  prompts, weekly digest).
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

## 4. AI processing (third-party AI - limited use)

To power features such as summarization, natural-language search, photo
understanding, and "Where did I park?" style Q&A,
LifeLensAI sends relevant content to AI providers we contract with (currently
OpenAI). Depending on the feature, this content can include:

- the **text** of relevant memories (never your entire history at once);
- **photos you choose to capture or upload**, which are analyzed by a vision
  model to produce a searchable text description;
- **voice recordings**, which are transmitted for speech-to-text
  transcription, and text that is converted to audio if you enable the
  premium voice feature.

**Limited use:** your content is sent to these providers **only** to provide
the specific feature you invoked, is retained by them only as long as needed
to process the request, is **never** used for advertising or profiling, and
these providers process content on our behalf under agreements that prohibit
them from training their models on your data.

You can turn off AI features from Profile -> Settings; the app will continue
to work as a plain memory archive.

### 4.1 Voice recordings - your consent

By tapping record or using a voice feature, you give your **explicit,
affirmative consent** for LifeLensAI and its processors (currently OpenAI) to
collect, transmit, store, and process your audio recordings and their
transcripts for the sole purpose of providing the Service to you.

- We do **not** use your recordings to biometrically identify you, and we do
  not create voiceprints or faceprints.
- We do **not** sell voice data or use it for advertising or profiling.
- Recordings and transcripts are retained until you delete the memory (plus
  the 30-day Trash window) or delete your account, whichever comes first.
- If you live in a jurisdiction with specific biometric or voice-data laws
  (e.g., Illinois BIPA, Texas CUBI, the Washington My Health My Data Act),
  your use of voice features constitutes your written release and consent to
  the processing described here.
- You are responsible for obtaining the consent of any other person you
  record; recording-consent laws vary by jurisdiction.

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
  - **OpenAI** - AI processing (text, vision, speech-to-text,
 text-to-speech), under the limited-use terms described in Section 4.
  - **Google (Places, Maps, Firebase Storage)** - place
 lookups, maps, and media storage.
  - **Stripe** - payment processing.
  - **Resend** - transactional and weekly-digest email.
  - **Open-Meteo and similar weather APIs** - weather (no personal
 identifiers sent).
- **Family members you add** - memories tagged as "family" become readable
  by everyone in your family circle. You can leave a family circle at any
  time in Profile -> Family.
- **Legal requirements** - if compelled by valid legal process (subpoena,
  court order) or to protect the safety of a person or property.
- **Business transfers** - if LifeLensAI is acquired or merged, we will notify
  you before your data is transferred, and you may delete your account
  first if you prefer.

We do **not** sell your personal information. Location data is
**never** shared with third parties for their own purposes.

## 7. Your rights

Depending on where you live, you may have the right to:

- **Access** your personal information.
- **Correct** or update it.
- **Delete** your account and everything associated with it. You can do this
  yourself in Profile -> Account -> Delete account, or by contacting us.
- **Export** your data. Profile -> Account -> Export my data downloads every
  memory as JSON.
- **Withdraw consent** for optional features (push, location).
- **Object** to processing or **restrict** it in certain cases.
- **Lodge a complaint** with your local data-protection authority.

Californian residents have additional rights under the CCPA/CPRA, including
the right to know, the right to opt out of "sales" and of "sharing" for
cross-context behavioral advertising (**we do neither**), and the right not
to be discriminated against for exercising any privacy right.

European Economic Area, UK, and Swiss residents: we process your data on the
legal bases of **contract performance** (providing the Service you signed up
for), **your consent** (optional features such as location, voice,
and marketing/digest emails), and **legitimate interests** (security and
abuse prevention). You additionally have the rights to data portability,
restriction of processing, and to lodge a complaint with your local
supervisory authority.

Residents of other jurisdictions with privacy statutes (e.g., Canada's
PIPEDA, Brazil's LGPD, Australia's Privacy Act) may exercise their
equivalent rights through the same channels.

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

**No one under the age of 13 is permitted to use, sign up for, or be invited
to LifeLensAI.** Where local law sets a higher minimum age of digital consent
(up to 16 in certain European countries under GDPR Article 8), that higher
age applies. We do not knowingly collect personal information from children
(consistent with the U.S. Children's Online Privacy Protection Act, COPPA).
If we learn that an account belongs to a child under the applicable minimum
age, we will terminate the account and delete its data. If you believe a
child is using LifeLensAI, please contact us and we will delete the data.

## 10. International transfers

Our servers are located in the United States. If you use LifeLensAI from
outside the United States, your data will be transferred to and processed
in the United States (and other countries where our processors operate),
where privacy laws may differ from your country. Where required - for
example for EEA/UK/Swiss users - our processors rely on appropriate
safeguards such as Standard Contractual Clauses. By using the app, you
consent to this transfer.

## 11. Changes to this policy

We may update this Privacy Policy from time to time. If we make material
changes, we will notify you inside the app and by email. The "Last updated"
date at the top always reflects the current version.

## 12. Contact us

Questions, concerns, or data-rights requests:

- **Email:** support@lifelens.app
- **In-app:** Profile -> Help & feedback
