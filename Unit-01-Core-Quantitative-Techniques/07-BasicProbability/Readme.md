# Basic Probability

## Introduction

Probability is a branch of mathematics that helps us measure the **chance of an event happening**.

In simple words:

> **Probability tells us how likely something is to happen.**

For example:

* What is the probability of getting a Head when a coin is tossed?
* What is the probability of getting a 6 when a dice is rolled?
* What is the probability of drawing an Ace from a deck of cards?

Probability is usually expressed as a fraction, decimal, or percentage.

---

# 1. Important Terms

Before solving probability questions, we need to understand some basic terms.

## Experiment

An **experiment** is an action or process that produces one or more possible results.

### Examples

* Tossing a coin
* Rolling a dice
* Drawing a card
* Picking a ball from a box

Each of these is called a **random experiment** because the exact result cannot be predicted with certainty before performing the experiment.

---

## Outcome

An **outcome** is a possible result of an experiment.

### Example: Tossing a Coin

The possible outcomes are:

```text
Head (H)
Tail (T)
```

Therefore:

```text
Outcomes = {H, T}
```

---

## Event

An **event** is a collection of one or more outcomes.

### Example

When rolling a dice, getting an even number is an event.

Possible outcomes are:

```text
{2, 4, 6}
```

Therefore:

```text
Event = Getting an even number
```

---

## Sample Space

The **sample space** is the set of all possible outcomes of an experiment.

It is generally represented by:

```text
S
```

### Example: Tossing a Coin

```text
S = {H, T}
```

Total possible outcomes:

```text
n(S) = 2
```

### Example: Rolling a Dice

```text
S = {1, 2, 3, 4, 5, 6}
```

Therefore:

```text
n(S) = 6
```

---

# 2. Basic Probability Formula

The basic formula of probability is:

```text
Probability = Number of Favourable Outcomes / Total Number of Possible Outcomes
```

Mathematically:

```text
P(E) = n(E) / n(S)
```

Where:

```text
P(E) = Probability of Event E

n(E) = Number of Favourable Outcomes

n(S) = Total Number of Outcomes
```

---

# 3. Probability of Tossing a Coin

When a coin is tossed once:

```text
S = {H, T}
```

Total outcomes:

```text
2
```

## Probability of Getting Head

Favourable outcomes:

```text
{H}
```

Therefore:

```text
P(H) = 1/2
```

## Probability of Getting Tail

```text
P(T) = 1/2
```

---

# 4. Two Coins

When two coins are tossed:

```text
S = {HH, HT, TH, TT}
```

Total outcomes:

```text
4
```

### Probability of Getting Two Heads

Favourable outcome:

```text
HH
```

Therefore:

```text
P(Two Heads) = 1/4
```

### Probability of Getting At Least One Head

Favourable outcomes:

```text
HH
HT
TH
```

Therefore:

```text
P(At Least One Head) = 3/4
```

---

# 5. Probability of Rolling a Dice

A standard dice has six possible outcomes:

```text
S = {1, 2, 3, 4, 5, 6}
```

Total outcomes:

```text
6
```

## Probability of Getting a 4

Favourable outcome:

```text
{4}
```

Therefore:

```text
P(4) = 1/6
```

---

## Probability of Getting an Even Number

Even numbers are:

```text
{2, 4, 6}
```

Favourable outcomes:

```text
3
```

Therefore:

```text
P(Even Number) = 3/6

= 1/2
```

---

## Probability of Getting a Number Greater Than 4

Possible numbers:

```text
{5, 6}
```

Therefore:

```text
P(Number > 4) = 2/6

= 1/3
```

---

# 6. Two Dice

When two dice are rolled:

```text
Total Possible Outcomes = 6 × 6

= 36
```

Each outcome can be represented as:

```text
(First Dice, Second Dice)
```

For example:

```text
(1, 1)
(1, 2)
(2, 1)
...
(6, 6)
```

## Example: Probability of Getting a Sum of 7

Possible combinations are:

```text
(1, 6)
(2, 5)
(3, 4)
(4, 3)
(5, 2)
(6, 1)
```

Total favourable outcomes:

```text
6
```

Therefore:

```text
P(Sum = 7) = 6/36

= 1/6
```

---

# 7. Probability with Cards

A standard deck contains:

```text
52 Cards
```

There are four suits:

* Hearts
* Diamonds
* Clubs
* Spades

Each suit contains:

```text
13 Cards
```

A deck contains:

```text
4 Aces
4 Kings
4 Queens
4 Jacks
```

---

## Example: Probability of Drawing an Ace

Favourable outcomes:

```text
4
```

Total cards:

```text
52
```

Therefore:

