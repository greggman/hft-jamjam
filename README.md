JamJam
=================

This is a sample game for the [HappyFunTimes party games system](http://greggman.github.io/HappyFunTimes).

<img src="screenshot.png" />

A collective drum sequencer. Each player has one drum they can set the sequence for.
All the machines are synced using a `SyncedClock`. Each player must turn on the volume
on their phone so everyone can hear their drum.

FYI: This is still a work in progress. Timing seems to be synced on iOS devices but
not Android.

Cloning
-------

Prerequisites

*   node.js http://nodejs.org
*   bower http://bower.io
*   happyFunTimes http://superhappyfuntimes.net/install
*   hft-cli http://github.com/greggman/hft-cli

If you clone this you'll need follow the following steps

1.  install happyFunTimes http://superhappyfuntimes.net/install
2.  install node.js http://nodejs.org/download/
3.  install hft-cli by typing `sudo npm install -g hft-cli`
4.  install bower by typing `sudo npm install -g bower`
5.  clone this repo
6.  After cloning cd to the folder you just cloned into and type `bower install`
7.  edit `package.json` and change the `gameId` to some other id.
8.  type `hft add` which will add this to happyFunTimes.

Attribution
-----------

Sounds

From Chromium Repo

Link: http://chromium.googlecode.com/svn/trunk/samples/audio/sounds/drum-samples/

Part of the [Web Audio Drum Machine](http://chromium.googlecode.com/svn/trunk/samples/audio/shiny-drum-machine.html)


