# Section 1 — Mechanics I
## 1. Projectile Motion Analysis
 
### Problem Statement
A projectile is launched from the ground with:
- **Initial Velocity ($v_0$):** $100 \text{ m/s}$
- **Launch Angle ($\theta$):** $37^\circ$
- **Assumptions:** No air resistance, $g = 9.8 \text{ m/s}^2$
- **Approximations:** $\sin(37^\circ) \approx 0.6$, $\cos(37^\circ) \approx 0.8$
 
---
 
### 1. Derivation of Differential Equations
To describe the motion, we use Newton's Second Law ($\vec{F} = m\vec{a}$) in a 2D Cartesian coordinate system.
 
**Horizontal Direction ($x$):**
There are no horizontal forces (ignoring air resistance).
$$m \frac{d^2x}{dt^2} = 0 \implies \frac{dv_x}{dt} = 0$$
By integrating, the horizontal velocity remains constant:
$$v_x(t) = v_0 \cos \theta$$
 
**Vertical Direction ($y$):**
The only force is the gravitational force acting downwards.
$$m \frac{d^2y}{dt^2} = -mg \implies \frac{dv_y}{dt} = -g$$
By integrating once, we get the vertical velocity:
$$v_y(t) = v_0 \sin \theta - gt$$
By integrating again, we get the vertical position:
$$y(t) = (v_0 \sin \theta)t - \frac{1}{2}gt^2$$
 
---
 
### 2. Calculations
 
#### A) Time of Flight ($t_{flight}$)
The projectile returns to the ground when $y(t) = 0$:
$$0 = (v_0 \sin \theta)t - \frac{1}{2}gt^2$$
Solving for $t$ (excluding $t=0$):
$$t_{flight} = \frac{2 v_0 \sin \theta}{g} = \frac{2 \cdot 100 \cdot 0.6}{9.8} \approx 12.24 \text{ s}$$
 
#### B) Maximum Height ($H$)
The peak is reached when the vertical velocity is zero ($v_y = 0$).
$$H = \frac{(v_0 \sin \theta)^2}{2g} = \frac{(100 \cdot 0.6)^2}{2 \cdot 9.8} = \frac{3600}{19.6} \approx 183.67 \text{ m}$$
 
#### C) Total Range ($R$)
The range is the horizontal distance at the end of the flight time.
$$R = v_x \cdot t_{flight} = (v_0 \cos \theta) \cdot \left( \frac{2 v_0 \sin \theta}{g} \right) = \frac{v_0^2 \sin(2\theta)}{g}$$
$$R = \frac{100^2 \cdot \sin(74^\circ)}{9.8} \approx \frac{10000 \cdot 0.96}{9.8} \approx 979.59 \text{ m}$$
 
---
 
### Final Summary
- **Time of Flight:** $12.24 \text{ s}$
- **Maximum Height:** $183.67 \text{ m}$
- **Total Range:** $979.59 \text{ m}$
 
 
