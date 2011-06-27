---
layout: blog 
title: "IPv6 Day Started"
---                     

IPv6 day officially started at midnight GMT. Over the next 24 hrs, a number of large web sites will be reachable via IPv6. For example Google, Yahoo and Facebook added AAAA records.

You can check yourself if you are able to receive the AAAA records with this nslookup command:

nslookup
> set type=AAAA
> www.facebook.com

Non-authoritative answer:
www.facebook.com    has AAAA address 2620::1c08:4000:face:b00c:0:2


The next 24 hrs bring a unique opportunity to test IPv6 and to experiment with it. I recommend that you setup at least a test system and attempt to connect to IPv6 via a tunnelbroker. You may also be able to use auto-configured 6-to-4 but it tends to be less reliable. See the end of this article for a number of free tunnel brokers.

Things to test:

    ping Google: on unix, use ping6 www.google.com, on Windows, ping -6 www.google.com
    measure latency via IPv4 and IPv6 and compare.
    test if you can reach various IPv6 sites (http://isc.sans.edu has been dual stack for a while now)
    can you detect the traffic with whatever tools you use (snort, tcpdump, windump, wireshark...)

More information about IPv6 day:

http://ipv6day.org