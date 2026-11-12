# WoW Forever Addons

A growing collection of addons by **Deathbringer98** for WoW Forever, covering questing help, inventory convenience, easy healing, animated portraits, map customization, dungeon maps, rare alerts, spell suggestions, talent guidance, a minimap button for every addon, and in-game games, including a mech battle you can play against bots or other players. Free and open source under the [GPL-3.0](LICENSE).

## My own spin on familiar addons

Many of these addons cover ideas that already exist in one form or another: quest helpers, click-to-heal frames, rare alerts, rotation helpers, minimap skins and so on. These are my own takes on those ideas, made for WoW Forever, and in some ways I have tried to improve on them, for example with clickable buttons instead of chat commands, settings anyone can find, and help built in for new players.

Except for QuestiePlus, they are written from scratch rather than copied from those addons. QuestiePlus is the one direct fork: it is built on Questie's code, with fixes and new features added, and it credits the Questie team.

## Addons and downloads

Download individual addons below, or use **Code > Download ZIP** to get the whole collection.

| Addon | What it does | Package version | Download |
| --- | --- | --- | --- |
| **BetterWorldMap / Gatherer** | Reveals unexplored map areas and marks flight points, ore, herbs, and skinnable beasts. | 1.0.1 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/BetterWorldMapGatherer-1.0.1.zip) |
| **Casty** | Suggests the next spell to cast with a glowing box, for every class, and switches between PvE and PvP on its own. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/Casty-1.0.0.zip) |
| **DungeonGuide** | Maps of every dungeon and raid with every boss marked on them. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/DungeonGuide-1.0.0.zip) |
| **Easy Heals** | Click-to-heal frames made for new healers: click a name to heal it, with a key that shows every click. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/EasyHeals-1.0.0.zip) |
| **Forever Addon Hub** | One minimap button that fans out a ring of buttons for every addon in this collection. Click one to open it, or get the download link for ones you do not have. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/ForeverAddonHub-1.0.0.zip) |
| **ForeverOneBag** | Combines your backpack and equipped bags into one inventory window. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/ForeverOneBag.zip) |
| **Gnomish Grudge Match** | Gnomes against goblins: build a battle mech from salvage, then watch it fight with real 3D mechs. Play bots, challenge other players, and let your group or guild watch. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/GnomishGrudgeMatch-1.0.0.zip) |
| **Living Portraits** | Replaces flat unit frame portraits with live, animated 3D heads in the style of Warcraft III. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/LivingPortraits-1.0.0.zip) |
| **QuestiePlus** | An improved version of the original Questie: quest helper with bug fixes for WoW Forever, a suggested quest route drawn on your map, a level-up planner, quest chain tooltips, and more. **QuestieDB is included** in the download. | 1.1.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/QuestiePlus-1.1.0.zip) |
| **Rare Alert** | Warns you when a rare mob shows up near you and lists your zone's rares with their spawn spots. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/RareAlert-1.0.0.zip) |
| **SexierMap** | A map appearance and customization addon. | 2.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/SexierMap-2.0.0.zip) |
| **Shift-Click Returns** | Shift-click a player's name to invite them to your group or guild, whisper, add as a friend, look up, or copy. | 1.1.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/Shift-Click_returns-1.1.0.zip) |
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

### Casty

Suggests the next spell to cast. The suggested spell gets a glowing box in two places: a suggestion box with the spell's icon, key binding, and the next two spells, and a glow on the action bar button that holds it.

- Rotations for all nine classes, each talent tree, and both PvE and PvP: 54 priority lists, with every spell name checked against WoW Forever's spells.
- On Auto, it uses the PvP rotation in battlegrounds, arenas, and against enemy players, and the PvE rotation everywhere else. PvP lists lead with control and burst.
- In PvE it uses Blizzard's own rotation helper first when the game offers one for your class.
- Healing trees get their class's damage spells, since an addon cannot see who needs healing.
- Every setting is a button: style (Auto, PvE, PvP), talent tree, Blizzard helper, action bar glow, suggestion box, lock, size, and minimap button.

**Open it:** click the blue sparkle on the minimap, pick Casty from the minimap addon menu, or type `/casty`.

