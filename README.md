# SkidMenu

A BepInEx IL2CPP mod menu for Among Us. SkidMenu combines a large number of public features from various Among Us cheat menus (such as MalumMenu, Hydra, and ElysiumModMenu), though not everything here is skidded. Some features are original and just got added because they seemed like a fun idea, like the notification system.

**Created by SNOWHAXX**

**Current build:** `1.0.2` (Stable)

> This build is labeled Stable. That tho doesnt mean that nothing will break. It just means that no errors occured while playing for long time. Some functions may break mid-game, cause disconnects, or behave unexpectedly. This is normal given how many features are packed in.

## Use this responsibly

SkidMenu is meant for private lobbies with friends who know you're using it and are fine with it. It is not meant to be used in public lobbies against strangers who never agreed to play against someone with a cheat menu. Using it that way ruins the game for people who just wanted a normal match.

SkidMenu is not affiliated with, endorsed by, or sponsored by Innersloth in any way. Whatever you choose to do with this menu, including any bans, account issues, or other consequences, is entirely your own responsibility, not the menu's.

## Why is it closed source

Honestly, there's no big reason behind it. Part of it is that I'm using this project as a way to learn a bit of reverse engineering along the way, and keeping it closed source is just part of that.

## Compatible Among Us versions

| Status | Versions |
|---|---|
| Supported | `2026.3.31`, `2026.6.5` |
| Tolerated (some features may not work) | `2026.2.24`, `2026.3.17` |

Running a different version than the ones above isn't recommended, you'll get a warning popup in the main menu.

## Installation

1. Install BepInEx (IL2CPP) for Among Us.
2. Drop `SkidMenu.dll` into your `BepInEx/plugins` folder.
3. Launch Among Us. Press Delete (default, configurable) to open the menu.

## Features

The menu is split across the following tabs:

- Movement: NoClip, invert controls, speed modifier, teleport (to cursor, to player, to fixed map locations)
- Self: Set color, rainbow, task animations, ladder cooldown, unlimited meetings, chat theme/font customization
- ESP: see roles, ghosts, player info,, notifications, votes, lobby info, no shadows
- Roles: fake roles, fake alive, kill aura/reach, vanish, tracking, vents
- Players: player targeted actions and info, teleport, murder, watch, copy info
- Ship: door control, meetings, body reports, fake tasks, unlock vents
- Sabotage: sabotage triggers, door menu, system manipulation
- Chat: chat unlocks, extended chat, chat history, chat sender (manual spam and trigger based messages on join, death, meeting, kill, and ejection)
- Animations: task animations
- Console: in game event log (kills, vents, phantom vanishes, shapeshifts, sabotages, meetings, ejections, votes, votekicks, chat, disconnects, joins, and more)
- Host: host only tools (disable sabotages, meetings, cameras, pre-game role forcing, disco party, level blocking, kill all, force start, end game)
- AutoHost: automatic lobby hosting and match starting
- Fun Ban Exploit: a single ban related exploit
- Schizo/FakeSab: fake sabotage spam
- Passive: anti-overload, unlock features, free cosmetics, penalty avoidance, cosmetic randomization
- Troll: troll stuff such as disabling vents, door troller, block sabotages, auto report bodies
- Votekick: votekick players
- Protections: client side hardening against malicious hosts and players (DTLS, overload protection, ladder and vent validation, anti exploits)
- Anticheat: RPC validation, known mod detection, punishments, max level
- Dating Shit: lobby browser filters for lobbies that could be probably used as dating lobbies, extended lobby list
- Modes: RGB, stealth, panic
- Settings/Config: save and load your profile
- Info: about, disclaimer, keybinds reference

## Keybinds

| Key | Action |
|---|---|
| Hold F1 | Close doors in your current room |
| Hold F2 | Close every door on the map |
| Hold F3 | Open every door on the map |
| Hold F6 | Trigger all sabotages at once |
| Hold F7 | Fix all active sabotages |
| Hold 7 | Spam electrical sabotage |
| F4 | Complete your tasks one by one with a small delay |
| F5 | Report a random dead body (in game only) |
| F8 | Votekick everyone in the lobby |
| F9 | Ban everyone in the lobby |
| F10 | Ban all impostors |
| F11 | Ban a random player |
| 0 | Call an emergency meeting (in game only) |
| 9 | Kill a random player (in game only, host or impostor) |
| 8 | Teleport kill a random player (in game only, host or impostor) |

All keybinds can be disabled from the Info tab.

## Saving your setup

Use Save to Profile / Load from Profile in the Config tab to not set the same settings over again in different sessions.

## About the creator

Active on Discord as snowhaxx, and sometimes around on discord.gg/XNmXUtPvGC. That server isn't owned by me and I don't personally know the people there, I'm just sometimes active on it. SkidMenu currently has no official Discord server.
