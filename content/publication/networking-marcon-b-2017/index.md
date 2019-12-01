---
title: "Packer: Minimizing multi-resource fragmentation and performance interference in datacenters"
date: 2017-01-01
publishDate: 2019-12-01T08:31:06.097551Z
authors: ["Daniel S Marcon", "Marinho P Barcellos"]
publication_types: ["1"]
abstract: "—Cloud applications perform rich and complex tasks, with time-varying demands for multiple types of resources (CPU, memory, disk I/O and network). However, multi-resource allocation is APX-Hard and, consequently, providers simplify it by (i) allocating computing resources according to slots (which leads to fragmentation); and (ii) allowing the network to be shared in a best-effort manner (which leads to performance interference among applications). Recent efforts cannot minimize multi-resource fragmentation and, at the same time, provide guaranteed network performance. In this paper, we introduce Packer, a scheme that aims at minimizing multi-resource frag- mentation and providing predictable and guaranteed network performance with work-conservation. Packer employs a novel allocation strategy that (a) extends previous heuristics developed for multi-dimensional bin packing; and (b) uses as input a new abstraction, called Time-Interleaved Multi-Resource Abstraction (TI-MRA), for specifying temporal multi-resource requirements of applications. It also leverages Software-Defined Networking to dynamically enforce bandwidth guarantees and to provide work- conserving sharing. Since Packer brings more benefits if temporal requirements are specified, it is better suited for applications that present a predefined behavior, repeatedly running the same type of tasks with similar input sizes and data sets (such as PageRank and traffic analysis). Results show that, in comparison to the state- of-the-art, acceptance ratio is increased, datacenter utilization is improved (i.e., fragmentation is minimized), provider revenue is augmented and applications achieve predictable and guaranteed network performance with work-conservation, with the cost of taking more (yet acceptable) time to allocate applications."
featured: false
publication: "*IFIP Networking*"
url_pdf: "https://doi.org/10.23919/IFIPNetworking.2017.8264836"
doi: "10.23919/IFIPNetworking.2017.8264836"
---

