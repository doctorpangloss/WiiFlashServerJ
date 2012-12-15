WiiFlashServerJ for Mac
=======================

An updated, less-crashy server component to WiiFlash, a library connecting a Wiimote to Flash games.

Read more about WiiFlash at

http://wiiflash.bytearray.org/

Notes
=====

For a working Macintosh binary, visit:

http://goo.gl/hSUg0

Follow Jean-Philippe Côté instructions on his website, which reference this binary:

http://cote.cc/blog/wiiflashserverj-crashing-or-slowing-down-on-mac-os-x

These are the sources to the binary above. The main difference between this version and Adam Ross's original version is a fix to event timer code and some weak referencing issues.

Installation
============

Compiling is easiest with Eclipse. This directory contains project settings, including a build step, that make that process easy. To produce an .app that can be run on Mac... that's more involved, and there are better tutorials elsewhere.

I built the binary by modifying the existing app bundle to use the update JAR containing the classes above.