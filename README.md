# WoW Forever Addons

A growing collection of addons by **Deathbringer98** for WoW Forever, covering inventory convenience, animated portraits, map customization, dungeon maps, talent guidance, and in-game entertainment.

## Addons and downloads

Download individual addons below, or use **Code > Download ZIP** to get the whole collection.

| Addon | What it does | Package version | Download |
| --- | --- | --- | --- |
| **BetterWorldMap / Gatherer** | Reveals unexplored map areas and marks flight points, ore, herbs, and skinnable beasts. | 1.0.1 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/BetterWorldMapGatherer-1.0.1.zip) |
| **DungeonGuide** | Maps of every dungeon and raid with every boss marked on them. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/DungeonGuide-1.0.0.zip) |
| **ForeverOneBag** | Combines your backpack and equipped bags into one inventory window. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/ForeverOneBag.zip) |
| **Living Portraits** | Replaces flat unit frame portraits with live, animated 3D heads in the style of Warcraft III. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/LivingPortraits-1.0.0.zip) |
| **Rare Alert** | Warns you when a rare mob shows up near you and lists your zone's rares with their spawn spots. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/RareAlert-1.0.0.zip) |
| **SexierMap** | A map appearance and customization addon. | 2.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/SexierMap-2.0.0.zip) |
| **TalentSuggester** | Provides guidance on talent choices while developing your character. | 1.1.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/TalentSuggester-1.1.0.zip) |
| **Warcraft Pinball** | Adds a Warcraft-themed pinball minigame to play inside WoW. | 3.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/WarcraftPinball_Forever_v3.0.zip) |
| **Warcraft Tetris** | A falling-blocks puzzle game you play inside WoW. Open it from the minimap button or with `/tetris`. | 1.1.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/WarcraftTetris-1.1.0.zip) |

### BetterWorldMap / Gatherer

Adds a world-map panel with switches for unexplored map artwork, flight points, ore, herbs, and skinnable beasts.

- Reveal data covers 84 map artworks from Forever's client data.
- Ore and herb markers have a clickable legend to hide individual node types.
- Beast markers show level ranges and skinning requirements, with a **Near my level** filter.
- Flight points can be filtered by faction. Hover flight and beast markers for details.
- Marker size is adjustable, and settings are saved between sessions.

**Commands:** `/bwm` shows help; `/bwm status` shows settings. Toggle layers with `/bwm reveal`, `/bwm flights`, `/bwm ore`, `/bwm herbs`, or `/bwm beasts`. Use `/bwm both` for both factions, `/bwm level` for the beast level filter, `/bwm size 1.2` to resize markers, and `/bwm showall` to restore hidden node types.

**Install:** Extract the ZIP and copy only the `BetterWorldMapGatherer` folder into `World of Warcraft/_forever_/Interface/AddOns/`. Restart the client and enable **BetterWorldMap / Gatherer**. The ZIP also includes developer tools and regression tests; only the addon folder belongs in `Interface/AddOns/`.

**Version 1.0.1:** Fixes map reveal artwork covering node, beast, and flight markers by keeping their frame order above the exploration pins, including after map refreshes. Regression mocks check changing frame levels/strata and unchanged node counts when reveal is toggled. Also includes the earlier marker texture-path fix. The Elwynn test now uses Forever's artwork ID and draws 18 reveal tiles. Lua 5.1 syntax and automated mock checks pass; **in-game validation is still pending**.

