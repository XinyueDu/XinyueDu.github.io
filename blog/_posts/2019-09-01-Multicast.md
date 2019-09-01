---
title: "WIFI Multicast"
subtitle: "802.11 MAC  protocol design"
layout: post
tags : [study]
---
Existing multicast protocols are not so efficient when they are used combining with the frame aggregation scheme of IEEE 802.11n.

the existing multicast protocols have serious  problems in 802.11n WLANs when the A-MPDU aggregation is used for multicast transmissions
1 ACK & NAK-based ARQ conflictt
2 rate mechanism cannot select appropriate date rate for A-MPDAU transmission 

In order to improve the  performance of multicast services in IEEE802.11n ,**Reliable and Efficient Multicast Protocol (REMP)**

Although REMP can provide reliable multicast servicesto multicast receivers, it may heavily penalize receivers exhibiting better channel conditions.
The extension of REMP, referred to as scalable REMP (S-REMP), aims at guaranteeing the minimal video quality to all users while providing a higher video quality to users exhibiting better channel conditions.
In S-REMP, different layers of scalable video are transmitted with different MCSs according to the network load.