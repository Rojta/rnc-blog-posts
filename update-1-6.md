---
title: Update 1.6
subtitle: WIP
coverImage: update-cover.webp
tags:
  - Update
---

## Additions

- Added weapon fire mode switching hud.
- **New badge system.**
  - With new badge system player will be able to learn new badges to display in chat, voice activity, scoreboard, etc..
  - **Every donator level will get its unique badge icon.**
  - You can have one active badge at the time for example:
    - You can display a maximum of 3 badges on your profile. The first two are system badges for your Admin and/or Donator level. The third is your "unique" badge (for example, Developer, Discord Verified, etc.). You can equip any unique badge to be displayed alongside the first two.
    - We plan on adding lot more badges in the future with ability for players to earn them, by completing challenges, etc..
- **Added new Login/Register screen.**
  - Added ability to request password reset email within game.
  - Added remember me checkbox. (It will automatically log you in, like quick login.)
    - Ability to logout with `/logout` command.
  - New background with back blur.
- **Added new chat.**
  - Improved player name and command autocomplete.
  - New design.
  - Added channel tags and badges to the chat.
  - In the future update we also plan on adding quick actions to the chat similar to scoreboard ones.
- Added new vehicle spawner.
  - Vehicle spawner will now always have up to date vehicle list, without us having to update it manually.
  - Added multiple preview images per vehicle. (Some newer vehicles won't have images un-till added.)
  - Added ability to shuffle.
  - Added filter by:
    - Class
    - Manufacturer
  - Added sort by:
    - Release Date
    - Top Speed
    - Acceleration
    - Breaking
    - Handling
    - Lap Time
    - Rating
    - Random
- Added new report menu.
  - You can now report players quick we preset options.
  - Presets
    - Cheating/Scripting
    - Abusive Language
    - Trolling/Griefing
    - Offensive Names/Clan Tags
    - Other (Type the reason manually into the textbox.)
- Added new scoreboard.

  - New badge system badges will show by the player name in the scoreboard.
  - **Added scoreboard actions.**

    - You can now quickly voice mute/un-mute, spectate, report players by right clicking on a player on the scoreboard.

- Added new vehicle ui.
  - New vehicle ui will show, fuel, speed, engine and locked status of the vehicle.
- Added new loading screen.
  - Added **27** new backgrounds.
  - Added new tips.
- Added Halloween weather option.
- Added new clan invite notification.
- Added new admin punishment menu.

## Changes

- ### New password hashing algorithm.

  - We are moving to more secure, modern and faster password hashing algorithm.
  - Because of this change when you login to the server for the first time after the update you will be prompted to change your password.

- **Re-designed whole main menu.**
  - Clan Tab
    - Toggle Clan Tag and Copchase Partnering are now toggleable per player.
    - Added confirmation dialog to leave/delete clan buttons.
    - Members tab
      - Added quick actions. (Right click on player name)
        - Kick
        - Change Rank
- Re-designed weapon spawner.
- Re-designed notifications.
- Re-designed diamond and points icons.
- Re-designed top right info hud.
  - Added username and player id into the info hud.
- Re-designed voice activity.
  - Added badges.
- Removed bank robbery event music.
- Removed lock picking minigame.
- #### Basically the whole server ui was rewrite to be faster and more responsive.

## Fixes

- ### UI Scale fix.
  - We implemented ui scale fix to work around ragemp ui scaling bug on resolutions such ask 2k and 4k ones.
  - UI should now scale with your resolution.
- Fixed anti-afk message color format bug.
- Fixed player disconnect error.
- Fixed bug where donators would't be able to buy items in the menu.
