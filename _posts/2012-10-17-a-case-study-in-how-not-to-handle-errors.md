---
title: "A Case Study in How Not To Handle Errors"
date: "2012-10-17"
categories: 
  - "mobile"
  - "rts"
tags: 
  - "civilization-revolution"
  - "error-message"
  - "failing-silently"
  - "icloud"
  - "ios"
  - "ipad"
  - "iphone"
  - "mobile-gaming"
  - "save-games"
  - "ui"
  - "ux"
---

The other day, I was watching a playoff baseball game, and in an attempt to keep my mind off the baseball game, I decided to fire up [Civilization Revolution](https://itunes.apple.com/us/app/civilization-revolution/id324563544?mt=8) on my iPhone. While it's a definitely cramped on the iPhone, it's still a great game for the mobile setting - easy to pick up for just a couple of minutes (in theory anyway), and balances complex gameplay with simple enough controls to make it a fun and rewarding diversion.

While I spent most of the baseball game conquering the Russians (they were in my way, what could I do?), I didn't get to see my civilization rise to its true glory. Not because the Americans were about to breach my defenses, but instead, the game silently refused to save my game. This is a UX disaster - read on to hear the whole story.

![20121016-210447.jpg](images/20121016-210447.jpg)

I played about 2 hours of Civilization Revolution on my iPhone during this particular session, and I was frequently saving as any good player does. Nothing seemed out of the ordinary while I was in-game; returning to the save or load screens displayed my game save as I would expect. Eventually I exited the game to go back to the main menu. From here, trying to load the game again showed no save ever existed. I built a 1:30 video to demonstrate (the iPad and iPhone versions act exactly the same - I used the iPad version in the video for my ease of creation).

<iframe width="560" height="315" src="https://www.youtube.com/embed/4kATxF9BcuU?si=ZtCSDH0EXkjtYhnS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Civilization Revolution recently issued an upgrade that enabled iCloud saves - this seems like a great idea, as it promises the ability to resume a game started on the iPhone on the iPad. I have a feeling it isn't working quite as intended here. As I said in the video, I don't know if it's a problem with my iCloud account or the Civilization Revolution game. Either way, I have no idea how I would fix it.

But that aside, let's think about the experience here. Possibly the worst experience that a user can have using any interface is losing all of their work, except maybe for a nuclear meltdown. And in my case, I seemed to have taken every necessary precaution - I was saving regularly, every sign pointed to success. At least if the power went out and the user lost two hours worth of work - that is a preventable problem. "Okay, I'll make sure and save more frequently next time", or the use of a recovery feature could help.

In this case, what would have been a better solution? Well, perhaps the obvious answer is to not lose my game. If the iCloud syncing portion doesn't work, then that's fine, just **don't blow away the local copy of my save file**. Equally as good would have been **an error message** saying that iCloud was somehow broken, and try using another save slot because this one doesn't work (in truth, after some combination of turning iCloud document syncing on and off, I did receive a message something like this - but it was the exception for sure).

People make mistakes, that's a part of life. But software shouldn't make mistakes. And software especially shouldn't make mistakes and not tell anybody about it. Especially when those mistakes mean the user's progress is wiped out, because those are the definitely the worst.

Here's the moral of this story: yes, you should always avoid giving your users an error. It's usability 101, right? However, **failing silently is not an improvement.**
