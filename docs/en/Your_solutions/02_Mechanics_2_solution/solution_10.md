# Problem 10: Force Field and Power in 3D Motion
 
A particle of mass $m = 0.5 \text{ kg}$ follows a trajectory defined by the following time-dependent position equations:
- $x(t) = 5t^2 - t$
- $y(t) = 2t^3$
- $z(t) = -3t + 2$
 
We determine the velocity, momentum, acceleration, force, and power.
 
---
 
## 1) Velocity Vector ($\vec{v}$)
Velocity is the first derivative of position with respect to time ($v = \frac{dr}{dt}$):
- $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
- $v_y = \frac{d}{dt}(2t^3) = 6t^2$
- $v_z = \frac{d}{dt}(-3t + 2) = -3$
 
**Result:** $\vec{v}(t) = (10t - 1) \hat{i} + 6t^2 \hat{j} - 3 \hat{k} \quad [\text{m/s}]$
 
---
 
## 2) Momentum Vector ($\vec{p}$)
Momentum is the product of mass and velocity ($\vec{p} = m\vec{v}$):
- $p_x = 0.5(10t - 1) = 5t - 0.5$
- $p_y = 0.5(6t^2) = 3t^2$
- $p_z = 0.5(-3) = -1.5$
 
**Result:** $\vec{p}(t) = (5t - 0.5) \hat{i} + 3t^2 \hat{j} - 1.5 \hat{k} \quad [\text{kg}\cdot\text{m/s}]$
 
---
 
## 3) Acceleration Vector ($\vec{a}$)
Acceleration is the derivative of velocity ($\vec{a} = \frac{dv}{dt}$):
- $a_x = \frac{d}{dt}(10t - 1) = 10$
- $a_y = \frac{d}{dt}(6t^2) = 12t$
- $a_z = \frac{d}{dt}(-3) = 0$
 
**Result:** $\vec{a}(t) = 10 \hat{i} + 12t \hat{j} + 0 \hat{k} \quad [\text{m/s}^2]$
 
---
 
## 4) Force Acting on the Particle ($\vec{F}$)
Using Newton's Second Law ($\vec{F} = m\vec{a}$):
- $F_x = 0.5(10) = 5$
- $F_y = 0.5(12t) = 6t$
- $F_z = 0.5(0) = 0$
 
**Result:** $\vec{F}(t) = 5 \hat{i} + 6t \hat{j} + 0 \hat{k} \quad [\text{N}]$
 
---
 
## 5) Power Transferred by the Field ($P$)
Power is the dot product of the Force and Velocity vectors ($P = \vec{F} \cdot \vec{v}$):
$$P(t) = (F_x v_x) + (F_y v_y) + (F_z v_z)$$
$$P(t) = [5 \cdot (10t - 1)] + [6t \cdot (6t^2)] + [0 \cdot (-3)]$$
$$P(t) = (50t - 5) + 36t^3 + 0$$
 
**Result:** $P(t) = 36t^3 + 50t - 5 \quad [\text{W}]$
 
---
 
## 6) Physical Interpretation
- **Motion Type:** The particle experiences a constant force in the $x$-direction and a time-dependent (increasing) force in the $y$-direction. The motion in $z$ is at a constant velocity, meaning no net force acts on the $z$-axis.
- **Power:** The positive $t^3$ and $t$ terms indicate that the field is doing increasing amounts of work on the particle as time progresses, significantly increasing its kinetic energy.
