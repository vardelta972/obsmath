First we need to prove that every natural number can be written in the form
$$
\sum a_{j} 10^{j-1}
$$
where $a_{j} \in \{ 0,\dots,9 \}$ uniquely.

#pro #ipro We use a greedy Algorithm. We take n and consider the higher power to 10, 10^j satisfying $10^{j_{1}} \leq n.$ If equality is achieved we are done if not we repeat the same process on $n-10^{j_{2}}$ and so on. Then by The Principle Of Infinite Descent this process terminates with equality. Now observe each power of 10 must occur atmost 9 times beacuse otherwise the new power can be written in this same form. #pro  
### For Real Numbers 
Every $x \in R$ can be written in the form
$$
\sum_{k=-\infty}^n a_{k} 10^k
$$
where ak are all digits, This is not necessarily unique.

#mpro #ipro #pro It suffices to show this for $x \in (0,1).$ ie we want to show such an x can be written in the form
$$
\sum_{j=1}^\infty \frac{a_{j}}{10^j}
$$
where aj are digits, and this expression may not be unique.