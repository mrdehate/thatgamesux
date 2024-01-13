---
title: "When Asynchronous Multiplayer Makes Sense"
date: "2013-05-08"
categories: 
  - "casual"
  - "mobile"
tags: 
  - "android"
  - "asynchronous-multiplayer"
  - "casual-games"
  - "ios"
  - "ipad"
  - "iphone"
  - "multiplayer"
  - "turn-based"
---

Asynchronous (or online turn-based) multiplayer games let gamers play at their own pace. Maybe the classic example of this is Words With Friends - you play a word, send it to your friend, and wait for their response. These games take advantage of mobile users' ability to play anywhere, for filling in those tiny slices of time that might otherwise be wasted. Not to mention, a group of people can play together despite never being in the same room or even the same time zone.

That said, this isn't a new concept. The [International Correspondence Chess Federation](http://en.wikipedia.org/wiki/International_Correspondence_Chess_Federation) reports that [correspondence chess](http://en.wikipedia.org/wiki/Correspondence_chess) may have been played [way back in the 12th century](http://www.chessinvasion.com/international-correspondence-chess-federation.html). Chess is a perfect example of when asynchronous multiplayer games make sense - in chess, each move is hugely important, and there is a ton of thought that goes into each one. In mobile games though, asynchronous multiplayer doesn't always fit the game.

# When asynchronous multiplayer is a good fit for a mobile game

Here are three rules for determining when it makes sense to support asynchronous multiplayer in a game:

1. When players can easily figure out what the current state of the game is, and they don't need a huge refresher each time they take a turn
2. When both a game and a turn can be completed in a reasonable amount of time
3. Players always have something meaningful to do each turn

This works really well with lots of word games. It's easy to pick up games like [Words with Friends](http://www.wordswithfriends.com/) and [Letterpress](http://www.atebits.com/letterpress/) when it's your turn, and there's always a meaty decision to make. There are no "throwaway" turns when you're trying to get a triple word score!

[![Super Stickman 2 multiplayer modes](images/multiplayer-300x168.jpg)](http://www.thatgamesux.com/wp-content/uploads/2013/05/multiplayer.jpg)Another really good implementation of asynchronous multiplayer is in [Super Stickman Golf 2](http://www.noodlecake.com/ssg2/). The turn-based mode has players competing for the best score in a 9-hole round of mini golf. The best part is it's not one hole at a time, each player completes _two_ holes at a time. While it doesn't sound like a big deal, that makes all the difference in the world when actually playing a game. While one hole could be completed in just one shot, two holes is a much more satisfying chunk of time to spend in the game. And even better, rounds are finished twice as fast.

[![Real Racing 3 Multiplayer](images/rr3_multiplayer-300x168.jpg)](http://www.thatgamesux.com/wp-content/uploads/2013/05/rr3_multiplayer.jpg)Real Racing 3 takes an interesting spin on the topic, with what they are calling "[time-shifted multiplayer](http://www.slashgear.com/real-racing-3-shows-off-time-shifted-multiplayer-03267962/)". The idea being you can race against your friends, except you're actually racing against the AI that's _acting_ like your friends. I haven't gotten the chance to play it myself quite yet, but it sounds like a cool way to introduce a bit of multiplayer in a racing game without all the coordination of getting your friends together.

One last game - [Draw Something](http://omgpop.com/drawsomething) does a great job of keeping players hooked by the way the turns are setup. The game transitions right from "guess what your friend drew" into "what do you want to draw?" Since players don't have the chance to get distracted between those steps, it keeps the chain alive and puts the ball back in the other person's court. Since a game is always mid-turn and not at what feels like a "safe stopping point", it makes it that much harder to stop playing. Classic!

# When asynchronous multiplayer doesn't work quite as well

Certain game types don't lend themselves well to turn-based multiplayer, especially ones that are some kind of reflex or dexterity based. Games like Angry Birds and Jetpack Joyride, it just doesn't make sense in those situations. You could do like the old Pac-Man arcade machine and just compare scores at the end of each round, but I don't think it would be very compelling.

I'm a big fan of board games on mobile devices, but unfortunately some games just need to be played in real-time. [Lost Cities](http://lostcitiesapp.com/) works okay, though in many turns it feels like nothing of interest really happens. [Carcassonne](http://carcassonneapp.com/) is better in that each turn, the player makes a more meaningful decision by placing a tile.

[![Zoomed-in display of Ticket to Ride Pocket](images/ttr_sample-300x200.jpg)](http://www.thatgamesux.com/wp-content/uploads/2013/05/ttr_sample.jpg)Ticket to Ride Pocket (the iPhone version, NOT the iPad version) recently added an asynchronous multiplayer mode in a patch. This might be the most painful experience I've had in a turn-based game, and it breaks all three of the rules listed above. Let's review:

1. Especially on the iPhone version, it's really hard to tell what the state of the board is, and what goals you're trying to achieve. It's just so small, and there's so much packed in, it takes some re-orientation every turn to remember where you need to go, and what your strategy was.
2. A game of Ticket to Ride isn't especially fast in person, so while each turn is short, an entire game could take months to finish.
3. For the majority of turns, players will be just drawing cards from the deck. Not much for a meaningful decision.

For sure, Ticket to Ride Pocket isn't a fun experience when playing a prolonged asynchronous game. Not to say that the game overall isn't fun - it's one of the best board game translations I've seen on iOS. And the asynchronous multiplayer mode does work great if you've got players dedicated to finishing a game in an hour or two. When playing quickly, you can treat the mode basically like an auto-save, which is quite handy.

# Conclusion

Asynchronous multiplayer is a really compelling feature that makes a lot of sense for many mobile games. If I can rock out a turn of some game on my lunch break or waiting in line at the DMV, that's awesome. It doesn't work in all situations, but for many games that are simple enough to be playable on a phone or tablet, it is a welcome addition.

What asynchronous multiplayer games out there did you find particularly compelling? Or any that were especially a bad fit? Let's discuss in the comments!
