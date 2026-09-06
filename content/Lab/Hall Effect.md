## Introduction
When we have a magnetic field perpendicular to the direction of flow of current is applied to a conductor, the charge carriers experience a force and accumulate on one of the sides of the conductor. Thus, a voltage is developed in the direction perpendicular to the flow of current and  the magnetic field. This voltage is called the Hall Voltage.

In this experiment, assuming drift velocity of all charge carriers (in our case electrons) is same, we determine the number density of the charge carriers in our sample.
## Experiment Setup and Procedure

#### Apparatus
A semiconductor sample to be studied connected to a digital millivoltmeter, Hall probe, digital Gaussmeter, electromagnet, a constant current source for the electromagnet and a current source of the semiconductor sample.
#### Experiment Setup
The Hall probe or the semiconductor sample is placed in between the two heads of the electromagnet in such a way that the probe is perpendicular to the direction of the magnetic field. The hall probe is connected to the Gaussmeter while the semiconductor sample is connected to a current source to provide the main current and the millivoltmeter which measures the Hall Voltage.
#### Procedure
First, for different values of current supplied to the electromagnet, the intensity of the magnetic field is measured using the Hall Probe. This is the calibration of the electromagnet. The linearity of this data is verified.

Now the semiconductor sample is placed in the electromagnet. The current in the electromagnet is fixed and the magnetic field obtained for this current from the calibration process is used. Varying the current through the semiconductor, hall voltage is measured and using this data, number density is calculated.
## Formulae and Relations
Let the dimensions of the semiconductor be $x$, $y$ and $z$.
Current flows in $x$ direction, magnetic field is in the $y$ direction and Hall voltage in the $z$ direction.

At equilibrium, the Lorentz Force on the moving carriers equals the Force due to the Hall Voltage gradient. So, $$q(\bar v\times \bar B) = \frac {V_h} z q$$$$\therefore vBz = V_h$$
Here $\bar v$ is the drift velocity, $\bar B$ is the magnetic field, $V_h$ is the Hall Voltage and $q$ is the charge of the carrier. Here $q = e = 1.6\times 10^{-19} \ C$

But the current density $\bar  J = ne\bar v$
And in this case, $I = J\times yz$

$\therefore v = \frac I {ne \ yz}$
substituting this in the previous equation, we get $$I = \frac {ney} {B} V_h$$
Thus after plotting $I$ vs $V_h$ and getting the slope, we can determine$$n= slope \times B/ey$$
## Data and Analysis

Calibration:

| $I \ (A)$ | $B \ (T)$ |
| --------- | --------- |
| 0.25      | 0.0040    |
| 0.50      | 0.0100    |
| 0.75      | 0.0180    |
| 1.00      | 0.0250    |
| 1.25      | 0.0320    |
| 1.50      | 0.0380    |
| 1.75      | 0.0440    |
| 2.00      | 0.0500    |
![[Hall - Calibration.png]]

Now we put we get reading for the semiconductor.
The current through the electromagnet is fixed at $1.5 \ A$.
The the magnetic field is $B = 0.036 \ T$

| $I \ (mA)$ | Zero error | Millivoltmeter<br>Reading | Hall Voltage $V_h$<br>$(mV)$ |
| ---------- | ---------- | ------------------------- | ---------------------------- |
| 4.66       | -19.7      | 32.8                      | 52.5                         |
| 6.24       | -26.5      | 43.6                      | 70.1                         |
| 7.00       | -29.8      | 48.5                      | 77.85                        |
| 7.94       | -33.6      | 54.2                      | 87.8                         |
| 9.04       | -38        | 60.9                      | 98.9                         |
Plotting $I$ vs $V$ we get:
![[Hall - IV.png]]
y = 0.094 x + 0.33
$\therefore slope = 0.094$
From this, we get $n = 4.46\times 10^{19}$ 