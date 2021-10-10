[[_Lecture 14, 3-22|Lecture]]

# 1

Show that for a determinantal process on $\mathbb{Z}$ or $\mathbb{R}$ with correlation kernel $K(x,y)$, we have (for finite / bounded set $A$)
$$
\mathbb{E}(\text{number of points of the point process belonging to}\ A)=
\sum_{x\in A}K(x,x)
$$
for $\mathbb{Z}$, and
$$
\mathbb{E}(\text{number of points of the point process belonging to}\ A)=
\int_A K(x,x)dx
$$
for $\mathbb{R}$.

# 2

Show that the kernel $K(x,y)$ of the Schur measure given [[1.1 Kernel|here]] converges to the discrete sine kernel:

As $x=\lfloor \chi N \rfloor $, $y=\lfloor \chi N \rfloor +\Delta x$, $\Delta x\in \mathbb{Z}$ fixed, $N\to+\infty$, $t=\tau N$, and $(\sqrt{\tau}-1)^2<\chi<(\sqrt{\tau}+1)^2$, we have 

![[../img/Pasted image 20210325112127.png]]

# 3

In the analysis, we considered only the case of one double critical point, $\chi^*=(\sqrt{\tau}-1)^2$, $\tau>1$. There are two more regimes:

- $0<\tau<1$, $\chi=(\sqrt\tau-1)^2$
- $\tau>0$, $\chi+(\sqrt\tau+1)^2$.

Determine the asymptotics of the kernel in these two other cases.

# 4

Explain why the terms $(z^*)^{(r-s)N^{1/3}}$ (in red in [[2.4 Asymptotics of the kernel#Theorem 2 4 1|this theorem]]) do not matter for the asymptotics of the process, and can be ignored.
