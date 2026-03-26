# Problem 3: Conservation of Energy in a Simple Pendulum
 
A pendulum with a length $L = 1.0 \text{ m}$ is released from an initial angle $\theta_0 = 15^\circ$. We aim to calculate the speed ($v$) of the bob at the lowest point of its swing (the bottom).
 
---
 
## 1) Theory: Mechanical Energy Conservation
 
In the absence of air resistance and friction at the pivot, the total mechanical energy is conserved. 
- At the **release point** (maximum angle), the energy is purely potential ($U$).
- At the **bottom point** (equilibrium), the energy is purely kinetic ($K$).
 
$$E_{top} = E_{bottom} \implies mgh = \frac{1}{2}mv^2$$
 
To find the speed $v$, we simplify the equation:
$$v = \sqrt{2gh}$$
 
---
 
## 2) Geometric Calculation of Height ($h$)
 
The height $h$ is the vertical distance the bob drops from its initial position to the bottom. 
- The total length of the string is $L$.
- When tilted at an angle $\theta$, the vertical distance from the pivot to the bob is $L \cos\theta$.
- Therefore, the height $h$ relative to the bottom is:
$$h = L - L \cos\theta_0 = L(1 - \cos\theta_0)$$
 
Substitute the given values ($L = 1.0 \text{ m}, \theta_0 = 15^\circ$):
$$h = 1.0 \cdot (1 - \cos 15^\circ)$$
Using $\cos 15^\circ \approx 0.9659$:
$$h = 1.0 \cdot (1 - 0.9659) = 0.0341 \text{ m}$$
 
---
 
## 3) Calculation of Final Speed ($v$)
 
Now, substitute the height $h$ into the energy equation ($g = 9.81 \text{ m/s}^2$):
$$v = \sqrt{2 \cdot 9.81 \cdot 0.0341}$$
$$v = \sqrt{0.6690}$$
$$v \approx 0.818 \text{ m/s}$$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Small Angle Approximation:** Since $15^\circ$ is a relatively small angle, we expect the height drop to be very small (only $3.4 \text{ cm}$), which results in a modest speed of approximately $0.8 \text{ m/s}$.
- **Mass Independence:** Notice that the mass ($m$) of the bob cancelled out in the calculation. This confirms that for any mass, the speed at the bottom depends only on the release height, consistent with Galileo's observations on falling bodies.
 
---
 
## 5) WolframAlpha Verification
To verify the trigonometric height and final speed:
`sqrt(2 * 9.81 * (1.0 * (1 - cos(15 degrees))))`
**Result:** `0.8179 m/s`
