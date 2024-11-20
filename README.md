# PRINCI (2023UCP1601)
## TW Assignment 4
### Vector Dot Product
**The dot product is a fundamental way we can combine two
vectors. Intuitively, it tells us something about how much two
vectors point in the same direction.**

***We write the dot product with a little dot between the two
vectors (pronounced "a dot b"):***
*a.b=|a||b| cosθ*
> This text has been copied from
[dot product article](https://www.khanacademy.org/math/multivariable-calculus/thinking-about-multivariable-function/x786f2022:vectors-and-matrices/a/dot-products-mvc)
~~This was a mistake~~
> This text is give the knowlege about multivariable function specially dot product.
Some important points:
```
a.b=0 implies angle is 90.
a.b=ab implies angle if 0.
```
# Image:
![Dot product of two vectors](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/dot-product-of-vectors-1626103027.png)
- When angle between a and b is 0 then a.b=|a||b|.
* When angle between a and b is 90 then a.b=0.
+ When angle between a and b is 30 then a.b=|a||b|/2.
**What we have learnt**
- [X] Dot product
- [X] Formula
- [ ] Properties
**also known as**
1. scalar product
2. inner product
3. projection product

Dot product code[^1].
[^1]: #Python Program illustrating dot product of two vectors
#Importing numpy module
import numpy as np
#Taking two scalar values
a = 5
b = 7
#Calculating dot product using dot()
print(np.dot(a, b))

> [!NOTE]
> Dot and cross products are notsame
> [!TIP]
> Helpful advice for doing things better or more easily.
# Table
| CROSS PRODUCT | DOT PRODUCT|
| :--- | :--- |
| The cross product is the product of the magnitude of the vector and the sine of the angle in which they subtend other. |The dot product is the product of the magnitude of thevectors and the cos of the angle between them |
| The output is a vector. | The output is a scalar. |




**MATHEMATICAL EXPRESSION**


**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n
a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
