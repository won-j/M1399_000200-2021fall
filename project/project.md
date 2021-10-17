# Course Project 

#### Proposal due: 2021-10-25 @ 11:59PM
#### Presentation: 2021-12-08 and 2021-12-13 (tentative)

This page lists some potential course project ideas. 
The goal of the project is to review recent developments in statistical computing, implement in *Julia*, and compare the related methods. 
Three (3) students should team up to accomplish the goal. Each team is required to choose one paper from the list below (no duplication is allowed) and submit a project proposal by the due date.

## Stochastic optimization

In large-scale optimization, often the objective function or its derivatives can only be estimated. In this case, *stochastic* methods come to rescue. Recent developments include:

* Chen, X., J. D. Lee, X. T. Tong, and Y. Zhang (2020). "Statistical inference for model parameters in stochastic gradient descent," Annals of Statistics, 48(1), 251–273.

* Zhu, W., X. Chen, and W. B. Wu (2021). "Online Covariance Matrix Estimation in Stochastic Gradient Descent," arXiv:2002.03979v2 [stat.ML], available at <https://arxiv.org/abs/2002.03979v2>.

## Optimal Design

In design of experiments, optimal designs are a class of experimental designs that are optimal with respect to some statistical criterion. Recent algorithmic developments include:

<!-- * Dennis Schmidt. "Characterization of $c$-, $L$-, and $\phi_k$-optimal designs for a class of non-linear multiple-regression models." Journal of the Royal Statistical Society -- Series B (2019): 101-120 -->

* De Castro, Yohann, Fabrice Gamboa, Didier Henrion, Roxana Hess, and Jean-Bernard Lasserre (2019). "Approximate optimal designs for multivariate polynomial regression." Annals of Statistics 47(1), 127-155.

<!--* Yue, Yuguang, Lieven Vandenberghe, and Weng Kee Wong (2019). "T-optimal designs for multi-factor polynomial regression models via a semidefinite relaxation method." Statistics and Computing 29(4), 725-738.-->

## Mixed integer optimization for model selection

Model selection is a difficult statistical problem with an exponential complexity. A typical example is high-dimensional linear model with L0 penalty. Nonetheless, recent progress in mixed integer optimization (MIO) has made large-scale problems tractable. They include:

<!--* Bertsimas, Dimitris, and Bart Van Parys (2020). "Sparse high-dimensional regression: Exact scalable algorithms and phase transitions." Annals of Statistics 48(1), 300-323.-->

* Bertsimas, Dimitris, Angela King, and Rahul Mazumder (2016). "Best subset selection via a modern optimization lens." Annals of Statistics 44(2), 813-852.

<!--* Dedieu, Antoine, Hussein Hazimeh, and Rahul Mazumder (2021). "Learning Sparse Classifiers: Continuous and Mixed Integer Optimization Perspectives." Journal of Machine Learning Research 22(135), 1-47.-->

* Hastie, Trevor, Robert Tibshirani, and Ryan Tibshirani (2020). "Best subset, forward stepwise or lasso? Analysis and recommendations based on extensive comparisons." Statistical Science 35(4), 579-592.
	+ R code available at <https://github.com/ryantibs/best-subset/>

* Lee, Sokbae, Yuan Liao, Myung Hwan Seo, and Youngki Shin (2021). "Factor-driven two-regime regression." Annals of Statistics 49(3), 1656-1678.
	+ R code available at <https://github.com/yshin12/fadtwo>

<!--
## Fused lasso and total variation penalty

Total variation (TV) penalty has been popular in image processing since the work of Rudin, L. I., Osher, S. and Fatemi, E. (1992), "Nonlinear total variation based noise removal algorithms," Physica D: 60(1), 259–268. This penalty has become popularized in statistics under the name "fused lasso," due to Tibshirani, R. , Saunders, M., Rosset, S., Zhu, J., and Knight, K. (2005), "Sparsity and Smoothness Via the Fused Lasso," Journal of the Royal Statistical Society, Series B, 67, 91–108; and Tibshirani, R. J., and Taylor, J. (2011), "The Solution Path of the Generalized Lasso," Annals of Statistics, 39, 1335–1371. TV penalty is becoming increasingly popular in other estimation problems than regression:

* Bassett, Robert, and James Sharpnack. "Fused density estimation: theory and methods." Journal of the Royal Statistical Society -- Series B (2019): 839-860. 

* Tan, K. M. and Witten, D. "Statistical properties of convex clustering." Electron. J. Statist. (2015): 2324–2347. 
-->

