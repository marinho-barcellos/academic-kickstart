---
title: "Dynamic Property Enforcement in Programmable Data Planes"
authors: ["Miguel Neves", "Bradley Huffaker", "Kirill Levchenko", "Marinho Barcellos"]
# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Networking, pp. 1540-1552, vol. 29"
publication_short: "*ToN*"
publication_types: ["2"]
date: 2021-08-01
publishDate: 2021-08-01
featured: false
tags: ["p4", "programmable data planes", "enforcement"]
links:
- name: DL
  url: https://doi.org/10.1109/TNET.2021.3068339
doi: "10.1109/TNET.2021.3068339"
url_pdf: "publication/2021-ton-neves/ton21-p4box-neves.pdf"
url_project: project/p4sec-RNP-NSF


#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

abstract: "Network programmers can currently deploy an arbitrary set of protocols in forwarding devices through data plane programming languages such as P4. However, as any other type of software, P4 programs are subject to bugs and misconfigurations. Network verification tools have been proposed as a means of ensuring that the network behaves as expected, but these tools frequently face severe scalability issues. In this paper, we argue for a novel approach to this problem. Rather than statically inspecting a network configuration looking for bugs, we propose to enforce networking properties at runtime. To this end, we developed P4box, a system for deploying runtime monitors in programmable data planes. P4box allows programmers to easily express a broad range of properties (both program-specific and network-wide). Moreover, we provide an automated framework based on assertions and symbolic execution for ensuring monitor correctness. Our experiments on a SmartNIC show that P4box monitors represent a small overhead to network devices in terms of latency, throughput and power consumption."

# Summary. An optional shortened abstract.
#summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- P4Sec

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


