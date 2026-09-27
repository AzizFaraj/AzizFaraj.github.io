---
title: "Experimental Evaluation: Maximum Weighted Matching Algorithms"
collection: publications
category: preprints
permalink: /publication/weighted-matching
date: 2026-09-20
authors: '<b>Abdulaziz Alfaraj</b>, Ahmed Al-Herz'
status: 'Manuscript, arXiv preprint coming soon'
excerpt: 'Do theoretical data-structure improvements for weighted matching pay off in practice? An experimental comparison of Edmonds, Gabow, and scaling algorithms on general weighted graphs.'
---

Maximum weighted matching in general (non-bipartite) graphs is a classical problem in combinatorial optimization. Its exact algorithms differ in their data structures and asymptotic bounds, but how those differences affect practical performance is much less understood.

This paper, advised by Dr. Ahmed Al-Herz at KFUPM, compares three exact implementations that I wrote in C++:

- **Edmonds:** Edmonds' weighted blossom algorithm [1, 2], organized along the lines of Galil, Micali, and Gabow's O(EV log V) algorithm [3]
- **Gabow:** the same search, using Gabow's data structures for weighted matching [4, 5]
- **Scaling:** the Hybrid scaling algorithm of Duan, Pettie, and Su for maximum weighted *perfect* matching [6]

We ask whether Gabow's theoretical data-structure improvements over Edmonds lead to practical gains in runtime, memory, or completion, and how graph order, density, weight range, and graph structure affect all three algorithms. Every run is checked for optimality against independent LEMON reference solutions.

## References

1. J. Edmonds. [Maximum matching and a polyhedron with 0,1-vertices](https://doi.org/10.6028/jres.069B.013). *Journal of Research of the National Bureau of Standards, Section B*, 69B:125–130, 1965.
2. J. Edmonds. [Paths, trees, and flowers](https://doi.org/10.4153/CJM-1965-045-4). *Canadian Journal of Mathematics*, 17:449–467, 1965.
3. Z. Galil, S. Micali, and H. N. Gabow. [An O(EV log V) algorithm for finding a maximal weighted matching in general graphs](https://doi.org/10.1137/0215009). *SIAM Journal on Computing*, 15(1):120–130, 1986.
4. H. N. Gabow. Data structures for weighted matching and nearest common ancestors with linking. In *Proceedings of the 1st Annual ACM-SIAM Symposium on Discrete Algorithms (SODA)*, pages 434–443, 1990.
5. H. N. Gabow. [Data structures for weighted matching and extensions to b-matching and f-factors](https://doi.org/10.1145/3183369). *ACM Transactions on Algorithms*, 14(3):39:1–39:80, 2018.
6. R. Duan, S. Pettie, and H.-H. Su. [Scaling algorithms for weighted matching in general graphs](https://doi.org/10.1145/3155301). *ACM Transactions on Algorithms*, 14(1):8:1–8:35, 2018.
