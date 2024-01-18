In a metric space X, an is cauchy iff
$$
\forall \varepsilon >0 \exists N \ge 0 \forall n,m \geq N : |a_{n}-b_{m}|<\varepsilon.
$$

ie distance bw any two terms of the sequence can be made small if you go far enough into the sequence.

### In terms of a limit 
an is cauchy iff 
$$
\lim_{ N \to \infty } \sup_{i,j \geq N} |a_{i}-a_{j}| =0
$$
Basically for N large enough distance betwenn any teo members of the sequence is small.

## Completeness
R is complete.
#pro Cauchy Implies Comvergence ->
If xn is cauchy then it's bounded implying the existence of a subsequence $x_{k_{n}}$ which converges to some limit L. Now forall $\varepsilon>0$ exists N such that
$$
\forall n,m \geq N (|a_{n}-a_{m}|<\varepsilon)
$$
and 
$$
\forall n \geq N (|a_{k_{n}}-L|<\varepsilon)
$$
thus we get forall $n \geq N$
