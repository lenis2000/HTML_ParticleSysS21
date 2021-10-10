[[_Lecture 10, 3-8|Lecture 10]]

# 1 

Let $\lambda,\nu\in GT_N^+$. Show that if $\lambda\prec \nu$ (interlace) and $|\lambda| =|\nu|$, then $\lambda=\nu$.


# 2

Establish the following contour integral formula for the skew Schur polynomials:

![[../img/Pasted image 20210309110851.png]]

Hint: use the skew Cauchy identity and orthogonality as in [[../Lecture 9, 3-3/2 Continuous specialization#Proposition 2 0 1|here]].


# 3

Show that for the continuous specialization $\rho_t$ we have

![[../img/Pasted image 20210309111112.png]]

# 4

For the continuous specialization $\rho_{dt}$, as $dt\to0$, we have the following expansion:
$$
s_{\lambda/\mu}(\rho_{dt})=
\begin{cases}
	1+O(dt),&\lambda=\mu;\\
	O(dt),&|\lambda|=|\mu|+1;\\
	O(dt^2), &\text{else}.
\end{cases}
$$

Hint: use the contour integral formula from the previous problem.

# 5

Prove [[3.1 Continuous time limit of the push-block process#Proposition 3 1 2|Proposition 3.1.2]].

# 6

Show that the Schur process $SP_{(1,\ldots,1 );\rho_0}$ with the continuous specialization $\rho_t$ at $t=0$ is the delta measure at the densely packed configuration $\lambda^{(k)}_j=0$ for all $k,j$.
