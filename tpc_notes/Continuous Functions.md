## Topological Notion

$f:X \to Y$ is continuous iff preimage of open sets are open. This is equivalent to #pro #ipro #mpro preimages of [[closed sets]] are closed. -> Say $C \subseteq Y$ is closed then its complement is open implying $f^{-1}(C^c)$ is also open implying 
$$
f^{-1} (C) = f^{-1}(C^c)^c 
$$
is closed.


#### In First Countable Spaces

### In Metric Spaces
f is cont at x0 iff #pro $$\forall \varepsilon > 0 \exists \delta  > 0 \forall x \in X : d(x,x_{0})<\delta \to  d(f(x),f(x_{0}))<\varepsilon.$$


Which is equivalent to the topological description of continuity ie 

![[Pasted image 20240109195354.png]]
these are equivalent #mpro #ipro #pro 

Open Set Criterion) Sequential -> Open
Say for contradiction $f^{-1}(V)$ is not open for some open set V in Y. Then for some point $c$ all neighbourhoods of the form $B_{\frac{1}{n}}(c)$ have something say $x_{n}$ not contained in $f^{-1}(V)$ then clearly $x_{n} \to c.$ But sequential continuity implies $f(x_{n}) \to f(c)$ but $f(x_{n}) \not\in V$ and $f(c) \in V$ this implies that all neighbourhoods around f(c) have some term outside V, a contradiction to its openess.
Open -> Sequential) 

Open -> Closed)


#### Examples
Norm is a continuous function by reverse triangle inequality 

# Behaviour With Boundedness

Conpactness ke saath chakkar hai (Heine Boral) complete metric space and totally bounded