# BetterTouchTool-SLite-Preset
**Introduction**

SLite is a preset of BetterTouchTool inspired by GoldenChaos and many other presets.

It is designed to be "light" and neat while doing everything I need it to do.

Although I like GoldenChaos, it is too messy and over-complex for me. Presets like GoldenChaos and AquaTouch take a long time to load. It is especially annoying when you find your MacBook Pro wake up from sleep and the touch bar loads for a long time. I disabled a lot of GC's functionality when I used it. For example, I believe that it should not be touch bars' job to deal with notifications and playback. The overwhelming amount of scripts it constantly runs to get notifications is unnecessarily using resources.

The same is more true for AquaTouch.

So, a few days back and I suddenly thought to myself: "why don't you just make a preset yourself?"

I built the preset based on GoldenChaos and it works the same, except that it takes only 1 second to load up.

Some features I added myself may be interesting to you, such as the always showing function keys.


**Showcase and Usage**

The main interface of SLite is used as a dock, plus calendar preview, reminder, emoji, clipboard, language, time, battery, and a button to toggle the BTT custom touch bar off.
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128682830-409325ec-37fc-4206-8ed0-0c0ac21efc47.png">

The emoji group, clipboard, language, and battery is from GoldenChaos. They did a great job on that.
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128683189-ce3f5699-e09f-44d2-8522-3c6d615e7bba.png">

I made some tweaks about the way to exit the groups, and added "history" button in the clipboard group (from GoldenRabit, I think). I also removed the keyboard shortcuts they sent (I don't know why they were added in the GoldenChaos preset).
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128683344-471fbdda-4098-483b-a5ce-4d372a1cd3bb.png">

The right most icon from AquaTouch is used to toggle the BTT custom touch bar off. (Ironically, this is the only part where I used their design).


Gestures:
I only use two-finger scrolling to modify sound, screen brightness, and eyboard illustration level. It modifies sound when holding no key, screen brightness when holding "command" key, and keyboard illumination level when holding "option" key. I found it annoying to use three or four fingers to do these things.


If you hold the **command** key, it shows this:
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128683818-11e4dc96-e698-45f8-88e0-302d8aae1c83.png">

From the left to the right, these buttons are:
1. Funtion keys group. They remain open after you open them whatever you do. This is my way of solving the problem "MacBook Pro doesn't have a way to let F1 to F12 show all the time with a key toggle". This group is closed by pressing the "X" button
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128685127-eabb5f3c-268b-4de3-baea-430fafeb3076.png">

2. Show menubar here. Shows the menubar where your pointer is.
<img width="1253" alt="image" src="https://user-images.githubusercontent.com/84777573/128685455-4b9b4ce1-e54e-4398-acad-fcac9617df74.png">

3. App expose. Show all the windows of the curren app, visible or hiden.

4. Save pointer position.

5. Restore pointer position.

6. Big cursor. Press again to make the cursor normal.

7. Hide cursor. Press again to show cursor.

8. Start mouse drag. Make the system think your pointer is draging constantly.

9. Stop mouse drag.

10. Reload BetterTouchTool. Press this when things are not working.

11. BetterTouchTool UI. Press this to change BetterTouchTool settings.


If you hold the **option** key, it shows window snapping options:
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128686257-cb777289-dd50-4519-a5d3-bd3f7a6ab708.png">

These are just straight from GoldenChaos with size changes. Try them yourself and you know what they do.


If you hold the **control** key, it shows this:
<img width="1004" alt="image" src="https://user-images.githubusercontent.com/84777573/128686582-b618a321-d744-4ae7-89d8-441b12d4c0f9.png">

From the left to the right, they are:
1. Lookup word under cursor. Same as "Look up & data detectors" in your Trackpad preferences.

2. Launchpad. From GoldenChaos.

3. Show desktop. From GoldenChaos.

4. Mission control. From GoldenChaos.

5. Move left a space. Switch to the "Desktop" to the left of the current shown one.

6. Move right a space. Switch to the "Desktop" to the right of the current shown one.

7. Mute speaker. From GoldenChaos.

8. Close window below cursor.

9. Empty trash.

10. Quit app below cursor.


**Installation**

This part focuses on how to install SLite.

Download .bttpreset file from Release.

Open BetterTouchTool UI. Press the "Preset" on the top-right corner.
<img width="1252" alt="image" src="https://user-images.githubusercontent.com/84777573/128681351-7f45f19d-3a43-474e-b40a-812df22c3c2a.png">

Click "Import".
<img width="546" alt="image" src="https://user-images.githubusercontent.com/84777573/128681506-4b07339f-bf14-4d8c-821d-6e00a574ba6d.png">

Choose the .bttpreset file you downloaded.

It will give you a warning because it could be dangerous if you import some virus, but in this case you can trust me 😉.  Check the two checkboxes and click "Start Preset Import".
<img width="627" alt="image" src="https://user-images.githubusercontent.com/84777573/128681920-1c03bb97-e8ac-4864-bb6c-529f703e803f.png">

And after 2 seconds it should say:
<img width="260" alt="image" src="https://user-images.githubusercontent.com/84777573/128682099-58d702ce-d337-4004-9faf-5011c5fff5fb.png">

And the installation is done!

One last thing to check: go to "Touch Bar Settings" (Command + ,) and make sure "Show BetterTouchTool icon in Control Strip" is ticked.
<img width="994" alt="image" src="https://user-images.githubusercontent.com/84777573/128682348-8030107d-919d-4ab3-bd82-47b28ff69920.png">

This way you can easily toggle the custom touch bar on after you toggle it off.


**Performance**

It takes roughly 1% of CPU and 56MB of memory on my 2019 MacBook Pro with intel i5 core. And it loads up in 1 second after the computer waking up from sleep.


**Compatibility**

You can add whatever other preset along with SLite as you like. Specifically presets for specific apps would override SLite.


**Contact Author**

My email: ramonamurphynsy25@gmail.com
Feedbacks and suggestions are appreciated.


**Thank you for trying this out!**
