A space is complete iff every cauchy sequence there converges.

## Completion Precedure
There is a general procedure for completion of a metric space X. We define $\bar{X}=XC\≈$ where XC is the set of all [[cauchy sequences]] in X and
$$
a_{n} ≈ b_{n} \iff \lim_{ n \to \infty } d(a_{n},b_{n} )=0.
$$
with metric
$$
d(X,Y)=\lim_{ n \to \infty } d(x_{n} ,y_{n})
$$
where xn and yn are any cauchy seq from X and Y respectively, the choice does not infact matter.

We can interpret x in X as an [[equivalence class]] of sequences converging to x. This new space is complete. #mpro #ipro #pro 

This uses a [[Diagonalization Argument]]. Say $X_{n} \in \bar{X}$ is a cauchy sequence. We can write
$X_{n}=[x_{n}]$. Where xn is a cauchy sequence in X. Cauchyness of Xn implies 
$$
\forall \varepsilon >0 \exists N>0 \forall n,m \geq N : d(X_{n},X_{m}) < \varepsilon \iff \lim_{ k \to \infty }  d(x^n _{k},x^m _{k}) < \varepsilon 
$$

Since for each n $x^n _k$ is cauchy we have forall $\varepsilon >0$ there exists $N_{\varepsilon} >0$ such that forall $k,j \geq N_{\varepsilon}$ we have
$$
d(x^n _{k},x^n _{j}) < \varepsilon
$$
We create a new sequence here by setting $\varepsilon = \frac{1}{n}$ then there exists $K_{n}$ such that forall $k \geq K_{n}$ 
$$
d(x^n _{k}, x^n _{n}) < \frac{1}{n}.
$$
This is the diagonalization part. Now our candidate is $Y=x^n _n.$ Then 
$$
d(X_{n},Y) = \lim_{ k \to \infty } d(x^n _{k},x^n _{n})
$$
Now we have for each n we get for large enough k $d(x^n _{k},x^n _{n})< 1/n$ since we are talking about [[limits]] we get
$$
\lim_{ k \to \infty }d(x^n _{k},x^n _{n}) \leq \frac{1}{n}.
$$
Now we can squeeze to get $X_{n} \to Y.$