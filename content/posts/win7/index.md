+++
title = 'Windows 7, eWaste, and the modern day Malware'
date = 2023-02-23T05:33:20-05:00
draft = false
tags = ['Tech', 'Malware', ]
+++

Windows 7 is an operating system that runs near and dear to my heart.

<!--more-->
I do admit that I have a little bit of nostalgia towards Windows 7, from the skeuomorphism of the calculator app, to the lovely blues and cyans that fill the Frutiger Aero aesthetic. I have fond(ish) memories of filling up my family computer with all different types of malware. Exploring all these interesting osbcure websites that I probably only saw through advertisements or heard through word of mouth.

![A screenshot of a Windows 7 desktop taken from an old Toshiba laptop](/posts/win7/win7desktop.png)

Windows 7 in my mind was the last era that we truly had "The Wild West" of the internet, and that's not necessarily a bad thing, *nor would I say it's a particularly great thing either*.

The way that I view how Windows 7 was utilized was in the types of malware or scareware people developed for it. Windows 7 was the first operating system for countless individuals, and was one of the widest used computers on the internet.
## Lets look at some statistics! Yay!
A chart from Statcounter GlobalStats shows us a map of Operating System usage in the 2012 year, with Windows 7 staying solidly in the 49-52 percentage.

![a chart by Globalstats](/posts/win7/globalstatschart.png)

