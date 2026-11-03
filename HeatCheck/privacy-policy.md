# Heat Check — Privacy Policy

**Last updated: November 2, 2026**

Heat Check is a food and training tracker made by OwlNest Studios ("we", "us"). This policy explains what the app stores, where it goes, and how to delete it. Heat Check has no ads, no advertising IDs and no analytics tools of its own, and we never sell or share your data for marketing.

## What Heat Check stores on your phone

Everything you log stays in one data file on your phone:

- **Food:** what you type about your meals, the calories and macros (protein, carbs, fat), portions and any numbers you edit, plus the estimate notes and questions that come back.
- **Training:** the exercises you log (sets, reps, weight), custom exercises, workout sessions, activities and your workout plan.
- **Body:** bodyweight weigh-ins, if you use them.
- **Goals and settings:** your daily macro targets and app settings (units, day start time, reminders, sound and haptics).
- **AI estimate usage:** a record of each AI estimate the app asks for (token counts and estimated cost).

Times are stored with your phone's time zone offset so your days stay correct. Heat Check doesn't ask for your name, contacts, location, photos or advertising IDs.

## AI estimates

Heat Check first answers from a food and exercise guide built into the app. Answers from the guide are worked out on your phone and aren't sent anywhere. When the guide can't answer and you're signed in, the app sends the meal to our server for an **AI estimate**, automatically, with no extra tap. The AI model is provided by Anthropic. AI estimates need you to be signed in (see below). If you'd rather not use them, don't sign in, or enter the numbers yourself.

- The app sends your meal description and the time you logged it (for example "Thursday 12:35 PM") to **our server**. For a custom exercise that isn't built in, it sends the exercise's name.
- Our server runs on Unity Cloud Code. It forwards the request to Anthropic using our own key, so you don't need an Anthropic account or key. The app itself doesn't contact Anthropic, and there is no Anthropic key on your phone.
- When a restaurant chain is named, the AI may search the web for that chain's official nutrition information. That search runs through Anthropic.
- Anthropic handles those requests under [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy).
- Meals you enter yourself ("Enter numbers myself"), meals you log again, and meals the built-in guide answers aren't sent for an AI estimate.

**What our server keeps about your account**, tied to your Unity player ID. It doesn't keep the text of your meals, **except in a problem report you choose to send** (see below):

- whether you're signed in, the time of your first AI estimate, and your plan (Free or Beta access) with its start and end dates;
- each month's counts and estimated cost of AI estimates (meals, exercises, searches, tokens), the times of your first and last estimate in the month and when you reached your limit. Records older than about 13 months are removed the next time you get an AI estimate in a new month; if you stop using AI estimates, your last months stay until you delete your account;
- for each AI estimate, a saved answer (item names and notes, but not what you typed) and a one-way fingerprint of the request, so a reply that didn't reach your phone can be replayed instead of asked again. A saved answer replays for 10 minutes. It is removed when you next ask for a billed estimate, when you use Erase phone + backup, or when you delete your account;
- a counter of calls in the current minute, used to limit abuse;
- **possibly a one-way hash of the email address you sign in with**, when Unity shares that address with the app. We don't use it to find accounts today. A hash can't be turned back into your address, but it is still personal data: anyone holding it who guessed your address could confirm the guess;
- **problem reports you send** (see below).

We use these only to run the app, enforce each plan's monthly limit, keep our own costs under control, answer deletion requests, and see overall use. We can read these numbers per account.

### Problem reports

An AI meal estimate and an AI-assigned exercise have a **Report a problem** link. If you use it, the app shows you exactly what will be sent and waits for you to tap Send. A report holds the **meal text or exercise name as you typed it**, the AI estimate you were shown, the reason you picked, your optional note, the app version and the time. Reports are sent only by you, one at a time. We keep your newest 20 until you delete your account. **Erase phone + backup does not remove them; Delete account does.** We read them to fix wrong estimates.

## Plans

Heat Check has a **Free** plan and **Beta access** (free, for invited testers; it allows more AI estimates each month). We don't take payment details or sell anything inside the app. If that changes, this policy will say so first.

## Services that receive your data

Heat Check's own network requests go to these companies and no others (links you tap, such as the privacy policy, simply open in your browser):

### Unity Technologies: sign-in, backup and our server

- **Unity Authentication** gives the app an anonymous player ID and a random installation ID. The app asks for them when you first sign in, back up or ask for an AI estimate, not before. No account or personal information is needed for that.
- **Unity Player Accounts:** if you choose **Sign in** (in Settings ▸ App settings ▸ Account & backup, or when an AI estimate asks), you sign in with a Unity Player Account on Unity's sign-in page, and your anonymous player is linked to that account. Unity receives the sign-in details needed to run the account, such as your email address. Heat Check reads that email to show which account you're signed in to, and sends our server its one-way hash (see above); the address itself is kept on your phone and isn't in the backup file. The sign-in keeps a refresh token on your phone until you sign out or erase.
- **Unity Cloud Save:** while you're signed in, Heat Check uploads a compressed copy of your data file (everything under "What Heat Check stores on your phone") to Cloud Save, stored under your player account, so you can restore your logs after a reinstall or on a new phone.
- **Unity Cloud Code and Remote Config** run our server functions and read our own settings (limits, plan options). Cloud Code also keeps the records listed under "What our server keeps about your account".

