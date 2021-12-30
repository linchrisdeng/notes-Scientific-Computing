---
title: 
description: Homepage for Lin's scientific computing
---

# Overview 

Welcome to Scientific Computing. This is a website for Lin Deng to store the notes and application of scientific computation methods during his PhD journey. The repo launched from Dec 2021 when Lin finished his first-year confirmation meeting at the U of Melbourne (Melbourne Business School). Aim to consolidate the understanding of scientific computation techniques and rebuild the notion of coordinate changing in the computational research work, the notes contain 3 aspects to illustrate SC in Finance, Econ. Part 1: Algebra with Matrix, Linear System and Factor Analysis, Part 2: Numeric Optimization, Part 3: Nonlinear/Dynamic System - Differential Equations. 

The material is mainly related to the book DDMSC[^1]. Contents are split into the following sections:
!!! note inline end 
    The content will be constantly updated and adjusted over time. 
    
    √ sign labels complete sections. 
    
    Structure tree is generated from [tree.nathanfriend.io](https://tree.nathanfriend.io/)
```
.
├── Home
├── Part1: Basics
│   ├── Algebra with Matrix
│   │   ├── 1.1 Vector and Matrix √
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

```

!!! note inline end
    Python and Matlab code will be supplied if I have time
=== "Python"

    ``` py
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "Matlab"

    ``` matlab
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```


--8<-- "includes/abbr.md"
[^1]: Kutz, J. N. (2013). Data-Driven modeling &#38; scientific computation: Methods for complex systems &#38; big data. Oxford University Press.
