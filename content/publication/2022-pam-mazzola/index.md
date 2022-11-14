---
title: "On the Latency Impact of Remote Peering"
authors: ["Fabricio Mazzola", "Pedro Marcos", "Ignacio Castro", "Matthew Luckie", "Marinho Barcellos"]
publication: "Proceedings of the 2022 Passive Active Measurement Conference (PAM)"
publication_short: "*PAM*"
publication_types: ["1"]
date: 2022-02-01
publishDate: 2022-02-01
featured: false
tags: ["Remote Peering", "IXPs", "BGP"]
links:
# - name: DL
#   url: https://dl.acm.org/doi/10.1145/3419394.3423642
# doi: "10.1145/3419394.3423642"

url_pdf: "publication/2022-pam-mazzola/pam22-rp.pdf"
#url_project: https://dynam-ix.github.io

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

abstract: "Internet Exchange Points (IXPs) play an essential role in the Internet, providing a fabric for thousands of Autonomous Systems (ASes) to interconnect. Initially designed to keep local traffic local, IXPs now interconnect ASes all over the world, and the premise that IXP routes should be shorter and faster than routes through a transit provider may not be valid anymore. Using BGP views from eight IXPs (three in Brazil, two in the U.S., and one each in London, Amsterdam, and Johannesburg), a transit connection at each of these locations, and latency measurements we collected in May 2021, we compare the latency to reach the same addresses using routes from remote peers, local peers, and transit providers. For four of these IXPs, at least 71.4% of prefixes advertised by remote peers also had a local peering route, BGP generally preferred the remote route due to its shorter AS path, but the local route had lower latency than the remote route in the majority of cases. When a remote route was the only peering route available at an IXP, it had slightly lower latency than a corresponding transit route available outside the IXP for >57.6% of the prefixes for seven of the eight IXPs."

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




