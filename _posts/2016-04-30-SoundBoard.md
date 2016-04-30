---
layout: post
title: SoundBoard
date: 2016-04-30 8:15
author: BetaLeaf
comments: true
categories: [Utilities]
tags: [Download]
permalink: /SoundBoard
---

**How to use**  

1. Download and run [SoundBoard](https://github.com/BetaLeaf/SoundBoard/raw/master/SoundBoard.exe).  
2. On first launch, a sample INI will be created in the same folder you saved SoundBoard to.
3. Configure this INI to suite your needs, save it, and restart SoundBoard.  
4. Press the [hotkey](https://www.autoitscript.com/autoit3/docs/functions/Send.htm) and enjoy.  
5. To close SoundBoard, find the icon in the tray and Right Click > Exit  

**Uses**  

  * Use it during your live-stream to hype the crowd. My personal favorite is to play the space jam theme right after winning the game or after a teamfight when you pull off an awesome combo/ultimate ability.  
  * Use it to annoy your enemies by using a Loopback and playing something like the Troll Song, Rick Roll, or John Cena's Theme in multiplayer games.  
  * Use it to play any song you want at the click of a button. Sorta basic yea, but it beats manually going to your music folder and double clicking the song you want to play every 3-5 minutes while you are in a game.  

**Notes**  

  * You can pipe SoundBoard into your mic by creating a Loopback. Use a headphone cable that is male on both ends and plug one end into your mic jack and one into your headphone jack. Then reconfigure the INI to use the headphone jack as the playback device. To get the name of the playback device, open VLC and go to Tools > Preferences > Audio. Set the Output module to WaveOut audio output. Now look at your device list and find your headphone jack. Copy exactly what it says and put it in the INI as the playback device. If you are off by even a single character, it will use the default playback device instead. There is no need to save VLC. Just cancel out of the Preferences by clicking the red X.  
  * You can view the [Source Code](https://github.com/BetaLeaf/SoundBoard/blob/master/SoundBoard.au3) on GitHub.  
  * Admin is required for the hotkeys to function in certain games, like Dota 2.

**Example INI**  

  ```[Sound1]```  
  ```Hotkey="+{numpad9}"```  
  ```File="C:\Users\BetaL\Music\SampleTrack.mp3"```  
  ```StartTime="12"```  
  ```EndTime="34"```  
  ```PlaybackDevice="Microsoft Soundmapper"```  

---

**Like my software? Let others know by commenting. It would be greatly appreciated.**  