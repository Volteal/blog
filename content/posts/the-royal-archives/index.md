+++
title = "The Royal Archives"
date = "2025-06-01T12:10:37+02:00"
author = "Angela Ridder"
authorTwitter = "VoltealCodeGoat"
cover = ""
tags = ["Programming", "Golang", "World of Warcraft", "Projects"]
keywords = ["", ""]
description = "A post where I explain what my pet project \"The Royal Archives\" is and how I am making it."
showFullContent = false
readingTime = true
hideComments = true
draft = flase
+++

## What is the Royal Archives?

The Royal Archives is a World of Warcraft RP Community project to create a website that can bring all roleplayers and the RP community together. This concept is not meant to replace how things are being done and/or managed currently it is meant to be supplimental to it. I can mostly speak for Moon Guard but a lot of events are advertised on Discord and reach is limited by who sees it, a lot of character profiles are hosted on a variety of different wikis, in particullar a lot of them are hosted on fandom.com wikis who keeps defacing all their articles with more and more disruptive advertisements that can not be removed. We want to offer an alternative to fandom.com for the WoW community. Made by the World of Warcraft community, for the communty. The only advertisements you see on our website will be **for player run**, **in-game** events which \***\*will never\*\*** be paid for.

## Who Will This Serve?

**Everyone** at least everyone who plays on the US RP Realms of World of Warcraft. This is a project that was started by me, and I play mainly on Moon Guard (US) but with Blizzard making large moves to remove the barriers between playing with your friends from other realms with cross-faction groups, guilds, and most recently cross-server guilds we see no need to arbitrarily limit out site to only one RP realm. The idea for this site is to help people find other players, RP scenes, events, and communities so there is no reason to exclude **Wyrmrest Accord (US)**, **Emerald Dream (US)**, and the other RP realms on the America servers from being able to use our site.

## Minimum Viable Product

I am currently workingn on the proof of concept for this site. The proof of concept is not going to have all the features that I want to have in the full release but it will be enough to to start a closed-alpha test and get user feedback on UI and functionality.

- **Base Site Module**: The basic website and its static pages: Home Page, About, Terms, FAQ, Contact, ETC pages.
- **User Module**: Manage user accounts and information. At most this will require a (non-public) email, display name, password, and visibility toggle.
- **Character Module**: Manage roleplay characters that are linked to your user account.
- **Event Module**: Manage events that are linked to your user account and characters.

## Full 1.0 Release

- **Guild Module**: Guilds can be managed by the Guild Master and their officers.
- **News Module**: A module spesifically to find In-Character news papers.
- **Adventure Module**: A place for user created (in universe) stories, poems, etc.
- **Noticeboard Module**: A place to put notices that have been posted in certain cities / major locations across the in-game world.

## Image Uploads Hurdles and Concerns

These are the things that need to be figured out how to handle in a cost effective manner first. While I would love to let users upload their awesome art to the website and hosting it for them there are important things that need to be considered. Images require a lot of storage space which is expensive (starting at $10/month for 100GB), allowing users to upload things is also a security risk. It's not that I do not trust the community, but the internet is full of threat actors and that is to mention malicious trolls with nothing better to do who could try uploading illigal content or malicious code. Stolen art is also an issue that needs to be considered which means I will need to add DMCA compliance, and lord knows what else with me being based out of the EU. Of course there needs to be a final answer to the AI question.

## Far Future Ideas

These ideas are things I want to do but they will be patched in over time. There are a lot of things I need to consider and everything mentioned above has a higher priority at the moment. Although the TRP Back-up service might see it's own smaller app release at some point before the Archives are finished.

- A TRP 3 Profile Import/back-up service.
- Community made Roleplay Guides / Advice pages.
- WoW head news integration? (not sure about this).
- Windows/Mac/Linux Desktop App. (Why? Because it would be a good learning project + Automated TRP backups)
- A Wiki style sub-website for fanon lore.

## Domain, Server, Storage, Etc Costs

You might read the ambitious concept and be wondering how much this is going to cost and how I play to pay for it all when I said that the site would not have any ads or paid features. This is a fair question, and I am not entirely sure on the how yet. Starting off I doubt that the hosting would be more than $6 a month (1GB on a CPU, 25GB SSD, 1TB Transfer) on Digital Ocean which should be enough for at least the closed-alpha.

For the open beta I can scale up as needed and I doubt that the need will initially be over $18 per month (2 GB on 2 CPUs, 60 GB SSD, 3 TB Transfere), $10 for 100 GB of storage space, $15 for a managed database, $2 for daily server backups, for a total of about $45 per month (rounded up). This would come up to $540 / year, 551 if we include the yearly renewal for the .com Domain name.

So, how do I plan paying for this if it starts really scaling up? The reality is that the only correct answer to me personally is donations. I don't want to enshitify the application by adding ads or paywalling features. If it takes off more than a curiosity I will set up a Patreon or something like that, the money will be used cover server and maintenance costs and anything left over will be set aside to use for the project. The dream, of course, is that I hope to eventually be able to compensate the volenteers for their hard work.

## Tech Stack Info

The stack for this application is simple and to the point. I originally considered using PHP and in particular Laravel which would make likely make it easier to build the initial concept application. But I want to also take this as a learning oportunity and as a chance to get back to basics rather than rely on a framework. The idea is to use a minimual amount of packages to keep reliance on other people's work to a minumum. I would rather not have a situation where a package being abandoned or discointinued causes issues down the road.

The main things used to create The Royal Archives are:

- Golang - The main programming language.
- Tailwind - CSS Library
- Templ - For templating
- HTMX or AlpineJS - For website interactivity

## How to Contribute

Were not currently at a stage where we need more people to contribute. We are still working on making our Minimum Viable Product. Once we have that finished and we start letitng people test the closed-alpha we will start looking for people to help with the project. If you are interested however you can contact me on discord () or in-game (on Ishathepious, Bishopishala, Abbessishala, Volteal, Iritheseeker). Once we get out of the MVP stage we're going to need programmers, artists, and UX designers, and at least one cybersecurity expert to advise.

## Links

- [Project Github](https://github.com/VoltealProductions/the-royal-archives-api)
- [My Twitch](https://www.twitch.tv/erasvolteal) Where I stream development.
- Community Discord: TBD
- [My BlueSky](https://bsky.app/profile/angelaridder.com) Where I will likely post updates.

## ~ Angela Ridder
