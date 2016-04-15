---
id: 186
title: "Fix for iPad 'Error 14'"
date: 2010-07-19T01:53:09+00:00
author: JM
layout: post
guid: http://www.adamalthus.com/?p=186
permalink: /blog/2010/07/19/fix-for-error-14-during-ipad-and-iphone-update/
aktt_notify_twitter:
  - no
image:
  - 
quote-author:
  - Unknown
quote-url:
  - http://
quote-copy:
  - Unknown
audio:
  - http://
link-url:
  - http://
categories:
  - Apple
  - Gadgets
tags:
  - Apple
  - error 14
  - iOS
  - iPad
  - iPhone
---
[Updated with Windows 7 File location]

The update of&nbsp;my&nbsp;iPad to&nbsp;version 3.2.1 of&nbsp;iOS failed last night. iTunes reported that an 'Error 14' had occured (Not very helpful) Subsequent attempts at&nbsp;un-docking and re-docking resulted in&nbsp;iTunes trying and failing to&nbsp;restore the device. Here&rsquo;s how I&nbsp;fixed the problem.
  
<!--more-->


  
I&nbsp;eventually took a&nbsp;scroll through the crash dump which iTunes was suggesting I&nbsp;should send to&nbsp;Apple for analysis. It&nbsp;appeared from the logs that the updated&nbsp;OS image was failing a&nbsp;checksum verification i.e. it&nbsp;had been corrupted during the download. A&nbsp;few minutes of&nbsp;searching provided the information needed to&nbsp;fix the problem:

  1. Un-dock and shutdown the iPad (Note: You will not see the 'Red' power down slider in&nbsp;this state)
  2. Shutdown iTunes
  3. Delete the previously downloaded software update file which you will find in&nbsp;these location depending on&nbsp;your system: 
      1. Mac Location: /users/<user name>/Library/iTunes/iPad Software Updates
      2. PC&nbsp;Location (Pre Windows 7): \Documents and Settings\<User>\Application Data\Apple Computer\iTunes\iPad Software Updates
      3. PC&nbsp;Location (Windows 7): \Users\<User>\AppData\Roaming\Apple Computer\iTunes\iPhone Software Updates
  4. 'Empty Trash' to&nbsp;be&nbsp;on the safe side.
  5. Restart iTunes
  6. Dock iPad
  7. Follow the prompts to&nbsp;have iTunes download the&nbsp;OS upgrade again
  8. Once downloaded iTunes should automatically upgrade the iPad with the new&nbsp;OS and bring it&nbsp;out of&nbsp;restore mode.
  9. This will restore the iPad to&nbsp;factory settings
 10. Once the factory restore is&nbsp;complete iTunes will let you further restore the iPad from the most recent backup of&nbsp;the device before it&nbsp;encountered the problems. This should recover your apps, data and user settings.

I&nbsp;believe this fix will also work if&nbsp;you get 'Error 14' during an&nbsp;iPhone update. The download files will be&nbsp;found at&nbsp;the same locations except in&nbsp;the 'iPhone Software Updates' directory.

I&nbsp;hope this helps if&nbsp;you been trying to&nbsp;recover from this very annoying and frustrating problem.