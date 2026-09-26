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

- **Edmonds**, following Galil, Micali, and Gabow's organization of the weighted blossom search
- **Gabow**, using Gabow's data structures for weighted matching
- **Scaling**, based on the Hybrid scaling algorithm of Duan, Pettie, and Su for maximum weighted *perfect* matching

We ask whether Gabow's theoretical data-structure improvements over Edmonds lead to practical gains in runtime, memory, or completion, and how graph order, density, weight range, and graph structure affect all three algorithms. Every run is checked for optimality against independent LEMON reference solutions.
