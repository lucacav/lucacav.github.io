---
permalink: /res/
title: "Resources"
author_profile: true
---

This is a collection of resources that made my research possible and also provide some usefull insights. 

## Software

Software created by my research group or in projects where I was involved with a scientific coordination role. Each repository is owned by the respective author. We would love to hear how you used the tools... 

**pcapStego** is an effective CLI tool for creating network covert channels within a .pcap file. The modified .pcap can be used for simulations and for preparing datasets. Traffic can be also lively replayed with [Tcpreplay](https://tcpreplay.appneta.com) against a network destination. [[REPO]](https://github.com/Ocram95/pcap_injector). [[PAPER]](https://dl.acm.org/doi/10.1145/3465481.3470067).

**DockerChannel** is a Python framework that allows to test covert channels between two Docker containers. The suite is composed of 5 basic covert channels that exploit the "loose" isolation of the /proc provided by Docker. It can be easily extanded to implement new covert communication mechanisms. [[REPO]](https://github.com/cybersecurity-cnr/DockerChannel/tree/main). [[PAPER]](https://www.sciencedirect.com/science/article/pii/S2352711023002728).

**IPv6CC** is a tool for implementing several network covert channels targeting the IPv6 protocol and test real deployments. It also supports different injection modes and naive/reliable packet marking mechanisms.  [[REPO]](https://github.com/Ocram95/IPv6CC_SoftwareX). [[PAPER]](https://www.sciencedirect.com/science/article/pii/S2352711022000024).

**bccstego** is a tiny framework for inspecting IP packets and compute histograms of seen values used for a specific header field. The program installs an eBPF filter on the ingress/egress path of a network interface and collects  measurements. Originally developed for spotting anomalous usages of fields and detect covert channels. [[REPO]](https://github.com/mattereppe/bccstego). [[PAPER1]](https://dl.acm.org/doi/abs/10.1145/3465481.3470028). [[PAPER2]](https://www.sciencedirect.com/science/article/pii/S1389128621001249). [[PAPER3]](https://ieeexplore.ieee.org/abstract/document/9779347). 

**Docker Stego Protector** is a small proof-of-concept Docker container for mitigating covert channels exploiting the memory of the host to create malicious container-to-container communications (see, e.g., the [YehudaCorsia/Docker-Covert-channel](https://github.com/YehudaCorsia/Docker-Covert-channel)). [[REPO]](https://github.com/cybersecurity-cnr/docker-stego-protector). [[PAPER1]](https://ieeexplore.ieee.org/abstract/document/10175435). [[PAPER2]](https://dl.acm.org/doi/abs/10.1145/3664476.3670884). 

## Other Resources

**steg-in-the-wild** is a list of real-world attacks or offensive campaigns that deployed steganography or information hiding to avoid detection. The list is maintained in a **relaxed** manner by [Wojciech Mazurczyk](http://mazurczyk.com) and me. [[REPO]](https://github.com/lucacav/steg-in-the-wild). [[PAPER]](https://ieeexplore.ieee.org/abstract/document/9889000).

**steg-tools** is a small collection of tools and resources for learning and experimenting with steganography and information hiding. I prepared it for having some fun with students of my course entitled **Information Hiding** that I regularly give to Ph.D. candidates of the [University of Genova](https://unige.it). [[REPO]](https://github.com/lucacav/steg-tools).

**Network Information Hiding 101** is the online course prepared by [Steffen Wendzel](https://www.wendzel.de) discussing terminology, methodology and practical aspects of *Network Steganography* and *Network Covert Channels*. If you have serious plans to party in network security, you ~~should~~ must check it. [[REPO]](https://github.com/cdpxe/Network-Covert-Channels-A-University-level-Course)