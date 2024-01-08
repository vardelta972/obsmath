Questions Are From Kaczor 
We define
$$
\omega _{V} f := \sup_{x \in V} f(x) - \inf _{x \in V} f(x).
$$
whenever it exists ofcourse. This is defined for functions mapping [[Topological Spaces]] to R.

## Relation With Continuity 

We have the relation f is cont at c iff
$$
\forall \varepsilon >0 \exists V(c) : | \omega _{V(c)}f | < \varepsilon
$$
#pro <- for any $\varepsilon>0$ we choose a $\delta>0$ so that
$$
\sup_{\delta} f - \inf_{\delta} f <\varepsilon
$$
but 
$$
|f(x)-f(c)| \leq |\sup_{\delta} f - \inf_{\delta} f| = \sup_{\delta} f - \inf_{\delta} f <\varepsilon
$$
forall x in $V_{\delta}$.
-> for any $\varepsilon>0$ we choose a $\delta>0$ so that
$$
|x-c| < \delta \implies |f(x)-f(c)|  <\varepsilon
$$
observe that $\sup_{\delta} f - \inf_{\delta} f$ maximises $|f(x)-f(y)|$ in this delta neighbourhood, thus we may have
$$
\sup_{\delta} f - \inf_{\delta} f < \varepsilon
$$
#unrigorous

It also is related to [[LimeSoup]] for functions.

### Relation With [[Limits]]
We have $\lim_{ x \to c }f(x)=L$ iff
$$
\forall \varepsilon>0 \exists \bar{V}(c):|\omega_{\bar{V}(c)}f| < \varepsilon
$$
where V bar indicates deleted neighbourhood.
#pro 