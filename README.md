# VLDFO Supplementary Material

This repository contains supplementary material associated with the paper

**A feasible point method for derivative-free linearly constrained optimization**

by Morteza Kimiaei and Arnold Neumaier.

The file `CUTEst_246_problem_characteristics.pdf` provides detailed information on the 246 linearly constrained CUTEst test problems used in the numerical experiments.

For each problem, the table reports the CUTEst classification, the number of variables \(n\), the number \(n_c\) of original CUTEst constraints other than variable bounds, and the numbers \(|E|\) and \(|P|\) of equality and inequality rows, respectively, in the linear constraint representation used by VLDFO after preprocessing.

Because finite variable bounds are incorporated into the working linear inequality system, \(|E|+|P|\) may exceed \(n_c\).
