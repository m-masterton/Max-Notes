202301052023
Status: #Note
Tags: [[Mathematics]] [[Abstract Algebra]]

___

>[!definition] Definition (Group)
>	A **group** $(G,*)$ is a [[Sets|set]] $G$ with [[Binary Operations|binary operation]] $*$ that satisfies the following axioms:
>1. **Closure axiom**: For all $a, b \in G$, we have $a * b \in G$.
>2. **Identity axiom**: There exists an element $e \in G$ such that for all $a \in G$, we have $$a * e = e * a = a.$$
>3. **Inverse axiom**: For all $a \in G$, there is some $a^{-1} \in G$ such that $$a * a^{-1} = a^{-1} * a = e.$$
>4.  **Associativity axiom**: For all $a, b, c \in G$, we have $$ a * (b * c) = (a * b) * c.$$

The element $e$ is called the **identity element** of $G$ and the element $a^{-1}$ is called the **inverse** of $a$.

Note that the closure axiom is not really needed because it is included in the definition of a binary operation. However, when confirming that something is a group, we will have to check that the binary operation is valid on the set, so it is useful to keep it there.


___
### References