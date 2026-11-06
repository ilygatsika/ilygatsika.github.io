+++
title = "Research"
+++

This is an overview of my current and recent work organised by topics, that I try to keep up to update.

### Sparse auxiliary basis generation for the density fitting problem: a nonlinear optimization approach

The density fitting problem in computational quantum chemistry concerns the reconstruction of a given electron density function obtained by solving the Kohn-Sham equations discretized on atomic Gaussian-type orbitals. The aim of the reconstruction is to represent the original density in an auxiliary basis set of low complexity. However, performing such a reconstruction is a two-fold task: both the auxiliary coefficients and the auxiliary basis set have to be determined. A main difficulty is to adapt both auxiliary objects to a prescribed reconstruction error. In this work, we formulate a model optimization problem that allows to generate auxiliary basis sets with optimal sparsity on the coefficients, while imposing constraints on the Coulomb-norm reconstruction error and the electron charge. We propose numerical methods for solving this problem focusing on the nonlinear model class of the auxiliary basis having the orbital exponents as parameters. This is ongoing joint work with Damiano Lombardi during my post-doc at Inria.

### Hardware-accelerated parallel eigensolvers for ab initio calculations of materials

The computation of the electronic structure of materials from first principles in condensed matter physics requires solving the Kohn-Sham equations discretized on a plane-wave basis. This problem consists in finding only a few eigenpairs of a large Hermitian matrix. In this work, we use matrix-free eigensolvers for solving such problems. We focus on the spectrum slicing subspace iteration, an algorithm recently implemented in the open-source software package Abinit. Our contribution is a new eigensolver implemented on hardware-accelerated architectures designed to be best suited for systems with a large number of electronic bands, for which existing eigensolvers reach their limitations in terms of memory and performance. This is joint work with Marc Torrent and Clémentine Barat carried out during my post-doc at CEA.



