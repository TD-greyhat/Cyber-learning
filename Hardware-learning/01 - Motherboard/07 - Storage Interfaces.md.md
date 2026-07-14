-  Storage interfaces:
	Its the mod how storage devices communicationg with the computer.
	Most populars:
		- SATA
		- PCIe (NVMe protokoll)

-  SATA (Serial ATA)
	- HDD
	- 2.5"SSD"
	-  some M.2 SSD
	SSD -> SATA cable -> Motherboard SATA port
	- How the back storage should communicate
	- What commands using
	- Loading speed

-  M.2
	Its a physical connection format, like the DIMM or RAM modules.
	Types:
	-  M.2 SATA SSD: M.2 -> SATA protokoll
	-  M.2 NVMe SSD: M.2 -> PCIe (NVMe protokoll)

-  What is NVMe?
	The NVMe (NON-Volatile Memory Express) its a modern communication protokoll.
	Made specifically for SSD-s.
	Its works on PCIe lanes.

-  Why NVMe is faster?
	-  SATA SSD -> SATA -> Chipset -> CPU
	- NVMe SSD -> PCIe x4 -> CPU 

-  M.2 keys
	M.2 slots has notches
		- B - key
		- M - key
		- B+M key

-  Linux view
	commands:
	
		- lsblk
		- sudo fdisk -l

	 The NVMe tools look like this:
	 /dev/nvme0n1
	 While The SATA:
	 /dev/sda

- Cybersecurity view
	- OS is here
	- User datas
	- Here we can encrypt the disk (ex: LUKS under Linux)
