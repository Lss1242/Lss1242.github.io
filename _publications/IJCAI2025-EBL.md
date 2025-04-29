---
title: " Randomised Optimism via Competitive Co-Evolution for Matrix Games with Bandit Feedback"
collection: IJCAI '25
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about a mathematically rigorous method to analyze co-evolutionary algorithms, successfully obtaining Maximin-solutions with improved runtime analysis and new mathematical tools.'
date: 2025-04-29
venue: 'Proceedings of the 34rd International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'https://www.ijcai.org/proceedings/2024/0767.pdf'
citation: 'Per Kristian Lehre, and Shishen Lin.  (2024). &quot;Concentration Tail-Bound Analysis of Coevolutionary and Bandit Learning Algorithms.&quot; <i>Proceedings of the 34rd International Joint Conference on Artificial Intelligence (IJCAI)</i>.
7 pages, Montreal, Canada, 2025. to appear.'

# <!-- This paper is about the number 1. The number 2 is left for future work. -->

# <!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->
---

Abstract: 
Learning in games is a fundamental problem in machine learning and artificial intelligence, with numerous applications (Silver et al., 2016; Schrittwieser et al., 2020). This work focuses on learning in two-player zero-sum matrix games with an unknown payoff matrix and bandit feedback, where players observe their actions and corresponding noisy payoffs. Previous studies have proposed algorithms for this setting (O’Donoghue et al., 2021; Maiti et al., 2023; Cai et al., 2023), with O’Donoghue et al. (2021) highlighting the effectiveness of deterministic optimism (e.g., UCB) in achieving sublinear regret. However, the potential of randomised optimism in matrix games remains theoretically unexplored.

We introduce Competitive Co-evolutionary Bandit Learning (COEBL), a novel algorithm that incorporates evolutionary algorithms (EAs) into the bandit framework to implement randomised optimism through the variation operator of EAs. We prove that COEBL achieves sublinear regret, matching the performance of deterministic optimism-based approaches. To the best of our knowledge, this is the first regret analysis of an evolutionary bandit learning algorithm in matrix games.

Empirical evaluations on various matrix game benchmarks demonstrate that COEBL not only achieves sublinear regret but also outperforms classical bandit algorithms, including EXP3 (Auer et al., 2002), EXP3-IX (Cai et al., 2023), and UCB (O’Donoghue et al., 2021). These findings highlight the potential of evolutionary bandit learning, particularly the effectiveness of randomised optimism via evolutionary algorithms, in game-theoretic settings.