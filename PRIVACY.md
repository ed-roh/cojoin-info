# Privacy Policy

**Cojoin** ("the app") is built by Andrew Nguyen. This privacy policy explains what data the app collects, where it lives, and what it does not do.

**Last updated: October 5, 2026**

---

## The short version

Cojoin requires a free account (email + password) so your friends list, hangout history, and messages stay in sync across your devices. We store your data securely and never sell it or use it for advertising. You can delete your account and everything tied to it at any time from Settings.

---

## What data the app collects

### Account data
- Email address and password (used for sign-in; passwords are hashed and never visible to us). We may also send occasional emails about Cojoin, such as new features or a newsletter. Every such email has an unsubscribe link, and the sign-up screen says this before you create an account.
- Your name and phone number, if you add them to your profile
- A profile photo, if you add one. It is resized on your device and stored in private cloud file storage. Authorized viewers receive temporary access links so they can see it next to your name. Removing it in Edit profile deletes the file.

**Where it lives:** Stored in our database (Supabase), protected by access controls. Your display name and profile photo are shared where needed for connections, events and conversations; your private account details are not publicly listed. On your phone, the sign-in session is kept encrypted: the key lives in the iOS Keychain (or Android Keystore) and the encrypted session in app storage.

You can change your email or password in Settings → Account. Both ask for your current password first; an email change is confirmed by links sent to both your old and your new address.

### Friends data
- Names, phone numbers, interests, and notes for the friends you add
- Hangout logs (date, activity type, optional memory note)
- Streaks, health scores, and flake logs

**Where it lives:** Synced to our database and cached on your device for offline use. This data is private to your account — other users cannot see your friends list.

### Contacts
If you choose **Import from contacts**, Cojoin asks for access to your address book and shows it to you on your device so you can pick people. Only the people you tick are saved — their name and phone number become entries in your friends list (above). The rest of your address book is never read into the app's storage, uploaded, or matched against other users. You can add friends without ever granting contacts access.

### Invites and connections
Friend connections are made with single-use invite links or QR codes. A link contains a random token tied to your account; when a friend opens it, the two accounts are connected and each of you gets the other's display name. Links expire after 7 days. Opening a link in a browser shows a short page on cojoin.io that hands off to the app; that page does not set cookies or collect anything.

