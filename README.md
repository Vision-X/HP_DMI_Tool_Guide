# HP_DMI_Tool_Guide 
(run **AFTER** replacing HP hardware)


## Booting & Using the DMI tool


1) Plug the Bootable USB into an open port and Power on the machine. Quickly press "F9" to enter boot menu (alternatively, you can use "F12" to enter BIOS Select menu and then choose boot menu in the list)

2) Select Bootable USB image (HP DMI / Branding tool)

3) Allow shell script to run and it will bring you to an options screen. Select 'Configure DMI'.

4) Follow guided steps in the DMI tool. 

  - If data is not auto-populating in the forms then you will need to look up the serial number on [partsurfer.hp.com](https://partsurfer.hp.com/partsurfer?searchby=swp)

  - Use the 'Advanced' tab after searching the serial number to locate the required info (use CTRL + F to search the page for the value)
  
  - For Prod ID, please note it is case sensitive AND will require both IMG_Desc1 and IMG_Desc2 to be entered (with no space in between) as one string
  
5) Complete DMI update (following the steps) and it will reboot into the DMI tool.

6) Commit the updated TPM data and it will reboot into the DMI tool.

7) Finally, Lock the TPM.

8) Wizard should be complete.

9) Shut down PC, remove the bootable USB drive / DMI tool, and restart the computer.

10) All HP pre-BIOS errors/countdowns/lockouts should now be resolved.
