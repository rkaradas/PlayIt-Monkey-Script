# PlayIt-Monkey-Script

Here is another aproach of a simple, yet useful client for the [PlayIt Service](http://forum.kodi.tv/showthread.php?tid=118251) for Kodi.

This time I implemented a Greasemonkey/Tampermonkey script, that adds a play & settings button on the left side of all websites, so you are able to access the functionality from everywhere.


## Installation
Of course you need Grease- or Tampermonkey to get this script to work. So lets start with the installation of the extension.
I tested it with Tampermonkey on Chrome and Firefox and also with Greasemonkey on Firefox, so I can't guarantee, that it will work with other extensions, that support User Scripts.

1. Choose your favorite extension and install it. For Firefox [Tampermonkey](https://addons.mozilla.org/de/firefox/addon/tampermonkey) or [Greasemonkey](https://addons.mozilla.org/de/firefox/addon/greasemonkey/) and for Chrome [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. You may need to restart your Browser
3. Follow the [link](https://github.com/rkaradas/PlayIt-Monkey-Script/raw/master/playit.user.js) to download my script.
4. Confirm the following messages to finish the installation.

## Overview
Now you should see two icons on the left side of all pages (see picture below, marked with a red border). A play button to send the current url to the PlayIt Service and a settings button, to configure the kodi connection information (at least the ip-address).
You can add as many entries as you want, update and delete them.  
 ![Main icons](/screenshots/play_settings_fixed.png?raw=true "Main icons")

 ![Settings overlay](/screenshots/settings_overlay.png?raw=true "Settings overlay")

## Known problems
It is possible that you won't see the icons on some websites, because other elements are laying over the icons. Let me know, if you find a page where this happens.
So that was it...  My night project, so there might be some bugs. You can keep them or share them with me :smiley:

Thanks and have fun :wink:
