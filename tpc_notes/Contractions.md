A function between metric spaces is contractive iff
$$
\exists c \in(0,1) \forall x,y (d(f(x),f(y)) \leq cd(x,y))
$$
These basically contract spaces some examples are x/2, $\sqrt{ x }$ on $[1,\infty]$.

# The Contraction Mapping Theorem

First we have the fact that contractions can have atmost one fixed point and that they are continuous. Very easily proven. 

When the space is complete they have exactly one fixed point which can be constructed as follows 
take $x_{1}=$some point in the domain
$x_{n+1}=f(x_{n})$. #mpro #ipro #pro 

It suffices to show xn is cauchy as X is complete. This is done as shown in this picture:

Now since contractions are automatically continuous we get L=f(L).

## Contractions And Derivatives
If $|f'|<1$ and $f'$ continuous then f is a contraction on $[a,b]$. #mpro #ipro #pro 

-> f' has a maximum on $[a,b]$ say f(c) then
$$
|\frac{f(x)-f(y)}{x-y}| = |f'(c_{xy})| \leq |f'(c)| <1
$$

#### Examples:
$f(x)=\cos(x), x \in [0, \frac{\pi}{4}]$ is a contraction thus the sequence $\cos\left( \cos\left( \dots\left( \frac{1}{2} \right) \right) \right)$ converges to fixed point of cos(x).