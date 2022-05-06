*********
/var/mrh/
*********
/var/mrh/ contains support files used by the MRH platform. Some of these 
files might be created or changed, while others remain static. 

/var/mrh/mrhcore/
-----------------
This directory contains the launch trigger files for mrhcore to recognize 
a user requested application stop.

The structure of this directory follows the required structure for a multi-
language launch trigger, using the locale code for the individual languages 
as well as a "Default" directory as a fallback.

/var/mrh/mrhpsapp/
------------------
The mrhpsapp directory is used by the mrhpsapp platform service to store 
information about currently planned timed launches.

/var/mrh/mrhpsuser/
-------------------
The mrhpsuser directory is used as the default MRH user directory by the mrhpsuser 
platform service. Included are all files and folders used by the service to allow 
user applications to access and store user files.

/var/mrh/mrhuapp/
-----------------
Contained inside the mrhuapp directory is the launch input storage text file which 
allows multiple sentences to be used for launch input. This file is then read by 
mrhuapp to read the user application launch input.