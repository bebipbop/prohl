Half-Life by default SUCKS for multiplayer in terms of controls. My goal here was to make a config that anyone can use to easily get better controls and better settings.

If you're using my config there are a few very important things to keep in mind. Not reading this file could result in lost binds and overwritten files and I won't take responsibility for that. 


***Important notes:***

- It is VERY important to keep in mind that this config resets ALL binds when executed. You should edit the config to match the binds you want to keep, or delete the "unbindall" and "exec default.cfg" lines, plus the binds you don't want overwritten. If you have a custom autoexec you'll want to avoid overwriting that aswell and instead just add "exec prohl.cfg" to the end of it. Otherwise, just put prohl.cfg inside of your Half-Life folder and then relaunch the game.
- I added a crosshairs sprite that work a lot better than the default ones and also a bunch of models. If you don't wan't these then you can just delete the "valve" folder. Otherwise, just put the valve folder inside of your Half-Life folder and then relaunch the game.


**Less important notes:**

- First, you should probably rebind the weapon keys to your liking. You'll especially need to rebind if you don't have mouse thumb buttons. 
- Second, theres a lot of aliases which make quick motions like the crossbow quick scope easier. You can utilize these, but some are broken and most(like x-bow quick scope) you should probably just learn the motion on your own.


*Special notes:*

- The bind to equip the crossbow and the .357 are special. They will unscope the weapon if the button is pressed again. This is useful because you can press mouse 1, mouse 2 and then the weapon button very quickly to fire a scoped shot and then unscope instead of waiting for the unscope cooldown. 
- The x-bow quick kill bind is broken. It is probably because of the framerate, so to fix it you'll probably have to set a lower fps_max and adjust the waits accordingly. I, however, would rather have a high fps_max for the low input latency :)