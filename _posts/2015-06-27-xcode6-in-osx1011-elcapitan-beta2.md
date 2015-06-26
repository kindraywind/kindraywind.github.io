---
layout: post
title: launch Xcode6.x in El capitan beta2
---
![xcode6elcapitan](/img/xcode6elcapitan.png)
Your Xcode 6.x can't be launched after installing the El Capitan beta2, but you're not ready to risk yourself by using Xcode7 beta.

Here is a solution.

```
vi /.bash_profile

alias xcode6='/Applications/Xcode.app/Contents/MacOS/Xcode'
```
Then, you just enter `xcode6` in your Terminal.


Happy coding. :]
