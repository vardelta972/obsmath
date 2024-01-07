
$$\forall x \in X \forall \epsilon >0 \exists \delta >0 \forall y \in D : |y-x|<\delta \implies |f(y)-f(x)|<\epsilon$$

If you bring the $\forall x \in X$ quantifier inside we get the def of uniform continuity$$ \forall \epsilon >0 \exists \delta >0 \forall x,y \in D : |y-x|<\delta \implies |f(y)-f(x)|<\epsilon$$
Basically if you want f(x),f(y) to be epsilon-close then there is a delta such that if two points x,y are delta close then we get the desired. Whereas in [[Continuity]] if you pick a point f(x) and you want f(y) to be epsilon close then there exists such a threshold delta which allows this. This is also defined for arbi metric spaces || gets replaced by d.

# Sequential Criterion
#ipro #pro Is equivalent to equivalent sequences are mapped to equivalent sequences.
 Say an bn are equivalent then $\forall \varepsilon >0 \exists N>0 \forall n \geq N : |x_{n}-y_{n}|<\delta.$ Then by continuity we get the result.
 Say that the epsilon criterion does not hold so that $\exists \varepsilon >0 \forall \delta >0 \exists x_{\delta},y_{\delta}:|x_{\delta}-y_{\delta}|<\delta \land |f(x_{\delta})-f(y_{\delta})|>\varepsilon.$ by [[axiom of choice]] [[ZFC Axioms#The Axiom Of Choice]] we get a seq $x_{n}-y_{n}$ converging to 0 but not for $f(x_{n})-f(y_{n}).$



## IMPORTANT FACT
They map [[cauchy sequences]] to [[cauchy sequences]]
#pro say an cauchy then after some N
$$
|a_{n}-a_{m}|< \delta \implies |f(a_{n}-f(a_{m})|< \varepsilon.
$$

They map bounded sets to bounded sets.
#mpro #ipro #pro Say some bounded set E has been mapped to an unbounded set f(E) , since f(E) is unbounded in reals WLOG we assume unbounded from above this gives us a sequence by [[axiom of choice]] $f(a_{n})$ that strictly increases to infinity, by [[bolzano]] weierstrass theorem we get a convergent subsequence $a_{k_{n}} \to L$. In particular akn is cauchy implying $f(a_{k_{n}})$ is also cauchy which is impossible.

### Compactness And Uniform Continuity
Turn out in general continuous functions over [[Compact Set]] are automatically uniformly continuous. #mpro #ipro #pro 
Say xn and yn are equivalent. By compactness we get their respective convergent subsequences $x_{k_{n}},y_{j_{n}}$ moreover they must converges to the same limit due to equivalence. Thus we get by continuity 
$$
d(f(x_{k_{n}}),f(y_{k_{n}})) \to 0
$$
But this implies by contradiction that
$$
d(f(x_{n} ),f(y_{n})) \to 0
$$
Done.

##### Example 
f(x,y) = exp(x)+exp(-y) on a closed disk is uniformly continuous.

### In Terms Of a limit
f is uniformly continuous iff
$$
\lim_{ \delta \to 0^+} \sup_{|x-y|<\delta} |f(x)-f(y)| =0
$$
Basically for x,y close enough f(x),f(y) are close.
#### Example
$|\cos(x)-\cos(y)| = 2|\sin\left( \frac{x+y}{2} \right)| |\sin\left( \frac{x-y}{2} \right)| \leq |x-y|$ this implies that the limit evaluates to 0, thus giving uniform continuity of cosine.
#### Proof Using The Limit Definition 
#mpro #ipro #pro We have
$$
\lim_{ N \to \infty } \sup_{i,j \geq N} |a_{i}-a_{j}| =0
$$
By uniform continuity we get
$$
\lim_{ N \to \infty } \sup_{|x-y|< \frac{1}{N} } |f(x)-f(y)|=0
$$
Now,
$$
\sup_{|a_{i}-a_{j}| < \frac{1}{N}} |f(a_{i})-f(a_{j})| \leq  \sup_{|x-y|< \frac{1}{N} } |f(x)-f(y)| \to 0
$$
Thus,
$$
\sup_{|a_{i}-a_{j}| < \frac{1}{N}} |f(a_{i})-f(a_{j})| \to 0
$$
as N goes to infinity.

since $\lim_{ N \to \infty } \sup_{i,j \geq N} |a_{i}-a_{j}|=0$ after some point M $|a_{i}-a_{j}| < \frac{1}{N}$. Thus we get
$$
\sup_{i,j \geq M(N)} |f(a_{i})-f(a_{j} )| \leq \sup_{|a_{i}-a_{j}| < \frac{1}{N}} |f(a_{i})-f(a_{j})|
$$
Now observe $\sup_{i,j \geq K} |f(a_{i})-f(a_{j})|$ does converge by [[MCT]] above we can form a subsequence of this one which goes to 0 by Squeezing this sequence also goes to 0 proving f(an) cauchy.