Unity processes this data under the [Unity Privacy Policy](https://unity.com/legal/privacy-policy). Questions about Unity Player Accounts can also go to Unity at [unity-player-login-privacy@unity3d.com](mailto:unity-player-login-privacy@unity3d.com). Unity may also process basic technical data (such as your device type and app version) as part of running its services.

### Anthropic: AI estimates

Described above. Anthropic receives what an AI estimate needs (the meal description or exercise name and the time), and it comes from our server, not directly from your phone. Web searches the AI makes for a chain's nutrition information go through Anthropic.

### YouTube: only when you tap Watch a demo

**Watch a demo ›** (exercise guide) opens a YouTube search for "<exercise name> exercise form" in the YouTube app or your browser, so the exercise's name (custom names too) is sent to YouTube when you tap it. Nothing is sent to YouTube otherwise.

Connections from the app to our server and Unity use encrypted HTTPS.

## Other things the app does on your phone

- **Export my data** writes a CSV of your full history to the phone's temporary storage and hands it to the app you pick. It stays until the next export or until you use Erase this phone.
- **Reminders** are notifications scheduled on your phone, with your macro numbers in the text. Nothing about them is sent anywhere. Heat Check asks for the notification permission when you turn Reminders on, and restarts them after you reboot your phone. Reminders use Android's flexible timing, so they can arrive up to about an hour after their time.
- **Rest timer** runs a short foreground notification while a rest counts down. It runs only while a timer you started is counting down, and stays on the phone.

## Your phone's own backups

Heat Check turns off Android's automatic backup and device-to-device transfer, so your phone's system backup (such as Android backup to your Google account) does not include Heat Check's data file. The only backup is the Unity cloud backup described above, which you control; after a reinstall or on a new phone, sign in to restore it.

## How long data is kept

Your logs are kept for as long as you keep them. Heat Check is built to keep long-term history, so nothing in your log is deleted automatically. Deleting a single meal, exercise or activity in the app hides it, but it stays in your data file and your cloud backup (so the deletion can sync between your devices) until you use Erase this phone, Erase phone + backup or Delete account.

- **On your phone:** until you erase it or uninstall the app.
- **In the cloud backup:** until you use **Erase phone + backup** or **Delete account**, or delete your Unity Player Account.
- **On our server:** your account record and plan (and a one-way email hash, if one was sent), until you delete your account; monthly usage counts, records older than about 13 months removed as described above; saved answers, replayed for 10 minutes and then removed at your next billed estimate, at Erase phone + backup or at Delete account (someone who stops using the app keeps the last few until they delete); problem reports, the newest 20 until you delete your account.

## Deleting your data

In Settings ▸ App settings ▸ Your data:

- **Delete account…** removes everything we keep about you: the records on our server (plan, usage counts, saved answers, any email hash and problem reports), your cloud backup file and your Unity player, then clears this phone. It can't be undone. Do this in the app first: deleting only your Unity sign-in on Unity's site leaves our records in place.
- **Erase this phone…** deletes all Heat Check data from this phone and signs you out. Your account and backup stay, and your logs come back if you sign in again.
- **Erase phone + backup…** also deletes your cloud backup and your saved answers. This can't be undone. Your account, plan, usage counts and any problem reports you sent stay; Delete account removes them. If you're signed in on another device, erase there too, or that device will back its copy up again.
- **Uninstalling** Heat Check removes the data from your phone. It doesn't delete your cloud backup or our records.
- **Your Unity Player Account** can also be deleted at [player-account.unity.com/delete-account](https://player-account.unity.com/delete-account).

**If you've lost your phone or can't use the app.** Delete account works from any phone: install Heat Check on another phone, sign in with the same Unity account (your logs come back), then use Settings ▸ App settings ▸ Your data ▸ **Delete account…**. That is the way to delete your account. We can't promise to find an account from an email address alone, so a request sent by email may not be something we can act on. If you can't do the above, write to OwlNestStudios@gmail.com anyway and tell us what happened, and we'll do what we can. We may keep a short record that a deletion was done. For anything sent to Anthropic, see Anthropic's privacy policy.

If you delete your account and sign up again, you start as a new user with a new allowance.

## Health

Heat Check is a logging tool, not medical advice. Estimates are approximate. Talk to a doctor or registered dietitian before changing your diet or training, especially with a health condition.

## Children

Heat Check is for people 18 and over. It isn't meant for children, and we don't knowingly collect data from them.

## Changes to this policy

If this policy changes, we'll update it here and change the "Last updated" date above. If the app ever collects anything new, this policy will say so first.

## Contact

Questions or requests about your data: OwlNestStudios@gmail.com

OwlNest Studios
