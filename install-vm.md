# Installing Ubuntu on a Windows Host

### Step 1

Open VirtualBox and select the "new" button

![step 1](/images/step1.png)

### Step 2

Choose a name for your virtual machine. Based on the name you entered, VirtualBox will try to guess the "Type" and "Version", the defaults are usually good. If they look wrong then use the drop down boxes to select Linux and Ubuntu and click on the "Next" button.

![step 2](/images/step2.png)

### Step 3

With the help of the slider, choose the amount of memory (RAM) to be allocated to the virtual machine. The recommended memory size is 1024 MB 1 GB, but it usually best to slide it all the way to the top of the green for scientific applications. Please note that this memory will only be used while the virtual machine is running.

![step 3](/images/step3.png)

### Step 4

Select "Create a virtual hard disk now" option and then click on the "Create" button.

![step 4](/images/step4.png)

### Step 5

Choose the "VDI (VirtualBox Disk Image)" option and click the "Next" button.

![step 5](/images/step5.png)

### Step 6

Choose "Fixed Size" and click "next" button.

![step 6](/images/step6.png)

### Step 7

Select the amount of space for your virtual machine. This will be used for your operating system which is going to be installed, for this workshop no more than 30GB but if you wish to use this for work then you might want to go bigger. Then click the "Create" button.

![step 7](/images/step7.png)

### Step 8

Now you have successfully created your virtual machine and it is time to install Ubuntu on it. 

The latest version of Ubuntu is now 20.04.1 LTS, the below steps are showing Ubuntu 18.04 but the steps remain the same. Follow the instructions below to proceed.

The name of your virtual machine will now appear on the left side of the VirtualBox Manager. Click on the name and then the "Start" button in the toolbar to launch your VM.

![step 8](/images/step8.png)

### Step 9

You now have to select your Ubuntu ISO file that you downloaded earlier. Click on the folder icon and then click on the "Add" button. Then, navigate to and select your Ubuntu ISO file. Click on the "Start" button to proceed.

![step 9](/images/step9.png)

You should now see the following screen

![step 10](/images/step10.png)

If you get the following error

The native API DLL was not found (C:\WINDOWS\system32\WinHvPlatform.dll) (VERR_NEM_NOT_AVAILABLE).
VT-x is not available (VERR_VMX_NO_VMX).

To resolve this above error, use the following command in Command Prompt (Admin), "dism.exe /Online /Disable-Feature:Microsoft-Hyper-V".
 
You should then try the above step again and your VM should start normally.

### Step 10

Now, click on the "Install Ubuntu" button.

![step 11](/images/step11.png)

### Step 11

Select your desired "keyboard layout" and click on the "Continue" button.

![step 12](/images/step12.png)

### Step 12

Use the default option as "Normal Installation" with the "Download updates while installing Ubuntu" and click on the "Continue" button.

![step 13](/images/step13.png)

### Step 13

Select the default option as the "Erase disk and Install Ubuntu" and click on the "Install Now" option to proceed (This is safe as it is in a virtual machine disk!).

![step 14](/images/step14.png)

### Step 14

A warning prompt will appear on the screen and click on the "Continue" button (again ignore this warning on a VM).

![step 15](/images/step15.png)

### Step 15

Choose your time zone on the map and click Continue.

![step 16](/images/step16.png)

### Step 16

Now, set your user account here by filling the necessary details and click on the "Continue" button to proceed. You can tick the login automatically box to avoid having to log in to your windows and then into your linux VM.

![step 17](/images/step17.png)

### Step 17

Now, the installation process will begin. You will see a bunch of shiney pages telling you about features as this completes!

![step 18](/images/step18.png)

### Step 18

Hit reboot and you're done!

![step 19](/images/step19.png)
