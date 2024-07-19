# Optimization of Water Distribution Networks Using the Newton-Raphson Method

This repository contains the implementation and results of the project titled "Optimization of Water Distribution Networks Using the Newton-Raphson Method." The project focuses on developing and refining mathematical models for optimizing the design and operation of water distribution networks to minimize costs and meet hydraulic constraints efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Contributors](#contributors)
- [References](#references)

## Introduction

Urban infrastructure is incomplete without efficient water distribution networks that ensure a reliable water supply to homes, industries, and businesses. This project aims to utilize the Newton-Raphson method to address optimization challenges in the construction of water distribution networks, providing a more accurate and efficient approach compared to traditional methods.

## Objectives

1. Develop a comprehensive model to apply the Newton-Raphson method in flow analysis of water distribution networks.
2. Analyze the shortcomings of current design approaches and identify challenges in achieving optimal design.
3. Refine and extend the cost-head loss ratio criterion method to incorporate the Newton-Raphson technique for rapid convergence and improved design accuracy.
4. Formulate a mathematical framework that integrates the modified optimization method with network hydraulic behavior equations.
5. Implement the proposed method into existing software tools for water distribution network analysis.
6. Validate the effectiveness and efficiency of the upgraded software through case studies.

## Methodology

The project employs the Newton-Raphson method to solve nonlinear equations governing network hydraulics, optimizing pipe diameters and nodal pressures. The univariate cost-head loss ratio criterion method is updated for rapid convergence using the Newton-Raphson technique.

## Implementation

The implementation involves:

- Developing a mathematical model for water distribution networks.
- Integrating the Newton-Raphson method into the model.
- Implementing the method in existing network analysis software.
- Conducting case studies to validate the approach.

## Results

The Newton-Raphson method demonstrated superior performance in optimizing water distribution networks, requiring fewer iterations and providing more accurate results compared to traditional methods. The method is versatile, applicable to both branched and looped networks, and adaptable for multi-source designs, including pumped source nodes.

## Conclusion

The project successfully demonstrates the application of the Newton-Raphson method for cost optimization in water distribution networks. This approach significantly improves design accuracy and efficiency, contributing to the sustainability and effectiveness of water supply systems.

## How to Use

1. Clone the repository: `git clone https://github.com/yourusername/water-distribution-optimization.git`
2. Navigate to the project directory: `cd water-distribution-optimization`
3. Follow the instructions in the `INSTALL.md` file to set up the necessary environment.
4. Run the provided scripts to perform optimization on sample water distribution networks.

## Contributors

- Reddybathuni Venkat
- Oruganti Dheekshitha
- Rathod Vatsalraj Vikramsinh
- Raiyani Vedanshi Sanjay
- Tarun Meena

## References

1. Andersen J. H., and Powell, R. S. (1999). “Simulation of water networks containing controlling elements”, J. Water Resour. Plng. and Mgmt., ASCE, 125(3), 162-169.
2. Bhave, P. R. (1977). “Optimality criteria for distribution networks.” Ind. Jour. of Environ Hlth., 19(2), 120-139.
3. Donachie, R. P. (1974). “Digital program for water network analysis”, J. of Hyd. Div., ASCE, 100(3), 393-403.
4. Martin, D. W., and Peters G. (1963). “The application of Newton’s method to network analysis by Digital Computers”, J. Inst. of Water Engrs., 17, 115-129.
