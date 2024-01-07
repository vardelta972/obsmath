## Properties Of Cardinality
- If $B$ is at most countable then any subset A is at most countable. #pro Fetch me thy sequence consisting of only elements from B wyth all of them appearing and appearing only once. We construct a sequence an as follows if A non empty 
$$
a_{1} = b_{min \{ j : b_{j} \in A \}}; a_{n+1} = b_{min \{ j : b_{j} \in A/ \cup_{1 \leq k <n+1} a_{k} \}}.
$$
Then this works.


A consequence of this is if a subset is uncountable then so is the whole set.

- f(N) is always atmost countable(images of countable sets is countable)
#pro We first consider the sequence an=f(n) then we start removing terms starting from second index as follows an is removed iff it appeared before in the sequence. Then this process produces a sequence which gives the bijection. As, every term that appears only once(by cont) and every member of f(N) still remains in the sequence(by cont and [[Principle Of Infinite Descent]], we get a sequence of indices in infinite descent).


- Finite Union Of Countable Sets is countable 
#pro We just need to prove this for two sets A,B we get sequences encoding them as an,bn we consider their 'product' abn where we have
$$
a_{1},b_{1},\dots.
$$
This successfully encodes their union in the required way.

An immediate consequence is that Z is countable.

- Countable Union Of Countable Sets is still countable 
#pro This uses [[ZFC Axioms#The Axiom Of Choice]]

A consequence of this is that finite cross product of countable sets is still countable. Which implies Q is countable. As if Z is countable then so is it's quotient

- X is infinite iff there exists a proper subset Y of X with same cardinality.
#pro <- This is never possible when X is finite obviously.
-> This uses [[ZFC Axioms#The Axiom Of Choice]]. 

- X is atmost countable iff there is an injection from X to N.
#pro 

### Cantor's Theorem
States cardinality of $2^X$ is strictly greater than X. #pro 
The mapping $x \to \{ x \}$ defines an injective mapping which does the job.

From here it immediately follows that $2^N$ is uncountable.

# Proofs Of R is Uncountable 

### By TTao

### By Cantor