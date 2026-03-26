# Problem 7: Dynamics with Friction (Two-Block System)
 
A $5 \text{ kg}$ block (Block A) is placed on a $10 \text{ kg}$ block (Block B). Block B is pulled with a force of $45 \text{ N}$. Block A is tied to the wall. The coefficient of kinetic friction ($\mu_k$) for all surfaces is $0.2$. We find the acceleration of Block B.
 
---
 
## 1) Theory: Analysis of Forces
 
In this system, Block B is moving to the right, while Block A remains stationary relative to the wall. Friction acts at two interfaces for Block B:
1.  **Interface 1 (Between A and B):** Friction opposes the relative motion of B sliding under A.
2.  **Interface 2 (Between B and the floor):** Friction opposes the motion of B across the floor.
 
---
 
## 2) Step-by-Step Calculation of Friction Forces
 
**Given:**
- $m_A = 5 \text{ kg}$
- $m_B = 10 \text{ kg}$
- $\mu_k = 0.2$
- $g = 9.8 \text{ m/s}^2$
 
### A) Friction between Block A and Block B ($f_{k1}$)
The normal force exerted by A on B is $N_1 = m_A \cdot g$:
$$f_{k1} = \mu_k \cdot m_A \cdot g$$
$$f_{k1} = 0.2 \cdot 5 \cdot 9.8 = 9.8 \text{ N}$$
 
### B) Friction between Block B and the floor ($f_{k2}$)
The total normal force on the floor is the weight of both blocks ($N_2 = (m_A + m_B) \cdot g$):
$$f_{k2} = \mu_k \cdot (m_A + m_B) \cdot g$$
$$f_{k2} = 0.2 \cdot (5 + 10) \cdot 9.8 = 0.2 \cdot 15 \cdot 9.8 = 29.4 \text{ N}$$
 
---
 
## 3) Equation of Motion for Block B
 
Using Newton's Second Law ($\sum F = m \cdot a$) for Block B:
$$F_{applied} - f_{k1} - f_{k2} = m_B \cdot a$$
 
**Substitute the calculated values:**
$$45 - 9.8 - 29.4 = 10 \cdot a$$
$$45 - 39.2 = 10 \cdot a$$
$$5.8 = 10 \cdot a$$
 
**Final Acceleration:**
$$a = \frac{5.8}{10} = 0.58 \text{ m/s}^2$$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Why subtract both frictions?** Block B is "sandwiched." It feels the "rubbing" from the floor below AND the "rubbing" from Block A above. Both forces act to the left, opposing the $45 \text{ N}$ pull.
- **Why doesn't Block A move?** The tension in the rope tied to the wall perfectly cancels the $9.8 \text{ N}$ friction force acting on Block A, keeping it in equilibrium.
- **Result Analysis:** The net force is relatively small ($5.8 \text{ N}$), leading to a modest acceleration of $0.58 \text{ m/s}^2$. This makes sense given the high total friction ($39.2 \text{ N}$) relative to the applied force ($45 \text{ N}$).
 
---
 
## 5) WolframAlpha Verification
`solve 45 - (0.2 * 5 * 9.8) - (0.2 * (5+10) * 9.8) = 10 * a`
**Result:** `a = 0.58`
