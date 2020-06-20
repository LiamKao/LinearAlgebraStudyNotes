# Vector Space

## 1.A: R<sup>n</sup> and C<sup>n</sup>

### Complex Numbers
![](assets/markdown-img-paste-20200617190125779.png)

![](assets/markdown-img-paste-20200617190200969.png)

![](assets/markdown-img-paste-20200617190227345.png)

![](assets/markdown-img-paste-20200617190259767.png)

* * *

### Lists

![](assets/markdown-img-paste-20200617190331237.png)

* * *


### F<sup>n</sup>

#### 1.10 Definition $\mathbf{F}^n$
$\mathbf{F}^n $ is the set of all lists of length n of elements of $\mathbf{F}$:

$$ \mathbf{F}^n = \{ (x_1, x_2, \dots, x_n ) \; : \; x_j  \;  for \; j = 1,2,\cdots,n   \}
$$

For $ \; (x_1,...,x_n) \in \mathbf{F}^n \; $ and $ \; j \; \in \{1,...,n\}
$ we say that $ x_j $ is the $ j^th $ ***coordinate*** of $(x_1,...,x_n)$

#### 1.12 Definition addition in $\mathbf{F}^n$
***Addition*** in $\mathbf{F}^n$ is defined by adding corresponding coordinates:
$$ (x_1,...,x_n)+(y_1,...,y_n)=(x_1+y_1,...,x_n+y_n) $$

#### 1.13 Commutativity of addition in $\mathbf{F}^n$
If $ x,y \in \mathbf{F}^n \; then \; x + y = y + x$

#### 1.14 Definition 0
Let 0 denote the list of length $n$ whose coordinates are all 0:
$$0 = (0,...,0).$$

#### 1.16 Definition ***additive inverse*** in $\mathbf{F}^n$
For $ x \in \mathbf{F}^n$, the ***additive inverse*** of $x$, denoted $-x$, is the vector $ x \in \mathbf{F}^n$
such that

$$ x + (-x) = 0 $$

In other words, if $x=(x_1,...,x_n)$, then $-x = (-x_1,...,-x_n)$.

#### 1.17 Definition ***scalar multiplication*** in $\mathbf{F}^n$
The ***product*** of a number $\lambda$ and a vector in $\mathbf{F}^n$ is computed by multiplying
each coordinate of the vector by $\lambda$:
$$\lambda(x_1,...,x_n) = (\lambda x_1,...,\lambda x_n) $$
here $\lambda \in \mathbf{F}$ and $ (x_1,...,x_n) \in \mathbf{F}^n $.

* * *

## 1.B: Definition of Vector Space

#### 1.18 Definition addition, scalar multiplication

- An ***addition*** on a set $\mathbf{V}$ is a function that assigns an element $u+v \in \mathbf{V}$ to each pair of elements $ u,v \in \mathbf{V} $

- A ***scalar multiplication*** on a set $\mathbf{V}$ is a function that assigns an element $\lambda v \in \mathbf{V}$ to each $\lambda \in \mathbf{F}$ and $v \in \mathbf{V}$.

#### 1.19 Definition vector space
A ***vector space*** is a set $\mathbf{V}$ along with an addition on $\mathbf{V}$ and a scalar multiplication on $\mathbf{V}$ such that the following properties hold:

- **commutativity**
$$u + v = v + u, \; \forall u,v \in \mathbf{V} $$
- **associativity**
$$ (u+v) +w = u+(v+w) , \; \forall \; u, v, w \in \mathbf{V} $$
- **additive identity**
  $$\exists 0 \in \mathbf{V} \; s.t. \; v + 0 = v, \; \forall v  \in \mathbf{V} $$

- **additive inverse**
$$\forall v  \in \mathbf{V},\; \exists w \in V \; s.t. \; v + w = 0$$
- **multiplicative identity**
$$1v = v, \; \forall v \in \mathbf{V} $$
- **distributive properties**
$$a(u + v) = au + av \; and \; (a + b)v = av + bv,\; \forall a, b \in \mathbf{F} \; and \; \forall u,v \in \mathbf{V}$$

##### notes
交換性(commutativity), 分配性(distributive properties), 結合性(associativity), 乘法單位元素(multiplicative identity), 加法單位元素(additive identity)

#### 1.20 Definition ***vector***, ***point***
Elements of a vector space are called ***vectors*** or ***points***.

#### 1.21 Definition ***real vector space, complex vector space***
- A vector space over $\mathbf{R}$ is called a ***real vector space***.
- A vector space over $\mathbf{C}$ is called a ***complex vector space***.


