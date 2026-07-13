# Quality of Salem v2.0.10 (WIP)
This mod can only be installed for the **Steam version**.

## Installation
1. Install the latest version of [BepInEx](https://github.com/BepInEx/BepInEx/releases) for 64-bit.
2. Run the application once, then close it.
3. Place *QualityOfSalem.dll* within "\TownOfSalem\BepInEx\plugins".

## Updating
1. Replace the old *QualityOfSalem.dll* with the new one.
2. Delete *ExtendedStringTable.en-USS.xml* located within "\TownOfSalem\BepInEx\config".
3. Additionally, delete *GameRules.xml* located within "\TownOfSalem\TownOfSalem_Data\StreamingAssets\res\WebAssets\XMLData".

## Features
All features are client-side, and they do not affect the gameplay for you or others.

### Fixes
- When you are a Blackmailer and whisper to someone, you will no longer hear your own whisper as if it came from someone else.
- Day and night headers in the chat log are now properly filtered in the Spanish language.

### Reversals
- T\*v\*rn K\*\*p\*r and B\*\*tl\*gg\*r are renamed back to Escort and Consort, their role icons and all associated strings are also changed back.
- The word *hang* is replaced back with the word *lynch*.
- Gender pronouns, *he* and *she*, are added back.
- Suicidal death reasons are restored.

### Enhancements
- When deaths are being announced, the messages appearing in the chat log will also appear in the chat box. (e.g., "He was killed by a member of the Mafia.")
- Any name references (player number + player name) and whispers will now also be filtered in the chat log.
- Player names will now have one of the following colors in the lobby chat: gold for you, red for blocked users, gold for best friends, light blue for non-best friends, and grey for others.
- Messages of blocked users in lobbies can now be hidden if the relevant setting is enabled.
- Some restrictions in the custom lobbies are now removed, including: opposing faction requirement, Vampire requirement for Vampire Hunters, and role limit for non-unique roles (except for Mafia and Coven).
- When the game ends, if the Town or lovers win, the "victory" music will play for everyone; if an evil faction, Witches, Neutral Killings, or the Plaguebearer/Pestilence win, the "defeat" music will play for everyone; if others win, the "victory" music will play only for them; and a celebration sound effect will play only for the winners.
- Name references that previously did not have player position numbers now have them. Player position numbers now appear during name selection. The victory message will now be sorted based on the position numbers of the winning players.
- The pregame and endgame lobbies now have new commands: /friend \[userName\], /unfriend \[userName\], /sendfriendmessage \[userName\] \[message\], /listfriends, /showonlinefriends, /block \[userName\], /unblock \[userName\], /listblockedusers.
- Some in-game events now have sound effects: being set on fire by an Arsonist, being controlled (regardless of being hypnotized), announcement of an Amnesiac remembering a role, announcement of the Mayor revealing, and announcement of a Guardian Angel protecting their target.
- The Necronomicon and the full moon notices will no longer display if the Coven (for the former), the Werewolf (for the latter), or the Juggernaut (for the latter) cannot appear in the game.
- The Jailor lock and blood drop animations can now be disabled from settings.
- The role list in non-custom lobbies will always show the full role list, regardless of the number of players in the lobby.

### New
- If you enabled the "Remember Me" (now "Log Me In Automatically") checkbox on the login screen, the game will automatically log you in the next time the application is launched.
- Lobby users now have friend and block buttons for you to block or unblock them, send them a friend request, accept or decline their friend request, or remove them from your friends.
- When a friend goes online or offline, you'll get notified by a toaster notification, if enabled.
- Notification messages regarding the friends and block system will be displayed in the pre-game and end-game lobbies.

Not everything may be listed here. Go find the others out!
