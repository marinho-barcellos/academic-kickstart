---
title: "Shoehorn: Towards Portable P4 for Low Cost Hardware"
authors: ["Christopher Lorier", "Matthew Luckie", "Marinho Barcellos", "Richard Nelson"]
publication: "IFIP Networking"
publication_short: "*IFIP Networking*"
publication_types: ["1"]
date: 2022-04-01
publishDate: 2022-04-01
featured: false
tags: ["SDN", "p4"]
links:
- name: DL
  url: https://doi.org/10.23919/IFIPNetworking55013.2022.9829819
doi: "10.23919/IFIPNetworking55013.2022.9829819"
url_pdf: "publication/2022-networking-lorier/networking22-shoehorn-lorier.pdf"


#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

abstract: "Having a consistent application stack for hardware from multiple vendors allows operators to build simpler, more stable networks. However, due to the limitations of low cost, fixed-function networking hardware, creating portable controlplane software with current SDN standards requires accepting limited functionality, navigating inconsistent implementations, or using powerful, flexible hardware that is prohibitively expensive in many scenarios. This paper describes Shoehorn, a system for creating portable SDN control-plane software for low cost hardware. Shoehorn allows control-plane software to define a hardware-agnostic virtual pipeline in P4 that can be algorithmically translated to control diverse low-cost hardware without a significant impact on memory usage or the rate that tables can be updated. To demonstrate the effectiveness of Shoehorn, we created virtual pipelines for a variety of existing control-plane software, and mapped them to low cost hardware. We found that the virtual pipelines could be supported by hardware from multiple vendors in almost all cases."

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




