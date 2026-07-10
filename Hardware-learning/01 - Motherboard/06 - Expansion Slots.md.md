-  What is expansion Slotsi? 
	Its a connector in the motherboard thats make it possible
	to expand the computer.

	back then there was some standards(ISA,PCI,AGP)
	nowadays there is mainly one: **PCI Express (PCIe)**

-  What is PCI Express?
	Its an high speed communication standard.

-  What we use for?
	PC-can connect to:
	- GPU
	- WI-FI Card
	- Network Card (NIC)
	- Capture Card
	- NVMe SSD (M.2 adapter or M.2 slot)
	- RAID control

- What is the PCIe lane?
	- Its a two way data connection. (like a road)
	- x1 x4 x8 x16 -> more lanes more data can flow
	- Physically it can be x16 but sometimes it works in x4 electricity. 

- Hardware needs
	GPU getting mainly x16 bcouse working with lot of data,
	but for the SSD enoug x4.

-  Where this lanes come from?
	- Many come from the CPU
	- Some from the chipset
	Thats why the direct connected PCIe slots to the CPU are
	generally faster than the others.

-  Linux perspectives
	To see the PCIe tools.
	
		- lspci
		
	This will list the,
	- GPU
	- Network Card
	- SATA controller
	- USB controller
	- Sound card
	and more PCIe tools.

- Cyber security perspectives
	A PCIe - tool
	- can have their own firmware
	- direct communicate with the system
	- some cases can have direct Memory access (DMA).
