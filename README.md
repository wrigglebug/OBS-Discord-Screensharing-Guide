# OBS Discord Screensharing Guide
## UPDATED 1/5/2024 (New method using capture device)
## Things you need
- OBS (https://github.com/obs/obs-studio/releases)
- win-capture-audio plugin for OBS (https://github.com/bozbez/win-capture-audio/releases)
- VBCABLE ([VBCABLE_Setup_x64.exe](https://files.catbox.moe/myob9e.7z))

## Initial Setup

Install all the software from the first section and open OBS


## OBS Setup

- Navigate to file>settings>audio
- Set audio monitoring device to CABLE Input (VB-Audio Virtual Cable)

 ![](https://i.imgur.com/s3NqL4k.gif)
 
- Add some sources to a scene, we'll use a basic display capture as an example
- Right click the sources list > Add > Application Audio Capture
- Select the running applications you DON'T want to capture audio from (Discord.exe and obs64.exe)
- Check "Capture all audio sessions except for the selected executables"

 ![](https://i.imgur.com/4cv0gw1.gif)

- Right click the audio mixer > Advanced audio settings
- Next to Application Audio Capture, set monitor to "Monitor and output"

 ![](https://i.imgur.com/wTzlIbs.png)
 
- In OBS, click Start Virtual Camera
- In Discord, start a screenshare
- Select Capture Devices, select OBS Virtual Camera, set audio device to CABLE Output (VB-Audio Virtual Cable)

![](https://i.imgur.com/QMYGNbs.gif)
- You're streaming using OBS in Discord! Wow!
