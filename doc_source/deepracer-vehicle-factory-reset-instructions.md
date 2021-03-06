# Restore Your AWS DeepRacer Vehicle to Factory Settings<a name="deepracer-vehicle-factory-reset-instructions"></a>

Follow the instructions here to restore your AWS DeepRacer vehicle to its factory settings\. Make sure you have made proper preparations as described in [Prepare for Factory Reset to Your AWS DeepRacer Vehicle](deepracer-vehicle-factory-reset-preparation.md)\. 

**Note**  
 After the factory reset, all data stored on your AWS DeepRacer vehicle will be erased\. <a name="deepracer-vehicle-factory-reset-procedure"></a>

**To restore your AWS DeepRacer vehicle to its factory settings**

1.  Insert the prepared USB drive to your AWS DeepRacer compute module\. Turn on the power and repeatedly press the *ESC* key to enter BIOS\. 

1.  From the BIOS window, choose **Boot From File**, then **The option with USB in it**, then **EFI**, then **BOOT**, and finally **BOOTx64\.EFI**\. 

1.  After the compute module is booted, wait for the device reset to start automatically when the power LED indicator starts to flash and a terminal window is presented to display the progress\. You don't provide any further user input at this stage\. 

   If some error happens and the recovery fails, restart the procedure from **Step 1**\. For detailed error messages, see the *result\.log* file generated on the USB drive\. 

1.  Wait for about 6 minutes for the power LED to stop flashing when the terminal closes automatically and the factory reset completes\. The device then reboots itself automatically\. 

1.  After the device is restored to factory settings, disconnect the USB drive from the vehicle's compute module\. 

After the factory reset, your AWS DeepRacer vehicle software is likely outdated\. To update the vehicle software, go to the AWS DeepRacer device console and follow the instructions\.