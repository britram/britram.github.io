---
layout: page
title: britram at github
tagline: network measurement geek
---
{% include JB/setup %}

### Greetings

I'm Brian Trammell, network measurement geek.

### Contents

Here you'll find three independent implementations of the [IPFIX flow export protocol][ipfix-protocol]: 

- [ripfix][ripfix] which bridges IPFIX Data Records to Ruby hashes, and is intended for rapid prototyping of new IPFIX applications. It's dreadfully slow.
- [python-ipfix][python-ipfix] which provides essentially the same interface as ripfix for python, but is (1) under heavy construction (i.e., it doesn't really work yet) and (2) designed such that it could be used for real analysis applications at some point in the future. The intention is to submit this to PyPI when it's ready.
- [libfc][libfc] which provides a template-transcoding interface between IPFIX Data Records and C data structures in C++ (i.e., like [libfixbuf][libfixbuf]); there's also a placement-based interface (written by @sten69). The focus here is on performance. Don't ask me where the name came from.

All three of these are essentially the first real project I did in each respective language, which may explain why they don't read especially idiomatically.

You'll also find the [QoF][qof] flow meter, a fork of [YAF][yaf]. This is where I'm doing my current research on large-scale TCP performance measurement.

[ipfix-protocol]: http://tools.ietf.org/html/draft-ietf-ipfix-protocol-rfc5101bis
[ripfix]: https://github.com/britram/ripfix
[python-ipfix]: https://github.com/britram/python-ipfix
[libfc]:  https://github.com/britram/libfc
[qof]:  https://github.com/britram/qof

[yaf]:  http://tools.netsa.cert.org/yaf
[libfixbuf]:  http://tools.netsa.cert.org/fixbuf


