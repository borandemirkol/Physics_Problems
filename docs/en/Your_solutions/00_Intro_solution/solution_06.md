# Section 0 — Mathematical Foundations
## 6. Function Analysis (Extrema)

### Problem Statement
Consider the function $f(x) = 3x^2 - 12x + 7$. Identify any local maxima or minima.


### Calculus Approach
To find the extrema, we must find the critical points where the first derivative is zero.

**Step 1: Find the first derivative $f'(x)$**
$$f'(x) = \frac{d}{dx}(3x^2 - 12x + 7) = 6x - 12$$

**Step 2: Set the derivative to zero**
$$6x - 12 = 0 \implies 6x = 12 \implies x = 2$$

**Step 3: Second Derivative Test**
To determine if it is a maximum or minimum, we find $f''(x)$:
$$f''(x) = 6$$
Since $f''(x) > 0$, the function is concave up, meaning $x = 2$ is a **local minimum**.

**Step 4: Calculate the y-coordinate**
$$f(2) = 3(2)^2 - 12(2) + 7 = 12 - 24 + 7 = -5$$


### Final Result
The function has a **local minimum** at the point **$(2, -5)$**.
