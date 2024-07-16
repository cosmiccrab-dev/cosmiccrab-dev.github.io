---
layout: wrapper
title:  "Galactic Devsmith #1"
date: 2019-12-28 12:00:00 -0500
categories: galactic-gunsmith
permalink: "/blog/:categories/:title"
---

<img class="float" src="{{site.baseurl}}/assets/posts/2019-12-20-galactic-devsmith-1/gunsmith_title.png">

## <i class="fas fa-globe-europe"></i> Galactic Devsmith #1

### 2019 in Review

{{ page.date | date_to_string }}

Welcome to the first devlog for Galactic Gunsmith. A gun-crafting RPG set in a far future. You are a gunsmith, a specialized engineer whose skills are highly sought after across the galaxy. Years ago, your father left on an exhibition and mysteriously never returned. You didn't know of his fate until a weak signal on a distant planet drove you to investigate.

It's been about one year since we submitted our JamCraft 2 game and decided we were going to attempt to develop a full commercial release. Since then, we have refined a lot of the core tools and features that made up the [original submission](https://saucyarmadillogames.itch.io/galactic-gunsmith).
I would also like to preface that none of the three developers are doing this full-time. Because of that, we're taking the time to make sure it's as good as it can be. Additionally, a lot can be refined between now and a release date. Keep in mind everything here is subject to change.

## <i class="fas fa-globe-europe"></i> Interface Redesign

<video controls loop muted playsinline src="{{site.baseurl}}/assets/posts/2019-12-20-galactic-devsmith-1/ui.webm"></video>

### Navigation

A major battle this year was redesigning core tools and UI. In the original release, we had two major UI objects: The navigation screen and the crafting screen.
Navigation has been reworked to make it more creatively interactive. Instead of clicking on a list, you physically click on each planet and select various regions to travel to. When we design future planets and their regions, you will be able to travel to them through this screen. We plan to have 6 to 8 planets you can visit.
Additionally, the main menu, pause, and option screens have also been completely redesigned.

### Weapon Crafting

Crafting weapons is an encompassing theme of the game, so we wanted to make sure the UI respects that. The game features 3 categories of weapon parts sporting their own unique stats. Some of these parts you can research and craft, while others will be rewarded through quests or taking down powerful creatures. Before you smith a weapon, you can also get a summary of a gun's final stats including damage, rate of fire, and bullet speed (to name a few). Not all weapon combinations are created equal, however, and you will have to figure out what combinations work best for different combat scenarios.
Another plan is to design a subtle, distinct sounds for each part. This way, every customized gun will have a unique, signature sound.
Designing this has been a major overhaul that took a couple months to get functioning. There's UI objects upon UI objects that make it fairly complicated (UI in GameMaker is hell). The front-end still needs some work/better colors, but we think it's on the right track to be a much better experience than the gamejam version.

## <i class="fas fa-globe-europe"></i> Dialog System

The dialog system from [Wizard's Tyranny](https://saucyarmadillogames.itch.io/wizards-tyranny) was imported into Galactic Gunsmith. We still have to write a lot of dialog for characters, but this will be an essential tool to establish our story. We will have a future devlog going into story and characters, so keep an eye out for that.

## <i class="fas fa-globe-europe"></i> Level Editor

The level editor is completely new feature to the project. Galactic Gunsmith will have manually crafted rooms which require a more sophisticated room editor than what we had available. All planets will have hand-crafted regions, and players will also have the option to make their own. Aside from painting tiles, the editor allows for setting up custom trigger points (like spawning enemies or starting dialog). Josh also included room transitions, allowing a region to stretch across multiple rooms.

## <i class="fas fa-globe-europe"></i> Particles & Effects

<video controls loop muted playsinline src="{{site.baseurl}}/assets/posts/2019-12-20-galactic-devsmith-1/resource-collection.webm"></video>
<video controls loop muted playsinline src="{{site.baseurl}}/assets/posts/2019-12-20-galactic-devsmith-1/dropship.webm"></video>

We have some animations for collecting resources now! Avis made a great debris script that causes little bits of the resource to fly off as you collect it.
Other effects include sparks, gun smoke, exhaust, bloom and shadows. There's a lot of little visual effects that are fitting into the world nicely. Even the dropship animation looks leagues better.

## <i class="fas fa-globe-europe"></i> Up Next

<video controls loop muted playsinline src="{{site.baseurl}}/assets/posts/2019-12-20-galactic-devsmith-1/upnext.webm"></video>

Thanks for taking a look at our progress so far. Making games takes a long time. It takes even longer to make good games. Our focus is shifting on combat and level design in 2020, so we'll have another update in the future with additional details.
If you want to hang out and discuss gamedev stuff, we do have a [Discord](https://discord.gg/ed6JAZa). Feel free to stop by and say hi!

💖🚀 Saucy Armadillo Team
