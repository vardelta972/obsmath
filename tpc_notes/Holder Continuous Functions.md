f is called $\alpha$ Holder Continuous iff 
$$
\exists C\geq 0 \forall x,y:d(f(x),f(y)) \leq Cd(x,y)^\alpha
$$

These are automatically continuous. 
Turns out that if $\alpha >1$ for real valued ones then f must be constant so the real stuff happens at $0 \leq \alpha \leq 1$ , all Holder [[continuous functions]] are also [[uniformly continuous]]. These are not necessarily differentiable.

#mpro #ipro #pro Proof of 2: Just take 
$$
\delta = \left( \frac{\varepsilon}{C} \right)^{1/\alpha}
$$
Proof of 1: Say $\alpha >1$ then we have 
$$
\lim_{ y \to x } | \frac{f(x)-f(y)}{x-y} | \leq \lim_{ x \to y} C |x-y|^{\alpha-1} =0
$$
Thus f is differentiable with derivative 0 thus constant.