# Heartbleed Honeypot

This Perl script listens on TCP port 443 and responds with completely bogus SSL heartbeat responses, unless it detects the start of a byte pattern similar to that used in Jared Stafford's (jspenguin@jspenguin.org) demo for CVE-2014-0160 'Heartbleed'. Run as root for the privileged port. Outputs IPs of suspected heartbleed scan to the console. Rickrolls scanner in the hex dump.

This work comes from not more accessible https://packetstormsecurity.com
