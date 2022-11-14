---
title: "Off the Wire Control: Improving the Control Plane Resilience through Cellular Networks"
date: 2015-02-01
publishDate: 2019-12-10T00:03:23.689328Z
authors: ["Tobias Petry", "Rafael da Silva", "Marinho Barcellos"]
publication_types: ["1"]
abstract: "Software Defined Networks simplify network pro- grammability by detaching the control plane from forwarding devices and deploying it into a logically centralized controller. While this allows a clearer separation of concerns, it also creates a dependency between them. Failures in the control plane break the controller view of the network state and could render the network unusable if forwarding devices cannot be reached. The relevance of this problem has led to a range of proposals, including physical distribution of controller instances and delegation of concerns to forwarding devices. In this paper, we propose and evaluate an architecture that leverages cellular data networks (4G) as control plane backup links. No previous work has explored this idea, despite the recent research intersecting SDN and wireless networks. Our experiments answer three research questions: (i) How is the behavior of control plane traffic affected by the characteristics of cellular links, (ii) how quickly is the control plane handed over to the backup link when a failure occurs and (iii) how well do network functions that rely on a snapshot of the network state behave on such an architecture. Our evaluation shows that, despite the expected higher latency of cellular links, this architecture maintains partial functionality of tasks that depend on global network awareness when failures occur in primary links in a simple, affordable fashion. I."
featured: false
publication: "*IEEE ICC*"
tags: ["SDN"]
url_pdf: "papers3://publication/uuid/80BF25D3-35AE-45D9-B682-589AA2F842F4"
---

