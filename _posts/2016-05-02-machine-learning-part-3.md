---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: "This came up so many times it made me sick, but overfitting is a huge challenge in machine learning. There's a pretty good reason, if you look back I talked about error. Well if you imagine any observation is made up of something we wanted to observe, and elements we did not want to observe, yet observed by mistake (error). Now it may not be known what we wanted to observe or how it relates to what we actually did observe, but that's okay. One mistake we can make, however, is to assume that our observation is entirely useful. When we do that, we have observed noise and interpreted it as signal. I said elements we observed by mistake because sometimes noise can actually be useful information, just not by our current observation. For example, if I wanted to determine the speed of a motor powering a saw in a saw mill and I decided I would use rough calculations based on computer vision from a feed of logs approaching the saw. Well I might find that it's sometimes hard to see the logs through the camera because too much sawdust is in the way, and I might consider that noise. However, if I was clever I might use the amount of the field of view obstructed by sawdust as my signal, and then it isn't noise at all. Just like quantum mechanics, it's all a matter of perspective. "
datePublished: '2016-05-02T04:35:19.038Z'
dateModified: '2016-05-02T04:32:43.674Z'
title: ''
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
starred: false
sourcePath: _posts/2016-05-02-machine-learning-part-3.md
published: true
url: machine-learning-part-3/index.html
_type: Article

---
This came up so many times it made me sick, but overfitting is a huge challenge in machine learning. There's a pretty good reason, if you look back I talked about error. Well if you imagine any observation is made up of something we wanted to observe, and elements we did not want to observe, yet observed by mistake (error). Now it may not be known what we wanted to observe or how it relates to what we actually did observe, but that's okay. One mistake we can make, however, is to assume that our observation is entirely useful. When we do that, we have observed noise and interpreted it as signal. I said elements we observed by mistake because sometimes noise can actually be useful information, just not by our current observation. For example, if I wanted to determine the speed of a motor powering a saw in a saw mill and I decided I would use rough calculations based on computer vision from a feed of logs approaching the saw. Well I might find that it's sometimes hard to see the logs through the camera because too much sawdust is in the way, and I might consider that noise. However, if I was clever I might use the amount of the field of view obstructed by sawdust as my signal, and then it isn't noise at all. Just like quantum mechanics, it's all a matter of perspective. 

So anyway, overfitting is just assuming that all of our information is signal; by dint, listening to the noise. It's not good. However, overfitting is not a necessary byproduct of complex models - a perfect model may just be complex. Essentially, we can assume that 100% of our information is not strictly useful and that some portion of it probably is (unless we completely do not understand the topic). It seems really strange to me that overfitting is pushed over and over again without really explaining the weakness of complexity. Every component has a nonzero chance of failure and stacking up components eventually leads to a near certainty of failure in the system as a whole. The machine learning model works the same way, except each component in this case is a piece of the data and some tool, and there's probably a diminishing significance in the data.