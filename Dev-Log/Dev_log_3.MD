Heya!
Asthriona here! I haven't given any update in a while so here we are I guess?
since last time Yukiko grows quite a bit, and we want to thank you all for this!
Yukiko is our main project and for some of us at the Yukiko Dev Team our full-time project. A lot of work has been done since last time, as for example, we re-write the whole bot for version 2.0, and this website as you may have noticed. Rise put a lot of effort into it,  and at the moment I am the one maintaining it. 

## Caching System
We have implemented a new caching system, the bot used to be pretty slow to reply to some commands, and mostly anything that require the Database, now it gets much faster with the new layered caching system, All request includes guilds, their settings, and users levels are on RING 0, that means on much more powerful server since this data is requested almost for each message, this is why starting now every change made on the bot may take up to 5 minutes to apply, this is required to avoid overflowing our databases with requests. I am working on a way to clear the cache or update the cache as you make changes to get said changes updates almost instantly.
Hopefully, this will release soon!

## Yukiko Premium
on the side, we are working on a premium option for Yukiko, As you may know, Yukiko is running off donations, and our own money, but to be able to run, we need servers, and servers cost quite a bit of money. and our resources are getting limited, which blocks us from expanding the bot as we would like. 
Eg: I am working on a new system for the rank cards, a system much faster and lighter for the bot, so we can save up resources on the bot servers and get better performances for you. but for this, we need more servers to run that code. 
Also, we would like some storage near the bot for let's say actions commands or pets commands (a!dog a!cat etc...) or any new features that requires storage for user-generated content. 
all those cost money yet again, all the donations are used for Yukiko's server bills, and anyone who would buy premium will be directly helping us keep the server online. 
We are trying to make the premium features as balanced as possible, so anyone who can't afford premium still can use the bot as usual. except for the music bot, all existing commands will remain free for everyone. 
The changes made to the music bot are minimal. premium users can play music longer than 10 minutes, Shuffle their playlists, and use the repeat function.
you will also be able to choose if you want Yukiko to stay in the channel once the queue is over or leave it. 
Premium will be a Monthly paid feature and per guilds.  
nothing sure for now, but our price should start at the same price as Nitro Classic on Discord ($5 per month per guild.).

we'd like to keep Yukiko as free as possible for as long as possible! so if you feel like it, and want to help us, feel free to do a one-time donation on Ko-fi or monthly on Patreon!
both will give you a role on our support server!

## Logs channels and basics command update
Some of you may know it already but discord is removing the possibility for bots to read users' messages. for now when a message is sent in a channel discord send to everyone (bot included) the message with a lot of data in it, like the users, is the message deleted, the content, timestamp, etc...
the developers have to sort them and only take/keep what they need. 
At the moment we are reading messages that start with Yukiko's prefix (a!) and messages where Yukiko is mentioned, as those could be commands. 
but since Discord will remove these options for bots we have to update all the commands as Slash commands. which means the prefix will become useless, just like the logs commands. Yukiko won't be able to know what message has been edited or deleted. we will do some testing once the deadline passed, but we know for sure those features will be disabled on the bot until we got either white-listed OR we still get Infos on those messages. 
We'll keep you informed on what discord decides to do and what direction the bot will take, on our Twitter [@YukikoApp](https://Twitter.com/YukikoApp) and here as a new Dev Update.

Thanks for reading and have a nice day!
