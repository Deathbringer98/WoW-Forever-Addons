# WoW Forever Addons

A growing collection of addons by **Deathbringer98** for WoW Forever, covering inventory convenience, animated portraits, map customization, talent guidance, and in-game entertainment.

## Addons and downloads

Download individual addons below, or use **Code > Download ZIP** to get the whole collection.

| Addon | What it does | Package version | Download |
| --- | --- | --- | --- |
| **ForeverOneBag** | Combines your backpack and equipped bags into one inventory window. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/ForeverOneBag.zip) |
| **Living Portraits** | Replaces flat unit frame portraits with live, animated 3D heads in the style of Warcraft III. | 1.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/LivingPortraits-1.0.0.zip) |
| **SexierMap** | A map appearance and customization addon. | 2.0.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/SexierMap-2.0.0.zip) |
| **TalentSuggester** | Provides guidance on talent choices while developing your character. | 1.1.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/TalentSuggester-1.1.0.zip) |
| **Warcraft Pinball** | Adds a Warcraft-themed pinball minigame to play inside WoW. | 3.0 | [Download](https://github.com/Deathbringer98/WoW-Forever-Addons/raw/refs/heads/main/WarcraftPinball_Forever_v3.0.zip) |

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
