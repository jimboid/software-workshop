# Introduction to Software Installation for Biomolecular Simulations

This material is designed to assist beginners/new scientists in biomolecular simulations with configuring their workstation with some basic software packages for the upcoming CCPBioSim training week. The idea here is to get familiar with installing scientific software on your workstation and have access to some of the most commonly used tools.

## Step 1 - Prepare Your Workstation

If the workstation you are setting up runs Windows (mac and linux users skip this step), decide if you are going to work in a Linux Virtual Machine (VM) or use the Windows Subsystem for Linux (WSL). The basic difference is that the VM offers full seperation of the operating systems whilst the WSL is more integrated. With the VM you would have to work fully within the VM, or setup some shared directories to pass files between Windows and Linux. With WSL you can use files seamlessly between the Windows installed tools and the ones installed in Linux. I tend to prefer working with the seperation of a VM, but on low end hardware, better results are often seen with WSL.

### Linux Virtual Machine

If you decided to install the Linux Virtual Machine then you will first need to download and install virtualbox (for Windows hosts) from here https://www.virtualbox.org/wiki/Downloads

Then download the Ubuntu Linux desktop iso https://ubuntu.com/download/desktop  

Then follow this tutorial to install a Linux (Ubuntu) VM https://github.com/jimboid/software-workshop/blob/master/install-vm.md.

### Windows Subsystem for Linux

If you decided to install the Windows Subsystem for Linux then you should follow the instructions from Microsoft here https://docs.microsoft.com/en-us/windows/wsl/install-win10


## Step 2 - Install a Molecular Visualiser (VMD)

**VMD** https://www.ks.uiuc.edu/Research/vmd/ is a tool for visualising, analysing and animating molecular structures. You can download (1.9.3, don't install the alpha version) it here https://www.ks.uiuc.edu/Development/Download/download.cgi?PackageName=VMD

It is also good to have an alternative tool for visualisation, as they often have different features. If you wish you can also in addition to VMD, install **pymol** https://pymol.org/2/

Each of these tools have documentation and tutorials that you can play with at your leisure!


## Step 3 - Install AmberTools

**AmberTools** https://ambermd.org/AmberTools.php is a suite of independantly developed tools and utilities that is available free of charge and is capable of fully setting up and running Molecular Dynamics calculations. You will use this suite of tools if you are attending Sarah Harris' workshops next week.


## Step 4 - Install Some Common Python Libs Using pip

Have a go at pip installing some common tools such as mdtraj, numpy, matplotlib. This exercise is designed to demonstrate how simple it is to install tools that are available on the Python Package Index (pypi https://pypi.org/). 

**mdtraj** http://mdtraj.org/1.9.3/ is quite useful for manipulating Molecular Dynamics trajectories.

**matplotlib** https://matplotlib.org/ is useful for scripting and quickly plotting charts (combined with Jupyter can be quite powerful). 

**numpy** https://numpy.org/ is a powerful numerical library that is very useful for manipulating complex numerical data. 

```pip install numpy```

```pip install matplotlib```

```pip install mdtraj```

### That's it for this workshop!

Some of the other workshops next week may have software installation requirements, you should check the programme descriptions http://www.ccpbiosim.ac.uk/events/upcoming/eventdetail/127/-/training-week-2020 and install any software they suggest. For those who are doing the DL_MESO workshop instructions can be found here https://github.com/jimboid/software-workshop/blob/master/dlmeso-install.md the instructor has indicated he will give some help on the day for those finding it difficult to install the software.
