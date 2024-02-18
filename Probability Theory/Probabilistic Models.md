The formulation of a probabilistic model consists of only one experiment. That is, if we have an experiment of flipping a coin three times, we wouldn't have three experiments, just one. From the experiment, we have a **sample space** which is the set containing all of the possible outcomes of the experiment. Subsets of the sample space are called **events**. Under a probability law, we can assign a non-negative number to an event.

The sample space for the experiment of flipping a coin three times will be the set $A = \set{HHH, HHT, ..., TTT}$.

>[!Elements of A probabilistic Model ]
>**Sample Space:** Denoted as $\Omega$, is the set of all possible **outcomes**  of an experiment.
**Events**: A subset of the sample space, a collection of possible outcomes.
**Outcome:** denoted as $\omega$.
**Probability Law: ** Under some probability law $P:\mathcal{P}(\Omega) \to [0,1]$, assigns an event $A$ to a non-negative number $P(A)$. It is considered the "likelihood" of $A$.


### Appropriate Sample Spaces
When choosing an appropriate sample space, we must consider the uniqueness of an outcome and that we always obtain an outcome from our experiment that is to be included in our sample space. When we say that there needs to be unique outcome, we say that the outcomes are **mutually exclusive**. For example, imagine our experiment is rolling a die. The possible outcome cannot be "1 or 2" or "2 or 4". The outcome has to be either "1", "2", ... , "6". We cannot have two outcomes simultaneously. When we always obtain an outcome that is in our sample space, then the chosen sample space is **collectively exhaustive**.

>[!note] 
>**Mutually Exclusive:** can't happen at the same time.
>**Collectively Exhaustive**: During an experiment, there is always an outcome obtained that is in our sample space.

### Probability Law Axioms
> (Non-negativity) $P(A) \geq 0$
> (Disjoint Additivity) Suppose $A_{1,}A_{2,}A_3,...$ are disjoint events. Then $P(A_{1}\cup A_{2} \cup A_{3} \cup ...) = P(A_{1)} + P(A_{2}) + P(A_{3}) +  ...$
> (Normalization) $P(\Omega) = 1$

>[!info] 
>From our normalization and additivity axiom, we can derive another formulation.
>Since $\Omega \cap \emptyset = \emptyset$, Thus $$