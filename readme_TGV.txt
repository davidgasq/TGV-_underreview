TOULGAITVIZ App v1.0 - August 23, 2023

Emmeline MONTANE, Florent MOISSENET & David GASQ - 2023
——————————————————————————————————————

If used for any publication, please cite:
Montané E, Cormier C, Scandella M, Cangelosi A, Marque P, Moissenet F, Gasq D. 2023. ToulGaitViz - A tool for the systematic description of lower limb clearance during the swing phase of hemiparetic gait after stroke. A cohort study.
Published in European Journal of Physical and Rehabilitation Medicine, 2023.

The ToulGaitViz application is released as a standalone application. 

This app has been compiled with MATLAB, version R2019a, The Mathworks, USA. 

The app needs the installation of MATLAB Runtime to run. Each version of the MATLAB Runtime is tied to the version of MATLAB.

This script uses MoCap Toolbox function mcreadc3d.m (https://www.jyu.fi/hytk/fi/laitokset/mutku/en/research/materials/mocaptoolbox).
Details regarding the application and data processing are available in the paper Montané et al. 2023. 

——————————————————————————————————————

INSTALLATION PROCESS

1. Prerequisites for Deployment: Install MATLAB Runtime v.9.6 

Verify that version 9.6 (R2019a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2019a 
from the following link on the MathWorks website:

    http://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation in the MathWorks Documentation Center.

2. Download and run the ToulGaitViz.exe Installer with the file 'splash.png' in the same folder. Then, let you guide by the wizard. You need to specify the path of the installation folder and the path of the v96 MATLAB Runtime folder previously installed. The application is located in installation folder/application folder.

———————————————————————————————————————

USE OF THE TOULGAITVIZ APP

- The export folder path is required to run the app
- You have the ability to change: 
	- Laboratory system settings as the orientation axes, marker names, event names…
	- Laboratory norms and SD 
- Subject information, dates and context of the 3DGA are required to continue
- Then select the .c3d of the 3DGAs, as many times as number of 3DGAs you want to process. Be careful to import the .c3d files in the same order than dates and context of the 3DGA you’ve previously provided
- Select the options of visualization 
- Find the ToulGaitViz report in the export folder you have previously selected 

————————————————————————————————————————

Good use!
