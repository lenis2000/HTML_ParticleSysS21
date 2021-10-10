[[_Lecture 6, 2-22|Lecture 6]]

# 1

Let $A$ be an $N\times N$ complex hermitian or real symmetric matrix. Let $\lambda_1\ge \ldots\ge \lambda_N$, $\lambda_i\in \mathbb{R}$, be eigenvalues of $A$. Let $B$ be the $(N-1)\times (N-1)$ matrix which is obtained by deleting, say, the $N$-th row and the $N$-th column of $A$. Show that the eigenvalues $\mu_1\ge \ldots\ge \mu_{N-1}$ of $B$ interlace with those of $A$:
$$\lambda_1\ge\mu_1\ge \ldots\ge \lambda_{N-1}\ge\mu_{N-1} \ge\lambda_N.$$

**Hint**. Use the "variational" characterization of the eigenvalues: $\lambda_1$ is the coefficient of maximal dilation of the norm of a vector by $A$, and so on:
$$
\lambda_k = \min_U \{ \max_x \{ \frac{(Ax,x)}{(x,x)} \mid x \in U \text{ and } x \neq 0 \} \mid \dim(U)=k \}
$$
$$
\lambda_k = \max_U \{ \min_x \{ \frac{(Ax,x)}{(x,x)} \mid x \in U \text{ and } x \neq 0 \} \mid \dim(U)=n-k+1 \}
$$

# 2

Show that the push-block process on infinite two-dimensional interlacing arrays (starting from an arbitrary initial configuration) exists.

**Hint.** Use compatibility of the dynamics restricted to the first $N$ levels, for all $N$.

# 3

Show that the PushTASEP (started from an arbitrary initial particle configuration on $\mathbb{Z}$) exists. 

**Hint.** Use a suitable version of the graphical construction, and maybe it is useful to replace particles by holes, and vice versa.

# 4

Show that the measure on interlacing arrays coming from a random walk with a fixed $\beta\in(0,1)$ satisfies the Gibbs property.

![[../img/Pasted image 20210222224658.png]]

# 5

Prove the formula for $\mathrm{Dim}_N\lambda$, the number of interlacing arrays of depth $N$ and with top row $\lambda$:
$$
\mathrm{Dim}_N\lambda=\prod_{1\le i<j\le N}\frac{\lambda_i-\lambda_j+j-i}{j-i},\qquad \lambda\in GT_N.
$$

**Hint.** You may use induction: $\mathrm{Dim}_N\lambda$ is the sum of $\mathrm{Dim}_{N-1}\mu$ over all $\mu\in GT_{N-1}$ which interlace with $\lambda$.

---

[[Solutions, 2-22|Solutions]]