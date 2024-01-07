# Topological Definition 

## Sequential Criterion 
# Limits and Boundedness of functions 

Say f is continuous on $[0,\infty]$ and $\lim_{ x \to \infty } f(x)$ converges then by definition it's definitely bounded after some M and on interval $[0,M]$ is bounded using the Maximum Principle [[Maxima And Minima]] . Thus its bounded overall.

If f has a limit at x0 them it must be bounded in some punctured neighbourhood around x0. #mpro #ipro #pro 
Well $f(V( x_{0})) \subseteq B_{1}(L)$ says it all in metric spaces.

# Limits And Surjectivity 

Say f continuous on $[0,\infty]$ with f(0) =0 and $\lim_{ x \to \infty } f(x)=\infty$ Then f is surjective as given any y bw 0 and inf f goes above it thus y is bw 0 and one of those values which forces [[IVT]], giving the result.

## Limits Of Multivariable Functions 
Here limits are componentwise, this follows from[[Convergence Of Sequences]].
![[Pasted image 20240105202305.png]]
3) #mpro #ipro This holds for arbitrary inner product spaces first prove for sequences in there proving for $<a_{n},1>$ suffices by ALT. for this observe 
$$
|<a_{n},1>-<L,1>| = |<a_{n}-L,1>| \leq |a_{n}-L|
$$
by [[Cauchy Swarchz]] . BTW the last mag is mag in metric.
The following is an easy corollary
![[Pasted image 20240106171757.png]]
![[Pasted image 20240106171941.png]]
another easy stuff, this allows us to build [[continuous functions]], the identity one is the most important.
![[Pasted image 20240105205236.png]]
 
 #mpro We prove a more general version that if $\gamma : (0,1) \to R^n$ is a continuous curve then with $\gamma(t_{0})=x_{0}$
$$
\lim_{ t \to t_{0}} f(\gamma(t)) = L
$$
Take any neighbourhood U(L) then there is a neighbourhood V(x0) whose image contained in U(L) since $\gamma$ is continuous there is a neighbourhood B(t0) contained in V(x0) this chain of containments gives the result.
Infact if we replace $(0,1)$ and Rn by arbitrary metric spaces then it still works. Infact it's just the composition law of limits.

### Squeeze Theorem
If $f:X \to R$ where X metric space satisfies 
$$
h \leq f \leq g
$$
and h,g have same limit at c then so doez f.
#pro trivial use epsilon delta then you get an inequality similar to real valued sqt.

## Limits At Infinity
![[Pasted image 20240106172100.png]]
Remember the notation
$$
\lim_{ |x| \to \infty } f(x) 
$$
not
$$
\lim_{ x \to \infty } f(x)
$$
The last one can be generalied to limits at infinity using neighbourhoods at infinity.

![[Pasted image 20240106172311.png]]
That limit is well defined as f must be non-zero in some neighbourhood otherwise [[Axiom Of Choice]] will give something terrifying!