```text
P(Ace) = 4/52

= 1/13
```

---

## Example: Probability of Drawing a Red Card

Red suits are:

```text
Hearts
Diamonds
```

Total red cards:

```text
26
```

Therefore:

```text
P(Red Card) = 26/52

= 1/2
```

---

# 8. Probability of Complementary Events

Sometimes it is easier to find the probability of an event **not happening**.

The formula is:

```text
P(Not E) = 1 - P(E)
```

### Example

Find the probability of not getting a 6 when a dice is rolled.

Probability of getting 6:

```text
P(6) = 1/6
```

Therefore:

```text
P(Not 6) = 1 - 1/6

= 5/6
```

---

# 9. Impossible Event

An event that can never happen is called an **impossible event**.

Its probability is:

```text
P(Impossible Event) = 0
```

### Example

Getting a 7 when rolling a standard dice.

```text
P(7) = 0
```

---

# 10. Certain Event

An event that will definitely happen is called a **certain event**.

Its probability is:

```text
P(Certain Event) = 1
```

### Example

Getting a number less than 7 when rolling a standard dice.

Possible outcomes:

```text
{1, 2, 3, 4, 5, 6}
```

Therefore:

```text
P(Number < 7) = 1
```

---

# 11. Range of Probability

The value of probability always lies between:

```text
0 ≤ P(E) ≤ 1
```

Where:

```text
0 = Impossible Event

1 = Certain Event
```

Probability cannot be:

```text
Less than 0

Greater than 1
```

---

# 12. Probability Based on Balls

### Example

A box contains:

* 5 Red balls
* 3 Blue balls
* 2 Green balls

Total balls:

```text
5 + 3 + 2 = 10
```

## Probability of Picking a Red Ball

```text
P(Red) = 5/10

= 1/2
```

## Probability of Picking a Blue Ball

```text
P(Blue) = 3/10
```

## Probability of Not Picking a Green Ball

```text
P(Green) = 2/10
```

Therefore:

```text
P(Not Green) = 1 - 2/10

= 8/10

= 4/5
```

---

# 13. Important Concepts

## At Least

"At least" means:

```text
Equal to or More Than
```

For example:

```text
At least one Head
```

means:

```text
One Head or More
```

When multiple outcomes are involved, it is often easier to use the complement rule.

### Example

Find the probability of getting at least one Head when two coins are tossed.

Instead of counting:

```text
HH
HT
TH
```

We can calculate:

```text
P(At Least One Head)

= 1 - P(No Heads)
```

No Heads means:

```text
TT
```

Therefore:

```text
P(At Least One Head)

= 1 - 1/4

= 3/4
```

---

# 14. Important Formulas

## Basic Formula

```text
P(E) = Favourable Outcomes / Total Outcomes
```

---

## Complement Rule

```text
P(Not E) = 1 - P(E)
```

---

## Probability Range

```text
0 ≤ P(E) ≤ 1
```

---

## Two Coins

```text
Total Outcomes = 2²

= 4
```

---

## Three Coins

```text
Total Outcomes = 2³

= 8
```

---

## n Coins

```text
Total Outcomes = 2ⁿ
```

---

## Two Dice

```text
Total Outcomes = 6²

= 36
```

---

# 15. Common Mistakes

### Mistake 1: Incorrect Total Outcomes

Always count all possible outcomes.

For two coins:

```text
HH
HT
TH
TT
```

Remember:

```text
HT ≠ TH
```

because the outcomes occur in different positions.

---

### Mistake 2: Forgetting to Simplify

For example:

```text
3/6 = 1/2
```

Always simplify the final answer where possible.

---

### Mistake 3: Confusing "At Least" and "Exactly"

```text
Exactly One Head
```

means only:

```text
HT
TH
```

But:

```text
At Least One Head
```

means:

```text
HH
HT
TH
```

---

### Mistake 4: Probability Cannot Be Greater Than 1

Always check:

```text
0 ≤ Probability ≤ 1
```

If your answer is greater than 1, something is wrong.

---

# 16. Quick Summary

Probability measures the chance of an event happening.

The most important formula is:

```text
P(E) = Favourable Outcomes / Total Possible Outcomes
```

Important concepts include:

```text
Sample Space → All Possible Outcomes

Event → Required Outcome or Outcomes

Favourable Outcomes → Outcomes That Satisfy the Condition
```

Remember:

```text
Impossible Event = 0

Certain Event = 1

0 ≤ P(E) ≤ 1
```

For complementary events:

```text
P(Not E) = 1 - P(E)
```

For basic aptitude problems, understanding the **sample space** and correctly counting the **favourable outcomes** is the most important step.
