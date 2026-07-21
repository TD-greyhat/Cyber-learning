-  What is a chipset?
   The chipset one or some controllerchip on the motherboard, that help
   the CPU-communicating  the other  hardwares, that has no direct contact with.

   The chipset is a traffic controller,
   that controlling the data between the CPU and the other hardwares.

-  Connetcions of the Chipset
	- SATA ports
	- USB ports
	- Voice controller
	- LAN
	- some PCIe lanes
	- BIOS/UEFI communications
	- other integrated controllers
	
-  Then and now
	- Back then, there were 2 different chip
	 CPU -> ([Northbridge] RAM, GPU) -> ([Southbridge] USB, SATA, Audio, LAN)
	 Northbridge handled the fast connections (RAM, GPU) and the Southbridge handled the slower ones.
	- Modern computers
	 a lots of tasks integrated to the CPU
	 ([CPU] RAM, GPU (PCIe)) -> ([Chipset] USB, SATA, Audio, Ethernet, Extra PCIe lanes)
	 This is why the system is faster.

-   The chipset determine what the motherboard is capeable of.
	- how many USB-port can be
	- how many M.2 SSD supported
	- how many SATA port there is
	- tuning is supported or not
	- how many PCi lanes are available
	- what kind of CPUs are compatible(beside the CPU slot)
	
- Why there is several type of chipset?
	Not every user need the same functions.
	- office machines
	- gamer PC
	- work station
	- server

-  Linux view
	The linux kernel, recognize the chipsets, then handling them with the suitable drivers(USB, SATA, networks stb...)

- Cybersecurity view
	- Handles many I/O- tools communications
	- Can have, firmware updates
	not that important target like the OS but there is some vulnerabilities.

- Important comment
		The chipset controlling and broadcasts the communications. 
		The OS, and the CPU is also part of what kind of operations is happening.