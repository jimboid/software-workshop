# Introduction to Software Installation for Biomolecular Simulations

This material is designed to assist beginners/new scientists in biomolecular simulations with configuring their workstation with some basic software packages for the upcoming CCPBioSim training week. The idea here is to get familiar with installing scientific software on your workstation and have access to some of the most commonly used tools.

## Step 1 - Prepare Workstation

If the workstation you are setting up runs Windows (mac and linux users skip this step), decide if you are going to work in a Linux Virtual Machine or use the Windows Subsystem for Linux.

Linux Virtual Machine

Windows Subsystem for Linux



## Step 2 - Install a Molecular Visualiser (VMD)

**VMD** https://www.ks.uiuc.edu/Research/vmd/ is a tool for visualising, analysing and animating molecular structures. You can download (1.9.3, don't install the alpha version) it here https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD

It is also good to have an alternative tool for visualisation, as they often have different features. If you wish you can also in addition to VMD, install **pymol** https://pymol.org/2/

Each of these tools have documentation and tutorials that you can play with at your leisure!


## Step 3 - Install AMBERTools

https://ambermd.org/AmberTools.php



## Step 4 - Install Some Common Python Libs Using pip

Have a go at pip installing some common tools such as mdtraj, numpy, matplotlib. This exercise is designed to demonstrate how simple it is to install tools that are available on the Python Package Index (pypi https://pypi.org/). 

**MDTraj** http://mdtraj.org/1.9.3/ is quite useful for manipulating Molecular Dynamics trajectories. 
**matplotlib** https://matplotlib.org/ is useful for scripting and quickly plotting charts (combined with Jupyter can be quite powerful). 
**Numpy** https://numpy.org/ is a powerful numerical library that is very useful for manipulating complex numerical data. 

'pip install numpy'
'pip install matplotlib'
'pip install mdtraj'
