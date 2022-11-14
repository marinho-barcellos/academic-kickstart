---
title: "AS-Path Prepending: there is no rose without a thorn"
authors: ["Pedro Marcos", "Lars Prehn", "Lucas Leal", "Alberto Dainotti", "Anja Feldmann", "Marinho Barcellos"]
publication: "Proceedings of the 2020 Internet Measurement Conference (ACM IMC)"
publication_short: "*ACM IMC*"
publication_types: ["1"]
date: 2020-10-27
publishDate: 2020-10-27
featured: false
tags: ["ASPP", "BGP", "Internet Security"]
links:
- name: DL
  url: https://dl.acm.org/doi/10.1145/3419394.3423642
doi: "10.1145/3419394.3423642"

url_pdf: "publication/2020-imc-marcos/imc2020-final.pdf"
#url_project: https://dynam-ix.github.io

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

abstract: "Inbound traffic engineering (ITE)—the process of announcing routes
to, e.g., maximize revenue or minimize congestion—is an essential
task for Autonomous Systems (ASes). AS Path Prepending (ASPP) is
an easy to use and well-known ITE technique that routing manuals
show as one of the first alternatives to influence other ASes’ routing
decisions.We observe that origin ASes currently prepend more than
25% of all IPv4 prefixes.
ASPP consists of inflating the BGP AS path. Since the length of
the AS path is the second tie-breaker in the BGP best path selection,
ASPP can steer traffic to other routes. Despite being simple
and easy to use, the appreciation of ASPP among operators and
researchers is diverse. Some have questioned its need, effectiveness,
and predictability, as well as voiced security concerns. Motivated by
these mixed views, we revisit ASPP. Our longitudinal study shows
that ASes widely deploy ASPP, and its utilization has slightly increased
despite public statements against it. We surprisingly spot
roughly 6k ASes originating at least one prefix with prepends that
achieve no ITE goal. With active measurements, we show that ASPP
effectiveness as an ITE tool depends on the AS location and the
number of available upstreams; that ASPP security implications are
practical; identify that more than 18% of the prepended prefixes
contain unnecessary prepends that achieve no apparent goal other
than amplifying existing routing security risks. We validate our
findings in interviews with 20 network operators."

# Summary. An optional shortened abstract.
#summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- Dynam-IX

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---




