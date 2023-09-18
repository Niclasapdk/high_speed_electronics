# High speed electronics in practice - exercises for lecture 4

## Exercise 4.1

The graph shows the BH curve for a transformer material. This task is solved graphically and approximately.

a. Determine $\mu_r$ for H = 200 A/m.

$$
\mu_r = \frac{B}{H\mu_0} = 3978
$$

b. Determine $\mu_r$ for H = 400 A/m.

$$
\mu_r = \frac{B}{H\mu_0} = 2387
$$

c. Determine the incremental $\mu_r$ when H varies between 150 A/m and 300 A/m.

$$
\Delta B = B(300) - B(150) = 0.23 \,\mathrm{\frac{Wb}{m^2}} \\
\Delta \mu_r = \frac{\Delta B}{\Delta H \cdot \mu_0} = 1220 \,\mathrm{\frac{H}{m}}
$$

d. Determine the initial permeability (relative permeability).

First part (up to H = 100 A/m) is linear.

$$
\mu_r = \frac{B}{H\mu_0} = \frac{100\,\mathrm{\frac{A}{m}}}{0.7\,\mathrm{\frac{Wb}{m^2}} \mu_0} = 5570
$$

e. Determine the saturation flux.

Asymptote at $\approx B = 1.35 \,\mathrm{\frac{Wb}{m^2}}$.

## Exercise 4.2

For the displayed transformer core, the iron has a BH curve as shown in the figure for Exercise 4.1. Use the
permeability we found for 400 A/m (if you don't have a value, then use $\mu_r$ = 2,000). We are not considering
hysteresis, and we assume the iron is linear. The winding consists of 200 turns, through which 4.5 A is sent.
The cross-sectional area of the legs of the core is $0.001 m^2$.

Note: We will use $\mu_r = 2000$.

a. Draw a magnetic diagram for the core and calculate the necessary path lengths and areas. An area
increase in the air gap is considered to be $1+\frac{2l}{\sqrt{A}}$.

$$
A_{air} = 1 + \frac{2l}{\sqrt{A}} \sqrt{A} = 1.13\mathrm{e}{-3} \,\mathrm{m^2} \\
l_{air} = 0.002 \,\mathrm{m} \\
l_2 = 0.238 \,\mathrm{m} \\
l_3 = l_4 = 0.64 \,\mathrm{m}
$$

b. Determine the reluctances and complete the magnetic equivalent diagram.

$$
R_1 = \frac{l_{air}}{\mu_0 A_{air}} = 1408451 \,\mathrm{H^{-1}} \\
R_2 = \frac{l_2}{\mu A} = 94697 \,\mathrm{H^{-1}} \\
R_3 = R_4 = \frac{l_3}{\mu A} = 254648 \,\mathrm{H^{-1}}
$$

c. Calculate the magnetic flux in each of the 3 legs.

Calculate reluctances.

$$
R_p = R_3 || R_4 = 127324 \,\mathrm{H^{-1}} \\
R_{tot} = R_1 + R_2 + R_p = 1630472 \,\mathrm{H^{-1}}
$$

Calculate magnetic current.

$$
\Phi_{tot} = \Phi_1 = \Phi_2 = \frac{NI}{R_{tot}} = 0.55\mathrm{e}{-3} \,\mathrm{Wb} \\
\Phi_3 = \Phi_4 = \frac{\Phi_1}{2} = 0.28\mathrm{e}{-3} \,\mathrm{Wb}
$$

d. Determine B and H in each of the 3 legs and in the air gap.

So for $B$ we get:

$$
B_1 = \frac{\Phi_1}{A_{air}} = 0.488 \,\mathrm{Wb}{m^2} \\
B_2 = \frac{\Phi_2}{A} = 0.552 \,\mathrm{Wb}{m^2} \\
B_3 = B_4 = \frac{\Phi_3}{A} = 0.276 \,\mathrm{Wb}{m^2}
$$

So for $H$ we use $H = \frac{F}{l} = \frac{\Phi R}{l}$

$$
H_1 = \frac{\Phi R_1}{l_1} = 388724 \,\mathrm{A_v} \\
H_2 = \frac{\Phi R_2}{l_2} = 220 \,\mathrm{A_v} \\
H_3 = H_4 = \frac{\Phi R_2}{l_2} = 110 \,\mathrm{A_v}
$$

## Exercise 4.3

The same core as in Exercise 4.2 is now connected to a voltage generator of 220 V (effective) at 50 Hz.

a. Determine the necessary flux in the core (middle leg).

b. Determine B and H in both the middle leg and the air gap.

## Exercise 4.4

A coil has the following specifications:
- Length: 1.2 m
- Number of turns: 750
- Diameter: 10 cm
- Current: 1.75 A
- The coil is "wrapped in air."

a. Calculate the H-field inside the coil.
b. Calculate the self-induction of the coil.

