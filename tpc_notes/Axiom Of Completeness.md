states that every nonempty subset of R bounded above has a least upper bound. Can be rephrased in terms of lower bounds.

$$\displaylines{\forall \emptyset \neq U \subseteq R : \exists upperbound(U): \exists lub(U) \\ \iff \forall \emptyset \neq L \subseteq R : \exists lowerbound(U): \exists glb(U)}$$

Turns out these lub and glb's are unique wherever they exist (see proof: ) and are denoted $sup(U),inf(L)$ respectively. See [[Sup And Inf]]. Plays Important role in proof of [[MCT]] and [[IVT]]

### Equivalent Forms

#### Cauchy Form
It's equivalent to saying every cauchy sequence in R converges. #mpro #ipro #pro 
-> The usual progression in books.
<- yet to be done later.

##### IVT
It's equivalent to [[IVT]] in the case of reals. 
#pro Forward implication is in [[IVT#Proof In The Case Of Reals Using Axiom Of Completeness]].
For the other direction: this uses many ideas such as [[Ancient Bisection Method]] possibly Best proof i have ever done myself.

<- Let S be a non empty subset of R bounded from above, if it were a singleton then we are automatically through. if it has atleast two elements, We pick a j in S then define
$$
D = S \setminus \{ k \in S : k \leq j \}
$$
Then our problem becomes showing D has a least upper bound(btw D is bounded from below now by j). Pick any continuous surjective function
$$
f : [a,b] \to [j,u]
$$
Now observe each $h \in D$ can be written as $f(\varepsilon_{h})$ for some real number $\varepsilon_{h}$. Now the bisection process starts, we take $[j,u]$ split it into two, the left one is half open from right and the right one is fully closed. We pick the right one from this splitting if some $f(\varepsilon_{h}) \geq u$ otherwise choose the left one. We continue doing this process indefinitely. Then we basically have a sequence of infinitely nested intervals $[a_{n},b_{n}]$ . By [[Nested Intervals Property]] (which follows from Axiom Of Completeness)
we get
$$
\bigcap [a_{n},b_{n}] = \{ s \}, \exists s 
$$
This is a singleton as length of those intervals goes to 0(this was proven in [[Nested Intervals Property#Special Case]]). 

Now we claim that s is infact the lowest upper bound for D.  
say $s<f(\varepsilon_{h}),\exists \varepsilon_{h}$ then we would eventually come at a step in the bisection process where in $[a_{k}, \frac{a_{k}+b_{k}}{2  } ) \cup [ \frac{a_{k}+b_{k}}{2},b_{k}]$ s falls in the left set but $f(\varepsilon_{h})$ falls in the right one , thus the right set is chosen and all further sets are subsets of this one but this implies that s cannot be in the intersection, a contradiction.
Using similar argument we show s is the least upper bound. Say a upper bound $l<s$ exists then eventually at some step l falls in the left set and s in the right. But s falling in the right set implies some $f(\varepsilon_{h}) >l$ a contradiction.

This finally completes the proof.
Can this falling into left/right sets be made rigorous?

##### Nested Intervals Property+[[Archemedian Property]] 
OR we can just replace the above sum of statements by [[Nested Intervals Property#Special Case]].

-> We do the same thing again, pick something in S use it to remove the lower unbounded part then consider the interval $[j,u]$ apply the bisection method then by Nested Intervals Property their intersection non-empty and the length of intervals tend to 0(showing this required Archemedian) thus intersection has exactly 1 element, argue the this element is the supremum as follows:

If it were not the upper bound then it would fall in a left set in some step and some actual element of D may fall in the right set giving a contradiction.
Similary if $l<s$ were the least upper bound then sometime l would fall in left implying l< some element of D.