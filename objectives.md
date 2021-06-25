---
title: "Objectives"
layout: post
---
The three archetypal factorizations of SVD, NMF  and $$k$$-means have all very popular standard methods to derive their solutions. 
For SVD these are established numerical methods (as provided by the standard libraries ARPACK and LAPLACK); 
for NMF these are multiplicative updates which preserve the nonnegativity of the factor matrices by multiplying with nonnegative constants; 
and for $$k$$-means this is the alternating minimization known as Lloyd's algorithm. In vanilla situations, these methods work reasonably well. 
However, what if the data characteristics require other solutions or the task specifics demand the integration of additional constraints?

In this tutorial, we discuss three solutions to the most pressing drawbacks of established methods. 
With regard to SVD, we put emphasis to large-scale problems and their solutions. In particular, data characteristics such as sparsity are of relevance 
here, which can lead to accurate and fast solutions. With regard to NMF, we discuss projected/proximal gradient descent as an alternative to 
multiplicative updates. Multiplicative updates can be seen as gradient descent, where the step size is chosen small enough such that the nonnegativity 
constraint is never violated. However, this conservative step size results in a very slow convergence rate. In contrast, proximal methods facilitate 
the optimization of non-continuous and nonconvex objectives with fast convergence properties.

Finally, with regard to clustering, we discuss optimization methods which enable the representation of overlapping clusters and outliers in the data. 
Allowing such general clustering structures is computationally not feasible with Lloyd's alternating minimization. 
In the past, relaxations of the binary constraints have been proposed, such that numerical optimizations, known from related factorizations such as 
NMF, could be applied. Correspondingly, the resulting factor matrices are not  binary anymore: they indicate fuzzy clusters, and in order to convert 
those to crisp cluster memberships, post-processing steps are required. Once again, proximal methods enable an efficient combination of the numerical 
optimization of relaxed objectives which converge to binary results.

Typical applications of the discussed methods include clustering, gene expression analysis, collaborative filtering, and network structure learning. 
Furthermore, the reviewed optimization methods have possible implications to other, indirectly related areas, where combinatorial optimization or the 
learning of binary structures (e.g., edges in a graph) are of importance.
