# Problem 7: Parametric Trajectory and Dynamics
 
Given the parametric equations: $x(t) = 2t^2$ and $y(t) = 3t^3$.
 
---
 
## 1) Elimination of Parameter $t$
From the x-equation: $t^2 = \frac{x}{2} \implies t = \left(\frac{x}{2}\right)^{1/2}$
Substitute $t$ into the y-equation:
$$y = 3t^3 = 3 \left(\sqrt{\frac{x}{2}}\right)^3 = \frac{3}{2\sqrt{2}}x^{3/2}$$
**Trajectory Equation:** $y = 1.06 x^{1.5}$ (This describes a power-law curve).
 
## 2) Velocity and Acceleration Vectors
- **Velocity ($\vec{v}$):**
  - $v_x = \frac{dx}{dt} = 4t$
  - $v_y = \frac{dy}{dt} = 9t^2$
  - $\vec{v}(t) = (4t)\hat{i} + (9t^2)\hat{j}$
  - **Magnitude:** $|\vec{v}(t)| = \sqrt{16t^2 + 81t^4} = t\sqrt{16 + 81t^2}$
 
- **Acceleration ($\vec{a}$):**
  - $a_x = \frac{dv_x}{dt} = 4$
  - $a_y = \frac{dv_y}{dt} = 18t$
  - $\vec{a}(t) = 4\hat{i} + (18t)\hat{j}$
  - **Magnitude:** $|\vec{a}(t)| = \sqrt{16 + 324t^2}$
 
## 3) Interpretation
**Is the acceleration constant?** No. While the x-component is constant ($4 \text{ m/s}^2$), the y-component ($18t$) increases linearly with time, making the total acceleration time-dependent.
