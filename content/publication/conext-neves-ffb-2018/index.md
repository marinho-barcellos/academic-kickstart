---
title: "Verification of P4 programs in feasible time using assertions"
date: 2018-01-01
publishDate: 2019-12-01T08:31:06.100476Z
authors: ["Miguel C Neves", "Lucas Freire", "Alberto E Schaeffer Filho", "Marinho P Barcellos"]
publication_types: ["1"]
abstract: "Recent trends in software-defined networking have extended net- work programmability to the data plane. Unfortunately, the chance of introducing bugs increases significantly. Verification can help prevent bugs by assuring that the program does not violate its re- quirements. Although research on the verification of P4 programs is very active, we still need tools to make easier for programmers to express properties and to rapidly verify complex invariants. In this paper, we leverage assertions and symbolic execution to propose a more general P4 verification approach. Developers annotate P4 programs with assertions expressing general network correctness properties; the result is transformed into C models and all possi- ble paths symbolically executed. We implement a prototype, and use it to show the feasibility of the verification approach. Because symbolic execution does not scale well, we investigate a set of tech- niques to speed up the process for the specific case of P4 programs. We use the prototype implemented to show the gains provided by three speed up techniques (use of constraints, program slicing, par- allelization), and experiment with different compiler optimization choices. We show our tool can uncover a broad range of bugs, and can do it in less than a minute considering various P4 applications."
featured: false
publication: "*ACM CoNEXT*"
url_pdf: "https://doi.org/10.1145/3281411.3281421"
doi: "10.1145/3281411.3281421"
---

