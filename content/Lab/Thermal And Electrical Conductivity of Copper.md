## Introduction
Given a material, it's electrical conductivity gives a relation between the resistance of wire and it's dimensions: $$R = \frac 1 \sigma \times \frac L A$$
The thermal conductivity gives information about the rate at which heat is transferred to the material. For cross sectional are $A$, rate of heat transfer is given by: $$\frac {dQ} {dt} = KA \frac {dT} {dx}$$
In this experiment, we determine the thermal and electrical conductivity of copper.
## Experiment Setup and Procedure
#### Apparatus
Thermal and electrical conductivity box, DC current sources and a multichannel voltmeter connected to the box.
#### Experiment Setup
![[Conductivity - Setup.jpg]]
The thermal and electrical conductivity box contains a copper tube that is connected to a heater. On both sides of the heater, there is a thermocouple which given reading to channels 1 and 2 respectively.

$R$ = Heater Resistance = $22 \ \Omega$
Outer diameter of copper tube $D = 9.5 \ mm$
Wall Thickness of copper tube $t = 0.75 \ mm$
Distance between thermocouple junctions $d_1 = 60 \ mm$
Distance between Voltage Leads $d_2 = 180 \ mm$
Thermo-electric power of Thermocouple: $\alpha = 40 \ \mu V / K$
#### Procedure
First, we measure the electrical conductivity. For different values of current, the voltage across the voltage leads is measured. Using this data and the dimensions of copper tube, we can determine electrical conductivity.

After this, we send different values of current through the heater. Since the resistance of heater is known, we know the heat released by the heater. We measure the potential difference between the the thermocouple leads. The system is allowed to reach equilibrium, then the potential difference across this thermocouple and the thermocouple on the other side are noted. Using this data, thermal conductivity is calculated.
## Formulae and Relations
Outer radius of tube = $r_2 = D/2$
Inner radius of tube = $r_1 = r_2 - t$
$A = \pi(r_2^2- r_1^1)$

$R = \frac V I$
$\therefore I = \frac {\sigma A} {d_2} V$
Upon plotting this, $slope = \frac {\sigma A} {d_2}$
$\therefore \sigma = slope \times \frac {d_2} A$

Voltage across first thermocouple = $V_1$
Voltage across second thermocouple = $V_2$

Temperature differences across thermocouples;
$\Delta T_1 = V_1/\alpha$
$\Delta T_2 = V_2/\alpha$

Power output by heater = $P = I^2R$

Power output by heater = The heat being transferred by on both sides
$\therefore I^2 R = K A (\Delta T_1 + \Delta T_2) / d_1$
$$K = \frac {I^2 R d_1} {A(\Delta T_1 +\Delta T_2)}$$
## Data and Analysis
Using the formulae above, we get
$A = 2.061\times10^{-5} \ m^2$

For the first part of the experiment, the following data was collected:

| $I \ (mA)$ | $V \ (mV)$ |
| ---------- | ---------- |
| 624        | 0.145      |
| 528        | 0.122      |
| 399        | 0.092      |
| 294        | 0.068      |
| 202        | 0.047      |
![[Electrical Conductivity Graph.png]]
y = 4311.16 x + 0.7

$\therefore \sigma = slope \times \frac {d_2} A =3.76\times10^7 S/m$

For the second part of the experiment, the following values were noted:

| $I$ (A) | $V_1 (\mu V)$ | $V_2(\mu V)$ | $\Delta T_1$ | $\Delta T_2$ | $\Delta T_1 +\Delta T_2$ | $K$    |
| ------- | ------------- | ------------ | ------------ | ------------ | ------------------------ | ------ |
| 0.215   | 184           | 196          | 4.6          | 4.9          | 9.5                      | 311.64 |
| 0.262   | 264           | 279          | 6.6          | 7.0          | 13.6                     | 323.86 |
| 0.169   | 114           | 122          | 2.85         | 3.0          | 5.85                     | 310.03 |
Taking the average value, we determine
$K = 315.17 \ W/mK$
