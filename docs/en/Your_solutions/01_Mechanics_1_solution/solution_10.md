# Problem 10: Analysis of a 3D Helix Path
 
The position is given by: $\vec{r}(t) = (a \cos\omega t, a \sin\omega t, bt)$.
 
---
 
## 1) Equation of the Trajectory
Squaring the x and y components:
$$x^2 + y^2 = a^2 \cos^2(\omega t) + a^2 \sin^2(\omega t) = a^2 (\cos^2\omega t + \sin^2\omega t) = a^2$$
This shows that the projection on the XY plane is a **circle** of radius $a$. Since $z = bt$ increases linearly with time, the point moves upward while circling, forming a **Circular Helix**.
 
## 2) Path Length ($s$) from $t=0$ to $t=t_0$
The velocity vector is: $\vec{v}(t) = (-a\omega \sin\omega t, a\omega \cos\omega t, b)$
The speed (magnitude of velocity) is:
$$|\vec{v}| = \sqrt{(-a\omega \sin\omega t)^2 + (a\omega \cos\omega t)^2 + b^2} = \sqrt{a^2\omega^2 + b^2}$$
Since the speed is constant, the path length $s$ is:
$$s = \int_{0}^{t_0} |\vec{v}| dt = t_0 \sqrt{a^2\omega^2 + b^2}$$
 
## 3) Special Cases
- **If $b = 0$:** The motion is a pure circle in the XY plane.
- **If $\omega = 0$:** The motion is a straight line along the Z-axis.
## 4) Interactive HTML
 
