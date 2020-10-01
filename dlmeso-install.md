# Large Scale Modelling with DL_MESO

If you intend to do this workshop, then preperation of your computer in advance will allow you to get the most out of the workshop. To prepare your computer, you should follow the below steps.

## Obtain and compile DL_MESO

You will first need to register and download DL_MESO (via the registration form found at www.ccp5.ac.uk/DL_MESO) to obtain its source code.
 
Compilation of DL_MESO’s codes and associated utilities requires:

Fortran 2003 compiler (e.g. gfortran in GCC suite)
C++ compiler (e.g. g++ in GCC suite)
 
and can optionally include an installed instance of MPI (e.g. Open-MPI) with compiler wrappers to speed up calculations. 
All of these can be installed using a Linux package manager – via Windows Linux Subsystem in Windows 10 – or either MacPorts or HomeBrew on Macs.

On ubuntu running ```sudo apt-get install build-essential``` in your terminal should install the GCC suite.

You can then follow the instructions for compiling DL_MESO here https://www.scd.stfc.ac.uk/Pages/USRMAN.pdf
 

## Setup Visualisation Tools
 

VMD (installed earlier) or Ovito https://www.ovito.org/ for DPD trajectories (only latter currently available as stable release for Macs)
Paraview for LBE results and some DPD analysis https://www.paraview.org/
A program to plot tabulated data (e.g. Gnuplot, Excel) or one of the Python scripts (see below).


# Optional Python Scripts

Some Python3 scripts to carry out a simple DPD simulation workflow for one of the practical exercises and plot graphs of simulation outputs (These scripts are optional but very useful and recommended for the DPD exercises.) 
As well as Python3, the following packages need to be installed using PIP:
 

```pip install docopt```

```pip install tqdm```

```pip install numpy```

```pip install PyQt5```

```pip install matplotlib```

 
Qt5 also needs to be installed for the visualisation scripts ```sudo apt-get install qt5-default```