#### 1.23 Notation $\mathbf{F}^S$
- If $\mathbf{S}$ is a set, then $\mathbf{F}^S$ denotes the set of functions from $\mathbf{S}$ to $\mathbf{F}$.
- For $f,g \in \mathbf{F}^S$, the sum $f+g \in \mathbf{F}^S$ is the function defined by
$$ f+g(x) = f(x)+g(x) ,\; \forall x \in \mathbf{S}$$
- For $\lambda \in \mathbf{F} $ and $f \in \mathbf{F}^S$ , the ***product*** $\lambda f \in \mathbf{F}^S$ is the function defined by
$$ (\lambda f)(x) = \lambda f(x) ,\; \forall x \in \mathbf{S} $$

#### 1.25 Unique additive identity
A vector space has a unique additive identity.

#### 1.26 Unique additive inverse
Every element in a vector space has a unique additive inverse.

#### 1.28 Notation $\mathbf{V}$
For the rest of the book, $\mathbf{V}$ denotes a vector space over $\mathbf{F}$.

#### 1.29 The number 0 times a vector
$0v=0 ,\; \forall v \in  \mathbf{V}$.

#### 1.30 A number times the vector 0
$a0 = 0 ,\; \forall a \in \mathbf{F}$

1.31 The number 1 times a vector
$(-1)v = -v ,\; \forall v \in \mathbf{V}$

* * *

## 1.C: Subspaces

#### 1.32 Definition ***subspace***
A subset $\mathbf{U}$ of $\mathbf{V}$ is called a subspace of $\mathbf{V}$ if $\mathbf{U}$ is also a vector space
(using **the same addition and scalar multiplication** as on $\mathbf{V}$)

#### 1.34 Conditions for a subspace
A subset $\mathbf{U}$ of $\mathbf{V}$ is a subspace of $\mathbf{V}$ if and only if $\mathbf{U}$ satisfies the following three conditions:
- additive identity
$$0 \in \mathbf{U}$$
- closed under addition
$$u,w \in \mathbf{U} \implies u+w \in \mathbf{U}$$
- closed under scalar multiplication
$$a \in \mathbf{F} \; and \; u \in \mathbf{U} \implies au \in \mathbf{U}$$

* * *

### Sum of Subspaces

##### 1.36 Definition ***sum of subsets***
Suppose $\mathbf{U}_1,...,\mathbf{U}_m$ are subsets of $\mathbf{V}$. The sum of $\mathbf{U}_1,...,\mathbf{U}_m$, denoted
$\mathbf{U}_1+,...,+\mathbf{U}_m$, is the set of all possible sums of elements of $\mathbf{U}_1,...,\mathbf{U}_m$.
More precisely,
$$\mathbf{U}_1,...,\mathbf{U}_m = \{u_1,...,u_m: u_1 \in \mathbf{U}_1,...,u_m \in \mathbf{U}_m \}$$

* * *

### Direct Sum


#### 1.40 Definition ***direct sum***
Suppose $\mathbf{U}_1,...,\mathbf{U}_m$ are subspaces of $\mathbf{V}$.
- The sum $\mathbf{U}_1+...+\mathbf{U}_m$ is called a ***direct sum*** if each element of $\mathbf{U}_1+...+\mathbf{U}_m$ can be written in only one way as a sum $u_1+...+u_m$, where each $u_j \in \mathbf{U}_j$
- If $\mathbf{U}_1+...+\mathbf{U}_m$ is a direct sum, then$\mathbf{U}_1 \oplus...\oplus \mathbf{U}_m$ denotes
$\mathbf{U}_1+...+\mathbf{U}_m$, with the $\oplus$ notation serving as an indication that this is a direct sum.


#### 1.44 Condition for a direct sum
Suppose $\mathbf{U}_1,...,\mathbf{U}_m$ are subspaces of $\mathbf{V}$. Then $\mathbf{U}_1+...+\mathbf{U}_m$ is a direct sum if and only if the only way to write 0 as a sum $u_1+...+u_m$, where each $u_j \in \mathbf{U}_j$ , is by taking each $u_j$ equal to 0.


#### 1.45 Direct sum of two subspaces
Suppose $\mathbf{U}$ and $\mathbf{W}$ are subspaces of $\mathbf{V}$. Then $\mathbf{U} + \mathbf{W}$  is a direct sum if and only if $\mathbf{U} \cup \mathbf{W} = \{ 0 \}$



* * *
