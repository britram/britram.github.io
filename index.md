---
layout: page
title: britram at github
tagline: network measurement geek
---
{% include JB/setup %}

### Greetings

I'm Brian Trammell, network measurement geek.

### Contents

Here you'll find the [QoF][qof] flow meter, a fork of [YAF][yaf]. QoF is focused on passive TCP performance measurement; you can read the manpage for the 0.9.0 release [here][qofpdf], or download the release [here][qofrelease-0.9.0].

You'll also three independent implementations of the [IPFIX flow export protocol][ipfix-protocol]: 

- [python-ipfix][python-ipfix] which bridges IPFIX Data Records to Python dicts and tuples, and is intended for rapid prototyping of new IPFIX applications.
- [ripfix][ripfix] which provides a similar interface for Ruby, and is dreadfully slow.
- [libfc][libfc] which provides a template-transcoding interface between IPFIX Data Records and C data structures in C++ (i.e., like [libfixbuf][libfixbuf]); there's also a placement-based interface (written by @sten69). The focus here is on performance. Don't ask me where the name came from.

All three of these are essentially the first real project I did in each respective language, which may explain why they don't read especially idiomatically.

[qofpdf]: /qof.pdf
[qofrelease]: http://www.trammell.ch/downloads/qof-0.9.0.tar.gz
[ipfix-protocol]: http://tools.ietf.org/html/draft-ietf-ipfix-protocol-rfc5101bis
[ripfix]: https://github.com/britram/ripfix
[python-ipfix]: https://github.com/britram/python-ipfix
[libfc]:  https://github.com/britram/libfc
[qof]:  https://github.com/britram/qof
[yaf]:  http://tools.netsa.cert.org/yaf
[libfixbuf]:  http://tools.netsa.cert.org/fixbuf


