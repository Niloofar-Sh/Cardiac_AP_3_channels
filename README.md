# Cardiac_AP_3_channels
A minimal Bond Graph model in BGT to generate a cardiac action potential with only three ion channels contributing to the action potential generation.
Ion fluxes: 1) Fast inward Sodium flux (Na+ channel), 2) Slow inward Calcium flux (Ca2+ channel), 3) Outward Delayed Potassium flux (K+ channel).
Two amounts for the Calcium channel reaction rate were tested: kappa_Ca=550.2 for generating a normal AP, and kappa_Ca=650 for generating an AP with EADs.
Each ion flux is plotted using functions adopted from the BGT source codes. As the ion concentrations for extra/intra-cellular environments are set fixed, 
the flux going through each channel cannot be calculated directly. As such, the corresponding built-in functions where picked from the BGT itself.
