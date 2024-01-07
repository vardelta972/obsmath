Given points more than 1 points $(x_{1},y_{1}),\dots,(x_{n},y_{n})$ we want to find the line which best fits these points to do this we want to minimize the quantity 
$$
E(a,b) = \sum (y_{j}-(ax_{j}+b))^2
$$
because minimizing $\sum |y_{j}-(ax_{j}+b)|$ and $max |y_{j}-ax_{j}+b|$ are both hard. Former because of possibility for [[partial derivatives]] to not exist.

To do this we set the gradient equal to 0 and get
$$
0=\frac{\partial E}{\partial a} ,0= \frac{\partial E}{\partial b}
$$
This gives
![[Pasted image 20240102195206.jpg]]
Note that the denomin is defined thanks to equality case in [[Cauchy Swarchz]].