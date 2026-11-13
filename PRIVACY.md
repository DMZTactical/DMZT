# DMZ Tactical privacy policy

Last updated: 10 November 2026 · [Lietuviškai](PRIVACY.lt.md)

DMZ Tactical is an independent, free companion app for Call of Duty DMZ. This policy explains what data the app and our Discord server handle, why, and how to remove it.

Contact for privacy requests: **dmztacticaltool@gmail.com**

## Summary

* No account is needed. Without one, the map, plans, loot lists and settings stay on your computer. If you sign in, your raid plans, Orders progress and Loot List are also kept in your account, so they are the same on your other computers.
* There are no ads. The app sends no analytics unless you turn on **Anonymous statistics** in Settings (off by default). The website has none.
* Squad search is optional. Only the players the server puts in your squad see your Activision ID, playstyle and portrait.
* DMZ Tactical never reads game files, game memory or your inventory.
* You can delete your account in the app at any time.

## Without an account

Without an account, the map, raid plans, loot lists, weapon builds and settings are stored only on your computer (your Windows user profile, or the Mac app's data on a Mac). They are not sent to us.

To check for and download updates, the app contacts GitHub. GitHub receives your IP address as part of that request ([GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)).

To get map, item and mission updates between app versions, the app downloads a signed data pack from dmzt.app, which is hosted on Cloudflare. Cloudflare receives your IP address as part of that request; the request carries no account, profile or plan data.

DMZ Tactical does not read or change game files, game memory or your inventory. It has no ads, and it sends nothing about how you use it unless you turn on anonymous statistics.

## Anonymous statistics (optional)

Off by default. If you turn on **Anonymous statistics** in the app's Settings, the Windows app sends:

* daily totals of a few steps: the app started (counted once a day), signed in, operator saved or refused, squad search joined, squad formed;
* short error messages from the app, with numbers, email addresses and links removed before they are sent;
* the app version.

No player, Discord or Activision ID, no install ID and no IP address is stored with it. It goes to Supabase in the EU and helps us find bugs (GDPR Art. 6(1)(a), your consent). Turn it off in Settings at any time; nothing more is sent after that.

## With an account (squad search and sync)

An account is optional. It is used for squad search and to keep your plans on all your computers. You sign in with Discord, and we store:

* **From Discord:** your Discord user ID, username, avatar and email address. Discord shares the email address at every Discord sign-in through our sign-in provider. We don't show it to anyone or use it to contact you.
* **Your operator profile:** Activision ID, portrait choice, playstyle, region, language and microphone preference.
* **Your plans and Loot List:** raid plans (name, route, goals, keys and checklist), Orders progress, and Loot List goals and amounts, so they are the same on your other computers. A raid in progress and the stops you visited stay on the computer you play on.
* **While you search:** your language, region, Duo or Trio, Discord voice choice and a queue entry that the app renews while it is running.
* **Your squad:** its members, their Ready answers and, for voice squads, a link to the voice channel on our Discord server.
* **Players you block:** so the server does not put them in your squad again.
* **Reports you send:** the reason you chose, your and the reported player's Discord user IDs, their Activision ID and the squad. Our Discord moderators see the report in a private staff channel.

Players in the queue do not see each other. When the server forms a squad, only its members see your Activision ID, playstyle and portrait. When you stop searching or close the app, your queue entry is removed within 90 seconds.

We check the Activision ID format only. DMZ Tactical never signs in to your Activision account.

Your sign-in is kept on your computer: on Windows encrypted by Windows (DPAPI) for your Windows user only, on a Mac in your login keychain.

## Discord server and bot

If you use our Discord server, the DMZ Tactical bot stores:

* the Activision ID you enter with `/activisionid`, which it syncs to your account;
* marketplace listings, including your Activision ID (the bot tells you it will be public before you post);
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

* to provide squad search, plan sync and the Discord features you choose (GDPR Art. 6(1)(b));
* to keep support conversations and protect the service (Art. 6(1)(f)).

We don't sell data or share it for advertising.

## How long we keep it

| Data | Kept |
| --- | --- |
| Account and profile | Until you delete them |
| Synced plans and Loot List | Until you delete them or your account; a removed entry is kept 90 days so your other computers remove it too |
| Queue entries | 90 seconds after the app last renewed them; up to 30 minutes for `/findsquad` |
| Squads and their voice channel links | 1 hour |
| Blocked players | Until you delete your account |
| Reports about squad members | 30 days |
| Anonymous statistics | 90 days |
| Closed ticket archives | 12 months, then deleted |
| Bot database backups | Replaced daily; the last three copies are kept |

## This website

The [DMZ Tactical website](https://dmzt.app/) is hosted on Cloudflare Pages. It has no analytics or ads and sets no cookies of its own. Cloudflare processes your IP address to deliver the pages and filter bots, and it may set a strictly necessary security cookie for that ([Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)).

## Delete your data

* **In the app:** open **Account settings**, choose **Delete account** and confirm. This removes your account, operator profile, synced plans and Loot List, stored Activision ID, queue entry and the players you blocked. The copies on your computers stay.
* **Discord bot data:** open a ticket with `/ticket` or email dmztacticaltool@gmail.com. We answer within 30 days.

## Your rights

You can ask for:

* access to your data or a copy of it;
* correction or deletion of your data.

You can also object to how your data is used.

You can complain to a data protection authority. In Lithuania, that is the State Data Protection Inspectorate ([vdai.lrv.lt](https://vdai.lrv.lt)).

## Changes

We publish changes to this policy on the website, in this repository and in our Discord server.

---

[Website](https://dmzt.app/privacy/) · [Download page](README.md) · [Discord](https://discord.gg/PzCZNqmybB)
