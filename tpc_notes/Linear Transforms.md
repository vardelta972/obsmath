A linear transform is a linear function between two vector spaces over the same field.

Infact in finite dimensional vector spaces it is enough to define their outputs at basis vector doing this defines them for everything because 
$$
L(v)=L\left( \sum v^j e_{j} \right) = \sum v^j L(e_{j})
$$
Observe that linear maps are always injective this follows straight from $L(0)=0.$
# The Space Hom(V,W)
We define $Hom(V,W)$ = All linear maps between V and W. Addition and scalar multiplication on this are defined pointwise over the common field, then Hom(V,W) is itself a vector space! This follows easily from V,W being vector spaces and operations defined pointwise.

### Conversion Of Basis
If V,W have the same dimensions then there exists a unique way to convert basis of V onto the basis of W ie there is a unique linear map L so that
$$
L(e_{j}) =f_{j}
$$
The proof is trivial as specifying outputs at basis vectors uniquely generate the linear map.
#### It's Basis