Luckily for us, we have an rough number of how many computers not only were running Windows 7, but also how many of them were connected online in 2012, and that's only possible due to the [Carna Botnet](https://en.wikipedia.org/wiki/Carna_botnet). The Carna botnet was a nonmalicious entity that recorded pings on unsecured routers online. ([If you want to learn more information outside of broad strokes, may I recommend Jack Rhysider's Darknet Diaries episode on the Carna Botnet?](https://darknetdiaries.com/episode/13/)) All you really need to know about the Carna botnet for this post is that it recorded 1.3 billion active addresses and 729 million reported DNS records.Taking another statistic from [Statistica.com](https://www.statista.com/statistics/748551/worldwide-households-with-computer/), 41.4% of the worldwide population of 2012 had atleast one computer.

Combining all of these statistics mathmatically leads us with **2,922,840,000** internet capable devices, or an estimated 4 computers per household, and **1,640,882,376** household devices running Windows 7 in 2012.

![A gif demonstrating the online activity of routers impacted by the Carna botnet](https://upload.wikimedia.org/wikipedia/commons/1/1a/Carnabotnet_geovideo_lowres.gif)

Tech is naturally a wasteful industry, however, I think that we oftentimes overlook how truly wasteful we've gotten within the past 20 years. With constant innovation comes the creation of tech that just straight up *ISN'T* built to last.

Caps burst, batteries leak, and my god, we're even starting to experience PCB tracerot in older consoles. I would absolutely love to say that there isn't a motive as to why this has been not only a consistent problem, but an escalating one at that. There's a simple and easy truth as to why it seems to be that tech keeps getting more fragile in certain aspects as the technology gets better.

## The problem is capitalism
Didn't think I would get political, huh?

Have you ever heard the anecdote about mattresses or more well known, light bulbs?

Well, Capitalism theoretically exists on the basis of supply and demand, where in a perfect existence, a high supply and low demand commodity would be cheap. Unfortunately (or fortunately) for all of us, the world doesn't conform to an Economy textbook.

Lightbulbs and mattresses were fron conception, both low demand commodity items that are produced very cheaply, and they both respectfully have two different solutions to being low demand items, they are as such:
* Planned Obsolescence
* Arbitrarily increase the price

These are both methods employed by hardware companies in the modern day. Computers and and the components inside of them can last ~5 years of decent to well usage before ever having to upgrade a component. According to Steam, 5% of PC gamers are **still** using a GPU from 2016. People have only just recently started to upgrade their graphics cards.

Like mattresses, people don't really buy new stock until its a necessity so they increase the profit margins as much as they can get away with, and like lightbulbs, hardware manufacturers have a tendency to *force* the hand of their most loyal users via planned obsolescence. The biggest example in recent years has to be Windows 11's TPM 2.0 requirements, which many desktop users, especially in the gaming sphere, did not care about.

Unfortunately, we can view the 1.6 million Windows 7 users in 2012 also as the number of computers laptops, their components, and their accessories thrown into landfills. Very little of what was once a cherished past is properly salvageable, and a lot of it gives credit to the constant advancement in the complexity of software. 64 Megabytes of RAM in 2023 is nowhere as useful as it was in 1998. Hell, an image loaded onto a web browser would easily overtake that amount.

## The Ghost of Malware Past
![A render of the Adware Desktop Assistant program Bonzi Buddy](https://upload.wikimedia.org/wikipedia/en/9/9d/Bonzi_Buddy.png)

I know it's a little bit generic to be talking about fucking Bonzi Buddy when referring to malware. I know all about the memes centering around him, but I'm talking about him for a good reason. Bonzi Buddy is the perfect dummy to use as an example of malware of the Wild West.

Bonzi Buddy is mostly nonmalicious. The most malicious aspects of Bonzi not comes from intentional designs, but by poor planning. Bonzi Buddy gets called numerous different names. Spyware, Adware, Trojan. All of these are true in the definition sense.

Bonzi Buddy works by behaving as an assistant for your computer. Think of it like Siri or Cortana but half as intelligent and twice as annoying. Bonzi Software collected user data to send to their centralized server to sell to advertisers. Stuff like their browsing history was monitored through unwarranted changes to their system, like changing their home page to bonzi.com. If bonzi buddy couldn't connect to the bonzi servers, it will store user data on their system, waiting for a reconnection to the central server.

As you can probably assume, this proved disastrous on people's hard drives, most of which didn't break a gigabyte or two. People will browse the internet for hours upon hours, unaware that their hard drives were potentially overwriting key system files for junk userdata, waiting to be sent to Bonzi Software.

They just simply don't make malware like they used to. (lol)

## Userdata? For nerds!
A new concept started in 2009, Cryptocurrency. A decentralized, purely speculative, unmoderated avenue for exchanging currency between hands. For malware developers, this was the dream.

This created a direct line for people to financially profit from developing malicious software, not saying everybody who used bitcoin did it for malicious purposes. But after the invention of Bitcoin, there was a noticable decrease in the development of Adware and spyware from small groups. Out went Adware, and in came Ransomware.

## Ransomware and Bitcoin, Partners in Crime
With the growth of Cryptocurrencies like Bitcoin and Ethereum, there had been a drastic increase in the cost of cybercrimes. In 2009 alone, the year Bitcoin was invented, there was an immediate doubling in the cost of cybercrimes, creating an exponential steepness or a parabola from that moment onwards.

![A chart showing a timeline for the number of transactions for cryptocurrencies](/posts/win7/transactionscrypto.png)![A chart showing a timeline for the cost of cybercrimes that have occurred, with the year that Bitcoin was created being marked](/posts/win7/cybercrimechart.png)

As malware moved away from trojan adware to purely profits, you can see less attempts of malicious software attempting to gain user trust. The wild west of the internet is over, there is now no question what is and what isn't malware anymore. Nondestructive malware is almost as rare as nonmalicious software was back then.

The internet is a safer place for the average user. Instead of being the target, average users have become collateral damage. The computers running Windows 7 are tools used, typically by Government Backed groups, to spread to more desirable systems.
## The Future Of Malware
With Malware groups moving towards more profit motives, its only obvious that they will continue to attack where there's money. Average users aren't where the money is.

If I was to make a guess as to where computing and malware is gonna go in the future, I'd wager a bet on a heavier focus on Thin Clients and Cloud-based computing. Chromebooks were a sign for companies like Microsoft that it's a profitable business. The only major downside is that these thinclients would be relying on a server for heavier processes, and those servers would definitely be targets for attacks of all sort.

How do you think computers and malware will change with time? [I'd love to hear your thoughts](https://wetdry.world/@ioletsgo/111199759552863724)!
