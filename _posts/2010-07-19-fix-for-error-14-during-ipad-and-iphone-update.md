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

The update of my iPad to version 3.2.1 of iOS failed last night. iTunes reported that an 'Error 14' had occured (Not very helpful) Subsequent attempts at un-docking and re-docking resulted in iTunes trying and failing to restore the device. Here's how I fixed the problem.
  
<!--more-->


  
I eventually took a scroll through the crash dump which iTunes was suggesting I should send to Apple for analysis. It appeared from the logs that the updated OS image was failing a checksum verification i.e. it had been corrupted during the download. A few minutes of searching provided the information needed to fix the problem:

  1. Un-dock and shutdown the iPad (Note: You will not see the 'Red' power down slider in this state)
  2. Shutdown iTunes
  3. Delete the previously downloaded software update file which you will find in these location depending on your system: 
      1. Mac Location: /users/<user name>/Library/iTunes/iPad Software Updates
      2. PC Location (Pre Windows 7): \Documents and Settings\<User>\Application Data\Apple Computer\iTunes\iPad Software Updates
      3. PC Location (Windows 7): \Users\<User>\AppData\Roaming\Apple Computer\iTunes\iPhone Software Updates
  4. 'Empty Trash' to be on the safe side.
  5. Restart iTunes
  6. Dock iPad
  7. Follow the prompts to have iTunes download the OS upgrade again
  8. Once downloaded iTunes should automatically upgrade the iPad with the new OS and bring it out of restore mode.
  9. This will restore the iPad to factory settings
 10. Once the factory restore is complete iTunes will let you further restore the iPad from the most recent backup of the device before it encountered the problems. This should recover your apps, data and user settings.

I believe this fix will also work if you get 'Error 14' during an iPhone update. The download files will be found at the same locations except in the 'iPhone Software Updates' directory.

I hope this helps if you been trying to recover from this very annoying and frustrating problem.