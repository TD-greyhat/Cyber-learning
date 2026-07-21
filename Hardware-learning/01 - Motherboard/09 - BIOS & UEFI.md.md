-  What is BIOS?
		**Basic Input/Output system**
	This is a firmware that is in one of the motherboard chips.
	- Main tasks is to start the computer
	- Check the hardwares
	- Give away the controll to the bootloader

-  What is UEFI?
	Modern computers mainly use UEFI (Unified Extensible Firmware Interface) 
	instead of BIOS becouse its an older software.
	
-  BIOS/UEFI is on a **flash memory chip** that is on the motherboard.
		thats why its updateable.

-  What is happening at the start?
	-  The CPU start
		but the CPU dont know yet
		- Where is the Linux
		- Where is the OS
		- Where is the SSD
		- How many RAMs there
		thats why the CPU starts from a premade link 
		where the firmware located.

	-  The BIOS/UEFI:
		- Initialize the hardwares
		- Start the **POST**
		- Locate the bootable device
		- Give the control to the bootloader

-  What is a POST?
	POST = **Power-On Self-Test**
	this is an hardware checking. 

-  Boot Order
	The BIOS/UEFI knows whats the checking order for the starable devices.

-  What is the Secure Boot?
	The secure boot reason is to make sure,
	 only the digitally signed bootloader and OS can start.
	 (harder to take control with a bad loader)

-  BIOS update
	Why?
	- New CPU support
	- Error handling
	- Security handling
	- Stability updates
	If the BIOS update break, it can be that the motherboard
	does not start. A lot of modern motherboard have repair solutions,
	forex: BIos Flashback or Dual BIOS but not all.

-  Linux view
	For Linux is important that:
	- UEFI of Legacy BIOS mod has been started?
	- What ACPI informations did the firmware give away?
	- What kind of hardware has been initialized?
	Commands:

		- dmesg
		- efibootmr
	- ls /sys/firmware/efi