---
title: "Dynamic Property Enforcement in Programmable Data Planes"
date: 2019-05-01
publishDate: 2019-12-01T08:31:06.109910Z
authors: ["Miguel Neves", "Bradley Huffaker", "Kirill Levchenko", "Marinho Barcellos"]
publication_types: ["1"]
abstract: "Network programmers can currently deploy an arbitrary set of protocols in forwarding devices through data plane programming languages such as P4. However, as any other type of software, P4 programs are subject to bugs and misconfigurations. Network verification tools have been proposed as a means of ensuring that the network behaves as expected, but these tools typically require programmers to manually model P4 programs, are limited in terms of the properties they can guarantee and frequently face severe scalability issues. In this paper, we argue for a novel approach to this problem. Rather than statically inspecting a network configuration looking for bugs, we propose to enforce networking properties at runtime. To this end, we developed P4box, a system for deploying runtime monitors in programmable data planes. Our results show that P4box allows programmers to easily express a broad range of properties. Moreover, we demonstrate that runtime monitors represent a small overhead to network devices in terms of latency and resource consumption."
featured: false
publication: "*IFIP Networking*"
url_pdf: "https://ieeexplore.ieee.org/document/8816830/"
doi: "10.23919/IFIPNetworking.2019.8816830"
---

