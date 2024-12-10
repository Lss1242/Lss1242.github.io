---
title: "No Free Lunch Theorem and Black-Box Complexity Analysis for Adversarial Optimisation"
collection: NeurIPS '24
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about a mathematically rigorous method to analyze co-evolutionary algorithms, successfully obtaining Maximin-solutions with improved runtime analysis and new mathematical tools.'
date: 2024-09-25
venue: 'The Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://openreview.net/pdf?id=NkuySm8qVs'
citation: 'Per Kristian Lehre, and Shishen Lin.  (2024). &quot; No Free Lunch Theorem and Black-Box Complexity Analysis for Adversarial Optimisation.&quot; <i>38th Annual Conference on Neural Information Processing Systems (NeurIPS)</i>.
9 pages, Vancouver, Canada, 2024.'

# <!-- This paper is about the number 1. The number 2 is left for future work. -->

# <!-- [Full paper here](https://arxiv.org/pdf/2407.17875) -->
---

Abstract: 
Black-box optimisation is one of the important areas in optimisation. The original No Free Lunch (NFL) Theorems highlight the limitations of traditional black-box optimisation and learning algorithms, serving as a theoretical foundation for traditional optimisation. No Free Lunch Analysis in adversarial (also called \maximin) optimisation is a long-standing problem \cite{wolpert1997no,wolpert_coevolutionary_2005}. This paper first rigorously proves a (NFL) theorem for general black-box adversarial optimisation when considering Nash Equilibrium (NE) as the solution concept. We emphasise the solution concept (i.e. define the optimality in adversarial optimisation) as the key in our NFL theorem. In particular, if Nash Equilibrium is considered as the solution concept, then the average performance of all black-box adversarial optimisation algorithms is the same. Moreover, we first introduce black-box complexity to analyse the black-box adversarial optimisation algorithm. We employ Yao's maximin principle and our new NFL Theorem to provide general lower bounds for query complexity of finding Nash Equilibrium in adversarial optimisation. Finally, we illustrate the practical ramifications of our results on simple two-player zero-sum games. More specifically, no black-box optimisation algorithm for finding the unique Nash equilibrium in two-player zero-sum games can exceed the logarithmic complexity relative to search space size. Meanwhile, no black-box algorithm can solve any bimatrix game with unique NE faster than the linear query complexity in terms of the size of input payoff matrices.