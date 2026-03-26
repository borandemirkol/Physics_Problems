# Problem 8: Work of a Variable Force and Potential Energy
 
We analyze a one-dimensional conservative force given by the linear relationship:
$$F(x) = -kx$$
where $k$ is a constant (Hooke's Law).
 
---
 
## 1) Equation of Motion
Using Newton's Second Law ($F = ma = m \frac{d^2x}{dt^2}$):
$$m \frac{d^2x}{dt^2} = -kx \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$
 
**General Solution:**
This is a second-order linear differential equation representing Simple Harmonic Motion (SHM). The solution is:
$$x(t) = A \cos(\omega t + \phi), \quad \text{where } \omega = \sqrt{\frac{k}{m}}$$
 
---
 
## 2) Calculation of Work Done ($W$)
The work done by a variable force during a displacement from $0$ to $x_0$ is the integral of the force over the path:
$$W = \int_{0}^{x_0} F(x) \, dx$$
 
**Substituting $F(x) = -kx$:**
$$W = \int_{0}^{x_0} (-kx) \, dx = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}$$
$$W = -\frac{1}{2}kx_0^2$$
 
---
 
## 3) Potential Energy Interpretation ($U$)
By definition, the change in potential energy is equal to the negative of the work done by a conservative force ($\Delta U = -W$):
$$U(x) - U(0) = -\int_{0}^{x} F(x') \, dx' = -(-\frac{1}{2}kx^2)$$
Assuming $U(0) = 0$:
$$U(x) = \frac{1}{2}kx^2$$
 
---
 
## 4) Verification of $F = -dU/dx$
To verify the relationship between force and potential energy, we take the negative derivative of the potential energy function:
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right)$$
$$-\frac{dU}{dx} = -\left( \frac{1}{2}k \cdot 2x \right) = -kx$$
 
**Conclusion:** Since $-\frac{dU}{dx} = F(x)$, the force is indeed conservative.
 
---
 
## 5) Graphical Analysis (WolframAlpha Logic)
- **$F(x) = -kx$:** A straight line passing through the origin with a negative slope. It represents a restoring force (always pointing toward equilibrium).
- **$U(x) = \frac{1}{2}kx^2$:** A parabola opening upwards. The minimum energy is at $x=0$.
 
**WolframAlpha Command for Visualization:**
`plot F = -2x and U = 0.5*2*x^2 from x=-5 to 5`
 
 
