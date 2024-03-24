# Tower Design Analysis by Maryam Hakimzadeh

## Overview
This project focuses on designing a tower capable of supporting a specific dead mass at its apex. The design constraints require the tower to be constructed solely from beam members, accommodating a mass of 36,000 kg at a height of 20 meters. The tower must also withstand its own weight and a specified wind load, ensuring structural integrity and safety.

### Objective
- Design a tower using only beam members.
- Support a 36,000 kg mass elevated at 20 m.
- Account for the tower's weight and wind load.
- Achieve a safety factor of 5 for structural stress analysis.
- Ensure minimum buckling load is greater than 10.

### Assumptions
- Thermal effects are disregarded.
- The analysis assumes linear elasticity.
- Stress risers near frictionless supports are not considered.

### Geometry
- The tower has a 5m x 5m cross-section and a height of 20m.
- Beam cross-sections are square and hollow, available in two sizes: small and large.

### Material Data
- Structural steel from Ansys Mechanical's default material set is used.

### Boundary Conditions
- A 36,000 kg dead load is applied at the top.
- A 9,000 N wind load is applied.
- The tower's own weight is considered.

### Mesh Convergence Study
- A mesh convergence study was omitted for efficiency, utilizing the default mesh.

## Results
- Total mass: 3803.7 kg
- Safety factor for bending: 4
- Buckling safety factor: 11

### Beam Cross Sections
- Beams with two cross sections are used.

## Conclusions
The analysis validates the tower's structural integrity, meeting the specified design objectives and safety requirements.


