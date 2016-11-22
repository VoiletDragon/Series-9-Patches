# Series-9-Patches

Common patches for Series 9 Z97/H97 Motherboards. Only use with Clover Hotpatch.
Use acpi_dsdt_patches.plist to copy and paste patches to youre existing config. Dont mix DSDT with these SSDTs. Only use SSDT-IGPU if your using onboard IGPU. SSDT-XWAK to disable XWAK renamed to ZWAK.

Common sleep problems on Z97/H97 boards is caused by XWAK which causes random reboots after sleep due to related Kernel Panics so i fixed it by renaming XWAK to ZWAK. 

