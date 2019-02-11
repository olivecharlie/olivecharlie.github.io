---
layout: post
title:  "Raspberry Pi Setup"
date:   2019-02-11 00:00:00 +0000
categories: pi mouse issue
---

Upon setting up Raspberry Pi , the wireless mouse was very slow. Updating the config as follows solve the issue.

	1.	Open commandLine.txt in nano and edit to include usbhid.mousepoll=0 at the end of the line.
	2.	Save and reboot.

