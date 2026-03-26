# Problem 11: Dynamics with a Time-Dependent Force
 
A particle of mass $m = 3 \text{ kg}$ is subject to a time-varying force field:
$$\vec{F}(t) = (15t) \hat{i} + (3t - 12) \hat{j} + (-6t^2) \hat{k} \quad [\text{N}]$$
 
**Initial Conditions (at $t=0$):**
- Position $\vec{r}_0 = (5, 2, -3) \text{ m}$
- Velocity $\vec{v}_0 = (2, 0, 1) \text{ m/s}$
 
We determine the velocity $\vec{v}(t)$ and position $\vec{r}(t)$ functions.
 
---
 
## 1) Theory: Newton's Second Law and Integration
 
First, we find the acceleration $\vec{a}(t)$ by dividing the force by mass ($\vec{a} = \vec{F}/m$):
$$\vec{a}(t) = \frac{15t}{3} \hat{i} + \frac{3t - 12}{3} \hat{j} + \frac{-6t^2}{3} \hat{k}$$
$$\vec{a}(t) = (5t) \hat{i} + (t - 4) \hat{j} + (-2t^2) \hat{k} \quad [\text{m/s}^2]$$
 
To find velocity and position, we perform successive integrations with respect to time.
 
---
 
## 2) Step 1: Calculating Velocity $\vec{v}(t)$
 
$$\vec{v}(t) = \vec{v}_0 + \int_{0}^{t} \vec{a}(t') dt'$$
 
Integrating term-by-term:
- **$v_x$:** $2 + \int 5t \, dt = 2 + \frac{5}{2}t^2$
- **$v_y$:** $0 + \int (t - 4) \, dt = \frac{1}{2}t^2 - 4t$
- **$v_z$:** $1 + \int -2t^2 \, dt = 1 - \frac{2}{3}t^3$
 
**Result:** $\vec{v}(t) = (2.5t^2 + 2) \hat{i} + (0.5t^2 - 4t) \hat{j} + (1 - \frac{2}{3}t^3) \hat{k} \quad [\text{m/s}]$
 
---
 
## 3) Step 2: Calculating Position $\vec{r}(t)$
 
$$\vec{r}(t) = \vec{r}_0 + \int_{0}^{t} \vec{v}(t') dt'$$
 
Integrating term-by-term:
- **$x(t)$:** $5 + \int (2.5t^2 + 2) \, dt = 5 + \frac{2.5}{3}t^3 + 2t$
- **$y(t)$:** $2 + \int (0.5t^2 - 4t) \, dt = 2 + \frac{0.5}{3}t^3 - 2t^2$
- **$z(t)$:** $-3 + \int (1 - \frac{2}{3}t^3) \, dt = -3 + t - \frac{2}{12}t^4 = -3 + t - \frac{1}{6}t^4$
 
**Result:** $\vec{r}(t) = (\frac{5}{6}t^3 + 2t + 5) \hat{i} + (\frac{1}{6}t^3 - 2t^2 + 2) \hat{j} + (-\frac{1}{6}t^4 + t - 3) \hat{k} \quad [\text{m}]$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Order of Motion:** The force is quadratic in time ($t^2$) for the $z$-axis, which results in a 4th-degree polynomial for position. This is consistent with the fundamental theorem of calculus (integration increases power by one).
- **Initial State Check:** If we set $t=0$, we retrieve $\vec{r}(0) = (5, 2, -3)$ and $\vec{v}(0) = (2, 0, 1)$, matching the given initial conditions perfectly.
- **Dimensional Analysis:** Force [N] divided by Mass [kg] yields acceleration [m/s²]. Successive integrations yield velocity [m/s] and position [m].
 
---
 
## 5) WolframAlpha Verification
`integrate [5t, t-4, -2t^2] dt, initial values [2, 0, 1]`
