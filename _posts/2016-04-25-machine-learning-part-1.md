---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: 'So it seems like at first what we learn from machine learning is: things are correlated. Crazytown I know, but yes there are things we want to know and those things are, in fact, often related to things we already know or can know. '
datePublished: '2016-04-25T23:29:20.114Z'
dateModified: '2016-04-25T23:28:14.091Z'
title: ''
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
starred: false
sourcePath: _posts/2016-04-25-machine-learning-part-1.md
published: true
url: machine-learning-part-1/index.html
_type: Article

---
So it seems like at first what we learn from machine learning is: things are correlated. Crazytown I know, but yes there are things we want to know and those things are, in fact, often related to things we already know or can know. 

First things first, "Can we learn?" This deep epistemological question doesn't actually seem to really have an answer. We can fool ourselves into believing we have learned and we can create useful models, but there isn't anyway to know for sure that we have actually learned. A lot of people never really internalize this but it's pretty important. However, in order for this entire field, and most of humanity, to make sense we really need this assumption to hold - so let's assume it does. How do we know we've learned? Well basically - we see if we we get better at things based on past performance. It's really that easy. 

So after assuming it is possible to improve by looking at the past, we have to assume something else. We can correctly classify something as true, so that we can distinguish whether or not our "machine" has classified something as true. They use the Titanic data as a good introductory project, we have a lot of information about the passengers including whether or not they lived or died, and we have to train the machine to predict survival based on information similar to the data we have. So we may, at first, take a stab in the dark and guess gender plays a role (hint: it does). The Titanic seemed to spare women so just evaluating whether the person was female seems to do a decent job at predicting whether or not they lived, but it's not perfect. Next we may try age (and test the whole "women and children" thing), and again it does a pretty good job, young people do a better job at surviving a sinking ship than the elderly. And now, we learn what must be the most important thing I've ever learned: Superposition!!! Basically superposition says, that if gender is a good predictor of survival and age is a good predictor of survival, then a function of gender and age must be a better predictor of survival. Now there's some formal reasoning that I just glazed over there, but basically superposition says that there are linear elements to a solution that add up to more than the some of their parts so with enough linear elements added together, we will solve any problem. So there is some combination of all the elements we have together that will yield a pretty good model.