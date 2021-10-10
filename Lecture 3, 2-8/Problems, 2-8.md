[[_Lecture 3, 2-8|Lecture 3]]

*Due date February 22, solutions posted around that day.*

# 1

Show that the $q$-TASEP defined in [[../Lecture 2, 2-3/2.4 Some other particle systems#q-TASEP|L2]] exists, using a graphical construction similar to [[../Lecture 2, 2-3/2.2 Existence of TASEP#Proof 2 2 1|the one for TASEP]].

# 2

Describe the Markov chain with discrete time on $\left\{ 0,1 \right\}^{\mathbb{Z}}$ which corresponds to the Last Passage Percolation with independent $\mathrm{Geo}(q)$ weights. That is, "discretize" the time in TASEP. 

Hint: consider the case of one particle. Which random jumping mechanism corresponds to the waiting time till jump distributed as $\mathrm{Geo}(q)$?

# 3

Show that if for a sequence $(a_n)_n$ we have $a_{n+m}\ge a_n+a_m$ for all $n,m$, then there exists
$$
\lim_{n\to+\infty}\frac{a_n}{n}=\sup_n \frac{a_n}{n}
$$
(this limit may be equal to $+\infty$).


# 4

In the setup of [[3.3 Subadditive ergodic theorem|section 3.3]], use the subadditive ergodic theorem to establish the classical Birkhoff theorem. That is, for $T$ an ergodic map, and $f(x)$ an integrable function on $\Omega$ define
$$
S_n(x)=\frac{1}{n}\sum_{k=0}^{n-1}f(T^k x),\qquad x\in \Omega.
$$
So $S_n$ is the "time", or "orbital" average. As $n\to+\infty$, $S_n$ converges to the space ("probabilistic") average, 
$$
\lim_{n\to+\infty} S_n=\int_{\Omega}f(x)\,\mathsf{P}(dx).
$$

# 5

Show that 
$$
\lim_{n\to+\infty}\frac{1}{n}\sum_{k=0}^{n-1}\left\{ 2^k x \right\}=\frac{1}{2}
$$
for (Lebesgue-)almost every $x\in[0,1]$, where $\left\{ a \right\}$ is the fractional part of $a$.

# 6

A number $x\in[0,1)$ is called \emph{normal} (in base 2), if the number of $1$-s in its base 2 expansion $x=0.a_1a_2a_3\ldots$ among the first $n$ digits  $a_1,\ldots,a_n$ goes to $\frac{1}{2}$ as $n$ grows. Show that (Lebesgue-)almost all numbers in $[0,1)$ are normal.


# T1 

By T$i$ I will suggest topics for 10-minute talks, where $i$ is a counter throughout all lectures. This first talk idea is to present the proof of the subadditive ergodic theorem (Theorem 3.3.3 [[3.3 Subadditive ergodic theorem|here]]).

---

[[Solutions, 2-8]]