---
title: From a spinning chip on /24 to a rolling doggo on /48
date: 2025-11-05
draft: false
---

I've come across a now-deleted Reddit post about how the whole range **89.106.90.0/24** has a single gif on it with a spinning chip. Meaning you can visit [89.106.90.1](http://89.106.90.1) or [89.106.90.233](http://89.106.90.233) and it will serve the same static page. I think that's hilarious use of an expensive /24 IPv4 range. 

Last year [I registered ASN](https://jf.si/posts/2024-07-27-ipv6-asn-bgp-wireguard/) and bought/leased a few IPv6 ranges and thought to myself why wouldn't I do the same thing but only on IPv6 /48 range? The only difference is that IPv4 /24 range has **only 256 IPs** on which the spinning chip is spinning and IPv6 /48 range has **281 trillion** IPs on which doggo is rolling. 

I used a subnet from my range of 2a0a:6044:bf00::/40 and decided on **2a0a:6044:bf4c::/48**. So now if you have IPv6 connectivity you can see a rolling doggo on all 281 trillion IPs. 

This is the doggo used:

![Spinning doggo](https://media.tenor.com/OqCFkWUCqScAAAAi/dog.gif)

A few funny examples:

- [http://[2a0a:6044:bf4c:c0de::cafe]](http://[2a0a:6044:bf4c:c0de::cafe])
- [http://[2a0a:6044:bf4c:feed::face]](http://[2a0a:6044:bf4c:feed::face])
- [http://[2a0a:6044:bf4c:ba5e::ba11]](http://[2a0a:6044:bf4c:ba5e::ba11])
- [http://[2a0a:6044:bf4c:ace::bead]](http://[2a0a:6044:bf4c:ace::bead])
- [http://[2a0a:6044:bf4c:fab::deed]](http://[2a0a:6044:bf4c:fab::deed])

![Website](/images/spinning-doggo-website.png)

Or from the toxic masculinity list:

- [http://[2a0a:6044:bf4c::cafe:babe]](http://[2a0a:6044:bf4c::cafe:babe])
- [http://[2a0a:6044:bf4c::dead:beef]](http://[2a0a:6044:bf4c::dead:beef])
- [http://[2a0a:6044:bf4c::bad:c0de]](http://[2a0a:6044:bf4c::bad:c0de])
- [http://[2a0a:6044:bf4c::b00b:1e55]](http://[2a0a:6044:bf4c::b00b:1e55])
- [http://[2a0a:6044:bf4c:fab:0:cab:ace:f001]](http://[2a0a:6044:bf4c:fab:0:cab:ace:f001])

Yeah, most of these IPv6 URLs can be quite childish, sorry about that. 