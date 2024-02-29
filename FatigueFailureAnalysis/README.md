# Fatigue Analysis of a Trailer Hitch

## Overview

This repository is dedicated to the fatigue analysis of a standard trailer hitch under various loading conditions. The primary objective is to assess the structural integrity and fatigue life of the hitch, proposing design modifications to enhance its performance and safety.

## Problem Statement

The trailer hitch is subjected to different loading scenarios to simulate real-world conditions:

- **LC1 & LC2**: Tongue Load of 2500 N, with variations in drop and rise, designed for an infinite life (1e6 cycles).
- **LC3**: Trailer Load on a Small Hill of 5,000 N, aiming for a design life of 1e5 cycles.
- **LC4**: Trailer Load on a Steep Hill of 11,000 N, with a design life of 5000 cycles.

The analysis seeks to determine the hitch's fatigue life and safety factor under these conditions and to identify any load cases not meeting design requirements.

## Analysis

### Assumptions

- Linear elasticity is used for stress analysis.
- Thermal effects are not considered.
- Stress risers near the frictionless support are ignored.
- The hitch's constraints are assumed to be frictionless, allowing free sliding, which is an idealization and not reflective of real-world conditions where resistance due to attachment occurs.
- Fatigue analysis is governed by the Goodman curve.

### Geometry

The hitch features a standard design with a 7.6 cm drop/rise and a maximum towing capacity of 22,000 N, with a 2,500 N tongue weight.

### Material Data

- Custom material with specified properties including Elastic Modulus (E), Poisson's Ratio (Nu), Density, Ultimate Strength, and Fatigue Properties.

### Boundary Conditions

- Applied loads simulate real-world usage conditions, including tongue and trailer loads in various configurations.
- Constraints allow for realistic movement and stress distribution within the hitch.

## Results

The fatigue analysis reveals critical stress locations and provides a comprehensive understanding of the hitch's performance under simulated conditions. Design modifications are proposed to improve the fatigue safety factor, particularly for the most challenging load cases.

## Conclusion

The fatigue analysis confirms the structural integrity and identifies areas for improvement in the trailer hitch design. Proposed modifications aim to enhance the safety factor, ensuring reliability and performance within specified loading conditions.

## Additional Notes

- Detailed reports include assumptions, analysis approach, results, and conclusions.
- Mesh convergence studies ensure accurate results, focusing on critical stress locations for optimization.
