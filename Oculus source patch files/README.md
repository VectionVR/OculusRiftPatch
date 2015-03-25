*Patch files for Oculus sources*

- Download LibOVR sources from https://developer.oculusvr.com/
- Download the patch corresponding to your OculusVR library version
- Enter the **Src** folder
- Apply the patch using *patch p1 < [patch_file]* on UNIX, Linux or OSX or using the unified patch functionality of TortoiseDiff **1.6.7** on windows. You can download it at http://sourceforge.net/projects/tortoisesvn/files/Tools/1.6.7/TortoiseDiff-1.6.7.zip/download 
- After the patch is applied, two new files are created in the LibOVR/Src/Service folder. Those two files must be added manually to your project :
  - Service_VVRNetClient.cpp 
  - Service_VVRNetClient.h 

###### *Vection VR is in no way affiliated with Oculus VR inc.* ######

