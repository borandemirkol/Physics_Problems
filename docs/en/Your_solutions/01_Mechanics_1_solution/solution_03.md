# Section 1 — Mechanics I
## 3. Path Intersection: Alice vs. Bob
 
### Problem Statement
- **Alice's path:** $A(t) = (2+t, 8-3t)$
- **Bob's path:** $B(t) = (2t-1, 2t+2)$
 
The goal is to determine if their paths cross, and if they do, whether they collide at the same moment.
 
---
 
### 1. Intersection Analysis (Do the paths cross?)
For paths to intersect, there must exist a point $(x, y)$ that lies on both trajectories. We set $x_A = x_B$ and $y_A = y_B$, but we must use different time variables ($t_1$ for Alice and $t_2$ for Bob) because they might reach the same spot at different times.
 
**Step 1: Solve for the x-coordinates**
$$2 + t_1 = 2t_2 - 1 \implies t_1 = 2t_2 - 3$$
 
**Step 2: Substitute into the y-coordinates**
$$8 - 3t_1 = 2t_2 + 2$$
Substitute $t_1 = 2t_2 - 3$:
$$8 - 3(2t_2 - 3) = 2t_2 + 2$$
$$8 - 6t_2 + 9 = 2t_2 + 2$$
$$17 - 6t_2 = 2t_2 + 2 \implies 8t_2 = 15 \implies t_2 = 1.875$$
 
**Step 3: Find $t_1$**
$$t_1 = 2(1.875) - 3 = 0.75$$
 
**Result:** Their paths **intersect** at the point:
- $x = 2 + 0.75 = 2.75$
- $y = 8 - 3(0.75) = 5.75$
**Intersection Point: $(2.75, 5.75)$**
 
---
 
### 2. Collision Check (Do they meet at the same time?)
A collision only occurs if $t_1 = t_2$. 
Since **$0.75 \neq 1.875$**, they **DO NOT COLLIDE**. Alice passes through the point at $t=0.75$, while Bob arrives at that same location much later at $t=1.875$.
 
---
 
### 3. Minimum Distance Calculation
Since they do not collide, we find the minimum distance between them at any time $t$ by minimizing the distance function $d(t) = |\vec{B}(t) - \vec{A}(t)|$.
 
The distance vector $\vec{D}(t)$ is:
$$\vec{D}(t) = ( (2t-1) - (2+t) , (2t+2) - (8-3t) )$$
$$\vec{D}(t) = (t-3, 5t-6)$$
 
To minimize the squared distance $f(t) = (t-3)^2 + (5t-6)^2$:
$$f'(t) = 2(t-3) + 2(5t-6)(5) = 0$$
$$2t - 6 + 50t - 60 = 0 \implies 52t = 66 \implies t \approx 1.27 \text{ s}$$
 
**Minimum Distance:**
Substitute $t \approx 1.27$ into $d(t)$:
$$d_{min} = \sqrt{(1.27-3)^2 + (5(1.27)-6)^2} \approx \sqrt{2.99 + 0.12} \approx \mathbf{1.76 \text{ units}}$$
