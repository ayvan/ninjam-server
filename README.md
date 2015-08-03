# ninjam-server

[![Build Status](https://travis-ci.org/Ayvan/ninjam-server.svg?branch=master)](https://travis-ci.org/Ayvan/ninjam-server)

Ninjam Server 0.06 by Cockos Incorporated

http://www.cockos.com/ninjam/


# New feature

Added support for charset conversion between Mac OS X client and server to support WINDOWS-1251 (russian language) chat.

To use chat in Mac OS X client  just add "_utf8" to your username when login to turn on UTF-8 conversion. You username in chat will be without "_utf8" and you don't need register new user in config, postfix will be cut after login.

# Changes

* WDL library updated
* fixed all compile warnings