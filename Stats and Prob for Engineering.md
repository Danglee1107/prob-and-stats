# Statistics and Probability for Engineering

## 1. The Role of Statistics in Engineering

Statistics is often called the **science of data**.  
In engineering, statistics is used to:

- Understand variability in systems
- Analyze experimental data
- Improve product quality
- Design efficient processes
- Support decision making under uncertainty

Engineering systems are rarely perfectly predictable because measurements, manufacturing processes, and environmental conditions all contain randomness and variability.

Statistics provides tools to:

- Collect data
- Organize data
- Analyze data
- Draw conclusions from data

---

## Why Statistics Matters in Engineering

Engineers use statistics in many fields:

| Field | Example |
|---|---|
| Manufacturing | Reducing defects in products |
| Electrical Engineering | Noise analysis in signals |
| Civil Engineering | Reliability of structures |
| Mechanical Engineering | Failure analysis of machines |
| Computer Engineering | Performance evaluation of algorithms |

### Example

Suppose an engineer measures the lifetime of batteries:

$$
[102,\ 98,\ 101,\ 105,\ 97]
$$

The engineer wants to know:

- What is the average lifetime?
- How much variation exists?
- Can future battery lifetime be predicted?
- Is the manufacturing process reliable?

Statistics helps answer these questions.

---

# Types of Statistics

Statistics is commonly divided into two major branches.

---

## 1.1 Descriptive Statistics

Descriptive statistics focuses on:

- Collecting data
- Organizing data
- Summarizing data
- Presenting data clearly

The goal is to describe what the data looks like.

### Common Descriptive Tools

- Tables
- Charts
- Histograms
- Mean
- Median
- Variance
- Standard deviation

### Example

Given temperatures:

$$
[20,\ 22,\ 21,\ 19,\ 23]
$$

The mean temperature is:

$$
\bar{x} = \frac{20+22+21+19+23}{5} = 21
$$

This describes the center of the data.

---

## 1.2 Inferential Statistics

Inferential statistics uses sample data to make conclusions about a larger population.

Because measuring an entire population is often impossible, engineers collect samples and infer information from them.

### Main Goals

- Estimate population parameters
- Test hypotheses
- Predict future outcomes
- Make decisions under uncertainty

### Example

An engineer tests 50 light bulbs from a factory batch of 100,000 bulbs.

Using inferential statistics, the engineer can estimate:

- Average lifetime of all bulbs
- Probability of failure
- Reliability of the production process

---

# Population vs Sample

## Population

The complete set of all observations.

### Example

- All cars produced in a factory
- All resistors manufactured this year

---

## Sample

A subset selected from the population.

### Example

- 100 cars chosen for inspection
- 50 resistors selected for testing

---

# Parameters and Statistics

| Concept | Meaning |
|---|---|
| Parameter | Numerical description of a population |
| Statistic | Numerical description of a sample |

### Examples

Population mean:

$$
\mu
$$

Sample mean:

$$
\bar{x}
$$

Population variance:

$$
\sigma^2
$$

Sample variance:

$$
s^2
$$

---

# 2. Data Collection and Modeling

Engineering analysis depends heavily on how data is collected.

Poor data collection leads to poor conclusions.

---

# Methods of Data Collection

## 2.1 Retrospective Study

A retrospective study uses historical data already collected in the past.

### Examples

- Old production records
- Historical temperature measurements
- Previous machine failures

### Advantages

- Fast
- Inexpensive

### Disadvantages

- Data may be incomplete
- Limited control over variables

---

## 2.2 Observational Study

In an observational study, researchers observe a system without changing it.

### Example

Observing traffic flow at an intersection.

### Characteristics

- No experimental intervention
- Variables are recorded naturally

### Advantages

- Real-world behavior
- Useful when experiments are impossible

### Disadvantages

- Hard to determine causation
- Confounding variables may exist

---

## 2.3 Designed Experiments

A designed experiment intentionally changes variables to study their effects.

### Example

Testing how temperature affects material strength.

### Characteristics

- Controlled conditions
- Manipulated variables
- Systematic testing

### Advantages

- Strong conclusions
- Can identify causation

### Disadvantages

- Expensive
- Time consuming

---

# Variables in Engineering Experiments

## Independent Variable

The variable controlled by the engineer.

### Example

Voltage applied to a circuit.

---

## Dependent Variable

The variable being measured.

### Example

Current flowing through the circuit.

---

# Mathematical Modeling

Engineers build models to describe relationships between variables.

Two important types of models are:

1. Mechanistic models
2. Empirical models

---

# 2.4 Mechanistic Models

Mechanistic models are based on physical laws and scientific principles.

These models explain *why* something happens.

### Example: Ohm's Law

$$
V = IR
$$

Where:

- $V$ = voltage
- $I$ = current
- $R$ = resistance

This model comes from electrical physics.

---

## Characteristics of Mechanistic Models

