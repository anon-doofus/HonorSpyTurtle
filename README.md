
### QUICK AND DIRTY EDIT TO LEXIE'S TURTLEWOW HONORSPY.
### MERGED MY POOL SIZE FIX, WITH LEXIE'S CENSUSPLUS EDIT FOR REMOVING CROSS-FACTION DATA.
### UNTESTED. 
### -t. Kyneswide
### Updating Lexie's CensusPlus.lua with recent Census data. Given that it apprantly crashes for any players not in the DB in your BG; still probably too unrlieable for rankers to use, defeating the purpose.

-------------------------------------------------------------------------

### ⚠️⚠️⚠️ THIS IS AN EXPERIMENTAL PRE-RELEASE ⚠️⚠️⚠️ ###

### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###
### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###
### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###

###  ⚠️⚠️⚠️ It REQUIRES [CensusPlusTurtle](https://github.com/Lexiebean/CensusPlusTurtle/releases/download/v1.0.3/CensusPlus.v1_0_3.zip) ⚠️⚠️⚠️ ###

You can place `CensusPlus.lua` in `\Turtle WoW\WTF\Account\ACCOUNT\SavedVariables` to use my pre-built CensusPlus database.

### ⚠️⚠️⚠️ It >>> WILL NOT WORK <<< and may even >>> ⚠️⚠️⚠️CRASH YOUR GAME⚠️⚠️⚠️ <<< if you do not have everyone on the Standing list scanned by CensusPlusTurtle ⚠️⚠️⚠️ ###

### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###
### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###
### ⚠️⚠️⚠️ USE AT OWN RISK ⚠️⚠️⚠️ ###

Later I will remove the CensusPlus dependancy. This is just up now for people that want early access.

-------------------------------------------------------------------------

### ORIGINAL README BELOW ###

-------------------------------------------------------------------------

### DISCLAIMER ###
I did not create this addon, nor adjusted the version for HonorSpy. The Turtle version was made by someone who didn't have a GitHub account and just distributed the addon through Discord. To prevent it getting lost, I'm hosting it on my GitHub.

### Turtle WoW
This addon was adapted to the Turtle WOW honor system changes. It is only accurate on turtle wow.

### Install
Download zip of 'master' branch (just click Clone or Download -> Download ZIP), unzip the archive, remove '-master' suffix from folder name and put it in Interface/Addons folder, relaunch WoW.

### About
Addon does all the magic in background.

1. It inspects every player in 'inspect range' which you target or mouseover
2. It syncs your db with other party/raid/bg members and your guildmates on your death
3. It can estimate your (or specific player) onward RP, Rank and Progress, taking into account your (player's) standing and pool size.
3. It can export your internal DB in CSV format to copy-paste it into Google Spreadsheets for future calculations. [Spreadsheet done specially for HonorSpy](https://docs.google.com/spreadsheets/d/1OvZ7PRhrFjRn8IoH8HIPwHfRDEq50uO64YLCsSsjBQc/edit#gid=2113352865), it will estimate RP for all players.
4. It supports automatic weekly pvp reset. Reset day can be configured.
5. You can see how old every player data is in your db by hovering it in table
6. Supports sorting by RP and ThisWeekHonor
7. Limit number of players shown to reduce lag on table open. Default limit is set to: 750.

Options can be invoked by right clicking on the minimap icon.

It only stores players with >15HKs.
Reset day can be configured, default is Wednesday. Reset time is fixed at 10AM UTC.

P.S. Do not be afraid of losing all your data, very likely that another players with HonorSpy will push you their database very soon. The more players use and collects data -> the more up-to-date data you will have. Magic of sync.

### Commands
`/hs show` -> show/hide standings table

`/hs search player_name` -> report specific player's standing

`/hs standby` -> enable/disable addon (in case you disabled it from right-click menu this helps to re-enable it)

### Screenshot

![HonorSpy Screenshot](https://habrastorage.org/files/31b/e92/f9e/31be92f9eb044a53b4eb642d0ca43bbc.png)
