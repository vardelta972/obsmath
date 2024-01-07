Taylors theorem states $f(x)=T_n(x)+R_{n+1}(x).\forall x$ [[Taylor's Theorem]] sometimes we may get  for some values of x
$$
|f(x)-T_n(x)|=|R_{n+1}(x)|  \to 0
$$
often due to [[Bounds For Taylor Remainder]]
Then we get $\lim T_n (x)=f(x)$ for those x.
So basically we get the series expansion 

$$
f(x)= \sum_{n=0}^{\infty} \frac{f^{[n]}(x_0)(x-x_0)^n}{n!}
$$
for those values of x.

# Convergence Comments



### Examples: 
#pro exp is it's own derivative so Rn is just a ratio of a power by a factor for each x, thus Rn goes to 0. Giving the famous result
$$
\exp(x)=\sum \frac{x^n}{n!}.
$$
where we center around 0.