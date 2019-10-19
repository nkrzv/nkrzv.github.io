---
layout: post
title: "Did Anybody Use Your Computer?"
categories: [Open Source Software]
date: 2019-10-19
---

Don’t know if this is possible on Windows or iOS but on Linux you can see if someone used your computer without your knowledge.

`last` [command](https://www.howtoforge.com/linux-last-command/) will show successful logins to your system.

`journalctl --list-boots` [shows](https://www.loggly.com/ultimate-guide/using-journalctl/) the boots your system went through.

`lastb` [lists](https://www.guyrutenberg.com/2014/09/26/view-failed-login-attempts-lastb/) failed attempts to your system.

`aureport` is a [tool](https://linux.die.net/man/8/aureport) to audit your logs in `/var/log/` .