# Section 1 — Mechanics I
## 4. Vector Calculus: Velocity and Acceleration
 
### Problem Statement
The position vector of an object is given by:
$$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$$
 
Find the velocity ($\vec{v}$) and acceleration ($\vec{a}$) vectors as a function of time.
 
---
 
### Mathematical Derivation
 
**1. Velocity Vector ($\vec{v}$):**
Velocity is the first derivative of the position vector with respect to time ($t$).
$$\vec{v}(t) = \frac{d\vec{r}}{dt}$$
$$\vec{v}(t) = \frac{d}{dt}(3t^2)\hat{i} + \frac{d}{dt}(5t - 8t^2)\hat{j}$$
Using the power rule:
$$\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}$$
 
**2. Acceleration Vector ($\vec{a}$):**
Acceleration is the first derivative of velocity (or the second derivative of position).
$$\vec{a}(t) = \frac{d\vec{v}}{dt}$$
$$\vec{a}(t) = \frac{d}{dt}(6t)\hat{i} + \frac{d}{dt}(5 - 16t)\hat{j}$$
$$\vec{a}(t) = 6\hat{i} - 16\hat{j}$$
 
---
 
### Observation
The acceleration vector is **constant** (independent of time $t$). The object experiences a constant force in both the $x$ and $y$ directions.
 
**Final Result:**
- $\vec{v}(t) = 6t\hat{i} + (5-16t)\hat{j}$
- $\vec{a}(t) = 6\hat{i} - 16\hat{j}$
