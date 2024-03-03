---
title: A Safe and Fast Repulsion Method for GPU-based Cloth Self Collisions
authors:
- Longhua Wu
- Botao Wu
- Yin Yang
- Huamin Wang
date: '2020-12-01'
publishDate: '2024-03-03T02:42:27.035025Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/3430025
abstract: 'Cloth dynamics and collision handling are the two most challenging topics
  in cloth simulation. While researchers have substantially improved the performances
  of cloth dynamics solvers recently, their success in fast collision detection and
  handling is rather limited. In this article, we focus our research on the safety,
  efficiency, and realism of the repulsion-based collision handling approach, which
  has demonstrated its potential in existing GPU-based simulators. Our first discovery
  is the necessary vertex distance conditions for cloth to enter self intersections,
  the negations of which can be viewed as vertex distance constraints continuous in
  time for sufficiently avoiding self collisions. Continuous constraints, however,
  cannot be enforced with ease. Our solution is to convert continuous constraints
  into three types of constraints: discrete edge length constraints, discrete vertex
  distance constraints, and vertex displacement constraints. Based on this solution,
  we develop a fast and safe collision handling process for enforcing constraints,
  a novel splitting method for integrating collision handling with dynamics solvers,
  and static and adaptive remeshing schemes to further improve the runtime performance.
  In summary, our cloth simulator is efficient, safe, robust, and parallelizable on
  a GPU. The experiment shows that it runs at least one order of magnitude faster
  than existing simulators.'
tags:
- GPU acceleration
- Vertex repulsion
- cloth simulation
- collision detection and handling
- the splitting method
links:
- name: URL
  url: https://doi.org/10.1145/3430025
---