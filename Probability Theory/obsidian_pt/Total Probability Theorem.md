Let $A_{1},A_{2}, ... , A_{n}$ be disjoint sets that form a partition of the sample space. Then 
$$
\begin{align*}\\
\\ P(B) &= P(A_{1} \cap B) + P(A_{2}\cap B) + .. +P(A_{n}\cap B)\\
&= P(A_1)P(B|A_{1}) + P(A_2)P(B|A_{2}) + ... +P(A_n)P(B|A_{n})\\
&=P(B)P(A_{1}|B) + P(B)P(A_{2}|B) + ... + P(B)P(A_{n}|B)
\end{align*}
$$
Intuitively, we are partitioning $B$ with the partitioned events $A_i$.  The probability of $B$ is then weighted based on the scenario of $A_i$.