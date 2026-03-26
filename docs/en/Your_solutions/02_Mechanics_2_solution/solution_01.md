# Section 2 — Mechanics II
 
# Problem 1: Gravitational Dependence of a Simple Pendulum
 
We analyze how the period of a simple pendulum changes with gravity and determine the physical length required for a specific period on Earth.
 
---
 
## 1) Theory: The Pendulum Period Formula
 
For small oscillations, the period ($T$) of a simple pendulum depends only on its length ($L$) and the local gravitational acceleration ($g$):
 
$$T = 2\pi \sqrt{\frac{L}{g}}$$
 
This formula shows that the period is inversely proportional to the square root of gravity ($T \propto 1/\sqrt{g}$).
 
---
 
## 2) Period on the Moon
 
**Given:**

- Period on Earth ($T_E$): $4.0 \text{ s}$

- Gravity on Earth ($g_E$): $\approx 9.81 \text{ m/s}^2$

- Gravity on the Moon ($g_M$): $\frac{1}{6}g_E$
 
Let us set up the ratio between the Moon's period and Earth's period:
 
$$\frac{T_M}{T_E} = \frac{2\pi \sqrt{\frac{L}{g_M}}}{2\pi \sqrt{\frac{L}{g_E}}} = \sqrt{\frac{g_E}{g_M}}$$
 
Substitute $g_M = \frac{1}{6}g_E$:
 
$$\frac{T_M}{T_E} = \sqrt{\frac{g_E}{\frac{1}{6}g_E}} = \sqrt{6} \approx 2.4495$$
 
Now, solve for $T_M$:
 
$$T_M = \sqrt{6} \cdot T_E = \sqrt{6} \cdot 4 \approx 9.80 \text{ s}$$
 
**Result:** On the Moon, the pendulum swings much slower, taking about $9.80 \text{ s}$ to complete one full cycle.
 
---
 
## 3) Required Length for $T = 1 \text{ s}$ on Earth
 
We want the period to be exactly $1 \text{ s}$ on Earth ($g_E = 9.81 \text{ m/s}^2$). We need to isolate length ($L$) from the period formula:
 
$$T = 2\pi \sqrt{\frac{L}{g}}$$
 
Square both sides:
 
$$T^2 = 4\pi^2 \frac{L}{g}$$
 
Isolate $L$:
 
$$L = \frac{g T^2}{4\pi^2}$$
 
Substitute $T = 1 \text{ s}$ and $g = 9.81 \text{ m/s}^2$:
 
$$L = \frac{9.81 \cdot 1^2}{4\pi^2} = \frac{9.81}{39.4784} \approx 0.2485 \text{ m}$$
 
**Final Length:**

$$L \approx 24.85 \text{ cm}$$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Why does the period increase on the Moon?** Gravity is the restoring force for a pendulum. If gravity is weaker, the force pulling the bob back to the center is weaker, meaning it takes more time to complete a swing.

- **Why is the length so short for $1 \text{ s}$?** A standard "seconds pendulum" (which takes 1 second to swing from one side to the other, hence a total period of 2 seconds) is about $1 \text{ meter}$ long. Since our desired total period is $1 \text{ second}$, the length must be roughly a quarter of a meter ($25 \text{ cm}$), which matches our calculation ($L \propto T^2$).

 
