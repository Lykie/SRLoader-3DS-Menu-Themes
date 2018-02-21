# What is this?
These are just some themes that I cropped and/or scaled to fit onto the 3DS Menu Theme for SRLoader

# "Installation"
Download the source of [SRLoader](https://github.com/Robz8/SRLoader)

Copy the folders from the theme, and paste them into "romsel_dsimenutheme" and build SRLoader.

# Notes
If you want to "port" your own themes for use, then you'll need to be able to scale/crop them and also limit the image to 16 colors (only required for bottom screen).

You'll also need a music editor such as [Audacity](https://www.audacityteam.org) to add music to the menu.

I recommend using [XNViewMP](https://www.xnview.com/en/xnviewmp/).

If your image is synced between the top and bottom screens on 3DS, then you should scale the bottom screen image, and crop the top screen canvas while having it align to the bottom.

# How to Limit to 16 Colors
Open the Image in XNViewMP

Click the Image tab

Click "Change Color Depth"

Click the bubble next to the word "Colors"

Click the dropdown menu and click "16"

(Optional) Click "Dithering" and set it to "None"

# Audacity Tutorial (inefficient)
Open the music file in Audacity

You'll need to modify the music file to get the time down to 50 seconds (this is the limit to how long SRLoader plays a theme without modifying the source)

Once that's done, click "Tracks" at the top of the screen, and click "Stereo Track to Mono" (this reduces the file size)

Next, click the dropdown menu displayed on the left side of the of the audio track

Hover over "Format" and click "16-bit PCM"

The final step is to click the dropdown menu where it says "Project Rate (Hz)"

This should be changed to "16000" to cut down on file size

Once modification is complete, click File -> Export Audio and change the dropdown menu to "WAV (Microsoft) signed 16-bit PCM"

Name it "menu.wav" and save it, now you can place the resulting file at "romsel_dsimenutheme/music" and compile SRLoader to see the fruits of your efforts
