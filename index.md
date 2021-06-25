---
layout: post
title: Matrix Factorizations and Binary Constraints
image: /assets/images/waldemar-brandt--9r5id5dNKs-unsplash.jpg
sub_title: Sibylle Hess and Michiel Hochstenbach @DSAA2021
---
## Abstract
Matrix decompositions are omnipresent in data mining and machine learning. Computing the solutions to fundamental tasks, such as ridge regression, principal component analysis, and image deblurring, may rely for example on a (truncated) Singular Value Decomposition (SVD). Matrix decompositions (or factorizations) are playing a particularly prominent role in the branch of unsupervised learning. They form a generalized framework under which many of the popular clustering objectives can be formalized. Examples are $$k$$-means clustering, spectral clustering or subspace clustering, which are all instances of matrix factorization with binary constraints. Subsequently, to get definite cluster assignments, binary constraints are imposed. A binary factor matrix indicates for every observation the cluster(s) to which it is assigned.    

Computing matrix decompositions, such as SVD and $$k$$-means clusterings, are well-researched and well-known tasks. However, those decompositions are also still the subject of active research, providing solutions to fundamental open problems which have an impact on various data mining subfields. 
In this tutorial, we discuss the broad spectrum of matrix factorizations where the approximation error in terms of the Frobenius norm is minimized. We discuss the similarities and differences between these factorizations by means of the imposed constraints. 
We review existing optimization approaches, generic to objective characteristics. Our focus is thereby on two aspects: on the one hand, conditions and methods which enable large-scale computations of singular value or eigenvalue decompositions, and on the other hand, optimization subject to binary constraints. Our goal is to provide our audience with a rich but clear basis knowledge about the matrix factorization zoo, along with recent advances in (nonconvex) optimization theory which inspire to find novel solutions to longstanding problems.

## Speakers
<p style="float: left; text-align: center; width: 30%; margin-left:10%; margin-bottom: 0.5em;"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/MeEggSquare.png" alt="" style="width: 100%;border-radius:50%">Sibylle Hess</p>
<p style="float: right; text-align: center;  width: 30%; margin-right:10%;margin-bottom: 0.5em;"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/michielSquare.jpg" style="width: 100%;border-radius:50%">Michiel Hochstenbach</p>
<div style="clear: both;"></div>

## Outline
* Singular Value Decomposition (SVD) 
  * Truncated SVD and Principal Components Analysis (PCA)
  * Connections to Eigendecompositions
  * Optimization
    * Numerical methods for small- and large-scale problems

* Nonnegative Matrix Factorization (NMF)
  * Parts-based representation, soft-orthogonality of solutions
  * Optimization 
    * Multiplicative updates
    * Proximal gradient descent
    * Proximal stochastic gradient descent
* Factorizations where one matrix is constrained to binary values
  * (kernel) $$k$$-means
  * Minimum cuts and spectral clustering
  * Optimization 
    * Lloyd's alternating minimization
    * The spectral relaxation: from SVD to clustering
* Factorizations where two matrices are constrained to binary values
  * Biclustering of real-valued data: tri-factorizations and bipartite graph cuts
  * Biclustering of binary data: binary and Boolean matrix factorization
  * Optimization
    * Variants of Lloyd's alternating minimization
    * The (soft)-orthogonal relaxation: from NMF to biclustering
    * The spectral relaxation: from SVD to biclustering
    * Nonbinary penalization: numerical optimization for approximately binary solutions
* Conclusions and Outlook



