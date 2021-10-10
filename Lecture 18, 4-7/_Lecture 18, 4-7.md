[[Lecture 18, 4-7/Problems, 4-7\|3 problems]], due April 21

# 1 Reminders

Recall the following two results which we proved in the previous lectures. 

#### Theorem 1.0.1

Consider the stochastic six vertex model with inhomogeneous parameters $u_1,u_2\ldots$ along the horizontal direction, and $v_1,v_2,\ldots$ along the vertical direction. Assume that $|u_iv_j|<1$ for all $i,j$. Recall that the parameter $t\in[0,1)$ is assumed fixed once and for all. In the stochastic vertex model, the probabilities at $(x,y)$ are
$$
b_1(u_x,v_y):=\frac{1-u_xv_y}{1-tu_xv_y},\qquad 
b_2(u_x,v_y):=tb_1(u_x,v_y)=
\frac{t(1-u_xv_y)}{1-tu_xv_y}.
$$

Then the height function $h(x,y)$ in this model has the same distribution as $m_0(\lambda^{(x,y)})=y-\ell(\lambda^{(x,y)})$, where $\lambda^{(x,y)}$ is a random partition distributed according to the Hall--Littlewood measure
$$
\mathrm{Prob}(\lambda)=\prod_{i=1}^x\prod_{j=1}^y\frac{1-tu_iv_j}{1-u_iv_j}\,
P_\lambda(v_1,\ldots,v_y )Q_\lambda(u_1,\ldots,u_x ).
$$

#### Theorem 1.0.2

The Hall--Littlewood polynomials possess the following explicit formula:
$$
F_\lambda(u_1,\ldots,u_N )=\prod_{i\ge 0}(t;t)_{m_i(\lambda)}
P_\lambda(u_1,\ldots,u_N ),
$$
and
$$
F_\lambda(u_1,\ldots,u_N )=(1-t)^{N}\sum_{\sigma\in S_N}
\sigma\left( u_1^{\lambda_1}\ldots u_N^{\lambda_N} \prod_{1\le i<j\le N}\frac{u_i-tu_j}{u_i-u_j} \right),
$$
where $\sigma$ acts by permutations of the $u_j$'s.

# 2 Eigenoperators

- [[2 Eigenoperators]]

# 3 Contour integral formulas

- [[3.1 Contour integral for D(0,t)]]
- [[3.2 Expectation]]
- [[3.3 Multiple t-moments]]
- [[3.4 Moment problem]]

# 4 Idea of the asymptotic analysis

- [[4.1 q-binomial theorem]]
- [[4.2 Asymptotic fluctuations via t-Laplace transforms]]

# Notes and references

There are several papers on the method of $t$- (or $q$-) moments in the analysis of interacting particle systems. Here are the main references:

1. Alexei Borodin, Ivan Corwin. Macdonald processes. https://arxiv.org/abs/1111.4408; Proposition 3.2.1 onwards
2. Alexei Borodin, Ivan Corwin, Tomohiro Sasamoto. From duality to determinants for q-TASEP and ASEP. https://arxiv.org/abs/1207.5035. Section 3
3. Alexei Borodin, Ivan Corwin, Leonid Petrov, Tomohiro Sasamoto. Spectral theory for the q-Boson particle system. https://arxiv.org/abs/1308.3475. Appendix 7.2 has the proof of the contour shift argument.
4. Alexey Bufetov, Matteo Mucciconi, Leonid Petrov. Yang-Baxter random fields and stochastic vertex models. https://arxiv.org/abs/1905.06815. Section 9.1 discusses operator approach to getting $t$-moments of the stochastic six vertex model, and the corresponding Fredholm determinants.
