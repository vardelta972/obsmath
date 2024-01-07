
![[Screenshot 2023-12-19 095417.png]]
-> Forall $\varepsilon >0$ choose $N=\left\lceil  \frac{1}{\varepsilon}  \right\rceil$. Then forall $n \geq N,$ we have $n \geq  \frac{1}{\varepsilon}$, which implies 
$$
\frac{1}{n} < \varepsilon
$$
.
![[Pasted image 20231219095736.png]]
-> forall $\varepsilon > 0$ choose $N=\left\lceil  \frac{1}{2\varepsilon}  \right\rceil$ then forall $n \geq N$ we have $n \geq \frac{1}{2\varepsilon}$ implying 
$$
|\frac{(3n+2)}{n+1}-3 |= \frac{1}{n+1}< \frac{1}{2n}  < \varepsilon
$$
.
![[Pasted image 20231219100152.png]]
-> forall $\varepsilon>0$ choose $N>\frac{1}{4\varepsilon^2}$ then $\forall n \geq N$ we have $n > \frac{1}{4\varepsilon^2}$ implying 
$$
(\sqrt{ n+1 }-\sqrt{ n }) = \frac{1}{\sqrt{ n+1 }+\sqrt{ n }} \leq \frac{1}{2\sqrt{ n }} < \varepsilon.
$$


![[Pasted image 20231219100604.png]]

-> Observe that $b_{n}$ is a strictly decreasing sequence of n, and it is bounded from below by 0. Thus it converges by [[MCT]], by Algebraic Limit Theorems and [[subsequences]] 
$$
\lim_{ n \to \infty } b^n = \lim_{ n \to \infty } b^{2n} \to \lim_{ n \to \infty } b^n = 0\lor 1. 
$$

Now observe that $b^n < b, \forall n \geq 2,$ this implies $\lim_{ n \to \infty } b^n \leq b <1.$ Thus limit is 0.

![[Pasted image 20231219101814.png]]

Say it converges to 0 then choose $\varepsilon = \frac{1}{2}$ then forall N>0 choose $n>N$ sho that $a_{n}=2$ then $a_{n}>\varepsilon.$(it is possible to choose such n as otherwise there would be finitely many 2's).

#mpro #ipro #pro 
![[Pasted image 20231219102235.png]]
-> For c=1 this is clear say c<1 then $c^{1/n}$ increases strictly and is bounded from above implying it converges by [[MCT]]. Now $\lim_{ n \to \infty } c^{1/n} = \lim_{ n \to \infty } c^{1/2n} =( \lim_{ n \to \infty } c^{1/n} )^2$ this implies limit is either 0 or 1. It cannot be 0 as $c>0$ and $c^{1/n}$ increases. Thus limit is 1.

Say c>1 then we have $c^{1/n} > 1$ and it is decreasing strictly and bounded from below by 1. By a similar reasoning we get lim = 0 or 1, it cant be zero as $c^{1/n} >1.$ Thus 1.

![[Pasted image 20231219102907.png]]
-> forall $\varepsilon>0$ choose $N=\left\lceil  \frac{1}{\varepsilon}  \right\rceil +1$ then forall $n \geq N$ we have $n \geq \frac{1}{\varepsilon}$ implying 
$$
\frac{n}{n^2+1} < \frac{n}{n^2} < \frac{1}{n} < \varepsilon 
$$

![[Pasted image 20231219123947.png]]
#ipro #pro -> if x=0 then $\forall \varepsilon>0$ take $N>0$ so that $x_{n}<\varepsilon^2$
then forall $n \geq N: \sqrt{ x_{n} }<\varepsilon.$

if x not 0 then $\forall \varepsilon>0$ take $N>0: |x_{n}-x|<\varepsilon$ then 
$$
|\sqrt{ x_{n} }-\sqrt{ x }|=\frac{|x_{n}-x|}{\sqrt{ x_{n} }+\sqrt{ x }} \leq \frac{|x_{n}-x|}{\sqrt{ x }}< \frac{\varepsilon}{\sqrt{ x }}.
$$

![[Pasted image 20231219122653.png]]

-> Consider the series $\sum \frac{2^n}{n!}$ applying root test this converges from here we have the result.

