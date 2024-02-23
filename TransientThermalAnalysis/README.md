# Steady State and Transient Analyses of an Elbow Pipe

## Overview

This repository focuses on the thermal analysis of a cast iron elbow pipe with a 90-degree bend, carrying steam at 150°C. The analysis is divided into two main sections: steady-state and transient heat transfer. The goal is to optimize insulation thickness to minimize heat loss and enhance thermal efficiency, as well as to examine the temperature response of the pipe to a thermal shock.

## Problem Statement

The elbow pipe, with inside and outside diameters of 70 mm and 90 mm respectively, is analyzed under two conditions:

- **Steady State Problem:** Determine the critical radius of insulation and its maximum outside temperature.
- **Transient Problem:** Analyze the maximum temperature on the outside of the insulation at 10 minutes and the time required to reach steady state conditions.

## Analysis

### Assumptions

- Steady-state heat transfer for part A.
- Radiative heat transfer is negligible.
- Material properties are assumed constant, except for the thermal conductivity of cast iron, which varies with temperature.
- Thermal contact resistance between the metal and insulation is negligible.

### Geometry

The pipe has a 90-degree bend with inside and outside diameters of 70 mm and 90 mm, respectively.

### Material Data

- **Pipe:** Cast iron with a density of 7200 kg/m³, specific heat of 447 J/kg-C, and variable thermal conductivity.
- **Insulation:** Material with a density of 2500 kg/m³, specific heat of 840 J/kg-C, and thermal conductivity of 0.2 W/m-C.

### Boundary Conditions

- Convection of 3.7 W/m²°C applied to the outside surface.
- Pipe ends are assumed adiabatic.
- For steady-state analysis, convection of 20 W/m²°C at 150°C applied to the inside surface.
- For transient analysis, a step-applied convection shock of 50 W/m²°C at 150°C applied to the inside surface.

### Results

- **Steady State Analysis:** The critical insulation thickness where heat loss becomes maximum is 10 mm.
- **Transient Analysis:** The system reaches steady state conditions after 95 minutes, with the maximum temperature on the outside of the insulation at 10 minutes being significantly lower than at steady state.

## Conclusion

The critical radius of insulation, where heat loss from the insulation surface peaks, occurs at an insulation thickness of 10 mm. The transient heat analysis reveals that the system reaches a steady state after 95 minutes, determined by considering 95% of the final temperature as the point at which steady state is achieved.

## Additional Notes

- A summary report detailing the results, assumptions, analysis approach, and conclusions is included.
- Accurate, convergence results in terms of mesh and time step selections are expected.


