# High speed electronics in practice - exercises for lecture 1

## Exercise 1.1

Three electric charges are placed in the xy-plane ($z=0$) as shown in the figure.

a. Determine the electric field strength at point A.

$$
\vec{E}(r) = \frac{Q_p}{4\pi\varepsilon \cdot r^2} \vec{r}
$$

The fields evaluated at A have the values:

$$
\vec{E_{00,A}} = \frac{-1/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot \sqrt{2}^2} \cdot \left(\frac{1}{\sqrt{2}}\hat{i} + \frac{1}{\sqrt{2}}\hat{j}\right)
$$

$$
\vec{E_{01,A}} = \frac{2/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot 1^2} \cdot \hat{i}
$$

$$
\vec{E_{10,A}} = \frac{2/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot 1^2} \cdot \hat{j}
$$

$$
\vec{E_{total}} = \vec{E_{00,A}} + \vec{E_{01,A}} + \vec{E_{00,A}}
$$

b. Determine the electric potential at point A.

$$
V = \frac{Q_p}{4\pi\varepsilon \cdot r}
$$

$$
V_{00,A} = \frac{-1/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot \sqrt{2}}
$$

$$
V_{01,A} = \frac{2/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot 1}
$$

$$
V_{10,A} = \frac{2/9 \,\mathrm{nC}}{4\pi\varepsilon \cdot 1}
$$

$$
V_{total} = V_{00,A} + V_{01,A} + V_{10,A} = \frac{2.91155684915524\cdot 10^{-11}}{\varepsilon}
$$

c. An electron is placed at point A. Calculate the force that affects the electron. The charge of the electron is $Q = -1.602 \cdot 10^{-19} \,\mathrm{C}$.

$$
\vec{F} = Q \cdot \vec{E_{total}} = 1.65 (\hat{i} + \hat{j}) \,\mathrm{N/C} \cdot (-1.602 \cdot 10^{-19} \,\mathrm{C}) = - 0.2638 \cdot 10^{-18} \cdot (\hat{i} + \hat{j}) \,\mathrm{N}
$$

d. Given the mass of the electron is $9.107 \cdot 10^{-31} \,\mathrm{kg}$, calculate the acceleration of the electron.

$$
\vec{a} = \frac{\vec{F}}{m} = -289.62\cdot10^9 (\hat{i} + \hat{j})
$$

e. Replace the three charges with respectively $2 \mathrm{C}$, $2 \mathrm{C}$, and $-1 \mathrm{C}$. Calculate the magnitude of the force that
will affect a charge of $1 \mathrm{C}$ at point $A$. Convert to kg (or kp).

Same equations as before, but replace $Q_p$ with the new charges.

## Exercise 1.2

We use spherical coordinates.

a. Calculate the electric field at the $2 \mathrm{\mu C}$ charge caused by the other two charges.

$$
\vec{E_7} = \frac{7\cdot10^{-6}\,\mathrm{C}}{4\pi\varepsilon \cdot (0.5)^2} \angle -120\degree
$$

$$
\vec{E_{-4}} = \frac{4\cdot10^{-6}\,\mathrm{C}}{4\pi\varepsilon \cdot (0.5)^2} \angle 0\degree
$$

$$
\vec{E_{total}} = \vec{E_{7}} + \vec{E_{-4}} = 36 \cdot 10^{-3} \hat{i} - 252 \sqrt{3} \cdot 10^{-3} \hat{j}
$$

b. Determine the force that affects the $2 \mathrm{\mu C}$ charge.

$$
\vec{F} = Q \cdot \vec{E_{total}} = 2 \cdot 10^{-6} \left( 36 \cdot 10^{-3} \hat{i} - 252 \sqrt{3} \cdot 10^{-3} \hat{j} \right)
$$
