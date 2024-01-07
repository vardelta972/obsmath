Very Motivational Theorem states if $\varepsilon >0$ and $y$ is any real number then epsilon can keep improving itself discretely to surpass y someday, i.e.
$$
\exists N \in Z (N \varepsilon > y)
$$

#pro Basically we need to prove $\frac{y}{N}$ can be made as small as we want if we have control over N. Well just pick $N = \left\lceil  \frac{y}{\varepsilon}  \right\rceil + 1.$ Then it works. ([[Axiom Of Completeness]] is indriectly involved in this proof as it's used to prove the existance of floor and ceiling functions.)
#### Proof Using IVT