### Messages and vibe posts
- Direct messages you send to other Cojoin users
- "Vibe" posts (what you're up to, when, and an optional photo) and who's visible to see them
- If you paste an event link (for example a Partiful, Luma or Eventbrite page) into a vibe, your phone fetches that page directly to read its title, time, place and cover image; the link, place and cover-image address are saved with the vibe and shown to its audience. Cojoin does not proxy or log the request.
- Message and vibe content is visible to the people you're messaging or sharing with, consistent with what you post and who you choose to share it with

**Where it lives:** Stored in our database. Vibe photos are stored in cloud file storage.

### Post-event check-ins and recaps
When a host enables a post-event check-in, invited guests and attendees can save a next-time reaction and optional date choices. The host can see who responded and their reaction; other guests see aggregate interest and date counts. Guests who explicitly decline can read that event’s chat and photos after it ends; this does not rejoin them to the chat. Events created before this feature keep their existing audience rules.

Private event notes submitted through earlier app versions remain private to the host, with no sender name or account ID shown to the host. Cojoin retains the account link for abuse handling and deletion; authorized safety reviewers can review reported notes and their senders. Event notes and responses are stored in our database and removed when the associated event or account is deleted. Opening a next-event draft never publishes it automatically.

### Location
Location sharing is **off until you turn it on** (Profile or Settings → Share my location, or the toggle during onboarding). When it is on, the app asks for while-in-use location permission and stores a **coarse** position — rounded to roughly 1 km — together with a neighbourhood label and a timestamp. It is shown only to friends you are connected with who also share theirs, on the Discover screen's "Near me". Your exact coordinates are never stored, and turning sharing off removes your stored position. Nothing in the app depends on location; every other feature works with it off.

Separately, the Suggestions screen looks up your approximate city from your IP address (ipapi.co) to show weather context for a suggested plan. That request is made from your device directly; Cojoin does not store or log your IP address or location from it.

### Camera
Cojoin requests camera access to scan a friend's QR code from the add-a-friend sheet, and photo-library access to attach a photo to a vibe or plan if you choose to. Photos you don't choose to attach are never captured or stored.

### Automated safety screening
Cojoin checks new content for abuse so people can see posts and messages right away. When you post a vibe, add a photo, send a message or change your profile name or photo, that content is visible to its audience immediately and is screened shortly afterwards. By default the text and any image are sent to OpenAI's moderation service, which returns only a safety classification and does not keep or train on the content; nothing else about you is sent. Content that is flagged, or that someone reports, is hidden and reviewed by a person on the Cojoin team, who can remove it or restrict the account. You can turn automated screening off in Settings; your content then goes only to human review. Appeals and report outcomes are under Settings → My reports.

### Notifications
If you grant notification permission, Cojoin can send server push notifications about messages, connections and events, and schedule local reminders on your device. Device push tokens and notification preferences are stored in Supabase. Push delivery uses Expo and Apple or Google notification services. Push payloads contain routing identifiers; message text is included only when you enable previews. You can change notification categories, previews and sounds in Settings and mute individual conversations.

### Feedback
If you submit feedback or a bug report from Settings → Help (or Profile → Send feedback), your message, account reference, optional reply email, app version and device type are stored in a restricted support queue in Supabase. Authorized team members review these submissions in the Safety inbox; submitting the form does not automatically send an email. Feedback is used to improve the app and respond to support requests.

Choosing “Or email us” or “Contact support” opens your mail app addressed to edwardroh89@gmail.com. If the in-app form cannot save, it offers the typed message in your mail app instead. You choose whether to send it. Email correspondence is also held by the email providers used by you and the support team; our support mailbox is hosted by Google (Gmail). The optional reply-email field in the form does not itself send a message or subscribe you to a mailing list.

---

## What the app does NOT do

- No advertising, no ad identifiers, no ad tracking
- No selling or sharing your data with third parties for their own purposes
- No analytics beyond what's needed to keep the app running reliably

---

## Reporting and blocking

You can report or block anyone who messages you directly from a chat thread. Blocking prevents that person from messaging you again; you can review and undo blocks anytime under Settings → Blocked. Reports are stored in our database for review. To follow up on a report or appeal a decision, contact the support address below.

---

## Third-party services

| Service | Purpose | Privacy policy |
|---|---|---|
| Supabase | Account, database, and file storage (photos) | https://supabase.com/privacy |
| Event sites you paste (Partiful, Luma, Eventbrite, …) | Fetched by your phone to fill in a vibe from a link; their images are loaded from their servers when the vibe is shown | Their own policies |
| ipapi.co | City-level location from IP, for weather context only | https://ipapi.co/privacy |
| Open-Meteo | Weather forecast | https://open-meteo.com/en/terms |
| OpenAI (moderation API) | Automated safety classification of new posts, photos, messages and profile details; on by default, can be turned off in Settings | https://openai.com/policies/privacy-policy |
| Expo | Delivers push notifications using device tokens and notification payloads | https://expo.dev/privacy |
| Apple / Google | Deliver notifications to iOS / Android devices | https://www.apple.com/legal/privacy/ / https://policies.google.com/privacy |
| Google (Gmail) | Hosts the support mailbox when you choose to email us or receive a support reply | https://policies.google.com/privacy |
| Vercel | Hosts cojoin.io (this page and the invite hand-off page) | https://vercel.com/legal/privacy-policy |

---

## Data deletion

Go to Settings → Delete Account to permanently delete your account, friends list, hangout history, messages, vibe posts, photos, shared location and invite links. This cannot be undone. Signing out (instead of deleting) keeps your data intact for when you sign back in.

---

## Children

Cojoin is not directed at children under 13 and does not knowingly collect data from children.

---

## Changes to this policy

If this policy changes, the updated version will be posted at this URL. The "last updated" date at the top will reflect the change.

---

## Contact

Questions? Use Settings → Help → Send feedback in the app, or email edwardroh89@gmail.com.

---

*The published version served to users and App Store reviewers is https://cojoin.io/privacy (generated from this file). The app repository keeps a copy; keep both in sync when this changes.*
