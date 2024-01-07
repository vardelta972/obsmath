We define $$\ln(x) := \int_{1}^{x} \frac{dt}{t}, x>0.$$ Then the fundamental properties $$ln(xy)=ln(x)+ln(y)$$ $$ln(\frac{1}{x})=-ln(x)$$ follow directly from properties of integrals. [[]]

## Construction of exp(x)
NTS $\ln(x)$ is invertible. Since ln is continuous by [[FTC]] , we only need to show its strictly monotone and try to use [[IVT]] for surjectivity. 

#### Monotonocity:

if x> y then $$\int_{y}^{x} \frac{dt}{t} >0$$ as otherwise $\frac{1}{t} = 0$ for all $t \in [y,x].$ This gives monotonicity.

#### [[IVT]]: 


From here we get the existence of $\exp(x)$ as inverse of the logarithm. Its strictly inc property follows from that of the logarithm[[]]. And by [[Inverse Function Theorem]] as ln is a regular function $\exp$ is differentiable with $\exp' =\exp.$ [[]]   

## The Complex Exponential

We define
$$
\exp(z) = e^x Cis(y)
$$
Observe it's fully consistent with exp for reals.
By [[Cauchy Riemann Condition]] its [[complex differentiable]] thus analytic. Infact it's derivative is $\exp(z)$ itself #pro 