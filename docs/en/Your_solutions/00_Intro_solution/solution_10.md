# Section 0 — Mathematical Foundations
## 10. Infinite Series (Ant's Path)

### Problem Statement
An ant moves 1m East, 1/2m North, 1/3m West, 1/4m South, 1/5m East, and so on. Determine the final position $(x, y)$.


### Analytical Approach
The movement can be split into independent $x$ and $y$ components using alternating series.

**1. X-coordinate (East-West):**
$$x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$$
This is the Leibniz formula for $\pi$:
$$x = \sum_{n=0}^{\infty} \frac{(-1)^n}{2n+1} = \frac{\pi}{4} \approx 0.785$$

**2. Y-coordinate (North-South):**
$$y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots$$
Factor out $1/2$:
$$y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)$$
The term in the parentheses is the natural logarithm of 2 ($\ln 2$):
$$y = \frac{1}{2} \ln(2) \approx 0.346$$


### Final Result
The ant's final position is:
**$(\frac{\pi}{4}, \frac{\ln 2}{2}) \approx (0.785, 0.346)$**.
