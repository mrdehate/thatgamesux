---
title: "Quento: Shaking My iPhone Makes Me Sad"
date: "2013-02-13"
categories: 
  - "casual"
  - "mobile"
tags: 
  - "casual-games"
  - "game-usability"
  - "gesture"
  - "ios"
  - "mobile-gaming"
  - "usability"
  - "user-experience"
  - "ux"
---

[![Example of iOS' confirm undo screen](images/iOS-Simulator-Screen-shot-Feb-12-2013-8.03.06-PM-200x300.png)](http://www.thatgamesux.com/wp-content/uploads/2013/02/iOS-Simulator-Screen-shot-Feb-12-2013-8.03.06-PM.png)Way back in iOS 3, Apple implemented the "shake to undo" feature. This means if you're typing, say, a text message, and you want to "undo" your text, just shake your iPhone, iPad, or iPod Touch. While it's a cool trick, this isn't the most usable feature that Apple has ever implemented. It's both hidden and unintuitive. And I've definitely triggered it more accidentally than I have on purpose.

Quento ([iTunes link](https://itunes.apple.com/us/app/quento/id583954698?mt=8)) is a stylish puzzler for iOS (and [Android](https://play.google.com/store/apps/details?id=nl.q42.quento), and [Windows 8](http://apps.microsoft.com/windows/app/quento/b68dc7f9-7694-4705-9b3e-ecc2f261893a), and [Chrome](https://chrome.google.com/webstore/detail/quento/nimiaepladfnjnkflgicmageogpmcneg)) that looks a lot like [Letterpress](http://www.thatgamesux.com/letterpress-for-ios-beautifully-simple/ "Letterpress for iOS: Beautifully Simple") except it substitutes simple math problems for word problems. It's a good distraction for your brain, but unfortunately it's also a good example of how not to implement a shake feature in your game. Shaking your phone resets the board, causing you to lose all your progress for that level - without any warning.

\[caption id="attachment\_732" align="alignright" width="169"\][![example screenshot of quento with some progress made](images/IMG_0874-169x300.png)](http://www.thatgamesux.com/wp-content/uploads/2013/02/IMG_0874.png) All that progress is one quick shake away from being gone...\[/caption\]

Here's how Quento works, in a nutshell: you've got to swipe over math problems in order to get the desired result. In the screenshot here, we've got to use two numbers to get to the total of 8. So 5+3=8, easy enough. You get a star for each time you solve a problem with the specified amount of numbers, and after getting all the stars, you move onto the next level.

This screenshot shows me having five of the six stars required to pass to the next level (the free version lets you play the two and three number puzzles; four and five number puzzles are an in-app purchase). Despite the big star indicating I've solved all the three number puzzles, shaking my phone will remove all my progress on this level. The intention is that if you get stuck on a puzzle, you can shake to get a fresh one.

Of importance here - there's not a ton of incentive to pass to the next level. You get a new background color, and a new set of puzzles, but that's about it. Even still, users _hate_ losing data, and getting your progress wiped out feels a lot like that. At best it feels like backtracking, which is also no good.

Of course, it's perfectly valid to make the player some penalty for "giving up" and wanting a new puzzle. Otherwise, a player could just keep re-rolling puzzles until they get one with an obvious answer, and that's just lame. Apple's implementation gives you a confirmation dialog making sure you want to undo your typing, and that would be a welcome addition here.

The thing to keep in mind is this: **if you're doing something destructive with the user's progress (or data), make doubly sure it's intentional.** The problem with the shake gesture is that it's really easy to do on accident. What if you're on the bus and you hit a pothole? Or someone pegs you in the head with a Nerf dart? Or you just get mad and shake your phone because you can't figure out how to add numbers up to 10? All valid reasons to shake. None of them should result in you losing progress.

In Words with Friends, shaking the phone causes the letters in your rack to shuffle. This is a great example of how to interpret a device shake, because it's not a destructive action. I've accidentally hit the pass button more than once trying to tap "shake" instead, so I'm a fan of this one. And like with most gesture-based features, it isn't super discoverable, but that's okay because it's not at all critical.

# Conclusion

The goal behind any interface is to make it match the mental model that your users have of the system. This means that users can intuitively know how to use it based on their past experience. Shaking your phone isn't a real common experience in the real world though, so it's hard to come up with a universal answer to what that action should do. The closest thing is probably the [Etch a Sketch](http://en.wikipedia.org/wiki/Etch_A_Sketch), which is moderately relatable to Apple's "shake to undo" feature.

Quento is a fun diversion to keep your math skills sharp, and the unfortunate implementation of shake to undo doesn't kill the experience by any means. It is a good reminder though that if you're implementing something to do with a shake, make sure it will surprise and delight users, and not resulting in another shake due to anger!

What other games (or apps for that matter) have implemented a shake gesture that you think is particularly noteworthy? Let's discuss in the comments!
