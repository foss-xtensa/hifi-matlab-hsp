# hifi-matlab-hsp
MATLAB/Simulink Hardware Support Package for HiFi DSPs

Toolbox created by Cadence to be used with MATLAB and Simulink.

The toolbox contains Cadence HiFi Hardware Support Package (HSP) that enables users to generate, optimize, build, run, and verify C code from MATLAB scripts and Simulink blocks on Cadence® Tensilica® HiFi processors. The toolbox can be used for rapid prototyping and production workflows for audio applications. The toolbox is supported on Windows and Linux operating systems. The HSP integrates with MATLAB's Coder (the code generation toolbox) and generates HiFi DSP optimized C code using Code Replacement Library (CRL). CRL replaces C functions with optimized HiFi kernels. Generated code can be compiled and executed in Xtensa Instruction Set Simulator (ISS) through processor-in-the-loop (PIL) simulation within the MATLAB environment

Latest release version : [2.0.1](https://github.com/foss-xtensa/hifi-matlab-hsp/releases)


## Repository structure:
Toolbox: → Contains Hardware Support Package (HSP) as a toolbox (.mltbx) file.

## System Requirements:
### MATLAB Version
• R2024a

### Add on toolboxes.

MATLAB Coder version 24.1<br />
Simulink version 24.1<br />
Simulink Coder version 24.1<br />
DSP System Toolbox version 24.1<br />
Embedded Coder version 24.1<br />
Signal Processing Toolbox version 24.1<br />


### Supported Xtensa Tools Versions
• RJ-2024.3


### Supported HiFi Cores
• HiFi 4 and HiFi 5/5s with SP-VFPU and XCLIB support.

### Nature DSP Library Versions
• HiFi 4: NatureDSP Library v >= 5.0.0<br />
• HiFi 5: NatureDSP Library v >= 2.7.0<br />
  *Note: The NDSP releases are available on XPG and GitHub*.
  
**GitHub locations**: Download the Xtensa Workspace(xws) of NDSP library from following Github Pages.<br />
Link to xws : [HiFi4 NDSP](https://github.com/foss-xtensa/ndsplib-hifi4/tree/main/xws)<br />
Link to xws : [HiFi5 NDSP](https://github.com/foss-xtensa/ndsplib-hifi5/tree/main/xws)<br />

Build the XWS on Xtensa Xplorer on respective cores to generate the library (.a).

## Installation Steps

Install the ".mltbx" file by openeing it through MATLAB, once installed successfully, please go to doc section to find the user guide.
Refer the Chapter 2 : HSP installation of the User Guide  from doc folder. 

## Support

All support questions, feedback  should be mailed to our official mail ID : hifi_matlab_hsp@cadence.com 
