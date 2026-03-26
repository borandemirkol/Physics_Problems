# Problem 2: Harmonic Motion and Energy Analysis
 
A mass of $m = 10 \text{ kg}$ is attached to a spring and follows the displacement equation:
$$x(t) = 0.2 \cos(10\pi t)$$
where $x$ is in meters and $t$ is in seconds.
 
---
 
## 1) Theory: Standard Form of SHM
 
The general equation for a Simple Harmonic Oscillator is:
$$x(t) = A \cos(\omega t + \phi)$$
 
By comparing the given equation $x(t) = 0.2 \cos(10\pi t)$ to the standard form, we identify:
- **Amplitude ($A$):** $0.2 \text{ m}$
- **Angular Frequency ($\omega$):** $10\pi \text{ rad/s}$
- **Phase Constant ($\phi$):** $0$
 
---
 
## 2) Calculation of the Spring Constant ($k$)
 
In a mass-spring system, the angular frequency is defined by the relationship:
$$\omega = \sqrt{\frac{k}{m}} \implies \omega^2 = \frac{k}{m}$$
 
To find $k$, we isolate it:
$$k = m \cdot \omega^2$$
 
Substitute the known values ($m = 10 \text{ kg}$ and $\omega = 10\pi$):
$$k = 10 \cdot (10\pi)^2$$
$$k = 10 \cdot 100\pi^2 = 1000\pi^2$$
 
Using the approximation $\pi^2 \approx 9.87$:
$$k \approx 9869.6 \text{ N/m}$$
 
---
 
## 3) Calculation of Total Mechanical Energy ($E$)
 
The total mechanical energy in a harmonic oscillator is the sum of kinetic and potential energy. At the maximum displacement (amplitude), all energy is stored as potential energy:
$$E_{total} = \frac{1}{2} k A^2$$
 
Substitute the values for $k$ and $A$:
$$E_{total} = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2$$
$$E_{total} = 500\pi^2 \cdot 0.04$$
$$E_{total} = 20\pi^2$$
 
Using the approximation $\pi^2 \approx 9.87$:
$$E_{total} \approx 197.39 \text{ J}$$
 
---
 
## 4) Physical Interpretation and Soundness
 
- **Spring Stiffness:** A value of nearly $10,000 \text{ N/m}$ indicates a very stiff spring, which is consistent with maintaining a high angular frequency ($10\pi \approx 31.4 \text{ rad/s}$) while moving a relatively large mass of $10 \text{ kg}$.
- **Energy Check:** The energy depends on the square of both amplitude and frequency. Even though the amplitude is small ($20 \text{ cm}$), the high frequency results in a significant energy level of nearly $200 \text{ Joules}$.
