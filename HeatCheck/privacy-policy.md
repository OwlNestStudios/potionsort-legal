# Heat Check — Privacy Policy

**Last updated: November 2, 2026**

Heat Check is a food and training tracker made by OwlNest Studios ("we", "us"). This policy explains what the app stores, where it goes, and how to delete it. Heat Check has no ads and no tracking, and we never sell or share your data for marketing.

## What Heat Check stores on your phone

Everything you log stays in one data file on your phone:

- **Food:** what you type about your meals, the calories and macros (protein, carbs, fat), portions and any numbers you edit, plus the estimate notes and questions that come back.
- **Training:** the exercises you log (sets, reps, weight), custom exercises, workout sessions, activities and your workout plan.
- **Body:** bodyweight weigh-ins, if you use them.
- **Goals and settings:** your daily macro targets and app settings (units, day start time, reminders, sound and haptics).
- **Smart-estimate usage:** a record of each smart estimate the app asks for (token counts and estimated cost).

Times are stored with your phone's time zone offset so your days stay correct. Heat Check doesn't collect your name, contacts, location, photos or advertising IDs.

## Smart estimates (Claude)

Heat Check first answers from a food and exercise guide built into the app; that never leaves your phone. When it needs more, you can ask for a **smart estimate** from Claude, an AI model from Anthropic. Smart estimates need you to be signed in (see below).

- The app sends your meal description and the time you logged it (for example "Thursday 12:35 PM") to **our server**. For a custom exercise that isn't built in, it sends the exercise's name.
- Our server runs on Unity Cloud Code. It forwards the request to Anthropic's Claude API using our own key, so you don't need an Anthropic account or key. The app itself never contacts Anthropic, and there is no Claude key on your phone.
- When a restaurant chain is named, Claude may search the web for that chain's official nutrition information.
- Anthropic handles those requests under [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy).
- Meals you enter yourself ("Enter numbers myself"), re-logged meals, and meals the built-in guide can answer are never sent anywhere.

**What our server keeps about your account**, tied to your Unity player ID and never including the text of your meals:

- whether you're signed in, the time of your first smart estimate, and your plan (Free or Beta) with its start and cancel dates;
- each month's counts and estimated cost of smart estimates (meals, exercises, searches, tokens);
- for each smart estimate, a saved answer (item names and notes, but not what you typed) in a small fixed set of slots that newer answers overwrite, so a reply that didn't reach your phone can be replayed instead of asked again;
- a counter of calls in the current minute, used to limit abuse.

We use these only to run the app, enforce each plan's monthly limit, keep our own costs under control, and see overall use. We can read these numbers per account.

## Plans

Heat Check has a **Free** plan and a **Beta** plan (free during the beta; it allows more smart estimates each month). We don't take payment details or sell anything inside the app today. If that changes, this policy will say so first.

## Services that receive your data

Heat Check sends data to two outside companies. It sends nothing anywhere else.

### Unity Technologies: sign-in, backup and our server

- **Unity Authentication** gives the app an anonymous player ID and a random installation ID the first time you open it. No account or personal information is needed for that.
- **Unity Player Accounts:** if you choose **Sign in** (in Settings ▸ App settings ▸ Account & backup, or when a smart estimate asks), you sign in with a Unity Player Account on Unity's sign-in page, and your anonymous player is linked to that account. Unity receives the sign-in details needed to run the account, such as your email address. Heat Check reads that email only to show which account you're signed in to; it is kept on your phone, not in the backup file. The sign-in keeps a refresh token on your phone until you sign out or erase.
- **Unity Cloud Save:** while you're signed in, Heat Check uploads a compressed copy of your data file (everything under "What Heat Check stores on your phone") to Cloud Save, stored under your player account, so you can restore your logs after a reinstall or on a new phone.
- **Unity Cloud Code and Remote Config** run our server functions and read our own settings (limits, plan options). Cloud Code also keeps the records listed under "What our server keeps about your account".

Unity processes this data under the [Unity Privacy Policy](https://unity.com/legal/privacy-policy). Questions about Unity Player Accounts can also go to Unity at [unity-player-login-privacy@unity3d.com](mailto:unity-player-login-privacy@unity3d.com). Unity may also process basic technical data (such as your device type and app version) as part of running its services.

### Anthropic (Claude): smart estimates

Described above. Anthropic receives only what a smart estimate needs, and it comes from our server, not directly from your phone.

All connections from the app to our server, Unity and Anthropic use encrypted HTTPS.

## Other things the app does on your phone

- **Export my data** writes a CSV of your full history to the phone's temporary storage and hands it to the app you pick. It stays until the next export or until you use Erase this phone.
- **Reminders** are notifications scheduled on your phone, with your macro numbers in the text. Nothing about them is sent anywhere. Heat Check asks for the notification permission, the exact-alarm setting and to restart after a reboot so they stay on time.
- **Rest timer** runs a short foreground notification while a rest counts down. It stays on the phone.
- **Watch a demo ›** (exercise guide) opens a YouTube search for "<exercise name> exercise form" in the YouTube app or your browser, so the exercise's name (custom names too) is sent to YouTube when you tap it.

## Your phone's own backups

Heat Check turns off Android's automatic backup and device-to-device transfer, so your phone's system backup (such as Android backup to your Google account) does not include Heat Check's data file. The only backup is the Unity cloud backup described above, which you control; after a reinstall or on a new phone, sign in to restore it.

## How long data is kept

Your logs are kept for as long as you keep them. Heat Check is built to keep long-term history, so nothing is deleted automatically.

- **On your phone:** until you erase it or uninstall the app.
- **In the cloud backup:** until you use **Erase phone + backup**, or delete your Unity Player Account.
- **On our server** (plan, monthly counts, saved answers): until you ask us to delete it (see below). Saved answers are overwritten by newer ones.

## Deleting your data

You can delete most of it yourself, at any time, in Settings ▸ App settings ▸ Your data:

- **Erase this phone…** deletes all Heat Check data from this phone and signs you out. Your cloud backup stays, and comes back if you sign in again.
- **Erase phone + backup…** also deletes your cloud backup. This can't be undone. If you're signed in on another device, erase there too, or that device will back its copy up again.
- **Delete your Unity Player Account** at [player-account.unity.com/delete-account](https://player-account.unity.com/delete-account). This deletes the account itself.
- **Uninstalling** Heat Check removes the data from your phone. It doesn't delete your cloud backup.

**What Erase does not delete today:** the records on our server (your plan, monthly counts and saved answers, described above). To have those deleted, and your cloud backup too if you can't reach the app, **email OwlNestStudios@gmail.com** from the address on your Unity account, or with your player ID, and ask us to delete your Heat Check data. We'll delete the records on our server and in Cloud Save within 30 days, and ask Unity to delete the account if you also want that. We may keep a short record that a deletion was done. For anything sent to Anthropic, see Anthropic's privacy policy.

## Health

Heat Check is a logging tool, not medical advice. Estimates are approximate. Talk to a doctor or registered dietitian before changing your diet or training, especially with a health condition.

## Children

Heat Check is for people 18 and over. It isn't meant for children, and we don't knowingly collect data from them.

## Changes to this policy

If this policy changes, we'll update it here and change the "Last updated" date above. If the app ever collects anything new, this policy will say so first.

## Contact

Questions or requests about your data: OwlNestStudios@gmail.com

OwlNest Studios
