---
layout: post
title: How to Enable App Notifications when managed by your organization
date: 2015-08-03 13:40
author: BetaLeaf
comments: true
categories: [Tutorials]
tags: [Fix, Windows 10]
---
<div class="body">
<div>1. Download and Open the Registry Key to Import. <a href="http://betaleaf.net/wp-content/uploads/2015/08/appnotification.reg?dl=1">Click Here to Download.</a>
2. Click Yes. (See Images)
3. Shutdown and reboot your computer.<strong>Images:</strong>
2. <img src="http://i.imgur.com/42wx5JC.png" alt="" />&nbsp;

<strong>Keys to Import:</strong>
[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\PushNotifications]
"NoToastApplicationNotification"=dword:00000000

</div>
</div>
