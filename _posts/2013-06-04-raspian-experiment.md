---
layout: post
category : qof
tagline: "slow things come in small packages"
tags : [hack, raspberry-pi]
---
{% include JB/setup %}

###What?

The master branch of QoF builds on a Raspberry Pi. It turns out that the autoconf runes hadn't caught up with the fact that libtrace is no longer optional. There are also indications of a regression from these tests: Linux privdrop doesn't seem to work with libtrace, though this could be a Raspbian-specific thing.

Although it builds, I can't get any traffic past it. Need to see if the built-in Ethernet can actually run promiscuous.

###Er, why?

Mainly because it seems an [mPlane](http://www.ict-mplane.eu)-controlled QoF instance sending congestion and latency data off a wireless network might make a fun conference demo. 

###How fast?

Watch this space.