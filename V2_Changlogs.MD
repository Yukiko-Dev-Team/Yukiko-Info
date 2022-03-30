# Yukiko Version 2.1

## Version 2.1.0 
+ Add Playlist Shuffle
+ Add Default Rank
+ Update Channel selection (Now search for logs/HOF/Welcome channel via ID)
+ Update Ping command (argument shards to see all the shards per servers.)  
***AFTER DEPLOY UPDATES***  
+ Add: Discord.bots.gg API updates
+ Add: Canary as YukikoClient status possibility.
+ Update: Presence
+ Update: a!commands now have a DEPRECATION NOTICE.
+ Fix: Error with Asthriona API (Internal)
+ Fix: Error with Ready event (Internal)
+ Fix: error with Datadog
+ fix: Error with a!channel commands.
+ Fix: Error with db.gg API
+ Fix: Yukiko's update timing (Rate Limite)


## Version 2.1.1 
+ Add Shard ID to ping command.
+ Add messageReactionAdd event support (Internal)
+ Add Role Reaction (Early tests, Prototype)
+ Add Birthday command (Prototype)
+ Update Yukiko Client: Add Partials support (Internal)
+ Update Osu Errors messages
+ Update Help command: Bold Yukiko Dev Team Link, Remove Support server link.
+ Removed Slash commands

## Version 2.1.2 
+ Update: Event Handler
+ Update: YukikoClient
+ Update: Error Handling
+ Delete: Event Disconnecting
+ Delete: Event Reconnecting
+ Add: Event ShardDisconnect
+ Add: Event ShardReconnecting
+ Add: Warn (was disabled due to bugs)
+ Add: Mute (Prototype WIP)  

