# DS4Win-Val-Project
This is a small project I've been working on for the past.. 2ish years? It started out because I didn't want to buy ReWASD, and use DS4 Windows instead to play valorant with my controller. After testing, and perfecting my profiles I figured out how to essentially match my controller and mouse gameplay. 

IMPORTANT! - If your mouse ISN'T WORKING while playing with a controller its because of Memory Integrity being DISABLED! You MUST ENABLE IT in your bios: https://support.riotgames.com/en-us/riot/support-tools/enabling-memory-integrity
Doing this stops Valorant from causing these specific issues while playing with a controller: Crashing or Freezing upon opening the game, input buffering mid game, crashing while alt tabbed. 

Project Ended?
Got bored and fooled around w some numbers, little better than original Z, and have a 2nd version coming if it works out. Goal is to smooth out the rough movements and simplify the config to basically be 1 on 1 with a mouse while being able to be easily understood how to configure as if it was on console. No Delays or Off Sets

VL4 - .359. .954 .858

VZ4 - .36 .95 .858

Valo Prec Z1 - 
.36
.98.
,858

Valo Phantom Z Profile -
This Profile is made for ZERO Deadzone Controllers with Hall Effect or TMR. Means you can put the deadzone all the way to 0 without drift. This has an adjusted DISABLED Gyro that works with the settings I made for it. It could be fine tuned more but haven't found anything better than these exact settings in the profile. It plays similar to Medium - Low cod controller settings, (7 horizontal, 5 vertical), 
.36
.956
.858

Current Profile - Prec X7 or X7G (G for Gyro) and Prec 7 Alt
.365 - .366
.968
.858

Changes - Slight Curve Adjustment allows a lower deadzone to have similar but more accurate movements without Input Fuzz. Input Fuzz issue was pixel skipping causing aiming to over or under shoot in certain distances. 
Added Gyro Settings from @IDKWhatApexIs (Valo Gyro Server), mixes pretty well with X7 actually, not perfect mix but good enough for tests. 
Deadzone lowered from .05 to .02, if drift is too much of an issue I reccomend .03-.04 deadzone, with either increrasing or decreasing anti deadzone accordingly. May need to adjust last curve value to .89 or .9 instead of .88. 


Valorant with a mouse of 800 DPI roughly I had the settings of
.36
.875
.85

I managed to figure out how to get my controller sensivity to feel consistent like playing with a mouse of 800 DPI, slowly adding acceleration thats manageable to emulate the full arm movement into a single joystick.
Controller Settings ranged from
Precision X6
.366
.96
.85.8

Phantom and Up
.361 - .36
.875, .88-.89, .9 - .95
.873

Beta 3
.363
.875
.85

I left the values loose here, ADS required a lot of change due to me straying away from Mouse Mimicry to turning the Profile back into ones more suited for actual controller playstyles. 

All Profiles are just drag and drop, ready to use to test out. I'll leave the profiles in TWO Folders, Featured and General. Featured are the profiles I kept going back to, either ones I kept accidentally remaking when changing the values or because of the headshot accuracy. Beta 3 was the one I had the most headshots on, but the slowest. After that point I was trying to speed up the mouse sensitvity of the controller while still being in control, where it took a long while of tests. I eventually started having a smoother setting starting at Valo Phantom 5 where I got it fast and accurate. The problem now was to slow it down, to make it more Precise but still fast to turn around, where Valo Phantom 9B to X came and I was able to essentially make different profiles with different smoothing, acceleration, and precision that will hit headshots and play like Call of Duty without Aim Assist. They're not perfect but I'm onto what feels like the final stages with the Precision Series of profiles. The current itteration feels the most stable, but it can definitely use more polish which is what I'm gonna figure out.


How did I figure out the sensitvity? I used math, I genuinely looked at my Fortnite and Apex Settings, and found a mediuum and tested what felt more accurate with the raw settings. Then I learned the advance settings of DS4 Windows and tried to figure out what matched to what in those games. They're not 100% but Delta Acceleration is similar to the Tuning Acceleration in Fortnite with the ramp delays. The Output curve was an exact copy of my Apex Curve then adjusted to be more precise as I played Valorant. Fuzz and Anti Deadzone controls what I call Dragging and Skipping. They work either alone or together to smooth the precision of your aim. Dragging is when you aim but always miss just short of the head, while skipping is the opposite landing near the head but never on it. Adjusting these values up and down by 1 can cause either issue in an inconsistent manner. It also slightly lifts the aiming making you aim more above the head if done incorrectly. 

Each profile is designed to travel to the center as perfectly as i could make it, but the problem with dragging and skipping is similar to how we view frames in animations. Rather than it being a smooth animation, the mouse travels across the pixels in different frames of FPS. Dependent of the value configuration, the mouse can skip where your cursor or crosshair is trying to land on the head of a player, Causing you to miss shots entiely. Fuzz can skip it in what feels like half frames, and anti deadzone can skip it in what feels like whole or quarter frames entirely. Its a really odd thing to imagine and visualise. What fixes this kinda is Anti Snap back, it smoothens out the frames sorta like "AI Generation" but its not perfect in that regard and I haven't figured it out entirely. 

Profiles Before Precision Warning and Issues: They utilize the drags and skips to hit more headshots, but sacrifice micro movements to aim. Each turn to aim is basically a big leap to hit the head but turning around or aiming at an angle isn't smooth. The Precision profile series aim to allow micro movemments to aim, but be able to turn fast and still be consistent. 
