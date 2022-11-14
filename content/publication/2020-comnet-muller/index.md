---
title: "Spoofed Traffic Inference at IXPs: Challenges, Methods and Analysis"
authors: ["Lucas Muller", "Matthew Luckie", "Bradley Huffaker", "Kimberly C Claffy", "Marinho Barcellos"]
publication: "Computer Networks Journal (COMNET)"
publication_short: "*COMNET*"
publication_types: ["2"]
date: 2020-08-01
#publishDate: 2019-12-17
featured: false
tags: ["IP Spoofing", "IXP", "Internet measurements"]
links:
links:
- name: ScienceDirect
  url: http://www.sciencedirect.com/science/article/pii/S1389128620311336
doi: "10.1016/j.comnet.2020.107452"

url_pdf: "publication/2020-comnet-muller/muller-spoofer-ix.pdf" # not placing the file because it is open and this way we count downloads
#doi: "10.1109/MSEC.2018.2874855"
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_source: '#'
#url_video: '#'

abstract: "Ascertaining that a network will forward spoofed traffic usually requires an active probing vantage
point in that network, effectively preventing a comprehensive view of this global Internet vulnerability.
Recently, researchers have proposed using Internet Exchange Points (IXPs) as observatories
to detect spoofed packets, by leveraging Autonomous System (AS) topology knowledge extracted
from Border Gateway Protocol (BGP) data to infer which source addresses should legitimately appear
across parts of the IXP switch fabric. We demonstrate that the existing literature does not capture
several fundamental challenges to this approach, including noise in BGP data sources, heuristic AS
relationship inference, and idiosyncrasies in IXP interconnectivity fabrics. We propose Spoofer-IX,
a novel method to navigate these challenges, leveraging customer cone semantics of AS relationships
to guide precise classification of inter-domain traffic as in-cone, out-of-cone (spoofed), unverifiable,
bogon, and unassigned. We apply our method in three distinct periods to two IXPs, with 200+ and
1,600+ members each, and find an upper bound volume of out-of-cone traffic to be more than an
order of magnitude less than the previous method inferred on the same data, revealing the practical
importance of customer cone semantics in such analysis. We observed no significant improvement in
deployment of Source Address Validation (SAV) in networks using the mid-size IXP between 2017
and 2019. In hopes that our methods and tools generalize to use by other IXPs whowant to avoid use of
their infrastructure for launching spoofed-source DoS attacks, we explore the feasibility of scaling the
system to larger and more diverse IXP infrastructures. To promote this goal, and broad replicability
of our results, we make the source code of Spoofer-IX publicly available."


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

