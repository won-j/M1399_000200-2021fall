# M1399.000200 Advanced Statistical Computing @ SNU 2021

This is the course website for M1399.000200: "Advanced Statistical Computing " at Seoul National University in Fall 2021. Assignments, lecture notes, and open source code will all be available on this website.

## Announcements

* 2021-09-25: Minor errors in lecture notes on Computer Arithmetic has been fixed. Thanks Taeyoung!
* 2021-09-23: HW1, Q4 has been clarified. Use the update notebook.
* 2021-09-22: Lecture notes on Computer Arithmetic and Algorithms have been updated. If you downloaded the notes before, try it again.
* 2021-09-08: Homework 1 has been posted.
* 2021-09-07: R package microbenchmark has been installed to the interactive lecture note `Julia Intro 1`. Now you can run all the cells online.
* 2021-09-01: course will be given online. Mostly real-time, but sometimes pre-recorded.

## Instructor 

Joong-Ho (Johann) Won

**Email**: wonj AT stats DOT snu DOT ac DOT kr

**Class Time**: Mondays/Wednesdays 11:00 - 12:15 @ online

**Office Hours**: By appointment.

**Textbook**: There is no required textbook.

**References**: 

- James Gentle, [Computational Statistics](https://link.springer.com/book/10.1007%2F978-0-387-98144-4), 2nd Edition, Springer (2009).
- Gene Golub and Charles Van Loan, [Matrix Computation](https://www.amazon.com/Computations-Hopkins-Studies-Mathematical-Sciences/dp/1421407949/ref=sr_1_1?keywords=matrix+computation+golub&qid=1567157884&s=gateway&sr=8-1), 4th Edition, Johns Hopkins Press (2012).
- Kenneth Lange, [Numerical Analysis for Statisticians](https://link.springer.com/book/10.1007%2F978-1-4419-5945-4), 2nd Edition, Springer (2010).
- Stephen Boyd and Lieven Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/), Cambridge University Press (2004).
- Dimitri P. Bertsekas, [Convex Optimization Theory](http://www.athenasc.com/convexduality.html) Athena Scientific (2009).
	

## Course Objectives

By the end of this course, you will be able to acquire

- basic programming skills using the [Julia programming language](https://julialang.org);
- basic knowledge of computer arithmetic;
- fundamental knowledge of numerical algorithms for statistical computing;
- hands-on knowledge of various optimization problems in statistical computing;
- basic theoretical understanding of mathematical optimization;
- wisdom of how *not* to reinvent the wheel.

## Course Overview

### Assessment

The course will be graded based on the following components:

- **Attendance** (10%): Mandatory.
- **Assignments** (65%): You will be assigned 4 homework assignments to be completed using Julia regularly throughout class. 
- **Final project** (25%): The project will be a reproduction of the code and results in a recent computational statistics research paper chosen by yourself *in Julia* . The ideas for projects will be provided towards the midpoint of the semester.

### Schedule

The following schedule is tentative, and is subject to change over the course.

| Week | Topic | Assignment | Due Date |
| --- | --- | --- | --- | 
| 1 (9/1)      | [Introduction](./lectures/01-intro/intro.html), [Julia Intro I](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/02-juliaintro/juliaintro1.ipynb) [[notebook](./lectures/02-juliaintro/juliaintro1.ipynb)] | [Jupyter](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/02-juliaintro/jupyter.ipynb) [[notebook](./lectures/02-juliaintro/jupyter.ipynb)], [Plotting](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/02-juliaintro/juliaplots.ipynb) [[notebook](./lectures/02-juliaintro/juliaplots.ipynb)]  |  | 
| 2 (9/6, 9/8)     | [Julia Intro II](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/02-juliaintro/juliaintro2.ipynb) [[notebook](./lectures/02-juliaintro/juliaintro2.ipynb)] | [Homework 1](./hw/hw1/hw01.html) [[notebook](./hw/hw1/hw01.ipynb)] | 2021-09-26 |
| 3 (9/13, 9/15)    | [Computer Arithmetic](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/03-arith/arith.ipynb) [[notebook](./lectures/03-arith/arith.ipynb)] |  |  |
| 4 (9/20, 9/22)    | [Computer Arithmetic](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/03-arith/arith.ipynb) [[notebook](./lectures/03-arith/arith.ipynb)], [Algorithm](https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/04-algo/algo.ipynb) [[notebook](./lectures/04-algo/algo.ipynb)] |  |  |
| 5 (9/27, 9/29)    | Numerical Linear Algebra: [intro]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/05-numalgintro/numalgintro.ipynb) [[notebook](./lectures/05-numalgintro/numalgintro.ipynb)]-->, [triangular systems]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/06-trisys/trisys.ipynb) [[notebook](./lectures/06-trisys/trisys.ipynb)]--> | [Homework 2]<!--(./hw/hw2/hw02.html) [[notebook](./hw/hw2/hw02.ipynb)]--> | 2021-10-17  |
| 6 (10/4, 10/6)    | [LU decomposition]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/07-gelu/gelu.ipynb) [[notebook](./lectures/07-gelu/gelu.ipynb)] [[example](./lectures/07-gelu/gelu.pdf)]-->, [Cholesky]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/08-chol/chol.ipynb) [[notebook](./lectures/08-chol/chol.ipynb)]--> |  |  |
| 7 (10/11, 10/13)  | [QR decomposition]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/09-qr/qr.ipynb) [[notebook](./lectures/09-qr/qr.ipynb)]-->, [Linear regression]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/10-linreg/linreg.ipynb) [[notebook](./lectures/10-linreg/linreg.ipynb)]-->, [Iterative methods]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/11-iterative/iterative.ipynb) [[notebook](./lectures/11-iterative/iterative.ipynb)]--> | [Final Project Proposal]<!--(./project/project.md)-->  | 2021-10-25  |
| 8 (10/18, 10/20)  | [Eigenvalue and singular value decompositions]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/13-eigsvd/eigsvd.ipynb) [[notebook](./lectures/13-eigsvd/eigsvd.ipynb)]--> |  |  |
| 9 (10/24, 10/27)  | [Introduction to mathematical optimization]<!--(./lectures/14-optmintro/optmintro.html)--> | [Homework 3]<!--(./hw/hw3/hw03.html) [[notebook](./hw/hw3/hw03.ipynb)]--> | 2021-11-16 |
| 10 (11/1, 11/3)   | [Optimization in Julia]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/15-juliaopt/juliaopt.ipynb) [[notebook]](./lectures/15-juliaopt/juliaopt.ipynb)--> |  |  |
| 11 (11/8, 11/10) | [Linear programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/16-lp/lp.ipynb) [[notebook]](./lectures/16-lp/lp.ipynb)-->, [Quadratic programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/17-qp/qp.ipynb) [[notebook]](./lectures/17-qp/qp.ipynb)-->, [Second-order cone programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/18-socp/socp.ipynb) [[notebook]](./lectures/18-socp/socp.ipynb)--> |  |  |
| 12 (11/15, 11/17) | [Semidefinite programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/19-sdp/sdp.ipynb) [[notebook]](./lectures/19-sdp/sdp.ipynb)-->, [Geometric programming]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/20-gp/gp.ipynb) [[notebook]](./lectures/20-gp/gp.ipynb)--> |  |  |
| 13 (11/22, 11/24) | [KKT conditions]<!--(./lectures/21-kkt/kkt.html)-->, [Newton's method I]<!--(https://mybinder.org/v2/gh/won-j/M1399_000200-2021fall/master?filepath=lectures/22-newton/newton.ipynb) [[notebook]](./lectures/22-newton/newton.ipynb)--> | [Homework 4]<!--(./hw/hw4/hw04.html) [[notebook](./hw/hw4/hw04.ipynb)]--> | 2021-12-13 |
| 14 (11/29, 12/1)   | [Newton's method II]<!--(./lectures/22-newton/newton_constr.html)-->, [MM algorithms]<!--(./lectures/24-mm/mm.html)--> |  |  |
| 15 (12/6, 12/8)  | [First-order methods]<!--(./lectures/23-first/first.html)-->, Final Projects      |  |  |
| 16 (12/13)  | Final Projects      |  |  |


