This document is a translation of the official regulations written in Russian. In case of any discrepancies or differences in interpretation between this translation and the original Russian version, the Russian version shall prevail.

# Table of Contents

- [Game Rules](#game-rules)
  - [1. Game version](#1-game-version)
  - [2. Anti-cheat](#2-anti-cheat)
  - [3. Map veto procedure](#3-map-veto-procedure)
  - [4. Match settings](#4-match-settings)
  - [5. Overtimes](#5-overtimes)
  - [6. Match server](#6-match-server)
  - [7. In-game chat](#7-in-game-chat)
  - [8. Coaching](#8-coaching)
  - [9. Pause usage](#9-pause-usage)
  - [10. Player settings](#10-player-settings)
  - [11. Match procedures](#11-match-procedures)
  - [12. Bugs and glitches](#12-bugs-and-glitches)
  - [13. Demo recordings for online matches](#13-demo-recordings-for-online-matches)

## Game Rules

### 1. Game version

The tournament uses the latest available game client. If the newest build introduces critical bugs or major balance changes, the administration may revert to an earlier version. Updates released during the event can be rolled back when possible.

### 2. Anti-cheat

The Tournament Operator may, at its discretion, designate the required anti-cheat for any stage.

* If matches are played on the FACEIT platform, FACEIT Anti-Cheat ([link](https://www.faceit.com/en/anti-cheat)) is mandatory for all participants.
* If matches are hosted on the Tournament Operator’s own servers, Akros Anti-Cheat ([link](https://akros.ac/#download)) may be required; in that case, the Operator will announce this in the captains’ group no later than 1 day before the first matches on Akros-protected servers.

### 3. Map veto procedure

**Map pool**

Matches use the current Active Duty map pool:

- Overpass
- Inferno
- Mirage
- Nuke
- Dust2
- Ancient
- Train

**Online tournaments**

The online map selection process (mappicking/mapvetoing/mapbanning) will take place at a time designated by the tournament administration on a platform designated by the tournament administration, such as Discord, vetoBot, or the FACEIT client. Participants will be notified of the platform in advance.

For matches on the FACEIT platform, the map veto process will begin at the scheduled match start time: each team will select players for the match, then veto the server, and finally veto the map. For all other online matches, this process typically begins 30 minutes before the scheduled match start time. If a team is 5 minutes late for the announced map selection start time, the remaining picks and/or bans will be randomized by the tournament administration.
In all cases, the map selection end time does not necessarily indicate the exact match start time.
The map selection process may be concluded (possibly significantly) earlier at the direction of the tournament administration. Completed map vetoes must not be published until Myskill has done so.
During the map selection process, a participant's first report to the tournament administration will be considered their ban or pick and cannot be retracted or removed.

**Offline tournaments**

The offline map selection process must begin 60 minutes before the scheduled match start.
If a participant is 5 minutes late for the announced map selection time, the remaining picks and/or bans will be randomized by the tournament administration. In all cases, the map selection end time does not necessarily correspond to the exact match start time. The map selection process may be completed (possibly significantly) earlier at the direction of the tournament administration. Information about completed map vetoes must not be published until Myskill does so.
Only two players from each team may participate in the map selection process in person. Otherwise, the entire team may participate in the map selection process. A participant's first report to the tournament administration during the map selection process will be considered their ban or pick and cannot be reversed. Participants will be given access to the veto platform upon arrival. They should write down the password they receive. This password should never be shared with anyone outside their team.
If a participant encounters an error or problem with the vetobot system during the match veto process, they must immediately notify the tournament administration. The veto will be reinstated, and the bans and votes will be identical to those issued during the initial veto, up until the point at which the problem arose. If the tournament administration is not notified of any veto issues before the process is fully completed, the result will stand, and the veto will not be re-issued.

**Best-of formats**

- **Bo1:** Higher seed chooses Team A or B. Order: A removes one, B removes two, A removes two, B removes one, remaining map is played. Starting sides are decided by a knife round.
- **Bo3:** Higher seed chooses Team A or B. Order: A removes one, B removes one, A picks one, B picks one, B removes one, A removes one, remaining map is decider if needed. Each team chooses starting sides on the opponent’s pick; the decider side is determined by knife round.
- **Bo5:** Higher seed chooses Team A or B. Order: A removes one, B removes one, A picks one, B picks one, A picks one, B picks one, remaining map is decider if needed. Starting sides follow the same rules as Bo3.

### 4. Match settings

Standard match settings:

- Rounds: Best of 24 (mp_maxrounds 24)
- Round time: 1 minute 55 seconds (mp_roundtime 1.92)
- Start money: $800 (mp_startmoney 800)
- Freeze time: 20 seconds (mp_freezetime 20)
- Buy time: 20 seconds (mp_buytime 20)
- Bomb timer: 40 seconds (mp_c4timer 40)
- Overtime rounds: Best of 6 (mp_overtime_maxrounds 6)
- Overtime start money: $12,500 (mp_overtime_startmoney 12500)
- Round restart delay: 5 seconds (mp_round_restart_delay 5)
- Halftime break: 3–4 minutes
- Overtime break: disabled
- Prohibited items: none (mp_items_prohibited "")

### 5. Overtimes

In the event of a tie after all 24 rounds of regulation time, overtime will be played in a Best of 6 format (mp_maxrounds 6) with a starting money of USD 12,500 (mp_startmoney 12,500). At the beginning of each overtime, teams play the same teams they played in the previous overtime or regulation time. During the break, teams switch places. Overtime continues until a winner is determined.

### 6. Match server

Matches are held on servers provided by Myskill. Teams are required to check all necessary gameplay aspects (including skins, loading errors, etc.) and network components (server latency and errors) no later than 5 minutes before the scheduled match start. Failure to do so and starting the match early will mean both teams have accepted the current map and server state, and the match may continue as long as these conditions are met.

Participants are advised to communicate their server location preferences prior to the event or each match. However, the final decision on server locations will be made by the tournament administration. Participants are encouraged to check the FACEIT event page for the most up-to-date information.

### 7. In-game chat

Use of game chat during a match is limited to communication with tournament administration only. Advertising and irrelevant comments before and after the match are prohibited. Using game chat to irritate an opponent or interrupt gameplay may result in a penalty.
Pre-match communication with opponents is permitted only in a respectful manner.

### 8. Coaching

**Online**

Participants are allowed to connect their registered coaches to the game server.
Depending on the platform used, coaches must enter the command "!coach t" or "!coach ct" in the game chat to become a coach. If the tournament is held using the FACEIT system, a coach can simply be selected as a coach before the match. Coaches are required to test the coaching function after the match begins.
During online matches, coaches are allowed to communicate freely with players; they are not required to take a tactical timeout and can talk during live streams.

**Offline**

Participants are permitted to have their registered coach accompany them during official matches. During the match, the coach will be connected to the voice communication system and will be able to communicate with players only during tactical pauses and breaks. Coaches are prohibited from communicating with players in any other way, including, but not limited to, shouting or nonverbal communication (such as touching) outside of the specified time windows.
Any coach who violates the communication restrictions outlined in this section will receive one (1) warning from the referees. This warning is valid for the entire match. For a second violation of this rule, or for the first time, the coach will be suspended from the game and will lose the right to coach the team for the remainder of the match. The administration will pause the match for the duration of the suspension, and this pause will be considered a technical pause.
Teams may be issued a preliminary warning in the event of a repeat violation. In the event of a repeat violation, the coach will be suspended from the game.
A suspended coach cannot be replaced.
Warnings are recorded by the tournament administration and may be reviewed for sanctions. If the incident clearly and significantly impacted the game, the consequences for the coach and/or team will be correspondingly more severe.

**Banned coaches**

Coaches banned by Myskill are subject to the following restrictions:
• Cannot actively or passively communicate with the team from 15 minutes before the official match start time until the end of the match.
• Cannot be physically present near the team from 15 minutes before the official match start time until the end of the match.
• Cannot be on the game server during official matches.
• Cannot be in the official match Discord channel.
• Cannot be part of the official map veto process or in contact with the team during this process.
• Tournament administration may impose additional restrictions if necessary.

### 9. Pause usage

The pause function can be used at any time, but it will only take effect during Freeze Time (immediately if used during Freeze Time, otherwise at the start of the next Freeze Time).

**Online**

If a participant encounters issues that prevent them from continuing the game, they can use the pause function.
The maximum total pause time is 10 minutes, which will be set by the tournament administration before the start of the match. Teams may pause an unlimited number of times for technical reasons, but cannot exceed the set maximum time. For example, each team may have a 10-minute total technical pause per match. They can pause an unlimited number of times, up to a total of 10 minutes.
Once the maximum allowed pause time is reached, the match will be unpaused, and that team will not be able to pause it again.

The technical pause function can be accessed by typing "!pause." Participants must announce the reason for the pause before or immediately after stopping the match. Headsets must remain on during the technical pause.
To call a timeout, participants must use the in-game voting system (ESC > Call a Vote > Call a Tactical Timeout). A timeout lasts thirty (30) seconds. Participants may call all three timeouts simultaneously, declaring them separately after the previous timeout expires.
If a map goes into Overtime (OT), all remaining timeouts will be removed, and each team will receive one (1) timeout to use in that Overtime (OT1). If a map goes into the next Overtime (OT2) round, the same thing happens: all remaining timeouts will be removed, and each team will receive one (1) more timeout. The number of timeouts used in Overtime cannot exceed one (1).

**Offline**

Technical Pause
If a participant experiences a problem that prevents them from continuing the game, they are allowed to use the technical pause function. The technical pause function can be accessed by typing "!pause." Participants must announce the reason for the pause before or immediately after stopping the match. Headsets must remain on during the technical pause.
Unless otherwise instructed by tournament administration, any form of communication, including but not limited to text, voice, or any form of non-verbal communication between players and coaches, is strictly prohibited during a technical pause.
Timeout
Each participant has the right to take a thirty (30) second timeout up to three (3) times during regular time rounds on each map. Participants may call timeouts through the in-game voting system (ESC Call Vote Call Tactical Timeout). Participants may call all three timeouts simultaneously by calling them separately after the previous timeout expires. If a map goes into Overtime (OT), all remaining timeouts will be removed, and each team will receive one (1) timeout to use in that Overtime (OT1). If a map goes into the next Overtime round (OT2), the same thing happens: all remaining timeouts will be removed, and each team will receive one (1) more timeout. The number of timeouts used in Overtime cannot exceed one (1).

Tournament administrators may pause the game from their workstation or from a participant's workstation if necessary. Communication during the pause is permitted only with tournament administrators.

### 10. Player settings

**Configuration files**

Any configuration changes are permitted as long as they do not provide an unfair advantage comparable to cheating. A player or team may be penalized for unauthorized settings in any configuration file, regardless of whether it is currently in use or stored in the game's corresponding folder.
Participants should contact the tournament administration if they are unsure of the reliability and integrity of a particular "team" (config).

**Warm-up maps**

The tournament image only features Steam Workshop maps: "CSStats Training Map (CSGOHUB)" and "Aim Botz - Aim Training (CS2)." Other maps will not be added based on player requests.

**Scripts**

All scripts are strictly prohibited without exception. This includes any game bindings that perform more than one movement and/or attack action. Participants may be penalized for prohibited scripts in any configuration file, whether used or stored in the game folder.

**Graphics drivers**

Any modifications or changes to the game using external graphics solutions or other third-party programs are strictly prohibited and may be punished as cheating.

**Overlays**

All types of overlays that can display system resource usage on a gaming PC (such as Discord and Rivatuner overlays) are prohibited. Overlays that only display frames per second (FPS) are not prohibited and may be used.

**Custom data**

Players are prohibited from using any custom game files during official matches. Counter-Strike skins may be changed, but Agent-type player skins are prohibited. Any other modifications, including but not limited to modifications to sprites, radars, HUDs, and scoreboards, are strictly prohibited.

**Device drivers**

Using device drivers to pre-install/record illegal macros on participant devices (keyboards, mice, sound cards) is prohibited and may be punished as cheating.

**In-game items**

All in-game items, including skins, name badges, and stickers (or any combination of stickers), must fully comply with the Code of Conduct and Sponsor Restrictions set forth in the General Rules.

### 11. Match procedures

**Breaks**

Participants will be given a break of at least 10 minutes between matches and 8 minutes between maps in best-of-three (Bo3) and best-of-five (Bo5) matches. In best-of-five (Bo5) matches, teams will also be given a break of at least 20 minutes between maps 3 and 4. The exact duration of these breaks will be announced by the tournament administration.

**Number of players**

All matches must start with five players per team (5v5); other combinations are not permitted. If a participant fails to show up with a sufficient number of players, the match will be counted as a no-show.
If a player disconnects during the current round, the current round ends. If the map has not yet ended, the game is paused until the player returns or is replaced. If the original player is unable to return to the game and find a replacement, the team may forfeit the series or continue with four players.
If a participant is forced to continue the game with fewer than four players, the opposing player automatically wins.

**Interrupted matches**

If a match is interrupted due to circumstances beyond the control of the participants (e.g., a server or player crash), tournament administrators will restore the round using Counter-Strike's backup and restore feature, but in some cases, as detailed below, may decide to replay the round or even the entire match:
• If the issue occurred before any damage was inflicted or significant gameplay occurred, and the opponent or referee was immediately notified, the round will be restored.
• If the issue occurred during a round and after damage was inflicted, and the outcome of the round can still be determined (e.g., one player is eliminated but others remain), the round will not be replayed or restored. The round will continue and be scored. Special exceptions may be made if the damage inflicted was deemed minor, such as accidental damage to a teammate inflicted early in the round, or if the damage was inflicted by the team that suffered the crash.
• If an issue occurs during a round, after damage has been dealt, and the outcome of the round cannot be determined (e.g., due to a server crash), the match will be restarted before the round begins.
• If an issue occurs during a round, after damage has been dealt, and the outcome of the round is clear (e.g., one team is sent to a save with 10 seconds remaining in the round), but the round cannot be continued, e.g., due to a server crash, then the round may be awarded to the team most likely to win the round.
Matches will not be stopped and/or rounds will not be restarted or replayed in cases where the participant is clearly at fault (e.g., purchasing an incorrect weapon).

### 12. Bugs and glitches

Intentional exploitation of any bugs, glitches, or errors in the game is prohibited. Tournament administration will decide at its sole discretion whether the exploitation of these bugs impacted the match and whether rounds or the match will be awarded to the opposing team, or a rematch will be ordered. Exploitation of the following bugs is strictly prohibited. If a bug exploit is not listed here, the decision regarding penalties will be made by tournament administration:
• Moving through restricted areas where movement is not allowed by the map design (any walls, ceilings, floors, etc.).
• Bombs cannot be planted in a location where they cannot be defusal.
• Bomb planting (planting) was done in a way that prevents anyone from hearing the sound signal or bomb plant sound.
• Pixel Walking. A player is considered to be in violation of this rule if they sit or stand on invisible pixels on the map where there is no visible edge. Violating any map features using objects (e.g., stopping the train on Overpass).
It is recommended to check with the tournament administration to determine whether a specific bug or glitch is considered prohibited.

The following bugs are allowed:
• Defusing the bomb through walls and objects, etc.
• Covering the bomb with map objects or graffiti spray
• Using graffiti spray to track the bomb timer
• Silent landing
• Surfing on pipes
• Molotov cocktails that fire through the ground
• "Infinite" grenade throws
Tournament administration reserves the right to add new bugs to the list of explicitly allowed bugs, retroactively or otherwise.

New Positions
If a participant wishes to use a new, unknown position, it is strongly recommended to contact the tournament administration to confirm whether the position is permitted before using it in an official match. Participants should be aware that testing new positions takes time, so they should contact the tournament administration as soon as possible before the official match. A full list of permitted bugs and pixel workarounds will be published here.

**Reconnections**

Participants are prohibited from reconnecting during a round. If a technical issue occurs that requires reconnecting, they must pause the game, report the cause, and only then reconnect. If a participant experiences a glitch during a round, they must wait until the round ends and pause the game before reconnecting. Any violation of this rule will result in a minimum of one (1) penalty point.
Joining the wrong team on the server when reconnecting is strictly prohibited.

### 13. Demo recordings for online matches

If instructed to do so, all match participants are required to record their own first-person demos and submit them to Myskill using the provided tools. Demos must be submitted within 1 hour of the match's conclusion and must be retained for at least 24 hours. Demo filenames must be map-identifiable (e.g.,EventnameTeamVSTeamMap1).
Failure to submit a demo to Myskill will result in a penalty of $100 + 1% of the prize pool for each missed map recording for each player. Incomplete demos will be considered as not submitted.
Any attempt to submit fake POV demos to Myskill will result in a more severe penalty.
