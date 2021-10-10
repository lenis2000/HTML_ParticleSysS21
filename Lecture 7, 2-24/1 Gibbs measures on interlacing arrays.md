Recall the definition of Gibbs measures:

#### Definition 1.0.1

![[../img/Pasted image 20210225114435.png]]

#### Definition 1.0.2

Gibbs measures form a convex set. That is, for $\mu_1,\mu_2$ Gibbs, their convex combinations $\gamma \mu_1+(1-\gamma)\mu_2$ are also Gibbs --- as convex combinations of uniform conditional distributions are uniform, too.

Recall that a Gibbs measure $\mu$ is called extreme if from $\mu=\gamma \mu_1+(1-\gamma)\mu_2$, $0<\gamma<1$, $\mu_1,\mu_2$ Gibbs, it follows that $\mu_1=\mu_2=\mu$.

#### Example 1.0.3

The "Bernoulli random walk" measure is an example of a nontrivial Gibbs measure. In fact, it is extreme. 

![[../img/Pasted image 20210225115805.png]]

---

Now, let us formulate several equivalent problems of classifying extreme Gibbs measures.

#### Problem 1.0.4

Classify extreme Gibbs measures on infinite interlacing arrays.

#### Problem 1.0.5

![[../img/Pasted image 20210225221154.png]]

The connection between Gibbs measures and harmonic functions is $\varphi_N(\lambda)=M(\lambda^{(N)}=\lambda)/\mathrm{Dim}_N\lambda$, $\lambda\in GT_N$.

#### Problem 1.0.6

Classify irreducible normalized characters of the infinite-dimensional unitary group $U(\infty)$.

#### Problem 1.0.7

![[../img/Pasted image 20210225221342.png]]

Example of a minor:

![[../img/Pasted image 20210225221353.png]]

#### Theorem 1.0.8

All the 4 problems formulated above are equivalent to each other. Details are outside of our scope for now; see the many papers in [[_Lecture 7, 2-24#Notes and references|Notes and references]].

#### Answer to all these problems

![[../img/Pasted image 20210225221437.png]]

For a not necessarily extreme normalized harmonic function $\{\varphi_N\}_N$, there exists a unique probability measure $\mu$ on $\Omega$ such that 
$$
\varphi_N(\lambda)=\int_\Omega \varphi_N^{\omega}(\lambda)\, \mu(d\omega),
$$
for all $N$ and all $\lambda\in GT_N$. Here $\varphi_N^{\omega}(\lambda)$ are the extreme harmonic functions (which have determinantal form).

#### Example 1.0.9 (Bernoulli random walk)

Below are some rough notes on the Bernoulli random walk extreme Gibbs measure.

![[../img/Pasted image 20210225221720.png]]

![[../img/Pasted image 20210225221727.png]]

![[../img/Pasted image 20210225221740.png]]