# Bayes Theorem

## Definition

Bayes Theorem reverses conditional probabilities.

$$
P(A \mid B)=\frac{P(B \mid A)P(A)}{P(B)}
$$

Where:

- $P(A)$ = prior probability
- $P(B \mid A)$ = likelihood
- $P(B)$ = evidence
- $P(A \mid B)$ = posterior probability

Condition:

$$
P(B) > 0
$$

---

## Using Total Probability

Often:

$$
P(B)=\sum_i P(B \mid A_i)P(A_i)
$$

So Bayes theorem becomes:

$$
P(A_k \mid B)=
\frac{P(B \mid A_k)P(A_k)}
{\sum_i P(B \mid A_i)P(A_i)}
$$

---

## Interpretation

Bayes theorem updates probabilities after observing new information.

---

## Example

Suppose:

- Disease prevalence:

$$
P(D)=0.01
$$

- Test sensitivity:

$$
P(T \mid D)=0.95
$$

- False positive rate:

$$
P(T \mid D^c)=0.03
$$

Find probability a person has the disease given a positive test.

First compute:

$$
P(T)=P(T \mid D)P(D)+P(T \mid D^c)P(D^c)
$$

$$
=0.95(0.01)+0.03(0.99)
$$

$$
=0.0392
$$

Then:

$$
P(D \mid T)=\frac{0.95(0.01)}{0.0392}
$$

$$
\approx 0.242
$$

So even with a positive test, the probability of actually having the disease is about:

$$
24.2\%
$$

---