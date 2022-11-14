---
title: "POSTER: Finding vulnerabilities in P4 programs with assertion-based verification"
authors: ["Lucas Freire", "Miguel Neves", "Alberto Schaeffer-Filho", "Marinho Barcellos"]
publication: "Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security (ACM CCS)"
publication_short: "*ACM CCS posters*"
publication_types: ["1"]
date: 2017-11-01
publishDate: 2017-11-01
featured: false
tags: ["P4", "Programmable Data Planes", "Verification"]
links:
- name: DL
  url: https://doi.org/10.1145/3133956.3138837
doi: "10.1145/3133956.3138837"
url_pdf: "papers/2017-ccsposters-freire.pdf"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: "slides/2019-conext-muller-slides.pdf"
#url_source: '#'
#url_video: '#'---

abstract: "Current trends in SDN extend network programmability to the data plane through the use of programming languages such as P4. In this context, the chance of introducing errors and consequently software vulnerabilities in the network increases significantly. Existing data plane verification mechanisms are unable to model P4 programs or present severe restrictions in the set of modeled properties. To overcome these limitations and make programmable data planes more secure, we present a P4 program verification technique based on assertion checking and symbolic execution. First, P4 programs are annotated with assertions expressing general correctness and security properties. Then, the annotated programs are transformed into C code and all their possible paths are symbolically executed. Results show that it is possible to prove properties in just a few seconds using the proposed technique. Moreover, we were able to uncover two potential vulnerabilities in a large scale P4 production application."


---