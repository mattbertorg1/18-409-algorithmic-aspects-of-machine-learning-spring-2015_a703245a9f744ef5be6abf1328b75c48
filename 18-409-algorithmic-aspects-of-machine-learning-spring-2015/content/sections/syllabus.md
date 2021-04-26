---
course_id: 18-409-algorithmic-aspects-of-machine-learning-spring-2015
layout: course_section
menu:
  leftnav:
    identifier: b720cccac7223beb0eabc7efa1b4d3aa
    name: Syllabus
    weight: 10
title: Syllabus
type: course
uid: b720cccac7223beb0eabc7efa1b4d3aa

---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Prerequisites
-------------

[_6.046J / 18.410J Design and Analysis of Algorithms_](/courses/6-046j-design-and-analysis-of-algorithms-spring-2012/) or equivalent and [_6.041SC Probabilistic Systems Analysis and Applied Probability_](/courses/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013/) or [_18.440 Probability and Random Variables_](/courses/18-440-probability-and-random-variables-spring-2014/) or equivalent. You will need a strong background in algorithms, probability and linear algebra.

Description
-----------

Modern machine learning systems are often built on top of algorithms that do not have provable guarantees, and it is the subject of debate when and why they work. In this class, we will focus on designing algorithms whose performance we can rigorously analyze for fundamental machine learning problems. We will cover topics such as: Nonnegative matrix factorization, tensor decomposition, sparse coding, learning mixture models, matrix completion and inference in graphical models. Almost all of these problems are computationally hard in the worst-case and so developing an algorithmic theory is about (1) choosing the right models in which to study these problems and (2) developing the appropriate mathematical tools (often from probability, geometry or algebra) in order to rigorously analyze existing heuristics, or to design fundamentally new algorithms.

Textbook
--------

There is no textbook for this course. Instead, [lecture notes]({{< baseurl >}}/sections/lecture-notes) and [readings]({{< baseurl >}}/sections/readings) are provided.

Course Outline
--------------

*   Nonnegative Matrix Factorization
    *   Qualitative Comparisons to SVD
    *   New Algorithms via Separability
    *   Applications to Topic Models

*   Tensor Decompositions
    *   Tensor Rank, Border Rank and the Rotation Problem
    *   Jennrich's Algorithm and the Generalized Eigenvalue Problem
    *   Learning HMMs
    *   Mixed Membership Models and Community Detection
    *   Cumulants and Independent Component Analysis

*   Sparse Coding
    *   Sparse Recovery, Incoherence and Uncertainty Principles
    *   Alternating Minimization via Approximate Gradient Descent
    *   Sum-of-Squares and Noisy Tensor Decomposition

*   Learning Mixture Models
    *   Expectation Maximization
    *   Clustering in High-dimensions
    *   Method of Moments and Systems of Polynomial Equations

*   Linear Inverse Problems
    *   Nuclear Norm, Atomic Norm and Matrix Completion
    *   Alternating Minimization via Principal Angles
    *   Tensor Prediction and Random CSPs

Assessment
----------

Students will be expected to solve 2 problem sets, and complete a research-oriented final project. This could be either a survey, or original research; students will be encouraged to find connections between the course material and their own research interests.