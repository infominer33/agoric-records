---
title: The Agoric Papers
date: '2018-06-26 01:16:01 +0000'
layout: posts
categories: blog
abstract: This post is a demonstration of indieweb blogging.
author: Infominer
permalink: '/posts/:year/:title/'
---

* [Mark Miller: Agoric and the Decades-Long Quest for Secure Smart Contracts.](https://epicenter.tv/episode/286/) -Epicenter Podcast

* [Eric Drexler](http://metamodern.com/about-the-author/)

## [The Agoric Papers](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers.html)

> These three papers by Mark S. Miller and K. Eric Drexler appeared in The Ecology of Computation, Bernardo Huberman (ed.) Elsevier Science Publishers/North-Holland, 1988. 

### Markets and Computation: Agoric Open Systems

> Like all systems involving goals, resources, and actions, computation can be viewed in economic terms. This paper examines markets as a model for computation and proposes a framework--agoric systems--for applying the power of market mechanisms to the software domain. It then explores the consequences of this model and outlines initial market strategies.

* [Agorics Open Systems Abstract](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.0.html) (5k)

* Mark S. Miller -Xerox Palo Alto Research Center,
* K. Eric Drexler - MIT Artificial Intelligence Laboratory,

>Like all systems involving goals, resources, and actions, computation can be viewed in economic terms. Computer science has moved from centralized toward increasingly decentralized models of control and action; use of market mechanisms would be a natural extension of this development. The ability of trade and price mechanisms to combine local decisions by diverse parties into globally effective behavior suggests their value for organizing computation in large systems.

>This paper examines markets as a model for computation and proposes a framework-agoric systems-for applying the power of market mechanisms to the software domain. It then explores the consequences of this model at a variety of levels. Initial market strategies are outlined which, if used by objects locally, lead to distributed resource allocation algorithms that encourage adaptive modification based on local knowledge. If used as the basis for large, distributed systems, open to the human market, agoric systems can serve as a software publishing and distribution marketplace providing strong incentives for the development of reusable software components. It is argued that such a system should give rise to increasingly intelligent behavior as an emergent property of interactions among software entities and people.


* [Introduction](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.1.html) (9k)

> This line of investigation leads us to propose what may be called the agoric approach to software systems. Agoric stems from agora, the Greek term for a meeting and market place. An agoric system is defined as a software system using market mechanisms, based on foundations that provide for the encapsulation and communication of information, access, and resources among objects. Each of these notions plays a role in supporting computational markets.

* [Overview of later sections](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.2.html) (5k)

* **Section 3: Computation and economic order.** - Basic characteristics of human markets illuminate the expected nature of computational markets. This section describes some of these characteristics and sketches some of the special issues raised in the context of computation.
* **Section 4: Foundations.** The foundations needed for agoric open systems may be summarized as support for the encapsulation and communication of information, access, and resources. This section describes these foundations and their role in computational markets.
* **Section 5:** Agents and strategies. The foundations of computational markets handle neither resource management (such as processor scheduling and garbage collection) nor market transactions. This section describes the idea of business agents and their use both in replacing centralized resource-allocation algorithms (discussed further by [III]) and in managing complex market behavior.
* **Section 6:** Agoric systems in the large. Large, evolved agoric systems are expected to have valuable emergent properties. This section describes how they can provide a more productive software market in human society-opening major new business opportunities-and how they can further the goal of artificial intelligence.
* **Section 7:** The absence of agoric systems. If market-based computation is a good idea, why has it not yet been developed? This section attempts to show why the current absence of agoric systems is consistent with their being a good idea.
* **Appendix I:** Issues, levels, and scale. Agoric open systems will be large and complex, spanning many levels of scale and complexity. This section surveys how issues such as security, reasoning, and trust manifest themselves at different levels of agoric systems.
* **Appendix II:** Comparison with other systems. Here are reviewed works ranging from those that draw analogies between human society and computational systems to those that explore adaptive computation from an economic point of view.

* [Computation and economic order](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.3.html) (26k)

>The objects participating in computational markets must initially be much simpler than the human participants in human markets. Can they participate successfully? Human markets are based on intelligent systems, but this does not show the impossibility of basing markets on simple objects-it merely shows that the argument for agoric systems cannot rest on analogy alone. Explicit attention must be paid to the question of the minimal competence and complexity necessary for an object to participate in a market system. (These issues provide another motivation to form computational "firms" and to open computational markets to human participation.)

* [Foundations](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.4.html) (23k)

>Computational foundations are frequently expressed in the form of programming language or operating system designs. Programming languages have evolved chiefly to provide abstractions for organizing computation on a small scale-the computation occurring inside a single machine and serving a single user. This has unfortunately led many programming lan- guage designers to make decisions (such as providing for global variables or access to arbitrary memory addresses) that make these languages unsuitable for organizing computation on a very large scale. The Actor languages, Argus, the concurrent logic programming languages (such as FCP), and the Mach operating system are examples of systems which have been designed to be extensible to large, open systems. These are covered in this book respectively in [II], [III], [IV], [V], and [VI]. All these projects have arrived at broadly similar models of computation from different directions, suggesting that their common elements will be of general value. This section briefly outlines some of the properties they share-properties which seem important for the implemention of computational markets.

* [Agents and strategies](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.5.html) (33k)

>Current resource allocation policies leave much to be desired. One sign of this is that most computing resources-including CPUs, disk heads, local area networks, and much more-sit idle most of the time. But such resources have obvious uses, including improving their own efficiency during later use. For example, heavily-used programs can be recompiled through optimizing compilers or partial evaluators; pages on disk can be rearranged to keep files contiguous; objects can be rearranged according to referencing structure to minimize paging [47], and so forth. In a computational market, a set of unused resources would typically have a zero or near-zero price of use, reflecting only the cost of whatever power consumption or maintenance could be saved by genuine idleness or complete shutdown. Almost any use, however trivial, would then be profitable. In practice, contention for use would bid up prices until they reflected the marginal value of use [5]. Idle time is a blatant sign of wasteful resource allocation policies; one suspects that it is just the tip of a very large iceberg.

* [Agoric systems in the large](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.6.html) (26k)

>Agoric systems will naturally support a charge-per-use market for software. In any market, software producers will attempt to extract substantial charges from high-volume users. With charge per use, however, the charges to be paid by high-volume users will no longer stand in the way of low-volume users; as a result, they will use expensive software that they could not afford today. At the same time, high-volume users will experience a finite marginal price for using software, rather than buying it and paying a zero marginal price for using it; they will cut back on some of their marginal, low-value uses. The overall benefit of numerous low-volume users making high-value use of the software will likely outweigh the loss associated with a few high-volume users cutting back on their low-value uses, yielding a net social benefit. It seems likely that some of this benefit will appear as increased revenues to software producers, encouraging increased software production.

* [The absence of agoric systems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.7.html) (6k)

>Why have agoric open systems not been implemented already? In part, because the software community has lacked an immediate, compelling need. Advances have been made, through better programming environments and methodologies (including the encapsulation and communication of information and access), and through tools for making larger structures visible to programmers [64]-all without building markets. These environments and method- ologies have extended the programmer's conceptual span of control, enabling one mind or a few closely-coordinated, mutually-trusting minds to build ever larger and more complex programs. These advances have decreased the urgency of enabling extensive cooperation without mutual trust or extensive communications.

* [Conclusions](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.8.html) (5k)

>This paper has examined many of the concrete issues involved in actually creating computational markets, from hardware and software foundations, to initial market strategies for resource management (chiefly in [III]), to the organization of systems of objects and agents able to interact in a market context. As yet, no obstacle to their realization has been found.

>Distributed systems based on the charge-per-use sale of software services and computational resources promise a more flexible and effective software market, in which large systems will more often be built from pre-existing parts. With many minds building knowledge and competence into market objects, and with incentives favoring cooperation among these objects, the overall problem-solving ability of the system can be expected to grow rapidly.

>On a small scale, central planning makes sense; on a larger scale, market mechanisms make sense. Computer science began in a domain where central planning made sense, and central planning has thus been traditional. It seems likely, however, that some modern computer systems are already large and diverse enough to benefit from decentralized market coordination. As systems grow in scale and complexity, so will the advantages of market-based computational systems.

* [Agorics Open Systems Appendix I](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.9.html) (17k)
* [Appendix II. Comparison with other systems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.10.html) (24k)
* [References](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.11.html) (41k)
