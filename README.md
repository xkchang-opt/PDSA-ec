# PDSA-ec
Code for primal-dual splitting algorithm proposed by Xiaokai Chang et.al.
Numerical results on image denoising, matrix-game, and LASSO problems are carried out.

Paper: A primal-dual splitting algorithm with convex combination and larger step sizes for composite monotone inclusion problems

Authors: Xiaokai Chang· Junfeng Yang· Jianchao Bai· Jianxiong Cao.


The primal-dual splitting algorithm (PDSA) by Chambolle and Pock is efficient for solving structured convex optimization problems. It adopts an extrapolation step and achieves convergence under certain step size condition. Chang and Yang recently proposed a modified PDSA for bilinear saddle point problems, integrating a convex combination step to enable convergence with extended step sizes. In this paper, we focus on composite monotone inclusion problems (CMIPs), a generalization of convex optimization problems. While V˜ u extended PDSA to CMIPs, whether the modified PDSA can be directly adapted to CMIPs remains an open question. This paper introduces a new PDSA for CMIPs, featuring the inclusion of both an extrapolation step and a convex combination step. The proposed algorithm is reformulated as a fixed-point iteration by leveraging an extended averaged nonexpansive operator. Under a significantly relaxed step size condition, both its convergence and sublinear convergence rate results are rigorously established. For structured convex optimization problem, we establish its sublinear convergence rate results measured by function value gap and constraint violations. Moreover, we show through a concrete example that our condition on the involved parameters cannot be relaxed. Numerical experiments on image denoising, inpainting, matrix games, and LASSO problems are conducted to compare the proposed algorithm with state-of-the-art counterparts, demonstrating the efficiency of the proposed algorithm.
