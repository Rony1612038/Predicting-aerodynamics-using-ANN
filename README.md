# Predicting aerodynamic characteristics of airfoils using ANN

Airfoil coordinates (X, Y ), angle of attack (α), Reynolds number (Re), lift coefficient (C<sub>L</sub>) and drag coefficient (C<sub>D</sub>) are the features of the dataset. 

1. Airfoils: NACA 0012, NACA 0015, NACA 0018 NACA 0021 and NACA 0025.
2. Airfoil Tools [1] was used to generate airfoil coordinates (X,Y).
3. Wind turbine experimental data [2] was used to get rest of the features (α, Re, C<sub>L</sub> and C<sub>D</sub>).
4. Angle of attack (α) is in the range of (0◦ ≤ α ≤ 180◦).
5. Reynolds number (Re) is in the range of (10<sup>4</sup> ≤ Re ≤ 10<sup>7</sup>).
6. Observations with the Reynolds number (Re) of 1.6 x 10<sup>5</sup> were separated and used as test data.
7. Training data : 2598
8. Test data: 80

References

[1] Tools, Airfoil. "Airfoil tools." Retrieved Augut 7 (2022): 2022
[2] Sheldahl, Robert E., and Paul C. Klimas. Aerodynamic characteristics of seven symmetrical airfoil sections through 180-degree angle of attack for use in aerodynamic analysis of vertical axis wind turbines. No. SAND-80-2114. Sandia National Labs., Albuquerque, NM (USA), 1981.
