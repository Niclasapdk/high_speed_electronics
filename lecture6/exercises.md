# High speed electronics in practice - exercises for lecture 6

## Exercise 6.1

The figure shows a transformer that is to be used in a power supply. The relative permeability of the core is 2500, and the core can be considered linear.

a. Draw a magnetic equivalent diagram for the transformer and calculate the reluctance of the air gap and the iron core.
Consider an area increase of $\frac{2l}{\sqrt{A}}$ the air gap, l is the length of the air gap, A is the actual area.

Length of iron is:
$$
l_{iron} = 2 (0.13 - 0.03) + 2(0.115 - 0.03) - 0.0009 = 0.37 \,\mathrm{m}
$$

Reluctance of iron core:
$$
R_{iron} = \frac{l}{\mu A} = 130.5 \,\mathrm{k\frac{A}{Wb}}
$$

Reluctance of the air gap:
$$
A = 0.03^2 = 0.0009 \,\mathrm{m^2} \\
A_{air} = A (1+\frac{2 \cdot 0.0009}{\sqrt{A}}) = 954 \mathrm{e}{-6} \,\mathrm{m^2} \\
R_{air} = \frac{l_{air}}{\mu_0 A_{air}} = 750.7 \,\mathrm{k\frac{A}{Wb}}
$$

b. Determine the magnetic flux in the iron core when a current of 475 mA flows in the winding.

$$
F = N I = 855 \,\mathrm{A_v} \\
\Phi = \frac{F}{R_{tot}} = \frac{F}{R_{air} + R_{iron}} = 970.2 \,\mathrm{\mu Wb}
$$

c. Calculate the magnetic voltage drop across the iron core and the air gap, respectively.

$$
F_{iron} = R_{iron} \Phi = 126.7 \,\mathrm{A} \\
F_{air} = R_{air} \Phi = 728.3 \,\mathrm{A}
$$

d. Determine the magnetic field strength (H-field) in the iron core and the air gap, respectively.

$$
H = \frac{F}{l}
$$

So

$$
H_{iron} = \frac{F_{iron}}{l_{iron}} = 343 \,\mathrm{\frac{A}{m}} \\
H_{air} = \frac{F_{air}}{l_{air}} = 809.3 \,\mathrm{k\frac{A}{m}}
$$

e. Calculate the "necessary flux" found in the core when the transformer is connected to a sinusoidal
voltage of 230 V (effective), 50 Hz.

Using

$$
\mathrm{emf} = \omega \Phi N
$$

where $\omega$ is angular frequency.

We get

$$
\Phi = \frac{\mathrm{emf}}{\omega N} = 406.7 \,\mathrm{Wb}
$$

## Exercise 6.2

The beam shown in the figure can move on the rails to the right and left without significant friction. The
rails are as long as necessary (infinitely long). The beam is electrically conductive.
The beam is at rest at time t = 0 s. After t = 0 s, the current generator supplies a current of 1.75 A in the
direction shown. The magnetic field of $0.98 \,\mathrm{Wb/m^2}$ is in the direction shown in figure (out of the paper).
The beam is 10 cm long and has a mass of 250 g.

a. What is the force that is applied to the beam after t = 0 s? Indicate the magnitude and the direction as either right or left.

Use the car formula
$$
F = BIl = 0.171 \,\mathrm{N}
$$

Force is to the left because of right hand rule.

b. Calculate the beam's acceleration.

We use bro Newton's 2nd law of movement speed.
$$
F = m a \implies a = \frac{F}{m} = 0.686 \,\mathrm{\frac{m}{s^2}}
$$

c. After 2.1 seconds, the beam is slowed down by an external force so that the speed becomes constant. What is the speed, and how large must the external force be?

The speed after $2.1$ seconds is
$$
v_{2.1} = a t = 1.44 \,\mathrm{\frac{m}{s}}
$$

The external force must be of same size as $F$, since $F_{tot} = F - F_{external} = 0$.
The external force must be to the right.

$$
F_{external} = F = 0.171 \,\mathrm{N}
$$

d. What is the magnitude of the mechanical power required to keep the beam's speed constant?

$$
P_{mech} = F v = 0.247 \,\mathrm{W}
$$

e. What will be the voltage across the current generator?

$$
P_{el} = P_{mech} = V I \implies V = \frac{P_{mech}}{I} = 0.141 \,\mathrm{V}
$$

f. Does point a in the drawing become positive in relation to point b, or vice versa? Indicate a as plus or minus.

Lorenz force on the charges will be upwards ($F = Q \vec{v} \times \vec{B}$).
This means there is an E-field upwards, which means that the voltage field will be opposite.
Thus, point a will have a higher voltage than point b.

