EnglishSav Privacy Policy
Effective: 5.3.8 (November 2026)

EnglishSav works fully offline without an account. You only send data to the internet when you create an account or use an online feature.

1. Without an account
Your progress, settings, saved words and tutor chat history stay on your phone (in the app's own storage). Nothing is sent to us. The app cannot be backed up by Android's cloud backup. Exports you make are saved where you choose.

2. With an account
When you create an account we store, on our server (Cloudflare Workers and Cloudflare D1):
- your username, and your password as a salted hash (we never see or keep the password itself) and a hashed recovery key;
- your synced learning progress and settings;
- your public profile, if you add one: bio, emoji, photo, and the stats you choose to show;
- who you follow and block, and reports you send or receive;
- daily usage counters for the AI tutor, pronunciation check and AI voice (kept 7 days);
- network (IP) counters used only to stop abuse and password guessing (kept about 48 hours, or longer for networks you signed in from).

3. Online features and the companies that process data
- AI tutor: the messages you send (and recent chat turns) go to Google Gemini or Cloudflare Workers AI to write a reply. They are not stored on our server.
- Pronunciation check: a short recording of your voice and the target sentence go to Google Gemini. The recording is not stored on our server.
- AI voice: the text to read aloud goes to ElevenLabs or Cartesia. The audio is cached on our server so the same phrase is not generated twice; it contains no account information.
- Neural voice (on-device): the voice model is downloaded once from Hugging Face and jsDelivr. Speech is generated on your phone.
Google may use content sent through its free Gemini tier to improve its products, and human reviewers may read it. Do not type personal information into the tutor.

4. Who can see your data
Other users can see your username and your public profile. The app's administrator can see account names, profiles, reports and usage counts to moderate the service and keep it running. We do not sell your data and show no ads.

5. Deleting your data
In the app: Profile, then Delete account. This removes your account, progress, profile, photo, follows, blocks, reports and usage counters from our server at once. You can also ask for deletion through the EnglishSav GitHub page. Data you keep on your phone is removed when you clear the app's data or uninstall it.

6. Security
All connections use HTTPS. Passwords are hashed with PBKDF2. No method is perfectly secure, so use a password you do not use elsewhere.

7. Changes and contact
We will update this policy in the app and on the EnglishSav GitHub page when something changes. Questions: open an issue on the EnglishSav GitHub page, or use the creator link in About.
