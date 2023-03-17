# Yukiko's Next Major Update: 

## Guilds Logs & Audit logs
Our next Major Update is the branch `GuildAuditLogEntry`  
This branch has for goal to Change the logging system we are currently using, that rely on guild changes event.  
This system being very unreliable, and shown weakness since launch, we are using a new system that use Discord AuditLogs events.
This Event is fired up everytime a change is made that is written in the audit logs. (List of event below.)  
Not all events will be processed by Yukiko. Only a select few (which endup being the vast majority of them).  
All line ending with `[!!]` is not planned to be processed by the bot.

### List of categories of events: 
 + Guild: 1
 + Channels: 10-15
 + Members: 20-28
 + Roles: 30-32
 + Invites: 40-42
 + Webhooks: 50-52
 + Emojis: 60-62
 + Messages: 72-75
 + Integrations: 80-82
 + Stage Instances: 83-85
 + Stickers: 90-92
 + Guild Scheduled Events: 100-102
 + Threads: 110-112
 + Application Commands: 121
 + Auto Moderation: 140-145

### Raw list of events sent by Discord ([!!] = not planned to be added to Yukiko.)

- [ ] 1: Guild Update
- [ ] 10: Channel Create
- [ ] 11: Channel Update
- [ ] 12: Channel Delete
- [ ] 13: Channel Overwrite Create
- [ ] 14: Channel Overwrite Update
- [ ] 15: Channel Overwrite Delete
- [ ] 20: Member Kick
- [ ] 21: Member Prune
- [ ] 22: Member Ban Add
- [ ] 23: Member Ban Remove
- [ ] 24: Member Update
- [ ] 25: Member Role Update
- [ ] 26: Member Move
- [ ] 27: Member Disconnect
- [ ] 28: Bot Add
- [ ] 30: Role Create
- [ ] 31: Role Update
- [ ] 32: Role Delete
- [ ] 40: Invite Create
- [ ] 41: Invite Update
- [ ] 42: Invite Delete
- [ ] 50: Webhook Create [!!]
- [ ] 51: Webhook Update [!!]
- [ ] 52: Webhook Delete [!!]
- [ ] 60: Emoji Create
- [ ] 61: Emoji Update
- [ ] 62: Emoji Delete
- [ ] 72: Message Delete [!!]
- [ ] 73: Message Bulk Delete [!!]
- [ ] 74: Message Pin [!!]
- [ ] 75: Message Unpin [!!]
- [ ] 80: Integration Create
- [ ] 81: Integration Update
- [ ] 82: Integration Delete
- [ ] 83: Stage Instance Create
- [ ] 84: Stage Instance Update
- [ ] 85: Stage Instance Delete
- [ ] 90: Sticker Create
- [ ] 91: Sticker Update
- [ ] 92: Sticker Delete
- [ ] 100: Guild Scheduled Event Create
- [ ] 101: Guild Scheduled Event Update
- [ ] 102: Guild Scheduled Event Delete
- [ ] 110: Thread Create
- [ ] 111: Thread Update
- [ ] 112: Thread Delete
- [ ] 121: Application Command Permission Update
- [ ] 140: Auto Moderation Rule Create [!!]
- [ ] 141: Auto Moderation Rule Update [!!]
- [ ] 142: Auto Moderation Rule Delete [!!]
- [ ] 143: Auto Moderation Block Message [!!]
- [ ] 144: Auto Moderation Flag To Channel [!!]
- [ ] 145: Auto Moderation User Communication Disabled [!!]
