---
title: "Concentration Tail-Bound Analysis of Coevolutionary and Bandit Learning Algorithms"
collection: IJCAI '24
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about a mathematically rigorous method to analyze co-evolutionary algorithms, successfully obtaining Maximin-solutions with improved runtime analysis and new mathematical tools.'
date: 2024-04-22
venue: 'Proceedings of the 33rd International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'https://www.ijcai.org/proceedings/2024/0767.pdf'
citation: 'Per Kristian Lehre, and Shishen Lin.  (2024). &quot;Concentration Tail-Bound Analysis of Coevolutionary and Bandit Learning Algorithms.&quot; <i>Proceedings of the 33rd International Joint Conference on Artificial Intelligence (IJCAI)</i>.
7 pages, Jeju, South Korea, 2024.'

# <!-- This paper is about the number 1. The number 2 is left for future work. -->

# <!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->
---

Abstract: 
Runtime analysis, as a branch of the theory of AI, studies how the number of iterations algorithms take before finding a solution (its runtime) depends on the design of the algorithm and the problem structure. Drift analysis is a state-of-the-art tool for estimating the runtime of randomised algorithms, such as bandit and evolutionary algorithms. Drift refers roughly to the expected progress towards the optimum per iteration. This paper considers the problem of deriving concentration tail-bounds on the runtime of algorithms. It provides a novel drift theorem that gives precise exponential tail-bounds given positive, weak, zero and even negative drift. Previously, such exponential tail bounds were missing in the case of weak, zero, or negative drift.

Our drift theorem can be used to prove a strong concentration of the runtime/regret of algorithms in AI. For example, we prove that the regret of the RWAB bandit algorithm is highly concentrated, while previous analyses only considered the expected regret. This means that the algorithm obtains the optimum within a given time frame with high probability, i.e. a form of algorithm reliability.

Moreover, our theorem implies that the time needed by the co-evolutionary algorithm RLS-PD to obtain a Nash equilibrium in a Bilinear max-min-benchmark problem is highly concentrated. However, we also prove that the algorithm forgets the Nash equilibrium, and the time until this occurs is highly concentrated. This highlights a weakness in the RLS-PD which should be addressed by future work.