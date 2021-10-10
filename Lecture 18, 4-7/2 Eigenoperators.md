#### 2.0.1 Recall the Schur case

![[../img/Pasted image 20210407212049.png]]

#### Definition 2.0.2. First Macdonald operator

![[../img/Pasted image 20210407212104.png]]

This operator is a member of a whole family of $N$ commuting operators, which form a "quantum integrable system"

#### Theorem 2.0.3. Eigenrelation

![[../img/Pasted image 20210407212153.png]]

The same eigenrelation holds for the other polynomials $F_\lambda,Q_\lambda,Q_\lambda^*$, since they are all proportional to each other, and the multiplicative constants are independent of the variables $x_j$.

#### Proof 2.0.3. Step 1.

![[../img/Pasted image 20210407212314.png]]

See also [[../Lecture 17, 4-5/Problems, 4-5#1|Problem 1]] from the previous lecture.

#### Proof 2.0.3. Step 2.

![[../img/Pasted image 20210407212353.png]]

![[../img/Pasted image 20210407212403.png]]

In words, we have split the $F_\lambda$ polynomial into three pieces. In the first piece, the operator $T_{0,x_i}$ eliminates all the variables. The third piece is a constant thanks to the symmetrization identity ([[../Lecture 17, 4-5/Problems, 4-5#2|Problem 2]] from the previous lecture). In the second piece, the action of $D(t,0)$ removes one of the factors and then restores it back. So we see that the overall action of $D(t,0)$ on $F_\lambda$ is diagonal and produces the same eigenvalue as if we applied $D(t,0)$ in $N-\ell$ variables to a constant. This produces the eigenvalue $(1-t^{N-\ell})/(1-t)$.
