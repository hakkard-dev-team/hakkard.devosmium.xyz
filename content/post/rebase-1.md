---
title: "Rebase"
date: 2018-10-05T14:14:58-04:00
draft: false
categories: []
---

## What happened?
Some of you may have noticed that the site looks a little different. This is because we have moved from [Evennia](https://evennia.org) to [Ranvier](http://www.ranviermud.com/). This allows us to stop focusing so much on core game mechanics and use the inbuilt mechanics present in Ranvier. Evennia has been a wonderful learning experience for Python, but for production we felt that we needed a system that allowed us to better manage rooms and mechanics without worrying about whether or not our code would compile. The old website was built into Evennia, and thus had to be discarded. The new templating engine, Jekyll, allows us to more easily add new content to better serve you.

## Is my data still here?
No. Since Ranvier  uses JSON and YAML files instead of a database to store game data, there is no possibility of migration for data. You will need to start from scratch and regain your character. If you have any questions about this, please send us an email.

## Final thoughts
It's my opinion that this allows us to focus more on delivering a great game and less on things that, while important, shouldn't need to be worried about.