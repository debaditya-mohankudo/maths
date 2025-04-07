## 🧮 Taxicab Metric and Open Balls

### 📌 Definition: Taxicab Metric

The **Taxicab metric** (also called the **Manhattan metric** or **L₁ norm**) is defined on ℝ² as:

**d(x, y) = |x₁ − y₁| + |x₂ − y₂|**

for points x = (x₁, x₂) and y = (y₁, y₂) in ℝ².

It measures the total horizontal and vertical distance — like a taxi driving on a city grid.

---

### 🧾 Example:

Let x = (2, 3) and y = (5, 7).  
Then:  
**d(x, y) = |2 − 5| + |3 − 7| = 3 + 4 = 7**

---

### 📐 Visual Intuition:

In the taxicab metric, **open balls** look like rotated squares (diamonds), not circles.

All points (x, y) satisfying **|x₁ − y₁| + |x₂ − y₂| < r** lie inside an open ball of radius *r*.

---

### 🟢 Open Ball in Taxicab Metric

Let **B(x, r)** be the open ball of radius *r* centered at point **x** in ℝ²:

**B(x, r) = { y in ℝ² : d(x, y) < r }**

With taxicab metric:

**B((x₁, x₂), r) = { (y₁, y₂) : |x₁ − y₁| + |x₂ − y₂| < r }**

This region forms a **diamond shape**.

---

### ⚙️ Application in Engineering:

- Used in **VLSI circuit design**, where wires can only go vertically or horizontally.
- Also relevant in **grid-based routing**, **logistics**, and **signal comparison**.

---

### 🧠 Quick Comparison:

| Metric     | Formula                            | Shape of Open Ball     |
|------------|------------------------------------|-------------------------|
| Euclidean  | √((x₁−y₁)² + (x₂−y₂)²)              | Circle                  |
| Taxicab    | |x₁−y₁| + |x₂−y₂|                   | Diamond (rotated square) |
