$S \subseteq X$ where X metric space, is called compact iff every seq in S has a subseq convergent in S(basically general [[bolzano]] weirstrass). So R is not compact.

### Examples: Closed intervals in R are compact(see [[Bolzano]] and [[Closed Sets]]). Closed and bounded sets in R^n are compact(see below)

# Topological Notion

S is compact iff every open cover of it has a finite subcover. The two notions are not necessarily equivalent in [[topological spaces]] but are in metric spaces.


# Heine-Borel Theorem
E in Rn is compact iff it is closed and bounded. This may not be true for metric space but works when it is complete see [[Complete Metric Spaces]]
#pro -> for E nonempty.First we show that it is bounded. Say it is unbounded then there exists a sequence xn such that xn is in E but is any term xn is outside the ball $B_{n}(c)$ compactness implies this has a subsequence converging in E. But observe that

$$
d(x_{n+1},x_{n})\geq 1
$$
this is inherited by its subsequence which implies that this subsequence cannot be cauchy. But since we are working in a complete space we get that this subsequence cannot converge.
From here the closedness follows trivially.

<- Taking any sequence in E all of its components are bounded, this gives us a convergent subsequence whose index function at j is the maximum of all component index functions at j which by closedness converges in E.

### Totally Bounded Sets
S is totally bounded iff given any sized ball we can cover S with finite amount of them.

# Equivalents In Metric Spaces


![[Pasted image 20240104075712.jpg]]
#mpro #ipro #pro 
1 -> 2 Consider the covering
$$
A = \{ B_{\varepsilon} (c) : c \in X \}
$$
then this has finite subcover which has finitely many epsilon balls, since these cover the space X we have that each $a_{n} \in B_{\varepsilon} (c_{m}), \exists m.$ Consider any ball $B_{\varepsilon}(h)$ which has infinitely many terms of $a_{n}$ say these are $a_{k_{1}},a_{k_{2}},\dots$ where kn are increasing. Then we have
$$
d(a_{k_{n}},h) < \varepsilon
$$

which gives the result.

2 <-> 3 Proof is literally the same as [[Cauchy Sequences#Completeness]].

3 -> 1 We can cover the space with finitely many $\varepsilon$ balls for any $\varepsilon >0$ we choose $\varepsilon$ small enough so that each $B_{\varepsilon} (a_{n})$ is contained in some open set $U_{n}$. Then this gives us our finite subcover.  Justification:
say for all $\varepsilon>0$ some ball $B_{\varepsilon} (a_{n})$ is not contained in any of the open sets. But since $a_{n} \in U_{n}, \exists n$ this implies an is an interior point of Un giving us a contradiction.


### An Important Result
[[Continuous functions]] map compact sets to compact sets.