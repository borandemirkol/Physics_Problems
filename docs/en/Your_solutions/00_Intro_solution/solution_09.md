# Section 0 — Mathematical Foundations
## 9. Optimization Problem

### Problem Statement
Find the dimensions of a rectangle with maximum area located under the curve $y = 3 - x^2$ in the first quadrant.


### Mathematical Model
Let the corner of the rectangle on the curve be $(x, y)$.
- **Width:** $x$
- **Height:** $y = 3 - x^2$
- **Area ($A$):** $A(x) = x \cdot (3 - x^2) = 3x - x^3$

**Step 1: Find the derivative $A'(x)$**
$$A'(x) = 3 - 3x^2$$

**Step 2: Find the critical point**
Set $A'(x) = 0$:
$$3 - 3x^2 = 0 \implies x^2 = 1 \implies x = 1$$
*(Note: x = -1 is ignored as it is not in the first quadrant).*

**Step 3: Find the corresponding height**
$$y = 3 - (1)^2 = 2$$


### Final Result
The dimensions for the maximum area are **$x = 1$** and **$y = 2$**. The maximum area is **2**.
