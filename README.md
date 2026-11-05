<p align="center"><img src="media/reveal-hero.svg" width="100%" alt="DMZ Tactical. Tactical intel for Hajin. Public beta."></p>

<p align="center"><strong>English</strong> &nbsp; · &nbsp; <a href="README.lt.md">Lietuvių</a></p>

<p align="center"><strong>DMZ Tactical</strong> is a Windows companion for <strong>Call of Duty DMZ on Hajin</strong>.<br><em>Plan the raid, find what you need, bring a squad.</em></p>

<p align="center">
<a href="https://discord.gg/PzCZNqmybB"><img src="media/discord-en.svg" width="288" alt="Join the DMZ Tactical Discord community"></a>
<a href="https://github.com/DMZTactical/DMZT/releases/download/v0.9.15-beta.1/DMZTactical-Installer.exe"><img src="media/download-en.svg" width="288" alt="Download DMZTactical-Installer.exe for Windows"></a>
<a href="https://github.com/DMZTactical/DMZT/releases/tag/v0.9.15-beta.1"><img src="media/release-notes-en.svg" width="288" alt="Read the beta release notes"></a>
</p>

## What it does

| Feature | What you get |
| --- | --- |
| **Hajin map** | Every key, location and grid square, searchable and available offline. |
| **Raid planning** | Objectives, stops, keys and a loadout in one plan that follows you into the raid. |
| **Loot list** | Items, recipes and base upgrades with shared ingredients added up for you. |
| **Equipment** | Weapon Meta rankings and builds, plus Operator Traits planning. |
| **Squad search** | Find players in your language and invite them in the game. |
| **In-game overlay** | Press F8 to see your route, loot, map and squad search on top of the game, and edit the route in raid. |

## Hajin, in detail

Search for a **key**, a **location** or a **grid square**. Bring the relevant layers into view, inspect commanders and points of interest, then mark the places you intend to visit. The full map is bundled with the app and **works offline**.

- **Hot Zones** shows estimated PvP areas with a short explanation of the risk.
- **UAV** gives you an optional camera orbit around a selected map marker.

Both can be switched off. *Hot Zones is an estimate; it does not track players or active exfils.*

![The HAJIN map and start screen in DMZ Tactical](media/reveal-map.jpg)

## Give every stop a purpose

**My plan** puts objectives, destinations, keys and a weapon loadout together before deployment. Once the raid starts, the view switches to the tasks and stops that remain. Keep separate preparations for different runs, and return to an unfinished raid without rebuilding the plan.

- **DMZ Orders** keeps mission steps and partial progress together.
- The **pinned raid window** puts your checklist beside the game or on a second monitor. You mark the progress; changes are carried back to the main plan.
- The **in-game overlay** opens with F8 over a Borderless or Windowed game. A second press leaves a small tracker in the corner while the mouse stays in the game.

## Find it. Bring it back.

Build a **loot list** from items, crafting recipes and base upgrades. Shared ingredients are added together, so you can see at a glance what you need, what you already have and what is still missing.

Open any item for **acquisition advice**, **map links** and available **reference photos**. Quantities stay saved between raids. *Your game inventory is never read.*

![Military Composites with acquisition advice and a linked commander location](media/reveal-find.jpg)

## Choose your equipment and traits

**Weapon Meta** brings weapon rankings, attachment builds and your saved loadouts into one catalogue. Review a build and add it straight to your plan. *Recommendations are community sourced and can change with game updates.*

**Operator Traits** covers **Warfighter**, **Scout** and **Survivalist**. Browse the trees, plan within the points you have earned and save a build for later. Minor examples and unconfirmed reservations stay separate from the traits you have actually received.

<table>
<tr><td width="50%"><img src="media/reveal-weapons-detail.jpg" alt="HAN 86 attachment build in Weapon Meta"></td><td width="50%"><img src="media/reveal-traits-detail.jpg" alt="Operator Traits reference with three trait trees"></td></tr>
<tr><td align="center"><sub>Weapon Meta</sub></td><td align="center"><sub>Operator Traits</sub></td></tr>
</table>

## Find a squad

Get into a raid with players who speak your language, in three steps:

1. **Sign in with Discord.** Other players see a real person, not a throwaway account.
2. **Enter your Activision ID.** Teammates use it to invite you in the game. You can also set it with `/activisionid` in our Discord server.
3. **Find a squad.** See each player's operator, callsign and playstyle, and copy their ID to send an invite.

> [!NOTE]
> Only players who are searching themselves can see other searchers. Stop searching, close the window or change the language, and you leave the list within 60 seconds. The ID format is checked; ownership of the Activision account is not.

## See the app in action

[![Watch the DMZ Tactical beta reveal on YouTube](media/reveal-film.svg)](https://www.youtube.com/watch?v=TBih6NpHspg)

## Install

1. Download **DMZTactical-Installer.exe** from the button above.
2. Close DMZ Tactical if it is running, then follow Windows Setup.
3. Choose **English** or **Lithuanian** in **Settings**.

The map, loot list and raid planning work **without an account**. Squad search needs a Discord sign-in.

> [!TIP]
> **Already have the beta?** Open **Settings** and choose **Check for updates**.

If the app opens but the map stays blank, Windows is missing Microsoft WebView2.

<a href="https://developer.microsoft.com/microsoft-edge/webview2/#download"><img src="media/webview2-en.svg" width="288" alt="Map not loading? Install Microsoft WebView2"></a>

<details>
<summary><strong>Requirements and beta details</strong></summary>

<br>

**Requirements**

- Windows x64, with administrator approval for installation.
- Microsoft Edge WebView2. Setup tries to install it if it is missing.
- An internet connection for downloads, squad search, account features and updates.

**Good to know**

- The installer is not Authenticode signed, so Windows may show an *Unknown Publisher* notice. Updates are checked against the app's signed manifest and file hashes.
- For the pinned raid window, use a second monitor or play in windowed or borderless mode. Exclusive fullscreen may cover it.
- The **Build your own** weapon editor is temporarily hidden. Previously saved custom loadouts are kept.
- DMZ Tactical is a planning companion. It does not read the game process, track live player positions or change in-game traits. Map notes and community advice can change as the game does.
- For a fresh install you only need **DMZTactical-Installer.exe**. The NUPKG file is used for in-app updates. GitHub's *Source code* archives contain this download page only; the application source is kept private.

</details>

<sub>Independent community companion. Not affiliated with or endorsed by Activision or Infinity Ward. Game names, map imagery and game artwork belong to their respective owners.</sub>
