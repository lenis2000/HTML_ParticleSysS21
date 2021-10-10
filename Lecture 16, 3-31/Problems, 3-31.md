[[_Lecture 16, 3-31|Lecture]]

# 1

Show that the Hall--Littlewood polynomials defined as partition functions normalized by $\prod 1/(t;t)_{m_i}$ (in the lecture) satisfy the **stability** property, where $\lambda=(\lambda_1,\lambda_2,\ldots,\lambda_{N-1},\lambda_N )$:
$$
P_{(\lambda_1,\ldots,\lambda_{N-1},\lambda_N )}(u_1,u_2,\ldots,u_{N-1},0 )=
\begin{cases}
	P_{(\lambda_1,\ldots,\lambda_{N-1})}(u_1,u_2,\ldots,u_{N-1}),& \lambda_N=0,\\
	0,&\text{otherwise}.
\end{cases}
$$

# 2

Show that the partition function for the Hall--Littlewood polynomial $P_\lambda$ reduces to the Schur polynomial $s_\lambda$ for $t=0$. For that, present a weight-preserving bijection between path configurations on the red lattice, and interlacing arrays (which are the model for Schur polynomials).


# 3

Let $Q_\lambda^*$ be the partition function on the blue lattice, as defined in the lecture. Show that

1. $Q^*_\lambda(v_1,\ldots,v_M )$ is symmetric in $v_1,\ldots,v_M$.
	
2. We have
	$$
	Q^*_\lambda(v_1,\ldots,v_M )
	=
	b_\lambda
	P_\lambda(v_1,\ldots,v_M ),
	$$
	where the constant $b_\lambda$ does not depend on $v_1,\ldots,v_M$.

# 4

Consider the HL vertex model on the cylinder:

![[../img/Pasted image 20210331222331.png]]

Show that the partition function is symmetric in the variables $u_i$. 

**Hint**. Use the fact that the red cross weights satisfy the following cancellation property:

![[../img/Pasted image 20210331222432.png]]