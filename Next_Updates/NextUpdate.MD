# Yukiko's Next Major Update: 

## Guilds Logs & Audit logs
Our next Major Update is the branch `GuildAuditLogEntry`  
This branch has for goal to Change the logging system we are currently using, that rely on guild changes event.  
This system being very unreliable, and shown weakness since launch, we are using a new system that use Discord AuditLogs events.
This Event is fired up everytime a change is made that is written in the audit logs. (List of event below.)  
Not all events will be processed by Yukiko. Only a select few (which endup being the vast majority of them).  
All line ending with `[!!]` is not planned to be processed by the bot.  
  
Info: All messages related event won't be Logged, as we can't log the message itself.  
We are also choosing not to, for Users Privacy reasons.  
  
**This Feature will also remove the old logging system**

### Status: 
Status: Indev  
Branch: `Canary`.  
Release estimate: `Unknown`  

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
 + Auto-Moderation: 140-145

### Raw list of events sent by Discord ([!!] = not planned to be added to Yukiko.)

- [x] 1: Guild Update
- [x] 10: Channel Create
- [x] 11: Channel Update
- [x] 12: Channel Delete
- [x] 13: Channel Overwrite Create [!!]
- [x] 14: Channel Overwrite Update [!!]
- [x] 15: Channel Overwrite Delete [!!]
- [x] 20: Member Kick
- [x] 21: Member Prune [!!]
- [x] 22: Member Ban Add
- [x] 23: Member Ban Remove
- [x] 24: Member Update
- [x] 25: Member Role Update
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

### Developper Notes: 
Invites logging are not working, so won't be added yet.
Voice channels logging still suffers some issues, some logs won't be added just yet.

## Yukiko OCR System
![Google Tesseract Logo](https://upload.wikimedia.org/wikipedia/commons/7/78/Tesseract_OCR_logo_%28Google%29.png)  
  
### Status: 
Status: Early Stage  
Branch: `None`.  
Release estimate: `Unknown`  
  
We are currently working on adding a OCR feature to Yukiko.  
This feature will allow you to scan a image, and get the text from it.
To use it You would have to send an image and right click on it, then hover "apps" and then click on "Yukiko OCR"
We are still working on what technology we will use, and strongly considering an in house solution, but we are also looking into Google Tesseract OCR.  
Our end goal would be to have a in house solution, for now the plan would be to start with Google until we have a working solution.  
Yukiko's OCR would be available for general public too, using Stellar's API.  
This project is still in early stages, and no ETA or confirmation that will happen is available at this time.
