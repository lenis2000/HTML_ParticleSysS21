[[_Lecture 9, 3-3|Lecture 9]]

# 1

Recall the inner product

![[../img/Pasted image 20210304213626.png]]

Show that the difference operator $D_q$ is self-adjoint: $\langle D_q f,g \rangle =\langle f,D_q g \rangle$. 

Hint: Recall $D_q=V^{-1}\circ \sum_{i=1}^{N}T_{q,x_i}\circ V$. Therefore, in the inner product, under the integral we can write
$$
\left( D_q f \right)V\overline {Vg} = 
\left( \sum_{i=1}^{N}T_{q,x_i}(Vf) \right)
\overline {Vg}.
$$
Therefore, it remains to show that $T_{q,x_i}$ is self-adjoint (for each $i$).

# 2

Justify that the integration and the summation can be swapped in the application of orthogonality to Cauchy identity (see [[2 Continuous specialization#Proposition 2 0 1|Proposition 2.0.1]]).

# 3

Prove the version of the Cauchy identity for the Plancherel specialization:

![[../img/Pasted image 20210304214516.png]]
