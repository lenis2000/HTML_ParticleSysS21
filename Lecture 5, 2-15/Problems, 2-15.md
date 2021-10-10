[[_Lecture 5, 2-15|Lecture 5]]

# 1

**Notation**. In this and the next problem we denote by $a^+=\max(a,0)$ the positive part of $a$.

Let $0<r<p<1 .$ Let $I, J$ and $Y$ be independent geometric random variables with distributions
$$
P[I=k]=\frac{p-r}{1-r}\left(\frac{1-p}{1-r}\right)^{k}, P[J=k]=r(1-r)^{k}, P[Y=k]=p (1-p)^{k}
$$
for $k \in \mathbb{Z}_{\ge0} .$ Let $I_{1}=(I-J)^{+}+Y, J_{1}=(J-I)^{+}+Y$ and $X=\min(I,J) .$ Then the triple $\left(I_{1}, J_{1}, X\right)$
has the same distribution as $(I, J, Y)$.

**Hint**: Use the joint moment generating function $\mathbb{E}\left[ a^{I_1} b^{J_1}c^{X} \right]$ and show that it's the same as for $(I,J,Y)$.

# 2

Consider the last-passage model with boundaries:

![[../img/Pasted image 20210215111212.png]]

Recall the notation $L(m,n)$ for the last-passage times from $(0,0)$ to $(m,n)$.

In the last-passage model with boundaries we define some new random variables. Horizontal and vertical increments are given by
$$
\begin{array}{ll}
\quad I_{i, j}=L(i, j)-L(i-1, j) & \text { for } i \geq 1, j \geq 0 \\
\text { and } \quad J_{i, j}=L(i, j)-L(i, j-1) & \text { for } i \geq 0, j \geq 1
\end{array}
$$
An alternative formula for $I_{i, j}$ develops as follows, if $i, j \geq 1$ :
$$
\begin{aligned}
I_{i, j} &=L(i, j)-L(i-1, j) \\
&=\max(L(i-1, j) ,L(i, j-1))+Y_{i, j}-L(i-1, j-1) \\
&-\left[L(i-1, j)-L(i-1, j-1)\right] \\
&=\max(J_{i-1, j} , I_{i, j-1})+Y_{i, j}-J_{i-1, j} \\
&=\left(I_{i, j-1}-J_{i-1, j}\right)^{+}+Y_{i, j}
\end{aligned}
$$
Similar formula works for $J_{i, j}$ by symmetry, so we have
$$
I_{i, j}=\left(I_{i, j-1}-J_{i-1, j}\right)^{+}+Y_{i, j}
$$
$$
J_{i, j}=\left(J_{i-1, j}-I_{i, j-1}\right)^{+}+Y_{i, j} \quad \text { for }(i, j) \in \mathbb{Z}_{\ge1}^{2}
$$
Define
$$
X_{i, j}=\min(I_{i+1, j} , J_{i, j+1}) \quad \text { for }(i, j) \in \mathbb{Z}_{\ge0}^{2}
$$

Take a down-right path $\sigma$ and let
$$
Z_{\ell}(\sigma)=\left\{\begin{array}{ll}
L(\sigma(\ell+1))-L(\sigma(\ell))=I_{\sigma(\ell+1)} & \text { if } \sigma(\ell+1)-\sigma(\ell)=(1,0) \\
L(\sigma(\ell))-L(\sigma(\ell+1))=J_{\sigma(\ell)} & \text { if } \sigma(\ell+1)-\sigma(\ell)=(0,-1)
\end{array}\right.
$$

Prove the following:

#### Theorem

The random variables $X_{i,j}$ below $\sigma$, and $Z_\ell(\sigma)$ for all $\ell$ are independent and geometrically distributed. Moreover, $X_{i,j}$ are distributed as "bulk" LPP weights; along $\sigma$ horizontal increments have the "horizontal" distribution; and along $\sigma$ the vertical increments have the "vertical" distribution.

![[../img/Pasted image 20210215111216.png]]

%%# 3

Show that the Bernoulli product measure $\mu_{\rho}$ on $\left\{ 0,1 \right\}^{\mathbb{Z}}$ is extreme within the class of translation invariant measures. 

**Notation**. $\mu_\rho$ is the measure corresponding to the sequence of iid Bernoulli random variables (with $\rho$ the probability of $1$) at each component of $\mathbb{Z}$. A translation invariant probability measure is called extreme if the equality $\mu=\gamma \mu_1+(1-\gamma)\mu_2$, where $\gamma\in(0,1)$ and $\mu_1,\mu_2$ are translation invariant probability measures, implies $\mu_1=\mu_2=\mu$.

**Hint**. We have $\mu_1\le 1/\gamma \mu$, so $\mu_1$ is absolutely continuous with respect to $\mu$. Therefore by Radon--Nikodym, there exists a function $f$ for which $\mu_1=f\, d\mu$. Show that $f$ must be a translation invariant function on $\left\{ 0,1 \right\}^{\mathbb{Z}}$. Show that this leads to a contradiction with $\gamma\in(0,1)$.

# 4

Extreme translation invariant probability measures on $\left\{ 0,1 \right\}^\mathbb{Z}$ form a wider family than just the Bernoulli product measures. Produce an example of an extreme translation invariant measure which is not $Ber(\rho)$.%%

# 3

Take the action of another group of transformations on $\left\{ 0,1 \right\}^{\mathbb{Z}}$, namely, _finitary permutations_. These are permutations $\sigma$ which fix all but finitely many points (but which points are fixed depends on $\sigma$); they form a group which is usually called the _infinite symmetric group_. A measure invariant under this group is usually called _exchangeable_.

De Finetti's theorem states that all extreme exchangeable probability measures on $\left\{ 0,1 \right\}^{\mathbb{Z}}$ are Bernoulli product measures.

Prove this theorem, or find its proof in the literature and understand the argument.


# T2

By T$i$ I will suggest topics for 10-minute talks, where $i$ is a counter throughout all lectures. This second talk idea is to continue the discussion of the stationary LPP field using Seppalainen's lecture notes, and explain how to get the explicit limit shape via a certain variational principle.

# T3 

(By T$i$ I suggest topics for 10-minute talks, where $i$ is a counter throughout all lectures.)

Explain a proof of de Finetti's theorem in a 10-minute talk.

---

[[Solutions, 2-15|Solutions]]