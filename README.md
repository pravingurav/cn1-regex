# Codename One Regex Library

This is a port of the [regexp-me project](https://code.google.com/p/regexp-me/) with minor changes to improve performance on Codename One, and wrapped as a cn1lib library.

## Motivation

Currently (as of August 26, 2013), the Codename One String class doesn't include regex support.  This provides cross-platform, lightweight regular expression support.

## Current Status

I whipped this up pretty quickly.  So far I have only tested it in the simulator and on the iPhone (using a build server debug build).  I don't see any reason why it shouldn't work on all platforms, though.  If you have problems on any platform just let me know.

## Installation

1. Download [CodenameOneRegexLib.cn1lib](https://github.com/shannah/cn1-regex/raw/master/dist/CodenameOneRegexLib.cn1lib) and copy it into your application's Netbeans project's lib directory.
2. In the "Projects" explorer in Netbeans, right click on your project, and select "Refresh Libs"

## Usage

For full usage examples see the [regexp-me project page](https://code.google.com/p/regexp-me/) and [javadocs](http://regexp-me.googlecode.com/svn/trunk/regexp-me/doc/index.html).

## Contact

[shannah78](https://twitter.com/shannah78)