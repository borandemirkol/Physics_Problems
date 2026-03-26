# Problem 6: Energy Dissipation in a Bouncing Ball
 
A tennis ball is dropped from an initial height $H_0 = 2.0 \text{ m}$. After each bounce, it loses $30\%$ of its mechanical energy. We aim to find the maximum height it reaches after the **second** bounce ($H_2$).
 
---
 
## 1) Theory: Energy-Height Relationship
 
The total mechanical energy of the ball at its maximum height is purely gravitational potential energy:
$$E = mgh$$
 
Since $m$ and $g$ are constant, the height $h$ is directly proportional to the mechanical energy ($E \propto h$).
 
If the ball loses $30\%$ of its energy during a bounce, it retains $70\%$ ($0.70$) of its energy to rise back up:
$$E_{after} = 0.70 \cdot E_{before} \implies H_{after} = 0.70 \cdot H_{before}$$
 
---
 
## 2) Step-by-Step Calculation
 
### Phase 1: After the First Bounce ($H_1$)
The ball falls from $H_0 = 2.0 \text{ m}$. Upon hitting the ground, it loses $30\%$ of its energy.
$$H_1 = 0.70 \cdot H_0$$
$$H_1 = 0.70 \cdot 2.0 = 1.4 \text{ m}$$
 
### Phase 2: After the Second Bounce ($H_2$)
The ball now falls from $H_1 = 1.4 \text{ m}$. Upon the second impact, it loses another $30\%$ of its *remaining* energy.
$$H_2 = 0.70 \cdot H_1$$
$$H_2 = 0.70 \cdot 1.4 = 0.98 \text{ m}$$
 
---
 
## 3) General Formula Approach (Optional Verification)
 
For $n$ bounces, the height can be calculated using the power of the retention factor ($r = 0.70$):
$$H_n = H_0 \cdot (r)^n$$
 
For the second bounce ($n=2$):
$$H_2 = 2.0 \cdot (0.70)^2$$
$$H_2 = 2.0 \cdot 0.49 = 0.98 \text{ m}$$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Energy Dissipation:** Each time the ball hits the floor, energy is dissipated through sound, heat (friction during deformation), and internal vibrations of the ball.
- **Result Analysis:** The ball fails to reach its original height each time. Starting at $200 \text{ cm}$, it drops to $140 \text{ cm}$ after the first bounce, and then to $98 \text{ cm}$ after the second. This exponential decay is typical for real-world bouncing objects.
 
---
 
## 5) WolframAlpha Verification
`2.0 * (0.70)^2`
**Result:** `0.98`
