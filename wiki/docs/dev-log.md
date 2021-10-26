# **Developer Logs**

A hopefully **weekly** blog post from the past week of what has been worked on with **AdventuresCraft**!

## 10/26/2021 - The Beginning

### The last few months 
Since this is the first Dev Log, lets recap what has been happening over the last few months.

On `08/20/2021` we released a brand new Prison Gamemode! I worked on this for a few months trying to create a really fun Prison Gamemode with MMORPG aspects and some unique features. 

I saw a LOT of the popular Prison servers and they're all super common, most have flaws, are low-quality, and looked rushed. This motivated me to work on my own Prison project because I take pride in the quality and uniqueness of my gamemode. Ensuring the Players have a great and fun experience is my top priority. 

I could go more in-depth into this time period and what happened, but after working on it for a few months, we published it for testing and to guage feedback. Listening to the feedback from some of my closer peers, I realized that I should primarily focus on the Adventure Gamemode and I could bring the Prison aspects over to it, because I was sorta already doing that with the Prison gamemode.

So, a few days after releasing the Prison Gamemode, I realized I should completely shift my priorities back to the Adventure Gamemode. 

The Prison Gamemode still exists on the server, but will be removed once I finish my revamp of the Adventure Gamemode. I still do believe the Prison Gamemode hit the quality I set out to acheive, but there was definitly other feedback about it which I'd need to implement into the gamemode to improve it. Who know what the future may hold, but for now the Prison Gamemode will be archived.

### Learning Java
So during the time period of creating the Prison gamemode, I actually began to learn Java. Before this, I was completely reliant on Plugins to create my gamemodes. Plugins are used by every single server, of course some use private, public, or maybe even a mix of both. 

