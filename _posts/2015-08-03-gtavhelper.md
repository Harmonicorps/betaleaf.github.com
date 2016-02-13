---
layout: post
title: GTAVHelper
date: 2015-08-03 08:15
author: BetaLeaf
comments: true
categories: [Game Tools]
tags: [GTA 5,Download]
---
[**Download** GTAVHelper](http://dl.dropboxusercontent.com/u/350004313/CDN/dl/GTAVHelper.exe)  
[**Download** Source](http://dl.dropboxusercontent.com/u/350004313/CDN/dl/GTAVHelper.zip)  

GTAVHelper is an AutoIt Script that gives you access to various pre-existing functions at the press of a hotkey.  

**Hotkey Features:**  

  - Quickly Deposit all into bank.  
  - Quickly Call contacts like the mechanic, Mor's Insurance, Pegasus and more.  
  - Quickly Accept the Most Recent Job.  
  - Find another Session, or Join a friend or crew session.  
  - GTAV Online only.  

**Automatic Features:**  

  - Faster Respawn when you die.  
  - AutoUpdating.  
  - AutoStart and Stops when you start and stop GTAV (Needs Helper App to function)  

**How to Use:**  
Extract into a separate folder and run the exe. The first run will install the necessary files in the current directory. Set the INI file, save, and then relaunch the exe. If you prefer to have GTAVHelper AutoLoad whenever you start GTAVHelper, launch LaunchWatcher.exe. To reinstall, simply delete the INI and relaunch GTAHelper.exe and it will re-extract everything.  

**How to Set the INI File:**  

[keys]  
PassiveMode=^+&#123;space&#125;  
CancelAction=^+&#123;esc&#125;  

In this Example, we can see that CancelAction is set to Control+Shift+Escape. When you press this key, GTAVHelper will stop any actively running command and idle until you press another hotkey.  

A Format Chart is below for your convenience.  
<table border="1">
<tbody>
<tr>
<th><strong>
<a href="https://www.autoitscript.com/autoit3/docs/functions/Send.htm">What to put in the INI File</a>
</strong></th>
<th><strong>and the resulting keypress</strong></th>
</tr>
<tr>
<td>a</td>
<td>a</td>
</tr>
<tr>
<td>b</td>
<td>b</td>
</tr>
<tr>
<td>+c</td>
<td>Shift+c</td>
</tr>
<tr>
<td>!d</td>
<td>Alt+d</td>
</tr>
<tr>
<td>^e</td>
<td>Ctrl+e</td>
</tr>
<tr>
<td>#f</td>
<td>Windows+f</td>
</tr>
<tr>
<td>^!+#g</td>
<td>Ctrl+Alt+Shift+Windows+g</td>
</tr>
<tr>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>&#123;!&#125;</td>
<td>!</td>
</tr>
<tr>
<td>&#123;#&#125;</td>
<td>#</td>
</tr>
<tr>
<td>&#123;+&#125;</td>
<td>+</td>
</tr>
<tr>
<td>&#123;^&#125;</td>
<td>^</td>
</tr>
<tr>
<td>&#123;&#123;&#125;</td>
<td>&#123;</td>
</tr>
<tr>
<td>&#123;&#125;&#125;</td>
<td>&#125;</td>
</tr>
<tr>
<td>&#123;SPACE&#125;</td>
<td>SPACE</td>
</tr>
<tr>
<td>&#123;ENTER&#125;</td>
<td>ENTER key (not the numpad enter)</td>
</tr>
<tr>
<td>&#123;ALT&#125;</td>
<td>ALT</td>
</tr>
<tr>
<td>&#123;BACKSPACE&#125; or &#123;BS&#125;</td>
<td>BACKSPACE</td>
</tr>
<tr>
<td>&#123;DELETE&#125; or &#123;DEL&#125;</td>
<td>DELETE</td>
</tr>
<tr>
<td>&#123;UP&#125;</td>
<td>Up arrow</td>
</tr>
<tr>
<td>&#123;DOWN&#125;</td>
<td>Down arrow</td>
</tr>
<tr>
<td>&#123;LEFT&#125;</td>
<td>Left arrow</td>
</tr>
<tr>
<td>&#123;RIGHT&#125;</td>
<td>Right arrow</td>
</tr>
<tr>
<td>&#123;HOME&#125;</td>
<td>HOME</td>
</tr>
<tr>
<td>&#123;END&#125;</td>
<td>END</td>
</tr>
<tr>
<td>&#123;ESCAPE&#125; or &#123;ESC&#125;</td>
<td>ESCAPE</td>
</tr>
<tr>
<td>&#123;INSERT&#125; or &#123;INS&#125;</td>
<td>INS</td>
</tr>
<tr>
<td>&#123;PGUP&#125;</td>
<td>PageUp</td>
</tr>
<tr>
<td>&#123;PGDN&#125;</td>
<td>PageDown</td>
</tr>
<tr>
<td>&#123;F1&#125; - &#123;F12&#125;</td>
<td>Function keys</td>
</tr>
<tr>
<td>&#123;TAB&#125;</td>
<td>TAB</td>
</tr>
<tr>
<td>&#123;PRINTSCREEN&#125;</td>
<td>Print Screen key</td>
</tr>
<tr>
<td>&#123;LWIN&#125;</td>
<td>Left Windows key</td>
</tr>
<tr>
<td>&#123;RWIN&#125;</td>
<td>Right Windows key</td>
</tr>
<tr>
<td>&#123;NUMLOCK on&#125;</td>
<td>NUMLOCK (on/off/toggle)</td>
</tr>
<tr>
<td>&#123;CAPSLOCK off&#125;</td>
<td>CAPSLOCK (on/off/toggle)</td>
</tr>
<tr>
<td>&#123;SCROLLLOCK toggle&#125;</td>
<td>SCROLLLOCK (on/off/toggle)</td>
</tr>
<tr>
<td>&#123;BREAK&#125;</td>
<td>for Ctrl+Break processing</td>
</tr>
<tr>
<td>&#123;PAUSE&#125;</td>
<td>PAUSE</td>
</tr>
<tr>
<td>&#123;NUMPAD0&#125; - &#123;NUMPAD9&#125;</td>
<td>Numpad digits</td>
</tr>
<tr>
<td>&#123;NUMPADMULT&#125;</td>
<td>Numpad Multiply</td>
</tr>
<tr>
<td>&#123;NUMPADADD&#125;</td>
<td>Numpad Add</td>
</tr>
<tr>
<td>&#123;NUMPADSUB&#125;</td>
<td>Numpad Subtract</td>
</tr>
<tr>
<td>&#123;NUMPADDIV&#125;</td>
<td>Numpad Divide</td>
</tr>
<tr>
<td>&#123;NUMPADDOT&#125;</td>
<td>Numpad period</td>
</tr>
<tr>
<td>&#123;NUMPADENTER&#125;</td>
<td>Enter key on the numpad</td>
</tr>
<tr>
<td>&#123;APPSKEY&#125;</td>
<td>Windows App key</td>
</tr>
<tr>
<td>&#123;LALT&#125;</td>
<td>Left ALT key</td>
</tr>
<tr>
<td>&#123;RALT&#125;</td>
<td>Right ALT key</td>
</tr>
<tr>
<td>&#123;LCTRL&#125;</td>
<td>Left CTRL key</td>
</tr>
<tr>
<td>&#123;RCTRL&#125;</td>
<td>Right CTRL key</td>
</tr>
<tr>
<td>&#123;LSHIFT&#125;</td>
<td>Left Shift key</td>
</tr>
<tr>
<td>&#123;RSHIFT&#125;</td>
<td>Right Shift key</td>
</tr>
<tr>
<td>&#123;SLEEP&#125;</td>
<td>Computer SLEEP key</td>
</tr>
<tr>
<td>&#123;ALTDOWN&#125;</td>
<td>Holds the ALT key down until &#123;ALTUP&#125; is sent</td>
</tr>
<tr>
<td>&#123;SHIFTDOWN&#125;</td>
<td>Holds the SHIFT key down until &#123;SHIFTUP&#125; is sent</td>
</tr>
<tr>
<td>&#123;CTRLDOWN&#125;</td>
<td>Holds the CTRL key down until &#123;CTRLUP&#125; is sent</td>
</tr>
<tr>
<td>&#123;LWINDOWN&#125;</td>
<td>Holds the left Windows key down until &#123;LWINUP&#125; is sent</td>
</tr>
<tr>
<td>&#123;RWINDOWN&#125;</td>
<td>Holds the right Windows key down until &#123;RWINUP&#125; is sent</td>
</tr>
<tr>
<td>&#123;ASC nnnn&#125;</td>
<td>Send the ALT+nnnn key combination</td>
</tr>
<tr>
<td>&#123;BROWSER_BACK&#125;</td>
<td>Select the browser "back" button</td>
</tr>
<tr>
<td>&#123;BROWSER_FORWARD&#125;</td>
<td>Select the browser "forward" button</td>
</tr>
<tr>
<td>&#123;BROWSER_REFRESH&#125;</td>
<td>Select the browser "refresh" button</td>
</tr>
<tr>
<td>&#123;BROWSER_STOP&#125;</td>
<td>Select the browser "stop" button</td>
</tr>
<tr>
<td>&#123;BROWSER_SEARCH&#125;</td>
<td>Select the browser "search" button</td>
</tr>
<tr>
<td>&#123;BROWSER_FAVORITES&#125;</td>
<td>Select the browser "favorites" button</td>
</tr>
<tr>
<td>&#123;BROWSER_HOME&#125;</td>
<td>Launch the browser and go to the home page</td>
</tr>
<tr>
<td>&#123;VOLUME_MUTE&#125;</td>
<td>Mute the volume</td>
</tr>
<tr>
<td>&#123;VOLUME_DOWN&#125;</td>
<td>Reduce the volume</td>
</tr>
<tr>
<td>&#123;VOLUME_UP&#125;</td>
<td>Increase the volume</td>
</tr>
<tr>
<td>&#123;MEDIA_NEXT&#125;</td>
<td>Select next track in media player</td>
</tr>
<tr>
<td>&#123;MEDIA_PREV&#125;</td>
<td>Select previous track in media player</td>
</tr>
<tr>
<td>&#123;MEDIA_STOP&#125;</td>
<td>Stop media player</td>
</tr>
<tr>
<td>&#123;MEDIA_PLAY_PAUSE&#125;</td>
<td>Play/pause media player</td>
</tr>
<tr>
<td>&#123;LAUNCH_MAIL&#125;</td>
<td>Launch the email application</td>
</tr>
<tr>
<td>&#123;LAUNCH_MEDIA&#125;</td>
<td>Launch media player</td>
</tr>
<tr>
<td>&#123;LAUNCH_APP1&#125;</td>
<td>Launch user app1</td>
</tr>
<tr>
<td>&#123;LAUNCH_APP2&#125;</td>
<td>Launch user app2</td>
</tr>
</tbody>
</table>
