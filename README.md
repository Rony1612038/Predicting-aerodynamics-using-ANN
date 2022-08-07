# Predicting aerodynamic characteristics of airfoils using ANN

## Dataset description

Airfoil coordinates (X, Y ), angle of attack (α), Reynolds number (Re), lift coefficient (C<sub>L</sub>) and drag coefficient (C<sub>D</sub>) are the features of the dataset. 

1. Airfoils: NACA 0012, NACA 0015, NACA 0018 NACA 0021 and NACA 0025.
2. Airfoil Tools [[1]](#1) was used to generate a total 201 airfoil coordinates (X,Y) for an individual airfoil.
3. Wind turbine experimental data [[2]](#2) was used to get rest of the features (α, Re, C<sub>L</sub> and C<sub>D</sub>).
4. Angle of attack (α) is in the range of (0<sup>◦</sup> ≤ α ≤ 180<sup>◦</sup>).
5. Reynolds number (Re) is in the range of (10<sup>4</sup> ≤ Re ≤ 10<sup>7</sup>).
6. Observations with the Reynolds number (Re) of 1.6 x 10<sup>5</sup> were separated and used as test data.
7. Training data : 2598
8. Test data: 80

## References
<a id="1">[1]</a> 
Tools, Airfoil. 2022. Airfoil tools URL: http://www.airfoiltools.com/.

<a id="2">[2]</a> 
Sheldahl, Robert E., and Paul C. Klimas. Aerodynamic characteristics of seven symmetrical airfoil sections through 180-degree angle of attack for use in aerodynamic analysis of vertical axis wind turbines. No. SAND-80-2114. Sandia National Labs., Albuquerque, NM (USA), 1981.
