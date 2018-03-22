# NightClock
Simple HTML NightClock (BIG text) for browsers.

See it in action: http://dev.open-meta.org/NightClock.html

I wear glasses. But not in bed. When I'm travelling, I like to have the laptop or Chromebook that's always with me show me what time it is in letters big enough for me to read from across the room. ALARMd (https://www.zachleat.com/alarmd/) worked for me on the laptop, but the Chromebook doesn't like that it requires external CSS and JavaScript files.

This project's html file has everything it needs embedded within it. It doesn't even require internet access once you've downloaded it.

The hamburger icon at the upper left toggles between full-screen and display of the browser controls. The app has no other options. However, you can edit the CSS yourself if you like.

If you actually use this on a Pixelbook, you will find it helpful to know that the Pixelbook option to "Keep display on" is under Settings/Device/Power/When idle. The sixth and seventh keys control screen brightness. For nightime use, I turn the screen all the way down until it's off, then brighten it just one notch. Also, in some cases you may need to change the Pixelbook's time zone by hand; if so, that's in Settings/Advanced/Date and time.

With other systems you probably want to find these options before travelling. Sleep well.

----------------
Acknowledgements:

JavaScript date-time syntax with help from Tushar Gupta's answer to a Stackoverflow question (https://stackoverflow.com/questions/18229022/how-to-show-current-time-in-javascript-in-the-format-hhmmss).

Hamburger icon as background gradient by enfatotuts+ (https://webdesign.tutsplus.com/tutorials/7-non-raster-approaches-for-making-the-hamburger-menu-icon--cms-21686).

How to hide the browser controls with JavaScript: https://developers.google.com/web/fundamentals/native-hardware/fullscreen/, which recommended screenfull.js (https://github.com/sindresorhus/screenfull.js).