**What it can see:** in combat WoW Forever hides mob debuffs, real cooldowns, health, and your resources from addons. Casty times your damage over time, buffs, and cooldowns from your own casts, shows procs only while the game makes the spell glow, and shows Overpower, Revenge, Execute, and similar spells only when the game says they can be cast. It cannot see resists, dispels, or a target's health. Rotations are plain lists in `Rotations.lua` that anyone can edit. Automated mock checks pass for all nine classes; **in-game validation is still pending**.

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

### Easy Heals

Healing made easy for new players. Your group shows up as shiny health bars, and you heal someone by clicking their name: no targeting, no macros, nothing to set up.

- **Click to heal:** left-click a name to heal that player. Right, middle, Shift, Ctrl, and Alt clicks give your other heals, shields, cures, and resurrection. Priest, Paladin, Druid, and Shaman are set up out of the box, and spells you have not learned yet are skipped.
- **A click key:** a pink "How to heal" panel next to the bars shows every click with its spell icon, and hovering a name shows it too.
- **Flashy bars:** glossy bars that turn from green to yellow to red as health drops, a pulsing red glow on anyone below half health, faded frames for players out of range, a sparkle on every click, and a beating-heart title bar.
- **Works everywhere:** shows just you when solo, your party in a group, and a 40-player grid in a raid.
- **Welcome guide:** a short guide pops up the first time and explains everything.
- Every setting is a button: lock frames, click key, health %, hover help, size, and minimap button.

**Open settings:** click the heart on the minimap, the `*` on the title bar, or type `/eh`.

**How it plays by the rules:** WoW Forever hides your party's health from addons as a number. Easy Heals never reads it: the bars, percent, colours, and red glow are drawn by the game's own widgets, which may show hidden values. Healing uses secure unit buttons, the same kind Blizzard's own frames use. Automated mock checks pass; **in-game validation is still pending**.

---

### Forever Addon Hub

All your addons from this collection, one click away on the minimap.

- **One button:** click the gear on the minimap and a ring of buttons fans out around the minimap, one for each addon here.
- **Open anything:** click a button to open that addon. Some also do something on right-click, like BetterWorldMap opening the world map or Living Portraits toggling the big portrait. Hover a button to see what it does.
- **Find what you are missing:** addons you have not installed show faded. Click one for its download link, ready to copy.
- **Settings on right-click:** hide addons you do not have, keep the ring open after a click, or hide the hub button (`/hub` brings it back). Drag the gear to move it around the minimap.

It is a separate small addon, so you get the buttons without installing any of the games. Automated mock checks pass; **in-game validation is still pending**.

---

### ForeverOneBag

View your carried inventory in one place instead of opening separate bag windows. ForeverOneBag is designed to make browsing your backpack and equipped bags simpler.

<p align="center">
  <a href="https://github.com/user-attachments/assets/5e5df2ff-5a8b-48c1-9e70-b18de9cfa679">
    <img src="https://github.com/user-attachments/assets/5e5df2ff-5a8b-48c1-9e70-b18de9cfa679" alt="ForeverOneBag screenshot 1" width="558" />
  </a>
</p>

---

### Gnomish Grudge Match

Gnomeregan Tinkers against Venture Co. Goblins. Build a battle mech from salvage, then watch it fight it out in an arena. Fun to play and just as fun to watch.

- **Pick your side:** gnome mechs are Spider Tanks, Mechanostriders, Pounders, Steam Tonks and Alarm-o-Bots. Goblins get Venture Co. shredders and stompers.
- **The workshop:** each round you get 3 choices for each of 5 parts: chassis, arms, power core, cannon and plating. Expect things like the Shrink Ray, Death Ray, Battle Chicken, Rocket Barrage, Oil Slick, Super Sapper Charge, Arcane Shield and Kaja'Cola Injector. Hover a part to see what it does, and check the scouting report to see what your rival was offered.
- **The fight:** the mechs battle on their own, using the game's real 3D models and sounds, with rockets and bombs flying, floating damage numbers, screen shake and death animations. Watch at 1x, 2x or 4x, or skip. Best of 3 rounds wins.
- **Bots:** Apprentice Tinker (easy), Chief Mekgineer (normal) and Trade Prince (hard, tests builds against yours before choosing).
- **Play your friends:** challenge your target, a party member or anyone by name. Picks are sealed until both players lock in, so nobody can change parts after seeing yours. They need the addon too and must be on your faction.
- **Spectate:** your group, and your guild if you allow it, can watch live player matches from the lobby.
- **Records:** your wins, losses and biggest grudge are saved.

**Open it:** click the gizmo on the minimap, pick it from the minimap addon menu, or type `/grudge`. Right-click the minimap button for a quick fight against a bot.

Bot matches have been played in game. Player matches and spectating pass automated mock checks; **in-game validation of those is still pending**.

---

### Living Portraits

Gives your unit frames live 3D portraits like the ones in Warcraft III. The heads use the game's own idle animation, play a talking animation when that character speaks, and show a dead pose when the unit is dead.

- Works on the default player, target, focus, pet, target of target, and party frames.
- A unit that is too far away to be drawn keeps its normal flat portrait until it comes into view.
- `/lp big` opens a larger Warcraft III style portrait window that shows your target, or you when you have no target. Drag it to move it.

In game, type `/lp help` for the full command list. Useful ones: `/lp on`, `/lp off`, `/lp fill 0.82` (how much of the circle the head fills), `/lp talk`, and `/lp status`.
<img width="246" height="89" alt="image" src="https://github.com/user-attachments/assets/d2df76c2-a112-4be2-a35b-aacbc53e444c" />

---

### QuestiePlus

An improved version of the original [Questie](https://github.com/Questie/Questie), based on Questie 12.7.0. It does everything Questie does (quest givers, objectives and turn-ins on the map and minimap, the quest tracker, the Journey) and adds fixes and new tools for WoW Forever.

**QuestieDB is included.** QuestiePlus reads quest data from the QuestieDB addon, so the download holds two folders: `QuestiePlus` and `QuestieDB`. Copy **both** into `Interface/AddOns/`. If `QuestieDB` is missing, QuestiePlus shows as "missing dependency" in the AddOns list and won't load. The included copy is the unchanged official Forever build 1.0.15 by the Questie team (GPL-3.0, license files included); newer versions come from the [QuestieDB releases](https://github.com/Questie/QuestieDB/releases/latest).

**Turn off the original Questie.** QuestiePlus replaces it, so only one can run. If both are on, QuestiePlus offers to turn Questie off and reload for you. Settings do not carry over from Questie, because WoW stores each addon's settings separately.

New features:

- **QuestiePlus window** (type `/qp` or middle-click the minimap button):
  - **Suggested route:** the quickest order to do your quests in, starting where you stand. It goes to each objective (the nearest camp of the mobs, objects or items you need), hands each quest in once its objectives are done, and adds up to 8 nearby quests worth picking up. Every stop shows its distance and has a **Go** button that points the waypoint arrow at it, with an estimate of the total travel time. The route is also drawn on your world map as a gold line with numbered stops, updated every time you open the map. Turn the map line or the extra pick-ups off in the QuestiePlus settings.
  - **Level-up planner:** your XP bar with the XP from your finished quests stacked on top, and whether handing them in levels you up.
  - **Ready to hand in:** every finished quest with its XP and who to hand it to. The **Map** button opens the map with a waypoint on that NPC.
  - **Grey quests:** quests far below your level, each with an **Abandon** button that always asks first, to free up quest log space.
  - **Zone progress:** how many of your current zone's quests you have done, out of the ones your character can do.
- **Quest chain on hover:** hover a quest in your quest log, a quest pin on the map, or a quest in the tracker to see the follow-up quests, their XP and money, and the total for the rest of the chain.
- **Quest complete banner:** a big banner in the middle of the screen the moment you finish a quest's last objective.
- **Hide the tracker in battlegrounds:** keeps the tracker out of the way in battlegrounds and arenas but still shows it in dungeons.
- **Shift-click an objective icon** on the map to hide that objective's icons when they clutter the map. Right-click the quest in the tracker and pick **Show Icons** to bring them back.

**Version 1.1.0** fixes 1.0.0 not starting ("Questie's TOC has a missing or invalid X-QuestieDB-Contract") and adds the suggested route. If you have 1.0.0, replace the whole `QuestiePlus` folder.

Quick checklist: unzip, drag `QuestiePlus` and `QuestieDB` into `Interface/AddOns/`, turn off the original Questie if you have it, restart the game, then type `/qp`.

Fixed Questie bugs on WoW Forever:

- The "you picked up an item that starts a quest" message no longer shows when you have turned chat messages off.
- Map pins for an item a quest needs (for example the Fresh Zhevra Carcass for Ishamuhale) now disappear once you loot it.
- Changing the icon style no longer brings back those pins on quests that are already complete.
- Auto Accept no longer takes escort quests, so the NPC doesn't walk off before you are ready.
- Minimap icons now show right after a hearthstone or portal, without having to move first.
- Shift-click and ctrl-click on an NPC's patrol path now work like clicking the NPC's icon.
- Less chance of the "tried to call the protected function" error when handing in quests. This one may not be fully fixed.

All new features can be turned on or off in the new **QuestiePlus** tab of the settings (shift-click the minimap button).

**Credits and license:** Questie is made by the Questie team (Aero, Logon, Muehe, TheCrux/BreakBB, Drejjmit, Dyaxler, Cheeq, TechnoHunter, Yttrium and many others). QuestiePlus is an unofficial fork and is **not supported by the Questie team**, so please report QuestiePlus problems here, not to them. Distributed under **GPL-3.0** like the Questie code it is built on; every change is listed in the included `CHANGES.md`. QuestiePlus has its own logo, not the Questie logo. Automated mock checks pass; **in-game validation is still pending**.

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

### Shift-Click Returns

Shift-click a player's name and do something with it in one click.

- Shift-click a player's name in chat, or their target, focus, or party frame, and the name lands in a small window.
- Buttons: **Invite to group**, **Invite to guild**, **Add friend**, **Who is this?**, **Whisper** (puts a link to them in your chat window; click it to start the whisper), and **Copy name** (selects it so Ctrl+C copies it), plus **My target** and a list of the last 8 names.
- The window closes during combat. A name you shift-click mid-fight is saved and the window opens with it when the fight ends.
- If Blizzard's guild invite, Add Friend, Add Ignore, or channel invite box is open, the name goes straight into it instead.
- While you are typing in chat, shift-clicking a name still puts it into your message as normal.
- Every setting is a button: chat names, unit frames, fill invite boxes, and minimap button.

**Open it:** click the green arrow on the minimap, pick it from the minimap addon menu, or type `/scr`. Automated mock checks pass; **in-game validation is still pending**.

**Version 1.1.0:** Fixes the "has been blocked from an action only available to the Blizzard UI" message in 1.0.0, which called the game's invite, friend, and who functions directly. Each button now runs the slash command you would type yourself (`/invite`, `/ginvite`, `/friend`, `/who`), which the game allows, and Whisper no longer opens the chat box itself.

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

**QuestiePlus** comes with two folders, `QuestiePlus` and `QuestieDB`. Copy both into `Interface/AddOns/`.

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

## License

Every addon in this collection is free software under the **GNU General Public License v3.0** (GPL-3.0). The full text is in [`LICENSE`](LICENSE).

Copyright (C) 2026 Matthew Menchinton ([Deathbringer98](https://github.com/Deathbringer98)), CircuitSpecter Studio.

What this means for players and other addon makers:

- You can use these addons for free, share them, and change them.
- If you share a changed version, or an addon built on this code, it must also be released under GPL-3.0 with its source, and it must keep the credits and say what you changed.
- The addons come with no warranty.

Parts made by others keep their own credits and terms:

- **QuestiePlus** is built on [Questie](https://github.com/Questie/Questie), and its download includes the unchanged [QuestieDB](https://github.com/Questie/QuestieDB), both by the Questie team under GPL-3.0. The Questie team asks forks not to use the Questie logo, so QuestiePlus has its own. Libraries in its `Libs` folder keep their own licenses.
- **BetterWorldMap / Gatherer**, **DungeonGuide** and **Rare Alert** use spawn data from [CMaNGOS classic-db](https://github.com/cmangos/classic-db) (GPL-3.0).
- **TalentSuggester** uses talent data and builds from [talentsforever.com](https://talentsforever.com) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), which requires keeping that credit.
- Game data read from the WoW Forever client (via [wago.tools](https://wago.tools)) belongs to Blizzard Entertainment.

## About

Maintained by [Deathbringer98](https://github.com/Deathbringer98).

This is an independent addon collection and is not affiliated with or endorsed by Blizzard Entertainment.
