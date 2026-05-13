# 1. Addition Rule

## Definition

The **Addition Rule** calculates the probability that **at least one** of two events occurs.

$$
P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

Where:

- $P(A)$ = probability of event $A$
- $P(B)$ = probability of event $B$
- $P(A \cap B)$ = probability that both $A$ and $B$ occur
- $P(A \cup B)$ = probability that either $A$ or $B$ occurs

---

## Why Subtract the Intersection?

When adding $P(A)$ and $P(B)$ together, the overlap $P(A \cap B)$ is counted twice.

Therefore, we subtract it once to avoid double counting.

---

## Special Case: Mutually Exclusive Events

If events cannot happen together:

$$
P(A \cap B) = 0
$$

Then:

$$
P(A \cup B) = P(A) + P(B)
$$

---

## Example

Suppose:

$$
P(A)=0.6
$$

$$
P(B)=0.5
$$

$$
P(A \cap B)=0.2
$$

Then:

$$
P(A \cup B)=0.6+0.5-0.2
$$

$$
=0.9
$$

---