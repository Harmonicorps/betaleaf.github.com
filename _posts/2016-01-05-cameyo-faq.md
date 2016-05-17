---
layout: page
title: Cameyo FAQ
date: 2016-01-05 14:45
author: BetaLeaf
comments: true
categories: [Manuals]
tags: [Manual]
---
**Q. What is Cameyo?**  

**A.** [Cameyo](http://www.cameyo.com/about) is an application used to package apps into a virtual app.  

---
**Q. What is a Virtual App?**  

**A.** A virtual app (or portable app) is a single .EXE file that holds an entire application, including files, DLLs and registry. Virtual apps can be copied & moved around like regular files and launched from anywhere without installation: home, office, Dropbox, USB disk-on-key, laptop, network shares. With Cameyo's app virtualization, you can take your apps and data with you, anywhere.  

---
**Q. Why does the Virtual App require more than twice the amount of space in order to run it?**  

By default, Cameyo will extract the Virtual App to the ```AppName.cameyo.files/PROG``` Folder. This is so the Virtual App loads faster on future runs.  

---
**Q. Are there any Public Virtual Apps available?**  

**A.** Yes, and you can view them at [https://online.cameyo.com/public](https://online.cameyo.com/public)  

If you have the Cameyo App downloaded, run it and select Cameyo Player to access these apps without the need of a web browser.  

---
**Q. Do I have to run the app on my computer?**  

**A.** No. You can save them to your Dropbox or Google Drive accounts and link them to your Cameyo Account. After you have done that, click the "Execute in Browser" button from [https://online.cameyo.com/library.aspx?mode=Private](https://online.cameyo.com/library.aspx?mode=Private)  

This will run the app on Cameyo's Secure Servers. Free accounts are limited to 15 minute sessions. Paid accounts are limited to 90 minute sessions. You can create your own secure server that allows for unlimited session time. You will need to be able to run (or have someone host for you) a Virtual Machine with a minimum of 1 Mb/s Upload Rate and specs to match the app you wish to run. [Read More...](https://online.cameyo.com/playservers/add)  

---
**Q. The Virtual App is unstable when Executed in Browser and often crashes. What can I do to fix this?**  

**A.** Try reducing the quality setting for the game. Alternatively, downloading Cameyo app and selecting Cameyo Player will allow you to run the app without having to download it. It will seamlessly looks like a normal application on your computer's task bar. This counts as running the app on Cameyo's Secure Servers and you will be subjected to their time limit, unless you run your own server.  

---
**Q. Is it safe to save my login info on Cameyo's Secure Server for Virtual Apps?**  

**A.** Yes. Any data stored on their servers are automatically deleted after you have been disconnected for more than 5 minutes. Relaunching the app within these 5 minutes will allow **ONLY YOU** to reuse any data stored on their servers, including your login for the Virtual app if you checked Remember Login/Username/Password and any files the Virtual app has extracted/downloaded.  

---
**Q. Cool. How do I make my own Virtual Apps?**  

**A.** You can [download](http://cameyo.com/download) Cameyo from their [website](http://cameyo.com/) and follow the instructions on the [manual](http://www.cameyo.com/doc/index.html).  

You can also use Cameyo's Secure Servers to package apps. Download the Cameyo app and select Cameyo Player.  

---
**Q. Any Performance Tips?**  

**A.** Copy the Virtual App stored in your Cameyo folder somewhere on the Local Disk and run it from there.  

If ```AppName.cameyo.files``` folder exists in your Cameyo folder, copy that along with the Virtual App to the Local Disk.  

---
**Q. What is the ```AppName.cameyo.files``` folder created when I run the Virtual App?**  

This folder stores any changes to the Virtual App. This includes any added or modified files and registry values. While this folder is not required to run the Virtual App, you may be required to update the Virtual App on launch, which will automatically create this folder.  

The default location for this folder is ```"%appdata%\VOS"```.  

On removal media, the folder will default to the directory where the Virtual App is stored.  

---
**Q. What is in the AppName.cameyo.files folder?**  

**A.** Changes contains any changes to the Virtual App.  

PROG contains the Virtual App. Unless [Ram Mode](http://www.cameyo.com/doc/step_2_editing_a_virtual_packa.htm) is used, this folder will require at least enough free space to extract itself into this folder.  

EngineStamps and the other files in the root of AppName.cameyo.files are required for Cameyo to run the app. Any files missing are recreated on run.  

---
**Q. Any useful command line flags?**  

**A.** Here are a few Frequently Used Flags and you can view the [full list](http://www.cameyo.com/doc/virtual_package_command_lines.htm):  

  ```- Exec```: execute an application from the virtual package context  

Executes a command from the virtual application's package.  

If no full path is provided (i.e. "skype.exe"), the entire virtual package tree will be searched.  

A number such as ```#1``` or ```#2``` etc. can be specified to execute the first or second etc. item from the package's autolaunch menu.  

Examples:  

  - ```AppName.cameyo.exe -exec "%Program Files%\OpenOffice.org 3\program\scalc.exe"```  
  - ```AppName.cameyo.exe -exec scalc.exe Parameter1 Parameter2```  
  - ```AppName.cameyo.exe -exec #1``` (executes the first item from the package's autolaunch menu)  
  - ```AppName.cameyo.exe -exec regedit.exe``` (opens the registry editor in the context of the virtual package)  
  - ```AppName.cameyo.exe -exec cmd.exe``` (opens a command-line box in the context of the virtual package)  

---
```-Repackage```: integrate the application's data storage into the virtual executable package (1.55 and higher)  

Takes all the deployed files and data from the local file system back into the virtual application package.  

This is useful if you want the virtual package to always include the files and data as they are currently on the machine.  

**Note:** If repackaging fails to capture a logged in user, try doing the repackaging while the app is running and after the user has logged in.  

Example:
  - ```AppName.cameyo.exe -Repackage```

---
```-Remove```: stop and remove virtual application  

Stops and removes the virtual application and its local data from the machine.  

Can be used with the ```-Confirm``` modifier, to request user confirmation.  

To remove only the virtual registry, you can specify ```-Remove:Reg```  

Examples:

- ```AppName.cameyo.exe -Remove```  

- ```AppName.cameyo.exe -Confirm -Remove```  