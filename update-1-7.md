---
title: Update 1.7
subtitle: List of changes for Update 1.7
coverImage: update-cover.webp
tags:
  - Update
---

## Additions

- ### Email verification
  - If you already have an account registered you will be asked to verify your email the next time you log in and all new players will be required to verify their email before registering.
- Automated password reset process with email, you can reset your password in-game by clicking **Forgot Password** or at [racenchase.com/password](https://racenchase.com/password)
- ### Character Customization Rework
  - The entire Character Customization system has been rebuilt from the ground up.
  - The Appearance & Clothing editor UIs have been completely reworked to be more intuitive than ever before.
  - Appearance & Clothing editors can now be accessed through the Menu.
  - You can have multiple different outfits per-team, accessible through the Menu. **The number of outfits you can save depends on your Donator Rank**!
  - You can now **import Character Appearance data from Menyoo XML files** onto Race 'N' Chase.
  - Added some new hairstyles.
  - **EUP Serve & Rescue pack has been added;** EUP hats & glasses have been added as well.

- ### New 'Anti-Peek' System
  - Shooting is no longer disabled when anti-peek is active.
  - Instead, when anti-peek is active, some debuffs will be active: **increased recoil, decreased weapon damage, disabled instant headshots.**
  - A small "**!**" icon will be visible under the crosshair when anti-peek is active now.

- ### Event Manager
    - Completely rewritten the way game events work on the server.
    - Events are now played in their own, **custom lobbies** instead of copchase lobbies, so they will no longer interfere with those who prefer playing classic copchase.
    - The Event Manager system gives us unlimited freedom and lays the path for more custom, exciting game events in the future!
    - *Currently, the only event available will be Bank Robbery; this system is still in the BETA phase.*

- ### 'Bank Robbery' Event Rework
  - Bank Robbery event is now hosted in a separate lobby which can be joined by anyone, with no player count limits.
  - The 'Sniper' role has been removed; instead, there will now be two heist leaders.
  - Police now spawn in random locations throughout the city, instead of spawning everyone at the police station.
  - The event has been made more accessible than ever, with a list of objectives being displayed at the beginning of the round, and the currently-active objective being displayed at all times, with multi-language support.
  - Blips for this event have also been reworked. For example, objective blips are now always yellow, teammate blips are green, etc.
  - Changed the loadouts, vehicle spawn locations, hideout locations, etc.

- Added restart notice message 5 minutes before server auto restart.
- Added embedded messages to chat for accessibility purposes.
- ### Teleport Markers / More Interiors!
  - Added **Teleport Markers**, allowing us to make almost any interior in GTA V accessible.
  - These teleport markers may also be used to balance out some OP spots in copchase.
  - *These also allow us to add custom interiors.. in a future update!*
- Added a few new ban evader detections.
- ### Custom Walkstyles
  - Silver Donators+ can now use **/walkstyle** to change their walkstyle.
  - Players below Silver Donator will now automatically have the **'Injured'** walkstyle applied whenever their HP is under 50.
- Added **'Display My Nametag'** option in Menu > Display to toggle display of your own nametag on your screen.
- Several login screen bugs have been fixed, such as the mouse cursor disappearing, anti-spam, etc.
- Added **Croatian** language support.
- Completely rewritten some core logic of the server, such as the copchase starting function, to be more optimized than ever before. *You may notice Copchase round starting much faster now with less loading screens!*
- Added **/eject** to remove fugitives with shot tags from your vehicle; Silver Donators+ are immune to this.
- Added **Language-based Voice Mode**; players who have their language set to anything other than English will have this mode set by default. They can switch to **Proximity** mode to talk with everyone. English language players will not be affected by this change.
- When you die, a yellow line will show up, showing you where you got shot from.

## Changes

- Instant Headshots **no longer work** if the target is **10+ meters away**! *This value may be fine-tuned in the future based on feedback we receive.*
- Removed old 'Anti-Peek' system, replaced with the new one mentioned above.
- Fuel in copchase now depletes based on **distance**; *this should fix the issue where some players ran out of fuel too fast*.
- **Removed vehicles with real-life brands** to align with Rockstar/Take-Two/RAGEMP's policies.
- Added new logging types for staff members.-
- 'Remember Me' will now **automatically be turned OFF** if you are **kicked by the server for AFKing too long**.
- Changed normal player messages to a new chat style.
- Minor changes have been done to the UI for Christmas season.
- Blood puddles when bleeding now spawn in form of decals; they should no longer look buggy.

## Fixes

- Anticheat fixes & improvements.
- Action Menu can no longer be opened in the login screen *(which would cause the cursor to disappear)*.
- The 'Double Chat' bug should no longer occur.
- Fixed fuel gauge always being stuck at 50%.
- Fixed a bug where vehicle fuel would refill itself after re-entering the vehicle.
- The new ban screen should now show correctly after login.
- The loading screen will no longer show up if the match was not started successfully.
- Fixed vehicle spawner, it should now work correctly.
- Fixed chat badges.
- *Other, minor bug fixes & improvements.*
