# Problem 4: Energy Conservation and Inelastic Collision
 
A $0.5 \text{ kg}$ block (Block A) slides down a frictionless track from a height $h = 3.0 \text{ m}$ and collides with a $1.5 \text{ kg}$ block (Block B) at rest. They stick together after the collision.
 
---
 
## 1) Phase 1: Energy Conservation (The Slide)
 
As Block A slides down the frictionless track, its gravitational potential energy ($U$) is converted into kinetic energy ($K$).
 
**Theory:**
$$E_{initial} = E_{final} \implies m_A g h = \frac{1}{2} m_A v_1^2$$
 
We solve for the speed of Block A just before the collision ($v_1$):
$$v_1 = \sqrt{2gh}$$
 
**Calculation:**
Using $g = 9.81 \text{ m/s}^2$ and $h = 3.0 \text{ m}$:
$$v_1 = \sqrt{2 \cdot 9.81 \cdot 3.0} = \sqrt{58.86}$$
$$v_1 \approx 7.67 \text{ m/s}$$
 
---
 
## 2) Phase 2: Conservation of Momentum (The Collision)
 
The collision is **perfectly inelastic** because the blocks stick together. While kinetic energy is not conserved during the impact, the total linear momentum of the system must be conserved.
 
**Theory:**
$$\vec{P}_{initial} = \vec{P}_{final}$$
$$m_A v_1 + m_B v_2 = (m_A + m_B) V_{combined}$$
 
Since Block B is initially at rest ($v_2 = 0$):
$$m_A v_1 = (m_A + m_B) V_{combined}$$
 
**Calculation:**
- $m_A = 0.5 \text{ kg}$
- $m_B = 1.5 \text{ kg}$
- $v_1 = 7.67 \text{ m/s}$
 
$$(0.5) \cdot (7.67) = (0.5 + 1.5) \cdot V_{combined}$$
$$3.835 = 2.0 \cdot V_{combined}$$
 
Solving for the final speed ($V_{combined}$):
$$V_{combined} = \frac{3.835}{2.0} \approx 1.918 \text{ m/s}$$
 
---
 
## 3) Physical Interpretation and Analysis
 
- **Speed Reduction:** Notice that the final speed ($1.92 \text{ m/s}$) is significantly lower than the initial speed ($7.67 \text{ m/s}$). This is expected because the total mass of the moving system increased four-fold ($0.5 \text{ kg}$ to $2.0 \text{ kg}$), while the momentum remained constant.
- **Energy Loss:** In this inelastic collision, a large portion of the kinetic energy was converted into internal energy (heat/deformation). 
    - Initial $K \approx 14.7 \text{ J}$
    - Final $K \approx 3.68 \text{ J}$
    - Nearly $75\%$ of the energy was dissipated.
 
---
 
## 4) WolframAlpha Verification
To check the combined steps in one go:
`solve (0.5 * sqrt(2 * 9.81 * 3.0)) = (0.5 + 1.5) * V`
**Result:** `V ≈ 1.918 m/s`
