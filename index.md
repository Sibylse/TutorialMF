---
layout: post
title: A Tutorial on Matrix Factorization with Binary Constraints
image: /assets/images/amine-ounnas-180287.jpg
sub_title: Sibylle Hess and Michel Hochstenbach
---

## Abstract
Matrix decompositions are omnipresent in data mining and machine learning. Computing the solutions to fundamental tasks, such as ridge regression, principal component analysis, and image deblurring, may rely for example on a (truncated) Singular Value Decomposition (SVD). Matrix decompositions (or factorizations) are playing a particularly prominent role in the branch of unsupervised learning. They form a generalized framework under which many of the popular clustering objectives can be formalized. Examples are $k$-means clustering, spectral clustering or subspace clustering, which are all instances of matrix factorization with binary constraints. Subsequently, to get definite cluster assignments, binary constraints are imposed. A binary factor matrix indicates for every observation the cluster(s) to which it is assigned.    

Computing matrix decompositions, such as SVD and $k$-means clusterings, are well-researched and well-known tasks. However, those decompositions are also still the subject of active research, providing solutions to fundamental open problems which have an impact on various data mining subfields. 
In this tutorial, we discuss the broad spectrum of matrix factorizations where the approximation error in terms of the Frobenius norm is minimized. We discuss the similarities and differences between these factorizations by means of the imposed constraints. 
We review existing optimization approaches, generic to objective characteristics. Our focus is thereby on two aspects: on the one hand, conditions and methods which enable large-scale computations of singular value or eigenvalue decompositions, and on the other hand, optimization subject to binary constraints. Our goal is to provide our audience with a rich but clear basis knowledge about the matrix factorization zoo, along with recent advances in (nonconvex) optimization theory which inspire to find novel solutions to longstanding problems.
