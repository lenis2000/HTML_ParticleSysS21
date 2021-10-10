#### Proposition 2.0.1

Schur polynomial $s_\lambda(x_1,\ldots,x_N )$ is a symmetric polynomial in $x_1,\ldots,x_N $. It is a homogeneous polynomial, of degree $|\lambda|=\lambda_1+\ldots+\lambda_N $.

#### Proof 2.0.1

Straightforward from the definitions.

#### Proposition 2.0.2. Stability of Schur polynomials

We will identify signatures $\lambda=(\lambda_1,\ldots,\lambda_N )$ and $(\lambda_1,\ldots,\lambda_N,0,0,\ldots,0  )$ (any finite number of zeroes), where $\lambda_N\ge0$.

With this identification, we have the following stability of Schur polynomials:

![[../img/Pasted image 20210301212602.png]]

In fact, this stability allows to define symmetric functions, which might be seen as an abstraction meaning "symmetric polynomials in an unspecified number of variables". We will not discuss these just yet.

#### Proof 2.0.2

![[../img/Pasted image 20210301212742.png]]

#### Proposition 2.0.3

The Schur polynomials $s_\lambda(x_1,\ldots,x_N )$, as $\lambda$ ranges over all nonnegative signatures with $N$ parts, form a basis in the space $\mathcal{S}=\mathbb{C}[x_1,\ldots,x_N ]^{S_N}$ of symmetric polynomials.

#### Proof 2.0.3

Let us look at the space of polynomials $\mathbb{C}[x_1,\ldots,x_N ]$. It has basis of monomials, $x_1^{\alpha_1}\ldots x_N^{\alpha_N}$, $(\alpha_1,\ldots,\alpha_N )\in \mathbb{Z}_{\ge0}^N$. That is, any polynomial is a finite linear combination of monomials. 

Now, consider two subspaces, $\mathcal{S}=\mathbb{C}[x_1,\ldots,x_N ]^{S_N}$ of symmetric polynomials, and $\mathcal{A}$ of antisymmetric polynomials. A polynomial is antisymmetric if $f(\sigma x)=\mathop{\mathrm{sgn}}\sigma\cdot f(x)$, where $\sigma\in S_N$ acts by permuting the variables.

A basis in $\mathcal{A}$ is formed by antisymmetrized monomials, 
$$
a_\mu(x_1,\ldots,x_N )=\sum_{\sigma\in S_N}\mathop{\mathrm{sgn}}\sigma\cdot x_{\sigma(1)}^{\mu_1}
\ldots x_{\sigma(N)}^{\mu_N} .
$$
Here $\mu_1> \ldots>\mu_N\ge0$ must be strictly ordered. Another way to write $a_\mu$ is to use the determinant, $a_\mu(x_1,\ldots,x_N )=\det\left[ x_i^{\mu_j} \right]_{i,j=1}^N$.

Moreover, any antisymmetric polynomial $f\in \mathcal{A}$ is divisible by the Vandermonde $V(x)=\prod_{i<j}(x_i-x_j)$, and the ratio is a symmetric polynomial. Therefore, we have $\mathcal{A}=\mathcal{S}\cdot V(x)$. 

Passing from the basis in $\mathcal{A}$ to the basis in $\mathcal{S}$, we get Schur polynomials. And they form a basis in $\mathcal{S}$, as desired.

#### Remark 2.0.4

In fact, the functions $s_\lambda$ form an orthogonal basis, with respect to an inner product defined using certain contour integrals over a torus. We will need this fact soon, and then will formulate and prove it.
