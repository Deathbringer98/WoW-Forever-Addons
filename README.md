# WoW Forever Addons

A growing collection of addons by **Deathbringer98** for WoW Forever, focused on quality of life, style, and entertainment.

## Addon collection

The descriptions below summarize the addons developed for this collection. **The addon files have not been uploaded to this repository yet.** Downloads and verified command references will be added alongside the source files.

| Addon | Purpose | Package version | Repository status |
| --- | --- | --- | --- |
| Warcraft Pinball | A WoW-themed pinball minigame to play in-game. | 3.0 | Upload pending |
| ForeverOneBag | Combines your backpack and equipped bags into one bag window for easier inventory browsing. | Not yet verified | Upload pending |
| FelPath | A warlock leveling helper designed to suggest a quest order based on the quests you have. | 1.0.0 | Upload pending |

### Warcraft Pinball

An in-game pinball addon built around a Warcraft theme. The project focuses on flipper-and-ball gameplay, bumpers and lanes, scoring, and themed targets and effects. Version 3.0 was prepared with improvements to ball physics, launch consistency, and readability.

### ForeverOneBag

A quality-of-life addon that presents your carried inventory in one window. Its goal is to make checking and managing bag contents easier without opening each bag separately.

### FelPath

A leveling guide for warlocks, designed around a quest-based to-do list and suggested quest order. Exact route coverage, supported levels, and commands will be documented after the packaged source is checked. It should not be treated as a verified complete leveling route yet.

## Installation

Once addon files are available here:

1. Download the addon package you want, or choose **Code > Download ZIP** for the repository.
2. Extract the download.
3. Copy each actual addon folder into your WoW Forever client's `Interface/AddOns/` directory. The addon's `.toc` file must sit directly inside that addon folder; do not copy an extra outer ZIP or repository folder around it.
4. Restart the client if it was running when the addon was installed.
5. At character selection, open **AddOns** and enable the addon.

Install only the addons you want. Follow any addon-specific instructions shipped with its package.

## Compatibility and testing

These projects target WoW Forever. Compatibility with other WoW clients is not guaranteed. Exact client/interface requirements will be listed with each addon's source and `.toc` metadata. The packages have not been inspected or tested in-game as part of this repository's initial documentation setup.

## Adding and updating addons

This README serves as the collection index and should be updated in the same commit whenever an addon is added or changed.

For each addition:

- Add the complete addon folder, including its `.toc`, code, and required assets.
- Update the table with the version, a short description, and a relative link to the addon folder or download.
- Document verified commands, controls, installation requirements, and limitations.
- Record meaningful changes in the addon's changelog.
- Check that referenced files are included and test the addon in the intended client before marking it tested.

## Bug reports

[Open an issue](https://github.com/Deathbringer98/WoW-Forever-Addons/issues) with the addon name and version, client version, steps to reproduce, and any Lua error text. Screenshots are useful for UI problems.

## About

Created by [Deathbringer98](https://github.com/Deathbringer98). This is an independent addon collection and is not affiliated with or endorsed by Blizzard Entertainment.
