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

FACEIT Anti-Cheat ([link](https://www.faceit.com/en/anti-cheat)) is mandatory for all qualifier matches. Players who cannot run the FACEIT client cannot compete.

Akros Anti-Cheat ([link](https://akros.ac/#download)) must be used during group stages and playoffs. Players are responsible for having valid credentials and two-factor authentication configured before the competition.

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

The veto (pick/ban) process takes place on the platform designated by the administration (e.g., Discord, vetoBot, FACEIT client) at the announced time. Participants are informed of the platform in advance.

On FACEIT, the veto begins at the scheduled match time: teams select their players, veto the server and veto the map. On other platforms the process typically starts 30 minutes before the match. If a team is five minutes late, remaining picks/bans may be randomised by the administration.

Completing the veto does not guarantee the exact match start time. The administration may finish the veto early and prohibits publishing the results before Myskill does.

Once a team communicates a pick or ban to the admin, it is binding. Each participant has 150 seconds to make their decisions; expiring the timer allows the admin to randomise the remaining picks/bans.

**Offline tournaments**

Offline vetoes begin 60 minutes before the match. A five-minute delay results in remaining picks/bans being randomised. The administration may end the process early, and results must not be published before Myskill. Each team has 150 seconds to act and may split the time into stages. Only two players per team may attend the on-site veto; otherwise the entire team may participate. Veto platform passwords must remain confidential. Any issues with veto tools must be reported immediately so the process can resume with identical decisions.

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

Ties after 24 rounds trigger overtime (Best of 6) with $12,500 starting money. Teams keep their sides from regulation or the previous overtime for the first half, then swap. Overtime repeats until a winner is determined.

### 6. Match server

Matches are played on Myskill servers. Teams must check gameplay elements (skins, load errors, etc.) and network conditions (latency, server variance) at least five minutes before the match. Starting early without reporting issues implies both teams accept the current server state.

Server location preferences should be communicated before the match, but the administration makes the final decision.

### 7. In-game chat

In-game chat is limited to communication with the tournament administration. Advertising and irrelevant comments before or after the match are prohibited. Using chat to provoke opponents may result in penalties. Pre-match interaction is allowed when respectful.

### 8. Coaching

**Online**

Registered coaches may join the server and use `!coach t` or `!coach ct` (or the FACEIT coach slot) to access coach mode. They must ensure the feature works once the match starts. Coaches may communicate freely with players during online matches without calling time-outs.

**Offline**

Registered coaches may stand behind the team. They are connected to voice comms but may only speak during tactical pauses and breaks. Any other communication—including shouting or non-verbal cues—is forbidden. The first violation earns a warning for the entire match; a second violation (or a severe first offence) removes the coach for the rest of the match. Removed coaches cannot be replaced. The administration records warnings and may escalate penalties if the incident affected the game.

**Banned coaches**

Coaches banned by Myskill may not communicate with the team starting 15 minutes before match time until the match ends, may not be near the team, may not join the game server or official Discord match channel, and may not take part in the veto. Additional restrictions may apply.

### 9. Pause usage

Pauses can be triggered at any time but take effect at the next freeze time (or immediately if triggered during freeze time).

**Online**

Teams may pause for technical issues using `!pause`. The total technical pause time per match is capped at ten minutes; multiple pauses are allowed within that limit. Reasons must be announced before or immediately after pausing, and headsets must remain on. Tactical time-outs are initiated via the in-game vote menu, last 30 seconds and can be stacked sequentially. When overtime begins, all unused time-outs reset and each team receives one new time-out per overtime. Only one time-out may be used per overtime phase.

**Offline**

Technical pauses follow the same `!pause` procedure. Unless instructed otherwise, no communication between players and coaches is allowed during technical pauses. Tactical time-outs last 30 seconds, up to three per regulation map, called via the vote menu. Overtime rules mirror the online format. The administration may pause matches from their stations; communication during an admin pause is restricted to officials.

### 10. Player settings

**Configuration files**

Config changes are allowed as long as they do not provide an unfair advantage. Unapproved settings may lead to penalties even if the config is unused. Players should consult admins if unsure.

**Warm-up maps**

Only the Steam Workshop maps “CSStats Training Map (CSGOHUB)” and “Aim Botz – Aim Training (CS2)” are available. Additional requests are not accepted.

**Scripts**

Scripts are strictly forbidden, including binds that execute multiple movements or attacks. Violations may result in penalties even if the script is unused.

**Graphics drivers**

External modifications or third-party tools that alter the game are prohibited and may be treated as cheating.

**Overlays**

System overlays displaying resource usage (e.g., Discord, Rivatuner) are banned. FPS-only overlays are allowed.

**Custom data**

Custom game files are prohibited during official matches. Counter-Strike skins may be changed, but Agent skins are banned. Modifying sprites, radar, HUD or scoreboard is forbidden.

**Device drivers**

Using device drivers to pre-load or record illegal macros on peripherals is prohibited and may be punished as cheating.

**In-game items**

All items (skins, name tags, stickers) must comply with the general rules on conduct and sponsorship.

### 11. Match procedures

**Breaks**

Teams receive at least 10 minutes between matches, 8 minutes between maps in Bo3/Bo5 series, and at least 20 minutes between maps 3 and 4 in Bo5 series. Exact durations are announced by the administration.

**Number of players**

Matches must start 5v5. If a team lacks players, it forfeits. If a player disconnects, the round is played out; the match is then paused until the player returns or a substitute joins. Teams may continue with four players but lose if they drop below four.

**Interrupted matches**

If a match is interrupted due to factors outside the teams’ control, the admin restores the round using CS2’s backup/restore tools. Depending on the situation, the round may be replayed, restored or awarded if the outcome was evident. Player-caused issues (e.g., buying the wrong weapon) are not grounds for a replay.

### 12. Bugs and glitches

Deliberately exploiting bugs or glitches is forbidden. Prohibited examples include leaving the playable area, planting the bomb where it cannot be defused, placing the bomb to hide sound cues, pixel walking and manipulating map elements (e.g., stopping the Overpass train). Admins decide on sanctions, which can include round forfeits or match losses.

Allowed exploits include defusing through walls/objects, covering the bomb with map objects or sprays, using sprays to track the timer, silent drops, pipe surfing, Molotov flames passing through the floor and infinite grenade throws. Myskill may update the list at any time.

Players should consult admins before using new or unknown positions. A maintained list of approved bugs and pixel walks is available [here](https://docs.google.com/spreadsheets/d/1PXd_ozvguzCs2bj8bk5WARriC3q5OSfaa6W0V-7h90E).

**Reconnections**

Players may not reconnect during a round. If a technical issue requires reconnecting, pause first, explain the reason and then reconnect. Crashed players must wait until the round ends, pause and reconnect. Violations incur at least one penalty point. Rejoining the wrong team is forbidden.

### 13. Demo recordings for online matches

When instructed, all players must record POV demos and submit them via the provided tools within one hour of the match ending. Files must be named per map (e.g., `EventNameTeamVSTeamMap1`) and kept for at least 24 hours. Failure to submit a demo results in a 100 USD fine plus 1% of the prize share per missing map for each player. Incomplete demos count as missing, and supplying fake POV demos leads to harsher penalties.
