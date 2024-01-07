states if your function is continuous then it obtains all values between any two given values of func. In reals it's equivalent to [[Axiom Of Completeness]]
More formally: If f is continuous on a connected domain(see [[Connected Set]]) then it has the [[IVP]]

Useful for showing surjectivity.

# Existance Of nth Roots
This can be done using IVT given any $x \geq 0$ just find an M so that $x \leq M^n$ then define 
$f(x)=x^n, x \in [0,M]$ then as f is continuous and $[0,M^n]$ is in it's image this x must be attained somewhere which we call $x^{1/n}$

### Proof of IVT
#pro 
Since [[continuous functions]] map [[Connected Set]] to [[Connected Set]] for any $f(a)\leq y \leq f(b)$ we must have $y \in f[D]$. because 

#### Proof In The Case Of Reals Using [[Axiom Of Completeness]]
#pro #mpro #ipro Given any $f(a) < y < f(b)$ consider 
$$
L = \{ f(x) : f(x) <y \}
$$
$$
R = \{ f(x) : f(x) > y \}
$$
Then observe both SupL and InfR exist. We claim that they are equal. This is pretty easy to prove and is left as an exercise (show each memeber is corresponding bound for memebers of other set)to the reader, this immediately implies by a bounding argument that y=supL=infR. Now we produce a sequence $f(x_{n})\to y$ in L this is done by squeezing, then [[Bolzano]] gives is a subsequence $x_{k_{j}} \to c$ then by continuity 
$$
f(x_{k_{n}}) \to f(c)=y
$$
This completes the proof.

#### Proof Using The [[Ancient Bisection Method]]
## Mahatvapurn Example:
Consider $\sin\left( \frac{1}{x} \right), x \in (0, \frac{1}{2\pi})$ then it's image is $[-1,1]$ thus IVT still applies and all values in this closed interval are obtained.Possible due to the connectedness of $\left( 0, \frac{1}{2\pi} \right)$.