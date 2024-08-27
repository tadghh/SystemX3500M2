# SystemX3500M2
Resources and other information

# Drivers - Firmware
Latest versions can be found [here](https://www.driversforlenovo.com/) this page bypasses lenovos stupid ftp download system


# ServeRaid BR10i
Latest BR10i firmware can be found [here](https://www.driversforlenovo.com/update-lenovo/critical-update-serveraid-br10i-sas-controller-bios-and-firmware-v2.75-for-microsoft-windows-ibm-system-x-drivers-update.html)

The installer will say "platform not supported" but its lying. Use 7zip to extract it, run the update yourself using sasflash. The recommended way of using sasflash is via MSDOS but thats.. just not very gaming. I updated in the following order. update bios -> update firmware. 

A PDF containing all the commands for sasflash can be found [here](https://github.com/tadghh/SystemX3500M2/blob/main/Manual-SASFlash-Quick-Ref-Guide_LSI_3041X-R_200811.pdf)  __you should read this, so you can make sure sasflash wont overwrite the incorrect device__

Also remember to install the latest [driver](https://support.lenovo.com/ca/en/downloads/ds019573-lsi-integrated-1068e-sas-controller-driver-microsoft-windows-small-business-server-2011-and-windows-server-2008-r2-64-bit)

Updating to the latest version allowed me to use ServeRAID BR10i with UEFI, Windows 10 LTSC 21H2. 
