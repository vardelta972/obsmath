States if f is n times continuously differentiable on $[a,b]$ then

$$ \forall x \exists \psi(x)\in[a,b]
f(x)=f(x_0)+f'(x_0)(x-x_0) +\frac{f''(x_0)(x-x_0)^2}{2}+..+ \frac{f^{[n]}(\psi(x))(x-x_0)^n}{n!}
$$
The last term is called the remainder term
$$
R_n(x)= \frac{f^{[n]}(\psi(x))(x-x_0)^n}{n!}
$$
So basically $f(x)=T_{n-1}+R_n$
From here if everything goes smoothly we may get [[Taylor Series]]
proof using [[MVT]] and integrals tho this does not give the remainder form above but it does give the bounds [[Bounds For Taylor Remainder]]which is what's useful for our purposes.
