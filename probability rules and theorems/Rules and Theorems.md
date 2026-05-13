# Probability Rules and Theorems

Probability theory provides mathematical tools for analyzing uncertainty and random events.  
These rules form the foundation of statistics, machine learning, engineering, and data science.

---

# Summary Table

| Concept                        | Formula                                    | Purpose                         |
| ------------------------------ | ------------------------------------------ | ------------------------------- |
| [[Addition Rule (Union Rule)]] | $P(A \cup B)=P(A)+P(B)-P(A \cap B)$        | Probability of either event     |
| [[Conditional Probability]]    | $P(A \mid B)=\frac{P(A \cap B)}{P(B)}$     | Probability under information   |
| [[Multiplication Rule]]        | $P(A \cap B)=P(A \mid B)P(B)$              | Joint probability               |
| [[Independence]]               | $P(A \cap B)=P(A)P(B)$                     | Events unrelated                |
| [[Law of Total Probability]]   | $P(A)=\sum_i P(A \mid B_i)P(B_i)$          | Split into cases                |
| [[Bayes Theorem]]              | $P(A \mid B)=\frac{P(B \mid A)P(A)}{P(B)}$ | Reverse conditional probability |

---

# Relationships Between the Rules

## Conditional Probability → Multiplication Rule

Starting from:

$$
P(A \mid B)=\frac{P(A \cap B)}{P(B)}
$$

Multiply both sides by $P(B)$:

$$
P(A \cap B)=P(A \mid B)P(B)
$$

---

## Multiplication Rule + Independence

If $A$ and $B$ are independent:

$$
P(A \mid B)=P(A)
$$

Substitute into multiplication rule:

$$
P(A \cap B)=P(A)P(B)
$$

---

## Total Probability + Bayes Theorem

Bayes theorem depends on the denominator:

$$
P(B)
$$

which is commonly computed using the Law of Total Probability.

---

# Key Ideas to Remember

- Addition Rule → probability of either event
- Conditional Probability → probability with extra information
- Multiplication Rule → probability of both events
- Independence → events do not influence each other
- Total Probability → split problem into cases
- Bayes Theorem → update probability using evidence

---
# Links

- [[Addition Rule (Union Rule)]]
- [[Conditional Probability]]
-  [[Independence]]
- [[Multiplication Rule]]
- [[Law of Total Probability]]
- [[Bayes Theorem]]
