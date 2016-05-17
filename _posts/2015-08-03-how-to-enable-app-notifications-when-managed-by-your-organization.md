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
1. Download and Open the Registry Key to Import. [Click Here to Download](../assets/dl/appnotification.reg)
2. Click Yes. (See Images)
3. Shutdown and reboot your computer.

**Images:**  
2. ![Screenshot](../I/42wx5JC.png)

<strong>Keys to Import:</strong>  
```[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\PushNotifications]```  
```"NoToastApplicationNotification"=dword:00000000```