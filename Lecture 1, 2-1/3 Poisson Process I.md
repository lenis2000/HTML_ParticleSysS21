## 3.1 General definition

![[../img/Pasted image 20210201210114.png]]

#### Definition. Poisson process

![[../img/Pasted image 20210201210133.png]]

On this picture we have $N(A)=0$, $N(B)=3$, $N(C)=1$. These three random variables must be independent.

![[../img/Pasted image 20210201210207.png]]

#### Notes. Poisson process

1. There are no *double points* in a Poisson process, since $\mu( \left\{ x \right\})=0$ for all points $x\in X$.
2. If $\mu(A)=\infty$, then there are infinitely many points of the Poisson process in $A$. An example, there are infinitely many points of the usual Poisson process in $\mathbb{R}$.
3. If $A\cap B=\varnothing$, then $N(A)$ and $N(B)$ are independent, and $N(A\cup B)=N(A)+N(B)$. Note that here we use additivity of Poisson random variables, so that $N(A \cup B)$ is also Poisson, and definition is self-consistent.
4. Same additivity can be employed for countable disjoint unions. In this sense, the Poisson process can be viewed as a *random atomic measure*.

![[../img/Pasted image 20210201210846.png]]

## 3.2 Uniformity and independence in a Poisson process

![[../img/Pasted image 20210201210901.png]]

#### Theorem 3.2.1

![[../img/Pasted image 20210201211152.png]]

#### Proof 3.2.1

![[../img/Pasted image 20210201211219.png]]

Then points are independent, because each of them independently chooses whether to land in $B$ or $A\setminus B$, with probabilities $p$ and $1-p$, respectively.

Let us now show the binomial distribution. We have
$$
\mathsf{P}\left( N(B)=m\mid N(A)=K \right)=
\frac{\mathsf{P}\left( N(B)=m, N(A)=K \right)}
{\mathsf{P}(N(A)=K)}=
\frac{\mathsf{P}\left( N(B)=m, N(A\setminus B)=K-m \right)}
{\mathsf{P}(N(A)=K)},
$$
and now we can use independence of the point counts corresponding to $B$ and $A\setminus B$:
$$
=\frac{e^{-\mu(B)}(\mu(B))^k/k!\cdot e^{-\mu(A\setminus B)}(\mu(A\setminus B))^{K-m}/(K-m)!}{e^{-\mu(A)}(\mu(A))^K/K!}=
\binom{K}{m}p^m(1-p)^{K-m},
$$
as desired. $\square$

#### Converse statement: from uniform to Poisson

![[../img/Pasted image 20210201211925.png]]

## 3.3 Using homogeneous Poisson process in 1d to model arrivals

The homogeneous Poisson process in $\mathbb{R}^1$ is a model for successive rings of an *exponential clock*, which is used in describing TASEP and other particle systems.

![[../img/Pasted image 20210201212521.png]]

#### Theorem 3.3.1

![[../img/Pasted image 20210201212546.png]]

#### Proof 3.3.1

![[../img/Pasted image 20210201212600.png]]

![[../img/Pasted image 20210201212607.png]]

![[../img/Pasted image 20210201212617.png]]