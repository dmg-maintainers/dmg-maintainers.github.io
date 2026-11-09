---
title: 'Non-Contiguous Channel Allocation in Multi-Beam Satellites: Formulations,
  Upper Bounds and Cooperative Matheuristics'
authors:
- Angus Gaudry
- Vicky-Mak-Hau
date: '2026-01-01'
publishDate: '2026-11-09T06:58:51.288781+00:00'
publication_types:
- manuscript
abstract: 'Summary: Demand for wireless communication is growing, and commercial satellite
  services are expanding with it, increasing pressure on a finite radio spectrum.
  Allocation efficiency directly limits how many users a satellite can serve. We study
  how to assign frequency sub-channels to the carriers of a multi-beam satellite,
  maximising the total priority of admitted carriers while keeping each within its
  interference tolerance. Earlier work on this interference-limited channel allocation
  problem placed each carrier in a single continuous frequency block. Removing this
  restriction can admit more carriers, but a direct integer programming model cannot
  solve the largest test problems in practical time, so new methods are needed. We
  prove the problem computationally hard, reformulate it around how carriers share
  sub-channels, and derive three bounds on the optimum. We develop heuristics, including
  matheuristics combining local search with optimisation models, and an orchestrated
  portfolio that schedules them, recombines their solutions and stops early once its
  result is proven optimal or no longer improves. On 24 problems with up to 500 carriers,
  the best heuristics come within about 1% of the best known solution on average.
  The portfolio matches or exceeds the best heuristic for each problem on 23 of 24
  with equal weights and 22 with priority weights, and is up to about 5% better on
  larger, more congested problems. It requires about a quarter of the time to run
  every heuristic and keep the best, and under half that of its heuristics run in
  a fixed order, which return slightly worse solutions on average.'
zbmath_date: '0001-01-01T00:00:00Z'
links:
- name: zbmath
  url: https://zbmath.org/903210411
  id: 903210411
- name: arxiv
  url: https://arxiv.org/abs/2610.17906
  id: '2610.17906'
---
