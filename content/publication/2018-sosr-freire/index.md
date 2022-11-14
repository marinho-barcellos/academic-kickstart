---
title: "Uncovering Bugs in P4 Programs with Assertion-based Verification"
authors: ["Lucas Freire", "Miguel Neves", "Lucas Leal", "Kirill Levchenko", "Alberto Schaeffer-Filho", "Marinho Barcellos"]
publication: "Proceedings of the Symposium on SDN Research (ACM SOSR)"
publication_short: "*ACM SOSR*"
publication_types: ["1"]
date: 2018-03-15
publishDate: 2018-03-15
featured: false
tags: ["p4", "programmable data planes", "verification"]
links:
- name: DL
  url: http://dl.acm.org/citation.cfm?doid=3185467.3185499
doi: "10.1145/3185467.3185499"

#url_pdf: "papers/2018-sosr-freire.pdf"

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'


abstract: "Recent trends in software-defined networking have extended network programmability to the data plane through programming languages such as P4. Unfortunately, the chance of introducing bugs in the network also increases significantly in this new context. Existing data plane verification approaches are unable to model P4 programs, or they present severe restrictions in the set of properties that can be modeled. In this paper, we introduce a data plane program verification approach based on assertion checking and symbolic execution. Network programmers annotate P4 programs with assertions expressing general security and correctness properties. Once annotated, these programs are transformed into C-based models and all their possible paths are symbolically executed. Results show that the proposed approach, called ASSERT-P4, can uncover a broad range of bugs and software flaws. Furthermore, experimental evaluation shows that it takes less than a minute for verifying various P4 applications proposed in the literature."

# Summary. An optional shortened abstract.
summary:  An optional shortened abstract.


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- P4Sec

---



