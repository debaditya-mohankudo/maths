# What is a Metric Space?

A **metric space** is a mathematical structure that allows us to *measure distances* between elements of a set.

---

## 📘 Formal Definition

A metric space is a pair **(X, d)** where:

- **X** is a non-empty set.
- **d: X × X → ℝ** is a function called a **metric** (or distance function).

The function **d(x, y)** must satisfy the following four properties for all **x, y, z ∈ X**:

1. **Non-negativity**:  
   \( d(x, y) \geq 0 \)

2. **Identity of Indiscernibles**:  
   \( d(x, y) = 0 \iff x = y \)

3. **Symmetry**:  
   \( d(x, y) = d(y, x) \)

4. **Triangle Inequality**:  
   \( d(x, z) \leq d(x, y) + d(y, z) \)

---

## 🔢 Example: Euclidean Space

Let \( X = \mathbb{R}^2 \), the 2D Cartesian plane. Define the distance function as:

\[
d(x, y) = \sqrt{(x_1 - y_1)^2 + (x_2 - y_2)^2}
\]

This is the standard **Euclidean distance**. The pair \( (\mathbb{R}^2, d) \) is a metric space.

---

## ⚙️ Application in Engineering

In Electrical Engineering, the concept of a metric appears in many forms, such as:

- Signal distance
- Error analysis (e.g., Mean Squared Error)
- Norms in vector spaces

All of these rely on the idea of **measuring distances**, which is the core idea behind metric spaces.

---

> **Tip**: Many theoretical results in analysis and topology rely on metric spaces, because they give us a structured way to talk about convergence, continuity, and limits.
