---
layout: post
title: Another small Release?
subtitle: Added one more to the Pile
tags: [projects, general,update]
---

Another update so fast? It's only been like what, 3 days? This is definitely a new record but a pace like this is probably something I can't sustain. Today I bring you another small program I just put the finishing touches on (good enough for release, I hope). If you haven't noticed by now, usually with most of my projects (the non gaming ones) I'm usually trying to solve a niche problem I've run into but they're specific use cases most the time. In the case of this small tool it was to add a virtual MUTE button to the Blue Yeti Snowball mic, since it doesn't have a physical one. This works with any Microphone since it's based on whatever default Input device Windows has set.

Once you run the program, you can minimize it and it'll sit in your task bar. From there you can use global keybinds which you can set yourself but by default are (these work even without the program being in focus):

- Ctrl+M = Mute/Unmute
- Ctrl+Q = Quit the program 
- You can also click the APP itself (it's essentially a giant button)

[*SnowMute*](https://github.com/Hoodstrats/SnowMute) |
[PatchNotes](https://hoodstrats.github.io/SnowMuteReleases)

***These can be changed under File>Settings, but the program does require a restart after applying changes.
This is due to the way in which the Key binds are set. They are registered in Windows so that they're able to 
work while APP isn't in focus.***

Whether you want to mute yourself for stream or just want a quick keybind you can press instead of a physical button somewhere, you might find this program useful. The code is open source ofcouse with [MIT](https://mit-license.org/). I plan on using some of this code for my personal Twitch bot which would essentially let chatters redeem channel points to mute me for 'x' amount of time. If you ever need a refresher on how to use the program, you can open the about me/help.