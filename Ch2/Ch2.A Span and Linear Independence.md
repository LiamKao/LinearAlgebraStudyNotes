# Finite-Dimensional Vector Spaces

## 2.A Span and Linear Independence

#### 2.2 Notation list of vectors
We will usually write lists of vectors without surrounding parentheses.

### Linear Combinations and Span

#### 2.3 Definition linear combination
A linear combination of a list $v_1+...+v_m$ of vectors in $V$ is a vector of the form$$a_1v_1+...+a_mv_m$$where $a_1,...,a_m \in \mathbf{F}$.

#### 2.5 Definition span
The set of all linear combinations of a list of vectors $v_1,...,v_m \in V$ is called the ***span*** of $v_1,...,v_m$, denoted $span(v_1,...,v_m)$In other words,
$$span(v_1,...,v_m)=\{ a_1v_1+...+a_mv_m \; : \; a_1,...,a_m \in \mathbf{F} \} $$
The span of the empty list $()$ is defined to be $\{0\}$
##### notes:
$i.e.: span()=\{0\}$

#### 2.7 Span is the smallest containing subspace
The span of a list of vectors in $V$ is the smallest subspace of $V$ containing all the vectors in the list.

#### 2.8 Definition spans
If $span(v_1,...,v_m)$ equals $V$, we say that $v_1,...,v_m \; spans \; V$.

#### 2.10 Definition finite-dimensional vector space
A vector space is called ***finite-dimensional*** if some list of vectors in it spans the space

### Linear Independence
#### 2.17 Definition linearly independent
- A list $v_1,...,v_m$ of vectors in $V$ is called ***linearly independent*** if the only choice of $a_1,...,a_m \in \mathbf{F}$ that makes $a_1v_1+...+a_mv_m = 0 \; where \; a_1=...=a_m=0$.
- The empty list $()$ is also declared to be linearly independent.

#### 2.19 Definition linearly dependent
- A list of vectors in V is called ***linearly dependent*** if it is not linearly independent.
- In other words, a list $a_1v_1+...+a_mv_m$ of vectors in $V$ is linearly dependent if there exist $a_1,...,a_m \in \mathbf{F}$, not all 0, such that $a_1v_1+...+a_mv_m = 0$.


#### 2.21 Linear Dependence Lemma
Suppose $v_1,...,v_m$ is a linearly dependent list in $V$. Then there exists $j \in \{ 1,2,...,m \}$ such that the following hold:
$(a) \quad v_j \in span(v_1,...,v_{j-1})  $
$(b) \quad $ if the $j^{th}$ term is removed from $v_1,...,v_m$, the span of the remaining list equals $sapn(v_1,...,v_m)$.

#### 2.23 Length of linearly independent list $\leq$ length of spanning list
In a finite-dimensional vector space, the length of every linearly independent list of vectors is less than or equal to the length of every spanning list of vectors.

#### 2.26 Finite-dimensional subspaces
Every subspace of a finite-dimensional vector space is finite-dimensional.
