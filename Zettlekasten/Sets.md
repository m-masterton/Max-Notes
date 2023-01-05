202301052056
Status: #Note
Tags: [[Mathematics]] [[Number Systems]] [[Discrete Mathematics]]

___

>[!definition] Definition (Set)
>A **set** is a collection of objects, which are called the **elements** of the set, without regards to order or repetition (so elements in a set are only counted once). We write $s \in S$ to mean that $s$ is an element of the set $S$ and $t \notin S$ to mean that $t$ is not an element of $S$.

There are lots of different ways of describing a set, one way is just to write out the elements of the set in a list. For example the set $\{1,3,5\}$ is the set consisting of elements 1, 3 and 5.

However, this is often not a convenient way to describe a set. For example the set of all people who live in Denmark cannot easily be described in this way. We also can't describe a set like "the set of all real numbers between 0 and 1".  To describe sets like this we use the following alternate notation:

Suppose $X$ is a set and $P$ is the property of some elements in $X$, we can write a set $\{x: x \in X, P(x)\}$ for all of the elements of $X$ for which $P(x)$ is true. For example the set of all real numbers between 0 and 1 is conveniently described by the notation: $$\{x : x \in R, 0 < x < 1\}.$$

>[!example] Example
>Here are some common sets and the symbols used to denote them
>+ $\mathbb{N} = \{1, 2, 3, \ldots\}$ is the natural numbers
>+ $\mathbb{N}_0 = \{0, 1, 2, \ldots\}$ is the natural numbers with 0
>+ $\mathbb{Z} = \{\ldots, -2, -1, 0, 1, 2, \ldots\}$ is the integers
>+ $\mathbb{Q} = \{\frac{a}{b}: a, b \in \mathbb{Z}, b \neq 0\}$ is the rational numbers
>+ $\mathbb{R}$ is the real numbers
>+ $\mathbb{C}$ is the complex numbers
>+ $\emptyset$ is the empty set (set with no elements)

### Equality of Sets and S

>[!definition] Definition (Equality of Sets)
>For two sets $A$ and $B$. $A$ is equal to $B$, written as $A = B$, if $$(\forall x) \: x \in A \iff x \in B,$$ i.e. the two sets are equal if they have the same elements.

>[!definition] Definition (Subsets)
>For two sets $A$ and $B$. $A$ is a **subset** of $B$, written $A \subseteq B$, if all elements of $A$ are in $B$: $$(\forall x) \: x \in A \implies x \in B.$$

>[!example] Example
>The subsets of $\{1,2\}$ are $$\{1,2\}, \{1\}, \{2\}, \emptyset.$$ (By convention, $\emptyset$ is a subset of every set.)

>[!theorem]
>$$(A = B) \iff (A \subseteq B \text{ and } B \subseteq A)$$
___

### Unions and Intersections

___
### References