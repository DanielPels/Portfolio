---
title: "First Go Project"
date: 2018-01-04T21:46:20+02:00
draft: false
---
For my first project I decided to write a tool to help me earn virtual money(ISK) in Eve online.

Fighting(PVP) and taking contol of systems is one of the core elements in Eve online, each player has a spaceship with modules at their disposal to use in those fights.
Getting those items can take quite a while, each player has to move their ship with modules from a trade-hub to their favorite system.
The market in Eve online is another core element that can be a lucrative business. Why not take advantage of that?

# killmail
If a player dies in their spaceship the player that killed them will receive a killmail, those killmails are often posten on [zKillboard](http://zkillboard.com).
Killmails are a detailed log of what has been lost.

# The catch
In the intrest of making virtual money and starting a lucrative business we will use those killmails to our advantage.
Playing the game my self I know that moving ships can be a pain. Players who wish to fight do not wish to wait a long time to move their ships and modules.
So we make two assumptions:

- Players are lazy
- Players want it fast

# Plan
* Sell items in hot combat areas
* Know what players are flying and sell those items

The first one is easy, the second one little less easy.
My idea was to use killmails to see what players lost in combat and to only stock those items that where lost.

# Goal
Write a crawler that gathers killmail information.

# Learn
Using the drive to learn a new language and making some virtual money, I decided to learn [Go](https://golang.org/) with the help of [Udemy course](https://www.udemy.com/learn-how-to-code/learn/v4/overview) by Todd McLeod. After lots of frustrating moments.

* Forgetting capital letter for json struct(!!!)
* Figuring how slices, maps and pointers work
* Parsing and formatting time
* Making html templates work
* Working out how to use GoRoutines effectively

I got it **working**.

# Crawler
[EveKillmailCrawler](https://github.com/DanielPels/eveKillmailCrawler) has been created. Letting this tool run overnight on my Raspberry Pi, gathering all the data I need to see what is and is not in demand.

# Reward
After knowing what to buy and investing 300 mil ISK in ships and modules to sell I started trading.
One week after trading my wallet balance was around ~1 billion ISK, nice profit for one week.

# Conclusion
Learning Go was a great move, the language is fun and works.