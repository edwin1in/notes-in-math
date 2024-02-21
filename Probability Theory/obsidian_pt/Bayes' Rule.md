Let $A_{1},A_{2}, ..., A_{n}$ be disjoint events that form a partition of the sample space and assume that $P(A_{i)} > 0$. For any event $B$, we have 
$$
	\begin{align*}\\
	\\P(A_{i} | B) &= \frac{P(A_i)P(B|A_{i})}{P(B)}
\\
\end{align*}
$$
By [[Total Probability Theorem]], we also have
$$
\begin{align*}\\
\\ P(A_{i}|B) &= \frac{P(A_i)P(B|A_{i})}{P(A_{1} \cap B) + ... + P(A_{n} \cap B)}\\
&= \frac{P(A_i)P(B|A_{i})}{P(A_{1})P(B|A_{1}) + P(A_{2})P(B|A_{2})+...+P(A_{n})P(B|A_{n})}
\end{align*}
$$
Think of $A_{i}$ as the cause and the event $B$ as an effect. With the bae