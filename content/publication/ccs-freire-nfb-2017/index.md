---
title: "Poster: Finding vulnerabilities in P4 programs with assertion-based verification"
date: 2017-01-01
publishDate: 2019-12-01T08:31:06.074405Z
authors: ["Lucas Freire", "Miguel Neves", "Alberto Schaeffer-Filho", "Marinho Barcellos"]
publication_types: ["1"]
abstract: "Current trends in SDN extend network programmability to the data plane through the use of programming languages such as P4. In this context, the chance of introducing errors and consequently software vulnerabilities in the network increases significantly. Existing data plane verification mechanisms are unable to model P4 programs or present severe restrictions in the set of modeled properties. To overcome these limitations and make programmable data planes more secure, we present a P4 program verification technique based on assertion checking and symbolic execution. First, P4 programs are annotated with assertions expressing general correctness and security properties. Then, the annotated programs are transformed into C code and all their possible paths are symbolically executed. Results show that it is possible to prove properties in just a few seconds using the proposed technique. Moreover, we were able to uncover two potential vulnerabilities in a large scale P4 production application."
featured: false
publication: "*ACM CCS*"
tags: ["P4", "Programmable Data Planes", "Verification"]
url_pdf: "https://doi.org/10.1145/3133956.3138837"
doi: "10.1145/3133956.3138837"
---