# Version 2.1.3
+ Update [Discord.JS](https://discord.js.org/#/) to V13
+ Update Level System
+ Update Rank command
+ Update Music Player
+ Add Slash commands support
+ Add Prototype Birthday command
+ Add Prototype Self role command
+ Add level management commands
+ Add general Leaderboard
+ Add Per guild Leaderboard
+ Remove Prototype commands from Help
+ Fix Music player create new player on commands that dont require it.

## Version 2.1.31
+ Add Economy support
+ Add Economy commands
+ Add 4 Client Patch (Internal bug fix)

## Version 2.1.32 
info: `Hug`, `Pat` and `Wink` commands (text-based) will be removed in the next version replaced with `/actions`.  
      `Cat`, `Dog` and `Fox` commands (text-base) will be replaced in the next version by the Slash command `/animals`
+ Add Client side Caching
+ Add Pay Command (Slash, Economy)
+ Add Fish Command (Slash, Economy)
+ Add GiveCoins Command (Slash, Economy)
+ Add Balance Command (Slash, Economy)
+ Add Bot user ban support (Internal Tool)
+ Add Action Command (Text)
+ Add Action Command (Slash)
+ Add Warn check command (Text)
+ Add Warn Delete command (text, Inactive)
+ Update Hug Command (Text)
+ Update Pat Command (Text)
+ Update Wink Command (Text)
+ Update Guild Ban (Internal Tool)
+ Update Warn command
+ update Daily coins (Commands)
+ Update Economy (Replacing "Coins" by "Yen")
+ re-enable warn commands

## Version 2.1.33 ([Production](https://yukiko.app/release))
Info: In this update, we have mainly worked on our caching system. This has been made to make the bot faster than requesting the slow database at every message. 
We made our own local caching system (persistant so even if the bot reboot or crash the cache is still there).
A lot of work is still to be made on this update, but at least the bot can take much more request than it used to without making a long queue of Database request.
This update made the bot around 200% faster, Now the only slow link is the connection between both datacenter (Bot, cache, Database, and  website are hosted in differant location.)
```
--- makoto.yukiko.app ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 12ms
rtt min/avg/max/mdev = 0.738/0.818/0.997/0.101 ms
root@ZeroTwo:~#
```
  
+ Extended Cache System (Read more: https://sh.nishikino.xyz/YukikoDelay2.1.33)
+ Add Guild Ban Caching (No Expiration time)
+ Add User Ban Caching (No Expiration time)
+ Add Guild Setting to cache (5 mn to expire)
+ Add Better Error Handling (Client)
+ Remove Client side caching.

## Version 2.1.34 ([Canary](https://yukiko.app/release))
Info: A word on the new Discord restrictions.  
Yukiko as you know it now, is about to change. as Discord decided to enforce the Slash commands System, we have to change the core functions of Yukiko as we wont be able to ready any messages. (except if @ mentioned.) Yukiko is actually reading your messages only looking for the `a!` prefix and a @mention, we do not log any of your messages.  
But as Discord will be removing the content of all messages, we wont be able to look for the prefix (`a!`).  
By this fact we have to accelerate the process of converting all commands to Slash commands.  
Expect a lot of breacking changes in the near future, as we are testing and updating the code for Slash commands.  
  
+ Extended Cache System
+ Add: Deprecation Warning **Message Delete** Logs
+ Add: Deprecation Warning **Message Update** Logs
+ Add: **Info Command set (Slash)**
+ Add: `/whois` to command to Info sub command
+ Add: `/guild` to command to Info sub command
+ Add: `/ping` to command to Info sub command
+ **Add: economy Command set (Slash)**
+ Move: `/fish` command to Economy sub command
+ Move: `/givecoins` to command to Economy sub command
+ Move: `/pay` to command to Economy sub command
+ Move: `/balance` to command to Economy sub command
+ Update: Database Driver
+ Update Divergence Meter command
+ Update: Ping and Shards Data commands
+ Disabled: Ahegao Commands (Temp)

## Version 2.2 ([Production](https://yukiko.app/release))
Info: This version is a skip of 2.1.34, as this one wont touch Canary. 2.2 is made to update the whole bot to Slash commands and gradually remove all legacy commands if released before 30/03/22. This version will mark the end of our massive update of Yukiko Client.  
After this version all update will only be to add commands features, fix bug, and maintain the software until the release of our new MoonDrop client planned to be release with Project "KillJoy"  

+ Removed: Message Delete feature
+ Removed: Message Edited feature
+ Update: Info Command set
+ Add: `bot` to command to Info sub command
+ Add: **Music Command Set**
+ Add: `join` to command to Music sub command
+ Add: `leave` to command to Music sub command
+ Add: `pause` to command to Music sub command
+ Add: `stop` to command to Music sub command
+ Add: `skip` to command to Music sub command
+ Add: `nowplaying` to command to Music sub command
+ Add: `queue` to command to Music sub command
+ Add: `shuffle` to command to Music sub command
+ Add: `clear` to command to Music sub command
+ Add: `loop` to command to Music sub command
+ Add: `volume` to command to Music sub command
+ Add: `seek` to command to Music sub command
+ Add: a new options on /join that allow you to ask to Yukiko to stay in the channel after the queue is over.
+ Add: `play` to command to Info sub command
+ Add: `leave` to command to Info sub command
+ update: General commands set
+ Add: `/ban` to general commands (Needs `BAN_MEMBERS` permissions to work)
+ Add: `/kick` to general commands (Needs `KICK_MEMBERS` permissions to work)
+ Add: `/timeout` to general commands (Needs `MODERATE_MEMBERS` permissions to work) 
+ Add: `/8ball` to general commands
+ Add: `/dice` to general commands
+ Add: `/coinflip` to general commands
+ Add: `/roll` to general commands
+ Add: `/avatar` to general commands
+ Add: `/osu` to general commands
+ Add: `/rank` to general commands

## Version 2.2.1 ([Production](https://yukiko.app/release)) ([Canary](https://yukiko.app/release))
+ Add: Report bot stats to [top.gg](https://top.gg/bot/641626560457342987)
+ fix: `/pay`
+ fix: `/givecoins`
+ Update: Canary command `/info bot` give now the link to invite the Canary version instead of production.
+ Removed: Regions from `/info bot` to set all guild to `Dynamic`


# Known bug: 
+ ~~Player break when adding playlist or song.~~ (Fixed)
+ ~~Shard Reboot without error. (Identified: user permissions issue.)~~ (Fixed)
