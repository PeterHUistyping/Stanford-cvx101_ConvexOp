# [CVXPY tutorial](https://cvxgrp.org/cvx_short_course)

CVXPY is an open source Python-embedded modeling language for convex
optimization problems. It lets you express your problem in a natural way that
follows the math, rather than in the restrictive standard form required by
solvers. This tutorial will cover the basics of convex optimization, and how to
use CVXPY to specify and solve convex optimization problems, with an emphasis on real-world applications. No prior knowledge of convex optimization is assumed.

## Getting started

1. Clone from CVXPY
2. Install CVXPY following [these instructions](https://www.cvxpy.org/install/index.html).
   We recommend Python 3.10 and CVXPY 1.3.
3. Test your CVXPY installation by running ``test.py`` in the repository.

## Slides

for the lecture, see ``book/docs/scipy22_slides``

## Projects

See ``docs/``

**Intro to Python**

See ``docs/python_intro``

- Basics
- CVXPY MSE
  - constraint.dual_value
  - $λ^* = \frac{dM^*}{d c}$, c is the const in the constraint requirements.
- Data Structures
- Python namespaces
- Plotting

**SVM Classifier**

See ``docs/intro``

- average hinge loss + $\ell_1$-regularization
- Regularization Path

![reg_path](./book/docs/intro/svm_reg.svg)
