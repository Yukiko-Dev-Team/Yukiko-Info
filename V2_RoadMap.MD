# Yukiko Bot RoadMap
This roadmap show what function we would like to add to the bot and/or are planed. Some may wont make it, if a version is added next to a function you can expect it for this version (You can know what version the bot is in via the `a!bot` commands.) if a function is maked with (**Canary**) it mean you can use it on our Canary version of Yukiko (found on the [release](https://yukiko.app/release) page of our [website](https://Yukiko.app))  
Remember: Yukiko is not our main priority, The Yukiko Dev Team is working on Yukiko on their own time, some of those function might take a long time before being deployed in production.

## Update 2.1.4 (Slash Update)
Info: This update don't fix any bugs nor adds features. this version is a skip of 2.1.34 that aim to remove all legacy commands (message based commands) and replace them with interaction commands (slash commands)

### Mandatory before update:
- [ ] info command set
- [x] /info bot
- [x] /info whois
- [x] /info guild
- [x] /rank
- [x] /ban
- [x] /kick
- [x] /timeout
- [x] /8ball
- [ ] /dice
- [ ] /roll
- [ ] /coinflip
- [x] /avatar
- [x] /osu
- [ ] Music command set
- [x] /music join
- [x] /music play
- [x] /music leave
- [ ] /music repeat
- [ ] /music shuffle
- [ ] /music nowplaying (may be out of the command set as /np)
- [x] /music queue (maybe out of the command ser as /queue)
- [ ] /clear
- [ ] /say
- [x] Add ban logging via events
- [x] add kick logging via events
- [ ] add timeout logging via events
- [x] remove message deleted logging
- [x] remove message edited logging

## Bot Addition

- [ ] Add Yukiko Premium (paid advenced features)
- [ ] Add default role (selected via Website)
- [ ] Add Role selector
- [ ] Add Timeout command
- [ ] Add Poll commands
- [ ] Add Leaderboard (leveling per server and general)
- [ ] Add AFK command
- [ ] Add YouTube Notification
- [ ] Add Twitch Notification
- [ ] Add Playlist save (Voice services)
- [ ] Add URL detector
- [ ] Add Ninja invite detector
- [ ] Add RAID lockdown
- [ ] Add custom commands
- [x] Add Shards to Ping command
- [x] Add Economy system / Give money to user
- [x] Add Slash commands
- [x] Add Shuffle (Voice Services)

### Would be great to release at the same time:
- [ ] Add full event log coverage
- [ ] more to come

## Bot Fixes
- [x] Fix `a!queue` commands (for very long playlist)
- [x] Fix Player break when adding songs or playlist

## Website Addition

## 2.0.1
- [x] Create Project
- [x] Add router
- [x] Add Login
- [x] Add Guild View
- [x] Add Guild Dashboard
- [x] Add Utility component
- [x] Add Roles Component
- [x] Add Channel Component
- [x] Link all guilds component to Guild Dashboard
- [x] Add verified guilds badge
- [x] Add Dev Guilds badge
- [x] Add user profile
- [x] Add "Delete all my data" to profile
- [x] Add Card uploading to user profile
- [x] Protect Guilds access
- [x] Add Status API
- [x] Add Shards Socket to Status
- [x] Add MPS metrics to Status (?)
- [x] Add Ping Metrics to Status Page
