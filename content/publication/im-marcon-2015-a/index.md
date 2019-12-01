---
title: "Predictor: Providing fine-grained management and predictability in multi-tenant datacenter networks"
date: 2015-01-01
publishDate: 2019-12-01T08:31:06.091611Z
authors: ["Daniel S Marcon", "Marinho Pilla Barcellos"]
publication_types: ["1"]
abstract: "Software-Defined Networking (SDN) can simplify traffic management in large-scale datacenter networks (DCNs). On one hand, it provides a robust method to address the challenge of performance interference (bandwidth sharing unfairness) in DCNs. On the other, its pragmatic implementation based on OpenFlow introduces scalability challenges, as it (a) adds latency for new flows (the controller must process hundreds of thousands of requests per second and install appropriate rules in switches); and (b) requires large flow tables in devices (DCNs can have more than 16 million distinct flows per second with different requirements and duration). To employ OpenFlow-based SDN in DCNs, recent work has proposed techniques that require hardware customization to keep up with the high dynamic traffic patterns of these networks. We make two key observations: providers do not need to control each flow individually (e.g., VM-to-VM), since they charge tenants based on the amount of resources consumed by applications; and congestion control in the intra-cloud network is expected to be proportional to the tenant's payment. Based on these insights, we introduce Predictor, a novel system for DCNs that enables fine-grained network management for providers, minimizes flow table size by controlling flows at application-layer and reduces flow setup time by proactively installing rules in switches. It also enables tenants to request and receive predictable network performance for both intra- and inter-application communication, with work- conserving bandwidth sharing. Evaluation results show that Predictor provides significant improvements against DevoFlow (reducing flow table size up to 87%) and offers predictable and guaranteed network performance for tenants. I."
featured: false
publication: "*IEEE IM*"
url_pdf: "http://ieeexplore.ieee.org/lpdocs/epic03/wrapper.htm?arnumber=7140278 papers3://publication/doi/10.1109/INM.2015.7140278"
---

