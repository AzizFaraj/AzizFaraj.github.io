---
title: "TODO: Title of the Weighted Matching Paper"
collection: publications
category: preprints
permalink: /publication/weighted-matching
date: 2026-09-20
authors: '<b>Abdulaziz Alfaraj</b>, Ahmed Al-Herz'
status: 'Manuscript, arXiv preprint coming soon'
excerpt: 'Implementations and an experimental study of exact algorithms for maximum weighted matching in general graphs.'
---

Maximum weighted matching in general (non-bipartite) graphs is one of the classical problems of combinatorial optimization. Several exact algorithms with strong theoretical guarantees exist, but their practical behavior is much less understood.

In this project, advised by Dr. Ahmed Al-Herz at KFUPM, I implemented three exact algorithms in C++:

- **Edmonds' algorithm**, following Galil, Micali, and Gabow's O(EV log V) implementation
- **Gabow's algorithm**, based on his data structures for weighted matching
- **A scaling algorithm** for maximum weighted *perfect* matching (the "Hybrid" algorithm of Duan, Pettie, and Su)

I validated them against the LEMON graph library and evaluated them experimentally across graph families, sizes, densities, and edge-weight distributions.
