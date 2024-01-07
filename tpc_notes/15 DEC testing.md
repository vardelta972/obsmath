testing.

By Axiom 1.1 we conclude that $$1+1 = 1+ S(0) = S(1)=2$$

![[Pasted image 20231214180502.png]]

For every $\epsilon > 0$ there exists $\delta_1,\delta_2>0$ such that for all $x \in D$ such that $0<|x-x_0|<\delta_1,0<|x-x_0|<\delta_2$ respectively we have that $$|f(x)-L|<\epsilon/2, |g(x)-G|<\epsilon/2 .$$ Thus if we choose $\delta := min(\delta_1,\delta_2)$ then for a fixed $x$ so that $0<|x-x_0|<\delta$ we get $$|f(x)-L+g(x)-G| \leq |f(x)-L| + |g(x)-G| < \epsilon/2 + \epsilon/2 = \epsilon.$$ $\qed$

Testin $$\displaylines{\mathbf{L}(X) = \int_{0}^{X} W(t)dt \\ = TEX(4\pi X)}$$

### P1: PT [[Axiom Of Induction]] is eq to [[Principle Of Infinite Descent]].
-> We show that all dec seq in N terminate eventually by induction on initial term a1.
Base: a1=0 then termination is automatic as 0 is the smallest number.

Induction: Say a1=n+1 then a2=n from here termination happens through the induction hypothesis.

<- Say Induction is false then there is a prop. P such that P(0) and $\forall n : P(n) \implies P(n++)$ hold both but for some nat m P(m) fails to hold. Since P(m) fails P(m-1) fails which in turn implies that P(m-2) fails also... continuing like this gives a sequence in infinite descent.

$\qed$

### P2: PT [[Principle Of Infinite Descent]] eq to [[Well Ordering Principle]].

-> If Well ordering does not hold then there is a nonmepty subset U of N with no minimum pick any c \in U from here we can easily obtain a seq in infinite descent.

<- If [[Principle of infinite descent]] fails there we arrange the corresponding seq obtained into a set. Then this set has no minimal element.

$\qed$



### P3: Prove [[Pigeonhole Principle]].

-> Part1: Say all boxes have atmost ceil(m/n)-1 pigs. Then no of pigs<= nceil(m/n)-n. So, m <= nceil(m/n)+n< m  so, m < m a contradiction.

Part2: Say all boxes have atleast floor(m/n)+1 pigs. Then m>=nfloor(m/n)+n so m>=m+n but this means n<=0. $\qed$

### P4: if $|A_1 \cup .... \cup A_n|=m$ then atleast one $A_j$ is so that $|A_j| \geq ceil(m/n)$ and atleast one $A_k$ so that $|A_k| \leq floor(m/n).$

-> Part1: say forall j that $|A_j|<ceil(m/n)$ then $|A_j|\leq ceil(m/n)-1 \implies m=|union|\leq nceil(m/n)-n<m \implies m<m.$

Part2: say forall j that $|A_j|\geq floor(m/n)+1 \implies m=nfloor(m/n)+n > m \implies m>m.$ 


### P5: General [[Bolzano]]

-> say $(x^1 _n,x^2 _n,...,x^m _n)$ is bounded then each component has a convergent subsequence $x^j _{n^j_{k}} \to L^j$ then we consider the subseq made by combining all those it converges to $(L^1,...L^m).$ 

### #imp P6 : [[IVT]] on Compact Domain with a cont func

-> say $f(x_1) \leq y \leq f(x_2).$ We now use the [[Ancient Bisection Method]] we break $[f(x_1),f(x_2)]$ into two using averages and check in which one y lies this way we get an increasing seq $f(x_j)$ which is also bounded so it converges by [[MCT]] we claim it converges to y. observe that that the lenght of the intervals halves by each step implying in nth setp its size is $\frac{1}{2^n}$ which tends to 0. Thus by [[Nested Intervals Property]] $f(x_j)$ indeed converges to y. Now [[compactness]] of domain implies that some $x_{n_{k}} \to L \in D$ combining with continuity gives $f(x_{n_{k}}) \to f(L).$ Thus, y=f(L).

$\qed$

