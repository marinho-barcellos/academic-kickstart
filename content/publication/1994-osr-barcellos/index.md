---
title: "The HetNOS network operating system: a tool for writing distributed applications"
authors: ["Marinho Barcellos", "Valdir Belmonte Filho", "João Schramm", "Cláudio Geyer"]
publication: "ACM SIGOPS Operating Systems Review (ACM OSR)"
publication_short: "*ACM OSR*"
publication_types: ["2"]
date: 1994-10-01
publishDate: 1994-10-01
featured: false
tags: ["distributed operating systems", "heterogeneity"]

links:
- name: DL
  url: http://portal.acm.org/citation.cfm?id=191525.191534
url_pdf: "papers/1994-osr-barcellos.pdf"
doi: "10.1145/191525.191534"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: "slides/2019-conext-muller-slides.pdf"
#url_source: '#'
#url_video: '#'


abstract: "The HetNOS network operating system is a set of software layers laid over 'native' operating systems to provide a distributed programming platform. The environment is composed of the HetNOS shell command language and the system calls interface (accessed through a procedure library). In both levels of interaction with users, the set of machines integrated by HetNOS are seen as a distributed virtual machine.The HetNOS command interpreter, namely hsh, implements most functions present in more traditional command interpreters. It is possible to spawn, monitor, and terminate processes in any host in the network like in the local case. The HetNOS distributed kernel uses a symbolic, global, location independent, process identification scheme. Distributed applications are split into sequential processes, which interact with each other by message exchange. There are neither connections nor ports, being the communication mechanism strongly influenced by the process identification scheme. This paper briefly describes the HetNOS software organization, presents the HetNOS environment for distributed programming, and then compares HetNOS with related work."

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

