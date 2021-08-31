# M1399.000200 Advanced Statistical Computing @ SNU 2020

This is the course website for M1399.000200: "Advanced Statistical Computing " at Seoul National University in Fall 2020. Assignments, lecture notes, and open source code will all be available on this website.

## Announcements

* 2020-12-02: Homework 4, Q2-3 has been clarified.
* 2020-11-22: Homework 4 has been posted. Due data is 2020-12-14.
* 2020-11-18: GP lecture notes have been updated to include the ECOS solver.
* 2020-11-10: Homework 3 Q3-2 has been corrected.
* 2020-10-31: Homework 3 has been posted. Due date is 2020-11-17.
* 2020-10-14: Final project has been announced.
* 2020-10-12: Homework 2 typos has been fixed. See especially Q5.
* 2020-09-27: Homework 2 has been posted. Due date is 2020-10-18.
* 2020-09-27: A make-up lecture for 2020-09-30 class will be recorded and posted on eTL.
* 2020-09-27: Lecture note 3 has been updated.
* 2020-09-16: Fixed typos in Homework 1.
* 2020-09-11: Homework 1 has been posted. Due date is 2020-09-27.
* 2020-09-02: course will be given online. Mostly real-time, but sometimes pre-recorded.

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
- **Final project** (25%): The project will be a reproduction of the code and results in a recent computational statistics research paper chosen *in Julia* by yourself. The ideas for projects will be provided towards the midpoint of the semester.

### Schedule

The following schedule is tentative, and is subject to change over the course.

| Week | Topic | Assignment | Due Date |
|---| --- | --- | --- | 
| 1 (9/2)      | [Introduction](./lectures/01-intro/intro.html), [Julia Intro](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/02-juliaintro/juliaintro.ipynb) [[notebook](./lectures/02-juliaintro/juliaintro.ipynb)] | | | 
| 2 (9/7, 9/9)     | [Plotting](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/02-juliaintro/juliaplots.ipynb) [[notebook](./lectures/02-juliaintro/juliaplots.ipynb)], [Jupyter](./lectures/02-juliaintro/jupyter.html) | [Homework 1](./hw/hw1/hw01.html) [[notebook](./hw/hw1/hw01.ipynb)] | 2020-09-27 |
| 3 (9/14, 9/16)    | [Computer Arithmetic](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/03-arith/arith.ipynb) [[notebook](./lectures/03-arith/arith.ipynb)] |  |  |
| 4 (9/21, 9/23)    | [Computer Arithmetic](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/03-arith/arith.ipynb) [[notebook](./lectures/03-arith/arith.ipynb)], [Algorithm](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/04-algo/algo.ipynb) [[notebook](./lectures/04-algo/algo.ipynb)] |  |  |
| 5 (9/28, 9/30)    | Numerical Linear Algebra: [intro](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/05-numalgintro/numalgintro.ipynb) [[notebook](./lectures/05-numalgintro/numalgintro.ipynb)], 	[triangular systems](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/06-trisys/trisys.ipynb) [[notebook](./lectures/06-trisys/trisys.ipynb)] | [Homework 2](./hw/hw2/hw02.html) [[notebook](./hw/hw2/hw02.ipynb)] | 2020-10-18  |
| 6 (10/5, 10/7)    | [LU decomposition](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/07-gelu/gelu.ipynb) [[notebook](./lectures/07-gelu/gelu.ipynb)] [[example](./lectures/07-gelu/gelu.pdf)], [Cholesky](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/08-chol/chol.ipynb) [[notebook](./lectures/08-chol/chol.ipynb)] | |  |  |
| 7 (10/12, 10/14)  | [QR decomposition](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/09-qr/qr.ipynb) [[notebook](./lectures/09-qr/qr.ipynb)], [Linear regression](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/10-linreg/linreg.ipynb) [[notebook](./lectures/10-linreg/linreg.ipynb)], [Iterative methods](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/11-iterative/iterative.ipynb) [[notebook](./lectures/11-iterative/iterative.ipynb)] | [Final Project Proposal](./project/project.md)  | 2020-10-26  |
| 8 (10/19, 10/21)  | [Eigenvalue and singular value decompositions](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/13-eigsvd/eigsvd.ipynb) [[notebook](./lectures/13-eigsvd/eigsvd.ipynb)] | | |
| 9 (10/25, 10/28)  | [Introduction to mathematical optimization](./lectures/14-optmintro/optmintro.html) | [Homework 3](./hw/hw3/hw03.html) [[notebook](./hw/hw3/hw03.ipynb)] | 2020-11-17 |
| 10 (11/2, 11/4)   | [Optimization in Julia](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/15-juliaopt/juliaopt.ipynb) [[notebook]](./lectures/15-juliaopt/juliaopt.ipynb) |  |  |
| 11 (11/9, 11/11) | [Linear programming](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/16-lp/lp.ipynb) [[notebook]](./lectures/16-lp/lp.ipynb), [Quadratic programming](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/17-qp/qp.ipynb) [[notebook]](./lectures/17-qp/qp.ipynb), [Second-order cone programming](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/18-socp/socp.ipynb) [[notebook]](./lectures/18-socp/socp.ipynb) | | |
| 12 (11/16, 11/18) | [Semidefinite programming](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/19-sdp/sdp.ipynb) [[notebook]](./lectures/19-sdp/sdp.ipynb), [Geometric programming](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/20-gp/gp.ipynb) [[notebook]](./lectures/20-gp/gp.ipynb) | |  |
| 13 (11/23, 11/25) | [KKT conditions](./lectures/21-kkt/kkt.html), [Newton's method I](https://mybinder.org/v2/gh/won-j/M1399_000200-2020fall/master?filepath=lectures/22-newton/newton.ipynb) [[notebook]](./lectures/22-newton/newton.ipynb) | [Homework 4](./hw/hw4/hw04.html) [[notebook](./hw/hw4/hw04.ipynb)] | 2020-12-14 |
| 14 (11/30, 12/2)   | [Newton's method II](./lectures/22-newton/newton_constr.html), [MM algorithms](./lectures/24-mm/mm.html) |  |  |
| 15 (12/7, 12/9)  | [First-order methods](./lectures/23-first/first.html), Final Projects      |  |  |
| 16 (12/14)  | Final Projects      |  |  |


