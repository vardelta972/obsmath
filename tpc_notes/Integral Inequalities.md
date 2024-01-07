The most important one

$$
m|I|\leq \int_I \leq M|I|
$$
#pro 
![[Pasted image 20231230205422.jpg]]


![[Pasted image 20231230205453.jpg]]
## [[Jensen]]'s Inequality For Integrals
States for convex&continuous phi and integrable f
$$
\phi\left( \frac{1}{|I|} \int_{I} f(x) \, dx  \right) \leq \frac{1}{|I|} \int_{I} \phi(f(x)) \, dx 
$$
This reverses for concave functions.
proof, this follows directly from Jensen.

## Cauchy Swarchz
$$
f \cdot g \leq \lvert f \rvert \lvert g \rvert  
$$

## Triangle Inequality 

$$
|\int f \, dx | \leq \int |f| \, dx 
$$

## Minkowski Inequality 

basically triangle inequality but for lp norms.
$$
\left\lvert  \int f +g \, dx   \right\rvert _{p} \leq |\int f \, dx |_{p} \, + |\int g \, dx |_{p}
$$
. notice the case p=2. This and the previous ones are proven from their discrete counterparts.

# Holder's Inequality 
States if $\frac{1}{p}+\frac{1}{q}=1$ and p,q>0 then for f,g positive 

$$
 f \cdot g = \int fg \, dx \leq \lvert f \rvert _{p} \lvert g \rvert _{q}.
$$
see [[Norms And Inner Products]]