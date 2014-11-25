---
layout: post
comments: true
title:  "More on the project"
date:   2014-11-09 23:14:54
categories: FreeWebOS update
---

More one the goals. OpenWebOS has two builds: one is the cross-build for the target platform and the other is the local build that allows people to try WebOS on their desktop. We would start from the latter and try to work our way to something resembling the former.

Here is a plan:
1. Porting all underlying components of the [desktop build][build-desktop] to the Ports Collection. 
2. Implementing a window manager that would allow using WebOS on a desktop
3. Go mobile, make sure it would build and run on a mobile platform

[build-desktop]: https://github.com/freewebos/build-desktop

