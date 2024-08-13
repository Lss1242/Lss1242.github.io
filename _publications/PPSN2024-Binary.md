---
title: "Overcoming Binary Adversarial Optimisation with Competitive Coevolution"
collection: PPSN '24
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about a mathematically rigorous method to analyze co-evolutionary algorithms, successfully obtaining Maximin-solutions with improved runtime analysis and new mathematical tools.'
date: 2024-05-31
venue: '18th International Conference on Parallel Problem Solving From Nature (PPSN)'
# paperurl: 'https://arxiv.org/pdf/2407.17875'
citation: 'Per Kristian Lehre, and Shishen Lin.  (2024). &quot; Overcoming Binary Adversarial Optimisation with Competitive Coevolution.&quot; <i>18th International Conference on Parallel Problem Solving From Nature (PPSN)</i>.
14 pages, Hagenberg, Austria, 2024. to appear.'

# <!-- This paper is about the number 1. The number 2 is left for future work. -->

<!-- [Full paper here](https://arxiv.org/pdf/2407.17875) -->
---

Abstract: 
Co-evolutionary algorithms (CoEAs), which pair candidate designs with test cases, are frequently used in adversarial optimisation, particularly for binary test-based problems where designs and tests yield binary outcomes. The effectiveness of designs is determined by their performance against tests, and the value of tests is based on their ability to identify failing designs, often leading to more sophisticated tests and improved designs. However, CoEAs can exhibit complex, sometimes pathological behaviours like disengagement. 
Through runtime analysis, we aim to rigorously analyse whether CoEAs can efficiently solve test-based adversarial optimisation problems in an expected polynomial runtime.

This paper carries out the first rigorous runtime analysis of $(1,\lambda)$ CoEA for binary test-based adversarial optimisation problems. 
In particular, we introduce a binary test-based benchmark problem called Diagonal problem and initiate the first runtime analysis of competitive CoEA on this problem. The mathematical analysis shows that the $(1,\lambda)$-CoEA can efficiently find an $\varepsilon$ approximation to the optimal solution of the Diagonal problem, i.e. in expected polynomial runtime assuming sufficiently low mutation rates and large offspring population size. On the other hand, the standard $(1,\lambda)$-EA fails to find an $\varepsilon$ approximation to the optimal solution of the Diagonal problem in polynomial runtime. This suggests the promising potential of coevolution for solving binary adversarial optimisation problems.