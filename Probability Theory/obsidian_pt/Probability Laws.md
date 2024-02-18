### Probability Law Axioms
> (Non-negativity) $P(A) \geq 0$
> (Disjoint Additivity) Suppose $A_{1,}A_{2,}A_3,...$ are disjoint events. Then $P(A_{1}\cup A_{2} \cup A_{3} \cup ...) = P(A_{1)} + P(A_{2}) + P(A_{3}) +  ...$
> (Normalization) $P(\Omega) = 1$

>[!info] 
>From our normalization and additivity axiom, we can derive another formulation.
>Since $\Omega \cap \emptyset = \emptyset$, Thus $\Omega$ and $\emptyset$ are disjoint events.
>From our normalization axiom, we have $P(\Omega) = 1$.
>$P(\Omega) =P(\Omega \cup \emptyset)$ By additivity, $P(\Omega \cup \emptyset) = P(\Omega) + P(\emptyset) = 1 + P(\emptyset)$. Thus $P(\emptyset) = 0$.

### Discrete Probability Law
Suppose we have a finite sample space. By the disjoint additivity axiom,  the probability of any event, is the sum of the probability of it's individual elements.
$$
\begin{align*}\\
 P(\set{s_1,s_2,s_{3,...})}= P(s_{1}) + P(s_{2}) + ...
\end{align*}
$$
### Discrete Uniform Probability Law
Suppose that we have $n$ outcomes in our sample space and the probability of the outcomes are "equally likely". Then the probability of  an event $A$ is the number of elements in $A$ divided by the $n$.
$$
\begin{align*}
P(A) &= \frac{|A|}{n}
\end{align*}
$$
### Properties of Probability Law
> If $A \subset B$ then, $P(A) \leq P(B)$ 
> $P(A \cup B) = P(A) + P(B) - P(A \cap B)$ Inclusion exclusion principle
> $P(A \cup B) \leq P(A) + P(B)$