---
title: "Verification of P4 programs in feasible time using assertions"
authors: ["Miguel Neves", "Lucas Freire", "Alberto Schaeffer-Filho", "Marinho Barcellos"]
publication: "Proceedings of the 14th International Conference on Emerging Networking Experiments And Technologies (ACM CoNEXT)"
publication_short: "*ACM CoNEXT*"
date: 2018-12-04
publishDate: 2018-12-04
publication_types: ["1"]
featured: false
tags: ["p4", "programmable data planes", "verification"]
links:
- name: DL
  url: https://dl.acm.org/citation.cfm?doid=3281411.3281421
doi: "10.1145/3281411.3281421"

#url_pdf: "papers/2018-conext-neves.pdf"
#url_slides: ''

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_source: '#'
#url_video: '#'


abstract: "Recent trends in software-defined networking have extended network programmability to the data plane. Unfortunately, the chance of introducing bugs increases significantly. Verification can help prevent bugs by assuring that the program does not violate its requirements. Although research on the verification of P4 programs is very active, we still need tools to make easier for programmers to express properties and to rapidly verify complex invariants. In this paper, we leverage assertions and symbolic execution to propose a more general P4 verification approach. Developers annotate P4 programs with assertions expressing general network correctness properties; the result is transformed into C models and all possible paths symbolically executed. We implement a prototype, and use it to show the feasibility of the verification approach. Because symbolic execution does not scale well, we investigate a set of techniques to speed up the process for the specific case of P4 programs. We use the prototype implemented to show the gains provided by three speed up techniques (use of constraints, program slicing, parallelization), and experiment with different compiler optimization choices. We show our tool can uncover a broad range of bugs, and can do it in less than a minute considering various P4 applications."

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




