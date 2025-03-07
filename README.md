# PDSA-ec
Code for primal-dual splitting algorithm proposed by Xiaokai Chang et.al.
Numerical results on image denoising, matrix-game, and LASSO problems are carried out.

Paper: A primal-dual splitting algorithm with convex combination and larger step sizes for composite monotone inclusion problems

Authors: Xiaokai Chang· Junfeng Yang· Jianchao Bai· Jianxiong Cao.


The primal-dual splitting algorithm (PDSA) proposed by V˜ u [Advances in Computational Mathematics, 38(3): 667–681, 2013] is efficient for solving composite monotone inclusion problems (CMIPs). It adopts an extrapolation step and achieves convergence under certain step size condition. Recently, Chang and Yang developed a modified PDSA for bilinear saddle point problems, a subclass of CMIPs, that incorporates a convex combination step and achieves convergence with larger step sizes. However, it remains unclear whether a straightforward extension of the modified PDSA to the CMIPs is possible. This paper introduces a new PDSA for CMIPs, featuring the inclusion of both an extrapolation step and a convex combination step. The proposed algorithm is reformulated as a fixed-point iteration by leveraging an extended averaged nonexpansive operator. Under a significantly relaxed step size condition, both its convergence and sublinear convergence rate results are rigorously established. Moreover, we shown by a constructed counterexample that, our condition on the involved parameters is sharp. Numerical experiments on image denoising, matrix-game, and LASSO problems are carried out, demonstrating the efficiency of the proposed algorithm.
