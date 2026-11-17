# DMZ Tactical privacy policy

Last updated: 17 November 2026 · [Lietuviškai](PRIVACY.lt.md)

DMZ Tactical is an independent, free companion app for Call of Duty DMZ. This policy explains what data the app and our Discord server handle, why, and how to remove it.

Contact for privacy requests: **dmztacticaltool@gmail.com**

## Summary

* No account is needed. Without one, the map, plans, loot lists and settings stay on your computer. If you sign in, your raid plans, Orders progress, Loot List, saved weapon loadouts and Loadout sets, Operator Traits build and the FOB upgrades, recipes and weapon manuals you mark in Progress are also kept in your account, so they are the same on your other computers.
* There are no ads. The app sends no analytics unless you turn on **Anonymous statistics** in Settings (off by default). The website has none.
* The DMZT Assistant saves your chats only after you agree, without your name or IDs. You can delete them with **Delete my chats**.
* Squad search is optional. Only the players the server puts in your squad see your Activision ID, playstyle and portrait.
* DMZT EXP, the leaderboard and DMZT SOCIAL are optional. Only players signed in on dmzt.app see them, and you can hide yourself from the leaderboard.
* DMZ Tactical never reads game files, game memory or your inventory.
* You can delete your account in the app or on dmzt.app at any time.

## Without an account

