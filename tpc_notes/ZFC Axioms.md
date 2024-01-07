
### Extensionality
Two sets equal iff they have same members.

### Specification
If A is a set and P(x) a predicate then there exists a set B whose only members are those in A that satisfy P. By extensionality this B is unique and denoted by $$\lbrace x \in A : P(x) \rbrace.$$
### Existence
There exists a set. Combining this with specification gives us the set $\lbrace x \in S : x \neq x \rbrace .$ Its easy to see this has no members, we call this the empty set $\emptyset$ (its unique cuz of uniqueness of specification).

### Pairing
Given sets a,b the [[Class]] $\lbrace x : x=a \lor x=b \rbrace$ is a set.(unique by extensionality) One of it's consequences is the existence of singletons(proof: )

### Union
Given a set X there is a set $$\bigcup X$$ whose members are only those who are in atleast one of j, where $j \in X.$ For Intersections see #imp [[Construction Of Intersections]]

### Power Set

Given a set, there exists a set of all its subsets.

### Infinity

There exists atleast one [[inductive set]]. Using this we can give a [[Set Theoretic Construction Of Naturals]].
## Replacement
If $\phi(x,y)$ is a formula and A a set such that forall x in A there is atmost 1 y for which $\phi(x,y)$ holds then 
$$
\{ z : \exists x \in A (\phi(x,z)) \}
$$
is a set.

### The Axiom Of Choice

States if you have an indexed collection of sets $\lbrace A_j \rbrace_{j \in J}$ then it is possible to choose one element from each set in the sense that there exists a function mapping J to $\cup A_j$ so that $f(j)\in A_j$. In particular this allows us to create sequence as in these proofs: .

Also if J is finite then it's called finite choice which is provable from other [[Axioms]], however Choice itsef is independent.
