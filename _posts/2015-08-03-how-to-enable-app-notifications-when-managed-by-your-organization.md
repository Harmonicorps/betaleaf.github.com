---
layout: post
title: How to Enable App Notifications when managed by your organization
date: 2015-08-03 13:40
author: BetaLeaf
comments: true
categories: [Tutorials]
tags: [Fix, Windows 10]
permalink: how-to-enable-app-notifications-when-managed-by-your-organization
---
1. [<i class="fa fa-download"></i> Download](/static/dl/appnotification.reg) and open the registry key to import.  
2. Click Yes. (See image below)
3. Reboot your computer.

![Screenshot](/static/img/42wx5JC.png)

<strong>Keys to Import:</strong>  
```[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\PushNotifications]```  
```"NoToastApplicationNotification"=dword:00000000```