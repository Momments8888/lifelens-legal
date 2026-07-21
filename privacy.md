<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LifeLens AI · Privacy Policy</title>
  <style>
    :root { --bg:#FDFBF7; --ink:#2C2B29; --muted:#5C5852; --accent:#8FA590; --card:#F4F0EA; --border:#EAE4DB; }
    * { box-sizing: border-box; }
    body { margin: 0; background: var(--bg); color: var(--ink); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; line-height: 1.6; }
    main { max-width: 760px; margin: 0 auto; padding: 40px 24px 80px; }
    header { border-bottom: 1px solid var(--border); padding-bottom: 24px; margin-bottom: 32px; }
    h1 { font-family: Georgia, serif; font-style: italic; font-size: 36px; margin: 0 0 8px; letter-spacing: -0.5px; }
    .sub { color: var(--muted); font-size: 15px; }
    h2 { font-family: Georgia, serif; font-size: 22px; margin: 40px 0 12px; }
    h3 { font-size: 16px; margin: 24px 0 8px; }
    p, li { font-size: 15px; color: var(--ink); }
    ul { padding-left: 20px; }
    .card { background: var(--card); border: 1px solid var(--border); border-radius: 12px; padding: 16px 20px; margin: 16px 0; }
    a { color: var(--accent); text-decoration: none; border-bottom: 1px dotted var(--accent); }
    footer { margin-top: 60px; padding-top: 24px; border-top: 1px solid var(--border); color: var(--muted); font-size: 13px; }
    code { background: var(--card); padding: 2px 6px; border-radius: 4px; font-size: 14px; }
  </style>
</head>
<body>
<main>
  <header>
    <h1>LifeLens AI Privacy Policy</h1>
    <div class="sub">Effective date: <strong>February 15, 2026</strong> · Last updated: <strong>July 20, 2026</strong></div>
  </header>

  <p><strong>LifeLens AI</strong> ("LifeLens", "we", "our", or "us") builds a searchable memory of your life so you can ask questions like "Where did I park at Costco?" or "Who was that plumber?" This policy explains what we collect, why, and the rights you have over your data.</p>

  <div class="card">
    <strong>Short version.</strong> Your memories belong to you. They are encrypted on our servers with a key derived per-user, we do not sell your data, and you can delete your account and everything in it from inside the app at any time.
  </div>

  <h2>1. Who we are</h2>
  <p>LifeLens AI is operated by <strong>LifeLens AI LLC</strong>, located at <strong>1111 6th Ave, Ste 550</strong>. Questions? Email <a href="mailto:support@lifelens.app">support@lifelens.app</a>.</p>

  <h2>2. What we collect</h2>
  <h3>2.1 Data you give us directly</h3>
  <ul>
    <li><strong>Account:</strong> email address, password (stored as a bcrypt hash — we never see the plaintext), optional name.</li>
    <li><strong>Memories you capture:</strong> text notes, voice recordings, photos, imported emails, imported text messages, optional location tags. This is your primary content.</li>
    <li><strong>Payments (Premium):</strong> processed by <strong>Stripe</strong>. We never store your card number. Stripe returns us only a customer ID and subscription status.</li>
  </ul>

  <h3>2.2 Data we generate about your memories</h3>
  <ul>
    <li><strong>AI transcripts:</strong> Voice notes are transcribed to text using OpenAI Whisper.</li>
    <li><strong>AI descriptions of photos:</strong> Each photo you save is analysed by OpenAI GPT‑5.2 vision to produce a short searchable description (e.g. "receipt total $47.23, Whole Foods, Aug 12"). This is what lets us answer questions about the contents of photos later.</li>
    <li><strong>AI answers &amp; conversation history:</strong> Your questions to LifeLens and its replies are stored so the assistant can carry multi-turn conversations.</li>
  </ul>

  <h3>2.3 Data your device sends automatically</h3>
  <ul>
    <li><strong>Approximate technical info:</strong> app version, OS version, crash logs. Standard for any published mobile app.</li>
  </ul>

  <h3>2.4 What we do NOT collect</h3>
  <ul>
    <li>We do not read your emails, texts, or contacts automatically. Any email or text message content in LifeLens is content <em>you</em> chose to paste or share into the app.</li>
    <li>We do not access your device's SMS/iMessage database. That is not possible for third-party apps on iOS, and we do not request the special permission required on Android.</li>
    <li>We do not sell your data. Ever. There is no advertising SDK in LifeLens.</li>
  </ul>

  <h2>3. Device permissions we request</h2>
  <ul>
    <li><strong>Microphone</strong> — only when you tap "record" to create a voice memory. Audio never leaves the device except to be transcribed to text and immediately discarded from our transcription pipeline.</li>
    <li><strong>Camera</strong> — only when you tap "take photo" to create a photo memory.</li>
    <li><strong>Photo library</strong> — only when you tap "pick from library" or "scan library" and pick specific photos. We do not scan your library in the background.</li>
    <li><strong>Location (while using the app)</strong> — only when you tap "attach location" to tag a memory. You can decline and the memory is still saved without location.</li>
  </ul>
  <p>You can revoke any of these in your device's OS settings at any time; LifeLens will keep working with reduced capability.</p>

  <h2>4. How we use the data</h2>
  <ul>
    <li>To store and retrieve your memories at your request.</li>
    <li>To generate transcripts, photo descriptions, and answer your questions using LifeLens AI.</li>
    <li>To operate your account, process Premium payments, and prevent abuse.</li>
    <li>To improve the app (aggregate, non-identifying usage patterns only — e.g. "N% of users use voice notes weekly").</li>
  </ul>
  <p>We do <strong>not</strong> use your memories to train third-party AI models.</p>

  <h2>5. Voice recordings — your consent</h2>
  <p>By tapping record or using a voice feature, you give your <strong>explicit, affirmative consent</strong> for LifeLens and its processors (currently OpenAI) to collect, transmit, store, and process your audio recordings and their transcripts for the sole purpose of providing the app's features to you.</p>
  <ul>
    <li>We do <strong>not</strong> use recordings to biometrically identify you, and we do not create voiceprints or faceprints.</li>
    <li>We do <strong>not</strong> sell voice data or use it for advertising or profiling.</li>
    <li>Recordings and transcripts are retained until you delete the memory (plus the 30-day Trash window) or delete your account, whichever comes first.</li>
    <li>If you live in a jurisdiction with specific biometric or voice-data laws (e.g., Illinois BIPA, Texas CUBI, the Washington My Health My Data Act), your use of voice features constitutes your written release and consent to the processing described here.</li>
    <li>You are responsible for obtaining the consent of any other person you record; recording-consent laws vary by jurisdiction.</li>
  </ul>

  <h2>6. Who else touches your data (sub-processors)</h2>
  <ul>
    <li><strong>OpenAI</strong> — for GPT‑5.2 (memory Q&amp;A, photo vision, email/text extraction) and Whisper (voice transcription). OpenAI's API does not use API inputs to train their models by default.</li>
    <li><strong>Stripe</strong> — payment processing for Premium subscriptions.</li>
    <li><strong>Cloudinary</strong> (when configured by us) — image hosting for photo memories.</li>
    <li><strong>MongoDB / cloud hosting</strong> — where your account, memories, and AI conversation history are stored, encrypted at rest.</li>
  </ul>

  <h2>7. Encryption &amp; security</h2>
  <ul>
    <li>All API traffic uses <strong>HTTPS/TLS</strong> in transit.</li>
    <li>Every sensitive memory field — content, transcript, AI description, image data, location name, source metadata, tags — is <strong>encrypted at rest with AES‑256 (Fernet)</strong> using a key derived per-user via HKDF‑SHA256 from a master key stored in our secure environment. Compromising one user's data cannot decrypt another's.</li>
    <li>Passwords are stored as <strong>bcrypt</strong> hashes.</li>
    <li>Auth tokens on your phone are stored in the OS Keychain (iOS) or EncryptedSharedPreferences (Android).</li>
  </ul>

  <h2>8. Data retention &amp; your right to delete</h2>
  <p>We keep your memories until you delete them. You can:</p>
  <ul>
    <li><strong>Delete a single memory</strong> — Home → tap the memory → trash icon → confirm.</li>
    <li><strong>Delete your whole account &amp; everything in it</strong> — Profile → Privacy → "Delete my account &amp; wipe data". This is permanent; we cascade-delete your account, every memory, every conversation, and every integration record from our databases within 30 days (usually within minutes).</li>
    <li><strong>Export your data</strong> — email <a href="mailto:support@lifelens.app">support@lifelens.app</a> and we will send you a machine-readable copy within 30 days.</li>
  </ul>

  <h2>9. Children</h2>
  <p><strong>No one under the age of 13 is permitted to use, sign up for, or be invited to LifeLens.</strong> Where local law sets a higher minimum age of digital consent (up to 16 in certain European countries under GDPR Article 8), that higher age applies. We do not knowingly collect personal information from children (consistent with the U.S. Children's Online Privacy Protection Act, COPPA). If we learn an account belongs to a child under the applicable minimum age, we will terminate it and delete its data. If you believe a child has created an account, contact us and we will remove it.</p>

  <h2>10. International transfers</h2>
  <p>Our servers may be located outside your country. By using LifeLens you consent to your data being processed in <strong>the United States of America</strong> (and other countries where our processors operate). Where required — for example for EEA/UK/Swiss users — our processors rely on appropriate safeguards such as Standard Contractual Clauses.</p>

  <h2>11. Your rights (GDPR, CCPA, and others)</h2>
  <p>You have the right to access, correct, port, restrict, or delete your personal data, and to object to certain processing. To exercise any right, email <a href="mailto:support@lifelens.app">support@lifelens.app</a>. We respond within 30 days.</p>
  <ul>
    <li><strong>California (CCPA/CPRA):</strong> you may know what we collect, opt out of "sales" and of "sharing" for cross-context behavioral advertising (<strong>we do neither</strong>), and you will never be discriminated against for exercising a privacy right.</li>
    <li><strong>EEA / UK / Switzerland:</strong> we process your data on the legal bases of contract performance (the service you signed up for), your consent (optional features such as location, voice, and digest emails), and legitimate interests (security and abuse prevention). You also have the right to lodge a complaint with your local supervisory authority.</li>
    <li><strong>Other jurisdictions</strong> (e.g., Canada's PIPEDA, Brazil's LGPD, Australia's Privacy Act): you may exercise your equivalent rights through the same channels.</li>
  </ul>

  <h2>12. Changes to this policy</h2>
  <p>If we change this policy meaningfully we will notify you in the app before the change takes effect. Small clarifications will just get a new "Last updated" date above.</p>

  <h2>13. Contact</h2>
  <p><a href="mailto:support@lifelens.app">support@lifelens.app</a></p>

  <footer>
    LifeLens AI · Your life remembers what you forget.
  </footer>
</main>
</body>
</html>
