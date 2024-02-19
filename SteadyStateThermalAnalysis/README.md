# Steady-State Thermal Analysis of a Curved Pipe

## Project Overview

This project presents a detailed steady-state thermal analysis of a curved cast iron pipe, conducted as part of the Applied Finite Element Analysis (FEA) course. The analysis aims to assess the thermal performance of the pipe under various conditions, including the application of insulation and changes in external convection coefficients.

## Problem Statement

The project investigates a curved cast iron pipe with an inside diameter of 70 mm and an outside diameter of 90 mm, carrying steam at 155°C. The analysis is divided into three parts to explore different thermal management strategies:

- **Part A:** Evaluates the pipe without insulation, focusing on the effects of external convection.
- **Part B:** Adds a 5 mm layer of foam insulation to the pipe's exterior, examining the impact of insulation combined with external convection.
- **Part C:** Models the 5 mm foam insulation using finite elements to accurately assess its thermal performance.

The primary objectives are to determine the maximum outside surface temperature of the pipe and the rate of heat loss in each scenario.

## Methodology

The analysis employs Ansys FEA software, adhering to the following assumptions:

- Steady-state heat transfer
- Constant thermal properties
- Negligible thermal contact resistance at the metal-insulation interface
- Radiation effects ignored


## Analysis Results

### Key Findings

- **Part A:** Uninsulated pipe scenario revealed a maximum outside surface temperature of 128.5°C and a heat loss rate of 35.4 Watts.
- **Part B:** With the addition of insulation, the maximum temperature slightly increased to 130.8°C, but the heat loss rate decreased to 32.3 Watts, indicating the effectiveness of insulation in reducing heat loss.
- **Part C:** Explicit modeling of the insulation showed a maximum surface temperature similar to Part A (128.3°C) but with a slightly higher heat loss rate (35.6 Watts), suggesting that the method of insulation application and the increased surface area due to insulation thickness play significant roles in thermal performance.

### Comparative Analysis

- The insulation effectively reduced the rate of heat loss compared to the uninsulated scenario, as demonstrated in Part B.
- The detailed modeling approach in Part C provided insights into the nuanced effects of insulation on thermal performance, highlighting the importance of comprehensive thermal management strategies.

## Conclusion

The analysis underscores the importance of insulation in managing the thermal performance of steam-carrying pipes. While insulation can significantly reduce heat loss, the method of its application and the physical characteristics of the insulation material are crucial factors that influence the overall thermal efficiency.


Contributions, questions, and discussions are welcome! Feel free to open issues or submit pull requests.

