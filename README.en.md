# Eslabot · 에슬라봇

[한국어](README.md) · **English**

## 🌐 [Explore mercenary builds and game data on the Eslabot website](https://eslabong-pvp-meta.eslabot.workers.dev/?lang=en)

**[Open the Eslabot website →](https://eslabong-pvp-meta.eslabot.workers.dev/?lang=en)**

Compare mercenaries, skills, relics and observed team builds, or plan your own squad. The website runs in your browser without installing the Windows program. Use **View program** at the bottom of the website to return to this repository.

**[Download the Windows launcher](https://github.com/Eslabot/eslabot/releases/latest)** · [Installation](#installation) · [Korean detailed guide](docs/USAGE.md)

Eslabot is an unofficial Windows companion mod for **Eslabong**. It helps with repetitive training and equipment tasks, displays useful information, and compares battle results. This page provides English documentation; the launcher and in-game mod currently use Korean labels.

## What's new in 1.0.46

- Compatibility updates for Eslabong 0.92.2, Steam public build 26527807, including the new classes, relics and redesigned roster and market screens.
- Battlefield zoom controls remain above the bottom HUD; outside-map gray padding is replaced with black padding.
- A missing native skill icon in the new roster list is restored in the isolated runtime.
- Market shutdown now preserves the game's own cleanup while saving the mod's viewed-mercenary records.
- The launcher shows the last actual program update date and provides an optional **Support development** link to Buy Me a Coffee.

## Features

| Feature | What it does |
| --- | --- |
| Growth calculation | Search for level-up results using stat weights and a target score, including level 1–20 training. Review the preview before applying and saving. |
| Development and card recommendations | Set goals for each mercenary and compare stat cards, skills, upgrades, specializations and masteries. Recommendations are estimates, not guaranteed optimal builds. |
| Rebirth search | Search for the desired pair of rebirth growth traits, then review and apply the result. |
| Skill replacement | Repeat eligible replacements, restore unsuccessful attempts and preserve successful targets. |
| Relic reset | Set quality or individual-option targets, including per-item target buttons and a shared work list. |
| Relic presets and exchange | Save equipment assignments, restore valid presets and exchange both relic slots between owned mercenaries. |
| Battle analysis | View damage and effective healing meters, per-battle averages and contributions; compare different mercenaries and identified skill, relic and crowd-control sources. |
| Battle speed and zoom | Additional speed settings, a saved entry speed and zoom, whole-battlefield view and manual wheel zoom during battle. |
| Market and roster information | Level-one stat sorting, S–F grades, level-one/current display switching and viewed-mercenary filtering. |
| Staff overview | View the effects and stats of staff in the clubhouse. |
| Quick save/load | F5 sets the protected manual save; F10 reloads it. Automatic work uses separate recovery points. |
| Save synchronization | Keep local campaign files and synchronize with the official Steam save location and Steam Cloud when available. |

The website shows **observed adoption and submitted builds**, not measured win rates or proof that a popular build is the best one. Its statistics and the Windows mod's battle records are separate systems.

## Installation

Requirements: **Windows x64 and Eslabong installed through Steam**. The launcher includes its required .NET runtime; no development tools are needed.

1. Start the unmodified game once and save a campaign, then close the game.
2. Download **[EslabotLauncher-win-x64-1.0.46.zip](https://github.com/Eslabot/eslabot/releases/download/v1.0.46/EslabotLauncher-win-x64-1.0.46.zip)**. On the release page, expand **Assets** and choose this file.
3. Extract the **entire ZIP** into a local folder. Do not run it inside the ZIP, move only the EXE, or overwrite your Steam game folder.
4. Run **에슬라봇 런처.exe** from the extracted folder. There is no installation wizard.
5. Check the game path. Use **게임 위치** (Game location) if detection fails.
6. Click **최신 버전 동기화** (Synchronize latest version).
7. When the status reads **사용 가능** (Available), click **에슬라봇 실행** (Launch Eslabot).

You do not need to download the separate mod ZIP, `stable.json`, or GitHub's **Source code** archives. Initial preparation copies and verifies roughly 2 GB of locally installed game data. Original game assets and personal saves are not distributed in the download.

Damage meters, battle recording, growth calculation and card recommendations start disabled. Enable only the features you need from the in-game **도구** (Tools) menu. Your choices are remembered.

## Updates and saves

Save and close the game, finish any Steam game update, then click **최신 버전 동기화**. The launcher updates both itself and the mod when a new public release is available.

An unverified game build can be attempted with the existing launch button; this does not guarantee compatibility. Known problematic builds remain blocked. Signature/file corruption and unresolved save conflicts still require attention.

Campaign saves and mod settings are stored separately from program versions, normally under `%LOCALAPPDATA%\Eslabot\data`. Use **저장 폴더** (Save folder) to open that location. Campaign progress is also synchronized with the official Steam save directory. Wait for the launcher's Steam Cloud completion message after the game exits. When offline, out of Cloud storage, or unable to connect, local saves are retained. Mod-specific settings and analysis records stay local.

If Steam and Eslabot contain different progress, choose which complete campaign to keep in the save-selection dialog. Different timelines are not merged. Do not delete your save folders to resolve an update issue.

## Shortcuts

| Key | Action |
| --- | --- |
| F5 / F10 | Save the protected manual checkpoint / reload it |
| F7 / F8 | Open card recommendations / growth calculation |
| F9 | Stop an active automatic task |
| Z / X | Lower / raise battle speed |
| Ctrl+F3 / Ctrl+F4 | Toggle damage meter / battle recording |

Shortcuts apply only on supported game screens.

## Help and optional support

If launching fails, click the large **실행이 안 되나요? 여기 눌러 알려주세요** button in the launcher. Describe what happened, review the generated diagnostics and submit the report to the private inbox. A successful submission returns a report number. Contact information is optional; save contents are not sent as part of the diagnostic report.

If Eslabot has been useful, you can optionally **[support its development](https://buymeacoffee.com/eslabot)**. Support is not required to use the program.

Eslabot is independent of the game's developer. It uses the game's result-generation systems rather than raising stat caps or changing reward tables. Automated searches select satisfactory results and recover unsuccessful attempts, so their costs and progression differ from ordinary uninterrupted play. Testing does not cover every campaign, skill combination, PC or future game update. Keep a copy of important saves before major changes.
