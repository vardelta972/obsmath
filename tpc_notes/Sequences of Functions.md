Well its a seq of functions with common domains and codomains so $f_{n} (x) = \frac{x^n}{n}$ where all are from R to R define a seq of functions with if we restrict one of them to (0,1) then they dont.

### Pointwise Convergence
We say $f_{n} \to f \iff \forall x : \lim_{ n \to \infty }f_{n}(x)=f(x).$ f: Metric Space X -> Metric Space Y.

## Uniform Convergence
We say $f_{n}\rightrightarrows f \iff \forall \varepsilon >0 \exists N >0 \forall n \geq N \forall x : |f_{n}(x)-f(x)|<\varepsilon$
i.e for any given $\varepsilon$ eventually the seq of func becomes $\varepsilon$close to f.

Its negation is
![[Pasted image 20231225172405.png]]

Uniform Convergence implies Pointwise convergence(easy to see).

# Must DO
![[Pasted image 20231225183537.png]]

### For Bounded Functions
![[Pasted image 20231225174317.png]]

Actually for bounded functions Uniform Convergence is equivalent to pointwise convergence.
#pro 
###### Examples:
![[Pasted image 20231225174959.png]]
For these, the limit theorems also hold #pro . But Not for unbounded ones see $f_{n}=x+\frac{1}{n}$ and it's square.
## Cauchy Criterion For Uniform Convergence
![[Pasted image 20231225175303.png]]
## Some interesting properties in this case
If fn converges to f uniformly ans each fn is continuous then f is also continuous.

-> Forall $\varepsilon>0$ choose a $\delta>0$ st forall x we have
$$
|x- x_{0}|<\delta \implies |f_{N+1}(x)-f_{N+1}(x_{0})|<\varepsilon
$$
where N is chosen such that forall $n \geq N$
we have forall x that $|f_{n}(x)-f(x)|<\varepsilon$
Then forall x in that delta neighbourhood we have
$$
|f(x)-f(x_{0})| \leq |f(x)-f_{N+1}(x)|+|f_{N+1}(x)-f(x_{0})| \leq |f(x)-f_{N+1}(x)|+|f_{N+1}(x) - f_{N+1}(x_{0})| +|f_{N+1}(x_{0}) - f(x_{0})| < 3 \varepsilon
$$

#### Behaviour With Integrability
Heres a very nice result handy for passing limits:

if fn are integrable functions converging uniformly to f, then f is also integrable with
$$
\int f \, =\lim_{ n \to \infty } \int f_{n} \,    
$$
#pro #ipro #mpro Uniform convergence gives us for large enough N
$$
f_{n} - \varepsilon \leq f \leq f_{n} + \varepsilon \implies \int _{L}f_{n} \, - \varepsilon(b-a) \leq \int _{L} \, f \leq \int_{U}f \, \leq \int _{U} f_{n} +\varepsilon(b-a) 
$$

Subtracting right side from the left gives us
$$
|\int _{U}f \, - \int _{L}f \,   | < 2\varepsilon(b-a)
$$
giving its existence. 

# Behaviour with [[differentiability]]

# It's continuous extension 

We can define this for a sequence indexed by R by just replacing N with an M in R.

It still retains good behaviour in this extended definition.