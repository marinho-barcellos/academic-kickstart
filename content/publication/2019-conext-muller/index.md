---
title: "Challenges in Inferring Spoofed Traffic at IXPs"
authors: ["Lucas Muller", "Matthew Luckie", "Bradley Huffaker", "Kimberly C Claffy", "Marinho Barcellos"]
publication: "Proceedings of the 15th International Conference on Emerging Networking Experiments And Technologies (ACM CoNEXT)"
publication_short: "*ACM CoNEXT*"
publication_types: ["1"]
date: 2019-12-09
publishDate: 2019-12-11
featured: false
tags: ["IP Spoofing", "IXP", "Internet measurements"]
links:
- name: DL
  url: https://dl.acm.org/citation.cfm?id=3365422

doi: "10.1145/3359989.3365422"
url_pdf: "papers/2019-conext-muller.pdf"
url_slides: "slides/2019-conext-muller-slides.pdf"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_source: '#'
#url_video: '#'

abstract: "Ascertaining that a network will forward spoofed traffic usually requires an active probing vantage point in that network, effectively preventing a comprehensive view of this global Internet vulnerability. Recently, researchers have proposed using Internet Exchange Points (IXPs) as observatories to detect spoofed packets, by leveraging Autonomous System (AS) topology knowledge extracted from Border Gateway Protocol (BGP) data to infer which source addresses should legitimately appear across parts of the IXP switch fabric. We demonstrate that the existing literature does not capture several fundamental challenges to this approach, including noise in BGP data sources, heuristic AS relationship inference, and idiosyncrasies in IXP interconnectivity fabrics. We propose a novel method to navigate these challenges, leveraging customer cone semantics of AS relationships to guide precise classification of inter-domain traffic as in-cone, out-of-cone (spoofed), unverifiable, bogon, and unassigned. We apply our method to a mid-size IXP with approximately 200 members, and find an upper bound volume of out-of-cone traffic to be more than an order of magnitude less than the previous method inferred on the same data. Our work illustrates the subtleties of scientific assessments of operational Internet infrastructure, and the need for a community focus on reproducing and repeating previous methods."

# Summary. An optional shortened abstract.
summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- P4Sec

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

