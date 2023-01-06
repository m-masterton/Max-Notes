202301061343
Status: #Note
Tags: [[Mathematics]]

___

### Definition and Examples

>[!definition] Definition (Function)
>Let $S$ and $T$ be [[Sets|sets]]. A **function** $f: S \to T$ is a rule that assigns for each element $s \in S$ precisely one element $f(s) \in T$. $S$ and $T$ are called the **domain** and **co-domain** respectivley.

>[!definition] Definition (Image of Function)
>If $f: S \to T$ is a function, the **image** of $f$ is the set of all elements of $T$ that are equal to $f(s)$ for some $s \in S$. We write $f(S)$ for the image of $f$. Thus $$f(S) = \{f(s) : s \in S\}.$$

>[!example]
>Here are some examples of functions:
>1. Define $f: \{1,2,3\} \to \mathbb{Z}$ by $f(x) = x^2 - 4$ for all $x \in \{1,2,3\}$. The image of $f$ is $\{3,0,5\}$.
>2. Define $f: \mathbb{R} \to \mathbb{R}$ by $f(x) = x^2$ for all $x \in \mathbb{R}$. Then the image of $f$ is $f(\mathbb{R}) = \{y : y \in R, y \geqslant 0\}$.
>3. Let $S$ be any set, and define a function $1_S: S \to S$ by $1_S(s) = s$ for all $s \in S$. This function $1_S$ is called the **identity function** of $S$.


### Onto, Onto-to-One and Bijection

>[!definition] Definition (Onto, One-to-One and Bijection)
>Let $f: S \to T$ be a function
>1. We say that $f$ is **onto** if the image $f(S) = T$. So for each $t \in T$ there exists $s \in S$ such that $f(s) = t$.
>2. We say that $f$ is **one-to-one** (sometimes written as **1-1**) if wherever $s_1, s_2 \in S$ with $s_1 \neq s_2$, then $f(s_1) \neq f(s_2)$.
>3. We say that $f$ is a **bijection** if $f$ is both onto and one-to-one.

>[!proposition]
>Let $f: S \to T$ be a function, where $S$ and $T$ are finite sets.
>1. If $f$ is onto then $|F| \geqslant |S|$.
>2. If $f$ is one-to-one then $|F| \leqslant |S|$.
>3. If $f$ is a bijection then $|F| = |S|$.


___
### References