Without an account, the map, raid plans, loot lists, weapon builds and settings are stored only on your computer (your Windows user profile, or the Mac app's data on a Mac). They are not sent to us.

To check for and download updates, the app contacts GitHub. GitHub receives your IP address as part of that request ([GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)).

To get map, item and mission updates between app versions, the app downloads a signed data pack from dmzt.app, which is hosted on Cloudflare. Cloudflare receives your IP address as part of that request; the request carries no account, profile or plan data.

DMZ Tactical does not read or change game files, game memory or your inventory. It has no ads, and it sends nothing about how you use it unless you turn on anonymous statistics or agree to save your DMZT Assistant chats.

## Anonymous statistics (optional)

Off by default. If you turn on **Anonymous statistics** in the app's Settings, the Windows app sends:

* daily totals of a few steps: the app started (counted once a day), signed in, operator saved or refused, squad search joined, squad formed;
* short error messages from the app, with numbers, email addresses and links removed before they are sent;
* the app version.

No player, Discord or Activision ID, no install ID and no IP address is stored with it. It goes to Supabase in the EU and helps us find bugs (GDPR Art. 6(1)(a), your consent). Turn it off in Settings at any time; nothing more is sent after that.

## DMZT Assistant chats (beta)

The DMZT Assistant answers questions about items, recipes, keys, bosses and locations from DMZT game data. It is a beta and understands English only. Before your first message it asks you to agree that we save your chats. Without agreeing you can't write to it. If you agree, we store for each question:

* your question and the assistant's answer, with email addresses, links and long numbers (like phone numbers) removed before they are sent and again on our server;
* the topic it recognised (for example an item or a recipe) and your Yes/No rating, if you give one;
* a random chat ID made in your browser, where you asked (the app, the map or dmzt.app), the app version and the time.

The chat ID is not linked to your account, Discord or Activision ID, and no IP address is stored with it. Don't write personal details, passwords or account info in the chat. We read the chats to find questions the assistant can't answer yet and to improve its answers. They are stored in Supabase in the EU (GDPR Art. 6(1)(a), your consent).

To stop, choose **Delete my chats** under the chat and confirm. This deletes the chats saved from that browser or app and asks for your agreement again before the next message.

## With an account (squad search and sync)

An account is optional. It is used for squad search and to keep your plans on all your computers. You sign in with Discord, and we store:

* **From Discord:** your Discord user ID, username, avatar and email address. Discord shares the email address at every Discord sign-in through our sign-in provider. We don't show it to anyone or use it to contact you.
* **Your operator profile:** Activision ID, portrait choice, playstyle, region, language and microphone preference.
* **Your plans, lists and builds:** raid plans (name, route, goals, keys, Loadout slots and checklist), Orders progress, Loot List goals and amounts, saved weapon loadouts (name, weapon and attachments), saved Loadout sets (name and slots), your Operator Traits build and the FOB upgrades, 3D Printer recipes and weapon manuals you mark in Progress, so they are the same on your other computers. A raid in progress and the stops you visited stay on the computer you play on.
* **While you search:** your language, region, Duo or Trio, Discord voice choice and a queue entry that the app renews while it is running.
* **Your squad:** its members, their Ready answers and, for voice squads, a link to the voice channel on our Discord server.
* **Players you block:** so the server does not put them in your squad again.
* **Reports you send:** the reason you chose, your and the reported player's Discord user IDs, their Activision ID and the squad. Our Discord moderators see the report in a private staff channel.

Players in the queue do not see each other. When the server forms a squad, only its members see your Activision ID, playstyle and portrait. When you stop searching or close the app, your queue entry is removed within 90 seconds.

We check the Activision ID format only. DMZ Tactical never signs in to your Activision account.

Your sign-in is kept on your computer: on Windows encrypted by Windows (DPAPI) for your Windows user only, on a Mac in your login keychain, and on dmzt.app in this browser's local storage until you sign out.

## DMZT EXP, leaderboard and DMZT SOCIAL

With an account, we also keep:

* **DMZT EXP:** the tasks you completed and when (a daily visit to dmzt.app, a squad found, and what the Discord bot reports: help in #mission-help, a #raid-highlights post, a trade posted or completed), the EXP for each, your level and the card background you choose. Your rank and level show next to your name in the app, on the F8 squad screen, in DMZT SOCIAL and as a role on our Discord server. Your level also shows next to your trades.
* **Leaderboard:** players signed in on dmzt.app see your Discord display name, operator portrait, level and EXP for the week, the month and all time. You can hide yourself from the leaderboard; your new ranks then stay out of DMZT SOCIAL too.
* **DMZT SOCIAL:** the posts you write (up to 280 characters and one picture), the GG you give, the players you follow and the reports you send (the post and the reason). If you have a DMZT account, the Discord bot also adds your #marketplace listings and finished trades and your #raid-highlights posts (the text and a link to the first picture on Discord). A post deleted on Discord or a removed listing is taken back. New ranks appear in the feed too.

Only players signed in on dmzt.app see DMZT SOCIAL and the leaderboard. Visitors who are not signed in get none of this data. Pictures you add are stored in Supabase Storage in the EU, in a private folder that only signed-in players can read. Three reports hide a post until an admin reviews it.

## Discord server and bot

If you use our Discord server, the DMZ Tactical bot stores:

* the Activision ID you enter with `/activisionid`, which it syncs to your account;
* marketplace listings, including your Activision ID (the bot tells you it will be public before you post). While a listing is open, the bot copies only the trade (items, amounts, language, dates and the link to the post, without your name or IDs) to Supabase, so the app and dmzt.app can show it. With a DMZT account, the listing and the finished trade also appear in DMZT SOCIAL with your name, rank and level;
* with a DMZT account, the text and the first picture link of your #raid-highlights posts, for DMZT SOCIAL;
* your DMZT rank, shown as a role on the server;
* trade alert settings;
* closed support tickets, including messages and attachments, in a private archive;
* while you queue with `/findsquad`: your queue entry in the same squad queue as the app, and a private voice channel for your squad that is removed once it is empty.

## Where data is stored and why

| Data | Stored with |
| --- | --- |
| Account data | [Supabase](https://supabase.com/privacy), in the EU |
| Anonymous statistics (if turned on) | [Supabase](https://supabase.com/privacy), in the EU |
| Bot data | Sparked Host, in Paris, France |

We use your data:

* to provide squad search, plan sync, DMZT EXP, the leaderboard, DMZT SOCIAL and the Discord features you choose (GDPR Art. 6(1)(b));
* to keep support conversations and protect the service (Art. 6(1)(f)).

We don't sell data or share it for advertising.

## How long we keep it

| Data | Kept |
| --- | --- |
| Account and profile | Until you delete them |
| Synced plans, lists and builds | Until you delete them or your account; a removed entry is kept 90 days so your other computers remove it too |
| Queue entries | 90 seconds after the app last renewed them; up to 30 minutes for `/findsquad` |
| Squads and their voice channel links | 1 hour |
| Blocked players | Until you delete your account |
| DMZT EXP, level and card background | Until you delete your account |
| DMZT SOCIAL posts with their pictures, GG, follows and reports | Until you delete them or your account |
| Discord trades and highlights in DMZT SOCIAL | Until the Discord post or listing is removed, or you delete your account |
| Reports about squad members | 30 days |
| Anonymous statistics | 90 days |
| DMZT Assistant chats | 90 days |
| Closed ticket archives | 12 months, then deleted |
| Bot database backups | Replaced daily; the last three copies are kept |

## This website

The [DMZ Tactical website](https://dmzt.app/) is hosted on Cloudflare Pages. It has no analytics or ads and sets no cookies of its own. Cloudflare processes your IP address to deliver the pages and filter bots, and it may set a strictly necessary security cookie for that ([Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)).

## Delete your data

* **In the app or on dmzt.app:** in the app open **Account settings**, on dmzt.app open **DMZT SOCIAL**, **My profile**, **Account**; choose **Delete account** and confirm. This removes your account, operator profile, synced plans, lists and builds, stored Activision ID, queue entry, the players you blocked, your DMZT EXP and everything of yours in DMZT SOCIAL, including the pictures in your posts. The copies on your computers stay.
* **One post in DMZT SOCIAL:** open the post's menu and choose **Delete**. Its picture is deleted with it.
* **DMZT Assistant chats:** choose **Delete my chats** under the chat and confirm. This deletes the chats saved from that browser or app.
* **Discord bot data:** open a ticket with `/ticket` or email dmztacticaltool@gmail.com. We answer within 30 days.

## Your rights

You can ask for:

* access to your data or a copy of it;
* correction or deletion of your data.

You can also object to how your data is used.

In the app, **Account settings**, **Data**, **Download** saves a copy of the plans, lists, builds and profile your account keeps as a JSON file; on dmzt.app, **DMZT SOCIAL**, **My profile**, **Account**, **Download** does the same and adds your EXP, leaderboard choice and DMZT SOCIAL posts.

You can complain to a data protection authority. In Lithuania, that is the State Data Protection Inspectorate ([vdai.lrv.lt](https://vdai.lrv.lt)).

## Changes

We publish changes to this policy on the website, in this repository and in our Discord server.

---

[Website](https://dmzt.app/privacy/) · [Download page](README.md) · [Discord](https://discord.gg/PzCZNqmybB)
