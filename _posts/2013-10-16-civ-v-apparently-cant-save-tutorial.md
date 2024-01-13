---
title: "Civ V: Apparently You Can't Save the Tutorial?"
date: "2013-10-16"
categories: 
  - "pc"
  - "rts"
---

Civilization V ([Steam link](http://store.steampowered.com/app/8930/)) is the most recent iteration of the legendary [Civilization series](http://en.wikipedia.org/wiki/Civilization_(series)) of turn-based strategy titles. I have a soft spot for the series, but I haven't played many just due to my inability to stop the "one more turn" syndrome. They are epic, complicated, and detailed, and have the incredible ability to destroy large blocks of time in one shot.

Since this was the first Civ title (excluding [Civ Revolution](http://thatgamesux.com/post/a-case-study-in-how-not-to-handle-errors)) that I've played in a long time, I figured I would play through the tutorial. While the tutorial is for sure a tiny version of a real game, it isn't like a 5-minute romp - there's lots of text and details to read, which I thought was a good idea. But strangely enough, despite what could be a relatively lengthy affair, Civ V doesn't support saving of the tutorial. At least, that's the conclusion I came to, because the game sure doesn't make that clear.

## The Tutorial

Let's start by checking out the tutorial screen. [![civv-tutorial main screen](images/tutorial-main-screen-1024x653.png)](http://thatgamesux.com/wp-content/uploads/2013/10/tutorial-main-screen.png)

The giant button at the top, that's what I chose. It's basically a normal game, but with all the help advisors turned on, constantly giving you advice on what's going on.

## Save Required

Okay, so I started playing a game, reading through all the various help texts, and turning them off, one by one. I wanted to play through this game to its completion, however, I encountered [this bug](http://steamcommunity.com/app/8930/discussions/0/864969953356808105/) that rendered my mouse cursor invisible. That's really a downer for Civ V.

The resolution to this bug is, of course, quit and restart. So I set about to try and save my game. Clicking on the menu link in the upper right brings me up the menu...suspiciously absent any save functionality:

[![civv-in game menu](images/in-game-menu-1024x653.png)](http://thatgamesux.com/wp-content/uploads/2013/10/in-game-menu.png)

## Save Absent

Okay, so here's my first beef with this: why would you not want the user to save the game? I don't understand why this would be the case. Maybe "normal" people can blitz through the tutorial in 15 minutes, I don't know. I just don't get why you'd disable the save function here.

Maybe that doesn't count as a beef, but here's one for sure: if you're going to do something like this, at least tell the user what's happening. I have an expectation set by many (many) hours of of PC strategy gaming that says I can save my game in the menu, whenever I want to.

A much better solution would be to have the save command there, just disabled with a little message saying "you can't save the tutorial". I still would think it was dumb, but at least I would know for sure what's going on.

## Trickery

Here's where things get even more confusing. After clicking around on other things that I knew shouldn't contain the save command (which was really hard, mind you, since I didn't have a mouse cursor), I gave up and clicked "Exit to Main Menu". And I got this message:

[![civv-are you sure](images/are-you-sure-cropped.png)](http://thatgamesux.com/wp-content/uploads/2013/10/are-you-sure-cropped.png)

Notice the part that says "...without saving your game". This message totally implies that you can, in fact, save your game.

Additional bonus complaint: this confirmation appears every time you quit to main menu, even if you saved your game seconds before. I wish it was a little smarter, because every time it says "without saving your game" I get a little bit nervous inside because I don't want to lose any data. Don't scare your users, that's my protip here.

I hunted around a little bit more and discovered this tooltip that appears when you hover over the "menu" button in-game:

[![civv-save hover-cropped](images/save-hover-cropped.png)](http://thatgamesux.com/wp-content/uploads/2013/10/save-hover-cropped.png)

Well this rather directly tells me that I can save my game, when in fact, that option isn't available at all.

## Conclusion

Civ V stacks some straight-up untrue help text onto a weird decision, and it results in a confusing and unpleasant experience for new players. If you know that players of your game will have an expectation to do X, if you aren't allowing it, make sure to let them know.

It's the same argument that happens on the web with hiding vs disabling controls. The best description I've heard of this is on this super long and super great post by Michael Zuschlag called ["Controlling Your Controls"](http://www.zuschlogin.com/?p=40). The gist of it is that you should disable a control when a user might be able to access it. Hide it if it will never be useful for them.

And don't lie to them about it!
