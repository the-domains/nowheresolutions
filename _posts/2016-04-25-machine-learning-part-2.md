---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: "Now I'm a pretty big fan of control systems which for some reason hasn't collided with machine learning to be absorbed into a general field of study. Basically, they are nearly the same. Anyway, what control theory teaches us is there's this thing called error, and that's what we learn from. People have all sorts of cute expressions to analogize this to life experience, but the point of the matter is: error is extremely important."
datePublished: '2016-04-25T23:40:18.256Z'
dateModified: '2016-04-25T23:40:06.325Z'
title: ''
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
starred: false
sourcePath: _posts/2016-04-25-machine-learning-part-2.md
published: true
url: machine-learning-part-2/index.html
_type: Article

---
Now I'm a pretty big fan of control systems which for some reason hasn't collided with machine learning to be absorbed into a general field of study. Basically, they are nearly the same. Anyway, what control theory teaches us is there's this thing called error, and that's what we learn from. People have all sorts of cute expressions to analogize this to life experience, but the point of the matter is: error is extremely important.

No error means no learning. Now, there are a bunch of different kinds of error, but a good way to think of it is that error is anything we cannot yet explain. Think of it this way, if we can explain everything there is nothing to learn. Philosophically this is pretty cool, so let's look at something unknowable like dice. Dice are pretty random in a truly random sort of way. Now suppose we had something that would predict which side a die would land on, there's no way we could possibly guess which side right? So assuming a six sided die we could only expect to get this right 1/6th of the time. Wrong, it's only unknowable if that's all the information you have. Imagine we have high-speed cameras all over the inside of a box and we look at the frames milliseconds before the die settles, can it then predict what side a die will land on 1 millisecond before it comes to rest? Of course it can (with perhaps some error)! So while it may be impossible with as vague of a notion as "I'm going to roll a die," that's only because there's not enough data to make a prediction. In this case some error may be irreducible (totally unknowable ever), but given the right information like which side is up 1 millisecond before settling, it's not that hard. So this error is actually a sum of many knowable and unknowable errors. Knowing absolutely nothing about a coin toss, we can predict the outcome only 50% of the time; however, knowing absolutely everything about the coin toss our accuracy can approach infinity.