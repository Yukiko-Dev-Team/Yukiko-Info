Howdy, everyone!
So what's up with Yukiko uh? last time I wrote a Dev Log was... quite some time ago.   
Let's start with the big changes!  
  
# No more a! commands
Yes, that is true, all message-based commands will be removed in the near future, due to discord always improving, we have to follow in their improvement, this time is for a great reason, first, you have to know actually, bots get a LOT of data, I mean an awful lot of it. what Yukiko is taking from all this data is barely 1%. as said in our privacy policy, we just take IDs, Usernames, Guilds, you are in (if said guilds use Yukiko), the permissions you have and the bot is reading the message sent. this last one is just in case you have sent a message with a command for Yukiko. but some people use those privileges for other intent, and this is exactly what Discord is trying to fight by removing the possibility for bots to read messages. **After August 31, 2022** Yukiko won't be able to read messages, and so won't be able to reply to message commands (even starting with a!)! but to keep the bots working discord release the Slash commands and application in general!  
Ever since this feature was announced, the YTD worked to switch all legacy commands (message-based) to Slash. this massive update is known as Yukiko 2.2. from now on, you can just type `/` in discord and get a list of commands you can use. this makes the development much easier for us, and way more easy usage for you. since now you just have to follow what the bot asks you, so no more no reply when you did something wrong or trying to figure out how to get this bot to reply! here are some examples:
![a list of Slash commands](https://cdn.asthriona.com/i/2022/05/DiscordDevelopment_27052022-050241PM.png)  
here is a list of all the Slash commands just by typing a slash (/) in chat.  
![Args and description for each command](https://cdn.asthriona.com/i/2022/05/DiscordDevelopment_27052022-050305PM.png)  
this is what commands and their argument looks like, with a nice description of what is for what.  
  
# New logging Systems.
Our old Logs system was a bit... dull. but not anymore!  
this is still a work in progress, but now you can log much more than before with Yukiko! like changes made to the channels, Moderations (Kicks, ban, unban, Timeout...) logs change from members like when they change their nicknames, or who gave/removed this or this role.
Much more is coming soon, but for now, we want to get the bot to behave as expected and manage any bug we can find on this new feature.  
The next logging system in line would be role changes, so if someone edits a role permission this will end up in the logs as well.  
you may have noticed that we removed the message logging. to comply with Discord's new privacy policy we decided to remove that feature early.  
In fact, as a lead developer, I never really liked to be able to log other people deleted messages and edited ones. I've added this feature just because it was requested, and to be honest I really wanted this not to be on Yukiko at all. I guess Discord understood that was a privacy issue, and finally decided to put a stop to it, so we very gladly comply with that change very early on.  
here is an example of the new Logging panel on this website.  
![Logging panel](https://cdn.asthriona.com/i/2022/05/chrome_27052022-051255PM.png)  
**Please remember for this feature to work you need to enable it, and select a channel, if the channel selected is deleted or not selected, the bot wont log anything.**
  
# What's next?
We still have a lot of features planned for Yukiko. you can take a look at our [Roadmap](https://github.com/Yukiko-Dev-Team/Yukiko-Info/blob/master/V2_RoadMap.MD) but I think we will keep working on the logging system, make sure it's bug-free, and make the bot more stable.  
as for the next features, I think we will work on bringing back the leaderboard for XP, a way to reset it, and probably some reward.  
we also want to finish migrating all the legacy commands to Slash commands and application settings, we are also working on a way to give roles, via reaction or the new modals system.  
  
Well, that's it for this Dev log 4 folks! see you at the next one!
