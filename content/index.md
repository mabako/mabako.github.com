---
title: projects
---

A collection of open source projects I contributed to.

Steam Group Tools
=================
with node.js &ndash; on
[github](https://github.com/mabako/steam-group-wishlist),
[live](http://swl.mabako.net/)

A set of tools to view different statistics associated with Steam groups and
friends list. It contains some minor customization geared towards running it
on OpenShift by RedHat.

Allows you to get the summed up wishlist of everyone with a public profile in
a group or on your friends list.
Alternatively, you may check a group or friends list against a specific Steam
store title.


Git.hub
=======
with c# and RestSharp &ndash; on
[github](https://github.com/mabako/Git.hub)

A tiny wrapper for some functions of the Github API v3, containing exactly
the features needed to integrate as a repository host plugin with
[Git Extensions](https://github.com/spdr870/gitextensions). That is, you can do
the following:

* login
* fork repositories
* search repositories by query string or user
* create, reply and close pull requests

Since the basic set of functions work, further extension is neither planned
nor required for the time being.
If there is a need for anything particular, feel free to drop me a note.

I have created the [Git Extensions](https://github.com/spdr870/gitextensions)
Github module in its current form as well.

zwickau-mensa
=============
with java &ndash; on
[github](https://github.com/mabako/zwickau-mensa),
[google play](https://play.google.com/store/apps/details?id=net.mabako.zwickau.mensa)

Simple Android application that provides me with my [university](http://www.fh-zwickau.de)'s food today,
tomorrow and in two days. The name is a derivate of the location, as it happens
to be [Zwickau](http://g.co/maps/2hzbr).

Menus are different for Android 2.x and Android 3+, the latter uses the
action bar instead of the menu key.

IV: Multiplayer
===============
with C++ &ndash; on
[google code](http://code.google.com/p/ivmultiplayer/),
[iv-multiplayer.com](http://iv-multiplayer.com/)

Open source multiplayer modification for Rockstar North's Grand Theft Auto:
IV, rather simple and unpolished as of now. Was in a different repository
before it became public, hence most of the commit history was lost.

Multi Theft Auto
================
with C++ &ndash; on
[google code](http://code.google.com/p/multitheftauto/),
[multitheftauto.com](http://multitheftauto.com/)

Open source multiplayer modification for Rockstar North's Grand Theft Auto:
San Andreas providing access to plenty and complex functions, a graphical
interface, DirectX-functions, completely scriptable via a [lua](http://www.lua.org/).

gamemodes
---------
with lua &ndash; on
[github](https://github.com/mabako/mta-paradise)

The pretty much only gamemode for Multi Theft Auto I worked on (except for
private ones) is a roleplay gamemode called mta-paradise set in the virtual
town of San Fierro.

server-side modules
-------------------
A bunch of mostly cryptographic modules.

* [base64](https://github.com/mabako/mta-base64): Base64 decoding and encoding as `base64_decode(str)` and `base64_encode1(str)`.
* [sha](https://github.com/mabako/mta-sha): The sha-family, namely `sha1(str)`, `sha224(str)`, `sha256(str)`, `sha384(str)` and `sha512(str)`.
* [whirlpool](https://github.com/mabako/mta-whirlpool): Implementation of the whirlpool hash function, exposed to lua as `whirlpool(str)`.

standalone server browser
-------------------------
with C++, GTK+ &ndash; on
[github](https://github.com/mabako/mta-browser)

Queries the Multi Theft Auto server list and shows all server info the way
it is retrieved. Filters and sorting are supported.

Originally built on Ubuntu Linux, it can be compiled with Dev-C++ on Windows.

sanandreasmap
=============
with ruby on rails &ndash; on
[github](https://github.com/mabako/sanandreasmap)

Visual Map of a collection of points to be represented in a full-screen ***Google Maps***-View,
drawn on a high-quality map of the county of San Andreas in Rockstar North's Grand Theft Auto: San Andreas.
