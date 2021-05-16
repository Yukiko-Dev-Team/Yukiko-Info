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

## Version 2.0.72 ([Canary](https://yukiko.app/release))
+ Update Error logging (Internal)
+ Add Early Support Slash commands
+ Add /rank command (No card)
+ Add /ping command

# Version 2.1.0 (In Dev)
+ Add Playlist Shuffle
+ Add Default Rank
+ Update Channel selection (Now search for logs/HOF/Welcome channel via ID)
+ Update Ping command (argument shards to see all the shards per servers.)

# Known bug: 
+ ~~Player break when adding playlist or song.~~
