[[../../Lecture 6, 2-22/Problems, 2-22|Problems]]

[[../../Lecture 6, 2-22/_Lecture 6, 2-22|Lecture]]

# 1

![[../../img/Pasted image 20210305103148.png]]

![[../../img/Pasted image 20210305103158.png]]

# 2

The push-block process exists by Kolmogorov extension theorem. Namely, for each finite $N$ the evolution of $\lambda^{(1)},\ldots,\lambda^{(N)}$ exists (starting from an arbitrary initial configuration) because it is a finite-dimensional Markov jump process (like a Poisson process, but possibly more complicated). 

Then, for different $N$'s, the stochastic processes are compatible with each other. That is, given $N$ and the evolution of $\lambda^{(1)},\ldots,\lambda^{(N)}$, the marginal evolution of $\lambda^{(1)},\ldots,\lambda^{(k)}$, $k<N$, is independent of levels $k+1,\ldots,N$, and coincides with the push-block process on the first $k$ levels. Therefore, by Kolmogorov extension, we can define the process on infinitely many levels.

# 3

Let us assume that the initial configuration is not densely packed to the left. 

Model the PushTASEP process by putting independent Poisson clocks at each site. Then make the graphical construction as follows. When a Poisson clock rings at a site, if there is a hole then nothing happens. If there is a particle, then the particle jumps to the next available hole on the right. 

![[../../img/Pasted image 20210305105757.png]]

There could be an issue with having a densely packed configuration of particles to the right, so that there is no available hole. In this case, employ Kolmogorov extension theorem and construct the process on $\mathbb{Z}_{\le N}$ for some $N$, with modified jumping rule: if there is no available hole before $N$, then the particle which wants to jump past $N$ must disappear. These processes are compatible with each other, and so a global process on $\mathbb{Z}$ exists. If initially there is a densely packed configuration to the right, then the process makes infinitely many jumps in finite time.

# 4

![[../../img/Pasted image 20210305110035.png]]



# 5

![[../../img/Pasted image 20210305120738.png]]

![[../../img/Pasted image 20210305120748.png]]

![[../../img/Pasted image 20210305120755.png]]