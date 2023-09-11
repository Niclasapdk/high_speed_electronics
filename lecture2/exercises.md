# High speed electronics in practice - exercises for lecture 1

## Exercise 2.1

The figure shows a plate capacitor consisting of two circular plates with a dielectric in between.

a. Calculate the capacitance value of the capacitor.

Given:
- $d = 1\mathrm{mm} = 1\mathrm{e}{-3} \,\mathrm{m}$
- $r = 5\mathrm{mm} = 5\mathrm{e}{-3} \,\mathrm{m}$

$$
C = \frac{Q}{V} = \frac{\varepsilon A}{d}
$$

In vaccum $C = 5.56 \mathrm{pF}$.

b. The capacitor is charged up to $10 \mathrm{V}$. Determine the strength and direction of the E-field and the D-field
between the plates.

$$
V \approx E d \iff E \approx \frac{V}{d} = 10 \mathrm{e}{3} \,\mathrm{\frac{V}{m}}
$$

$$
D = E \varepsilon = 707.3 \mathrm{\frac{nC}{m^2}}
$$

c. Calculate the stored energy in the capacitor.

$$
U = \frac{1}{2} C V^2 = 275 \mathrm{e}{-12} \,\mathrm{J}
$$

d. Calculate the stored charge in the capacitor.

$$
Q = C V = 55.6 \mathrm{e}{-12} \,\mathrm{C}
$$

e. The capacitor is now discharged through a 1 ohm resistor. Calculate the change in the capacitor's charge
(in C/s) at the initial point.

The current is the rate of charge leaving the capacitor.

$$
I = G V = 10 \mathrm{\frac{C}{s}}
$$

## Exercise 2.2

A $100\mathrm{km}$ long sea cable with $C = 150 \mathrm{\frac{nF}{m}}$ transports electricity between Sweden and Finland. The voltage
is $400 \mathrm{kV}$ DC.

a. Calculate the energy contained in the cable when it is charged. Express the answer in kWh.

$$
U = \frac{1}{2} C V^2 \\
C_{tot} = 15 \,\mathrm{mF} \\
U = 1.2 \,\mathrm{GJ} = 333.3 \,\mathrm{kWh}
$$

b. How long will it take to charge the cable with $10 \,\mathrm{A}$?

$$
Q = C_{tot} V = 6000 \,\mathrm{C} \\
t = \frac{Q}{I} = 600 \,\mathrm{s}
$$

## Exercise 2.3

The schematic below shows a connection of 4 capacitors connected to a DC voltage of 10 V.

a. Calculate the resulting capacitance as experienced by the voltage source.

$$
C_{tot} = \Bigl(\bigl((4^{-1} + 3^{-1})^{-1} + 2\bigr)^{-1} + 1^{-1}\Bigr)^{-1} = 0.7878 \,\mathrm{F}
$$

b. Calculate the voltage across each of the capacitors.