## Exercise 6.3

The green frame in the figure is a coil with 450 turns and dimensions 10 x 10 cm as shown. The frame is
hinged so that it can rotate around the z-axis. The current through the coil is 1.5 A in the direction shown in
figure (the red arrow). There is a magnetic field in the area, given by:

$$
\vec{B} = (0.32 \hat{y} + 0.15 \hat{z}) \,\mathrm{\frac{Wb}{m^2}}
$$

a. Calculate the magnetic dipole moment of the loop. The answer should be given as a three-dimensional
vector. (Remember to include the direction of the current).

Area vector
$$
\vec{A} = 0.1 \cdot 0.1 (\sin(45\degree) \hat{x} - \cos(45\degree) \hat{y}) = (0.007\hat{x} - 0.007\hat{y}) \,\mathrm{m^2}
$$

$$
\vec{\mu} = N I \vec{A} = 4.77 (\hat{x} - \hat{y}) \,\mathrm{A m^2}
$$

b. Calculate the torque the loop is subjected to.

$$
\vec{\tau} = \vec{\mu} \times \vec{B} = (- 0.72 \hat{x} - 0.72 \hat{y} + 1.53 \hat{z}) \,\mathrm{Nm}
$$

c. Will the frame rotate around the z-axis when the current is connected? If so, which way? (clockwise or
counterclockwise).

Since z-axis component of $\tau$ is not zero, it will rotate around the z-axis.
It will rotate counter-clockwise since the z-component is positive (and $\vec{\tau} = \vec{l} \times \vec{F}$).
The frame is fixed in the other rotation directions, so it wont rotate around x- and y-axis.

## Exercise 6.4

We consider two point charges in a rectangular (x, y, z) coordinate system in empty space. Remember to
provide the answers with correct units.

The charges are:
- Q1: +10/9 nC at (x, y, z) = (2, 2, 1) m
- Q2: -20/9 nC at (x, y, z) = (-1, -1, -1) m

a. Sketch the configuration of charges.

Niclas will draw it... Maybe...
Work in progress....
The lazy fokker...

b. Determine the electric field vector at point A: (x, y, z) = (0, 0, 0).

$$
\vec{E} = \frac{Q}{4 \pi \varepsilon \cdot r^2} \hat{r}
$$

We call the distance vectors from the origin to the charges $r_1$ and $r_2$.

$$
\vec{E_1} = \frac{Q_1}{4\pi \varepsilon r_1^2} \frac{\vec{r_1}}{r_1} = (-0.74\hat{x} -0.74\hat{y} -0.37\hat{z}) \,\mathrm{\frac{V}{m}}\\
\vec{E_2} = \frac{Q_2}{4\pi \varepsilon r_2^2} \frac{\vec{r_2}}{r_2} = (-3.85\hat{x} -3.85\hat{y} -3.85\hat{z}) \,\mathrm{\frac{V}{m}}\\
\vec{E} = \vec{E_1} + \vec{E_2} = (-4.59\hat{x} -4.59\hat{x} -4.22\hat{x}) \,\mathrm{\frac{V}{m}}
$$

c. Calculate the D-field (electric displacement field) at point A (The D-field should be given as a vector).

$$
\vec{D} = \varepsilon_0 \vec{E} = (-4.06\hat{x} -4.06\hat{y} -3.73\hat{z}) \cdot 10^{-11} \,\mathrm{\frac{C}{m^2}}
$$

d. Calculate the absolute electric potential at point A.

$$
V = r E
$$

$$
V_1 = r_1 E_1 = 3.33 \,\mathrm{V} \\
V_2 = -r_2 E_2 = -11.5 \,\mathrm{V} \\
V = V_1 + V_2 = - 8.21 \,\mathrm{V}
$$

e. Now, a spherical surface is inserted in the coordinate system. The sphere has a radius of 2 m and center
at (0,0,0). Determine the value of the total flux of the D-field out through the spherical surface. You can use
a method of your choice for the calculation.

The answer sheet is cited for this question :gorilla:.
It is the amount of charge in the spherical surface.

f. Calculate the magnitude of the force acting between the two charges Q1 and Q2. Indicate attraction or repulsion.

Use Coloumb's law.
The charges will attract each other, since they have opposite polarity.

The direction vector is found by $\vec{d_{12}} = \vec{r_1}-\vec{r_2}$.

$$
\vec{F} = \frac{Q_1 Q_2}{4 \pi \varepsilon_0 d_{12}^2} \hat{d_{12}} = (-646, -646, -431) \,\mathrm{pN} \\
F = 1.01 \,\mathrm{nN}
$$
