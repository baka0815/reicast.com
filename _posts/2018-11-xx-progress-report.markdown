---
layout: post
title:  "Progress report November"
date:   2018-11-xx 00:00:00 +0100
categories: news
---

November again was a month full of fantastic changes.
We unfortunatly missed our goal to release 18.11 in November (again) so we now try to get 18.12 out, so stay tuned for the next feature report.

Documentation [#1453](https://github.com/reicast/reicast-emulator/pull/1453)
---
Thanks to [@luserx0](https://github.com/luserx0) we now have an extensive list of documentation inside the project. That doesn't mean it's the end, but more of a start.

Snap packages [#1452](https://github.com/reicast/reicast-emulator/pull/1452)
---
[@luserx0](https://github.com/luserx0) also played around with our snap packages support so we now have the snap status on our main github page as well as a comprehensive readme for the snap package itself.

Emulation
---
[@flyinghead](https://github.com/flyinghead) did it again and fixed some emulation related bugs.

- Thanks to his work on enabling log2 depth at runtime when supported (GL, GLES 3) Whacky races is now playable. This fixes the gamedb issue [#83](https://github.com/reicast/gamedb/issues/83) from 2016! [#1448](https://github.com/reicast/reicast-emulator/pull/1448)
- Texture-based fog table fixed the long standing issue [#549](https://github.com/reicast/reicast-emulator/issues/549) from 2014! Now Ecco can swim freely through the ocean and not through some ugly somewhere. [#1449](https://github.com/reicast/reicast-emulator/pull/1449)

![Ecco before](/assets/img/2018-11-1449-before.jpg "Ecco before")
![Ecco after](/assets/img/2018-11-1449-after.jpg "Ecco after")


Miscellaneous
---
- [@baka0815](https://github.com/baka0815)s work on evdev unfortunatly broke SDL input support because there was no longer any controller created. This is now fixed. [#1458](https://github.com/reicast/reicast-emulator/pull/1458)
- [@baka0815](https://github.com/baka0815) and [@flyinghead](https://github.com/flyinghead) finally added support for CHDv5. Now all your up-to-date MAME roms should finally be playable. [#1400](https://github.com/reicast/reicast-emulator/pull/1400)
- Our new contributor [@ccawley2011](https://github.com/ccawley2011) slightly optimized our Linux makefile. [#1442](https://github.com/reicast/reicast-emulator/pull/1442)
- And finally (thanks to [@dmiller423](https://github.com/dmiller423)) we fixed the upload to the build server for Android! [Update Android *SdkVersion to 26](https://github.com/reicast/reicast-emulator/commit/3ab2eefb501f3f495b86407c59524f536aeb6a5f)

That's it for November,

team reicast
