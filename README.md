[![Appveyor Status][]][Appveyor] [![Travis Status][]][Travis]

A C library for portable packet creation and injection
======================================================

Libnet is an API to help with the construction and handling of network
packets.  It provides a portable framework for low-level network packet
writing and handling (use libnet in conjunction with libpcap and you can
write some really cool stuff).  Libnet includes packet creation at the
IP layer and at the link layer as well as a host of supplementary and
complementary functionality.  Libnet is very handy with which to write
network tools and network test code.  See the manpage and sample test
code for more detailed information.

> **NOTE:** Legacy code written for *libnet-1.0.x* WILL NOT WORK with
> *libnet-1.1.x*.  Read *doc/MIGRATION* for porting legacy code.

**LIBNET 1.1 (c) 1998 - 2004 Mike D. Schiffman <mike@infonexus.com>**
http://www.packetfactory.net/libnet

**LIBNET 1.1.3 and later (c) 2009 - 2013 Sam Roberts <vieuxtech@gmail.com>**
http://github.com/sam-github/libnet


Origin & References
-------------------

Libnet is widely used, but had become unmaintained at packetfactory.net,
and its author is unreachable.  This version was forked from the 1.1.3
release candidate from packetfactory.net, then bug fixed, actively
maintained, and rereleased.

Use GitHub issues and pull request feature for questions and patches:

  http://github.com/libnet/libnet

Some old docs are available at:

  http://packetfactory.openwall.net/projects/libnet/index.html


[Appveyor]:        https://ci.appveyor.com/project/troglobit/libnet
[Appveyor Status]: https://ci.appveyor.com/api/projects/status/fkw05hw8cysfl2p1?svg=true
[Travis]:          https://travis-ci.org/libnet/libnet
[Travis Status]:   https://travis-ci.org/libnet/libnet.png?branch=master
