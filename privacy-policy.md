# Privacy Policy for StoryTime Buddy

**Last Updated: July 2026**

StoryTime Buddy ("we," "our," or "us") is committed to protecting the privacy of children and families who use **StoryTime Buddy: AI Stories** (the "App"). This Privacy Policy explains what information the App handles, where it goes, and the choices you have.

The short version: **your stories live on your device.** On devices with Apple Intelligence, stories can be created entirely on-device. Cloud AI features are optional, always require a grown-up's in-app permission first, and send only what is needed to create your story — never your identity.

## 1. Information Stored Only on Your Device

The following never leaves your device unless you use a cloud feature described in Section 2:

- Stories you create (text, images, and narration audio)
- Character preferences and settings
- Reading progress, favorites, and tags
- App preferences (language, voice settings, font choices)
- Drawings and photos you use in stories (these never leave your device — cloud illustration requests contain only text descriptions)

We do **not** require accounts or registration, do **not** collect names, email addresses, or contact information, do **not** track location, do **not** use advertising or analytics trackers, and do **not** serve advertisements.

## 2. AI Processing

### 2.1 On-Device AI (Apple Intelligence devices)

On supported devices, story text and illustrations can be generated entirely on your device using Apple Intelligence and Image Playground. Nothing is sent to us or anyone else, and your content is never used to train AI models.

### 2.2 Optional Cloud AI ("cloud magic")

Cloud AI features (part of the StoryTime Premium subscription, plus one free trial story on devices without Apple Intelligence) use trusted AI providers to create stories. **Cloud features never run without a grown-up first granting permission inside the App** (Settings → AI & your privacy shows and revokes this permission at any time).

When you use cloud features, the following is sent through our server solely to create your story:

- Your story idea/prompt and story text → **Anthropic** (Claude) to write the story
- Scene descriptions of each page — and, for character consistency, previously AI-generated story images — → **Google** (Gemini) to create illustrations. Your own photos and drawings are never sent.
- Story text → **Microsoft** (Azure Speech) to create narration audio

We use paid/enterprise API tiers of these services: **your content is never used to train AI models** and is not retained by these providers beyond transient processing and short-term abuse monitoring. Finished stories, images, and audio are returned to your device and stored only there — we keep no copy of your stories.

Requests travel through our server (hosted on Cloudflare), which enforces child-safety rules on every image request and does not log story content.

### 2.3 Safety

Every cloud illustration request is constrained server-side to child-safe, G-rated content, and generated images pass an automated safety check before reaching your device. You can report any story or picture from the reader (see Section 4).

## 3. Information We Process to Run the Service

To operate subscriptions and fair-use quotas, our server stores:

- An **anonymous app-generated identifier** (a random ID created on your device — it contains no personal information and is not linked to your identity)
- **Purchase entitlement records** received from Apple (App Store transaction identifiers — never your payment details, which Apple keeps)
- **Usage counts** (how many stories, images, and narration characters your subscription has used this month)

This data cannot be used to identify you or your child and is used only to provide the service you purchased.

## 4. Content Reports

If you report a story or picture from the reader ("Report a problem"), we receive: the report category, the reported page's text, your optional note, and your anonymous identifier. We use reports only to review the content and improve our safety systems.

## 5. Bring-Your-Own-Key Voice Engines (optional)

If you connect your own Google Cloud or ElevenLabs API key for narration voices, your key is stored only on your device, and narration requests go directly from your device to that provider under **your** account and their privacy terms. This feature is intended for grown-ups.

## 6. Children's Privacy (COPPA)

StoryTime Buddy is designed for children ages 4–10.

- We do not collect personal information from children. No accounts, no social features, no chat, no behavioral advertising.
- Cloud AI features are gated behind a **parental consent screen inside the App** and a grown-up check; parents can revoke this permission at any time in Settings → AI & your privacy.
- Story prompts should not include personal details (real full names, addresses, phone numbers). The App does not ask for them and they are not needed to make a great story.
- Purchases are protected by a parental gate in addition to Apple's own purchase protections.

## 7. In-App Purchases

All purchases are processed by Apple through the App Store. We never see your payment information. Manage or cancel subscriptions in your Apple ID settings; purchases support Family Sharing and can be restricted via Screen Time.

## 8. Data Retention and Deletion

- **Stories and all creative content:** on your device only — delete them in the App or by deleting the App.
- **Cloud permission:** revoke any time in Settings → AI & your privacy.
- **Entitlement and usage records:** kept while needed to operate your subscription.
- **Content reports:** kept only as long as needed to review and fix issues.

To request deletion of server-side records (entitlements, usage counts, reports), contact us at the address below with your request; because records are keyed to an anonymous identifier, we may ask you to send it from within the App's support flow so we can locate them.

## 9. Data Security

Device data uses iOS secure storage (SwiftData with iOS file protection). Server communication uses TLS encryption. Server-side records are stored with a managed database provider (Supabase) with access restricted to our service.

## 10. Third-Party Service Providers

| Provider | Purpose | What they receive |
|---|---|---|
| Apple | App distribution, purchases, on-device AI | Purchase/billing (under Apple's policy) |
| Anthropic (Claude) | Cloud story text | Story prompts and text |
| Google (Gemini) | Cloud illustrations | Scene descriptions + previously AI-generated story images (never your photos or drawings) |
| Microsoft (Azure Speech) | Cloud narration | Story text |
| Cloudflare | Our server infrastructure | Relays the above; no story content stored |
| Supabase | Entitlement/usage database | Anonymous ID, purchase entitlements, usage counts, content reports |

We do not sell data, and no provider may use your content for advertising or AI training.

## 11. Changes to This Policy

We will update this page when our practices change and revise the "Last Updated" date. Material changes affecting children's data will be reflected in the App's consent screens.

## 12. Contact Us

Questions or requests: **mrrmfamily2022@gmail.com**
