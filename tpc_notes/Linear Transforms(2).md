Its a linear functions $l : R^m \to R^n$. i.e. 
$$
L(\alpha x + \beta y)=\alpha L(x) + \beta L(y).
$$
Intuitively they are any transforms which keep the origin fixed and apply rotation or shear. But Translation is not allowd as $L(0)=0.$ 
#### Examples: (x,y) -> (2x,3y) , Rotation matrix 
$$ R(\alpha)=
\begin{pmatrix}
\cos \alpha & -\sin \alpha \\
\sin \alpha & \cos \alpha
\end{pmatrix}
$$

A linear transformation is completely determined by $L(e_{j})$ i.e. once we know where the basis vectors go we know the whole transform. The result below illustrates
#pro ->
$$
L(v)=\sum v^jL(e_{j})
$$ 
Another important result is that matrix and transforms are essentially the same thing i.e. we can write for any linear transform $L(x) := Mx$ for 
$$
M=\begin{pmatrix}
L(e_{1}) & L(e_{2}) & \dots. & L(e_{m})
\end{pmatrix}
$$
Similary we can write each matrix as the linear transform $Mx =: L(x)$ .
