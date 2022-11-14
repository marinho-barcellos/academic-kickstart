---
title: "Light, Camera, Actions: characterizing the usage of IXPs' action BGP communities"
authors: ["Fabricio Mazzola", "Pedro Marcos", "Marinho Barcellos"]
publication: "2022 CoNEXT (to appear)"
publication_short: "*CoNEXT*  (to appear)"
publication_types: ["1"]
date: 2022-10-01
publishDate: 2022-10-01
featured: false
tags: ["BGP Communities", "IXPs"]
links:
# - name: DL
#   url: https://dl.acm.org/doi/10.1145/3419394.3423642
# doi: "10.1145/3419394.3423642"

#url_pdf: "publication/2022-pam-mazzola/pam22-rp.pdf"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

abstract: "Border Gateway Protocol (BGP) communities, an optional message attribute, allow network operators to tag BGP announcements and act on routing decisions. Although widely used, it is so far unclear how prevalent the different types of communities are and the degree to which the different traffic engineering actions have been used. There are two major reasons for this gap: few community values have been standardised and the limited visibility at route collectors. In this paper, leveraging the fact that Internet eXchange Points (IXPs) have sets of well-documented BGP communities, we use their BGP Looking Glasses (LGs) to inspect their route servers and shed light on how IXP members are using action BGP commu- nities. During twelve weeks, we collected and analysed routing data from eight IXPs worldwide, focusing the analysis on the four largest IXPs. We observe that i) over one-third of IXP members (>35.7%) use action communities in at least one route; ii) two-thirds (66.6%) of them are intended to avoid propagating routes, mostly to content providers (CPs); iii) nearly one-third (31.8%) are targeting Autonomous Systems (ASes) that are not present at the IXPs’ route servers, resulting in no practical routing effect and only increasing processing and memory storage overheads."

# Summary. An optional shortened abstract.
#summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- FRIDA

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---




