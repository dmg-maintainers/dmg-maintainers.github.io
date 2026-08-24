---
title: Overcoming Tight Constraints in Soft Happy Colouring
authors:
- Mohammad Hadi Shekarriz
- Asef Nazari
- Dhananjay-Thiruvady
date: '2026-01-01'
publishDate: '2026-08-17T02:00:37.674721+00:00'
publication_types:
- manuscript
doi: https://doi.org/10.1016/j.ins.2026.123951
abstract: "Summary: The Soft Happy Colouring (SHC) problem, a mathematical framework
  for identifying homophilic network structures, seeks to maximise the number of $ρ$-happy
  vertices, i.e., vertices with at least a proportion $ρ$ of neighbours that share
  the same colour. Because this NP-hard problem makes finding exact solutions intractable
  for large networks, probabilistic metaheuristics such as the Cross-Entropy (CE)
  method are suitable candidates. However, pure CE frequently suffers from stagnation
  of the probability distributions and non-convergence in high-dimensional spaces.
  To address this, we introduce {\\sf CE+LS}, synergising CE's adaptive learning with
  a fast, structure-aware local search ({\\sf LS}). By restricting the search exclusively
  to local optima, {\\sf CE+LS} learns from high-quality structural characteristics
  rather than raw random samples. We mathematically and empirically demonstrate that
  this search space reduction resolves CE's stagnation, yielding a convergent algorithm.
  Evaluating {\\sf CE+LS} across 28,000 Stochastic Block Model graphs, validated by
  non-parametric statistical testing, demonstrates that it consistently outperforms
  existing heuristic and memetic algorithms. Furthermore, benchmarking against the
  commercial exact solver, CPLEX, on real-world networks confirms that {\\sf CE+LS}
  identifies near-optimal configurations in a fraction of the required computational
  time for CPLEX. Crucially, {\\sf CE+LS} remains highly efficient even in the tight
  constraint regime, where comparative algorithms usually fail."
zbmath_date: '0001-01-01T00:00:00Z'
links:
- name: zbmath
  url: https://zbmath.org/902980483
  id: 902980483
- name: arxiv
  url: https://arxiv.org/abs/2603.11050
  id: '2603.11050'
---
