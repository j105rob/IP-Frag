IP Frag Streaming Packet Reassembly
===================================

This is the attempt at capturing resources from traffic sniffing on the fly.

The reassembler.py was originally source from http://baggett-scripts.googlecode.com/svn/trunk/reassembler/reassembler.py
which was part of http://www.sans.org/reading_room/whitepapers/detection/ip-fragment-reassembly-scapy_33969

I needed a way to stream live caps thru a process that would reassemble the packets based on resource types I am interested
in looking at.

Eventually this will be rolled into a ex-filtration detector.

j105rob