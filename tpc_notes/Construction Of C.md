
#### Real And Imaginary Parts
$$
\Re(z) = \pi_{x}(z) \ evaluates \ = \frac{z + \bar{z}}{2}
$$
similarly 
$$
\Im(z)=\pi_{y}(z) \ evaluates \ = \frac{z - \bar{z}}{2}
$$
These satisfy the bounds
$$
\begin{matrix}
|\Re(z)| \leq |z| \\
|\Im(z)| \leq |z|
\end{matrix}
$$

From these we can prove the triangle inequalities 
$$
|z+w| \leq |z|+|w|
$$
and
$$
|z-w| \geq ||z| - |w||
$$
where mod outside is the one from R and inside from C. (they are consistent with each other anyways )

### Polar Representation

By graphing we see


![[Pasted image 20240104155450.jpg]]
$$
z =(x,y)= (|z|\cos \theta , |z|\sin \theta) = |z|(\cos \theta + i \sin \theta)
$$
where $\theta$ is an angle corresponding to z. Observe there are many possible angles, we call these arguments of z. But this value is unique when we restrict $\theta \in (-\pi,\pi]$ we call this $Arg(z)$. #pro We can see it's uniqueness bu visualising this region and seeing only one theta is possible as others require a full revolution which is prevented by the cut at $-\pi$ meaning you can never cross $-\pi.$

![[Pasted image 20240104160126.jpg]]

Actually it's completely possible to choose other intervals of Arg as long as a full revolution is covered with a cut eg $[0,2\pi),\left( \frac{\pi}{2} , \frac{5\pi}{2} \right]$ are also completely valid intervals but the one used in generally most acceptable. Infact it is best to leave Argz undefined as conflicting definitions may lead to mistakes.

#### Properties Of arguments
- if $\theta$ is an arg of z then $- \theta$ an angle from $\bar{z}.$
- if $\theta$ an arg of z then $-\theta$ an arg for $\frac{1}{z}$ #pro 
Observe $\frac{1}{z} = \frac{\bar{z}}{|z|^2}$ this implies $\frac{1}{z}$ and $\bar{z}$ have same arguments. Scaling doesn't change angle
- if $\theta,\omega$ arguments for $z,w$ respectively then $\theta + \omega$ is an argument for $zw.$

From here it follows when multiplying two complex numbers multiply their moduli and add arguments. This leads to

## De Moivere 
$$
(\cos \theta + i\sin \theta)^n = \cos n \theta + i \sin n \theta.
$$
For any $n \geq 0$ for $n \leq -1$ this also holds proof is trivial (by conjugation ).

This is most important and useful. For eg can derive triple angle formulas easily. Theoretically you can now do same for $n  \geq 4$

### Roots
we say z is an nth root of w iff
$$
z^n =w.
$$
In polar form we gave
$$
r^n CiS(\theta)^n = \rho CiS(\Phi)
$$
this is equivalent to by taking modulus
$$
r = \rho ^{1/n} , \ \theta = \frac{2\pi k}{n} + \frac{\Phi}{n}
$$
Note the first part is well defined as we can take n roots for non neg reals , and the second one is trivial. Observe all distinct values of theta are obtained for $0 \leq k \leq n-1$, giving exactly n distinct possibilities of theta implying 

*There are EXACTLY n nth roots of $\omega$ if it's non zero*

## Roots Of Unity

The n distinct roots of $1$ are called nth roots of unity. So these are
$$
\cos\left( \frac{2\pi k}{n} \right) +i\sin\left( \frac{2\pi k}{n} \right), k \in \{ 0,\dots,n-1 \}
$$

