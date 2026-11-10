<p align="center">
<picture>
<source media="(max-width: 600px)" srcset="media/hajin-r6-hero-mobile-en.jpg">
<img src="media/hajin-r6-hero-en.jpg" width="100%" alt="DMZ Tactical: Hajin map, loot tracker and raid planner for Call of Duty: Modern Warfare 4 DMZ. Free app for Windows.">
</picture>
</p>

<p align="center"><strong>English</strong> · <a href="README.lt.md">Lietuvių</a> · <a href="https://dmzt.app/">Website</a></p>

<p align="center">
<a href="https://github.com/DMZTactical/DMZT/releases/download/v0.9.38-beta.1/DMZT.APP-Installer.exe"><img src="media/hajin-install-0-9-38-en.svg" width="330" alt="Download DMZT.APP-Installer.exe. Beta 0.9.38-beta.1 for Windows x64."></a>
<a href="https://discord.gg/PzCZNqmybB"><img src="media/hajin-community-r2-en.svg" width="330" alt="Join the DMZ Tactical community on Discord for feedback and news."></a>
<br>
<a href="https://github.com/DMZTactical/DMZT/releases/tag/v0.9.38-beta.1"><img src="media/hajin-r3-notes-en.svg" width="330" alt="Release notes on GitHub: what's new in this beta."></a>
<a href="#faq"><img src="media/hajin-r4-faq-button-en.svg" width="330" alt="FAQ: safety, price, consoles and more."></a>
</p>

# DMZ Tactical – Hajin map, loot tracker and raid planner for MW4 DMZ

**DMZ Tactical** is a free Windows companion app for **Call of Duty: Modern Warfare 4 DMZ**. Find every key, location and grid square on the **Hajin** and **X01** maps, see where each item drops, plan your raid and open it in game with **F8**. The map works offline and no account is needed.

<p align="center"><img src="https://dmzt.app/assets/img/app-map-en.webp" width="100%" alt="Hajin map in DMZ Tactical with key markers by rarity, numbered locations and Hot Zones."></p>

## Features

### Hajin and X01 map with every key
- Keys, locked doors and points of interest by rarity
- Locations, exfils, commanders and grid squares (for example B5 or F4)
- Hot Zones show where PvP fights are likely
- UAV mode gives an orbiting view of the map
- Works offline

### Find any item and where it drops
- Search an item, a key or a location
- Containers with drop rates, such as Tool Chest 1 in 52
- Add items to your loot list with the amount you need
- FOB upgrades and 3D printer crafts add their materials for you

<p align="center"><img src="https://dmzt.app/assets/img/app-find-en.webp" width="100%" alt="Item details for Military Composites: how to get it and three possible Colossus areas with grid squares."></p>

### Raid plan and F8 overlay
- Objectives, stops, keys and loadout in one raid plan
- DMZ Orders progress and a loot list that shows what you still need
- Press F8 in game to open your route, loot list and map above Call of Duty
- Search zones on a mini map. It does not show your position
- Works in Borderless or Windowed display mode

<p align="center"><img src="https://dmzt.app/assets/img/overlay.webp" width="680" alt="F8 overlay above the game showing the route, the loot list and a search zone for Alloyed Plating on the mini map."></p>

### Weapon meta, builds and Operator Traits
- Season 1 weapon tiers from Meta to D
- Long range and versatile builds with attachment unlock levels
- Operator Traits planner with points and trade-offs

## Get started

1. **Install.** Download [DMZT.APP-Installer.exe](https://github.com/DMZTactical/DMZT/releases/download/v0.9.38-beta.1/DMZT.APP-Installer.exe) and run it.
2. **Find.** Search for a key, an item, a location or a grid square.
3. **Press F8.** Set the game to Borderless or Windowed mode, then press F8 in a raid.

**Already using the beta?** Open Settings and choose **Check for updates**. If no update appears, download the installer above and run it. Your plans and settings stay.

**Map not loading?** Install [Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/#download) and start the app again.

### Requirements
- Windows 10 or 11, 64-bit, with administrator rights for the installation
- Microsoft Edge WebView2
- An internet connection for the download and updates
- Borderless or Windowed display mode for the F8 overlay

## What's next

<picture>
<source media="(max-width: 600px)" srcset="media/hajin-roadmap-1-0-r6-mobile-en.jpg">
<img src="media/hajin-roadmap-1-0-r6-en.jpg" width="100%" alt="Roadmap to 1.0, drawn as a raid route on the Hajin map from infil to exfil. 0.9.2 Weapon Builder: build your own weapons, Gunsmith prices, Season 1 weapons. 0.9.3 Squad search: one queue for the app, F8 and Discord; Duo or Trio formed for you; old and new Activision IDs. 0.9.4 Mac: DMZ Tactical on macOS, a code-signed installer and smaller updates. 0.9.5 One account: plans and lists on every PC, the same account on dmzt.app, operators and traits saved. 0.9.6 Assistant: loadout slots so you forget nothing, grab reminders in F8, and what to do next. 0.9.7 Smart raid: a route built for your items, an exfil clock and a place card in F8. 0.9.8 FOB: a stash advisor for what to sell or keep, operator MIA cost and Prestige. 0.9.9 Squad: a live shared raid plan and who carries what. 0.9.10 Live intel: live reports from players and Hot Zones from real raids. 1.0 Full release for Windows and Mac with the full assistant. Plans are subject to change.">
</picture>

<p align="center">Follow progress on <a href="https://discord.gg/PzCZNqmybB">Discord</a>.</p>

## Check your download

Open Terminal in the folder with the installer and run:

```powershell
Get-FileHash .\DMZT.APP-Installer.exe | Format-List
```

The hash must match `EE9929A611CD5958E878D94E473435738BCBBC3FB10AEA96D4728E07EBB46901`.
[SHA256SUMS.txt](https://github.com/DMZTactical/DMZT/releases/download/v0.9.38-beta.1/SHA256SUMS.txt) · [VirusTotal report](https://www.virustotal.com/gui/file/ee9929a611cd5958e878d94e473435738bcbbc3fb10aea96d4728e07ebb46901)

The installer isn't code-signed yet, so Windows SmartScreen or some antivirus apps may warn about it. Updates are verified with a signed manifest and file hashes.

## FAQ

**Is DMZ Tactical free?**
Yes. It's free to download and use. There are no ads and no paid features.

**Is it safe to use with Call of Duty?**
DMZ Tactical runs as a separate Windows app. It doesn't read or modify game files or memory, and it doesn't send input to the game. The F8 overlay is a standard window shown on top of the game. Activision hasn't reviewed DMZ Tactical, so we can't say how its security systems treat other apps.

**Which maps does it cover?**
Hajin and the X01 Exclusion Zone, with both X01 Black Site floor plans.

**Does it work with PlayStation or Xbox?**
Yes, on a Windows PC next to your console. The F8 overlay needs the game on the same PC.

**Does it read my inventory?**
No. You enter item counts yourself.

**Is there a Mac version?**
Not yet. Mac is what we are working on now (roadmap 0.9.4), and 1.0 will support Windows and Mac.

**Which languages are supported?**
English and Lithuanian. Map, item and location names stay as they appear in the game.

More answers on the [website](https://dmzt.app/#faq).

---

<sub>© 2026 DMZ Tactical. A fan-made companion app, not affiliated with, endorsed by, or sponsored by Activision Publishing, Inc. or Infinity Ward. Call of Duty® and related marks are trademarks of Activision Publishing, Inc. All game content and imagery belong to their respective owners. · [Privacy policy](PRIVACY.md) · [Licence terms](LICENSE.md)</sub>
