---
title: "Uncovering Bugs in P4 Programs with Assertion-based Verification"
date: 2018-01-01
publishDate: 2019-12-01T08:31:06.116555Z
authors: ["Lucas Freire", "Miguel Neves", "Lucas Leal", "Kirill Levchenko", "Alberto Schaeffer-Filho", "Marinho Barcellos"]
publication_types: ["1"]
abstract: "Recent trends in software-defined networking have extended net-work programmability to the data plane through programming languages such as P4. Unfortunately, the chance of introducing bugs in the network also increases significantly in this new context. Existing data plane verification approaches are unable to model P4 programs, or they present severe restrictions in the set of proper-ties that can be modeled. In this paper, we introduce a data plane program verification approach based on assertion checking and symbolic execution. Network programmers annotate P4 programs with assertions expressing general security and correctness proper-ties. Once annotated, these programs are transformed into C-based models and all their possible paths are symbolically executed. Re-sults show that the proposed approach, called ASSERT-P4, can uncover a broad range of bugs and software flaws. Furthermore, experimental evaluation shows that it takes less than a minute for verifying various P4 applications proposed in the literature."
featured: false
publication: "*ACM SOSR*"
tags: ["p4", "programmable data planes", "verification"]
url_pdf: "http://dl.acm.org/citation.cfm?doid=3185467.3185499"
doi: "10.1145/3185467.3185499"
---

