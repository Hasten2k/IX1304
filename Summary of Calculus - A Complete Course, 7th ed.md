# Summary of Calculus - A Complete Course 7th ed - R. Adams, C. Essex

## Chapter P

### Real Numbers and the Real Line

Real numbers can be expressed as decimal values, both positive and negative.

```
1.0000, 2.2412, -5.2314, π, e
```

Real numbers can be represented on a number line (the **Real Line**).

The symbol `ℝ` denotes the Real Numbers.

#### Algebraic Properties

Real numbers can be added, subtracted, multiplied and divided to produce new real numbers.

#### Order Properties

If `x` lies to the left of `y` on the number line, `x < y` or `y > x`.

#### Rules for Inequalities

If `a`, `b`, and `c` are real numbers, then:

1. `a < b` ⟹ `a + b < b + c`
2. `a < b` ⟹ `a - b < b - c`
3. `a < b` and `c > 0` ⟹ `ac < bc`
4. `a < b` and `c < 0` ⟹ `ac > bc`; this leads to `-a > -b`
5. `a > 0` ⟹ `1/a > 0`
6. `0 < a < b` ⟹ `1/b < 1/a`

#### The Completeness Property

The **Completeness Property** states that for any set **A** with real numbers in it, if it exists a number `y` that is larger than any number in **A**, then `y` is called an **Upper Bound**. If such a `y` exists, then there exists another number which is smaller than any other in **A**. This smaller number is called a **Least Upper Bound** or **Supremum** of **A**.

#### Subsets of Real Numbers

1. The **Natural Numbers**. This is the same as the positive integers (1, 2, 3 etc). Note that the **Positive Integers** does not include the number 0.
2. The **Integers**, the numbers 0, 1, 2, 3 etc.
3. The **Rational Numbers**. That is, numbers that can be expressed as a fraction `(m / n)` where `n ≠ 0`. Rational Numbers can be either **terminating** or **repeating**.

  1. **Terminating** numbers are fractions that end with an infinite string of zeros.
  2. **Repeating** numbers are numbers that end in an infinite string of digits that repeat over and over.

**Real numbers** that are not a part of the **Rational** subset are called **Irrational Numbers**.

The **Rational Numbers** does not possess the [**completeness property**](#the-completeness-property). There is for example no rational number whose square is equal to 2.

### Intervals

An **interval** is a subset of the Real Number Line. It can be **open**, **closed** or **half-open**.

1. An **Open Interval** `(a, b)` is defined as all real numbers `x` where the inequality `a < x < b` is true.
2. A **Closed Interva** `[a, b]` is defined as all real numbers `x` where the equality `a ≤ x ≤ b` is true.
3. A **half-open Interval** `(a, b]` or `[a, b)`, is defined as all real numbers `x` where the inequality `a < x ≤ b` or `a ≤ x < b` is true.

In a graph, endpoints (also boundary points) of an interval are marked **●** if the point is included in the interval, and **○** if the point is excluded from the inteval.

A **Finite Interval** `(a, b)` has a fixed length `(b - a)` while an **Infinite Interval** is just that. The whole Real Line, `ℝ`, is an infinite interval: `(-∞, ∞)`. Note that the interval is open, not closed.

### Absolute values

An **Absolute Value** of a number, `x`, also known as a **magnitude**, is denoted `|x|`

#### Properties of absolute values

1. `|-a| = |a|`

  - A number and it's negative have the same absolute value.

2. `|ab| = |a||b|` and `|a / b| = |a| / |b|`

  - The absolute value of a product of two numbers, is the product of their absolute values.

3. `|a ± b| ≤ |a| + |b|`

  - The absolute value of a sum or difference between two values, is less than or equal to the sum of their absolute values. This is called the **triangle inequality**. It is derived from the fact that no side in a triangle can be longer than the sum of the two other sides.
