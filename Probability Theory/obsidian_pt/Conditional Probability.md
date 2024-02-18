Given **partial information** that the outcome is within some event $B$, we wish to find the likelihood of the event $A$. Namely, the **conditional probability of $A$ given $B$** denoted as $P(A|B)$.

$$
\begin{align*}\\
\\ P(A | B) &= \frac{P(A \cap B)}{P(B)}, P(B)>0
\end{align*}
$$
### Satisfying Axioms
> (Normalization) $P(\Omega | B) = \frac{P(\Omega \cap B)}{P(B)} = \frac{P(B)}{P(B)} = 1$
> (Additivity) Let $A_{1}, A_{2}$ be disjoint sets. $P(A_{1} \cup A_{2}|B) = \frac{P((A_{1}\cup A_{2}) \cap B)}{P(B)} = \frac{P((A_{1}\cap B) \cup (A_{2} \cap B))}{P(B)} = \frac{P(A_{1}\cap B)}{P(B)} + \frac{P(A_{2}\cap B)}{P(B)} = P()$