# Problem 12: Work and Energy with a Constant Force
 
A constant force acts on a body of mass $m = 2 \text{ kg}$:
$$\vec{F} = 6 \hat{i} + 2 \hat{j} \quad [\text{N}]$$
 
**Initial Conditions (at $t=0$):**
- Velocity $\vec{v}_0 = (1, -1) \text{ m/s}$
- Position $\vec{r}_0 = (0, 0) \text{ m}$
 
We determine the dynamics and verify the Work-Energy Theorem.
 
---
 
## 1) Acceleration Vector ($\vec{a}$)
Using Newton's Second Law ($\vec{a} = \vec{F}/m$):
$$\vec{a} = \frac{6 \hat{i} + 2 \hat{j}}{2} = 3 \hat{i} + 1 \hat{j} \quad [\text{m/s}^2]$$
The acceleration is constant since the force is constant.
 
---
 
## 2) Velocity $\vec{v}(t)$ and Position $\vec{r}(t)$
 
Integrating acceleration with respect to time ($t$):
$$\vec{v}(t) = \vec{v}_0 + \vec{a}t = (1 + 3t) \hat{i} + (-1 + t) \hat{j} \quad [\text{m/s}]$$
 
Integrating velocity to find position:
$$\vec{r}(t) = \vec{r}_0 + \int \vec{v}(t') dt' = (t + 1.5t^2) \hat{i} + (-t + 0.5t^2) \hat{j} \quad [\text{m}]$$
 
---
 
## 3) Motion Analysis at $t = 3 \text{ s}$
 
- **Velocity:** $\vec{v}(3) = (1 + 9) \hat{i} + (-1 + 3) \hat{j} = 10 \hat{i} + 2 \hat{j}$
- **Speed Squared ($v^2$):** $v^2 = 10^2 + 2^2 = 104$
- **Position (Displacement):** $\vec{r}(3) = (3 + 1.5 \cdot 9) \hat{i} + (-3 + 0.5 \cdot 9) \hat{j} = 16.5 \hat{i} + 1.5 \hat{j}$
 
---
 
## 4) Calculation of Work Done ($W$)
Work is the dot product of Force and Displacement ($\vec{d} = \vec{r}(3) - \vec{r}_0$):
$$W = \vec{F} \cdot \vec{d} = (6, 2) \cdot (16.5, 1.5)$$
$$W = (6 \cdot 16.5) + (2 \cdot 1.5) = 99 + 3 = 102 \text{ J}$$
 
---
 
## 5) Verification of Work-Energy Theorem
The theorem states $W = \Delta K = K_{final} - K_{initial}$.
 
- **Initial Kinetic Energy ($K_i$):**
$$v_0^2 = 1^2 + (-1)^2 = 2 \implies K_i = \frac{1}{2} \cdot 2 \cdot 2 = 2 \text{ J}$$
- **Final Kinetic Energy ($K_f$ at $t=3$):**
$$v_f^2 = 104 \implies K_f = \frac{1}{2} \cdot 2 \cdot 104 = 104 \text{ J}$$
- **Change in Kinetic Energy ($\Delta K$):**
$$\Delta K = 104 - 2 = 102 \text{ J}$$
 
**Conclusion:** Since $W = 102 \text{ J}$ and $\Delta K = 102 \text{ J}$, the **Work-Energy Theorem is verified**.
 
---
 
## 6) Trajectory Visualization (WolframAlpha Logic)
`parametric plot (t + 1.5t^2, -t + 0.5t^2) from t=0 to 3`
