### P1: PT Rn is [[Hausdorff Space]]
-> Given two distinct points x,y. Consider balls around both of them with radius less than half the distance between them. If they have a common point u then we must have $$
d(x,y)=d(x,u)+d(u,y).$$ But we have $$d(x,u)+d(u,y)<d(x,y).$$.

### P2: Power set topologies give rise to hausdorff spaces

-> If X contains less than 2 objects then its vacously true. Say X has atleast 2 ele then for any x,y \in X x,y qualify as neighbourhoods of their respective sets. Since they are assumed to be distinct we are done.

### P3: Rn is second countable.

-> Consider $B :=$ All balls centered at rational coordinates with rational radii. Then for every U in Rn for each rational $x \in U$ there is a ball $B_{\epsilon}(x) \subseteq U.$ Now for each such $\epsilon$ we find any $0<r<\epsilon.$ then $$U = \bigcup_{x \in U} B_{r}(x).$$ Note that epsilon,r depend on x, but we choose to not indicate here.

### #imp P4: If $c \in X$ and $f_n : X \to X$ are functions for $n \geq 2$ then there exists a unique sequence in X $a_n$ such that $$a_1 =c, \forall n \geq 1 : a_{n+1}=f_{n+1}(a_n).$$ -> SKIPPED

### P5: Total order implies trichotomy

-> given x,y \in X if x \neq y then either x< y or y > x, otherwise x=y. So atleast one holds. If x=y then obv. x<>y cannot hold , if x< y then x=y cannot hold and x > y cannot hold as it would imply x=y. Similarly forr x > y.


#imp #vimp
### P6: prove [[Closed Sets#In Metric Spaces]] 

-> Say a seq in A conv to x \in Ac. Then there is a neighbourhood around x contained in Ac, but due to convergence this contains terms from A.

<- Say Ac is not open then for some $x \in A^c$ forall neighbourhoods $N(x)$ we have some $x \in N(x)$ is also in A. By considering balls we get a seq $x_n \to x,$ where $x_n \in A.$ Then we must have $x \in A.$ 

### P7: f is integrable iff there exists a seq of partitions Pn st $||P_n|| \to 0$ and $U(f,P_n)-L(f,P_n) \to 0.$

-> for $\epsilon_n := \frac{1}{n} > 0 \exists P_n : U(f,P_n)-L(f,P_n) < \frac{1}{n}.$ Then this sequence of partitions works. (might see [[ZFC Axioms#The Axiom Of Choice]]).

<- let $\epsilon >0$ then $\exists N>0$ such that $U(f,P_N)-L(f,P_N) < \epsilon.$

### P8: States if $[a_n,b_n]$ are nested so that $a_n$ increases and $b_n$ decreases then their intersection is always nonempty.
#imp 
-> Observe that $b_1$ is an ub for $a_n$ by induction on n. Thus by [[MCT]] $a_n \to L=sup(a_n).$ Similarly $b_n \to inf(b_n)=M.$ Now $$a_n \leq L \leq M \leq b_n$$ by order limit theorem and properties of sup and inf. 

### P9: if the length of subintervals goes to 0 then intersection has exactly one element.
#mimp #imp #vimp 

-> In this case L=M. So any x is intersection has to be equal to L by squeeze.

### P10: Prove [[MCT]] for increasing sequences.

-> forall $\epsilon > 0$ observe $sup - \epsilon < a_k, \exists k.$ Now forall $n \geq k:$ $$sup - \epsilon<a_k \leq a_n < sup + \epsilon.$$

### P11: PT Cantor Set is uncountable
#mimp #vimp #imp 
-> We do this by creating a bijection bw $\mathcal{C}$ and the set of all binary sequences(which is uncountable proof:[[16 DEC TST#P12 Let S be the set consisting of all sequences of 0’s and 1’s. Observe that S is not a particular sequence, but rather a large set whose ele- ments are sequences; namely, S = {(a1, a2, a3, . . .) an = 0 or 1}. As an example, the sequence (1, 0, 1, 0, 1, 0, 1, 0, . . .) is an element of S, as is the sequence (1, 1, 1, 1, 1, 1, . . .). Give a rigorous argument showing that S is uncountable.]]) given $c \in \mathcal{C}$ we encode its address as follows a1 = 0 if it fell to the left set in C1 , 1 if in the right. an+1 = 0 if it fell to the left set in n+1st setp, 1 if in the right. This encoding gives the bijection. 

### P12: Let S be the set consisting of all sequences of 0’s and 1’s. Observe that S is not a particular sequence, but rather a large set whose ele- ments are sequences; namely, S = {(a1, a2, a3, . . .) : an = 0 or 1}. As an example, the sequence (1, 0, 1, 0, 1, 0, 1, 0, . . .) is an element of S, as is the sequence (1, 1, 1, 1, 1, 1, . . .). Give a rigorous argument showing that S is uncountable.
#mimp #vimp #imp 

->Say that it is countable arrange it as (A1,.....) construct B as follows B_1 = 1st term of A1, B_n+1 = first term of A_n+1 which makes it distinct from A_n (possible as all terms in the seq distinct and [[well ordering principle]]). This way we obtain something not in the list.