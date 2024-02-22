### [[Conditional Probability]]
When the given information/event $B$ does not alter the probability of $A$ then,
$$
	\begin{align*}\\
\\ P(A|B) &= P(A), \text{Given } P(B)
 > 0\end{align*}
$$
From here we can deduce that 
$$
\begin{align*}\\
\\ P(A \cap B) &= P(A)P(B)
\end{align*}
$$
By symmetry, if event $A$ is independent of $B$ then event $B$ is independent of $A$.

If $A$ and $B$ are independent then $A^c$ and $B$ are independent.

*Proof*:
$$
\begin{align*}\\
\\ P(A|B) &= P(A)\\
1-P(A^{c}|B)&= 1-P(A^c)\\
P(A^{c}|B)&= P(A^c)\\
\end{align*}
$$
If A and B are independent then $A$ and $B^c$ are independent.

*Proof*:
$$
\begin{align*}\\
\\P(B|A) &= P(B)\\
  1-P(B^{c}|A) &= 1 - P(B^c) 
\\ P(B^{c}|A) &= P(B^c)
\end{align*}
$$
If $A$ and $B$ are independent then $A^c$ and $B^c$ are independent.
$$
\begin{align*}\\
\\ P(A^{c} \cap B^{c}) &= P((A \cup B)^c)\\
&= 1 - P(A \cup B)\\
&= 1 - (P(A) + P(B) -P(A \cap B))\\
&= (1-P(A))(1-P(B))\\
&= P(A^c)P(B^c)
\end{align*}
$$
### Conditional Independence 

Given an event $C$, the events $A$ and $B$ are called conditionally independent if
$$
\begin{align*}\\\\
P(A \cap B | C) &= P(A|C)P(B|C)
\end{align*}
$$
*Proof*:
$$
\begin{align*}\\
\\P(A \cap B|C) &= \frac{P(A \cap B \cap C)}{P(C)}
\end{align*}
$$
By [[multiplication rule]],
$$
\begin{align*}\\
\\ &= \frac{P(C)P(B|C)P(A|B \cap C)}{P(C)}\\
&= P(B|C)P(A|B\cap C)\\
&= \frac{P(B \cap C)}{P(C)} \cdot \frac{P(A \cap B \cap C)}{P(B \cap C)}
\end{align*}
$$
So if 

$$
\begin{align*}\\
\\ P(A|B \cap C) &= \frac{P(A \cap B |C)}{P(B|C)}\\
&= P(A|C)
\end{align*}
$$

### Independence of Several Events 
Suppose that $A_{1}, A_{2}, A_{3}, ..., A_{n}$ are independent events if 

$$
\begin{align*}\\
	P(\bigcap_{i=1}^{n}A_{i}) &= \prod_{i=1}^{n}P(A_{i})
\\
\end{align*}
$$