# Heat Check — Privacy Policy

**Last updated: October 31, 2026**

Heat Check is a food and training tracker made by OwlNest Studios ("we", "us"). This policy explains what the app stores, where it goes, and how to delete it. Heat Check has no ads, no analytics and no tracking, and we never sell or share your data for marketing.

## What Heat Check stores

Everything you log stays in one data file on your phone:

- **Food:** what you type about your meals, the calories and macros (protein, carbs, fat), portions and any numbers you edit, plus Claude's estimate notes and questions.
- **Training:** the exercises you log (sets, reps, weight), custom exercises, workout sessions and your workout plan.
- **Body:** bodyweight weigh-ins, if you use them.
- **Goals and settings:** your daily macro targets and app settings (units, day start time, reminders, sound and haptics).
- **Claude usage:** a record of each call the app makes to Claude (token counts and estimated cost), so the app can show what you've spent.

Times are stored with your phone's time zone offset so your days stay correct. Heat Check doesn't collect your name, contacts, location, photos or advertising IDs.

## Your Claude API key

To estimate meals, Heat Check uses your own Anthropic (Claude) API key, which you paste in Settings.

- On Android the key is encrypted with a key held in the Android Keystore and saved in a folder that phone backups never copy.
- It's never synced, never included in the cloud backup, and never written to the data file. After a reinstall you enter it again.
- It's only ever sent to Anthropic, to authorize the app's requests.

## Services that receive your data

Heat Check sends data to two outside services. It sends nothing anywhere else.

### Anthropic (Claude): meal estimates

When you choose **Estimate with Claude**, the app sends your meal description to Anthropic's Claude API, along with the time the meal was logged (for example "Thursday 12:35 PM"). When you add a custom exercise that isn't built in, the app sends the exercise's name so Claude can assign its muscles. When a restaurant chain is named, Claude may search the web for that chain's official nutrition information.

These requests are made with **your** API key, under **your** agreement with Anthropic. How Anthropic handles them is covered by [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy) and the terms of your Anthropic account. Meals you enter yourself ("Enter numbers myself"), re-logged meals, and meals matched to one you logged before are never sent to Claude.

### Unity Technologies: sign-in and cloud backup

Heat Check uses Unity Gaming Services to back up your logs:

- **Unity Authentication** gives the app an anonymous player ID the first time you open it. No account or personal information is needed for that.
- **Unity Player Accounts:** if you choose **Sign in to back up**, you sign in with a Unity Player Account (for example with Google or Apple), and your anonymous player is linked to that account. Unity receives the sign-in details needed to run that account, such as your email address. Heat Check reads that email from the sign-in only to show which account you're backed up to; the email is kept on your phone, not in the backup file.
- **Unity Cloud Save:** while you're signed in, Heat Check uploads a compressed copy of your data file (everything listed under "What Heat Check stores", but never your Claude API key) to Cloud Save, stored under your player account. This lets you restore your logs after a reinstall or on a new phone.

Unity processes this data under the [Unity Privacy Policy](https://unity.com/legal/privacy-policy). Questions about Unity Player Accounts can also go to Unity at [unity-player-login-privacy@unity3d.com](mailto:unity-player-login-privacy@unity3d.com).

All connections to Anthropic and Unity use encrypted HTTPS.

## Your phone's own backups

Heat Check turns off Android’s automatic backup and device-to-device transfer, so your phone’s system backup (such as Android backup to your Google account) does not include Heat Check’s data file or your Claude API key. The only backup is the Unity cloud backup described above, which you control; after a reinstall or on a new phone, sign in to restore it.

## How long data is kept

Your logs are kept for as long as you keep them. Heat Check is built to keep long-term history, so nothing is deleted automatically.

- **On your phone:** until you erase it or uninstall the app.
- **In the cloud backup:** until you use **Erase phone + backup**, or delete your Unity Player Account.

## Deleting your data

You can delete everything yourself, at any time, in Settings ▸ App settings ▸ Your data:

- **Erase this phone…** deletes all Heat Check data and your Claude API key from this phone, and signs you out. Your cloud backup stays, and comes back if you sign in again.
- **Erase phone + backup…** also deletes your cloud backup. This can't be undone. If you're signed in on another device, erase there too, or that device will back its copy up again.
- **Delete your Unity Player Account** at [player-account.unity.com/delete-account](https://player-account.unity.com/delete-account). This deletes the account itself.
- **Uninstalling** Heat Check removes the data and the API key from your phone. It doesn't delete your cloud backup.

For anything sent to Anthropic, see your Anthropic account and Anthropic's privacy policy.

## Children

Heat Check isn't meant for children under 13, and we don't knowingly collect data from them.

## Changes to this policy

If this policy changes, we'll update it here and change the "Last updated" date above. If the app ever collects anything new, this policy will say so first.

## Contact

Questions or requests about your data: OwlNestStudios@gmail.com

OwlNest Studios
