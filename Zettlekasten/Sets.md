202301052056
Status: #Note
Tags: [[Mathematics]] [[Number Systems]] [[Discrete Mathematics]]

___

### Definition and Examples

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

We call $S$ a **finite** set if it only has a finite number of elements. If $S$ has $n$ elements, we write $|S| = n$. 

### Equality of Sets and Subsets

>[!definition] Definition (Equality of Sets)
>For two sets $A$ and $B$. $A$ is **equal** to $B$, written as $A = B$, if $$(\forall x) \: x \in A \iff x \in B,$$ i.e. the two sets are equal if they have the same elements.

This basically just reiterates the point that elements of a set are only counted once. So $\{1,2,3,3,4\}$ $=$ $\{1,2,2,3,4\}$. 

>[!definition] Definition (Subsets)
>For two sets $A$ and $B$. $A$ is a **subset** of $B$, written $A \subseteq B$, if all elements of $A$ are in $B$: $$(\forall x) \: x \in A \implies x \in B.$$

>[!example] Example
>The subsets of $\{1,2\}$ are $$\{1,2\}, \{1\}, \{2\}, \emptyset.$$ (By convention, $\emptyset$ is a subset of every set and every set is a subset of itself.)

>[!theorem]
>$$(A = B) \iff (A \subseteq B \text{ and } B \subseteq A)$$
___

### Union, Intersection and Difference

>[!definition] Definition (Unions and Intersections)
>Let $A$ and $B$ be sets. The **union** of $A$ and $B$, written $A \cup B$, is the set consisting of all elements that lie in either $A$ or $B$ (or both). Symbolically, $$A \cup B = \{x : x \in A \text{ or } x \in B\}.$$
>The **intersection** of $A$ and $B$, written $A \cap B$, is the set consisting of all elements that lie in both $A$ and $B$; this $$A \cap B = \{x : x \in A \text{ and } x \in B\}.$$
>

Note that two sets are said to be **disjoint** if their union is the empty set.

>[!proposition]
>Let $A,B,C$ be sets. Then $$A \cap (B \cup C) = (A \cap B) \cup (A \cap C).$$

>[!proof]
>$$\begin{align*}x \in A \cap (B \cup C) & \iff x \in A \text{ and } x \in (B \text{ or } C)\\ & \iff (x \in A \text{ and } x \in B) \text{ or } (x \in A \text{ and } x \in C)\\ & \iff x \in (A \cap B) \cup (A \cap C).\end{align*}$$
>Hence, $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$.

We sometimes use the more concise notation $$A_1 \cup \ldots \cup A_n = \bigcup_{i=1}^n A_i$$
and $$A_1 \cap \ldots \cap A_n = \bigcap_{i=1}^n A_i.$$
>[!definition] Definition (Set Difference)
>If $A$ and $B$ are sets, their **difference** is define to be the set $$A - B = \{x : x \in A \text{ and } x \notin B\}.$$

>[!example]
>For example $\{1,2,3,4\} - \{2,4\} = \{1,3\}$. And $\mathbb{R}^* = \mathbb{R}- \{0\}$, the set of non-zero real numbers.

### Cartesian Products

>[!definition] Definition (Ordered Pair)
>An **ordered pair** $(a,b)$ is a pair of two items in which ordered matters. Formally, it is defined as $\{\{a\}, \{a,b\}\}$. We have $(a,b) = (a',b')$ if and only if $a = a'$ and $b = b'$.

>[!definition] Definition (Cartesian Product)
>Given two sets $A$, $B$, the **Cartesian product** of $A$ and $B$ is $A \times B = \{(a,b) : a \in A, b \in B\}$. This can be extended to $n$ products, e.g. $\mathbb{R}^3 = \mathbb{R} \times \mathbb{R} \times \mathbb{R} = \{(x,y,z) : x, y, z \in \mathbb{R}\}$ (which is technically $\{(x,(y,z)) : x, y, z \in \mathbb{R}\}$).

>[!example]
>For example if $A = \{1,2\}$ and $B = \{1,4,5\}$, then $A \times B$ consists of the six ordered pairs $$(1,1), (1,4), (1,5), (2,1), (2,4), (2,5).$$

### The Inclusion-Exclusion Principle



___
### References