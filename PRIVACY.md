# Privacy Policy

**Cojoin** ("the app") is built by Andrew Nguyen. This privacy policy explains what data the app collects, where it lives, and what it does not do.

**Last updated: September 30, 2026**

---

## The short version

Cojoin requires a free account (email + password) so your friends list, hangout history, and messages stay in sync across your devices. We store your data securely and never sell it or use it for advertising. You can delete your account and everything tied to it at any time from Settings.

---

## What data the app collects

### Account data
- Email address and password (used only for sign-in; passwords are hashed and never visible to us)
- Your name and phone number, if you add them to your profile
- A profile photo, if you add one. It is resized on your device and stored in cloud file storage at a public URL, so the friends you connect with can see it next to your name. Removing it in Edit profile deletes the file.

**Where it lives:** Stored in our database (Supabase), access-controlled so only you can read your own account data. On your phone, the sign-in session is kept encrypted: the key lives in the iOS Keychain (or Android Keystore) and the encrypted session in app storage.

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

### Location
Location sharing is **off until you turn it on** (Profile or Settings → Share my location, or the toggle during onboarding). When it is on, the app asks for while-in-use location permission and stores a **coarse** position — rounded to roughly 1 km — together with a neighbourhood label and a timestamp. It is shown only to friends you are connected with who also share theirs, on the Discover screen's "Near me". Your exact coordinates are never stored, and turning sharing off removes your stored position. Nothing in the app depends on location; every other feature works with it off.

Separately, the Suggestions screen looks up your approximate city from your IP address (ipapi.co) to show weather context for a suggested plan. That request is made from your device directly; Cojoin does not store or log your IP address or location from it.

### Camera
Cojoin requests camera access to scan a friend's QR code from the add-a-friend sheet, and photo-library access to attach a photo to a vibe or plan if you choose to. Photos you don't choose to attach are never captured or stored.

### Notifications
If you grant notification permission, Cojoin schedules local reminders on your device (e.g., "You haven't seen Jordan in a while"). These are generated on-device from your synced data. Cojoin does not send push notifications from a server.

### Feedback
If you send feedback or a bug report from Settings → Help (or Profile → Send feedback), your message, the optional reply address you enter, your account email, and the app version and device type are emailed to the team through a form-to-email relay (FormSubmit) and kept in our database so nothing is lost. Feedback is used only to improve the app and reply to you.

---

## What the app does NOT do

- No advertising, no ad identifiers, no ad tracking
- No selling or sharing your data with third parties for their own purposes
- No analytics beyond what's needed to keep the app running reliably

---

## Reporting and blocking

You can report or block anyone who messages you directly from a chat thread. Blocking prevents that person from messaging you again; you can review and undo blocks anytime under Settings → Blocked. Reports are reviewed by the developer.

---

## Third-party services

| Service | Purpose | Privacy policy |
|---|---|---|
| Supabase | Account, database, and file storage (photos) | https://supabase.com/privacy |
| Event sites you paste (Partiful, Luma, Eventbrite, …) | Fetched by your phone to fill in a vibe from a link; their images are loaded from their servers when the vibe is shown | Their own policies |
| ipapi.co | City-level location from IP, for weather context only | https://ipapi.co/privacy |
| Open-Meteo | Weather forecast | https://open-meteo.com/en/terms |
| FormSubmit | Delivers in-app feedback to the team by email | https://formsubmit.co/privacy |
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

Questions? Use Settings → Help → Send feedback in the app, or email andrew.v1.win@gmail.com.

---

*The published version served to users and App Store reviewers is https://cojoin.io/privacy (generated from this file). The app repository keeps a copy; keep both in sync when this changes.*
