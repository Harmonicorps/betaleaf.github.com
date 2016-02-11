---
layout: page
title: Cameyo FAQ
date: 2016-01-05 14:45
author: BetaLeaf
comments: true
categories: [Manuals]
tags: [Manual]
---
<strong>Q. What is Cameyo?</strong>

A. <a href="http://www.cameyo.com/" target="_blank">Cameyo</a>&nbsp;is an application used to package apps into a virtual app.

<strong>Q. What is a Virtual App?</strong>

A. A virtual app (or portable app) is a single .EXE file that holds an entire application, including files, DLLs and registry. <span class="text_exposed_show">Virtual apps can be copied &amp; moved around like regular files and launched from anywhere without installation: home, office, Dropbox, USB disk-on-key, laptop, network shares. With Cameyo's app virtualization, you can take your apps and data with you, anywhere.&nbsp;</span>

<strong>Q. Why does the Virtual App require more than twice the amount of space in order to run it?</strong>

By default, Cameyo will extract&nbsp;the Virtual App to the AppName.cameyo.files/PROG Folder. This is so the Virtual App loads faster on future runs.

<strong>Q. Are there any Public&nbsp;Virtual Apps available?</strong>

A. Yes, and you can view them at&nbsp;<a href="https://online.cameyo.com/public" target="_blank">https://online.cameyo.com/public</a>

If you have the Cameyo App downloaded, run it and select Cameyo Player to access these apps without the need of a web browser.

<strong>Q.&nbsp;Are there any Private Virtual Apps available?</strong>

You can view my private collection of Virtual Apps at&nbsp;<a href="https://betaleaf.net/category/cameyo/" target="_blank">https://betaleaf.net/category/cameyo/</a>

<strong>Q.&nbsp;Do I have to run the app on my&nbsp;computer?</strong>

A. No. You can save them to your Dropbox or Google Drive accounts and link them to your Cameyo Account. After you have done that, click the "Execute in Browser"&nbsp;button from&nbsp;<a href="https://online.cameyo.com/library.aspx?mode=Private" target="_blank">https://online.cameyo.com/library.aspx?mode=Private</a>

This will run the app on Cameyo's Secure Servers. Free accounts are limited to 15 minute sessions. Paid accounts are limited to 90 minute sessions. You can create your own secure server that allows for unlimited session time. You will need to be able to run (or have someone host for you) a Virtual Machine with a minimum of 1 Mb/s Upload Rate and specs to match the app you wish to run.&nbsp;<a href="https://online.cameyo.com/playservers/add" target="_blank">Read More...</a>

<div id="UnstableHTML5"><strong>Q. The Virtual App is unstable when Executed in Browser and often crashes. What can I do to fix this?</strong>

A. Try reducing the quality setting for the game. Alternatively, downloading Cameyo app and selecting Cameyo Player will allow you to run the app without having to download it. It will seamlessly looks like a normal application on your computer's task bar. This counts as running the app on Cameyo's Secure Servers and you will be subjected to their time limit, unless you run your own server.
</div>
<strong>Q. Is it safe to save my login info on Cameyo's Secure Server for Virtual Apps?</strong>

A. Yes. Any data stored on their servers are automatically deleted after you have been disconnected for more than 5 minutes. Relaunching the app within these 5 minutes will&nbsp;allow <span style="text-decoration: underline;"><strong>ONLY YOU</strong></span>&nbsp;to reuse any data stored on their servers, including your login for the Virtual app if you checked Remember Login/Username/Password and any files the Virtual app has extracted/downloaded.

<strong>Q. Cool. How do I make my own Virtual Apps?</strong>

A. You can download <a href="http://www.cameyo.com/" target="_blank">Cameyo</a>&nbsp;from their website at <a href="http://www.cameyo.com/download" target="_blank">http://cameyo.com/download</a>&nbsp;and follow the instructions on the manual found at&nbsp;<a href="http://www.cameyo.com/doc/index.html" target="_blank">http://www.cameyo.com/doc/index.html</a>

You can also use Cameyo's Secure Servers to package apps. Download the Cameyo app and select Cameyo&nbsp;Player.

<strong>Q. Any Performance Tips?</strong>

A. Copy the Virtual App stored in your Cameyo folder somewhere on the Local Disk and run it from there.

If AppName.cameyo.files folder exists in your Cameyo folder, copy that along with the Virtual App to the Local Disk.

