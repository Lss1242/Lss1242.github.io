---
title: "How does Problem Separability Impact the Co-operative Co-evolutionary (1+1) EA? "
collection: talks
type: "Talk"
permalink: /talks/2022-12-01_ThrashTalk
venue: "University of Birmingham, UK"
date: 2022-12-01
location: "Online"
---

[More information here](https://thrash-seminars.github.io/)

Real-world optimisation problems are increasingly large-scale optimisation (LSO) problems. To solve an LSO more efficiently using evolutionary methods, and cooperative coevolution in which more than two populations get involved and combine the idea of divide and conquer has been introduced.

However, the behaviour of cooperative coevolutionary algorithms is not fully understood because of the interactions between two or more populations, making analysis more challenging. Runtime analysis has improved the understanding of traditional EAs. We argue that such a study of co-evolutionary algorithms could provide useful insights, e.g., how their expected optimisation time depends on algorithmic design decisions.

Here, we continue the development of runtime analysis of co-evolutionary algorithms. By solving an open conjecture proposed by Jansen and Wiegand, we show that the expected optimisation time of the basic cooperative co-evolutionary (1+1) EA (CC-(1+1) EA) on linear functions is Θ(nlogn)
. We also show how the algorithm behaves on an even broader class of functions. Moreover, empirical analysis is conducted on two more complicated problems: NK-Landscape and k-Maxsat problems. Our results show that the CC-(1+1) EA perform similarly to the (1+1) EA in general, however, by adjusting block length, we can still optimise its performance of it on NK-Landscape problem. We expect that our result can provide a more precise expected runtime of CC-(1+1) EA and its behaviour of it on more complicated inseparable problems.


