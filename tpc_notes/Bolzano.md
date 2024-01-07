States every bounded sequence in R has a convergent subseq.
#pro There are two cases either there exist infinitely many peaks or finitely many. From here it's trivial.
Can be trivially done by [[LimeSoup]]

# Proof By Bisection

Pick a term $x_{n_{1}}$ of the sequence and then bisect the interval and choose one with infinitely many terms and pick a term there with greater index(possible) repeat this process to obtain a subsequence $x_{n_{k}} \in [a_{k},b_{k}]$. Observe $|b_{k}-a_{k}| \to 0.$ Thus by [[MCT]] ak and bk both converge to the same limit implies that the subsequence converges.

## General Bolzano

Every bounded seq in R^n has a conv subseq(see proof [[15 DEC testing#P5 General Bolzano]]) but not necessarily when we have a general metric space: for example in Q we can consider any seq that would have converged to $\sqrt 2$ then all of its [[subsequences]] must converge to $\sqrt 2$ also but that cannot happen in Q thus it does not have any subseq conv in Q.  