<strong>Q. What is the AppName.cameyo.files folder created when I run the Virtual App?</strong>

This folder stores any changes to the Virtual App. This includes any added or modified files and registry values. While this folder is not required to run the Virtual App, you may be required to update the Virtual App on launch, which will automatically create this folder.

The default location for this folder is "%appdata%\VOS".

On removal media, the folder will default to the directory where the Virtual App is stored.

<strong>Q. What is in the AppName.cameyo.files folder?</strong>

A. Changes contains&nbsp;any changes to the Virtual App.

PROG contains the Virtual App. Unless <a href="http://www.cameyo.com/doc/step_2_editing_a_virtual_packa.htm" target="_blank">RAM Mode</a> is used, this folder will require at least&nbsp;enough free space to extract&nbsp;itself into this folder.

EngineStamps and the other files in the root of AppName.cameyo.files are required for Cameyo to run the app. Any files missing are recreated on run.

<strong>Q. Any useful command line flags?</strong>

A. Here are a few Frequently Used Flags and you can view the full list at <a href="http://www.cameyo.com/doc/virtual_package_command_lines.htm" target="_blank">http://www.cameyo.com/doc/virtual_package_command_lines.htm</a>:
<div style="text-align: left; text-indent: 0px; padding: 0px 0px 0px 0px; margin: 2px 0px 2px 0px;">
<table style="line-height: normal;" border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr style="vertical-align: baseline;" valign="baseline">
<td width="13"><span style="font-size: 10pt; font-family: 'Arial Unicode MS', 'Lucida Sans Unicode', 'Arial'; color: #000000;">•</span></td>
<td><span style="font-weight: bold;">-Exec: execute an application from the virtual package context</span></td>
</tr>
</tbody>
</table>
</div>
Executes a command from the virtual application's package.

If no full path is provided (i.e. "skype.exe"), the entire virtual package tree will be searched.

A number such as "#1", "#2" can be specified to execute the first, second etc. item from the package's autolaunch menu.

<span style="text-decoration: underline;">Examples</span>:

- AppName.cameyo.exe -exec "%Program Files%\OpenOffice.org 3\program\scalc.exe"

- AppName.cameyo.exe -exec scalc.exe Parameter1 Parameter2

- AppName.cameyo.exe -exec #1 (executes the first item from the package's autolaunch menu)

- AppName.cameyo.exe -exec regedit.exe (opens the registry editor in the context of the virtual package)

- AppName.cameyo.exe -exec cmd.exe (opens a command-line box in the context of the virtual package)

&nbsp;
<div style="text-align: left; text-indent: 0px; padding: 0px 0px 0px 0px; margin: 2px 0px 2px 0px;">
<table style="line-height: normal;" border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr style="vertical-align: baseline;" valign="baseline">
<td width="13"><span style="font-size: 10pt; font-family: 'Arial Unicode MS', 'Lucida Sans Unicode', 'Arial'; color: #000000;">•</span></td>
<td><span style="font-weight: bold;">-Repackage: integrate the application's data storage into the virtual executable package (1.55 and higher)</span></td>
</tr>
</tbody>
</table>
</div>
Takes all the deployed files and data from the local file system back into the virtual application package.

This is useful if you want the virtual package to always include the files and data as they are currently on the machine.
Note: If repackaging fails to capture a logged in user, try doing the repackaging while the app is running and after the user has logged in.

&nbsp;
<div style="text-align: left; text-indent: 0px; padding: 0px 0px 0px 0px; margin: 2px 0px 2px 0px;">
<table style="line-height: normal;" border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr style="vertical-align: baseline;" valign="baseline">
<td width="13"><span style="font-size: 10pt; font-family: 'Arial Unicode MS', 'Lucida Sans Unicode', 'Arial'; color: #000000;">•</span></td>
<td><span style="font-weight: bold;">-Remove: stop and remove virtual application</span></td>
</tr>
</tbody>
</table>
</div>
Stops and removes the virtual application and its local data from the machine.

Can be used with the "-Confirm" modifier, to request user confirmation.

To remove only the virtual registry, you can specify -Remove:Reg

<span style="text-decoration: underline;">Examples</span>:

- AppName.cameyo.exe -Remove

- AppName.cameyo.exe -Confirm -Remove

&nbsp;
