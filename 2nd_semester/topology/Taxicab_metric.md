## 🧮 Taxicab Metric and Open Balls

### 📌 Definition: Taxicab Metric

The **Taxicab metric** (also called the **Manhattan metric** or **\( L^1 \) norm**) is defined on \( \mathbb{R}^2 \) as:

\[
d(x, y) = |x_1 - y_1| + |x_2 - y_2|
\]

for \( x = (x_1, x_2), y = (y_1, y_2) \in \mathbb{R}^2 \).

It measures the total horizontal and vertical distance, like a taxi driving on a city grid.

---

### 🧾 Example:

Let \( x = (2, 3) \) and \( y = (5, 7) \).  
Then,

\[
d(x, y) = |2 - 5| + |3 - 7| = 3 + 4 = 7
\]

---

### 📐 Visual Intuition:

Unlike Euclidean circles, **open balls** in the Taxicab metric look like **diamonds** (rotated squares). This is because all points that satisfy:

\[
d(x, y) < r
\]

form a region where the sum of coordinate differences is less than \( r \).

---

### 🟢 Open Ball in Taxicab Metric

Let \( B(x, r) \) be the **open ball** of radius \( r \) centered at \( x \in \mathbb{R}^2 \). Then:

\[
B(x, r) = \{ y \in \mathbb{R}^2 : d(x, y) < r \}
\]

With taxicab metric:

\[
B((x_1, x_2), r) = \{ (y_1, y_2) : |x_1 - y_1| + |x_2 - y_2| < r \}
\]

This region forms a **diamond** shape.

---

### ⚙️ Application in Engineering:

- The Taxicab metric is used in **VLSI design** and **routing algorithms** where movement is constrained to horizontal and vertical paths.
- Also used in **signal distance** when differences along individual components matter more than Euclidean similarity.

---

### 🧠 Quick Comparison:

| Metric | Distance Formula | Shape of Open Ball |
|--------|------------------|--------------------|
| Euclidean | \( \sqrt{(x_1 - y_1)^2 + (x_2 - y_2)^2} \) | Circle |
| Taxicab  | \( |x_1 - y_1| + |x_2 - y_2| \)             | Diamond (rotated square) |

---

### 📝 Practice Task

- [ ] Draw an open ball of radius 1 centered at (0, 0) in taxicab metric.
- [ ] Compare with Euclidean ball of same radius.
