Let the space be $\mathbb{Z}_{\ge0}$ or $\mathbb{Z}$. 

#### Definition 2.0.1

A random subset $\mathcal{S}\subset \mathbb{Z}$ is called a **determinantal point process** if for any $m$ and any distinct points $a_1,\ldots,a_m\in \mathbb{Z} $ we have
$$
\mathrm{Prob}\left( \mathcal{S}\supset\left\{ a_1,\ldots,a_m  \right\} \right)
=
\det\left[ K(a_i,a_j) \right]_{i,j=1}^m,
$$
for some function $K(a,b)$. The function $K$ is called the **determinantal correlation kernel**.

#### Remark 2.0.2

For $m=1$ we have $K(x,x)=\mathrm{Prob}(\mathcal{S}\supset \left\{ x \right\})$, which is the density function we already worked with.

#### Remark 2.0.3. Repelling property

Assume that $K$ is Hermitean symmetric, that is, $K(x,y)=\overline{K(y,x)}$. Then
$$
\mathrm{Prob}\left( \mathcal{S}\supset\left\{ x,y \right\} \right)=
K(x,x)K(y,y) - |K(x,y)|^2\le K(x,x)K(y,y).
$$
This signifies that particles in a determinantal point process repel each other. 

Recall this example:

![[../img/Pasted image 20210203174112.png]]

#### Example 2.0.4

Take the Bernoulli process on $\mathbb{Z}$, where each location $x\in \mathbb{Z}$ is included in $\mathcal{S}$ independently with probability $p$. Then 


![[../img/Pasted image 20210317221300.png]]

#### Remark 2.0.5

A kernel is not defined uniquely, $\frac{f(x)}{f(y)}K(x,y)$ defines the same process (where $f$ is a nonvanishing function).

#### Example 2.0.6. Some other kernels

Discrete sine:

![[../img/Pasted image 20210317221459.png]]

See [[Problems, 3-17#1|Problem 1]]. 

Another correlation kernel, for example:

![[../img/Pasted image 20210317221813.png]]

#### Example 2.0.7. 

Kernel for the process on the right figure here:

![[../img/Pasted image 20210203174112.png]]

(here the process is in $\mathbb{C}$). We have
$$
K(z,w)=\frac{1}{\pi}e^{z\bar w-\frac{1}{2}(|z|^2+|w|^2)}.
$$
