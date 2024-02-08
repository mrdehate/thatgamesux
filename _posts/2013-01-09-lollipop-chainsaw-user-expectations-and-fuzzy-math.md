---
title: "Lollipop Chainsaw: User Expectations and Fuzzy Math"
date: "2013-01-09"
categories: 
  - "action"
  - "console"
tags: 
  - "game-experience"
  - "game-usability"
  - "high-score"
  - "leaderboard"
  - "lollipop-chainsaw"
  - "score"
  - "suda51"
  - "usability"
  - "user-experience"
  - "ux"
---

![logo for Lollipop Chainsaw](images/lollipopchainsaw-logo.jpeg)

Lollipop Chainsaw is, undoubtedly, a high-score fest. [Destructoid's review](http://www.destructoid.com/review-lollipop-chainsaw-229321.phtml) compares it to the SEGA classics House of the Dead and Crazy Taxi - odd comparisons for a hack and slash game. But it's true, much like the game of Diablo III has barely started by the time you beat the story once, Lollipop Chainsaw begs to be played again and again so you can rack up a massive score.

Okay, score is important in Lollipop Chainsaw, what's the big deal, and how is this related to usability at all? It's how the score is presented to the player. It looks like the game is producing some seriously fuzzy math, and it's an example of how important it is to mind your users' expectations.

I snapped this screenshot at the end of stage 5. Take a close look at these numbers:

![The end-level score screen in Lollipop Chainsaw](images/130106-1338-37.jpg)

The screenshot claims my score is 384,620. But if you add up the numbers that are above it, those don't total anywhere close to that - it's only 28,720, less than 10% of my total score.

Where on earth is the other 90% of my score coming from? Apparently I did pretty well somewhere, as I got an A+ in total score despite receiving _zero_ A-pluses in the listed scores. Of course, the answer is simple - it comes from killing zombies, among other in-game score bonuses that aren't listed on this screen.

The point is, the way this screen is laid out it looks like those numbers should add up. The user's expectation is that a stack of numbers followed by a large number at the bottom indicates that the big number is a total of what's listed above. When the interface doesn't fit the user's mental baggage, it means they have to stop and think for a second what's going on.

And there's a fair amount of consideration to have on this screen - consider that the letter grade next to my score is an A+, while my overall rank is a C+ (which is an average of all the letter grades on this screen). You can figure it out, but on first glance, one would think those values should be the same. Not to mention my "hunter level" of 18.0, whatever the heck that means. That's three different scores that all seem to represent how well I did in the level, and I don't really know which of them to believe.

## Conclusion

I'm deeming this one "Mark's law of number stacks": **If you're putting a stack of numbers on top of another, larger number, everyone expects that the big number is a total of the smaller numbers.** This is what we've been taught since the first grade - don't mess with it. In this example, if Lollipop Chainsaw pushed that score over to the right side (where the other aggregate figures are), it wouldn't have triggered those same thoughts. So make sure that you're aware of what mental models your users already have before using your interface.

Joel Spolsky's excellent book "_[User Interface Design for Programmers](https://www.amazon.com/dp/1893115941/ref=as_li_ss_til?tag=keepi00-20&camp=0&creative=0&linkCode=as4&creativeASIN=1893115941&adid=1PDCHZC523ZDT2Q3X8PK&)_" has a chapter on user's expectations, and it's actually [available online as a blog post](http://www.joelonsoftware.com/uibook/chapters/fog0000000058.html). The examples are a little dated but the concepts are still highly relevant; I highly recommend it.

Now I'm off to see if I can do something about that C+...