**Data and license:** Map overlays and flight points were extracted from Forever client tables via wago.tools. Ore, herb, and beast positions derive from [CMaNGOS classic-db](https://github.com/cmangos/classic-db); this addon is distributed under **GPL-3.0**, as stated in its included README. These spawn locations describe the original game and may differ in Forever. A node marker indicates a possible spawn, not a currently available resource.

---

### DungeonGuide

A dungeon atlas. Pick any dungeon or raid to see its map floor by floor, with every boss marked by a numbered pin that matches the boss list beside it.

- Full maps for 26 classic dungeons and raids, from Ragefire Chasm to Naxxramas. The maps are the game's own dungeon map art, loaded from the client files; no images are shipped.
- Multi-floor dungeons get a button per floor. A boss on another floor shows that floor's name; click it to jump there.
- Dungeons that are new in WoW Forever have no map in the game files yet, so they show a boss list only.
- Some bosses have no pin, such as event and summoned bosses, and the Upper Blackrock Spire bosses, which are not drawn on the Blackrock Spire maps.

**Commands:** `/dg` opens the guide on the dungeon you are in. `/dg deadmines` opens a dungeon by name, `/dg auto` opens the guide whenever you enter a dungeon, and `/dg help` lists the commands.

**Data and license:** Dungeon and boss lists come from Forever client tables via wago.tools. Boss positions derive from [CMaNGOS classic-db](https://github.com/cmangos/classic-db) spawn points; this addon is distributed under **GPL-3.0**, as stated in its included README. Positions describe the original game, and in dungeons with stacked floors a few bosses may show on the wrong floor. Automated mock checks pass; **in-game validation is still pending**.

---

### ForeverOneBag

View your carried inventory in one place instead of opening separate bag windows. ForeverOneBag is designed to make browsing your backpack and equipped bags simpler.

<p align="center">
  <a href="https://github.com/user-attachments/assets/5e5df2ff-5a8b-48c1-9e70-b18de9cfa679">
    <img src="https://github.com/user-attachments/assets/5e5df2ff-5a8b-48c1-9e70-b18de9cfa679" alt="ForeverOneBag screenshot 1" width="558" />
  </a>
</p>

---

### Living Portraits

Gives your unit frames live 3D portraits like the ones in Warcraft III. The heads use the game's own idle animation, play a talking animation when that character speaks, and show a dead pose when the unit is dead.

- Works on the default player, target, focus, pet, target of target, and party frames.
- A unit that is too far away to be drawn keeps its normal flat portrait until it comes into view.
- `/lp big` opens a larger Warcraft III style portrait window that shows your target, or you when you have no target. Drag it to move it.

In game, type `/lp help` for the full command list. Useful ones: `/lp on`, `/lp off`, `/lp fill 0.82` (how much of the circle the head fills), `/lp talk`, and `/lp status`.
<img width="246" height="89" alt="image" src="https://github.com/user-attachments/assets/d2df76c2-a112-4be2-a35b-aacbc53e444c" />

---

### Rare Alert

Warns you the moment a rare mob shows up near you, so you can find it and kill it first.

- An alert banner shows the rare's name, level, and zone, with the raid warning sound, big warning text, a flashing taskbar icon, and a chat line.
- Banner buttons: **Target it** targets the rare for you, **Map pin** marks where it was spotted, and **Dismiss** closes the banner.
- Rares are spotted by their nameplates (turn on enemy nameplates with V), your target, your mouseover, and minimap markers. It knows 323 open-world rares and also catches anything the game marks as rare, so rares new in WoW Forever are caught too.
- The zone panel lists every known rare in your zone with its level, the distance and direction to its nearest spawn spot, when you last saw it, and a **Pin** button. Right-click a rare to ignore it.
- Every setting is a button: Alerts, Sound, Screen flash, Chat line, Minimap button, and Test alert.

**Open it:** click the star button on the minimap, pick Rare Alert from the minimap addon menu, or type `/rare`. Alerts only work out of combat, because the game hides who a mob is from addons while you fight.

**Data and license:** The rare list and spawn spots derive from [CMaNGOS classic-db](https://github.com/cmangos/classic-db); this addon is distributed under **GPL-3.0**, as stated in its included README. Zone shapes come from Forever client data via wago.tools. Spawn spots describe the original game and may differ in Forever. Automated mock checks pass; **in-game validation is still pending**.

---

### SexierMap

Customize the look of your map interface. SexierMap focuses on the visual side of the UI for players who want a different map presentation.

<p align="center">
  <a href="https://github.com/user-attachments/assets/fdfe0edb-0a08-4489-82e0-335c91535c77">
    <img src="https://github.com/user-attachments/assets/fdfe0edb-0a08-4489-82e0-335c91535c77" alt="SexierMap screenshot 1" width="131" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/user-attachments/assets/b1341f79-9136-4a5a-8203-3a1d7bb048af">
    <img src="https://github.com/user-attachments/assets/b1341f79-9136-4a5a-8203-3a1d7bb048af" alt="SexierMap screenshot 2" width="509" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/user-attachments/assets/a581afd2-c803-4e37-a7b4-8b69607d41d6">
    <img src="https://github.com/user-attachments/assets/a581afd2-c803-4e37-a7b4-8b69607d41d6" alt="SexierMap screenshot 3" width="485" />
  </a>
</p>

---

### TalentSuggester

A talent-choice helper for planning your character's progression. TalentSuggester focuses on recommendations to help you decide where to spend talent points.
# In game type /tsug to open addon.

Talent data and build picks come from [talentsforever.com](https://talentsforever.com), used under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

<p align="center">
  <a href="https://github.com/user-attachments/assets/e5806a9b-aab3-4454-933b-157f33222105">
    <img src="https://github.com/user-attachments/assets/e5806a9b-aab3-4454-933b-157f33222105" alt="TalentSuggester screenshot 1" width="720" />
  </a>
</p>

---

### Warcraft Pinball

Take a break with a Warcraft-themed pinball game inside the client. The project includes flipper-and-ball gameplay, scoring, bumpers, lanes, and themed targets and effects. Version 3.0 focuses on improved ball physics, launch consistency, and a more readable interface.

<p align="center">
  <a href="https://github.com/user-attachments/assets/e824e011-60e1-4ba9-8099-a38b0342db9b">
    <img src="https://github.com/user-attachments/assets/e824e011-60e1-4ba9-8099-a38b0342db9b" alt="Warcraft Pinball screenshot 1" width="560" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/user-attachments/assets/9c5c65b5-8b92-41bf-8d2e-91c2be4801d2">
    <img src="https://github.com/user-attachments/assets/9c5c65b5-8b92-41bf-8d2e-91c2be4801d2" alt="Warcraft Pinball screenshot 2" width="178" />
  </a>
</p>

---

### Warcraft Tetris

A falling-blocks puzzle game in its own window. Click the Tetris button on the minimap, pick it from the minimap addon menu, or type `/tetris` to play.

- 10 x 20 board with a hold slot and a preview of the next three pieces.
- Pieces come in shuffled sets of seven, turn with standard wall kicks, and wait half a second before locking.
- Pieces fall faster every 10 lines. Scoring rewards multi-line clears, combos, and back-to-back four-line clears, and your best score is saved.
- Each piece is coloured for a school of magic or a faction: Frost, Holy, Arcane, Fel, Fire, Alliance, and Horde.
- Entering combat closes the window and pauses the game, so your keys come straight back.

**Keys:** arrows or WASD to move, Down to soft drop, Up or X to turn, Z to turn back, Space to hard drop (and start), C or Shift to hold, P to pause, Esc to close. Keys the game does not use, like Enter for chat, still work as normal.

**Buttons:** every setting is a button, so no commands are needed. The left side of the window has Start / Pause, Preview on/off, Sound on/off, Minimap on/off, and Center window. New game sits at the top left, and your best score and games played show on the right. Drag the minimap button to move it around the minimap.

**Commands (optional):** `/tetris` opens or closes the game, `/tetris new` starts a new game, `/tetris ghost` toggles the drop preview, `/tetris sound` toggles sounds, `/tetris minimap` toggles the minimap button, and `/tetris best` shows your records.

**Version 1.1.0:** adds the setting buttons, the minimap button, the minimap addon menu entry, and a games-played counter.

Lua 5.1 syntax and automated mock checks pass; **in-game validation is still pending**. Tetris is a trademark of The Tetris Company; this fan-made game is not affiliated with or endorsed by The Tetris Company or Blizzard Entertainment.

---

## Installation

1. Close your WoW Forever client.
2. Download the ZIP for the addon you want from the table above.
3. Extract it and locate the actual addon folder containing its `.toc` file.
4. Copy that folder into your client's `Interface/AddOns/` directory. Keep the internal folder name and its files together.
5. Start the client, open **AddOns** at character selection, and enable the addon.

The correct layout is `Interface/AddOns/<AddonName>/<AddonName>.toc`, with the addon's other files alongside it. Avoid an extra enclosing download folder.

**Downloading the entire repository?** Extract the repository ZIP first, then extract each individual addon ZIP you want to install. Copy the extracted addon folders into `Interface/AddOns/`; the ZIP files themselves are not installable addons.

## Updating

Close the client, back up your existing addon folder, and replace it with the newly extracted version. Keep your `WTF` folder if you want to preserve saved settings. Follow any additional instructions included in the addon package.

## Compatibility

This collection is intended for **WoW Forever**. Check each package's `.toc` file and included documentation for its client requirements, controls, and configuration options. Versions in the table reflect the uploaded filenames; ForeverOneBag's ZIP does not specify a version.

Compatibility with other WoW clients is not guaranteed. Package availability here does not indicate that every addon has been tested on every client build.

## Growing the collection

This README is the index for the addons currently available in this repository. Whenever an addon is added or updated, update this README alongside it:

- Add or replace the addon package.
- Update its download link, version, and description.
- Document new features, verified commands, and any special installation steps.
- Remove links to packages that are no longer included.

## Bug reports and suggestions

[Open an issue](https://github.com/Deathbringer98/WoW-Forever-Addons/issues) with the addon name, version, your client version, steps to reproduce the problem, and any Lua error message. Include a screenshot when it helps explain a UI issue.

## About

Maintained by [Deathbringer98](https://github.com/Deathbringer98).

This is an independent addon collection and is not affiliated with or endorsed by Blizzard Entertainment.
