---
title: Update 1.6
subtitle: List of changes for Update 1.6
coverImage: update-cover.webp
tags:
  - Update
---

## Additions
- Anticheat improvements & additions.
- Helmets that used to be bulletproof should no longer be bulletproof.
- [EXPERIMENTAL] When entering interiors, you will no longer see Player Blips on radar & Nametags.
  - This was added due to a suggestion that players massively voted in favour of.
  - With this change, players will have to carefully plan their approach to barricaded suspects, instead of just rushing inside and spraying & praying. It'll give interior shootouts a completely new feel.
- Added "Digital HP & AR Display" which displays your health & armour in numbers, bottom-left corner of the radar. Toggleable in the menu.
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
  - Added multiple preview images per vehicle. (Some newer vehicles won't have images until they are added.)
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
- You will no longer be removed from spectate mode when the player you are spectating dies.
- /settime will no longer affect players in copchase, only those in the lobby.

- Recoil changes:
  - When shooting from a vehicle, your recoil now depends on the speed of the vehicle. More speed = more recoil.
  - Changed the way drive-by recoil looks *(it now jolts the camera upwards, making it look more 'natural')*.
  - Reduced sidewards recoil when shooting on-foot.

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
- Removed lock picking minigame since it was unused *(might be brought back in a future update when we optimize spawning random vehicles in copchase)*.
- Moved the lobby location to LSPD HQ in Mission Row due to complaints about the previous lobby being too big.
- The Race 'N' Chase Discord bot has been reworked:
  - It now uses Discord's slash-command system, making it more accessible for staff members & players to know which commands are available to them and which parameters they take.
  - The **/link** command has been moved to the Race 'N' Chase bot and should now work fully as intended.
- #### Basically the whole server ui was rewrite to be faster and more responsive.
- Removed the outdated Clothing Editor that would appear after creating your character. Instead, players will now spawn with default police & fugitive clothing that they can later adjust with */clothing*.
- Moved some UI elements around for consistency purposes *(for example, the Action Bar has been removed - current Action progress will show up in the form of a notification; the Game Progress timer shows up in the Mini HUD next to the radar...)*.

## Fixes
- Your camera will no longer move & rotate while chat is turned on in Noclip mode.
- Fixed bug where clans could accept more members than their current limit.
  - As mentioned in the announcements, ALL clans' Kills, Deaths & COTW Wins will be reset to 0 as result of this change, giving everyone a fresh start and fair chance at competing.
- The animation played when using painkillers will no longer freeze you in place - you'll be able to freely move and even shoot.
- ### UI Scale fix.
  - We implemented ui scale fix to work around ragemp ui scaling bug on resolutions such ask 2k and 4k ones.
  - UI should now scale with your resolution.
- Fixed anti-afk message color format bug.
- Fixed a number of backend errors that would randomly pop up during specific moments *(such as player disconnects)*.
- Fixed bug where donators wouldn't be able to buy items in the menu.
- *Other, minor optimizations and bug fixes that will hopefully improve performance & reduce client/server crashes!*
