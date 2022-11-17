# ROR

Refer to ROR_manual_v1.pdf for step by step procedure

This chapter describes the step-by-step procedure to do topology optimization of a chair using Ansys topology optimization 2020 R1.
An initial design domain of the chair, as shown in fig.1(ROR_manual_v1.pdf), is applied with seating and spine resting pressure (surface) loads and is fixed in the bottom four squares, i.e. the contact area with the ground. The optimization problem is to minimize compliance along with a mass/volume constraint in two scales, respectively macro scale for optimizing the geometry and a micro scale for optimizing the material microstructure.

The boundary conditions are considered non-design domains; hence, the level set-based topology optimization method is used to optimize the geometry of the initial design domain. Further, the resultant optimized geometry is fed to micro-scale optimization using homogenization-based lattice optimization. The design and non-design domains are differentiated with grey and red/blue colours, respectively, as shown in fig.1(ROR_manual_v1.pdf).

The initial design domain geometry is attached under the file name: Initial domain.stp
The level set optimized results are attached under the name: Level_set_optimized.stl
