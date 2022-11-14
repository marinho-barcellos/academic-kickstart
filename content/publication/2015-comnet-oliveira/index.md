---
title: "Opportunistic resilience embedding (ORE): Toward cost-efficient resilient virtual networks"
authors: ["Rodrigo Oliveira", "Daniel Marcon", "Leonardo Bays", "Miguel Neves", "Luciano P Gaspary", "Deep Medhi", "Marinho Barcellos"]
publication: "Computer Networks Journal (COMNET)"
publication_short: "*COMNET*"
publication_types: ["2"]
date: 2015-10-01
publishDate: 2015-10-01
featured: false
tags: ["software-defined networks", "virtual network embedding"]
links:
- name: ScienceDirect
  url: https://doi.org/10.1016/j.comnet.2015.07.010
doi: "10.1016/j.comnet.2015.07.010"
url_pdf: "papers/2015-comnet-oliveira.pdf"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: "slides/2019-conext-muller-slides.pdf"
#url_source: '#'
#url_video: '#'

abstract: "Network Virtualization promotes the development of new architectures and protocols by enabling the creation of multiple virtual networks on top of the same physical substrate. One of its main advantages is the use of isolation to limit the scope of attacks – that is, avoiding traffic from one virtual network to interfere with the others. However, virtual networks are still vulnerable to disruptions on the underlying network. Particularly, high capacity physical links constitute good targets since they may be important for a large number of virtual networks.

Previous work protects virtual networks by setting aside backup resources. Although effective, this kind of solution tends to be expensive, as backup resources increase the cost to infrastructure providers and usually remain idle. This paper presents ORE (opportunistic resilience embedding), a novel embedding approach for protecting virtual links against substrate network disruptions. ORE’s design is two-fold: while a proactive strategy embeds each virtual link into multiple substrate paths in order to mitigate the initial impact of a disruption, a reactive one attempts to recover any capacity affected by an underlying disruption. Both strategies are modeled as optimization problems. Additionally, since the embedding problem is -Hard, ORE uses a simulated annealing-based meta-heuristic to solve it efficiently. Numerical results show that ORE can provide resilience to disruptions at a lower cost."


# Summary. An optional shortened abstract.
summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- P4Sec

---



