---
title: A GPU-Based Multilevel Additive Schwarz Preconditioner for Cloth and Deformable
  Body Simulation
authors:
- Botao Wu
- Zhendong Wang
- Huamin Wang
date: '2022-07-01'
publishDate: '2024-03-03T02:42:27.050540Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/3528223.3530085
abstract: In this paper, we wish to push the limit of real-time cloth and deformable
  body simulation to a higher level with 50K to 500K vertices, based on the development
  of a novel GPU-based multilevel additive Schwarz (MAS) pre-conditioner. Similar
  to other preconditioners under the MAS framework, our preconditioner naturally adopts
  multilevel and domain decomposition concepts. But contrary to previous works, we
  advocate the use of small, non-overlapping domains that can well explore the parallel
  computing power on a GPU. Based on this idea, we investigate and invent a series
  of algorithms for our preconditioner, including multilevel domain construction using
  Morton codes, low-cost matrix precomputation by one-way Gauss-Jordan elimination,
  and conflict-free symmetric-matrix-vector multiplication in runtime preconditioning.
  The experiment shows that our preconditioner is effective, fast, cheap to precompute
  and scalable with respect to stiffness and problem size. It is compatible with many
  linear and nonlinear solvers used in cloth and deformable body simulation with dynamic
  contacts, such as PCG, accelerated gradient descent and L-BFGS. On a GPU, our preconditioner
  speeds up a PCG solver by approximately a factor of four, and its CPU version outperforms
  a number of competitors, including ILU0 and ILUT.
tags:
- preconditioning
- multilevel method
- conjugate gradient
- cloth and deformable body simulation
- additive Schwarz
links:
- name: URL
  url: https://doi.org/10.1145/3528223.3530085
---
