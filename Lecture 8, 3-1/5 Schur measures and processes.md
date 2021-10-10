#### Definition 5.0.1. Schur measure

![[../img/Pasted image 20210301223143.png]]

Notation, if parameters are important:
$$
SM_{(\vec x,\vec y)}(\lambda)
$$

#### Definition 5.0.2. (Ascending) Schur process

![[../img/Pasted image 20210301223314.png]]

Notation:
$$
SP_{(\vec x,\vec y)}(\lambda^{(1)},\ldots,\lambda^{(N)} )
$$

#### Proposition 5.0.3

![[../img/Pasted image 20210301223412.png]]

#### Proof 5.0.3

![[../img/Pasted image 20210301223423.png]]

We see that the probability weight does not depend on $\lambda^{(1)},\ldots,\lambda^{(N-1)}$, and depends only on $\lambda^{(N)}$. This is precisely the Gibbs property from [[../Lecture 6, 2-22/_Lecture 6, 2-22|Lecture 6]] and [[../Lecture 7, 2-24/_Lecture 7, 2-24|Lecture 7]].

#### Proposition 5.0.4

Under the Schur process $SP_{(x_1,\ldots,x_N;y_1,\ldots,y_M  )}$, the marginal distribution of $\lambda^{(k)}$ is the Schur measure $SM_{(x_1,\ldots,x_k;y_1,\ldots,y_M  )}$.

#### Proof 5.0.4 (sketch)

For simplicity, let $k=N-1$. Other cases are similar.

We sum the probability weights of $SP_{(x_1,\ldots,x_N;y_1,\ldots,y_M  )}(\lambda^{(1)},\ldots,\lambda^{(N-2)},\nu,\lambda^{(N-1)} )$ over $\lambda^{(1)},\ldots,\lambda^{(N-2)}$ and over $\lambda^{(N-1)}$, where $\nu$ is fixed. The first sum does not involve $y_j$'s, and using the definition of the skew Schur polynomials we get $s_\nu(x_1,\ldots,x_{N-1} )$. Then we need to sum over $\lambda^{(N)}$. This sum looks as
$$
\sum_{\lambda^{(N)}}s_{\lambda^{(N)}/\nu}(x_N)s_{\lambda^{(N)}}(y_1,\ldots,y_M ).
$$
This sum can be computed using the [[4.3 Skew Cauchy identity and a bijective proof#Theorem 4 3 1 Skew Cauchy identity|skew Cauchy identity]], and the result follows. [[Problems, 3-1#6|Problem 6]]: finalize the details of the proof.
