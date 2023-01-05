202301051939
Status: #Note
Tags: [[Mathematics]] [[Abstract Algebra]]

___

>[!definition] Definition (Binary Operation)
>Let $S$ be a set. A **binary operation** $*$ on $S$ is a rule which assigns to any ordered pair $(a,b)$ where $a,b \in S$ an element $a * b \in S$. Formally, it is a function from $S \times S \to S$.

>[!example] Example
>Here are a few examples of binary operations:
>1. $S = \mathbb{Z}$, $a * b = a + b$ for all $a, b \in S$.
>2. $S = \mathbb{C}$, $a * b = ab$ for all $a, b \in S$.
>3. $S = \mathbb{R}$, $a * b = \frac{a + b}{2}$ for all $a, b \in S$.
>4. Let $S = S_n$ (the set of all permutations of $\{1, 2, \ldots, n\}$), and for $f, g \in S$ define $f * g = f \circ g$, the composition of permutations $f$ and $g$.

>[!definition] Definition (Commutativity)
>A binary operation $*$ on $S$ is **commutative** if, for all $a, b \in S$ we have $$a * b = b * a.$$

>[!definition] Definition (Associativity)
>A binary operation $*$ on $S$ is **associative** if, for all $a, b, c \in S$ we have $$a * (b * c) = (a * b) * c.$$

>[!definition] Definition (Distributivity)
>Given a set $S$ and two binary operations $*$ and $+$ on $S$,
>+ the binary operation $*$ is **left-distributive** over $+$ if, for all $a, b, c \in S$ we have $$a * (b + c) = (a * b) + (a * c);$$
>+ the binary operation $*$ is **right-distributive** over $+$ if, for all $a, b, c \in S$ we have $$(b + c) * a = (b * a) + (c * a);$$
>+ and the operation $*$ is **distributive** over $+$ if it is both left- and right-distributive.
>
>Note that when $*$ is commutative, the three conditions above are logically equivalent

___
### References

A Concise Introduction to Pure Mathematics, Pages 225-226