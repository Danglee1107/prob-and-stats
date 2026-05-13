# Law of Total Probability

## Definition

The **Law of Total Probability** breaks a probability into several mutually exclusive cases.

$$
P(A)=\sum_i P(A \mid B_i)P(B_i)
$$

Where:

- $B_1, B_2, \dots, B_n$ form a partition of the sample space
- The events are mutually exclusive
- Their union equals the entire sample space

---

## Two-Case Form

For two cases:

$$
P(A)=P(A \mid B)P(B)+P(A \mid B^c)P(B^c)
$$

Where:

- $B^c$ is the complement of $B$

---

## Interpretation

We compute the probability of $A$ by considering all possible scenarios.

---

## Example

Suppose:

- 60% of products come from Factory 1
- 40% come from Factory 2

Defect probabilities:

$$
P(D \mid F_1)=0.02
$$

$$
P(D \mid F_2)=0.05
$$

Then:

$$
P(D)=0.02(0.6)+0.05(0.4)
$$

$$
=0.012+0.020
$$

$$
=0.032
$$

---