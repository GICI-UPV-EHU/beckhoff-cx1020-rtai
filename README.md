
# Real-Time Control on Beckhoff CX1020 using Linux/RTAI

This repository preserves technical resources developed by the
**Intelligent Control Research Group (GICI)** at the University of the
Basque Country (UPV/EHU) for the implementation of real-time control
applications on the **Beckhoff CX1020 industrial controller**.

The work was originally developed in the context of Master's Thesis
activities and was publicly disseminated by GICI in 2012 through its
former DrupalGardens website.

The materials are now preserved in this GitHub repository to maintain
public access to the original technical resources.

## Overview

The work addresses the use of the Beckhoff CX1020 as an open platform
for the implementation and experimental validation of real-time control
algorithms.

The developed environment combines:

- Beckhoff CX1020 industrial PC
- Beckhoff K-Bus I/O terminals
- Linux
- RTAI (Real-Time Application Interface)
- Comedi
- MATLAB/Simulink
- Real-Time Workshop / code generation tools

The resulting platform enables control algorithms designed and simulated
in MATLAB/Simulink to be converted into C code, compiled and executed
under RTAI on the Beckhoff CX1020.

## Technical documentation

Two technical guides were produced as part of this work:

### 1. How to install RTAI in Beckhoff CX1020

This document describes the configuration of a Beckhoff CX1020 for
real-time control using Linux and RTAI.

It covers, among other aspects:

- Linux installation and configuration
- RTAI installation
- Comedi installation
- RTAI-Lab installation
- MATLAB/Simulink configuration
- Real-Time Workshop code generation
- Compilation and execution of real-time applications on the CX1020
- Experimental verification of the resulting real-time system

### 2. How to install K-Bus driver in a Beckhoff CX1020 (RTAI)

This document describes the installation and use of a K-Bus driver
developed under the Comedi interface to provide access to the
input/output signals of Beckhoff terminals connected to the CX1020.

The work includes:

- K-Bus driver configuration
- Integration with Comedi
- Access to Beckhoff analog and digital I/O terminals
- Integration with MATLAB/Simulink
- Automatic code generation
- Execution of control applications under RTAI
- Experimental validation using physical I/O signals

## Software

The original development included software components for the
integration of the Beckhoff K-Bus with the Linux/RTAI real-time
environment.

Among the files referenced in the original technical documentation are:

- `kbusdrv.c`
- `loadrtaimodules.sh`
- `unloadrtaimodules.sh`

Available original source files will be progressively preserved in this
repository.

## Authors

The original technical documentation was prepared by:

- J. Andrés Cubillos Galvis
- Eloy Irigoyen Gordo
- Ekaitz Larzabal Balerdi
- Mikel Larrea Sukia

Intelligent Control Research Group (GICI)  
Department of Systems Engineering and Automatic Control  
University of the Basque Country (UPV/EHU)

## Historical context

These materials were originally developed and publicly disseminated by
GICI in **2012** through the group's former DrupalGardens website.

The current GitHub repository is a preservation and dissemination copy
of those original resources. The creation date of this repository should
therefore not be interpreted as the date on which the technical work was
originally developed.

## License

The original technical documents were released under the:

**Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported
License (CC BY-NC-SA 3.0).**

Please refer to the individual documents for the original licensing
information.

## Citation

If you use these materials in academic or technical work, please
acknowledge the original authors and the Intelligent Control Research
Group (GICI), University of the Basque Country (UPV/EHU).
