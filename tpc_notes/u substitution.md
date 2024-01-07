Sometimes one needs to bend space inorder to evaluate certain integrals. Basically if we transform $[a,b]$ to $[g(a),g(b)]$ then we have the relation
$$
\int _{[g(a),g(b)]} f(x) \, dx = \int _{[a,b]} f(g(x)) g'(x) \, dx 
$$
this $g'(x)$ is basiclly the factor accounting for the distortion of space, in higher dimensions it's known as The Jacobian. 

### Formal Statement (Form 1)

If $\psi : [a,b] \to [\psi(a),\psi(b)]$ is differentiable it's derivative integrable on $[a,b]$ and f continuous on $[\psi(a),\psi(b)]$ then we have the relation
$$
\int _{[\psi(a),\psi(b)]} f(x) \, dx = \int _{[a,b]} f(\psi(x)) \psi'(x) \, dx 
$$

#pro #mpro #ipro Observe
$$
\int _{{a,b}} f(\psi(x))\psi'(x) \, dx = \int _{{a,b}} (F(\psi(x)))' \, dx = F(\psi(b))-F(\psi(a)) = \int _{[\psi(a),\psi(b)]} f(x) \, dx 
$$
Where 
$$
F(y) = \int _{[c,y]} f(x) \, dx 
$$
where we have chosen some c in $[\psi(a),\psi(b)]$.(eg c can be $\psi(a)$).
##### Formal Statement (Form 2)

If $f$ is integrable on $[c,d]$ and $\psi : [a,b] \to [c,d]$ is a bijective, differentiable map with $\psi '$ integrable on $[a,b]$ then
$$
\int_{[c,d]} f(x) \, dx = \int _{[a,b]} f(\psi(x)) \psi'(x) \, dx 
$$

#mpro #ipro #pro 