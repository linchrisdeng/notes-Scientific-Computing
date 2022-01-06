---
title: 
description: Homepage for Lin's Scientific Computing & Numerical Analysis
---

# Overview 
!!! tip "Summary" 
    ** The entire core of Scientific Computing & Numerical Analysis (SCNA) can be said to be the study of how to make computers compute systems of linear/non-linear equations ** 

Welcome to SCNA. This is a website for Lin Deng to store the notes and application of scientific computation methods during his PhD journey. The repo launched from Dec 2021 when Lin finished his first-year confirmation meeting at the U of Melbourne (Melbourne Business School). Aimed at consolidating the understanding of scientific computation techniques and rebuild the notion of coordinate changing in the computational research work, the notes contain 3 aspects to illustrate SCNA in Finance, Econ. Part 1: Algebra with Matrix, Linear System and Factor Analysis, Part 2: Numeric Optimization, Part 3: Nonlinear/Dynamic System - Differential Equations. 

The material is mainly referenced to the book DDMSC[^1] and Project LAFF[^2]. Contents are split into the following sections:

!!! note inline end 
    The content will be constantly updated and adjusted over time. 
    
    √ sign labels complete sections. 

    ** <p> Last Update: <span id="datetime"> </span></p>
    <script>
    var dt = new Date();
    document.getElementById("datetime").innerHTML = dt.toLocaleDateString();
    </script> **



!!! check "TOC" 
    - [ ] ** [Part 1: Basics](Section_1/index.md) ** 
        - [ ] [Algebra with Matrix](Section_1/algebra_with_matrix.md)
            - [x] 1.1 Vector and Matrix
            - [ ] 1.2 Matrix Inverse
        - [ ] Linear System
            - [ ] 2.1 Matrix Decomposition
            - [ ] 2.2 Eigenvalues and Eigenvector
        - [ ] Simple Latent State Model
            - [ ] 3.1 Factor Analysis (FA)
            - [ ] 3.2 State Space Model (SSM)
    - [ ] ** Part 2: Numerical Optimization **
        - [ ] Gradient-Based Optimization
            - [ ] Gradients of vector and matrix
        - [ ] Gradient-Free Optimization
    - [ ] ** Part 3: Differential Equations **


<!-- https://tree.nathanfriend.io/ -->
<!-- ```
.
├── Home
├── Part1: Basics
│   ├── Algebra with Matrix 
│   │   ├── 1.1 Vector and Matrix 
│   │   └── 1.2 Inversion of a Matrix
│   ├── Linear System
│   │   ├── 2.1 Matrix Decomposition
│   │   └── 2.2 Eigenvalues and Eigenvector
│   └── Simple Latent State Model
│       ├── 3.1 Factor Analysis (FA)
│       └── 3.2 State Space Model (SSM)
├── Part 2: Numeric Optimization
│   ├── Gradient and Hessian
│   │   └── 4.1. Gradients of vector and matrix
│   └── First-Order Newton's Method
└── Part 3: Differential Equations
``` -->

!!! note inline end
    Python and Matlab code will be supplied if I have time
=== "Python"

    ``` py
    # requirements
    matplotlib == 3.1.1
    numpy == 1.19.4
    pandas == 0.25.1
    scikit_learn == 0.21.3
    torch == 1.8.0
    ```

=== "Matlab"

    ``` matlab
    'Release R2020b'
    ```

--8<-- "includes/abbr.md"
[^1]: Kutz, J. N. (2013). Data-Driven modeling &#38; scientific computation: Methods for complex systems &#38; big data. Oxford University Press.
[^2]: [Linear Algebra: Foundations to Frontiers](http://www.ulaff.net/).
