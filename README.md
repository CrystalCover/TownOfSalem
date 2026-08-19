# Quality of Salem v2.0.20 (WIP)
This mod is made for the **Steam version** on Windows.

## Installation
1. Install the latest version of [BepInEx](https://github.com/BepInEx/BepInEx/releases) for 64-bit.
2. Place *QualityOfSalem.dll* within "\TownOfSalem\BepInEx\plugins"; create the folders if missing.
3. Run *TownOfSalem.exe*.

## Updating
1. Replace the old *QualityOfSalem.dll* with the new one.
2. Delete *ExtendedStringTable.en-US.xml* located within "\TownOfSalem\BepInEx\config". This file is most likely updated between versions.
3. Optionally, delete *GameRules.xml* located within "\TownOfSalem\TownOfSalem_Data\StreamingAssets\res\WebAssets\XMLData". This file is most likely not updated between versions.

## Features
All features are client-side and do not affect the gameplay for you or others.

### Fixes
- Upon role conversions, avatar name label colors will be properly updated.
- When you are a Blackmailer and whisper to someone, you will no longer hear your own whisper as if it came from someone else.
- Chat messages containing invalid characters (chat exploits) will be shown as "[SenderAccountName] has sent an invalid message.", and the sender's account name will be colored black until the next launch of the application.
- Day and night headers in the chat log are now properly filtered in the Spanish language.
- The chat log will no longer scroll to the bottom every time you change the position filter.
- Toaster notifications for party invites appear again.
- If you end up visiting a jailed player as an Arsonist, the jailed player will no longer be shown as doused.
- Some stuff in the friend service has been made more sane.

### Reversals
- T\*v\*rn K\*\*p\*r and B\*\*tl\*gg\*r are renamed back to Escort and Consort; their role icons and all associated strings are also changed back.
- The word *hang* is replaced back with the word *lynch*.
- Gender pronouns, *he* and *she*, are added back.
- Suicidal death reasons are restored.

### Enhancements
- Role card, role list, and graveyard panels can now be automatically hidden if the relevant settings are enabled.
- The Necronomicon and the full moon notices will no longer display if the Coven (for the former), the Werewolf (for the latter), or the Juggernaut (for the latter) cannot appear in the game.
- When deaths are being announced, the messages appearing in the chat log will also appear in the chat box. (e.g., "He was killed by a member of the Mafia.")
- Any name references (player number + player name) and whispers will now also be filtered in the chat log.
- Night chat message backgrounds will be colorized if the player's role is known or the sender is a Medium, the Jailor, or a Vampire (for Vampire Hunters) if the relevant setting is enabled.
- Player names will now have one of the following colors in the party and pre-game lobby chats: gold for you, light green for best friends, light blue for non-best friends, red for blocked users, and grey for others.
- Messages of blocked users in lobbies can now be hidden if the relevant setting is enabled.
- Forgers now have a Forged Will button next to the Last Will button to edit the forged info at any time.
- Pressing the Escape key will no longer undo the changes on the forged will while editing it.
- Some restrictions in the custom lobbies are now removed, including: opposing faction requirement, Vampire requirement for Vampire Hunters, and role limit for non-unique roles (but not the faction limits).
- When the game ends, if the Town or lovers win, the "victory" music will play for everyone; if an evil faction, Witches, Neutral Killings, or the Plaguebearer/Pestilence win, the "defeat" music will play for everyone; if others win, the "victory" music will play only for them; and a celebration sound effect will play only for the winners.
- Name references that previously did not have player position numbers now have them. Player position numbers now appear during name selection. The winners in the victory message will now be sorted by their position numbers.
- Party, pre-game, and end-game lobbies now have new commands: /friend \[userName\], /unfriend \[userName\], /sendfriendmessage \[userName\] \[message\], /listfriends, /showonlinefriends, /block \[userName\], /unblock \[userName\], and /listblockedusers.
- The jail lock and blood drop animations can now be disabled from settings.
- The role list in non-custom lobbies will always show the full role list, regardless of the number of players in the lobby.

### New
- If you enabled the "Remember Me" (now "Log Me In Automatically") checkbox on the login screen, the game will automatically log you in the next time the application is launched.
- Lobby users now have friend and block buttons for you to block or unblock them, friend or unfriend them, or accept or decline their friend request.
- When a friend goes online or offline, or when someone friends or unfriends you, you'll get notified by a toaster notification, if enabled.
- Some in-game events now have sound effects: being set on fire by an Arsonist, being controlled (regardless of being hypnotized), announcement of an Amnesiac remembering a role, announcement of the Mayor revealing, and announcement of a Guardian Angel protecting their target.
- Notification messages regarding the friends and block system will be displayed in the pre-game and end-game lobbies.

### Discord Rich Presence
- You can present your Town of Salem activity on Discord by installing [Salem Rich Presence](https://github.com/CrystalCover/TownOfSalem-SalemRichPresence)!

Not everything may be listed here. Go find the others out!
