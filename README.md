# HTML5 tower defense game
![Screenshot](screenshots/4.png)

This is a fork of Oldj's [HTML5 Tower Defense](https://github.com/oldj/html5-tower-defense), with the following changes/improvements:

- [x] Hosted on [github.io](https://mipmap.github.io/)
- [x] READMEs translated to English
- [ ] Place buildings over existing ones, automatically sells existing one
- [ ] Code comments translated to English
- [ ] Expand/shrink canvas to fit the available window
- [ ] Option to adjust grid size to fit window before start
- [ ] Place/sell buildings while paused
- [ ] Click & drag (or touch & drag) to place multiple buildings
- [ ] Move tooltip out of playing area to bottom or sidebar
- [ ] Building strength meter and/or color
- [ ] Hotkey ('u') or mode (double click) for upgrading multiple buildings quickly
- [ ] Adjust gameplay for more building time (more money at start) and watching destruction (slow down later levels)
- [ ] Smoke, fire, and scorch marks which fade over time
- [ ] Sound
- [ ] Save/restore
- [ ] High score table
- [ ] Machine learning player/opponent


## Run

Check out the [online demo](http://mipmap.github.io).
Or open `src/td.html` or `build/td.html` with a browser to run the game.


## Description

1. This game is completely implemented using HTML5 / JavaScript / CSS, and does not use Flash, SilverLight or other technologies.
2. This version does not use images, all the items in the game are drawn using HTML5.


## Table of contents

    /build          Compressed, publishable file
    /screenshorts   Screenshots
    /src            Source code
        /css        Style sheet
        /js         JavaScripts source files
    /tools          Gadgets, scripts
    /README.md      This document


## Cheat methods

To facilitate testing, this game has several built-in cheat methods, you can enter the following commands in the browser address bar during the game (if debug is enabled in the source and the browser supports [bookmarklets](https://en.wikipedia.org/wiki/Bookmarklet)):

1. Add 1 million dollars: `javascript:_TD.cheat="money+";`
2. Double the difficulty: `javascript:_TD.cheat="difficulty+";`
3. Halve the difficulty: `javascript:_TD.cheat="difficulty-";`
4. Health recovery: `javascript:_TD.cheat="life+";`
5. Health is reduced to a minimum: `javascript:_TD.cheat="life-";`

Note that the above cheat method is mainly for test design, please use it as appropriate during the normal game, otherwise it may reduce the fun of the game. 


## Update history
 - 2019-05-03 Create fork to run from github.io.
 - 2015-09-06 Support for retina display.
 - 2011-01-01 Adjust the parameters, and according to the netizen's suggestion, add a check when building a new building, and it is forbidden to surround the monster with the building (v0.1.14).
 - 2010-12-29 According to the netizen's suggestion, increase the automatic life recovery function (recover 5 points every 5 waves, and restore 10 points every 10 waves). Adjusting the parameters reduces the range of the laser gun and enhances the power of the heavy machine gun (v0.1.12).
 - 2010-12-18 Added new weapon "laser gun" (v0.1.8.0).
 - 2010-12-12 Suspend the development of the image resource version branch and continue to optimize and develop the circle version (v0.1.7.0).
 - 2010-11-28 The first image resource version (v0.2.1.3267).
 - 2010-11-23 Released the circle version (v0.1.6.2970) .
 - 2010-11-14 The first version was released online.
 - 2010-11-11 Start writing this game. 
