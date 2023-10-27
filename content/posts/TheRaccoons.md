---
title: "The Raccons"
date: 2023-10-24T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["Hackathon", "Typescript", "React"]
author: "Jake"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "My experience in the Racoons hackathon and what we built over the 48 hours"
disableHLJS: true # to disable highlightjs
disableShare: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
  image: "https://static.wixstatic.com/media/53ba9f_dfbc6cd19f2e459ba0409345c505c447~mv2.gif" # image path/url
  alt: "Cover for the light and dark theme post" # alt text
  caption: "Cover for the light and dark theme post" # display caption under cover
  relative: false # when using page bundles set this to true
  hidden: false # only hide on current single page
---

# My experience in The Racoons hackathon 2023

To start off, this was a hackathon hosted by the Latvia University Computer Faculty student council with the support of 
sponsors and partners. While it was meant for high school and university students, there were others "of age" there 
that participated.

## The experience in the event outside of hacking

The food at the venue was plenty but the location could have been better as the nearest large store was quite a bit 
away, that staff were amazing to us (the participants) and the judges and mentors were very friendly. Sadly (or luckily)
my group didn't have much use for the mentors but when they came up to ask how our project was coming along they were 
very friendly and saw that we weren't running in to much trouble. The other participants seemed friendly enough, except 
for one man (seemingly in his 30s or 40s) who kept bothering my teammates to come smoke with him and seemed drunk after 
the first night.

## The project

Now to the juicy part. Me and my team initially were aiming for the Sustainability and Data challenge, but since we were 
running in to a wall with how boring all of our idea were, we switched to game dev and started making "Mental Chess", as 
the challenge specified of focusing on mental health awareness.

### The proposal

I proposed this idea "Since we all play chess to some level and enjoy the game, lets create a superset of chess rules 
that give the game a bit of new charm and raise awareness about the impacts of mental illness", and after some talk about 
the proposed rules we got to work, one of my teammates got to work creating the basic website in react and a small 
backend to handle the websocket connection between players, the other (Gustavs) got to work making the pixel art for the 
chess pieces, and i worked on the new rule set and design ideas.

### What problems did we run in to in the process

- The pawn movement we problematic as not only is its movement odd (it can only move forward one spece unless it is its 
first move in which case it can move two spaces) but ther is also "En pessant" where if an enemy pawn moves two spaces 
and lands next to your pawn you can take it as if it had only moved one space
- There were some minor networking issues, where initially we trusted the client to have accurate time on their browser 
to an accuracy of about 2 seconds, but that was a very bad assumptuin as one player turned out to have a clock 2 min in 
the future
- We sadly ran out of time to test everything properly, and because of the mental illnesses being implemented later 
then the base game, that including the check mate, in some cases you could take the enemy king and the game would continue

### The pitch and results of the project

In the end the pitch got recieved well and our Mental Chess took first place in the GameDev challenge, which won use
500 EUR to share and each a free spot as an intern in their game studio, but since i dont plan on entering the game dev 
field ill sadly not be taking them up on it, even tho it sounds like a wonderful oppertunity.

You can watch me pitching the game [here](https://youtu.be/-RU_4tzY0Bw?t=5282) and the results announcment [here](https://youtu.be/-RU_4tzY0Bw?t=16797).

The project can be viewed [here](http://nav.lv:5173/) as well, and the devpost submition can also be viewed [here](https://devpost.com/software/mental-chess).
