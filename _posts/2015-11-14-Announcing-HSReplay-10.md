---
layout: post
title: Announcing HSReplay 1.0
permalink: /blog/announcing-hsreplay-10/
---

I'm really excited to announce the release of [HSReplay 1.0]({{ site.baseurl }}/hsreplay/).

HSReplay is a specification for an XML-based format implementing Hearthstone
replay files. It is inspired by the internal Hearthstone packets, closely
following their structure, and can be generated by reading the Power.log file.

The [HSReplay repository](https://github.com/hearthsim/hsreplay) includes a
reference implementation in Python and C#. They can read Power.log files and
produce HSReplay output.
Examples are available available [on the HSReplay page]({{ site.baseurl }}/hsreplay/).

In the near future, support for HSReplay files will be available on both
[Hearthstone Deck Tracker](http://hsdecktracker.net) and [HearthStats](http://hearthstats.net/).

The format is licensed CC0, essentially placing it in the public domain. This
makes it legally suitable for use in all applications, without any attribution.

As development is meant to be done in the open, we are inviting everyone else
who wants to work on or with replay files to send us an email at
<[contact@hearthsim.info](mailto:contact@hearthsim.info)>. We will be happy
integrate them and improve the spec further.
Yes, Blizzard, this goes for you too. :)

The DTD for the HSReplay format is available here:

<http://hearthsim.info/hsreplay/dtd/hsreplay-1.0.dtd>

Jerome
