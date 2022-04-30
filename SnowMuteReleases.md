---
layout: page
title: SnowMute Releases
tags: [project,programming,tool]
---
`RELEASE`
[V1.0.0](https://github.com/Hoodstrats/SnowMute)

4-30-22
###### Added
- new public method in options script to allow public access to apply settings 
###### Changed
- FirstRun variable in settings is now IsFirstRun for clarity 
- CanRun variable in first run dialogue changed to match FirstRun var in Settings
###### Fixed
- FirstRunDialogue now only triggers upon first run and not when About is pressed 

4-21-22
###### Added
- a small timer of 5 seconds to the OK button when the program is first run (enforce some reading)

1-12-22
###### Added
- Save system implemented 
	- Can now change Muting and Quitting keybind combinations after pressing apply on new options window 
	- settings will load on startup

12-28-21
###### Fixed
- Using async operation for synth PROMPTS doesn't allow for completion checks so removed for program exiting 

12-27-21
###### Added
- Right click menu for tray icon 
	- Mute, Unmute and Exit
- The mute button itself (the whole program is a mute button) actually works now

###### Change
- Tray icon now needs to be double clicked in order to restore program
- Exiting the program normally still triggers exit message/delay
- Refactored all mute toggling functionality
- Synth speak now run async for better performance/less delay

12-26-21
###### Added
- different tray icons for Muted and Unmuted

###### Fixed
- Toggling MUTE now uses built in Audio device mute to avoid volume issues
- Stopped getting and setting volume programmatically

###### Changed
- TTS program greeting
- When pressing CTRL+Q to quit the program TTS says something before exiting 