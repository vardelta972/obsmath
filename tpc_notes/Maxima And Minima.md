Just Like [[IVT]] holds for [[continuous functions]] over [[Connected Set]], Maxima and Minima exist for [[continuous functions]] over [[Compact Set]].

### Proof Of The Maximum Principle
#pro Since [[continuous functions]] map [[Compact Set]] to [[Compact Set]], f(D) is compact. Now say it has no maximum then there is a strictly increasing unbounded sequence xn, this must diverge to infinity. This implies no subsequence converges a contradiction to [[Compact Set]].
##### Alternatively 
We show that $s = \sup_{x\in K} f(x)$ is attained by f. Observe 
$$
s-\frac{1}{n} < f(x_{n}) \leq s
$$
now xn has a convergent subsequence xnk due to compactness but continuity implies s is indeed attained.

# For Monotone Functions
![[Pasted image 20231228153008.jpg]]
Isn't this overly complicated 
## First Derivative Test

States if $f:(a,b) \to R$ has a local maxima/minima at c then $f'(c)=0.$
#pro -> we have $f'(c+) = \lim_{ x \to c^+} \frac{f(x)-f(c)}{x-c} \leq 0$ as we can just take the limit in the corresponding neighbourhood where c is the local maxima. Similarly  $f'(c-) = \lim_{ x \to c^-} \frac{f(x)-f(c)}{x-c} \geq 0$ . thus we are done.

# Second Derivative Test
Second derivative gives [[convexity]] , first derivative tells that we are at the required point on that convex/concave graph.

# Nth Order Derivative Test

# Without Second Order Derivative and higher

f'=0 and [[convexity]] are enough 
# Global Maxima And Minima

Bootstrap this through an example 
say $f(x)=\frac{x}{e^{nx}}$ then it intuitively has a maximum at 1/n . We show f has global max at 1/n . Consider a closed interval around 1/n then f has a max on it implies it must be 1/n since around any closed interval the same is true, 1/n is global max.

NOTE : make this more formal.
#### Multivariable version
