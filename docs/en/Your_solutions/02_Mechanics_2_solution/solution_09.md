# Problem 9: Vertical Throw with Air Drag (Linear Resistance)
 
We analyze a particle of mass $m$ thrown vertically with an initial velocity $v_0$ and initial position $x(0) = 10$. The motion is subject to gravity ($g$) and a drag force proportional to velocity ($kv$).
 
---
 
## 1) Equation of Motion
 
According to Newton's Second Law, the sum of forces acting on the particle during its upward motion is:
$$m \frac{dv}{dt} = -mg - kv$$
 
To solve for velocity $v(t)$, we rearrange the differential equation to separate variables:
$$\frac{dv}{mg + kv} = -\frac{dt}{m}$$
 
---
 
## 2) Analytical Solution for Velocity ($v$)
 
Integrating both sides from $t=0$ to $t$:
$$\int_{v_0}^{v(t)} \frac{dv}{g + \frac{k}{m}v} = -\int_{0}^{t} \frac{k}{m} dt'$$
 
Using the substitution $u = g + \frac{k}{m}v$, we get the logarithmic solution:
$$\ln\left( \frac{g + \frac{k}{m}v(t)}{g + \frac{k}{m}v_0} \right) = -\frac{k}{m}t$$
 
Exponentiating both sides and solving for $v(t)$:
$$v(t) = \left( v_0 + \frac{mg}{k} \right) e^{-\frac{k}{m}t} - \frac{mg}{k}$$
 
---
 
## 3) Determining Maximum Height ($H_{max}$)
 
The maximum height is reached when the velocity becomes zero ($v(t_{rise}) = 0$). 
Setting $v(t) = 0$ in the equation above:
$$0 = \left( v_0 + \frac{mg}{k} \right) e^{-\frac{k}{m}t_{rise}} - \frac{mg}{k} \implies e^{-\frac{k}{m}t_{rise}} = \frac{mg}{kv_0 + mg}$$
 
Integrating $v(t)$ to find position $x(t)$:
$$x(t) = x_0 + \int_{0}^{t} v(t') dt'$$
$$x(t) = 10 + \frac{m}{k}\left( v_0 + \frac{mg}{k} \right)(1 - e^{-\frac{k}{m}t}) - \frac{mg}{k}t$$
 
Substituting $t_{rise}$ into $x(t)$ gives the analytical $H_{max}$.
 
---
 
## 4) Comparison: With Drag vs. Without Drag
 
| Feature | Without Drag ($k=0$) | With Drag ($k > 0$) |
| :--- | :--- | :--- |
| **Acceleration** | Constant ($-g$) | Variable ($-g - \frac{k}{m}v$) |
| **Max Height** | $H = x_0 + \frac{v_0^2}{2g}$ | $H < x_0 + \frac{v_0^2}{2g}$ (Lower) |
| **Velocity Curve** | Linear | Exponential decay |
 
**Interpretation:** Air drag always performs negative work, dissipating mechanical energy. Consequently, the particle reaches a lower peak height and takes less time to reach it compared to a vacuum.
 
---
 
## 5) Numerical Simulation (WolframAlpha Logic)
 
To see the trajectory with specific values (e.g., $m=1, k=0.1, v_0=20$):
`x''(t) = -9.81 - 0.1*x'(t), x(0)=10, x'(0)=20`
 