- Based on theory
- Explain physical behavior
- Often highly accurate
- Require understanding of physics

### Examples

- Newton’s Laws
- Thermodynamics equations
- Fluid dynamics equations

---

# 2.5 Empirical Models

Empirical models are built from observed data rather than physical theory.

They are useful when the true mechanism is unknown or too complex.

### Example

Predicting machine failure from historical sensor data.

---

## Regression Models

A common empirical model is regression.

Simple linear regression:

$$
y = \beta_0 + \beta_1 x
$$

Where:

- $x$ = input variable
- $y$ = predicted output
- $\beta_0$ = intercept
- $\beta_1$ = slope

---

## Advantages of Empirical Models

- Easy to construct
- Useful with large datasets
- Good predictive ability

## Disadvantages

- May not explain physical causes
- Accuracy depends on data quality

---

# 3. Fundamentals of Probability

Probability is the mathematical study of randomness and uncertainty.

Statistics depends on probability theory because uncertainty exists in real-world data.

---

# Random Experiments

A random experiment is a process whose outcome cannot be predicted with certainty.

### Examples

- Tossing a coin
- Rolling a die
- Measuring component lifetime

---

# Sample Space

The sample space is the set of all possible outcomes.

Usually denoted by:

$$
S
$$

---

## Example: Tossing a Coin

Sample space:

$$
S = \{H, T\}
$$

Where:

- $H$ = heads
- $T$ = tails

---

## Example: Rolling a Die

Sample space:

$$
S = \{1,2,3,4,5,6\}
$$

---

# Events

An event is a subset of the sample space.

### Example

Event:

"Rolling an even number"

$$
A = \{2,4,6\}
$$

---

# Set Operations in Probability

---

## Union of Events

The union means:

- Event $A$
- OR event $B$
- OR both

Notation:

$$
A \cup B
$$

---

## Intersection of Events

The intersection means:

- Both $A$ and $B$ occur

Notation:

$$
A \cap B
$$

---

## Complement of an Event

The complement means:

- Event $A$ does not occur

Notation:

$$
A^c
$$

---

# Probability Rules

## Basic Probability Rule

For any event $A$:

$$
0 \le P(A) \le 1
$$

---

## Total Probability of Sample Space

$$
P(S) = 1
$$

---

## Complement Rule

$$
P(A^c) = 1 - P(A)
$$

---

## Addition Rule

For two events:

$$
P(A \cup B)=P(A)+P(B)-P(A \cap B)
$$

---

# Tree Diagrams

Tree diagrams visually represent sequential events.

### Example: Tossing Two Coins

Possible outcomes:

$$
\{HH, HT, TH, TT\}
$$

Tree diagrams help compute probabilities step-by-step.

---

# Venn Diagrams

Venn diagrams visually represent relationships between events.

They are useful for:

- Unions
- Intersections
- Complements

---

# 4. Counting Techniques

Counting techniques help determine the number of possible outcomes without listing everything manually.

These techniques are fundamental in probability.

---

# 4.1 Multiplication Rule

If a process has multiple steps:

- First step: $n_1$ choices
- Second step: $n_2$ choices
- Third step: $n_3$ choices

Then total outcomes:

$$
n_1 n_2 n_3
$$

---

## Example

A password contains:

- 2 letters
- 3 digits

Possible combinations:

$$
26^2 \times 10^3
$$

---

# 4.2 Permutations

Permutations are ordered arrangements.

Order matters.

---

## Formula for Permutations

$$
P(n,r)=\frac{n!}{(n-r)!}
$$

Where:

- $n$ = total objects
- $r$ = selected objects

---

## Example

How many ways can 3 students be arranged from 5 students?

$$
P(5,3) = \frac{5!}{2!} = 60
$$

---

# 4.3 Combinations

Combinations are selections where order does not matter.

---

## Formula for Combinations

$$
C(n,r)=\frac{n!}{r!(n-r)!}
$$

---

## Example

Choose 3 students from 5 students:

$$
C(5,3)=10
$$

---

# Difference Between Permutations and Combinations

| Concept | Order Matters? |
|---|---|
| Permutations | Yes |
| Combinations | No |

---

# Engineering Applications of Counting

Counting techniques are used in:

- Communication systems
- Network design
- Reliability analysis
- Cryptography
- Machine learning
- Algorithm analysis

---

# Summary

Statistics and probability form the mathematical foundation for engineering analysis.

Key ideas include:

- Statistics helps engineers analyze variability and uncertainty.
- Descriptive statistics summarizes data.
- Inferential statistics draws conclusions from samples.
- Data can be collected through retrospective studies, observational studies, and experiments.
- Mechanistic models rely on physics laws.
- Empirical models rely on observed data.
- Probability provides tools to analyze uncertainty.
- Counting techniques help calculate possible outcomes efficiently.

Together, these concepts allow engineers to:

- Design better systems
- Predict outcomes
- Improve reliability
- Make informed decisions using data