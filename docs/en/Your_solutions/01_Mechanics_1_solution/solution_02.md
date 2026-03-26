# Section 1 — Mechanics I
## 2. Range Optimization
 
### Problem Statement
For projectile motion, show analytically that the maximum range $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$ for a given initial velocity is achieved at a launch angle of $45^\circ$.
 
---
 
### Mathematical Proof
 
To find the angle $\theta$ that maximizes the range, we need to find the **critical point** of the function $R(\theta)$. This is done by taking the derivative of the range with respect to $\theta$ and setting it to zero.
 
**1. The Range Function:**
$$R(\theta) = \frac{v_0^2}{g} \sin(2\theta)$$
 
**2. Taking the Derivative ($dR/d\theta$):**
Using the chain rule, where the derivative of $\sin(2\theta)$ is $2\cos(2\theta)$:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta}(\sin 2\theta)$$
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta)$$
 
**3. Setting the Derivative to Zero:**
To find the maximum, we set $\frac{dR}{d\theta} = 0$:
$$\frac{2v_0^2}{g} \cos(2\theta) = 0$$
 
Since $v_0$ and $g$ are non-zero constants:
$$\cos(2\theta) = 0$$
 
**4. Solving for $\theta$:**
We know that $\cos(x) = 0$ when $x = 90^\circ$ (or $\pi/2$ radians).
$$2\theta = 90^\circ$$
$$\theta = 45^\circ$$
 
---
 
### Physical Interpretation
The range depends on the term $\sin(2\theta)$. The maximum possible value for any sine function is **1**. 
$$\sin(2\theta) = 1 \implies 2\theta = 90^\circ \implies \theta = 45^\circ$$
 
At this angle, the projectile perfectly balances its time in the air (vertical component) with its forward progress (horizontal component).
 
---
 
### Final Conclusion
The maximum range is achieved at **$\theta = 45^\circ$**.