If you're unfamiliar with Plugins, they're basically building blocks made for ordinary people who have knowledge of programming. One plugin which I still use and have great pride in, is [BetonQuest](https://docs.betonquest.org/RELEASE/) which is used to easily create Quests!

So of course learning Java and becoming efficient with it, took a fair amount of time. I tried learning is 3 seperate times and quit the first two. Luckily the third time I pushed through, stuck with it, and finally started to understand it. That's when I created my [first plugin](https://github.com/Dancull47/Basic-Captcha-Plugin). I never actually used this Plugin for anything, I just thought the idea was simple and I could use it to further my understanding while still learning, and it was really helpful in that regard!

At this point I'm about 7 months into working with Java and I feel much more comfortable and confident in my abilities. Although I would never brag about it, because I don't think my Java is amazing, but I'm able to accomplish literally everything I want or think of with Java at this point.

So why was learning Java such a huge milestone in my "Server Career?" Well, Java gives you practically complete control over literally everything you want to do. Plugins are building blocks, but sometimes you don't need all the extra things the include. Other times you have a larger systems which are used throughout multiple Plugins, but then you need to make changes to every single Plugin, rather than 1 central file. Plus there a LOT of things you can do in Java to make your life sooo much easier when working in this field, some are simply indescribable. I have to say though, learning Java is honestly my most proudest accomplishment ever, it feels amazing creating systems and all the aspects which go into that. 

### Adventure Gamemode 2.0 (Technical)
Since I learned became competent with Java, I decided to redo a lot of things within the Adventure gamemode to improve it in many ways, especially scalability and easily making changes without having to change that one thing in a bunch of locations. 

Additionally, I got a much more competent with the Plugins I use, such as BetonQuest, so I went back to improve and optimize every single quest. I did the same with Mobs, GUIs, handling of many things, and so much more.

Of course all of these things take time. I'd say the biggest part of it, is building the inital system, because once you got that made, you can easily expand it to many other areas. The initial system will take the longest because you're trying to think of many different parts, like how will Players try to break this, and also planning for the future.

Plus once you come up with one system, you might think of another necessary system, like Anti-Dupe measures. So a lot of time is spent building the inital system, but once that's done, it takes a lot less time to maintain, imrpove, and expand in the future when you want to, as long as your system was efficiently made.

### Adventure Gamemode 2.0 (Gameplay)
When going back through every single area in the world to redo the Quests, I realized there are many changes I can make to improve the area. Some were a little bit more simple, such as adding a few more NPCs, with more quests, or mechanics. Other times it was literally scrapping an entire area such as Hell.

Ya, unfortunately I scrapped Hell because I really didn't like the area itself. It wasn't too appealing to me, although I would say it had the coolest public boss fight, which actually required some strategy to defeat. Basically, Ghastly couldn't be damaged by players, so Ghastly would teleport around Hell spawning in waves of enemies. Each enemy had its own amount of damage it would deal to Ghastly upon dying, harder mobs dealt more, smaller mobs dealt far less. After 3 waves Ghastly would be defeated and the players rewarded. 

The Ghastly fight was still relatively basic, but I've tried staying away from too complicated of fights, because I don't want the player to be confused in the earlier stages, which Hell was mid-game. Of course in the future when we have an actual audience, which I can guage feedback from about difficulty, I'll see how far I can expand in terms of complexity for boss fights, because I'd like to make them more difficult, than just hit the boss until it dies.

Why did I remove Hell? 1. I didn't like the area. I felt Hell should be scaled much larger and really be different. I want full sized WITHERS walking around, and bigger things like that. Things which will excite the player and make the gameplay feel different. 2. Hell was originated when I was really first making the Gamemode, so I had much less knowledge of basically everything back then. Getting Hell to the point I wanted it would take a LOT of work, on top of the already TON of work I'm doing for the 2.0 update.

I have also completely removed the 6 mines. They were really basic, and made even earlier than Hell. Since I now have a much better understanding of what I want this Gamemode to be, I realize I want much larger scale areas, which I can put a lot more content into. 

The good news is that I replaced the 6 mines with a Cavern, which is much much larger. I'm really excited for players to see the Cavern, because it's my newest Content Area, and it benefitted greatly from my much more knowledgable approch and planning. Plus, I already have future expansion content planned to branch off from that area as well.

Since Hell was removed and that was the "mid-game" area, I had to rescale the Void, which was end-game. I'd say the Void is still end-game, but scaled down to where Hell was in terms of enemy health, damage, etc, so Players won't find a huge jump in difficulty when going from say the Castle to the Void.

Another thing I realized was how much lower quality content I put in the game. Companions are basically friendly versions of enemies, which you can summon to fight for you. These were implmented very early into making this gamemode and I cringed when I saw how poorly they were made. So I completely scrapped this system for now, until I can dedicate time to perfecting it into the perfect system I desire. The same goes for Stews & Totems, which were basically just replacements of Potions. I completely scrapped them for now and will reimplement them in a better way.

Spells and Wands have also been scaled back heavily. I had a LOT of filler spells in there originally, which I think now we might be "lacking" on the amount of spells we have, but at least I can create more easily and add them with futurue content updates. I didn't like a lot of the low quality filler spells and felt it was harder to maintain and balance around them.

The Mount system is in the same field. Although, I haven't actually got around to that yet. I haven't scrapped it or redone it yet...I think I'm going to leave the Mounts which are currently in-game, but just improve the overall Mounting system for controlling them. There's basically just a basic Horse & Pig Mount, but also one of the Void Bosses drops a mount too, which I don't want to get rid of. So in the future I'll revamp the entire system and add in many more mounts, but for now it'll be a much much smaller scaled system.

Oh yea, I think the final system which was scaled down or scrapped were some Weapon Types. Once again, I felt like there was just a lot of lower quality filler items out there. I wanted to reduce the amount so I could have better control over and properly balance everything, then add more throughout new content. The most notable weapon type removed is Whips, but there were a few others as well. Additionally, I plan to redo Bows because I don't think Minecraft's Vanilla bows fit well into our Gamemode. My idea for bows is to make them a simple Left-Click to shoot out an arrow, so it can be much more rapidly used, but of course that's a larger system and not something I want to create before releasing 2.0.

Thought of one more...The Home system! During our Beta, Homes were actually Islands. Then going into release I wanted to diversify from Islands to Plots, because I thought that would be better, but I was completely wrong. Plots are so UGLY(:P)! Islands on the other hand allow players to not see others if they don't want to. Also I plan to add a Central Area to Homes, sorta like a Hub area, which will contain Quests relating to Homes and maybe other things to improve the Home experience.

### Releasing 2.0
I'm hoping to be able to release 2.0 before December. I feel like I've finished most of the core systems which I set out to. Although there are still a lot of things I need to get done before I really want to release it.

The release will require a complete wipe of the entire main server, which sucks. I plan to compensate players who feel "robbed" of what they earned, because I understand that. Although I'm hoping nobody will be too upset because we haven't had many players, especially in the last few months.

I'd like to start out 2.0 as a BETA, which could be reset before another full release, because I'm expecting there to be unexpected bugs which I'll need to patch up. 

I also plan to begin the marketing of AdventuresCraft hopefully a bit after the beta if I get enough feedback. My desire is to avoid marketing a gamemode with a lot of bugs in it to brand new players, but might be necessary if we don't have enough people who care to test it currently.

### Closing Statement
Wow, I've been typing for at least an hour now and I am so drained! I originally planned on detailing some of the things I've worked on this past week, but realize I've gone way too deep into a recap rabbit hole, so I'll save it for the next post! 

I doubt anyone will actually read this to be honest, but I do wanna say, I've put SO MUCH time, work, and effort into creating AdventuresCraft, it's insane! I've been working on this project for almost 2 years. I originally had the desire to start learning how to work with Minecraft Servers on 12/24/2019, and really began learning not too long after.

I would say during the first entire year of working was really all just learning and I didn't realize it at the time. Some aspects of the Server were done during that time and I look back at how bad it is now, and that's why I'm redoing so much of it.

For the past 2 years, I've easily spent around 5,000 hours working and learning with this entire project. Many days I spend more than 12 hours just working on the Server itself, it's insane.

I believe in AdventuresCraft a ton, and I really cannot wait to see what the future holds. Hopefully I look back on this one day and become even more proud than I already am with how far I've come :D

Well, that's it. Have a great day!