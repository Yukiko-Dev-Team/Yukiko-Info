# Yukiko Version 2
## Version 2.0.0
+ Complete rewrite
+ Add YukikoClient (Internal)
+ Add Command Handler v2 (Internal)
+ Add Event Handler V1 (Internal)  
+ Add YukikoEmbed (Internal)
+ Add Ping (Commands)
+ Add Server Info (Commands)
+ Add Uptime (Commands)
+ Add Whois (Commands)
+ Add Bot Infos (Commands)
+ Add Help Commands (Commands)
+ Add Owner only category (Sets of commands only usable by bot owner)
+ Add 8ball
+ Add Leveling System
+ Add Rank Cards
+ Add User Model (Internal)
+ Add Ban
+ Add Kick
+ Add Mute
+ Add Binary encode/Decode (Commands)
+ Add Base64 encode/Decode (Commands)
+ Add Ahegao (Commands)
+ Add Cat (commands)
+ Add Dog (commands)
+ Add Fox (commands)
+ Add Hug (commands)
+ Add meme (commands)
+ Add Pat (commands)
+ Add Wink (commands)
+ Add Reddit (commands)
+ Add Divergence Meter
+ Add custom Rank Cards
+ Add level up cards
+ Add member add event
+ Update Voice Services
+ Add Dynamic Presences
+ Add Volume Commands (Voices Services)
+ Add Skip Commands (Voices Services)
+ Add Repeat Commands (Voices Services)
+ Add Pause Commands (Voices Services)
+ Add Dependabot (Internal)
+ Add Say (Commands)
+ Add Yukiko Canary (Bot)
+ Add Monitoring (Internal)

## Version 2.0.1
+ Add Channel Lock (Commands)
+ Update reply on mention
+ Update Skip Commands
+ Fix Disable repeat on Skip commands (Voice Services)
+ Fix Player dont destroy on diconnection


## Version 2.0.2
+ Update Lock (commands)
+ Update Custom cards and guild Icons (Database)
+ Fix an issue with Playlist (Voice Services)
+ Fix an issue with Leave command  (Voices Services)
+ Add Webhook call on ready (Internal)
+ Add XP cooldown

## Version 2.0.3
+ Add Early verified Badge (whois commands)
+ Fix an issue with ban and kick logging

## Version 2.0.4
+ fix an issue with ban commands
+ Fix an issue with kick commands  
+ Fix an issue with XP cooldowns 
+ Fix an issue with lock commands
+ Add  Channel commands

## Version 2.0.5
+ Fix an issue with Channel commands
+ Add OSU commands
+ Update Presence
+ Fix Bot crash if no guild settings on database

## Version 2.0.6
+ Update presences
+ Fix an error with Ahegao commands

## Version 2.0.61
+ fix an error with Message delete logging event 
+ Add give chicken commands
+ Update KFC commands Alias

## Version 2.0.62
+ fix Critical bug on ban commands

## Version 2.0.63
+ Fix an issue with kick commands
+ Add Disconnecting event + webhook (Internal)
+ Add Reconnecting event + Webhook (Internal)
+ Add warn event
+ Add Error event 

## Version 2.0.64
+ Fix an issue with ban commands 
+ ignore DMs 
+ add Dashboard commands 
+ Add eval commands (Owner Only)
+ update Osu commands and usage field 
+ Add RateLimite event 

## Version 2.0.65
+ Add Debug event 
+ Add guild delete event 
+ Add guild add event 
+ Add  Shard Manager 
+ Update cards storage to CDN 
+ Update Datadog (Internal)
+ Update Datadog tyo add ping 
+ Update Reddit command error handling 
+ Update Error on ban command
+ Update error on kick command 
+ Update Rank Cards
+ Disable Unlock commands 
+ Disable lock commands 
+ Fix an issue with adding playlists (Voices Services)
+ Fix an issue on LOADED_PLAYLISTS (Voice services)
+ fix an issue with voice services loading system 
+ Fix an error on Osu commands 

## Version 2.0.66
+ Add per shards monitoring (Internal)
+ Fix an issue on png commands 
+ Fix an issue with event handler

## Version 2.0.67
+ Fix an error with join command (Voices Services)
+ Update Database connection packages
+ remove Owner commands from help command

## Version 2.0.68
+ Add Sharding Support
+ Add Docker support

## Version 2.0.69
+ Add better error handling for debug 
+ Add Channel info commands
+ Add Shards commands (Owner commands)
+ Update Database Connection 
+ Update presence
+ Fix Issue with Lock/Unlock commands 
+ Fix an issue with Ping monitoring
+ Fix an issue with ban/kick logging 

## Version 2.0.70 
+ Add Player count (Monitoring Voice Services)
+ Add color rank cards
+ Re-enable presence on guild info
+ Fix Shard crash on player queue end

## Version 2.0.71 (Production)
+ Update `a!serverinfo` to `a!guild`
+ Update `a!serverinfo` is now an alias for `a!guild`
+ Update `a!queue` commands
+ Add Yukiko Dev Team's playlist to `a!play` command (`a!play devteam`)
+ Add Last played song in `a!queue`
+ Fix `a!queue` commands reply is too long
+ Fix Player break when add music to queue
+ Remove Datadog voice channel count

## Version 2.0.72 
+ Update Error logging (Internal)
+ Add Early Support Slash commands
+ Add /rank command (No card)
+ Add /ping command

# Version 2.1.0 
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


# Version 2.1.1 
+ Add Shard ID to ping command.
+ Add messageReactionAdd event support (Internal)
+ Add Role Reaction (Early tests, Prototype)
+ Add Birthday command (Prototype)
+ Update Yukiko Client: Add Partials support (Internal)
+ Update Osu Errors messages
+ Update Help command: Bold Yukiko Dev Team Link, Remove Support server link.
+ Removed Slash commands

# Version 2.1.2 
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

# Version 2.1.31
+ Add Economy support
+ Add Economy commands
+ Add 4 Client Patch (Internal bug fix)

# Version 2.1.32 
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

# Version 2.1.33 ([Production](https://yukiko.app/release))
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

# Version 2.1.34 ([Canary](https://yukiko.app/release))
Info: A word on the new Discord restriction.  
Yukiko as you know it now, is about to change. as Discord decided to enforce the Slash commands System, we have to change the core functions of Yukiko as we wont be able to ready any messages. (except if @ mentioned.) Yukiko is actually reading your messages only looking for the `a!` prefix and a @mention, we do not log any of your messages.  
But as Discord will be removing the content of all messages, we wont be able to look for the prefix (`a!`).  
By this fact we have to accelerate the process of converting all commands to Slash commands.  
Expect a lot of breacking changes in the near future, as we are testing and updating the code for Slash commands.  
  
+ Extended Cache System
+ Add Deprecation Warning **Message Delete** Logs
+ Add Deprecation Warning **Message Update** Logs

# Known bug: 
+ ~~Player break when adding playlist or song.~~ (Fixed)
+ ~~Shard Reboot without error. (Identified: user permissions issue.)~~ (Fixed)
