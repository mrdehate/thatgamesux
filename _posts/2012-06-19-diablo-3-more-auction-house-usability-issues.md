---
title: "Diablo 3: More Auction House Usability Issues"
date: "2012-06-19"
categories: 
  - "pc"
  - "review"
  - "role-playing"
tags: 
  - "diablo-3"
  - "game-usability"
  - "gold-auction-house"
  - "gui"
  - "real-money-auction-house"
  - "ui"
  - "usability"
  - "usability-in-gaming"
  - "user-experience"
  - "ux"
---

![](images/diablo-icon.jpg "diablo icon")
I've received a lot of great feedback from last week's article on the [usability of the Diablo 3 auction house](http://www.thatgamesux.com/diablo-3-auction-house-usability-is-hellish-but-not-nightmarish/ "Diablo 3: Auction House Usability is Hellish"). So much feedback in fact, this week I want to cover five more points on the topic:

- Searching for named items
- No arrow key support in named item autocomplete
- Finding items with socketed gems
- Bonus Minimum Damage on accessories
- Unhelpful item recommendations

## Named Item Search
<img src="images/disabled-equipment-search.png" align="right">

A feature that I hadn't actually used much until recently is the named item search. I mentioned in the last article that all of the items in Diablo 3 have randomly generated names. That's not entirely true; certain "legendary" (rarer than rare) items or items that are part of a set both have names that are fixed. A textbox enables the user to directly search for these items, which is handy. But, strangely enough, when entering a named item, it disables the rest of the search criteria.

That doesn't make sense - the name may be fixed, but the stats are as random as anything else. Not only does this make it way harder to find a suitable item, it is also something that you'd never expect. The [Principle of Least Astonishment](http://en.wikipedia.org/wiki/Principle_of_least_astonishment) is one of my favorite design principles, and it's definitely violated here. I was searching here for a legendary dagger called "The Horadric Hamburger", and I got a lot of results:

[![](images/horadric-hamburger.png "horadric hamburger")](images/horadric-hamburger.png)
> That's a lot of burger daggers

When I did this search, I found over 300 instances of The Horadric Hamburger. Each one of them has the same name, but completely different attributes. Why Diablo 3 doesn't let you use the existing interface to continue narrowing down your selection, I have no idea. This means the should-be helpful name search is basically worthless - to make an informed decision, you'll need to continue searching by attributes.

## Keyboard-Supported Autocomplete

![](images/legendary-autocomplete.png "legendary autocomplete")

Here's an easy one to fix - when typing in the name of a legendary or set item, a handy autocomplete box pops up to help guide the user. There are many [examples](http://ui-patterns.com/patterns/Autocomplete) of [autocomplete](http://welie.com/patterns/showPattern.php?patternID=autocomplete) [patterns](http://developer.yahoo.com/ypatterns/selection/autocomplete.html) on the web, and all of them say the user should be able to use the keyboard to make the selection. Using arrow keys is natural here because that's the way it works everywhere else. This doesn't work in Diablo 3 however, which is frustrating. **If you're using a standard control, make it act like a standard control!**

## Finding Items with Socketed Gems

In Diablo 3, the good items generally are "socketed", meaning they can have a gem added to them which provides a special bonus. It's a good way to tailor an item to each character's needs. Items can be sold with either a gem in the socket, or with the socket empty. The auction house doesn't differentiate though if the criteria you are searching for comes from a gem or from the item directly.

This might not seem like a big deal, but an item that gives you +30 strength with an empty socket is way more valuable than an item that gives you 0 bonus strength natively with a gem equipped providing +30 strength. That's something that the player needs to inspect for every potential item they are looking for, which is super annoying.

## Searching for Bonus Minimum Damage

Occasionally, accessories such as rings or amulets provide the wearer with a bonus to the minimum amount of damage they do. It's an affix just like anything else, so just like any other attribute, you should be able to find items that include it. Except, it doesn't work. That's right, there are definitely rings for sale that have +2 minimum physical damage, but if you try to search for them, they will never show up. This is less of a usability issue and more of a straight-up bug, though it's irritating regardless.

## Recommended Items - Belts for Sale

When first opening up the Diablo 3 auction house, what should be a helpful screen appears with recommended items. I'll be the first to admit that I'm not a master at Diablo and I'd love the chance for the game to recommend things that would be good for my character. What I think happens is the game finds the lowest level item that you have equipped, and gives you a whole bunch of recommendations for that:

![](images/recommended-belts.png "recommended belts")
At the moment, it looks like I need a belt, so the game gives me about 500 recommendations. This list can be sorted by the buyout amount, but it doesn't show the armor value like other lists do - probably because theoretically, any item type could be in this list. Regardless, sorting by buyout amount is the only way to filter this data. So how useful really is this list then? Not very much.

I love the idea for recommended items - it would be way better though if I could make a choice up front on what I want recommendations for. Or some kind of filtering mechanism, at least by the primary attribute for the item (so armor, DPS for weapons, etc). The way it is right now, it's just a waste of space - you might as well put a scary Diablo picture in there.

## What Else?

It's clear that the auction house in Diablo 3 has a lot of improving left. What else is grinding your gears? Let me know in the comments below!
