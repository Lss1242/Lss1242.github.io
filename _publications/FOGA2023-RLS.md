---
title: "Runtime
Analysis of a Co-Evolutionary Algorithm: Overcoming Negative Drift in
Maximin-Optimisation"
collection: FOGA '23
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about a mathematically rigorous method to analyze co-evolutionary algorithms, successfully obtaining Maximin-solutions with improved runtime analysis and new mathematical tools.'
date: 2023-08-31
venue: 'Proceedings of the 16th ACM/SIGEVO Conference on Foundations of Genetic Algorithms (FOGA)'
conference_short: FOGA'2023
year: 2023
paperurl: 'https://dl.acm.org/doi/10.1145/3594805.3607132'
citation: 'Mario Alejandro Hevia Fajardo, Per Kristian Lehre, and Shishen Lin.  (2023). &quot;Runtime analysis of a Co-Evolutionary Algorithm: Overcoming Negative Drift in
Maximin-Optimisation.&quot; <i>Proceedings of the 16th ACM/SIGEVO Conference on Foundations of Genetic Algorithms (FOGA)</i>. 11 pages, Potsdam, Germany, 2023.'

# <!-- This paper is about the number 1. The number 2 is left for future work. -->

# <!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->
---

Abstract: Co-evolutionary algorithms have found several applications in game-theoretic applications and optimisation problems with an adversary, particularly where the strategy space is discrete and exponentially large, and where classical game-theoretic methods fail. However, the application of co-evolutionary algorithms is difficult because they often display pathological behaviour, such as cyclic behaviour and evolutionary forgetting. These challenges have prevented the broad application of co-evolutionary algorithms.

We derive, via rigorous mathematical methods, bounds on the expected time of a simple co-evolutionary algorithm until it discovers a Maximin-solution on the pseudo-Boolean Bilinear problem. Despite the intransitive nature of the problem leading to a cyclic behaviour of the algorithm, we prove that the algorithm obtains the Maximin-solution in expected O(n1.5) time.

However, we also show that the algorithm quickly forgets the Maximin-solution and moves away from it. These results in a large total regret of Θ(Tn1.5) after T iterations. Finally, we show that using a simple archive solves this problem reducing the total regret significantly.

Along the way, we present new mathematical tools to compute the expected time for co-evolutionary algorithms to obtain a Maximin-solution. We are confident that these tools can help further advance runtime analysis in both co-evolutionary and evolutionary algorithms.