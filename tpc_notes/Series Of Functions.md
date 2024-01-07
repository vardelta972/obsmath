# Pointwise Convergence 
Can be done by normal ways or [[Taylor Series]]
# Uniform Convergence 
![[Pasted image 20231224102037.jpg]]

# Important Results
There are direct consequences of theorems from [[Series Of Functions]]

If $\sum f_{n}$ converges uniformly to f and each fn is continuous then so is f.
#pro Just NTS $\sum f_{n}$ is continuous for each n which is another consequence of [[Sequences of Functions]]

If $\sum f_{n}$ converges uniformly to f and each fn is integrable then f is integrable with $\sum \int f_{n} \,$ as its value. (Rewrite after practice )

#### Examples:
Observe
$$
\sum \frac{t^n}{n!}
$$
converges uniformly on $[0,x]$ by weierstrass M test, thus it converges uniformly to exp(x) on each $[0,x].$ Thus 
$$
\sum \int _{[0,x]} \frac{t^n}{n!} \, = \exp -1
$$

is the value of $\int_{[0,x]} \exp \,$

# Uniform Convergence Of [[Taylor Series]]
Can be established using The Weierstrass M Test On the series itself then using unqiueness of uniform [[limits]].



## Weierstrass M-Test
Literally the comparison test but for uniform convergence.

States if each fn is bounded by Mn and the series of Mn converges then series of fn converges uniformly.
#pro We use Cauchy Criterion For Uniform Convergence Of Series. Everything follows from the inequality
$$
|\sum_{j=n}^{m} f_{j} | \leq \sum _{j=n}^m M_{j}
$$

IMPORTANT EACH fn can have different bounds depending on n.