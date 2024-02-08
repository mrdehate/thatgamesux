---
title: "Final Fantasy XIII: Where is North?"
date: "2013-03-05"
categories: 
  - "console"
  - "role-playing"
tags: 
  - "final-fantasy"
  - "game-usability"
  - "gui"
  - "rpg"
  - "usability-in-gaming"
  - "ux"
  - "world-map"
---

![Title logo for Final Fantasy XIII](images/title-clean.jpg)

After 35+ hours, I'm finally getting to the point in [Final Fantasy XIII](http://en.wikipedia.org/wiki/Final_Fantasy_XIII) where I need to use the map. Up until now it's been a straightforward affair mostly consisting of following a hallway until the next cutscene. Back when FF XIII was in the news, this caused quite a stir among the Final Fantasy faithful. Personally I like it, because it lets me focus more on the storytelling of the game, and less on the getting lost in the forest.

Anyway, now that I've made it to chapter 11 need the map to navigate the Archylte Steppe, I've discovered a peculiar missing feature: north. The game's map doesn't have any way to tell which direction you're facing. Which is made especially hard because the map is constantly moving depending on which way you're facing. It does have one big landmark to help you out, but even that isn't clearly marked. Let's talk about the map.

## Problem 1: A rotating camera and a rotating map

Here's the first problem: the map's orientation isn't fixed. It moves around, depending on which way the camera is facing. Imagine this sequence. 1) You look at your map. 2) Leaving the menu, you swing the camera 180 degrees so it's facing your character. 3) You re-open the map. At this point, the map will have **flipped upside down** to match the camera.

Here, I made a quick YouTube video of this in action - make sure to keep an eye on the white ridge feature that's right in the middle of the map.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8ER42gKk9gk?si=-ZeKt5X1rXzeNEvC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Moral of the story, this makes it really disorienting when trying to locate anything, because it's impossible to have any non-moving reference points.

## Problem 2: No north, but an unexplained circle

So there's no north on the map, which is constantly moving around depending on the camera angle. But let's look at a (partial) list of areas within the Archylte Steppe:

- Western Benchland
- Central Expanse
- Northern Antrepass
- Eastern Tors
- Northern Highplain
- Southern Funnelway

(Source: [http://finalfantasy.wikia.com/wiki/Archylte\_Steppe#Areas](http://finalfantasy.wikia.com/wiki/Archylte_Steppe#Areas))

Notice all the directions in the area titles? That would be a really convenient way to get a lay of the land...if you knew what any of the directions actually were, that is.

There is, however, a landmark that is designed (I assume anyway) to help navigate the Archylte Steppe. Here it is, on the map:

![Final Fantasy XIII map screen](images/map-zoomed-out.jpg)
> See that funny circle up at the top? That's Cocoon. Notice how it's not listed in the legend on the left either

Here's the problem: **the game never tells the player what this represents**. In fact, it represents Cocoon, a floating moon-like world that's visible in the sky. Once I found that bit of information online, it does give the player a reference point that's visible while wandering around, and can be used to make sure the map is in a consistent orientation.

![Lightning in the Archylte Steppe, with Cocoon in the background](images/lighting-and-cocoon.jpg)

# Conclusion

Maps have been around for a long time, and north has been up since [at least the time of Ptolemy](http://www.straightdope.com/columns/read/441/on-maps-why-is-north-always-up) nearly 2000 years ago. So this is a convention that you probably shouldn't break unless there's a really good reason, and I'm not finding one in Final Fantasy XIII.

In building a map for your game, think about what kind of problems you want the player to solve. Is getting lost a goal of the game? Does it add to the atmosphere or add tension in some way? Or is it only going to add another 10 hours onto the game as they mindlessly wander around trying to find the Eastern Tors? If you're not trying to get the player lost, then put in a reasonable map system, along with what direction is north. It's that easy.

So what do you think about the map in Final Fantasy XIII? Do you have any other examples of maps that are particularly good or bad? I've talked about [the terrible map in the Witcher 2](http://www.thatgamesux.com/getting-lost-in-the-witcher-2-how-not-to-build-a-map/ "Getting Lost in The Witcher 2: How Not to Build a Map") before, I'm sure there are more examples out there. Give a shout out in the comments!
