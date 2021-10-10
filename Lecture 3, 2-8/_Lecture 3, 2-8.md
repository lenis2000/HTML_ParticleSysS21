[[Problems, 2-8|6 problems + T1]], due 2/22

# 1 Leftovers from the previous lecture

- 1.1 [[../Lecture 2, 2-3/2.4 Some other particle systems#Coloured TASEP|Coloured TASEP]] and answer [[../Lecture 2, 2-3/Problems, 2-3#?|to the question about the limiting behaviour of the second class particle]], without proof. Here is the [[1.1 TASEP second-class particle asymptotics|answer]].
- 1.2 [[../Lecture 2, 2-3/2.4 Some other particle systems#q-TASEP|q-TASEP]] and [[Problems, 2-8#1|problem of its existence]]

# 2 TASEP and Last Passage Percolation

- [[2.1 Height function]]
- [[2.2 Random interface growth]]
- [[2.3 Percolation times]]
- [[2.4 Point-to-point directed LPP]]
- [[2.5 Other environment weights]]

# 3 Subadditive ergodic theory and limit shape

- [[3.1 Subadditivity in LPP]]
- [[3.2 Limit in expectation]]
- [[3.3 Subadditive ergodic theorem]]

We also discussed applications of the subadditive ergodic theorem to the last-passage percolation limit shape, but I am going to repeat this in the next lecture.

# Notes and references

1. The uniform limit law of the second class particle extends to arbitrary product measures with densities $\rho$ to the left of the origin and $\lambda$ to the right of the origin, where $\rho>\lambda$ (then the segment on which the uniform distribution lives should be suitably modified). There are many papers discussing second class particles, and several beautiful exact couplings available, including:
	1. ```P. A. Ferrari. Shock fluctuations in asymmetric simple exclusion. Probab. Theory Related Fields, 91(1), 1992```.
	2. ```P. A. Ferrari and C. Kipnis. Second class particles in the rarefaction fan. Ann. Inst. H. Poincar ́e Probab. Statist., 31(1), 1995```.
	3. ```P. A. Ferrari and L. P. R. Pimentel. Competition interfaces and second class particles. Ann. Probab., 33(4), 2005```.
	4. ```O. Angel, A. Holroyd, and D. Romik. The oriented swap process. Annals of Probability, 37(5):1970–1998, 2009```.
2. Subadditive ergodic theorem is originally due to Kingman
	1. ```J. F. C. KINGMAN, The Ergodic Theory of Subadditive Stochastic Processes, J. Roy. Statist. Soc. Ser., Vol. B30, 1968, pp. 499-510```. 
	2. ```J. F. C. KINGMAN, Subadditive Ergodic Theory, Ann. Probability, Vol. 1, 1973, pp. 883-909```. 
	3. ```J. F. C. KINGMAN, Subadditive Processes, Lecture Notes in Math., Vol. 539, 1976, pp. 167-223```.
	4. See also ```J. MICHAEL STEELE. Kingman’s subadditive ergodic theorem Annales de l’I. H. P., section B, tome 25, no 1 (1989), p. 93-98``` ([link](http://www-stat.wharton.upenn.edu/~steele/Publications/PDF/Steele_AIHPB_1989.pdf)) for a proof.
3. The proofs of the limit shape results were done without a careful exploration of integer parts. In particular, note that the subadditive ergodic theorem holds for sequences. Therefore, one has to extend the function $\ell$ from integer/rational points to all points. This exercise is done with great care in [Seppalainen's lecture notes](https://www.math.wisc.edu/~seppalai/cornergrowth-book/ajo.pdf), Theorem 2.1.
4. First-passage (undirected) percolation is a subject of intense study, too. See, for example, the [survey](https://arxiv.org/abs/1511.03262) ```Antonio Auffinger, Michael Damron, Jack Hanson. 50 years of first passage percolation```.